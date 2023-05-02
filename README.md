# PythonGroup Project
Python For Data Analysis - Spring 2023
Problem Statement You are given two datasets: - left_dataset.csv - right_dataset.csv These datasets contain business names and their addresses. The goal of this project is to find the businesses that are common to both datasets, that is, the businesses that have a name and address that match between the left and right datasets.

These datasets come from different sources and so there may be some subtle differences between records, even if they do refer to the same business.
Since the business names and addresses don't align perfectly between these datasets, you will need to develop an algorithm that can find approximate matches. When your algorithm runs, it should produce a list of triplets consisting of the entity_id from the left dataset, the business_id from the right dataset, and a confidence score. The confidence score should have values between 0 and 1.0 and convey a sense of confidence of the match. An identical match should have a score of 1.0. Your submission should consist of matches that have a high degree of confidence, eg greater than 0.8. 

The technical work that you are expected to conduct as part of this project is: 
- conduct exploratory data analysis to understand the data, including visualizations 
- develop an algorithm that can produces matches across both datasets 
- assign a confidence score to your matches Your algorithm should take no more than a few hours to run, ie you should not implement a brute force Order N^2 matching algorithm. 

**Deliverables** 
○ **Python code: **
EDA_and_Visualization.ipynb  - contains EDA
FinalCode.ipynb - contains EDA and algorithm for best matches
○ Finalmatches.xlsx - csv that contains the match IDs and confidence score 
○ presentation deck - Team 87 Group Project Presentation

