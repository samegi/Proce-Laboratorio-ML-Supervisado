# Laboratorio-ML-Supervisado
**Autor:** Sara Mejia Giraldo
**Started:** 28/04/2026
**Last Update:** 17/05/2026
#### Lab: Metrics and Machine Learning with PySpark

## Description

## Proyect Structure

## Requierments

## Variables
| Variable Name | Role | Type | Demographic | Description | Units | Missing Values |
|---|---|---|---|---|---|---|
| age | Feature | Integer | Age | Age of the client. |  | no |
| job | Feature | Categorical | Occupation | type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown') |  | no |
| marital | Feature | Categorical | Marital Status | marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed) |  | no |
| education | Feature | Categorical | Education Level | (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown') |  | no |
| default | Feature | Binary |  | has credit in default? |  | no |
| balance | Feature | Integer |  | average yearly balance | euros | no |
| housing | Feature | Binary |  | has housing loan? |  | no |
| loan | Feature | Binary |  | has personal loan? |  | no |
| contact | Feature | Categorical |  | contact communication type (categorical: 'cellular','telephone') |  | yes |
| day_of_week | Feature | Date |  | last contact day of the week |  | no |
| month | Feature | Date |  | last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec') |  | no |
| duration | Feature | Integer |  | last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.|  | no |
| campaign | Feature | Integer |  | number of contacts performed during this campaign and for this client (numeric, includes last contact) |  | no |
| pdays | Feature | Integer |  | number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)|  | yes |
| previous | Feature | Integer |  | number of contacts performed before this campaign and for this client |  | no |
| poutcome | Feature | Integer |  | 	outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')	 |  | yes |
| y | Target | Binary |  | 	has the client subscribed a term deposit? |  | yes |

## Methodolody
### 1. Preparation
#### 1.1. Setting Up pip Environment Variables
#### 1.2. Initializing the Spark Session
#### 1.3. Loading Data from Hadoop HDFS
### 2. Data Wrangling
#### 2.1. Understanding the variables (Columns)
#### 2.2. Data Types: Consistency and Transformations
- 2.2.1. Initial Structure Review
- 2.2.2. Definition of expected data types
- 2.2.3. Variable transformation
#### 2.3. Null Data Visualization
#### 2.4. Descriptive statistics
### 3. Exploratory Data Analysis (EDA)
#### 3.1. Parameter Distribution
- 3.1.1. Age Distribution
- 3.1.2. Balance Distribution
- 3.1.3. Day Distribution
- 3.1.4. Duration Distribution
- 3.1.5. Campaign Distribution
- 3.1.6. Pdays Distribution
- 3.1.7. Previous Distribution
#### 3.2. Correlation
#### 3.3. Pairplot Analysis
#### 3.4. Binary Variable Distribution
- 3.4.1. Default Distribution
- 3.4.2. Housing Distribution
- 3.4.3. Loan Distribution
#### 3.5. Distribution of Categorical Variables

https://archive.ics.uci.edu/dataset/222/bank+marketing
