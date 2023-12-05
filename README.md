# SmartEDA in Google Colab with R Kernel

## Overview
This repository contains a Jupyter notebook configured to run R within Google Colab, a platform typically associated with Python. The notebook demonstrates how to use the SmartEDA package for exploratory data analysis in R, in conjunction with the 'tidyverse' suite of packages. This setup allows users to utilize Google Colab's resources without needing a local R installation.

## Accessing and Running the Notebook
- Navigate to the Notebook: Locate the Jupyter Notebook file (.ipynb) in this repository.

- Open in Colab: Click the "Open in Colab" badge at the top of the file to launch the notebook in Google Colab.

- Change Runtime to R: To ensure the notebook runs with an R kernel:

1. In Colab, go to the Runtime menu.
2. Select Change runtime type.
3.  Choose R from the dropdown under Runtime type.
4. Click Save.

- Verify the R Environment: The first line of code print(R.version.string) confirms the R setup. Run this cell to display the version of R in use.

```print(R.version.string)```

- Using Tidyverse: Directly load the pre-installed tidyverse package in the notebook:

``` library(tidyverse)``` 

- Install SmartEDA: Follow the notebook instructions to install and load the SmartEDA package:

``` install.packages("SmartEDA")```
``` library(SmartEDA)```

# Automated Exploratory Data Analysis with SmartEDA

**SmartEDA** is an R package designed to simplify the exploratory analysis of data, ideal for quickly understanding the structure and relationships in datasets. It efficiently handles both numeric and categorical predictors and remains useful even in the absence of categorical variables.

**SmartEDA**  automates various aspects of data exploration, including descriptive statistics, information value analysis, and the creation of custom tables and graphical representations. This makes it an invaluable tool for data scientists and analysts looking to save time and gain immediate insights into their data.

# Features Demonstrated in the Notebook
- Basic data exploration with SmartEDA.
- Generating descriptive statistics.
- Creating custom tables and visualizations.
- Utilizing tidyverse for data manipulation and visualization.
- Generating HTML reports.

# Prerequisites
No local installation of R, SmartEDA, or tidyverse is required, as everything runs in the cloud on Google Colab. However, a Google account is necessary to access Google Colab.

# Note
The notebook does not cover the weight of evidence (WoE) analysis. Users interested in this aspect might need to perform additional steps.

# License

- This project is licensed under the MIT License. For more details, see the LICENSE file in this repository.

- Dataset License
The dataset used in this project, "Global Country Information Dataset 2023," is maintained by Kaggle and is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). For more information about this license, please visit Creative Commons License CC BY 4.0.

