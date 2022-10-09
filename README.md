## Project Overview

This project has five major stages

1.**Choose the Data Set:** 

The data to be used is downloaded from the link provided in a Google doc [here]()

2.**Get Organized**

Create a single folder that will eventually contain, the report communicating the findings, Python code written as part of the analysis, and the data set used.

3.**Analyze the Data**

Assess the dataset and brainstorm some questions that could be answered using the dataset. These questions should aim at looking at relationships between multiple variables, clearly identifying dependent and independent variables.

4.**Share the Findings**

After analyzing the data, create a report that shares the findings found to be most interesting.

5.**Review**

Use the Project Rubric to review and improve the project. 

## Project Details

The project involves conducting data analysis; data gathering, data cleaning, data visualization as well as sharing the findings. I'll start by assessing the dataset, and brainstorming appropriate questions could be answered using it. Then I'll use pandas and NumPy to answer the questions and create a report sharing the answers. 

## What I need to install

I will install Python, plus the following libraries:

* pandas
* NumPy
* Matplotlib
* csv

## Why this Project

In this project, I'll go through the data analysis process and see how everything fits together using the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier. I will also clean and combine all the seven datasets into one master dataset to be used in the analysis

## Project Questions for Analysis

1. What teams improved the most over the time period?
2. Which players had the most penalties?
3. Which was the the most preferred leg for penalty-takers in 2016 among the players who scored more than the mean penalties in that year?

## Dataset

In this project, I will analyze a soccer dataset [here](https://www.kaggle.com/datasets/hugomathien/soccer/download?datasetVersionNumber=10) and then communicate the findings about it.

## Dataset Description

In this project, I willl be analysing ultimate soccer [dataset](https://www.kaggle.com/datasets/hugomathien/soccer), which is an open-source dataset in kaggle. The dataset is a one .sql file comprising _seven tables_, each with different(unique) but interrelated features. 

- **Country table** has 11 European countries. 
- **League table** has 11 lead championship names. The country and league tables are related by their ID. 
- **Match table** has over 25,000 matches for different seasons as well as betting odds from upto 10 providers. The match table is also related to the previous tables by country_id. 
- **Player table** contains 11 columns including playes name, birthday, fifa_api_id, weight, and height 
- **Player_Attributes table** has 42 player attributes.
- **Team table** contains tema long name, short name, team api id, team fifa api id.
- **Team_Attributes table** has 25 team attributes.

## Data Cleaning

First, I want to create functions that will help me drop duplicates, merge two datasets, change data type, remove missing rows, drop unnecessary columns, then proceed to to merge the country data to that for league. I will correct the league name for Germany 1. Bundesliga to Germany Bundesliga 1. I will also change the name column for both the country data and league data, and also make the datafrmaes have the same dimensions and finally merge the two dataframes into country_league data using the country id as the key

## Findings

The top 3 most improved teams are Paris Saint_Germain, Napoli and Cracovia.

![image](https://user-images.githubusercontent.com/7541585/193405315-144e92ff-95ab-474a-8848-2ad62d4a794c.png)

## Limitations

The soccer database is a very extensive data. In, seeking to address the three questions in the description, I was able to show only the correltaion between the number of goals scored in the two season. However, the other seasons were not considered.The data base had a lot of unprocessed html files under certain columns, which made take a lot of time thinking on how well they can be used in the analysis. In addition, the data had a lot of missing and duplicate values. Identifying such inconsistencies, wss realy time consuming.

Another limitation is that in the creation of bar graph for the most improved teams, the bars are not sorted in order of either increasing or decreasing frequency, which would have enabled the identification of the improved teams easily. In getting the most preffered leg, it was only based on the year 2016 instead of the whole duration of time.

## Conclusions

The soccer database has five datasets, league, country, player, player attribute, team and team attribute. It is a detailed dabase for European major leagues covering several seasons from 2008/2009 t0 2015/2016.

The project seeks to answer three questions, what teams improved the most over the time period, which players had the most penalties and which was the the most preferred leg for penalty-takers in 2016 among the players who scored more than the mean penalties in that year?

In attempting to find solutions to the question, each dataset was examineed for inconsistencies, colomn names, corrected, missing values replace or droped in certain datasets before they were finally merged and cleaned. Visual presentations created and inteprated.

From the analysis and visualization, Richie Lambert is the player who scored most of the penalties. I also found that Paris Saint-Germain is the most improved team over the period of time given, followed by Napoli and Cracovia being the in the third position. Moreover, the findings also indicate that most of the penalty takers in 2016 preferred right leg compared to the right leg. The findings also shows that the distribution of the number of goals scored in the two seasons are right skewed.

Whereas I was able to show that there is a correltaion between the number of goals scored in the two extreme seasons (2008/2009 and 2015/2016), theer are other seasons that were not considered. There is likelihood that a team that improved between the two seasons might not have improved in the seasons prior 2015/2016. Goal difference between the two seasons was used as a measured of improvement in performance because the ultimate objective of team managers, players and teams is to improve to score goals, but there could be criteria for measuring performance.

## Skills learned

- The steps involved in a typical data analysis process
- Formulating the research questions that can be answered with a given dataset and then answering those questions
- Investigating problems in a dataset and wrangle the data into a format that can be used
- Communicating the results of the analysis
- Vectorized operations in NumPy and pandas to speed up your data analysis code
- Pandas' Series and DataFrame objects
- Matplotlib skills to produce plots showing findings
