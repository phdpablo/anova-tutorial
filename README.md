<<<<<<< HEAD
# Applying ANOVA in Crossover Trials (In Development)
=======
# Applying ANOVA in Crossover Trials

[![Deploy ARTE Template](https://github.com/phdpablo/anova-tutorial/actions/workflows/deploy.yml/badge.svg)](https://github.com/phdpablo/anova-tutorial/actions/workflows/deploy.yml)
[![DOI](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F3RXF2-blue)](https://doi.org/10.17605/OSF.IO/3RXF2)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
>>>>>>> 9e6d121701155fcc7f041cff37e7d6b5ef6a8608

Repository for a dynamic, reproducible tutorial article on crossover ANOVA in randomized clinical trials related to physiotherapy and rehabilitation, written in the R language (RStudio + Quarto)

<<<<<<< HEAD
# How cite this project?

Georgeto, S. M., & Rogers, P. (2024). Applying ANOVA in Crossover Trials. https://doi.org/10.17605/OSF.IO/3RXF2
=======
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
├── project/                    # Main project folder (TIER Protocol 4.0)
│   ├── Data/                   # Data files (Input, Analysis, Intermediate)
│   ├── Scripts/                # R scripts for data processing and analysis
│   ├── Output/                 # Generated results, figures, and tables
│   ├── *.qmd                   # Quarto source files for the tutorial
│   └── README.md               # Project documentation
├── docs/                       # Rendered website (HTML output)
├── .github/workflows/          # GitHub Actions for CI/CD
├── Dockerfile                  # Container definition for reproducibility
├── renv/                       # R package management (renv)
├── _quarto.yml                 # Quarto configuration
├── references.bib              # Bibliography in BibTeX format
├── apa7ed.csl                  # Citation style (APA 7th edition)
└── README.md                   # This file
```

## Getting Started

### Prerequisites

- [R](https://cran.r-project.org/) (≥ 4.5.0)
- [RStudio](https://posit.co/download/rstudio-desktop/) (recommended)
- [Quarto](https://quarto.org/docs/get-started/) (≥ 1.3)
- [Docker](https://www.docker.com/) (optional, for containerized reproducibility)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/phdpablo/anova-tutorial.git
   cd anova-tutorial
   ```

2. **Restore R package environment:**
   ```r
   # In R console
   renv::restore()
   ```

3. **Render the tutorial:**
   ```bash
   quarto render
   ```

### Using Docker (Recommended for Full Reproducibility)

```bash
# Build the Docker image
docker build -t anova-tutorial .

# Run the container
docker run -p 8787:8787 anova-tutorial

# Access RStudio Server at http://localhost:8787
```

## Usage

### Viewing the Tutorial

The rendered tutorial is available online at: [https://phdpablo.github.io/anova-tutorial/](https://phdpablo.github.io/anova-tutorial/)

### Running Analyses Locally

1. Open the R project in RStudio: `anova-tutorial.Rproj`
2. Navigate to the `project/` folder
3. Open any `.qmd` file to view/edit tutorial content
4. Run code chunks interactively or render the entire document

### Modifying Content

- **Tutorial Content:** Edit `.qmd` files in the root and `project/` directories
- **Data Processing:** Modify scripts in `project/Scripts/`
- **Configuration:** Adjust settings in `_quarto.yml`
- **References:** Add citations to `references.bib`

## Methodology

This project follows the [TIER Protocol 4.0](https://www.projecttier.org/tier-protocol/protocol-4-0/) for organizing reproducible research and adopts open science principles as outlined in:

- Limongi, R., & Rogers, P. (2025). Open Science in Three Acts: Foundations, Practice, and Implementation. *BAR - Brazilian Administration Review*, 22(1-3).

## Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

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

- **Article Template (ARTE):** [https://phdpablo.github.io/article-template/](https://phdpablo.github.io/article-template/)
- **GEE in Crossover Studies:** [https://doi.org/10.17605/OSF.IO/MU67G](https://doi.org/10.17605/OSF.IO/MU67G)

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
>>>>>>> 9e6d121701155fcc7f041cff37e7d6b5ef6a8608
