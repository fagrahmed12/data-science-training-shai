# Heart Disease Analysis
Heart Disease is considered one of the most common diseases, in addition to the great diversity of its causes and indications (symptoms) of its occurrence, single or combined symptoms, and this makes prediction of its occurrence or its possibility of occurrence very difficult and important in a good analysis of symptoms in order to identify and prevent them.
Hence, the idea of analyzing Heart Disease Dataset and get some insights of it using Python EDA.
## Table of Contents
* [Introduction](#introduction)
* [Dataset General info](#dataset-general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Run Example](#run-example)
* [Sources](#sources)

## Introduction
This project is a part of my training at SHAI FOR AI.
I chose the Heart Disease dataset because of the variety of analytics I can do with its features.
I checked the state of the data of its problems and errors, NaN, duplicated values, and then I determined some outliers that could be removed in the next versions of this notebook, or later when I build the model and  then check its effect on the model, and then I do some EDA on this dataset to understand more about the data and the correlation between features, numerical features density, its ranges, and the correlation between features and dependent variable.
I tested the relationships through many methods, which showed a number of correlation diagrams, whether or not they showed their correlation with each other.

## Dataset General info
General info about the dataset:
* HeartDisease\
Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI)

* BMI\
Body Mass Index (BMI)

* Smoking\
Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes]

* AlcoholDrinking\
Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week

* Stroke\
(Ever told) (you had) a stroke?

* PhysicalHealth\
Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? (0-30 days)

* MentalHealth\
Thinking about your mental health, for how many days during the past 30 days was your mental health not good? (0-30 days)

* DiffWalking\
Do you have serious difficulty walking or climbing stairs?

* Sex\
Are you male or female?

* AgeCategory\
Fourteen-level age category

* Race\
Imputed race/ethnicity value

* Diabetic\
(Ever told) (you had) diabetes?

* PhysicalActivity\
Adults who reported doing physical activity or exercise during the past 30 days other than their regular job

* GenHealth\
Would you say that in general your health is...

* SleepTime\
On average, how many hours of sleep do you get in a 24-hour period?

* Asthma\
(Ever told) (you had) asthma?

* KidneyDisease\
Not including kidney stones, bladder infection or incontinence, were you ever told you had kidney disease?

* SkinCancer\
(Ever told) (you had) skin cancer?

## Technologies
* Programming language: Python.
* libraries: Numpy, Matplotlib, Pandas, Seaborn.
* Platform: Jupyter Notebook.

## Setup
To run this project setup the following libraries on your local machine using pip on the terminal after installing Python:
'''
pip install numpy
pip install matplotlib
pip install pandas
pip install seaborn
'''
To install these packages with conda run:
'''
conda install -c anaconda numpy
conda install -c conda-forge matplotlib
conda install -c anaconda pandas
conda install -c anaconda seaborn
'''

## Features
* Give us a brief and quick overview of the correlations of the dataset.

### To Do:
* Extract ideas from features and combine the features with a comprehensive view.
* Find the most effective and ineffective features.

## Run Example
To run and show correlation between any set of features of the dataset, here is a simple example of it:

* Note: you have to use a jupyter notebook to open this code file.

1. Run the importing stage

2. Run the dataset

3. Select which cell you would like to run and show its output.

4. Run Selection/Line in Python Terminal command (Shift+Enter)

## Sources
This data was taken from (https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)
