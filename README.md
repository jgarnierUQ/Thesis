# Overview
My thesis was a piece of biomedical research at the University of Queensland. I investigated the relationship between Obstructive Sleep Apnea (OSA), and Hypertension using Machine Learning. My specific goal was to determine if there were any characteristics of OSA that were highly associated with hypertension, that previous research methods had not yet uncovered. At the end of the project, I was left with a newfound knowledge of OSA, working with large datasets, and applying Machine Learning algorithms to extract useful information from data. I used MATLAB and Python for all the coding aspects of the project.

## Dataset
I used a pre-existing dataset from the Sleep Heart Health Study (SHHS). This study contains data from over 5,804 adults aged 40 and older, who were subjected to an overnight polysomnogram and were followed up for over 10 years later monitoring for cardiovascular disease outcomes. Each sample has over 1800 features.
https://sleepdata.org/datasets/shhs

## Method
As a brief summary, here is how I tackled this project:
- Decided to make this a classification problem rather than regression
- I first selected features based off previous literature that were relevant to OSA and Hypertension
- I used feature selection techniques to narrow down which features to use in my Machine Learning algorithms
- I tested certain a range of algorithms with all of these base features to determine which ones gave the best performance to focus on
- I then chose to look further into a certain algorithm and begin modifying which features were used to see if there were any connections or massive increases/decreases in the models performance
- Analysed results and made conclusions from there

## Results
Comparing classifiers led to the decision to focus on a Logistic Regression model.
<img src="https://github.com/jgarnierUQ/Thesis/blob/main/pictures/rocComparison.png" alt="drawing" width="700"/>

From comparing many different Logistic Regression models using different subsets of features, no single feature stood out above the rest and all models performed very similarly.

<img src="https://github.com/jgarnierUQ/Thesis/blob/main/pictures/logisticRegressionROCCurves.png" alt="drawing" width="700"/>

From looking at the table of coefficients of the highest performing model, the following variables all had p-values < 0.05 which meant they had statistical significance and affected the outcome of whether or not a patient had hypertension or not.

<img src="https://github.com/jgarnierUQ/Thesis/blob/main/pictures/tablecoeefsTable.PNG" alt="drawing" width="700"/>

## Summary
This project was extremely interesting to me as I got to learn all about Machine Learning, data analysis, OSA and Hypertension, and how important a good nights sleep is!
Obviously there was a lot more that went into this project than what is shown in this README file, I have attached my demonstration poster which has a better summary of the entire project, and I am more than happy to talk about anything further that you may be curious about!
