# 🎖️ IBM Data Science Certification..
SpaceX Falcon 9 first stage success landing prediction with Machine Learning Models  
  
This is the rersult of the IBM Data Science Certification capstone.  

## We will predict if the SpaceX Falcon 9 first stage will land successfully.  
![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)


SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.

Therefore if we can determine if the first stage will land, we can determine the cost of a launch.  
This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.  
  
## Table of Contents
- [Data Collection Notebook](01_data-collection-api.ipynb) - Collects data from the SpaceX API, cleans and saves it to a csv file.
- [Webscraping Notebook](02_webscraping.ipynb) - Extracts a Falcon 9 launch records HTML table from Wikipedia, parses the table, convert it into a Pandas data frame and saves it to a csv file.
- [Data Wrangling Notebook](<03_data wrangling.ipynb>) - Performs exploratory  Data Analysis and determine Training Labels.
- [SQL Exploratory Data Analysis Notebook](04_eda-sql-sqllite.ipynb) - Uses SQL to explore the data.
- [Exploratory Data Visualization](05_eda-dataviz.ipynb) - Performs exploratory Data Analysis and Feature Engineering using `Pandas` and `Matplotlib`.
- [Interarctive Map](06_launch_site_location.ipynb) - Uses `Folium` to create an interactive map of the launch sites and some data marks.
- [Dashboard Application](07_dashboard_application.ipynb) - Crerates a dashboard application using `Plotly Dash`.
- [Machine Learning Prediction](08_Machine_Learning_Prediction.ipynb) - Determine Training Labels, finds the best hyperparameters for different models such as 'SVN', 'Classification Trees' and 'Logistic Regression' and evaluates their performance.
  
## Presentation
[Power Point](00_presentation_ds-SpaceX-capstone.pptx) presentation of the project.  


## License
Copyright (c) 2023 Felipe Seleme Ribeiro  
  
  ![IBM Data Science Professional Certificate](https://s3.amazonaws.com/coursera_assets/meta_images/generated/CERTIFICATE_LANDING_PAGE/CERTIFICATE_LANDING_PAGE~L84DUWCD8F9X/CERTIFICATE_LANDING_PAGE~L84DUWCD8F9X.jpeg)