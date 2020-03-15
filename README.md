# Inferential-Statistics-Project-Medicare-Claims
Statistical Analysis of Medicare Claims: Inferential Statistics Project
# Statistical Analysis of Medicare Claims Data
### Medicare Project Inferential Statistics

**Introduction**: This project analyses different types of payment claims from Medicare for Diabetes and Renal Disease across different demographic groups in the population including male and female belonging to 'White', 'Black', 'Hispanic', and 'Unknown'. It estimates population parameters from observed sample statistic based on Hypothesis Testing and Confidence Interval. This project uses statistical and mathematical libraries from python.

**About Medicare**: Medicare is a national health insurance program in the United States, begun in 1966 under the Social Security Administration and now administered by the Centers for Medicare and Medicaid Services. (https://en.wikipedia.org/wiki/Medicare_(United_States)).

**Data**: The data for the project has been gathered from the website (https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/DE_Syn_PUF). The data on the website is split into 20 different sample files due to size limitations. In this project, all the 20 sample csv files have been imported and read into a Pandas DataFrame. The dataframes further have been concatenated to form the complete population. Python libraries such as Matplotlib and Seaborn have been used for visualizing the population data to look for any trends in the claims across different demographic groups. From the population, simple random samples have been generated using the python program and inferential statistics has been used to estimate population parameters.

**Code Book**: The data files columns have abbreviated names and codes such as for Male and Female etc. These have been expanded in dataframes using code book made available for by CMS at: https://www.cms.gov/files/document/de-10-codebook.pdf-0 In this code book in CMS Beneficiary (BEN) Summary, in column (Variable Name) BENE_SEX_IDENT_CD code 1 is used for Male and code 2 is used for Female.

**Disclaimer**: As per CMS: "All variables in theDE-SynPUF are imputed/suppressed/coarsened as part of disclosure treatment". "They are all synthetic beneficiaries meant to represent actual beneficiaries". "File (DE-SynPUF) was designed to create new type of file that would be useful for data entrepreneurs for software and application development and training purposes".

**Purupose of This Project**: This project is an effort to showcase what I learnt from the Specialization course on Statistics with Python from the University of Michigan on Coursera by building a project of my own.

**Programming Language**: Python 3.6

**Libraries Used**: 
* numpy
* pandas
* matplotlib
* seaborn
* statsmodels
* scipy

**Statistical Methodologies Employed**: 
* Data Wrangling
* Exploratory Analysis
* analysing distribution with a distplot histogram
* using BoxPlots for visualizing variations
* studying conditional relationships using FacetGrids
* Central Limit Theorem - distribution plots of sampling distribution
* Countplots for categorical analysis
* Estimating Population Parameters from Sample Statistic
* Confidence Interval, Standard Error
* Hypothesis Testing: Null Hypothesis, Alternative Hypothesis
* Difference in Population Proportions
* Difference in Population Means
* Stratifying data and comparing proportions within bands
* Estimating central tendency with pointplots

**Notebook**:  
Python notebook file is available with this project and is named: 
Medicare_Project_Inferential_Statistics.ipynb

**Data**:
The data for the project has been gathered from the website:
https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/DE_Syn_PUF

**Powerpoint Summary**:
Medicare_Project_Inferential_Statistics.pptx
