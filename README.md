# ROBIGUS

Reproducible Object-Based Image-Guided Uredinia Scoring

ROBIGUS is a Fiji/ImageJ macro package for semi-automated quantification of wheat rust disease from digital images.

## Contents

- `macros/` – calibration and quantification macros
- `example_data/` – example images for testing the workflow
- `help_images/` – instructional images used by the calibration macro
- `docs/` – user guide
- `validation/` – scripts used for validation analyses reported in Mann et al. (2026)

## Requirements

- Fiji/ImageJ v. 1.54

## Quick start

1. Run `ROBIGUS_Calibration_v1.0.0.ijm`
2. Calibrate detection parameters using representative images
3. Save the calibration profile
4. Run `ROBIGUS_Quantification_v1.0.0.ijm`
5. Load the calibration profile and quantify the dataset

## Citation

Mann et al. (2026). [paper details when available]

## Version

v1.0.0
