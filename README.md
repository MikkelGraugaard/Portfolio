# School Projects

## Project 1 - Relationship between sentiments in SoMe and the stock market 

### Including
  - Scraping Reddit and Twitter with API's
  - Transforming half a million rows of unstructured data to structured
  - Feature engineering with the use of natural language processing
  - Classifying stock movements using, but not limited to:
    - Random Forest
    - Extreme gradient boosting
    - Support vector machines
    - Logistic regression

### Description
The project is made in cooperation with 3 other university students.   
Analyzing whether stock movements can be predicted in the short term. We are doing this by collecting data from the platforms Twitter and Reddit. We retrieved data from tweets regarding certain stocks and posts/comments on subreddits involving investing, i.e. "WallStreetBets", "SecurityAnalysis" and "Investing". By using natural language processing to determine the sentiment in relation to the specific stocks, and comparing this to the actual market valuations of these stocks, to predict whether the price goes up or down.


[Link to the project](https://github.com/DataScienceProjectUni/PredictStockusingRedditandTwitter) 



# Student Work Projects

## Project 2 - Creating business KPI's using VBA and Visualization in Power BI
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

#### VBA Code Example 

[Link to VBA used](https://github.com/MikkelGraugaard/Mock_Work_project_KPI_creation)


## Project 3 - Automating Cost Allocation of Invoices
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

#### VBA Code Example 

[Link to VBA used](https://github.com/MikkelGraugaard/Mock_Work_project_Invoive_Automation) 
    

