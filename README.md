# EDA on Yahoo Finance Dataset

This repository contains an exploratory data analysis (EDA) project using the Yahoo Finance dataset. The main objective of this project is to visualize and analyze company categorization by sector and sector performance, focusing on leading sectors from January 2023 to December 2023.

## Contents

- `EDA on Yahoo_finance_Dataset.ipynb`: Jupyter notebook containing the EDA, visualizations, and insights derived from the Yahoo Finance dataset.

## Prerequisites

To run the notebook, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- plotly

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn yfinance plotly
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/yahoo-finance-eda.git
cd yahoo-finance-eda
```

2. Open the Jupyter notebook:

```bash
jupyter notebook "EDA on Yahoo_finance_Dataset.ipynb"
```

3. Run the cells to perform the EDA and visualize the data.

## Notebook Overview

The notebook includes the following sections:

1. **Data Collection**: Fetching the data from Yahoo Finance using the `yfinance` library.
2. **Data Cleaning**: Handling missing values and data types.
3. **Exploratory Data Analysis**:
    - Descriptive statistics
    - Sector-wise performance analysis
    - Visualization of sector trends and performance
4. **Visualization**: Generating plots to understand sector performance and leading sectors.
    - Time period covered: January 2023 to December 2023.
    - Preferred color scheme: Red for heatmaps.

## Insights

The analysis focuses on identifying the leading sectors and understanding their performance trends over the specified time period. Visualizations include sector-wise heatmaps, line plots, and bar charts.
