# ASHRAE---Great-Energy-Predictor-III---Kaggle-

ASHRAE---Great-Energy-Predictor-III

## Introduction

The objective of the ASHRAE---Great-Energy-Predictor-III challenge is to create the best model to answer the following question: how much does it cost to cool a skyscraper in summer? The challenge is to use the energy data for the entire building to create a model that estimates the energy consumption of the building using a fantastic set of energy consumption data in more than 1000 buildings. The model should predict how much energy a building would have consumed if it had not implemented an energy efficiency project.

The challenge is hosted Kaggle platform. it has been frequented by a growing community of Data scientists for many years. Kaggle is a web platform that organizes competitions that challenge anyone with machine learning skills to build the best model for predicting all kinds of things. Looking at the list of currently active competitions, you'll see everything from forecasting the number of yards an NFL player will earn after receiving a transfer to forecasting selling prices for real estate. The platform makes it possible to provide Datasets for a competition, offers users the possibility of sharing notebooks which detail their work step by step, accepts results submissions, maintains the rankings and discussion forums.
## Dataset

building_metadata.csv (6 columns)
sample_submission.csv(2 colones)
test.csv (4 columns)
train.csv(4 columns)
weather_test.csv(9 colones)
weather \ _train.csv(9 colones)

This Dataset can be downloaded by the following command  : kaggle competitions download -c ashrae-energy-prediction

In this project, we will explore and execute our code with Kaggle Python Notebook which is a cloud computing environment which allows a reproducible and collaborative analysis in which the code is a Python script.

## Code
{Step 1:} ***********

Import libraries
Import of Dataset
Explore the Datset
{Step 2:} *********** 
Data processing
Fix timestamp
Replace missing data
Merge data sets
Reduced memory usage
Data processing for building dataset
Data processing for weather dataset

{Step 3:} *********** 
train Dataset processing

Merged data
Reduced memory usage
{itemize}
textbf {Step 4:} *********** 
Creation of models
keras Neural Network
K-Fold
LSTM Network
{Data reFormatting}
To run the LSTM neural network, the data must have a three-dimensional shape where the axis corresponds to the following data: \\
$ * $ x-axis time steps 
$ * $ y-axis data examples 
$ * $ z-axis features for single point in time 
textbf {Step 5:} *********** 
 Creation of submission.csv


