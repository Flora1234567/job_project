# Job Analysis/visualization


Recently, a large number of students will graduate from the university. This repository will contain the dataset for administrative, trade, and bank fields used to analyze recruitment information. And also have the map in NZ. 

Firstly, cleansing dirty data for recruitment information. Data visualization will then see the location field for administrative, trade, and bank field, classification share in different fields, top5 hottest job in the different field, mean salary distribution for different fields, and the relationship between post-day and high salary, low salary in different fields. Finally, visualize a heatmap to show the number of jobs in a different location.

# Data

For different fields of work, each column contains JOB_ROLE, WEBSITE_LINK, COMPANY, LOCATION, POST_DAY, and CLASSIFICATION.

* [NZ_Admin_JOBS.csv](https://github.com/Flora1234567/job_project/blob/main/NZ_Admin_JOBS.csv) - administrative field job
* [NZ_Banking_JOBS.csv](https://github.com/Flora1234567/job_project/blob/main/NZ_Banking_JOBS.csv) - bank field job
* [NZ_TRADE_SERVICES_JOBS.csv](https://github.com/Flora1234567/job_project/blob/main/NZ_TRADE_SERVICES_JOBS.csv) - trade service field job

Map

* [nz_region.geojson](https://github.com/Flora1234567/job_project/blob/main/nz_region.geojson) - NZ map
* [region_sum2.csv](https://github.com/Flora1234567/job_project/blob/main/region_sum2.csv) - concat administrative, trade, and bank field data frame, group by location to get job count that number of people work in a different location, then transform to CSV file



# Notebook

* [data_project_visuallization](https://github.com/Flora1234567/job_project/blob/main/project_plot2.ipynb) - Data analyze recruitment information
* [NZ heatmap](https://github.com/Flora1234567/job_project/blob/main/GIS_plot.ipynb) - Job count for different locations


