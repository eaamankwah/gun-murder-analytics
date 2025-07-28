# Gun Murder Analytics

## Overview

This project provides a comprehensive analysis of US gun murder data collected by the FBI. The analysis implements a complete data science workflow from data acquisition through visualization, demonstrating proficiency in data wrangling, statistical analysis, and reproducible research practices.

## Project Structure

```
Gun-Murder-Analytics/
├── data/                   # Raw data files
├── rda/                    # Processed R data objects
├── figs/                   # Generated visualizations
├── murders/                # Additional analysis files
├── download-data.R         # Data acquisition script
├── wrangle-data.R          # Data preprocessing and cleaning
├── analysis.R              # Statistical analysis and visualization
├── report.Rmd              # R Markdown report source
├── report.html             # HTML report output
├── report.pdf              # PDF report output
├── murders.Rproj           # RStudio project file
└── README.md               # Project documentation
```

## Methodology

### 1. Data Acquisition (`download-data.R`)
* Automated download of FBI gun murder statistics
* Data validation and initial quality checks
* Saves raw CSV files to the `data/` directory

### 2. Data Preprocessing (`wrangle-data.R`)
* Data cleaning and transformation
* Feature engineering and derived variable creation
* Exports processed datasets as R objects (`.rda` format) for efficient loading

### 3. Statistical Analysis (`analysis.R`)
* Exploratory data analysis
* Statistical modeling and hypothesis testing
* Generates publication-ready visualizations
* Saves plots to the `figs/` directory

### 4. Reporting (`report.Rmd`)
* Comprehensive analysis documentation
* Reproducible research workflow
* Available in multiple formats (HTML, PDF)

## Key Features

* **Reproducible Workflow**: Complete pipeline from raw data to final results
* **Version Control**: Git-based project management with detailed commit history
* **Multiple Output Formats**: Analysis results available in HTML and PDF formats
* **Modular Design**: Separate scripts for each stage of the analysis pipeline
* **Data Integrity**: Processed data objects for consistent analysis reproducibility

## Technical Stack

* **Language**: R
* **Environment**: RStudio
* **Documentation**: R Markdown
* **Version Control**: Git
* **Data Formats**: CSV (raw), RDA (processed)
* **Output**: HTML, PDF reports with embedded visualizations

## Getting Started

1. Clone the repository
2. Open `murders.Rproj` in RStudio
3. Run scripts in sequence:
   ```r
   source("download-data.R")    # Download raw data
   source("wrangle-data.R")     # Process and clean data
   source("analysis.R")         # Generate analysis and plots
   ```
4. Knit `report.Rmd` for comprehensive documentation

## Results

The analysis produces:
* Clean, processed datasets ready for analysis
* Statistical summaries and insights
* Professional visualizations in the `figs/` directory
* Comprehensive reports documenting methodology and findings

## Repository Maintenance

This project follows best practices for reproducible research:
* Regular commits with descriptive messages
* Organized file structure with clear naming conventions
* Comprehensive documentation
* Separation of data, code, and outputs

---

*This analysis demonstrates proficiency in data science workflows, statistical computing with R, and reproducible research methodologies.*
