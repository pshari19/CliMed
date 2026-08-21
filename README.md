# CliMed
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22037325.svg)](https://doi.org/10.5281/zenodo.22037325)
## Download CliMed

### Windows — Recommended

[**Download CliMed v1.0.0 Complete Public Package (ZIP)**](https://github.com/pshari19/CliMed/releases/download/v1.0.0/CliMed_v1.0.0_Complete_Public_Package.zip)

This package contains the CliMed Windows application, signed runtime licence, public configuration, documentation and example test data.

1. Download and extract the ZIP.
2. Keep the supplied application, `license.lic` and `run_config_public.json` together.
3. Start `CliMed_v1.0.0_Windows_x64.exe`.

> **Note:** GitHub's **Code → Download ZIP** downloads the repository files only. For the ready-to-run Windows software and example data, use the **Complete Public Package** above.
**CliMed** is a climate-informed mechanistic modelling framework for Aedes-borne dengue-risk analysis. This public repository is limited to the **Runs 1–3 release** and provides public documentation, test data and release information. The proprietary implementation is distributed only in compiled form.

## Public release scope
The Runs 1–3 release supports:

- climate-input preparation and automatic variable/coordinate detection;
- common-grid preparation and area-of-interest masking;
- mechanistic Aedes transmission calculations;
- *Aedes aegypti*, *Aedes albopictus* and weighted combined-species modes;
- model-derived outputs including EIR, force of infection, infection probability, vector-to-host ratio and infectious-vector fraction;
- user-selected LULC and population inputs;
- optional user-supplied VIIRS/night-light and Aedes occurrence/suitability rasters.

The bundled climate, administrative-boundary and LULC files are provided only as reproducible software-test inputs. Population, VIIRS, Aedes occurrence/suitability and dengue-case datasets are not bundled.

## Windows application

The Windows executable is distributed through **GitHub Releases**. Source implementation files are intentionally not published in this repository.

See `INSTALLATION.md` for the release layout and use instructions.

## Scientific interpretation

CliMed outputs are mechanistic/model-derived estimates. They are not official dengue surveillance counts, confirmed infections, clinical diagnoses or medical advice. Interpretation depends on the quality, resolution and suitability of user-supplied inputs and model assumptions. See `DISCLAIMER.md`.

## Development status

This public repository is restricted to Runs 1–3. Additional development functionality is not distributed here. Severity/recovery and DENV-serotype-specific functionality remain in development and are not part of this public release.

## Copyright and licence

CliMed software work diary no. **SW-15346/2026-CO** and literary/dramatic work diary no. **LD-15328/2026-CO**. See `COPYRIGHT.md` and `LICENSE_NOTICE.md`.

The supplied application runtime licence is cryptographically signed and valid through **31 December 2030 UTC**. This runtime licence is separate from repository reuse rights.

## Citation

If you use CliMed in research, publications, reports or presentations, please cite:

**Peri, Subrahmanya Hari Prasad & Satyanarayana, A. N. V. (2026).  
CliMed: Climate-Informed Mechanistic Modelling Framework for Dengue Risk (Version 1.0.0). Zenodo.  
https://doi.org/10.5281/zenodo.22037325**

Citation metadata are also available in `CITATION.cff`.
