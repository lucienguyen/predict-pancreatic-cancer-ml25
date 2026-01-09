# Classifying pancreatic cancer with biomarker data

This project focuses on medical diagnostics using machine learning to distinguish between healthy individuals, patients with non-cancerous pancreatic conditions, and those with pancreatic cancer using urinary biomarker data. 


This project is done in the course Machine Learning D at Aalto University. 


**Grade: 100/100**

### Data source
This project utilizes the Pancreatic Cancer Biomarker Dataset originally published by Debernardi et al. (2020), which contains measurements of specific proteins in urine samples from 590 patients across three diagnostic categories:
- Healthy controls (183 samples)
- Benign pancreatic diseases (208 samples)
- Pancreatic ductal adenocarcinoma (PDAC) (199 samples)


The goal was to develop an accurate, non-invasive screening tool for early pancreatic cancer detection using machine learning classification.

### Results
After evaluating the data (i.e., processing missing values, and selecting features), Multinomial Linear Regression and Random Forest are implemented in this task in 5 folds cross validation. RF outperformed MLR in classification accuracy, with 77% in multinomial (healthy, benign, and cancerous) and 90% in binary (cancerous or non-cancerous) classification problem. Highest confusion occurred between healthy and benign cases, possibly because of biological similarities. The level of Plasma CA19-9 and REG1A were most predictive features in this task. 
