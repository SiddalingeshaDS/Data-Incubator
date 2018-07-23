# Project for Data Incubator Program
This is a project proposal for Data Incubator program. The goal of the project is to analyze district wise statistics available for all the districts in India.

## Goal
To analyze the district wise statistics across telecommunication, internet penentration, education and health, and observe their corelations with the economic/population characteristics. 

Leverage the above observation to predict the future increase in stats at rural and urban level based on population/economic changes.

## Data Source
I have scrapped for district wise excel files from Census of India website (http://censusindia.gov.in/pca/cdb_pca_census/cd_block.html).
Also, I have manually downloaded district wise statistics excel files from Niti Aayog website (http://niti.gov.in/best-practices/district-wise-statistics) and organized them at a state > district heirarchy for ease of access.

## Preprocessing of Data
To begin with, I am collecting the total number of households, rural households, urban households, total households with internet pct, rural households with internet pct and urban households with internet pct. These fields are present at a district level for all the states from the excel data obtained from Niti Aayog website. 
I am parsing the excel files for each district and creating a cumulative CSV with the information in them.

