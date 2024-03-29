# Recommendation System using Market Basket Analysis for Retailers

## Overview 

The proposed project aims to implement a comprehensive recommendation system with an MBA that retailers can easily use to influence customers through recommendation plans with forecasting capabilities. Leveraging advanced pattern mining techniques on transactional data, the system aims to uncover hidden associations between products to enhance the customer experience by increasing the sales through personalized recommendations and by forecasting future purchase behaviors.

## App Demo
[Click me for User App](https://market-basket-analysis-group17.streamlit.app/)

## Dataset

For this we have used dataset 
Dataset: (https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis/data)

## Problem

Nowadays, many medium scale retailers struggle to formulate sales plans and have little interest in leveraging customer purchase behaviors to influence sales. This reluctance may be because of various factors:
-Financial constraints preventing investment in data scientists.
-Inadequate data collection processes.
-Not having knowledge of the data science approaches which leads to enhance sales
Consequently, retailers lack proper incentive plans, sales forecasting capabilities, and inventory management strategies. Due to the above mentioned factors, retailers have comparatively less sales on their products.

## Solution

In the initial stage, we are going to use the following dataset, which includes transactional data captured over by the retailer. Each row of this dataset represents a unique transaction, with columns indicating the BillNo, Date, and the items purchased in that transaction.
Our system will utilize the insights gained from this analysis to improve customer engagement, enhance the shopping experience, and identify patterns in customer behavior.
The proposed system will consist of the following features:
1. Pattern Mining Algorithms: Utilize advanced pattern mining algorithms such as Apriori or FP-Growth for Market Basket Analysis.
2. Recommendation Engine: Implement collaborative filtering or content-based filtering techniques for personalized recommendations.
3. Identifying Seasonal Products: Using time series methodologies for discovery trends, seasonalities.

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/MBA-Retailers/mba-project.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mba-user python=3.9 -y
```

```bash
conda activate mba-user
```
### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
streamlit run streamlitapp.py
```
Now,
```bash
open up you local host and port
```
