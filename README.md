# IBM HR ANALYTICS - EMPLOYEE ATTRITION

## PROJECT DESCRIPTION

![Alt text](https://github.com/elvis-darko/EMPLOYEE-CHURN--SQL-POWER-BI-PYTHON-/raw/main/Assets/images/ibm_1.webp)

This project is for International Business Machines, popularly known as IBM. It was reported that there have been an increase in the rate at which employees are leaving the company. As Data Analysts at IBM, we are tasked to undertake deep data exploration and analysis to gain insights into employee characteristics and develop machine learning models that will accurately predict the likelihood of an employee leaving the company.

The solution will help the HR department develop policies that will raise employee morale and overall satisfaction. This will help reduce the rate at which employees are leaving the company.

Data Analysis is done using SQL. Visualizations are made using Microsoft Power BI. Additionally, python is used to undertake further analysis and machine learning modeling. A Streamlit App and Fast API app will be built to deploy the best performing models on the web. These apps will help the HR department determine employees who will likely leave in the near future based on the various factors given.


## SUMMARY
| Code      | Name        |   Deployed App |
|-----------|-------------|:------|
|TZ 1       | IBM EMPLOYE CHURN  | STREAMLIT APP<br />FAST API APP|



## NOTES ON DATASETS
This the data about the employee on various factor influencing the attrition from the company.
<br />
 This is a fictional data set created by IBM data scientists.

| Variable      | Definition | Data Type |
|:-----------|:------------|:------------|
|Age |Age of the Employee| int |
|Attrition | Employee who stayed: 0 , Employee who leave: 1| int |
|BusinessTravel: |Frequency of travels | object |
|DailyRate | Daily Rate of Employee | int |
|Department | Department to which employees belong to | object |
|DistanceFromHome | Distance from home from work for each Employee | int |
|Education | Education level of employees | object |
|EducationField : Education fields of employees | object |
|EnvironmentSatisfaction | Satisfaction towards work environment | int |
|Gender | Gender of employees | object |
|HourlyRate | Hourly Rate of Employee | int |
|JobInvolvement | Rate at which employee is involved with work | int|
|JobLevel | The hierarchical level of employee's role | int |
|JobRole | Role of employee | object |
|JobSatisfaction | Level of employee satisfaction towards current role | int |
|MaritalStatus | Marital status of employee | object |
|MonthlyIncome | Montly income of Employe between 2094 and 26999 | int |
|MonthlyRate   | Monthly bonus of employee | int |
|NumCompaniesWorked | Number of Companies the employee has worked with before the current one | int |
|Over18 | Age of employee being above 18 years | object |
|OverTime | Employee working additional hours | object |
|PercentSalaryHike | Percentage of Salary increase between 11%-25% | int |
|PerformanceRating | Rating of employee performance | int |
|RelationshipSatisfaction | Employee satisfation of relationship with current manager | int |
|StandardHours | standard work hour for each employee: 80 Hours | int |
|StockOptionLevel | It categorized from 0 to 3 indicate the stock level of employee | int |
|TotalWorkingYears | Employee`s total working years and it varies between 0 to 40 years | int |
|TrainingTimesLastYear | Employee`s training time in the last year | int |
|WorkLifeBalance | The work-life balance of employee | int |
|YearsAtCompany | Employess`s total working year at the company adn it varies between 0 to 40 years | int |
|YearsInCurrentRole | Employee`s number of years of holding current position at the company and it varies between 0 to 18 years | int |
|YearsSinceLastPromotion | The time the employee got the last promotion and it varies between 0 to 15 years | int |
|YearsWithCurrManager | Number of years employee has worked with current manager and it varies between 0 to 17 years | int |

## SCREESHOTS OF DEPLOYED APPS


## SETUP
It is recommended to have Virtual Studio Code or any other standard code editor on your local machine.<br />Install the required packages locally to your computer.

It is recommended that you run a python version 3.0 and above. 
You can download the required python version from [here](https://www.python.org/downloads/).

Use these recommended steps to set up your local machine for this project:

1. **Clone the repo :** To clone this repo, copy the url and paste it in your GitHub desktop or code editor on your local machine.
        
        https://github.com/elvis-darko/EMPLOYEE-CHURN--SQL-POWER-BI-PYTHON-.git

1. **Create the Python's virtual environment :** <br />This will isolate the required libraries of the project to avoid conflicts.<br />Choose any of the line of code that will work on your local machine.

            python3 -m venv venv
            python -m venv venv


2. **Activate the Python's virtual environment :**<br />This will ensure that the Python kernel & libraries will be those of the created isolated environment.

            - for windows : 
                         venv\Scripts\activate

            - for Linux & MacOS :
                         source venv/bin/activate


3. **Upgrade Pip :**<br />Pip is the installed libraries/packages manager. Upgrading Pip will give an to up-to-date version that will work correctly.

            python -m pip install --upgrade pip


4. **Install the required libraries/packages :**<br />There are libraries and packages that are required for this project. These libraries and packages are listed in the `requirements.txt` file.<br />The text file will allow you to import these libraries and packages into the python's scripts and notebooks without any issue.

            python -m pip install -r requirements.txt 

## MACHINE LEARNING MODEL DEPLOYMENT
### Run Streamlit App
A streamlit app was added for further exploration of the model. The streamlit app provides a simple Graphic User Interface where predicitons can be made from inputs.

- Run the demo app (being at the root of the repository):
        
        Streamlit run streamlit.app.py

### Run Fast API App

## EVALUATION
The evaluation metric for this challenge is Area Under the Curve (AUC).

The values can be between 0 and 1, inclusive. Where 1 indicates an employee who churned and 0 indicates an employee who stayed with IBM.

Our final work would look like this:

            employee_id                                   CHURN
            001                                           0.98
            002                                           0.12
            003                                           0.37


## RESOURCES
Here are some ressources you would read to have a good understanding of tools, packages and concepts used in the project:
- [How to improve machine learning models](https://neptune.ai/blog/improving-ml-model-performance)
- [Machine Learning tutorial - A step by step guide](https://github.com/eaedk/Machine-Learning-Tutorials/blob/main/ML_Step_By_Step_Guide.ipynb)
- [Create user interfaces for machine learning models](https://www.youtube.com/watch?v=RiCQzBluTxU)
- [Getting started with Streamlit](https://docs.streamlit.io/library/get-started)


## CONTRIBUTORS
| NAME  |   COUNTRY |   E-MAIL  |
|:------|:----------|:----------|
|ELVIS DARKO|GHANA|elvis_darko@outlook.com|
|           |       |           |
|           |       |           |


