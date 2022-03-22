# Module 3 Project

* Student name: **Will Dougherty**
* Student pace: **self paced**
* Scheduled project review date/time: **18 March 2022, 2:00-2:45 PM**
* Blog post URL: **TBD**
* Presentation Video URL: **TBD**

## Description

In this project I will be tackling the Tanzanian Water Pump dataset, provided by a DrivenData competition. I will use the methodologies I have learned in Module 3 to analyze, clean, and model this data to produce a workable model that can predict the functionality of water pumps in Tanzania.

I will approach this with a set of business goals created to simulate how I would be interacting with this problem in the real world.

## Business Problem

Due to limited resources, and the vast size of Tanzania, it is hard to get up-to-date information on water pump functionality. As well, they cannot all be inspected, repaired, and replaced comprehensively.

### Goals:

1) Build a model to predict **non-functionality** in pumps - that is, pumps that are not fully functional, and are in need of repair or replacement. As we already have data on the functionality of the pumps in this dataset, we need to be able to predict functionality of pumps for which we do not have good functionality data.

2) Advise on the most efficient use of this model and pump predictions to best use our limited resources to repair and replace water pumps.

## Dataset and Methodology

There are nearly 75,000 data points representing as many water pumps spread over the entire nation of Tanzania. The data provided consists of a training set of 59,400 pumps which includes their status_group (target variable) data, and a test set of 14,850 pumps without status_group data. 

After EDA/data cleaning/feature engineering/feature selection/encoding, I will try out different modelling packages, tune the best ones, and create a final model. The goal is to have a good **recall** score, so as to correctly identify as many of the non-functional pumps as possible.

After this, I will develop a plan for implementing this model and its predictions, so as to efficiently allocate resources throughout Tanzania.