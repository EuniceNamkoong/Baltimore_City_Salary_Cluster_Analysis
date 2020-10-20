# Cluster Analysis of Baltimore City Salaries Based on Annual Salary, Gross Salary, and Years Worked

[phrase](link) 

## Background 
In 2019, a study was conducted by JHU that reviewed [Baltimore police officer pay](https://www.wbaltv.com/article/johns-hopkins-university-21st-century-cities-initiative-study-baltimore-police-officer-pay/29776272#). This research further outlined various public sector pay and employment in Baltimore City which led to insight on staffing, overtime, pay gaps, and more. In this data analysis, we will be looking at a macroscale of employment in Baltimore using public data of [Baltimore City Salaries](https://data.baltimorecity.gov/browse?category=City+Government) to determine how different job titles are group based on annual salary, gross salary, and years worked. 

## Business Question 

How are different job titles grouped based on annual salary, gross salary, and years worked? 

The data has been filtered to only include the fiscal year 2020. The years worked was calculated from the date of hiring to the end of the 2020 fiscal year (6/30/2020). A cluster analysis was then conducted to further analyze the data. 

## Data Analysis and Findings 

![cluster_table](https://github.com/EuniceNamkoong/Baltimore_City_Salary_Cluster_Analysis/blob/main/Cluster_Anchor_Table.PNG)

The data set was divided into three distinct clusters as shown in the table above. 

Data points within the cluster 1 have characteristics that reflect the anchor point Paramedic CRT job. The years worked, annual salary, and gross pay are higher than the average. 

Data points within the cluster 2 have characteristics that reflect that of Community Aide job. The years worked are slightly less than average while annual salary below average and gross pay is greatly below average. 

Data points within the cluster 3 have characteristics that reflect EMT Firefighter Suppression job. The years worked, annual salary, and gross pay are all slightly below average. 


![cluster_graph](https://github.com/EuniceNamkoong/Baltimore_City_Salary_Cluster_Analysis/blob/main/Data_Points_Cluster_Graph.PNG) 

As shown in the graph, there are 4095 job titles within the entire public record data set that identify most similiar to cluster 1, 7535 for cluster 2, and 5586 for cluster 3.

## Summary
This information can be best used in practice when looking to gain insight on salaries for various jobs in Baltimore City. Using the cluster analysis, information such as disparities between pay, how far metrics within each cluster are away from each, etc. within job sectors can be analyzed. If there are economic or social policies that are looking to target socioeconomic disparities by looking at income and standard of living, it would be helpful to look at jobs that fall into clusters with variables that fall below average to better target advocacy efforts. Additional data such as hours that are worked per week by each job could help differentiate between discrepancies due to overtime, minimum wages, or position within the job. 


## Step by Step 

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
