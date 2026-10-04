# Sea Level to Space

An interactive altitude explorer. Drag from the ground to 1,000 km and watch the air thin out, the gas mix change, gravity ease off, and see how Earth's spin compares with orbital speed. Built to answer common flat-earth objections about the atmosphere with numbers anyone can test.

## What is on the page

- **Altitude column**: the five layers (troposphere to exosphere) with tappable landmarks such as Everest, airliner cruise, the Kármán line and the space station.
- **Live readouts**: pressure, density, temperature, particles per cubic centimetre, mean free path, boiling point of water, gas composition, gravity, orbital and escape speed, and spin speed at a chosen latitude.
- **Three charts**: pressure against altitude, gravity against distance (space station, GPS, geostationary, Moon), and gas composition from sea level to 1,000 km.
- **Check it yourself**: six tests, split into checks on the air column and checks that tell a spinning globe from a flat plane.
- **Common objections**: ten short answers with numbers.
- US and metric units.

## Model and sources

- Atmosphere: U.S. Standard Atmosphere, 1976. Layer equations below 86 km; table interpolation (temperature, pressure, density and species number densities) from 86 to 1,000 km. It describes average mid-latitude, mid-solar-cycle conditions.
- Gravity and spin: WGS 84 constants, with a 6,371 km mean radius for gravity and orbits.
- Water boiling point: Antoine equation, valid down to the triple point.

The model was checked against published Standard Atmosphere tables (within 0.1% at table altitudes) and the page text was reviewed for physics errors before publishing.

## Files

- `index.html`: the whole site. One self-contained file, no build step. Fonts load from Google Fonts.

## Deploy

Static site. On Vercel: import this repository, framework preset "Other", no build command, output directory `/`.
