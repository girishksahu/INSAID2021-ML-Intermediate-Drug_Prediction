# INSAID2021-ML-Intermediate-Drug_Prediction
INSAID 2021 ML Intermediate Term Project
# Project Description
## Introduction
Client for this project is a pharmaceutical company.

They have a long history of making effective drugs and are the leading producer of antibiotics for bacterial infection.
Their research and development team have recently developed five types of drugs to fight against chronic throat infection.

They want to quickly release the drug in the market so that they could cure people and increase revenue for the company.
Their R&D team made a brief analysis of the chemical composition present in the drug and made a brief report stating that each drug has a different effect according to their health.

The drug which has a higher concentration of chemicals should be given to those groups of people whose health report passes some criteria as suggested by the R&D team.

## Current Scenario
The R&D group has invited some groups of people to test the drug, but going through each person’s health report might take a lot of time and cause a delay in launching the drug in the market.

## Problem Statement
The current process suffers from the following problems:

* Testing phase takes a lot of time and it's done manually because they need to carefully examine each person for the side effects.
* Most of the crucial time is being wasted in checking each person’s health report and dispensing specific drugs according to the health metric as suggested by the R&D team.
* This process is time-consuming and wastage of resources.

They want to automate the process of assigning the drug according to their health report.
## Project Task
* Dataset containing the health report of the people from the test group is provided.
* Project task is to build a multi-class classification model using the dataset.
## Project Deliverables
* Deliverable: Drug classification.
* Machine Learning Task: Multi-class classification
* Target Variable: Drug
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the Accuracy Score.
# Data Description
* The dataset contains all the necessary information about the person’s health like their sex, BP, Age, Cholesterol etc.
* We have the health metrics of the person which is an essential factor for transcribing the drug to that person without any side effect.

This is the data that we have to predict for future samples.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 160 rows and 7 columns.
* The last column Drug is the target variable.

## Test Set:
* The test set contains 40 rows and 6 columns.
* The test set doesn’t contain the Drug column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique Id of the sample |
|02| **Age**      | Age of the person|
|03| **Sex**        | The sex of the person(M and F)|
|04| **BP**          | Blood pressure of the person|
|05| **Cholesterol**      | The level of cholesterol in a person's body |
|06| **Na_to_K**           | Sodium and potassium ratio|
|07| **Drug**     | Contains 5 classes of drugs encoded as(drug A : 3, drug B : 4, drug C : 2, drug X : 0, drug Y : 1) |
