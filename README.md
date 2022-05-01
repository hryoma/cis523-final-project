# CIS 523 Final Project - Differential Privacy and Fairness in Machine Learning

## Overview
The pay gap is the result of many factors, including race and ethnicity, disability, access to education and age and different groups experience very different gaps in pay. “Data Scientist” is one of the hottest jobs on the market today and we are interested in building a fair model to best predict the compensation of a data scientist by applying or referencing the algorithms and mechanisms in the [Fairlearn package](https://fairlearn.org/).

Dataset: Over 60,000 data scientist salaries were scraped from levels.fyi along with some information about the employee submitting the data. The dataset contains information about the name of the company, level and title of position, total yearly compensation, location, year of experience, years at the company, job functionality, gender, education background, and race. The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries).

Given the amount of personal information disclosed in the dataset, we are applying a differential privacy mechanism (for example, adding noise) from the OpenDP’s toolkit. We are also considering using a TensorFlow library to implement the differential privacy with the machine learning model.

