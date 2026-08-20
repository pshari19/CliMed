# Bundled test-data provenance

The bundled data were supplied by the project maintainer for public software testing. Renaming in this package is only for portability and a neutral user-facing layout; file contents were not rewritten during packaging.

## Climate example — reference

- `data/example_climate/reference/temperature.nc`  
  Original file: `tas_day_MPI-ESM1-2-LR_ssp126_r1i1p1f1_gn_20150101-20241231.nc`
- `data/example_climate/reference/precipitation.nc`  
  Original file: `pr_day_MPI-ESM1-2-LR_ssp126_r1i1p1f1_gn_20150101-20241231.nc`
- `data/example_climate/reference/specific_humidity.nc`  
  Original file: `huss_day_MPI-ESM1-2-LR_ssp126_r1i1p1f1_gn_20150101-20241231.nc`
- `data/example_climate/reference/pressure_msl.nc`  
  Original file: `psl_day_MPI-ESM1-2-LR_ssp126_r1i1p1f1_gn_20150101-20241231.nc`

## Climate example — projection

- `data/example_climate/projection/temperature.nc`  
  Original file: `tas_day_MPI-ESM1-2-LR_ssp245_r1i1p1f1_gn_20240101-20301231.nc`
- `data/example_climate/projection/precipitation.nc`  
  Original file: `pr_day_MPI-ESM1-2-LR_ssp245_r1i1p1f1_gn_20240101-20301231.nc`
- `data/example_climate/projection/specific_humidity.nc`  
  Original file: `huss_day_MPI-ESM1-2-LR_ssp245_r1i1p1f1_gn_20240101-20301231.nc`
- `data/example_climate/projection/pressure_msl.nc`  
  Original file: `psl_day_MPI-ESM1-2-LR_ssp245_r1i1p1f1_gn_20240101-20301231.nc`

The public UI does not provide an SSP selector. Users are responsible for climate-scenario choice and preprocessing for their own analyses.

## Spatial example

- `data/example_spatial/India_LULC.tif`  
  Original file: `Ind_LULC(1).tif`; CRS EPSG:4326.
- `data/example_spatial/Admin2/India_Admin2.*`  
  Original files: `Admin2(1).*`; CRS EPSG:4326.

## Excluded supplied files

The supplied `aegypti-base.tif` and `albopictus-base.tif` occurrence/suitability rasters are intentionally **not** bundled because public users are expected to prepare/select their own occurrence inputs.
