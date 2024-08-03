# Global Hunger Index Dive Deep Using SQL

## Overview

This project analyzes the Global Hunger Index (GHI) data using SQL to uncover trends, improvements, and persistent issues in global hunger from 2000 to 2023. The analysis is conducted through SQL queries executed within a Jupyter notebook.

## Table of Contents

- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [SQL Queries and Analysis](#sql-queries-and-analysis)
- [Results](#results)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Structure

The project consists of a Jupyter notebook that contains SQL queries and the corresponding analysis. The notebook is organized as follows:

1. **Introduction**: Overview of the project and objectives.
2. **Data Loading**: Loading the dataset into a SQL database.
3. **Exploratory Data Analysis**: Performing initial data exploration to understand the dataset.
4. **SQL Queries**: Detailed SQL queries to analyze various aspects of the GHI data.
5. **Results Visualization**: Visualization of the results obtained from SQL queries.

## Datasets

The dataset used in this project includes Global Hunger Index values from 2000 to 2023. It encompasses:

- Country names
- GHI values for the years 2000, 2008, 2015, and 2023

## SQL Queries and Analysis

The analysis is conducted using a series of SQL queries, each addressing a specific question or aspect of the GHI data. Some key queries include:

1. **Countries with Improved GHI**: Identifying countries that had a decrease in GHI in 2023 compared to 2015.
2. **Number of Countries Above Threshold**: Counting the number of countries with a 2023 GHI value greater than 20.
3. **Top Improvers**: Listing the countries with the highest total decrease in GHI from 2000 to 2023.
4. **Consistent Improvement**: Analyzing the countries with consistent improvement over the years.
5. **Highest Average GHI**: Finding the country with the highest average GHI across all years.

## Results

The results of the analysis provide valuable insights into global hunger trends, such as:

- Countries showing significant improvement in GHI
- The number of countries with critical GHI values
- Top-performing countries in reducing hunger
- Consistency in improvement over multiple years
- Countries with persistently high GHI values

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- SQLAlchemy
- Pandas
- Matplotlib (for visualization)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Soniya-krishikka/Global-Hunger-Index-Dive-Deep-Using-SQL.git
cd global-hunger-index-sql-analysis
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Usage

1. Open the Jupyter notebook:

```bash
jupyter notebook Global\ Hunger\ Index\ Dive\ Deep\ Using\ SQL.ipynb
```

2. Run the cells in the notebook to load the data, execute SQL queries, and visualize the results.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.
