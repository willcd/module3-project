# Module 3 Project

* Student name: **Will Dougherty**
* Student pace: **self paced**
* Scheduled project review date/time: **18 March 2022, 2:00-2:45 PM**
* Blog post URL: **TBD**
* Presentation Video URL: **TBD**

## Description

This project will be tackling the Tanzanian Water Pump dataset, provided as part of a DrivenData competition. I will use the methodologies I have learned in Module 3 to analyze, clean, and model this data to produce a workable model that can predict the functionality of a water pump on a level competitive with the best models in the competition.

In addition, I will approach this with a set of business goals created to simulate how I would be interacting with this problem in the real world.

## Business Problem

As a data scientist for the Tanzanian Government, I am tasked with:
* Building a predictive model for water pump functionality
* Identifying efficient ways of allocating resources to inspect/repair pumps
* Make recommendations for future data collection/cleanup to create better data sets and models

## Dataset and Methodology

There are nearly 75,000 data points representing as many water pumps spread over the entire nation of Tanzania. The data provided consists of a training set of 59,400 pumps which includes their status_group (target variable) data, and a test set of 14,850 pumps without status_group data. 

Thus, all eda / cleaning / initial modelling will be done with the training set to prevent data leakage, and once decisions have been made as to methodology, the test set will be used at the end to create the submission to be scored on the DrivenData website.
