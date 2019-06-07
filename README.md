# Air Pollution vs GDP Analysis
## Getting Started:
Hi Team :D!
Please review the Google Doc “Repository Instructions” before getting started to set up your terminal and connect to the repo.

Note about Repo Setup:
I’ve set up the branches to act as folders for each category we are doing analysis for. 
Thus, if you’d like to create a new folder/branch please feel free to do so and notify us of the changes. 

## DataSet Workflow:
We do our analysis from one dataset! I’ve found a dataset called “World Development Indicators” from the World Bank. 

*Optional*
We can call the OpenAQ API to make heat graph of how air pollution has changed over the past 90 days. 
Since we just entered summer maybe we can show a heat map from March to today and call it “Seasonal Air Pollution Changes” or something like that?

## Actual Dataset Used
*Dataset Docs are in the Google Drive if you're having issues*

- Dataset: https://datacatalog.worldbank.org/dataset/world-development-indicators
- Subject: Refer to doc “World_Dev_Indicators_Reviewed_Subjects.docx”

I included some other interesting indicators in case you were inspired to do further analysis. 
As long as we keep the scope of population/GDP aka consumptions vs air_pollution then we should be good. 
I included an environment component in case we wanted to show how those consequences affect biodiversity. :) (again optional)

List of Indicators:
Refer to csv “WDI_list_of_reviewed_indicators.csv”

Columns: 
- Country Name
- Country Code
- Indicator Name
- Indicator Code
- Years (1960 thru 2018)

##Objectives:
Task List: 
Josefina - Make API and Datasets into DF in pandas - Set to Master

Each Subject: 
1. Bar Graph - Current
2. Line Graph - Historical 5 Years
3. Statistical Correlation Graph *Optional

Potential Data Visualizations:
1. T-Test & p-value : Using a histogram to show the frequency/distribution of the values in the table [Use class example: 07-Project-1/3/Activities/02-Ins_TTest] note: use ANOVA? instead of ttest for mlt variances
This can be used to show how an industry’s growth correlates matches with air pollution
2. Also using a scatter plot to show how pollution and population are correlated (either prove or disprove)
3. Line graph to show pollution growth over time as GDP (whichever we decide) increases over time - agree, I like this idea. It can be the first graph we show. - Wendy

## Analysis Outline
Branch Name: (GDP_analysis) Alex
- Create a table of top 30 Countries GDP <Alex B>
- Create a csv of top 30 countries GDP for others to use
- Find the distribution of GDP throughout the countries 
- Create a new column in DF and categorize the countries into GDP buckets (Low, Medium Low, Medium, and High) [suggestion] 
- Output new analysis into csv for others to use
- GDP per Country (Bar Graph)
- GDP by Country per Year (Line Graph)
  
  
 Branch Name: (air_pollution) Joyce
- Create a csv of CO2 pollution by countries for others to use
- Find the distribution of air pollution throughout the countries 
- Create a new column in DF and categorize the countries into air pollution buckets (Low, Medium Low, Medium, and High) [suggestion]
- Output new analysis into csv for others to use
- Air Pollution per Country (Bar Graph)
- CO2 & PM.25 by Country per Year (Line Graph)
  
Branch Name:(population) Wendy
- Create a csv of population by countries for others to use
- Find the distribution of population throughout the countries 
- Create a new column in DF and categorize the countries into population buckets (Low, Medium Low, Medium, and High) [suggestion]
- Output new analysis into csv for others to use
- Population per Country (Bar Graph)
- Population Growth % by Country per Year (Line Graph)
  
Branch Name: (correlation_analysis)  All
- We can create a graph of GDP, Air Pollution and Population by Buckets 
This will help us compare apples to apples to falsify our hypothesis
- Summary chart of cities that have appeared in each set
Create a list of top cities by columns: GDP, Air Pollution, and Population; rows: Cities ; values: *see Fig 1* for each column
Create a column to sum up the rows
Use these values to create a map of which cities were in each category

Link to Fig1: https://github.com/JosefinaAureaAmaro/Project_1_AirPollution_vs_GDPperCapita/blob/correlation_analysis/fig1.PNG
- The values in figure 1 will help us make conclusions based on the sum of the final column. 

## The End

Please let me know if you have any questions or recommendations















