# INF2008-Machine-Learning

Team: Lab P4 Group 4  

Group Members:
1. BRENDAN EDWARD RAJ (2302986)
2. CHUA ZONG HAN LIONEL (2302964)
3. JASBIR KAUR (2302990)
4. KOH YAO HAO (2302952)
5. TIANG SOON LONG (2302974)
6. TOH ZHEN WEI (2303006)

## Table of Contents
- [Problem Statement](##Problem-Statement)
- [Project Overview](#Project-Overview)
- [Things to Note](#Things-to-Note)
- [Datasets](#Datasets)


## Problem Statement:   
Accurately predicting football match outcomes has long been a challenge for analysts, bettors, and sports fans. Traditional prediction models rely on expert opinions, statistical trends, and historical performance, but these methods often fail to capture the complexity and dynamic nature of the game.  

This project aims to **explore the various machine learning models that predict football match outcomes** based on historical match data, team statistics, and other relevant factors.  

By utilising modeling techniques, the objective is to enhance forecasting reliability and offer useful insights for analysts, teams, and even fans of the game.

## Project Overview
Since we had 6 members in this group, we each volunteered to work on 1 model per person as we wanted to explore all possibilities and try to gain hands on experience on the content learnt in class.

The main models we explored to solve our *multi-class classification (Win/Draw/Lose)* problem were:
- Support Vector Machine
- Random Forest
- AdaBoost
- Logistic Regression
- K Nearest Neighbors
- Decision Trees

However, the final shortlisted models that we chose to present during our presentation as they were more relevant were:
- Support Vector Machine
- Random Forest
- AdaBoost

In addition, as part of *future works*, we explored an alternative *binary classification (Win/Never Win)* problem to confirm our findings from our main models, therefore, you should view this model **only at the end**:
- Logisitic Regression (Binary)

## Things to Note
- Each file contains a standard template for ease of navigation and also consistency between the models when it comes to Data Preparation, Cleaning and Feature Engineering.
- Thus, each file would have identical content from `Section 1 (Introduction)` to `Section 5 (Data and Feature Engineering)`, the main difference for each file would begin from `Section 6 (Model Building)`
- Recommendation is to view Section 1 to Section 5 once and you may skip those sections for the rest of the files.
- Recommended to view `Logistic Regression - Binary` as the last model as it is related to our future works 

## Datasets: 
1. Match data dataset from the Premier League (2017-2024)
2. FIFA Team Rating Dataset sourced from the FIFA video game series 

URL Links to Data Sources:  
1. https://fbref.com/en/comps/9/Premier-League-Stats
2. https://sofifa.com/teams
