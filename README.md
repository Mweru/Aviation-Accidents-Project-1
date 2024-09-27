# Aviation Accident Analysis

## Project Overview
This project aims to analyze aviation accident data from 1962 to 2023 to identify low-risk aircraft for purchase and operation. By leveraging data cleaning, imputation, analysis, and visualization techniques, we provide actionable insights for the aviation division.

## Business Problem
As our company expands into the aviation industry, it is crucial to understand the risks associated with different aircraft types. This project focuses on determining which aircraft present the lowest risk for our new business endeavor in commercial and private aviation.

## Data
We are working with a CSV version of the Aviation Accident & Synopses named AviationData.csv, which can be found on [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) and was originally from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
Each record represents an aviation accident/incident.
Dataset Size: 88889 entries with 31 columns

## How to contribute/ Usage
- Fork this repository(optional)
- Clone the repository to your device
- Navigate to the project directory
- Open your desired notebook application and share your contributions
- When done, push your commits to your repository
    
## Data Cleaning and Preparation
In this section, we detail the data cleaning process, including handling missing values and data type conversions. The cleaned dataset is used for further analysis. 

## Analysis and Visualizations
The analysis is conducted with the aim of providing valuable insights to company stakeholders. The objective is to determine the potential risks of aircrafts and to provide recommendations about which aircraft models would be of the lowest risk for the company to invest in.
The analysis includes:

- Bar charts of accidents by aircraft Make and Model
- Line plots for correlation between injury types
- Line plots for Total Accidents by weather condition
- Time series analysis of trends over the years

[More Visualizations can be found on my dashboard](https://public.tableau.com/views/Phase1-Project_17273071137820/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) and in the Notebook file.
    
## Key Findings
Certain aircraft categories exhibit lower accident rates, others high, we should least consider those with a record of high number of accidents
Adverse weather conditions correlate with more accidents and as as result higher total injuries.
The aircrafts with 1 engine have recorded high number of accidents

[See Slide presentation here](https://docs.google.com/presentation/d/1aKcoomGOx3dadl9XBWRZdeFGosfuYmgmohNMtGTOWRc/edit?usp=sharing)
    
## Conclusion and Recommendations
The analysis provides actionable insights for the aviation division. It is recommended to prioritize aircraft types with lower risks and establish protocols for managing adverse weather conditions. Here are the 3 main recommendations based on my results; 
1. When selecting the Make of the Aircraft to purchase, we should least consider Cessna and Piper.
2. We should ensure we utilize IMC weather condition aircraft instruments.
3. Consider aircraft types that have 2 or more engines since the acciedent rate is lower. 

In summary, aircraft accidents can cause aircraft damage leading to fatal injuries. Therefore, as a company it is our responsibility to take the neceassary steps to mitigate the risks. 


## Additional Information and resources
Refer to the Notebook file in this repository to see the step by step process.
Refer to the Tableau [Dashboard](https://public.tableau.com/views/Phase1-Project_17273071137820/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) for interractive visualizations.

For more information contact Mweru Gitau at mweruwagitau@gmail.com
