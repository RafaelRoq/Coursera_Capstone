# Coursera_Capstone


## Introduction
In this project, the aim is to identify the region within Alberta (Canada) that would be a good place to open a spanish restaurant. To do so, for each region, it will be study all the restaurants within (discarding fast food and local restaurants), and the ones that contains a greater number of foreign restaurants will be the ones more suitable to open a spanish restaurant in. The main reason behind this is that the places with more variety of restaurants will probably have a lot of tourism and clients.

## Data
The data source is https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_T (concretely, the section "Alberta - 157 FSAs"). Foursquare will provide data about the many types of restaurants in each region within Alberta (such as italian or chinese). At the end, the dataset will show the number of each type of restaurant within each region, and will help us to decide where is the best place to open a spanish restaurant.

## Methodology
In order to solve this problem, a lot of descriptive analysis have been done. Knowing that the goal is to identify the most friendly region for foreign restaurants, many tables have been created with information such as the number of foreign restaurants per region, and histograms to study its distribution (for instance, with this exploratory analysis most of the regions were discarded because they have 4 or less foreign restaurants, meaning that those are not good places to open a spanish restaurants). Taking into account that this problem requires descriptive analysis and exploratory data analysis, machine learning techniques weren't needed because the exploratory analysis was enough to solve the classification problem.

## Results
As it is shown in the last table, there is a clearly winner: North Downtown has 22 foreign restaurants within (the next one in the ranking only has 12). It should be taken into account that th
