# Generative AI in Data Science

## Project background and context:
A used car dealer has a special feature on Ford cars and wants to design a model that can predict the optimum quotation price for the cars in their lot. Sales data for the past few years have been provided. The dataset contains different features of the cars and the price they were sold at.

The task is to use Generative AI to generate a code to complete the following:

Handle duplicate entries and missing values. 
1. Perform exploratory data analysis to draw keen insights on the data and determine the effect of different features on the price. Some specific requests     are:
    a. Identify number of sales for each fuel type
    b. Identify which transmission type has more price outliers
2. Compare the models with linear, polynomial and ridge regressions on single and multiple variables to find the best performing model
3. Perform a Grid Search on the Ridge regression model to identify the optimum hyperparameter for the model for best performance

The repository contains files:
  1. prompts.txt -  the list of prompts sent to AI agent 
  2. Falcon9WebScraping - web scraping Wikipedia content
  3. Falcon9DataWrangling - (conversion of categorical non-numerical landing outcomes into numerical labels (1,1,0,…)
  4. Falcon9SQL - using SQL queries to explore factors such as unique launch sites, total payload mass, the date of the first successful landing, etc... 
  5. Falcon9FeatureEngineering - visualization of relations between features using matplotlib and seaborn
  6. Falcon9FoliumGeospatial - Geospatial data visualization in order to gain an insight into the factors that affect the success of the launch
  7. Falcon9DASHS - quick insights to questions such as which site/payload range/booster version has the highest successful rate, etc..
  8. Falcon9MachineLearningPrediction - building and testing different classifiers: KNN, SVM, Logistic Regression and Decision Tree to predict the success/failure of landing 
     
Dataset Sources: 
  1. Dataset provided by IBM Skills Network - json file can be found [here.](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/API_call_spacex_api.json)
  2. [Wikipedia - List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/w/index.php?title=List_of_Falcon_9_and_Falcon_Heavy_launches&oldid=1027686922)
  3. dataset_part_1.csv, the result of Falcon9CollectingData also available [here.](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_1.csv)
  4. my_data1.db and Spacex.csv, available in this repository
  5. dataset_part_2.csv, the result of Falcon9DataWrangling, also available [here.](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_2.csv)
  6. Dataset provided by IBM Skills Network - spacex_launch_geo.csv, available in this repository
  7. Dataset provided by IBM Skills Network - spacex_launch_dash.csv, available in this repository
  8. Datasets provided by IBM Skills Network - dataset_part_2(for Falcon9Machine Learning).csv and dataset_part_3(for Falcon9Machine Learning).csv, available in this repository

Technologies Used: python, pandas, matplotlib, sklearn, plotly, folium, dash, seaborn

Installation: copy and run the code in Jupyter Notebooks or other Python editor of choice. Keep dataset files in the same folder.

![First_stage_landing](https://github.com/natvnu/SpaceX-Landing-Success-Project/blob/main/landing_1.gif?raw=true)



