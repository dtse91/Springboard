# Data Science Projects

Note: Please use a notebook viewer if github fails to preview any jupyter notebook [here](https://nbviewer.jupyter.org/).

### Capstone Project 1: Predicting Building Permit Issue Times

**In Progress!**

Building permits are oftentimes a long and less predictable item in a construction project schedule. A data-driven prediction of the issue time would benefit real estate developers, homeowners and building permit officials by ultimately reducing financial risk. To provide some guidance on building permit issue times for these permit applications, I used classification algorithms to classify permit issue times as short, medium or long time duration. I found that location, time and work/permit type are some of the most important features in predicting building permit issue times. Decision trees or random forests may be used to predict building permit issue time durations (medium or long duration) for non-trivial work items based on a 79% AUC metric; non-trivial items may include new buildings and major alterations that will change the use, egress, or occupancy of the building. For minor work (e.g. electrical work and demolition) involving single building departments, a heuristic may be used where issue times of less than a month may be expected.

Presentation Materials:

1. [Report](https://github.com/dtse91/Springboard/blob/master/Capstone%201%20Project/Capstone%20Project%201%20Final%20Report.pdf)

2. [Slide Deck](https://github.com/dtse91/Springboard/blob/master/Capstone%201%20Project/Capstone%20Project%201%20Final%20Presentation.pptx) 


Jupyter Notebook Code:
1. [Data Wrangling](https://github.com/dtse91/Springboard/blob/master/Capstone%201%20Project/Capstone%20Project%201%20Data%20Wrangling.ipynb)

2. [Exploratory Data Analysis](https://github.com/dtse91/Springboard/blob/master/Capstone%201%20Project/Capstone%20Project%201%20Exploratory%20Data%20Analysis%20(EDA).ipynb)

3. [Machine Learning](https://github.com/dtse91/Springboard/blob/master/Capstone%201%20Project/Capstone%20Project%201%20Machine%20Learning.ipynb) 


### Data Wrangling
1. [SQL with Mode Analytics](https://modeanalytics.com/dtse/reports/f9c91d091a0b): In this case study, I role play as an analyst responsible for triaging product and business problems as they come up. In many cases, these problems surface through key metric dashboards that executives and managers check daily. One morning, I noticed a dip in user engagement and now I am responsible for determining what caused the dip and, if appropriate, recommending solutions for the problem. At the end, I recommended a further discussion with the product manager to look closely into the mobile U.S. users who recently experienced lower email click-through rates thus leading to lower user engagement.

2. [SQL with Country Club Data](https://github.com/dtse91/Springboard/blob/master/Data%20Wrangling/1520094343_sql_project.sql): I am approached by the owners of a fictitious country club and asked to answer several business-related questions. The data is located in a MySQL database with three tables: Facilities, Members and Bookings. I use a variety of SQL commands such as joins, aggregations, filters and subqueries to answer their business questions.

3. [JSONs with World Bank Data](https://github.com/dtse91/Springboard/blob/master/Data%20Wrangling/JSON%20Project/sliderule_dsi_json_exercise.ipynb): Given a World Bank dataset, I first load the data into a dataframe and use groupings and agggregations to gain insights about World Bank projects. I also perform visualizations and clean the data by filling in empty cells based on some rules.

4. [APIs Requests with Quandl data](https://github.com/dtse91/Springboard/blob/master/Data%20Wrangling/API/api_data_wrangling_mini_project.ipynb): Using stock data from the Frankfurt Stock Exhange (FSE), I make a request to the Quandl API and convert the data to a dictionary. I then use list comprehensions and custom-made functions to better understand the performance of a particular stock in 2017.

### Exploratory Data Analysis (EDA)
1. [Analyze Human Body Temperature](https://github.com/dtse91/Springboard/blob/master/Exploratory%20Data%20Analysis/EDA_human_temperature/sliderule_dsi_inferential_statistics_exercise_1.ipynb): The mean normal body temperature was held to be 37 degrees C or 98.6 degrees F for more than 120 years since it was first conceptualized and reported by Carl Wunderlich in a famous 1868 book. But, is this value statistically correct? To answer this question, I analyze a dataset of human body temperatures and employ the concepts of hypothesis testing, confidence intervals, and statistical significance. 

2. [Examine Racial Discrimination](https://github.com/dtse91/Springboard/blob/master/Exploratory%20Data%20Analysis/EDA_racial_discrimination/sliderule_dsi_inferential_statistics_exercise_2.ipynb): Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers. Here, I perform a statistical analysis to establish whether race has a significant impact on the rate of callbacks for resumes.

3. [Reduce Hospital Readmissions](https://github.com/dtse91/Springboard/blob/master/Exploratory%20Data%20Analysis/hospital_readmit/sliderule_dsi_inferential_statistics_exercise_3.ipynb): In this excercise, I critique a preliminary analysis of readmissions data and recommendations for reducing the readmissions rate. I also construct a statistically sound analysis and make recommendations of my own.

### Machine Learning
1. [Boston Housing Price](https://github.com/dtse91/Springboard/blob/master/Machine%20Learning/Linear%20Regression/Mini_Project_Linear_Regression.ipynb): Using the Boston Housing Price dataset where every feature is a continuous random variable, I explore the intracacies of multiple linear regression. More specifically, I test assumptions (e.g. normality of residuals), investigate outliers/ high leverage points, calculate/extract relevant statistics (e.g. F-Statistic), and compare/contrast sklearn vs. stats model libraries.

2. [Classify Gender from Heights and Weights](https://github.com/dtse91/Springboard/blob/master/Machine%20Learning/Logistic%20Regression/Mini_Project_Logistic_Regression.ipynb): Using a 3-column data table with height, weight and gender, I use logistic regression to classify the dependent variable gender. I develop code to cross-validate and tune hyperparameters for my model.

3. [Movie Critic Text Analysis](https://github.com/dtse91/Springboard/blob/master/Machine%20Learning/Naive%20Bayes/Mini_Project_Naive_Bayes.ipynb): Using data obtained from Rotten Tomatoes, I use Naive Bayes to classify movie critiques as "fresh" or "rotten," i.e. good or bad. I vectorize based on either term importance or word counts, experiment with Latent Dirichlet Allocation (LDA) to group words into topics, identify strongly predictive features, etc.

4. [Customer Segmentation of Wine Consumers](https://github.com/dtse91/Springboard/blob/master/Machine%20Learning/Clustering/Mini_Project_Clustering.ipynb): Using customer data for wine purchases sourced from [Data Smart](https://www.wiley.com/en-us/Data+Smart%3A+Using+Data+Science+to+Transform+Information+into+Insight-p-9781118661468), I explore multiple clustering algorithms (KMeans, agglomerative, etc.) to derive insights about customer purchasing patterns.
