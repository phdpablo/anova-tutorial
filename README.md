# Applying ANOVA in Crossover Trials

[![Deploy ARTE Template](https://github.com/phdpablo/anova-tutorial/actions/workflows/deploy.yml/badge.svg)](https://github.com/phdpablo/anova-tutorial/actions/workflows/deploy.yml)
[![DOI](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F3RXF2-blue)](https://doi.org/10.17605/OSF.IO/3RXF2)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains a **dynamic and reproducible tutorial** on applying Analysis of Variance (ANOVA) in crossover trials within the context of randomized clinical trials related to physiotherapy and rehabilitation. The tutorial is implemented as an interactive document using R, RStudio, and Quarto, following open science principles and best practices for reproducible research.

**📖 Live Tutorial:** [https://phdpablo.github.io/anova-tutorial/](https://phdpablo.github.io/anova-tutorial/)

## Project Goals

- Conduct comprehensive research on ANOVA methods for crossover designs in clinical trials
- Provide a hands-on, reproducible tutorial for analyzing crossover data
- Demonstrate best practices for transparent and reproducible research in R
- Offer practical examples relevant to physiotherapy and rehabilitation research

## Features

- **Fully Reproducible:** All analyses can be reproduced using provided data, scripts, and computational environment
- **Dynamic Document:** Interactive tutorial built with Quarto that combines narrative, code, and results
- **Containerized Environment:** Docker support ensures computational reproducibility across platforms
- **Open Science Compliant:** Follows FAIR principles and open science practices
- **Version Controlled:** Complete project history available through Git
- **Automated Deployment:** GitHub Actions workflow for continuous deployment

## Repository Structure

```
anova-tutorial/
├── main/                       # Main branch project folder
│   ├── Data/                   # Data files (Input, Analysis, Intermediate)
│   ├── Scripts/                # R scripts for data processing and analysis
│   ├── Output/                 # Generated results, figures, and tables
|   ├── renv/                   # R package management (renv)
|   ├── docker/                 # Container definition for reproducibility
|   ├── .github/workflows/      # GitHub Actions for CI/CD
|   ├── .binder/                # Binder configuration for cloud execution
│   ├── *.qmd                   # Quarto source files for the tutorial
|   ├── _quarto.yml             # Quarto configuration
|   ├── references.bib          # Bibliography in BibTeX format
|   ├── apa7ed.csl              # Citation style (APA 7th edition)
|   └── README.md               # This file
├── gh-pages/                   # Github Pages branch for rendered project
|   └── docs/                   # Rendered website structure (HTML output)
```

## Getting Started

### Prerequisites

- [R](https://cran.r-project.org/) (4.5.1)
- [RStudio](https://posit.co/download/rstudio-desktop/) (2025.05.1+513)
- [Quarto](https://quarto.org/docs/get-started/) (1.6.42)
- [Docker](https://www.docker.com/) (optional, for containerized reproducibility)

## Usage

See more instructions in the [ARTE Repository Template](https://github.com/phdpablo/article-template)

### Viewing the Dynamic Article

The rendered tutorial is available online at: [https://phdpablo.github.io/anova-tutorial/](https://phdpablo.github.io/anova-tutorial/)

## Methodology

This project follows the [ARTE Template](https://github.com/phdpablo/article-template) for organizing reproducible research and adopts open science principles as outlined in:

- Rogers, P., & Limongi, R. (2025). Open Science in Three Acts: Foundations, Practice, and Implementation - Third Act. *BAR - Brazilian Administration Review*, *22*(3),e250162. <https://doi.org/10.1590/1807-7692bar2025250162>
- Limongi, R., & Rogers, P. (2025). Open Science in Three Acts: Foundations, Practice, and Implementation - Second Act. *BAR - Brazilian Administration Review*, *22*(2), e250116. <https://doi.org/10.1590/1807-7692bar2025250116>
- Limongi, R., & Rogers, P. (2025). Open Science in Three Acts: Foundations, Practice, and Implementation - First Act. *BAR - Brazilian Administration Review*, *22*(1), e250079. <https://doi.org/10.1590/1807-7692bar2025250079>


## Citation

If you use this tutorial in your research or teaching, please cite:

```bibtex
@article{georgeto2024a,
  title = {Applying ANOVA in Crossover Trials},
  author = {Georgeto, Sérgio Murilo and Rogers, Pablo},
  year = {2024},
  publisher = {OSF},
  doi = {10.17605/OSF.IO/3RXF2},
  url = {https://osf.io/3rxf2/}
}
```

**APA Format:**  
Georgeto, S. M., & Rogers, P. (2024). *Applying ANOVA in Crossover Trials*. OSF. https://doi.org/10.17605/OSF.IO/3RXF2

## Related Projects

- **GEE in Crossover Studies:** [https://doi.org/10.17605/OSF.IO/MU67G](https://doi.org/10.17605/OSF.IO/MU67G)
- **Quantitative Methods in Crossover Studies:**
[https://doi.org/10.17605/OSF.IO/Q2MGK](https://doi.org/10.17605/10.17605/OSF.IO/Q2MGK)
- **Article Template (ARTE):** [https://phdpablo.github.io/article-template/](https://phdpablo.github.io/article-template/)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## Authors

- **Sérgio Murilo Georgeto** - *Principal Investigator*
- **Pablo Rogers** - *Co-Investigator* - [Website](https://www.phdpablo.com)

## Acknowledgments

- Built with [Quarto](https://quarto.org/)
- Follows the [TIER Protocol](https://www.projecttier.org/) for reproducible research
- Inspired by open science principles and practices
- Template based on [ARTE](https://github.com/phdpablo/article-template)

## Contact

For questions or feedback, please [open an issue](https://github.com/phdpablo/anova-tutorial/issues) or contact the authors through the [OSF project page](https://osf.io/3rxf2/).

---

**Status:** 🚧 In Development

**Last Updated:** January 2026
