# Data Visualization: A Story of Socioeconomic Segregation in Lyon's Public Middle Schools (2018)

#### NOTE: These are rough deductions made based on observations and a number of earlier assumptions, not a thorough quantitative analysis.

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

### Key Findings

From this data visualization project, I observed that:
1. Socioeconomic classes are concentrated in specific areas of Lyon. The more apart these groups
are on the socioeconomic scale, the less likely they are to reside in the same geographic area.
2. The socioeconomic status of students in middle schools reflects the socioeconomic fabric of
the working population in the geographic area where the school is located. As such, the further
apart students are on the socioeconomic scale, the less likely they are to attend the same school.  
3. 

### Residential Segregation in Lyon's neighborhouds
I use occupation as a proxy for socioeconomic status. 

![image](https://github.com/user-attachments/assets/e4889331-e718-4871-892f-3f238b1cd320)

The map represents the percentage of the active population depending on their occupation type. The 
maps reveals how Lyon’s city center is dominated by higher-status white-collar professionals 
("cadres"), while blue-collar workers and lower-status employees ("ouvriers" and "employés") are 
pushed to the outskirts. This stark division shows more than just geographical separation; it reflects 
the economic divides ingrained in the city's fabric in what could be referred to as "socioeconomic 
isolation".

The visual contrast between affluent city centers and impoverished outskirts COULD be an indicator of 
limited social mixing.

![image](https://github.com/user-attachments/assets/3113ab16-88f1-4406-a5f5-c50a6f314d13)

Through graphical analysis, we see how a mere 1% increase in white-collar residents leads to a steep 
decline in lower social classes in nearby areas (bottom left), proving further the idea of socioeconomic 
isolation, especially between the 2 extremes of the socioeconomic spectrum.

For instance, the distribution of the data between the percentage of blue collar workers and employees 
indicates similar levels of concentration of the two groups across the same IRISes (bottom right). This 
is in line with the maps I created earlier where the zones with the lowest percentage of white collar 
workers are the ones with the highest percentage of blue collar workers and employee-level workers, and 
the maps for blue collar workers and employee-level workers appear to match in terms of high/low 
concentration across zones.

In short, it appears that the more disparity between two people's socioeconomic status, the less likely 
they are to live in the same IRIS.

### Socioeconomic Makeout of Lyon's Middle Schools

My theory suggests that the socioeconomic composition of Lyon’s middle schools mirrors the socioeconomic 
characteristics of the neighborhoods in which they are located. If we can establish a connection between 
a school's socioeconomic profile and that of its surrounding area, it suggests that residential segregation 
directly contributes to segregation within the school system. This leads to unequal opportunities for 
students, as those from higher- and lower-income backgrounds remain separated, limiting their exposure to 
diverse social realities. This perpetuates a cycle of social reproduction, where students are likely to remain 
within the socioeconomic conditions they were born into. This theory assumes that there is minimal change in 
the demographic makeup of these neighborhoods over time.

In this map, category (1) Très Favorisé and (2) Favorisé represent High Socioeconomic status in schools. 
Category (3) Moyen and (4) Très Défavorisé represent Low Socioeconomic status in schools.

![image](https://github.com/user-attachments/assets/a9dfc923-ec50-401a-af33-ba58fd528873)

Areas populated by blue-collar and employee workers appear to correlate directly with schools that have the 
highest percentages of students from the lowest socioeconomic backgrounds. Meanwhile, schools in affluent 
areas serve predominantly high-SES students. This map clues us into how socioeconomic divides might be 
linked to the perpetuation of educational inequality.

It shows how wealth and opportunity are concentrated not just geographically, but institutionally. So, we find
the same dynamic as was for the working population: the further apart students are on the socioeconomic scale, 
the less likely they are to attend the same school.

This is best represented by the following graphs:
![image](https://github.com/user-attachments/assets/48fdf03b-c5fa-481f-8bf7-2ff0be2e4a2a)


