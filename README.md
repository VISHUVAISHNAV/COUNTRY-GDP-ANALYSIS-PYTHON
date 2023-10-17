# Country-GDP-Analysis
This is a simple data analysis project that demonstrates how to perform basic data analysis using Pandas and visualize the data using Matplotlib. In this project, we will work with a dataset containing information about countries, their GDP per capita, life expectancy, and other variables.

## Prerequisites

Before you begin, make sure you have the following libraries installed:

- Pandas
- Matplotlib

You can install them using pip:

```bash
pip install pandas matplotlib
```

## Installation

To run this code, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/your-repository.git
```

2. Navigate to the project directory:

```bash
cd your-repository
```

3. Open the Jupyter Notebook `Untitled0.ipynb` using Jupyter Notebook or any compatible environment.

## Data

The dataset used in this project is available in `data.csv`. The data contains information about various countries, including columns like `year`, `gdp_cap`, `life_exp`, `country`, and `continent`.

You can download the dataset [here](https://drive.google.com/uc?export=download&id=1E3bwvYGf1ig32RmcYiWc0IXPN-mD_bI_).

## Code Overview

The Jupyter Notebook `Untitled0.ipynb` contains the following code:

1. Importing necessary libraries.
2. Downloading the dataset from Google Drive.
3. Reading the dataset into a Pandas DataFrame.
4. Basic data exploration using functions like `head()`, `size`, `shape`, `info()`, and `describe()`.
5. Filtering data for the year 2007.
6. Finding countries with the minimum life expectancy and maximum GDP per capita in 2007.
7. Performing value counts on the 'country' and 'continent' columns.
8. Extracting data for a specific country (e.g., India) and plotting GDP per capita and life expectancy.

The code demonstrates how to perform basic data analysis tasks, such as filtering, aggregation, and visualization.

## Usage

You can run the code in the provided Jupyter Notebook and modify it to analyze different aspects of the dataset or use it as a reference for your own data analysis projects.

Feel free to explore the code and adapt it to your specific needs.
