# SWOT Observations of the Mode-1 M2 Internal Tide in the Southern Ocean

[![DOI](https://img.shields.io/badge/Preprint-ESSOAr-blue)](https://doi.org/10.22541/essoar.177038605.57238714/v1)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18292089.svg)](https://doi.org/10.5281/zenodo.18292089)

## Overview

We map coherent mode-1 M2 internal tides across the Southern Ocean using SWOT satellite observations from the Calibration/Validation phase (March–July 2023). Internal tide amplitudes, phases, and propagation directions are extracted using two-dimensional plane-wave fitting applied to 102 cycles of SWOT Level-3 sea surface height anomaly data.

- **New detections** in eddying regions (Drake Passage, Southwest Indian Ridge) where conventional nadir altimetry has limited sensitivity.
- **Beam attenuation** across Antarctic Circumpolar Current fronts, with phase curvature consistent with mesoscale refraction.
- **Good agreement** with the 25-year HRET model, with SWOT resolving systematically more energetic signals.
- **Depth-integrated energy and flux** estimated through modal structure functions from climatological stratification.

## Paper

> Li, Y., Mazloff, M. R., & Gille, S. T. (2026). SWOT observations of the mode-1 M2 internal tide in the Southern Ocean. *Journal of Geophysical Research: Oceans*. In review. [doi:10.22541/essoar.177038605.57238714/v1](https://doi.org/10.22541/essoar.177038605.57238714/v1)

## Data

> Li, Y., Mazloff, M. R., & Gille, S. T. (2025). SWOT Observations of the Mode-1 M2 Internal Tides in the Southern Ocean [Dataset]. Zenodo. [doi:10.5281/zenodo.18292089](https://doi.org/10.5281/zenodo.18292089)

## Notebooks

| Notebook | Description |
|----------|-------------|
| `open_research_public_light.ipynb` | Reproduces all figures in the paper using the Zenodo dataset |

## Dependencies

Python ≥ 3.9, xarray, numpy, scipy, matplotlib, cartopy, cmocean

## Related Repository

- [**plane-wave-fit**](https://github.com/youranli001/plane-wave-fit) — Python package for two-dimensional plane-wave fitting of internal gravity waves, used in this study
