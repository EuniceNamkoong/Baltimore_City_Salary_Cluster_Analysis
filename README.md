# Cluster Analysis of Baltimore City Salaries Based on Annual Salary, Gross Salary, and Years Worked

[phrase](link) 

## Background 
In 2019, a study was conducted by JHU that reviewed [Baltimore police officer pay](https://www.wbaltv.com/article/johns-hopkins-university-21st-century-cities-initiative-study-baltimore-police-officer-pay/29776272#). This research further outlined various public sector pay and employment in Baltimore City which led to insight on staffing, overtime, pay gaps, and more. In this data analysis, we will be looking public data of [Baltimore City Salaries](https://data.baltimorecity.gov/browse?category=City+Government) to determine how different job titles are group based on annual salary, gross salary, and years worked. 

## Business Question 

How are different job titles grouped based on annual salary, gross salary, and years worked? 

## Data Analysis
![name of file](link) 
Three Clusters
why are there three distinct clusters
what are they? 

paramedic jobs are in the first cluster, defined by .. higher than average year





# Step by Step 

1) Download data set from https://data.baltimorecity.gov/browse?category=City+Government
1) Filter to only include FY2020 data.
1) Format cells for variable HireDate to only include dd/mm/yyyy.
1) Create an EndDate of 6/30/2020 to mark the end of the fiscal year.
1) Find the mean and standard deviation of the 3 variables AnnualSalary, GrossPay, and YearsWorked for each job title.
1) Using the mean and standard deviation, find the z-scores for the 3 variables using the standardize formula. 
1) Select all the data points including the following: Job # sequence, JobTitle, AgencyName, YearsWorked, AnnualSalary, and correlating z-scores. Name it “cluster” 
1) Create an anchor table with 3 anchor points that include the job #, JobTitle, and z scores. 
1) Find the distance squared from the z-scores in the anchor table from the z-scores in the “cluster” data set. 
1) Find the minimum distance between the three distances and separate it in another column.
1) Calculate the minimum sum.
1) Match anchor number for all the job titles.
