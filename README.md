## Boat Sales Analysis
 ## Objective and Purpose
To build an interactive dashboard that will visually showcase well-curated results of an advanced exploratory analysis conducted in Python. 
This dataset represents the sales information of used boats listed on a website. The website allows users to advertise their used boat for sales. This allows prospective buyers to have a ﬁrst impression about the boat, its manufacturing details, present conditions as well as listing price. The marketing has requested for the sales analysis in preparation of a weekly newsletter. Essentially, this analysis would help sellers by giving them insights on how they could get more engagement for listed
boats, as well as stay on top of the market trends.  

## Context  
For this Achievement the goal of conducting an exploratory visual analysis in Python and finding connections between variables that seem worth exploring. After developing hypotheses, use various advanced analytical approaches to help test hypotheses.  
The results analyses will be presented in a Tableau dashboard/storyboard. Dashboard will tell the story of analytical journey and, as such, needs to contain a curation of the key results was discovered throughout this Achievement.  

## Data Sources  
The data for this project is an open source data downloaded from https://www.kaggle.com/datasets/karthikbhandary2/boat-sales  

## Limitation and Ethics. 
-	The prices of the boats were listed in diﬀerent currency. This makes it diﬃcult to compare the price amongst the listed boats.  
-	The location of the boats includes the country and an imprecise location which is not consistent across all the listings.  

## Data Cleaning and Data Consistency Checks  
-	Adjust the data type  
-	Convert the prices to a single currency  
-	Extract the country and city from the location  
-	Check for missing data  
-	Check for duplicate data  
-	Check for mixed data type  

## Data Proﬁle. 
-	Number of rows and columns in the cleaned dataset: 6001 x 11 (original data is, 9888 x 10)  

## Ǫuestions to Explore. 
-	Characteristics of the most viewed boat listing in the last 7 days  
-	What is the price of boat that get the most views?  
-	Are there common features among the most viewed boats?  
-	What is the location of the most viewed boat?  

## Exercise 6.2: Exploring Relationships  
- Conduct exploratory visual analysis using relevant Python libraries.  
- Use the questions defined in the previous task to guide your exploration.  
- If possible, define hypotheses to test.  

## Exercise 6.3: Geographical Visualizations with Python  
- Source a shapefile containing location data that corresponds to the location data in the main project data set.  
- Wrangle, clean, and merge data files in preparation for analysis.  
- Conduct a geospatial analysis by creating a choropleth map using relevant Python libraries.  

## Exercise 6.4: Supervised Machine Learning: Regression  
- State hypothesis.  
- Select the relevant variables.  
- Prepare data for a regression analysis.  
- Split the data into two sets: a training set and a test set.  
- Run a linear regression on the data and analyze the model performance statistics.  

## Exercise 6.5: Unsupervised Machine Learning: Clustering  
- Prepare data for a cluster analysis.  
- Use the elbow technique to determine the optimal number of clusters.  
- Run the k-means algorithm.  
- Attach a new column to the dataframe with the resulting clusters.  
- Create a variety of different visualizations using clustered data.  
- Calculate the descriptive statistics for your clusters using the groupby() function and discuss findings and any proposed next steps. 

## Exercise 6.6: Sourcing & Analyzing Time Series Data  
- Source time-series data relevant to project data via an API.  
- Subset data if necessary so that it contains only relevant historical data.  
- Visualize the data in a line plot and decompose its structure.  
- Conduct a Dickey-Fuller test and plot autocorrelations to test for stationarity.  
- Perform differencing to stationarize non-stationary data. 

## Exercise 6.7: Creating Data Dashboards  
- Define the use-case for the dashboard.  
- Outline dashboard contents based on curated results of analysis.  
- Create dashboard/storyboard in Tableau per the requirements in the project brief.  
- Publish a storyboard to Tableau Public.  

## Data Requirements
The data set(s) choose must:  
- Be open-source.  
- Come from an authentic/authoritative source.  
- Include non-anonymized column names.  
- Be recent (ideally, no more than 3 years old. However, this factor is not essential - it could be older too, but not more than 10 years old).  
- Contain at least 2-3 continuous variables (apart from index variables, ID variables, dates, years, etc).  
- Contain at least 2-3 categorical variables (apart from index variables, ID variables, dates, years etc).  
- Contain at least 1,500 rows.  
- Include a geographical object of some kind: for instance, a column relating to a country, continent, or something similar. If the information from the data set refers to the US, for example, there should be a column containing the names/abbreviations of the states.  
**Note:** there should be at least a couple of different values in this column. This is important for the geospatial analysis you’ll be conducting. Of course, can also be used data sets with latitude and longitude.  
- In the course of the Achievement will be sourced a time series data set too, but this procedure will be explained explicitly in the corresponding Exercise.  
