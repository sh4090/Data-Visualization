# Data Visualization: A Story of Socioeconomic Segregation in Lyon's Public Middle Schools (2018)

## Project Overview
This project is one of my presentations for STAT6106 Communicating Data and Statistics class.

It explores the relationship between residential segregation and educational inequality in Lyon, 
using occupation as a proxy for socioeconomic status (SES). By leveraging data on employment and 
school demographics from INSEE and the French Ministry of Education, I analyzed patterns of social 
stratification across the city and display the strong correlations between SES and academic 
achievement in the form of graphs and maps. 

My aim is to provide an argument that middle schools act as agents of social replication instead 
of agents of social mobility.

The graphs are created in R using ggplot2. The maps are created using QGIS, the spatial analysis 
software.

## A Story of Socioeconomic Segregation in Lyon's Public Middle Schools

#### Residential Segregation in Lyon's neighborhouds
I use occupation as a proxy for socioeconomic status. 

![image](https://github.com/user-attachments/assets/e4889331-e718-4871-892f-3f238b1cd320)

The map represents the percentage of the active population depending on their occupation type. The maps 
reveals how Lyon’s city center is dominated by higher-status white-collar professionals ("cadres"), while 
blue-collar workers and lower-status employees ("ouvriers" and "employés") are pushed to the outskirts. 
This stark division shows more than just geographical separation; it reflects the economic divides 
ingrained in the city's fabric in what could be referred to as "socioeconomic isolation".

The visual contrast between affluent city centers and impoverished outskirts COULD be an indicator of 
limited social mixing.

![image](https://github.com/user-attachments/assets/3113ab16-88f1-4406-a5f5-c50a6f314d13)

Through graphical analysis, we see how a mere 1% increase in white-collar residents leads to a steep decline 
in lower social classes in nearby areas (bottom left), proving further the idea of socioeconomic isolation, especially 
between the 2 extremes of the socioeconomic spectrum.

For instance, the distribution of the data between the percentage of blue collar workers and employees indicates 
similar levels of concentration of the two groups across the same IRISes (bottom right).

In short, it appears that the more disparity between two people's socioeconomic status, the less likely they are 
to live in the same IRIS.


