# CyanoBioActiveDB

> A curated machine learning-driven database of bioactive compounds derived from cyanobacteria, designed as a resource for therapeutics and bioremediation research.

[![DOI](https://img.shields.io/badge/DOI-10.1021%2Facs.jcim.4c00995-blue)](https://doi.org/10.1021/acs.jcim.4c00995)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![FAIR](https://img.shields.io/badge/FAIR-Principles-green)](https://www.go-fair.org/fair-principles/)

---

## Overview

Cyanobacteria are among the most prolific natural producers of structurally diverse bioactive metabolites, with broad applications in drug discovery and bioremediation. **CyanoBioActiveDB** aggregates, standardizes, and curates data on these compounds from multiple public repositories and peer-reviewed literature, providing a unified and reproducible resource for the scientific community.

This repository contains all materials supporting the publication *Machine Learning-Driven Discovery and Database of Cyanobacteria Bioactive Compounds: A Resource for Therapeutics and Bioremediation* (J. Chem. Inf. Model., 2024), including the main databases, machine learning datasets, Orange workflows, and Python scripts.

| Metric | Value |
|---|---|
| Bioactive compounds | **3,431** |
| Unique protein targets | **373** |
| Molecular descriptors | **3,027** |
| Data sources | CyanoMet_DB · NPAtlas_DB · PubChem · ChEMBL |

---

## Repository Structure

```text
cyanobioactivedb/
│
├── Main databases/                           # Core curated compound datasets
├── ML databases with no oversampling/        # ML-ready datasets (no oversampling)
├── Orange Machine learning workflows/        # Orange Data Mining .ows workflow files
├── Python Scripts/                           # General data processing scripts
├── Python scripts used for Machine learning/ # ML training and evaluation scripts
├── TOP 25 Descriptors/                       # Top-ranked molecular descriptor subsets
│
├── LICENSE
└── README.md
```

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/joaomiguelsov/cyanobioactivedb.git
cd cyanobioactivedb
```

Navigate to the relevant folder:

- **`Main databases/`** — core compound data files for exploration and analysis
- **`ML databases with no oversampling/`** — balanced ML-ready datasets
- **`Orange Machine learning workflows/`** — open `.ows` files in Orange Data Mining for interactive model training and evaluation
- **`Python Scripts/`** and **`Python scripts used for Machine learning/`** — reproducible pipelines for descriptor calculation, data processing, and model building
- **`TOP 25 Descriptors/`** — feature-reduced descriptor files for efficient modelling

---

## Citation

If you use CyanoBioActiveDB or any associated materials in your research, please cite the following publication:

> Soares R., Azevedo L., Vasconcelos V., Pratas D., Sousa S.F., Carneiro J. (2024). *Machine Learning-Driven Discovery and Database of Cyanobacteria Bioactive Compounds: A Resource for Therapeutics and Bioremediation*. **J. Chem. Inf. Model.**, 64(24), 9576–9593. https://doi.org/10.1021/acs.jcim.4c00995

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions, issues, or contributions, please open a [GitHub Issue](https://github.com/joaomiguelsov/cyanobioactivedb/issues) or contact the repository maintainer at [@joaomiguelsov](https://github.com/joaomiguelsov).
````

This version balances:
- **GitHub-style** — badges, clean headers, quick-start block, emoji anchors
- **Academic style** — formal language, full citation with journal volume/page, compound statistics table, and FAIR reference

Feel free to ask if you'd like to adjust badge colors, add a changelog, or include a funding acknowledgement section.
