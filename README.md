# Data Science Job‑Market Analysis Project

This repository hosts a collaborative project to analyze the data‑science job market in the United States.  Our goals are to understand which data‑science roles are in demand, how they are defined, and what skills employers look for.  The project is organized and maintained by volunteer students in the BU Master’s in Data Science program with guidance from instructors.

## Goals

1. **Data collection** – gather public job‑posting data from sources such as LinkedIn, Indeed, Glassdoor and the U.S. Bureau of Labor Statistics.  Store raw data in the `data/raw` folder.
2. **Role taxonomy** – define common data‑science roles (e.g. data analyst, data scientist, machine‑learning engineer).  Document official definitions and typical responsibilities.
3. **Skill extraction** – identify and count the technical and non‑technical skills required for each role using natural‑language processing and manual annotation.
4. **Analysis & visualization** – analyze demand over time, geography and industry; visualize skill frequency and job distribution; publish notebooks and figures in `notebooks/` and `reports/`.
5. **Reporting** – summarize findings in a final report and prepare presentations for the class.

## Repository structure

The project follows a standardized structure inspired by the [cookiecutter‑data‑science template](https://github.com/drivendataorg/cookiecutter-data-science):

```
.
├── data/               # Data storage
│   ├── raw/            # Original, unprocessed job‑posting data
│   ├── interim/        # Intermediate cleaned data
│   └── processed/      # Final datasets ready for analysis
├── notebooks/          # Jupyter notebooks (exploration, analysis, visualization)
├── src/                # Source code for data collection, cleaning, feature extraction and analysis
├── reports/            # Analysis reports and figures
│   └── figures/        # Generated graphics
├── docs/               # Optional project documentation site
├── requirements.txt    # Python dependencies
├── CONTRIBUTING.md     # Guidelines for contributing
├── CODE_OF_CONDUCT.md  # Community standards
└── .github/
    ├── ISSUE_TEMPLATE/ # Issue templates (task, research, bug)
    └── PULL_REQUEST_TEMPLATE.md
```

## Getting started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/data-science-job-market-analysis.git
   cd data-science-job-market-analysis
   ```
2. **Create a virtual environment** and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Run notebooks**: start JupyterLab or Jupyter Notebook and explore the notebooks in the `notebooks/` directory.  Each notebook is prefixed with a number for ordering and includes the author’s initials and a short description.

## How to participate

We welcome contributions from all volunteers.  Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidelines on how to propose issues, work on tasks, submit pull requests and follow coding standards.  You’ll also find information about our labeling system, project board and milestones.

If you are new to the project, check the project board for “good first issue” labels or reach out to a mentor in the Slack channel.  We encourage everyone to document their work and ask questions — there are no dumb questions!

## License

This project is released under the MIT License.  See the [LICENSE](LICENSE) file for details.
