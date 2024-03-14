# Ultratherapeutics Patient Satisfaction Analysis

Task 1 -Data Exploration and Preprocessing

Introduction:-

This project focuses on analyzing patient satisfaction surveys in the field of different treatment with ultratherapeutics, with the different type of rating to improve healthcare service quality.
Focused on understanding patient perceptions, experiences, and outcomes to advance treatment methodologies.

## Dependencies

Using Following external libraries are required to run the Jupyter Notebook:

Pandas,
Numpy,
Matplotlib,
Seaborn

## Setup Instructions:

Open the Jupyter Notebook:
Launch the Jupyter Notebook application using this command.

Install Dependencies:
installs the required Python libraries.

Load The Data Sets:
Loading the data sets in Jupyter Notebook.

Run the Cell in Jypiter Notebook:-
(commonly Shift + Enter) used for the Running a cell in Jypiter Notebook.

## Usage

i have the required Dataset ('patient_satisfaction_ultratherapeutics.csv') form the client.
following the instructions witin Notebook to Load the Data and interepting the result.

## Schema Mapping Explanation:

1. Loading Data:
Utilizes pandas to load the datasets.

2. Data Cleaning:
Before go through the Analysis of the data, using some `info` and `describe` mehtod to understand the data structure.

first part of analysis in data Cleaning i remove the missing values from the data sets by using `dropna` method and finding there is no any missing values find in the datasets.

finding outliers -
There are three columns in which there is possibility for the outliers ((Wait Time) Column / Wait Time (minutes) Column / Age Column).
after check all three columns and find that there is no outliers in the Dataset.
So after that i check My dataset is cleaned.

3. Visual Analysis on The Dataset:
using `matpolotlib` and `seaborn`, getting some interesting insights from the Data. There are 6 graphs to get the better undestand the inights from the Data.

#### Gender Vs Treatment type

#### Gender vs Hospital Cleanliness Rating

#### Gender vs Staff Friendliness Rating

#### Gender & Treatment type vs Treatment Duration (weeks)

#### Gender & Treatment type vs wait time minutes

#### (Treatment Type & Gender & Age) vs Overall Health Improvement Rating

#### (Age group & gender & Treatment Type) vs side effect rating


4. Output Results:
#### From Graph : Gender Vs Treatment type :- 

Others Gender Group Mostly recommended Type A Treatment

Male Gender Group Mostly recommended Type C Treatment

Female Gender Group Mostly recommended Type B Treatment


#### from Graph : Gender vs Hospital Cleanliness Rating:-

All Gender mostly not satisfly with the Hospital Cleanliness 


#### from Graph: Gender vs Staff Friendliness Rating:-

Higher number of Females receommeded rating 4 means female is satisfy with Staff Friendliness.

higher Number of others and Males gender group recommended rating 3 means they are not satisfly with the Staff Friendliness.

#### From Graph :- Gender & Tratment type vs Treatment Duration (weeks):- 

Type A - Average Treatment Durations for Male is high

Type B - Average Treatment Durations for Female is high

Type C - Average Treatment Durations for Female is high

#### From Graph - Gender & Treatment type vs wait time minutes:

Type A - Avg wait time is high for Male Gender group

Type B - Avg wait time is high for other Gender group

Type C - Avg wait time  is high for Female Gender Group

#### (Treatment Type & Gender & Age) vs Overall Health Improvement Rating:

Type B & Type C is the Most Popular treatment plan among all Gender having good Health Inprovement rating.
Type A is not popular Treatment plan among all Genders.


#### (Age group & gender & Treatment Type) vs side effect rating:

for Type A :- Higher Side Effects rating (rating 5) given by the Man Gender group (Avg age - 60-70)

for Type B :- Higher Side Effects rating (rating 5) given by the Man Gender group (Avg age - 50-60)

For type C :- Higher Side Effects rating (rating 5) given by the Man Gender group (Avg age - 50-60)


## Acknowledgements

https://drive.google.com/file/d/1B4X23WVr6ECt3tNw1LT2xEKP-ltCh7B8/view?usp=drive_link


---
Contributor: Vinay Mudgal
Contact: insightfulvinay@gmail.com
Date: February 25, 2024
---
