# JMA XML Animator v1.0.0

**JMA XML Animator** is a Python add-on for Blender developed for the import, reconstruction, visualisation, and frame-level analysis of mandibular kinematic XML exports from Zebris JMA and Medit i700 workflows.

The add-on was developed as part of the pilot methodological study:

**Comparative Analysis of Mandibular Kinematics Recorded with Zebris JMA and Medit i700 Using an Open-Source 3D Model-Based Framework**

## Purpose

The add-on supports:

- XML import from jaw-motion recording workflows
- SVD-based rigid-body mandibular motion reconstruction
- Blender timeline animation of mandibular movement
- threshold-based frame selection
- displacement magnitude and directional component analysis
- occlusal contact-area computation within a shared 3D environment

## Software Environment

The add-on was developed for the manuscript workflow using:

- Blender 4.5 LTS
- Blender4Dental 1.1.99
- Python bundled with Blender
- NumPy

The add-on metadata specifies Blender 3.0.0 as the minimum Blender version, but the manuscript workflow was developed and tested in Blender 4.5 LTS. Additional software version details are provided in [`docs/software_versions.md`](docs/software_versions.md).

## Repository Contents

- [`src/jma_xml_animator.py`](src/jma_xml_animator.py) — main Blender Python add-on
- [`docs/installation.md`](docs/installation.md) — installation instructions
- [`docs/usage.md`](docs/usage.md) — basic usage instructions
- [`docs/software_versions.md`](docs/software_versions.md) — software version requirements
- [`docs/limitations.md`](docs/limitations.md) — methodological and clinical limitations
- [`SUPPLEMENTARY_CODE_S1.md`](SUPPLEMENTARY_CODE_S1.md) — repository information for supplementary submission

## Data Availability and Privacy

This repository does **not** include raw patient datasets, STL/OBJ/PLY models, XML kinematic recordings, screenshots containing patient data, or example workflow files derived from clinical cases. These data are not publicly available due to privacy and ethical restrictions.

## Intended Use

This software is provided for research and methodological validation purposes. It is **not** intended as a standalone clinical decision-support system and should not be used as the sole basis for diagnosis, treatment planning, prosthodontic design, or occlusal adjustment.

## License

This project is released under the MIT License. See the [`LICENSE`](LICENSE) file for details.

## Citation

If you use this software, please cite the associated manuscript when available and the repository citation metadata in [`CITATION.cff`](CITATION.cff).

Repository URL: https://github.com/radusmaximus/JMA-XML-Animator
