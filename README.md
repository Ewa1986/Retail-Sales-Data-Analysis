# Retail Sales Data Analysis Project

**Retail Sales Data Analysis Project ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. 

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

Historical sales data for 45 stores located in different regions of USA - each store contains a number of departments. The    
Data (Excel sheets: Stores, Features, Sales) was downloaded from https://www.kaggle.com/datasets/manjeetsingh/retaildataset/data .


## Business Requirements
 
Analyse retail sales data to identify trends, insights, and the impact of promotional markdowns on sales. 
Provide comprehensive, visually appealing sales reports and insights to assist in strategic decision-making.


## Hypothesis and how to validate?

* Bigger shops generates more sales - check using Data Visualisation
* Majority of sales are happening over non-holidays weeks - check using Data Visualisation
* There is a massive pick in a sales over Christmas period - check using Data Visualisation
* All the shops (Type A, B and C) are experiencing pick time over the Christmas - check using Data Visualisation
* Markdowns during non - holidays weeks has smaller impact on sales rather than during holidays - check using Data Visualisation

## Project Plan
1. Downloading data set
2. ETL Pipeline: Extract, Transform and Load
3. Suggesting hypothesis
4. Data Visualisation: Descriptive Statistics, Trend Analysis, Impact Analysis & Comprehensive Analysis
5. Concluding 

I decided to use data visualisation as clear visual representation aids in better decision-making. 

## The rationale to map the business requirements to the Data Visualisations

* Pinpoint which stores generate the highest weekly sales - Average Weekly Sales per Store and Department (bar chart)
* Detect seasonal trends and cyclic pattern in sales - Average sales trend by type (line chart)
* Examine if larger stores drive higher sales - Correlation between store size and weekly sales (scatter chart)


## Analysis techniques used

Data Visualisation - can oversimplyfy data or mislead if not designed carefully. There is no alternative to this method. 

Descriptive Statistics - sensitive to outliers, assumes normal distribution which is not always the case, oversimplify patterns and relationships

Trend Analysis - assumes that historical trends continue

Impact Analysis - correlation vs causation: may identify relationships without proving causation

Comperative Analysis - comparison can be misleading if datasets have diffrent structures or scales which wasn't the case in this project 

In my view, combining all these techniques within a project ensures success by providing a comprehensive and balanced analysis.


I used AI tools (ChatGPT) to help with bugs.

## Ethical considerations

* Analysed data set didn't include sensitive information like names, contact details, purchase history therfore there was no ethical consideration involved. 
* There was no legal or social concerns as well. 

## Unfixed Bugs

* I didn't leave any unfixed bugs, but unfortunately I coudn't fully utlised plotly as my laptop has insufficient RAM. One of plots generated by me was causing gitpod website to crash and subsequently I had to delete it plot and use instead Matplotlib in my project. 

I recognised that I have limited knowledge about gitpod and to address that I visited LMS platform and I watched few videos on youtube about the platform.

## Development Roadmap

* The biggest challenge I faced was quickly locating the relevant functions on the LMS platform as I had an idea what I want to do but I didn't remember function name.

* Based on this project experience, I realized that I need to practice formulating hypotheses from a given dataset, as I spent too much time overthinking it this time.

## Main Data Analysis Libraries
* pandas
* numpy
* plotly.express
* seaborn
* matplotlib

## Credits 

* Content:

General information about the data set taken from: https://www.kaggle.com/datasets/manjeetsingh/retaildataset/data (Data Card Tab)

LMS - getting an idea which charts I can generate from the dataset 
