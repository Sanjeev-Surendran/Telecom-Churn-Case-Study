# Telecom Churn Case Study
A case study to solve a business problem by building a machine learning model to predict if a telecom customer will churn or not.
* Comprehend the given data set and perform Exploratory Data Analysis (EDA) to analyse the data set.
* Build a prediction model to identify the best fit variables that can predict the churning probability more accurately.

## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)

### General Information
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

#### Data Set Brief Information
The data set contains information about the customer and details of their respective telecom usage.
A data dictionary is provided along with the data set to understand various terms and variables used.

#### Business Objective
Analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

#### Business Solution
Build a machine learning model that is able to predict churning customers based on the features provided and their respective usage.


### Project Contents
* **Telecom Churn Case Study.ipynb** - Jupyter Notebook for Telecom Churn Case Study (Language : Python)
* **train.csv** - Data Set for training model
* **test.csv** - Test data for prediction using trained model
* **solution.csv** - Predicted Result from Test data
* **sample.csv** - Expected Result from Test data
* **data_dictionary.csv** - Data Dictionary
* **README.md** - Readme file


### Conclusion
Any business analytics problem can be solved using **CR**oss **I**ndustry **S**tandard **P**rocess for **D**ata **M**ining (CRISP-DM) model.
* Data set was analysed and prepared for EDA. EDA was done on data set to understand the relationship between variables.
* Various machine learning models was built with and without PCA to predict if a customer will churn or not
* Models performed well without PCA.
* GBoost and XGBoost without PCA outperformed all models
* XGBoost was selected for final prediction

#### Recommendation
XGBoost without PCA gives good prediction results

#### Top 5 features
* total_ic_mou_8 - 0.1745
* loc_ic_mou_8 - 0.0863
* roam_og_mou_8 - 0.0748
* av_rech_amt_data_8 - 0.0279
* monthly_2g_6 - 0.0218

These features helps in realizing if a customer will churn or not.


### Software and Library Versions
* ![Jupyter Notebook](https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=4.9.2&color=blue&labelColor=grey)

* ![NumPy](https://img.shields.io/static/v1?label=numpy&message=1.21.5&color=blue&labelColor=grey)

* ![Pandas](https://img.shields.io/static/v1?label=pandas&message=1.4.2&color=blue&labelColor=grey)

* ![matplotlib](https://img.shields.io/static/v1?label=matplotlib&message=3.5.1&color=blue&labelColor=grey)

* ![seaborn](https://img.shields.io/static/v1?label=seaborn&message=0.11.2&color=blue&labelColor=grey)

* ![statsmodels](https://img.shields.io/static/v1?label=statsmodels&message=0.13.2&color=blue&labelColor=grey)

* ![sklearn](https://img.shields.io/static/v1?label=sklearn&message=1.0.2&color=blue&labelColor=grey)


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->
