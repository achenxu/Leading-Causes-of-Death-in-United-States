# Analyzing the Leading Causes of Death in United Stated
#### By Pratyush Painuly, Mohammad Shiwani and Brandon Valmont

## About - 
CDC releases Mortality data set for each death occured in United States annually, under the National Vital Statistics Systems. This mortality dataset gives insight into every death in the country, including the cause of death, location(State), Time and scientific description of the respective cause. Data.cdc.gov takes that data to present the age-adjusted death rates for the 10 leading causes of death in the United States beginning in 1999, which we will be analysing for this project. Our goal is to look into the pattern of death distribution across the country/states and explore the complex circumstances which dominate this dataset, hence get a better understanding of leading causes around the country. We also aim to look at this data with a global stand point and analyse how the mortality rates of countries with similar size, per capita and GDP match with United States.

## Dataset Overview
The [dataset](https://data.cdc.gov/NCHS/NCHS-Leading-Causes-of-Death-United-States/bi63-dtpu) was obtained in .csv format from Data.CDC.gov under the publisher National Center for Health Statistics. The information in the dataset compiles the death certificates filed in each state and presents it as a summary for each year by state and cause of death. Age-adjusted death rates (per 100,000 population) are based on the 2000 U.S. standard population. The source dataset has 10,296 rows and 6 columns (Year, 113-Cause,Cause Name,State, Deaths and Age Adjusted Deaths). We downloaded the dataset directly from the website and imported as a dataframe in jupyter notebook before beginning our analysis. 

## Questions regarding the Dataset - 
We discussed in details various ways to approach the dataset. We divided our approach in Section, each one aiming to look at the data in a different perspective. 

### Section 1 - Causes of Death, Nation Wide/Global Insights
We looked at the dataset in a general countrywise view. We looked at what have been the leading causes throughout the timeframe and how have they changed. How can we look at the same questions for each state. Now, how does the number of deaths compare with the rest of the world? Espcially to "similar" countries with respect to size, GDP and wealth(or poverty). How does United States rank with other countries in mortality rate and what is the progression of time?

### Section 2 - Add Title and summary (Mohammad)
<ADD SUMMARY>

### Section 3 Leading Causes of Death in Texas and their Trends (Brandon)
The original data was taken from the CDC included all states and the District of Columbia.  In this section of the project, the group wanted to answer what the leading causes of death were on a micro level.  The discision was made to analyze Texas since that state would satisfy slicing the data to a micro level and would also be the state local to Rice University.  After drilling down into the original dataset and filtering for Texas, it was determined that heart disease, cancer, and stroke were the three leading causes of death respectively.  Please see figure below for more details.


## Research Questions and Analysis

