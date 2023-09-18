# Byssinosis_Data_Analysis

![](images/plant-4645684_1280.png)

## Introduction

Welcome to the Byssinosis Data Analysis Report repository. In this report, we analyze the "Byssinosis.csv" dataset, a collection of data from a cotton textile company in North Carolina, as part of a study to investigate the prevalence of byssinosis. Throughout our analysis, we aim to understand the factors that influence the occurrence of byssinosis in the workplace.

## Data Description

The dataset comprises seven variables, including two numerical variables and five categorical variables. Our analysis begins with graphical exploration to visualize the interactions between variable factors, providing initial insights into the dataset.

## Findings 

From our analysis, we observed several key findings:

1. High-Risk Factors: Workers who are male, of other races, smokers, and have worked for more than 20 years in dusty workplaces are more likely to develop byssinosis.

2. Model Selection: To identify the best-fit model, we employed stepwise forward regression with AIC (Akaike Information Criterion) and evaluated it against the saturated model using LR tests, null deviance statistics, Chi-square p-values, and log-likelihood differences. This rigorous testing process confirms that our chosen model is well-suited to the dataset.

3. Impactful Variables: Our fitted model demonstrates that workspace conditions, smoking status, and employment period significantly influence the likelihood of byssinosis.

4. Conclusion: Ultimately, our analysis concludes that individuals who smoke and have worked in dusty environments for over 20 years are at the highest risk of developing byssinosis compared to other factory workers.

## Conclusion

In summary, the relationships between byssinosis and various factors such as smoking status, sex, race, length of employment, and dustiness of the workplace were not immediately evident from initial observations and plots. However, through the application of rigorous statistical tools and model selection techniques, we have uncovered meaningful associations within the dataset.

This repository contains the code used for the analysis, the dataset ("Byssinosis.csv"), and this README file to provide an overview of the project's findings and conclusions.

Thank you for your interest in our analysis. If you have any questions or require further information, please feel free to reach out.