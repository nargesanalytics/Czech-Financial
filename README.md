#    Czech Bank Data Cleaning Exercise
##   Overview
This repository contains datasets related to Czech bank transactions, accounts, and district demographics. The purpose of this project is to practice data cleaning, column transformations, and other techniques 
to improve the quality of the data.## Environment

This project was developed using the Kaggle environment. You can find the original Kaggle notebook (https://www.kaggle.com/code/nargeshaghparast/czech-financial).



## Datasets
- account.csv: Static characteristics of bank accounts.
- transaction.csv: Records of individual transactions on accounts.
- district.csv: Demographic characteristics of districts.

## Objective
- Examine and clean each individual dataset.
- Combine datasets into a single dataset for further analysis.
- Create new columns based on existing columns to enhance understanding.

## Installation
- pip install pandas

## Data Cleaning Process
- Examine Individual Datasets: Open and explore each dataset separately to understand its structure and content.

- Cleaning Steps: Document the steps taken to clean each dataset. This may include handling missing values, correcting data types, and removing duplicates.

- Combining Datasets: Merge the cleaned datasets into a single dataset using appropriate keys.

- Create New Columns: Based on the bank's description and your analysis, create new informative columns that can aid in understanding customer behavior.

## Usage
- import pandas as pd
- mport numpy as np
- import os
  - for dirname, _, filenames in os.walk('/kaggle/input'):
   - for filename in filenames:
      -  print(os.path.join(dirname, filename))
 

# Load cleaned dataset
- df = pd.read_csv('cleaned_dataset.csv')

# Acknowledgments
- Original dataset source: Czech Financial Dataset
