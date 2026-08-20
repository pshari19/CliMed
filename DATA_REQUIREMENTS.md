# Data requirements

## Required for Run 1–3

1. Climate input containing temperature and precipitation plus either relative humidity, dew point, or specific humidity with a compatible pressure field.
2. AOI boundary shapefile.
3. LULC GeoTIFF for Run 3.
4. Population density supplied by the user as either a GeoTIFF or a numeric density value.

## Pressure handling

The automatic detector accepts common pressure variables including `ps`, `sp`, `psfc` and `psl`. In the bundled example, `psl` (mean sea-level pressure) is used as the pressure input for the existing specific-humidity-to-RH calculation. The software labels this as a pressure input/MSLP proxy rather than misidentifying it as surface pressure.

## Bundled test data

- Two generic climate example sets: `reference/` and `projection/`.
- India Admin2 boundary shapefile.
- India LULC GeoTIFF.

The generic filenames do not imply that CliMed computes or selects a particular SSP. Scenario selection, preprocessing and suitability of climate forcing remain the user's responsibility. Original source filenames/provenance are recorded in `DATA_PROVENANCE.md`.

## User-supplied data

The public package does **not** bundle:

- population-density data;
- VIIRS/night-light data;
- Aedes aegypti occurrence/suitability data;
- Aedes albopictus occurrence/suitability data;
- dengue case observations;
- DENV serotype occurrence data.

Optional occurrence and VIIRS inputs are neutral when left blank and can be supplied by the user through the normal Run 1–3 interface.
