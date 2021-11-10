# School Projects

## Project 1 - Relationship between sentiments in SoMe and the stock market 

### Including
  - Scraping [Reddit](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter/blob/main/DataCollection/Tools/ScrapeForChosenStock.ipynb) and [Twitter](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter/blob/main/DataCollection/Tools/Twitter_Webscraper.R) with API's
  - Transforming half a million rows of unstructured text data to structured
    - Making the Twitter and Reddit data compatible and [appending the data](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter/blob/main/DataCleaning/Tools/Appending_Prep_Twitter.R)
  - Feature engineering with the use of [natural language processing](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter/blob/main/PreProcessedData/PreProcessingScript.R)  
  - [Classifying stock movements](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter/blob/main/DataModelling/Modelling.R) using, but not limited to:
    - Random Forest
    - Extreme gradient boosting
    - Support vector machines
    - Logistic regression

### Description
The project is made in cooperation with 3 other university students.   
Analyzing whether stock movements can be predicted in the short term. We are doing this by collecting data from the platforms Twitter and Reddit. We retrieved data from tweets regarding certain stocks and posts/comments on subreddits involving investing, i.e. "WallStreetBets", "SecurityAnalysis" and "Investing". By using natural language processing to determine the sentiment in relation to the specific stocks, and comparing this to the actual market valuations of these stocks, to predict whether the price goes up or down. Predicting for stock movements in the hours after the posts have been posted. 


[Link to the project](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter) 


## Project 2 - Exam from first semester of Machine Learning (Grade: A)

### Including
  - Transforming variables
  - Exploring the data, distributions etc.
  - Feature engineering of variables
  - Classifying fraud using:
    - Linear regression
    - Logistic regression
      - AIC step models
    - LDA and QDA
    - Bayesian model averaging
    - Bayes naive classifier

### Description
This is my exam from Machine Learning 1 at my first semester of my masters. The exam was a 4-hour exam, where we got a data set and a set of questions to answer.
The exam main objective was fraud detection of suspicious firms. The data was a cross-section of 1550 observations containing 12 variables and was collected over a 1 year period. The data contained both ordinal, continuous and binary data.  

[Link to the project](https://github.com/MikkelGraugaard/Machine_Learning1_Exam) 


# Internship Projects

## Project 1 - Vessel Performance Analytics

### Including
 - Power BI
 - SQL
 - SQL SSAS (DAX)

### Description
Responsible for frontend of the product in Power BI and calculating business measures with DAX.


## Project 2 - Handball Analytics

### Including
 - SQL
 - SQL SSAS (DAX)
 - Power BI
 - Python
    - Pandas
    - Numpy
    - OpenCV
  - Tensorflow
  - PyTorch
  - Scikit-learn
  - Keras

### Description
Creating the backend data warehousein SQL, frontend in Power BI and Computer Vision with Python


# Student Work Projects

## Project 3 - Creating business KPI's using VBA and Visualization in Power BI
*Unfortunately due to GDPR I can't show much of the project, this includes the data and report/visualizations*

### Including
- Creating business rules to make KPI's
- Using VBA in excel to create functions for automation of KPI calculations
- Creating KPI's for reporting
- Handling, cleaning and merging data sets of roughly 30.000 rows
- Visualizing the data for reporting using Power BI

### Description
Using the knowledge I got of the business and data in my position as a student assistant for the IT-asset manager, to clean our existing data of computer hardware in the organization, consisting of around 20.000 active laptops and 16.000 retired laptops. Creating KPI's from the existing data to evaluate what should happen with every individual computer in terms of: Being delivered back to the central unit for redistribution, being retired to the leasing company, being renewed or being disposed. 

The KPI's were created using different excel formulars and creating a function in VBA to classify the different computers to the right categories, depending on 8 different factors and giving the reason for the classification in the output.  

I then visualized the added KPI's in Power BI so the different finance departments, could get a grip of how many computers to renew each quarter and the cost of this. Also making it easy to track the specific computers as the data was connected with the users. 
Overall leaning the IT-assets as the amount of resources used on the IT hardware assets, both in terms of time spend in all departments and the total amount of money, as unused computers easily could be tracked and returned. 

[Link to VBA used](https://github.com/MikkelGraugaard/Mock_Work_project_KPI_creation)  
[Link to some DAX code used](https://github.com/MikkelGraugaard/DAX)


## Project 4 - Automating Cost Allocation of Invoices
*Unfortunately due to GDPR I can't show the actual project data*

### Including
- Analyzing the invoices to find pattern in data
- Creating a VBA macro
  - Using loops
  - Finding specified text in invoice
  - Copying the invoice amount if containing specified text
  - Decomposing the invoice into categories to be invoiced to other departments

### Description
Every month we receive a huge invoice, approximately 90 pages. The invoice has to be allocated to all the different departments in the municipality. This means that a person has to read the invoice line for line and copying the right data/costs to an allocation excel sheet. 
This takes approximately 6-9 work hours per month for an individual. 

I made a VBA macro that finds the categories in the invoice and copies the data/costs to specified columns in excel and cross checking if the total matches. This reduces the task of allocating the invoice to approximately 10-15 minutes, thus saving a lot of recourses per year.  

[Link to VBA used](https://github.com/MikkelGraugaard/Mock_Work_project_Invoive_Automation) 
    

