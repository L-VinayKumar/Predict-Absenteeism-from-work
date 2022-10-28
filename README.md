
# **To Predict the predominant reason for absenteeism from work**

In this project, I want to share what is the most frequent reason that employees has stated which had much higher chance of getting excessive absence. To solve that problem I use data analytics to describe the pattern and predict which employee will absent using regression method (supervised learning).




![App Screenshot](https://thumbs.dreamstime.com/b/letter-block-word-absent-wood-background-another-alphabet-as-frame-167167738.jpg)
For full report of this project, please visit: [Absenteeism](https://github.com/L-VinayKumar/Predict-Absenteeism-from-work/tree/main/Predict-Absenteeism)
## Summary Process
Table of Contents:

    1. Problem / Object Statement
    2. Data Extraction
    3. Data understanding
    4. Installation
    5. Exploratory Data Analysis
    6. Data Preprocessing
    7. Final CheckPoint
    8. Building Model
    9. Testing Model
    10. Conclusion

### Problem Statement:
From a business perspective, employees who are not present to do their jobs, will cost more than they should. The absence is a big problem because it reduces output and is annoying because it requires rescheduling and changing programs which is one of the contributing factors to the failure of a department's organization to meet performance targets.

### Objective:
Based on these problems, this analysis is carried out to predict the predominant reason for employees absenteeism from work. To get answers to these problems, an analysis is carried out using supervised machine learning: Logistic regression.

## Data understanding

•	ID : Individual identification

•	Reason of absence : Reasons 1-21 are registered in the International Classification 

•	Date : Date of Absence

•	Transportation Expense : Cost related to business travel (fuel, parking, meals, etc)

•	Distance to work : Distance measured in km

•	Age : Years of age

•	Daily workload average : Measured in minutes

•	Body Mass Index : Number based on your weight and height

•	Education : Representing different levels of education

•	Childern : Number children in the family

•	Pets : Number of pets in family

•	Absenteeism time in hours : Target
       




## Installation

To install the libraries used i this project. Follow the below steps

```bash
 pip install pandas
 pip install sklearn
 pip install numpy
 pip install seaborn
 pip install matplotlib
```

## Exploratory Data Analysis
At this stage, a brief analysis of the data will be carried out,

    1. Data Distribution - Histogram
    2. Boxplot
    3. Data Correlation
![Logo](https://github.com/L-VinayKumar/Predict-Absenteeism-from-work/blob/main/Predict-Absenteeism/Data-Corr.png?raw=true)


## Data Preprocessing

At this stage, data preparation and processing will be carried out before being used as a data model

    1. Encode
    2. Casting Data Type
    3. Categorization
    4. Extract Date feature
    5. Final Checkpoint

## Model Building

* Preprocessing the new Dataset
* Creating the Targets
* Standardize the data
* Logistic regression model is used for prediction

## Prediction Results

At this stage, new data set will predict with selected model before,

* Predict New Dataset:![Logo](https://github.com/L-VinayKumar/Predict-Absenteeism-from-work/blob/main/Predict-Absenteeism/Standardize-Data.png?raw=true)

## Conclusion

We Conclude our results:

![Logo](https://github.com/L-VinayKumar/Predict-Absenteeism-from-work/blob/main/Predict-Absenteeism/Conclusion.png?raw=true)

### From the Conclusion, it seems that whenever a person has stated reason 3, we have a much higher chance of getting excessive absence
#### Reason 3 = Poisoning
#### Reason 1 = Various diseases
#### Reason 2 = Pregnancy and giving birth
#### Reason 4 = Light diseases
