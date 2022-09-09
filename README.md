# Data-Science-Capstone-Project
In this interdisciplinary data science capstone project, my group members and I created a digital dashboard (tableau) that shows users groups of countries clustered based on country COVID-19, QS university rankings and socioeconomic index data.

## COVID-19 Digital Dashboard
Link to our COVID-19 digital dashboard: [Oabroad](https://public.tableau.com/app/profile/christopher.tong2548/viz/COVID-03DEMO/Home?publish=yes)

## Final Report
Link to the final report: [Final Report](https://sanghyunkim1.github.io/Data-Science-Capstone-Project/COVID-C03-Report.html)

## Aim
With loosened travel restrictions, we aim to help high school / undergraduate students make better decisions when choosing a university to study overseas. <br> As our country clustering system takes into account (1) COVID-19 spread, (2) country socioeconomic index, and (3) university rankings by subject, we expect our digital dashboard to help students find the most suitable countries for their study.

## Individual Contribution - COVID-19 Country Clustering
As a data scientist of the group, I imputed COVID-19 missing data using a Multiple Imputation by Chained Equations (MICE) technique. <br>
Then I computed Dynamic Time Warping (DTW) distance matrix to identify similarity in shapes between two time series data. With this DTW distance matrix, I clustered countries using a hierarchical clutering algorithm. The below dendrgoram shows COVID-19 country clusters.

<img src = "https://github.com/SanghyunKim1/Data-Science-Capstone-Project/blob/master/COVID-19%20Clusters.png" width="800" height="450" p align="center">



## Acknoledgements
