# Bundled public test data

This directory contains only the approved inputs needed to make a basic CliMed Runs 1–3 test reproducible:

- `example_climate/reference/`: temperature, precipitation, specific humidity and MSL pressure inputs.
- `example_climate/projection/`: temperature, precipitation, specific humidity and MSL pressure inputs.
- `example_spatial/Admin2/`: India Admin2 shapefile components.
- `example_spatial/India_LULC.tif`: India LULC example.

Population, VIIRS, Aedes occurrence/suitability, dengue-case and DENV-serotype datasets are intentionally not bundled. Users provide those inputs themselves when required.

The climate filenames are deliberately generic. They are test inputs, not a built-in scenario selector. See `../DATA_PROVENANCE.md` for the original source filenames and metadata notes.
