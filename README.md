# end-of-phase-1-project
By Joy Gitau

# Aviation Accident Analysis

## Project Overview
This project aims to analyze aviation accident data from 1962 to 2023 to identify low-risk aircraft for purchase and operation. By leveraging data cleaning, imputation, analysis, and visualization techniques, we provide actionable insights for the aviation division.

## Business Problem
As our company expands into the aviation industry, it is crucial to understand the risks associated with different aircraft types. This project focuses on determining which aircraft present the lowest risk for our new business endeavor in commercial and private aviation.

## Data
We are working with a CSV version of the Aviation Accident & Synopses named AviationData.csv, which can be found on [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) and was originally from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
Each record represents an aviation accident/incident.
Dataset Size: 88889 entries with 31 columns

## Installation
To run the analysis on your notebook, ensure you have the following libraries installed:
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

## Usage
Fork the the repository:
Click on the Fork button at the top right of this repository on GitHub
Clone the repository:
git clone <repository-url>
Navigate to the project directory:
cd <name-of-directory>
Open the Jupyter notebook:
jupyter notebook 
    
## Data Cleaning and Preparation
In this section, we detail the data cleaning process, including handling missing values and data type conversions. The cleaned dataset is used for further analysis. 

## Analysis and Visualizations
The analysis is conducted with the aim of providing valuable insights to company stakeholders. The objective is determine the potential risks of aircrafts and to provide recommendations about which aircraft models would be of the lowest risk for the company to invest in.
The analysis includes:

Bar charts of accidents by aircraft Make and Model
Line plots for correlation between injury types
Line plots for Total Accidents by weather condition
Time series analysis of trends over the years
[Here is my Tableau Dashboard with addidtional Visualizations] (https://public.tableau.com/views/Phase1-Project_17273071137820/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
    
## Key Findings
Certain aircraft categories exhibit lower accident rates.
Adverse weather conditions correlate with more accidents and higher total injuries.
    presentation- https://docs.google.com/presentation/d/1aKcoomGOx3dadl9XBWRZdeFGosfuYmgmohNMtGTOWRc/edit?usp=sharing
    
## Conclusion and Recommendations
The analysis provides actionable insights for the aviation division. It is recommended to prioritize aircraft types with lower risks and establish protocols for managing adverse weather conditions.

## License

    add license
    This project is licensed under the MIT License. See the LICENSE file for more details.