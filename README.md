## Project Overview

In this project, I will analyze a dataset and then communicate the findings about it. I will use the Python libraries NumPy, pandas, and Matplotlib to make the analysis easier.

## Project Details

For the final project, you will conduct your own data analysis and create a file to share that documents your findings. You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers. You will not be required to use inferential statistics or machine learning to complete this project, but you should make it clear in your communications that your findings are tentative. This project is open-ended in that we are not looking for one right answer.

## Dataset Description

In this project, I willl be analysing ultimate soccer dataset, which is an open-source dataset in kaggle. The dataset is a one .sql file comprising seven tables, each with different(unique) but interrelated features. First, Country table has 11 European countries. Second, league table has 11 lead championship names. The country and league tables are related by their ID. Third, match table has over 25,000 matches for different seasons as well as betting odds from upto 10 providers. The match table is also related to the previous tables by country_id. in the rows and 2 columns id and name I have check the shape of table to determine the nummber of rows and columns.

## Project Question(s) for Analysis

1. What teams improved the most over the time period?
2. Which players had the most penalties?
3. Which was the the most preferred leg for penalty-takers in 2016 among the players who scored more than the mean penalties in that year?

## What do I need to install?

I will install Python, plus the following libraries:

* pandas
* NumPy
* Matplotlib
* csv

## Why this Project?

In this project, I'll go through the data analysis process and see how everything fits together.  using the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier!

## Data Cleaning

First, I want to create functions that will help me drop duplicates, merge two datasets, change data type, remove missing rows, drop unnecessary columns, then proceed to to merge the country data to that for league. I will correct the league name for Germany 1. Bundesliga to Germany Bundesliga 1. I will also change the name column for both the country data and league data, and also make the datafrmaes have the same dimensions and finally merge the two dataframes into country_league data using the country id as the key

## Project stages

1. **Step One** - Choose the Data Set

Click this link (available in a Google doc here) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.

2. **Step Two** - Get Organized
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:

The report communicating your findings
Any Python code you wrote as part of your analysis
The data set you used (which you will not need to submit)
You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a notebook template to help organize your investigation, you can click here. Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project.

3. **Step Three** - Analyze the Data
Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the data set options to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!

4. **Step Four** - Share the Findings
Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.

5. **Step Five** - Review
Use the Project Rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!

## Findings

The top 3 most improved teams are Paris Saint_Germain, Napoli and Cracovia.

![image](https://user-images.githubusercontent.com/7541585/193405265-ed2d1ed9-3ac3-4466-9816-8fa4f1733d8e.png)

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
