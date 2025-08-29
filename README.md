# Football Data Analysis and Visualization --- Premier League 2024/25 Season

## Project Description / Overview

This project analyzes and visualizes detailed statistics from the
Premier League 2024/25 season. Leveraging match-level data, team
statistics, and referee card data, the analysis provides comprehensive
insights into team performance, disciplinary behavior, and match
outcomes. The project aims to help football enthusiasts, analysts, and
data scientists understand key trends and dynamics through dynamic,
interactive visualizations.

## Table of Contents

-   [Installation / Requirements](#installation--requirements)
-   [Usage](#usage)
-   [Features / Functionality](#features--functionality)
-   [Project Structure](#project-structure)
-   [Contributing](#contributing)
-   [Credits](#credits)

## Installation / Requirements

### Dependencies

Make sure you have Python 3.7 or higher installed, then install the
following packages:

``` bash
pip install pandas numpy plotly kaleido
```

-   `pandas` for data manipulation\
-   `numpy` for numerical operations\
-   `plotly` for interactive visualizations\
-   `kaleido` for exporting static plot images

### Setup

1.  Clone this repository:

``` bash
git clone https://github.com/yourusername/football-data-analysis.git
cd football-data-analysis
```

2.  Ensure the `data/` folder contains cleaned CSVs and pickle files as
    required.

## Usage

Open and run the Jupyter notebooks in the following order to reproduce
the analysis and visualizations: 1. **Data Cleaning and Preparation:**
`file_cleaning.ipynb`\
2. **Data Exploration and Statistics Generation:**
`data_exploration.ipynb`\
3. **Analysis and Visualization:** `data_analysis_vizualization.ipynb`

Example command to launch Jupyter notebook:

``` bash
jupyter notebook
```

## Features / Functionality

-   Calculation of league-wide and team-specific statistics including
    points, goals scored/conceded, fouls, and disciplinary records.
-   Interactive Plotly visualizations: bar charts, line charts, radar
    charts, and box plots.
-   Modular data handling using CSV and pickle formats for efficient
    reuse.
-   Ability to export high-quality static images of graphs for
    reporting.

## Project Structure

    football-data-analysis/
    │
    ├── data/                       # Cleaned datasets and pickle files
    │   ├── cleaned_data.csv
    │   ├── Final League Table.csv
    │   └── team_stats_detailed.pkl
    │
    ├── file_cleaning.ipynb         # Notebook for raw data cleaning and preprocessing
    ├── data_exploration.ipynb      # Notebook for exploring data and computing stats
    ├── data_analysis_vizualization.ipynb  # Notebook for creating interactive visualizations
    └── README.md                   # This documentation file

## Credits

Developed by : Rayhan Feroz
Thanks to the open data communities and tools including Pandas and
Plotly that make this analysis possible.

------------------------------------------------------------------------

