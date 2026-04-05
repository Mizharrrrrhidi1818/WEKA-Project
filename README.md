# Overview
This project implies WEKA (Waikato Environment for Knowledge Analysis) which is open-source application. We will learn fundamental about WEKA SOFTWERE.

# Objective
**A. WEKA EXPLORER**
1. Which file formats does WEKA support?
2. what is the ARFF format and what form does it take?

**B. Data Set for Analysis**
1. Search the repositories to select a dataset for analysis
- UC Irvine Machine Learning Repository -https://archive.ics.uci.edu/datasets
- Kaggle Repository-https://www.kaggle.com/datasets?fileType=csv
2. Prepare data for analysis, if necessary
- discrete values of attributes
- no missing values

**C. Association Rules**
1. Save the dataset you selected in the previous lab in ARFF format
2. Use WEKA to generate the statistics for this dataset
3. After loading your database into WEKA, go to the Associate tab and run the algorithm with the default parameters. What results did you get? Check other parameter settings of the algorithm
4. How does the number of rules change when the values of support and confidence increase?
5. Interpret obtained results

**Feature Selection and Attribute Ranking**
1. Prepare your selected data set in ARFF format (if possible, use the data sets from the Previous laboratory).
2. Generate two rankings using two different ranking methods. Describe in detail what parameters were used to generate the rankings: Justify why the selected parameters were used.
3. Compare the effectiveness of classification models (e.g., decision trees) using the full set of features and the reduced set based on the ranking. Perform this comparison for both generated rankings.
4. Select one of the rankings and evaluate the classification model by sequentially eliminating the attributes placed at the lowest position in the ranking and creating reduced data table. Indicate the smallest number of attributes that allows you to obtain the highest classification quality.
5. Assess the stability of rankings Do different algorithms generate similar feature rankings for the same data set? Which features are most important in the context of the selected data set?


