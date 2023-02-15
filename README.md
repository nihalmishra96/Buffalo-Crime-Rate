# Buffalo-Crime-Rate


This project aims to analyze the crime patterns in the city of Buffalo, New York. The dataset was
collected from Open Data Buffalo, (Buffalo’s official open data program that makes public
information publicly available). This dataset is updated daily and offers a preliminary look at crime
reports in the City of Buffalo. We extracted the data using Socrata Open Data API. The consumed
data was then stored in a csv file, from which the data was ingested in database using SQLite. EDA
was then performed on the data to find underlying patterns, and visualized using various Python
libraries. Finally, predictions were made to categorize if a certain type of incident is a
Larceny/Theft or not.

## Objective

By analyzing the crime dataset, we aimed to answer the following questions:
a. Analyze crime patterns over months and identify the month with the highest number of
criminal activities recorded
b. Analyze most frequently occurring incidents(Larceny/Murder/Sexual Assault)
c. Analyze the most unsafe neighborhoods in Buffalo
d. Analyze if crimes happen more over weekends than weekday


## Implementation

We used the public dataset provided daily by the Buffalo Police Department. It offers a
preliminary look at crime reports in the City of Buffalo. The dataset consists of 287K rows with
29 columns, each with a crime incident (Crime Incidents | OpenData Buffalo)
The data was consumed via Socrata Open Data API. The data was then stored in a csv file from
which the data was ingested in the database.
The data was normalized and stored in 3 tables namely: INCIDENT TYPE, INCIDENT INFO
and INCIDENT LOCATION
