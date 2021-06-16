![Toronto](img/toronto2.jpg "Toronto")
# Coursera Capstone Project: The Battle of Neighborhoods
This github repository is part of the capstone project in order to obtain the IBM Data Science Professional Certificate. 
The purpose of this repository is to store the jupyter notebook and other files related to this capstone project. I will use this readme file
as a presentation for my project.

# Table of Contents
1. Business Problem
2. Target Audience
3. Data Sources
4. Methodology
5. Results
6. Discussion
7. Conclussion

# Business Problem
After searching google for Indian Restaurants in Toronto, I found out that there are just a few of them. Given that are just a few Indian Restaurants
in Toronto, it is a great idea to open one, but the great question is where to open it? In this project I will try to analyze Toronto's neighborhoods
and find out which ones would be a great choice to open an Indian Restaurant.

# Target Audience
The target audience for this project is people who are looking to open an Indian Restaurant in Toronto, developers who are interested in machine learning with python,
and people living in Toronto and looking for Indian Restaurants.

# Data Sources
For this project I used data from three different sources:
1. Wikipedia: I used Wikipedia to web scrape a list of Toronto's boroughs, neighborhoods and postal codes.
2. Coursera: Coursera provided me a CSV that contains the geographical coordinates for each neighborhood in Toronto.
3. Foursquare: I used Foursquare to obtain near venues for each neighborhood in Toronto.

# Methodology
In this project I used data science techniques such as:
- Web scraping
- Data transforming
- K-mean clustering
- Data visualization
- Data cleaning

During the entire project, the following conditions were taken into account:
1. Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned.
2. More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, you will notice that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11 in the above table.
3. If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the borough.

# Results

# Discussion

# Conclusion
