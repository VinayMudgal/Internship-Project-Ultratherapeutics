# Ultratherapeutics Patient Satisfaction Analysis

Task 2 - Exploratory Data Analysis (EDA)

Introduction:-

This Task focuses on analyzing patient satisfaction surveys with the different type of rating to improve healthcare service quality and also Focused on understanding Pattern with diffrenet variables using EDA (Exploratory Data Analysis) method.

## Dependencies

Using Following external libraries are required to run the Jupyter Notebook:

Pandas,
Matplotlib,
Seaborn

## Setup Instructions:

Open the Jupyter Notebook:
Launch the Jupyter Notebook application using this command.

Install Dependencies:
install the required Python libraries.

Load The Data Sets again:
Loading the data sets in Jupyter Notebook.

Run the Cell in Jypiter Notebook:-
(commonly Shift + Enter) used for the Running a cell in Jypiter Notebook.

## Usage

i have required Dataset ('patient_satisfaction_ultratherapeutics.csv') form the client.
following the instructions witin Notebook to Load the Data and interepting the result.

## Schema Mapping Explanation:

1. Loading Data:
Uusing pandas to load the dataset.

2. Data Cleaning:
we Already did in previous task.

3. Visual Analysis on The Dataset:
EDA Analysis using with `matpolotlib` and `seaborn`, getting some interesting insights from the Data.

### `Total Patients Vs Gender`
### `Avgerage Age Vs Treatment type`
### `Total Patients Vs Treatment Type & Gender`
### `TreatmentType Vs Side effect`
### `Corrleation between Different rating` To understading the relationship between different variables.
### `Treatment Type VS Staff Friendliness Rating`
### `Perceived Effectiveness Rating VS Treatment Type with Gender`
### `Total patients VS Staff Friendliness Rating`
### `Treatment Type VS wait time (Minutes)`
### `Treatment Type  VS Treatment Duration (weeks)`



4. Output Results:
#### From Graph : Total Patients Vs Gender

Higher Number of patients are from Other Gender Group and Lower number are from Female Group. 


#### From Graph : Avgerage Age Vs Treatment type

Type A :- Patients Average Age is 55

Type B :- Patients Average Age is 50 

Type C :- Patients Average Age is 45


#### From Graph : Total Patients Vs Treatment Type & Gender

Type A :- Mostly provides to Other Gender group

Type B :- Mostly provides to Females Gender group

Type C :- Mostly provodes to Male Gemder group


#### From Graph : TreatmentType Vs Side effect

Type C has higher side Effect Rating.

Type A has lower Side effect Rating.

#### From Graph : Corrleation between Different rating

Overall Health improvement Rating is correlated with (wait time, Perceived Effectiveness Rating , side Effect rating) Means
Overall Health improvement Rating has higher effect with Perceived Effectiveness Rating.
Overall Health improvement Rating has also effected by Side Effect Rating and then Wait time duration.


### From Graph :Treatment Type VS Staff Friendliness Rating

lower Staff Friendliness Rating provided by the Patients who has Treatment Type A & Type C


#### From Graph : Perceived Effectiveness Rating VS Treatment Type with Gender

for Type A :- Other Gender gives lower Perceived Effectiveness rating

for Type B :- Male gives lower Perceived Effectiveness rating

for Type C :- Other gives lower Perceived Effectiveness rating


### From Graph : Total patients VS Staff Friendliness Rating

Type A :- Other Gender Group Patients are disappoints with the Staff Friendliness.

Type C :- Other Gender and Male Group Patients are disappoints with the Staff Friendliness.


### From Graph : Treatment Type VS wait time (Minutes)

Type A :- Lower Wait time (Minutes) for Female & higher time for Male

Type B :- Lower Wait time (Minutes) for Male  & higher Females & Other Gender Group

Type C :- Lower Wait time (Minutes) for Other & higher Male & Female Gender Group


### From Graph : Treatment Type  VS Treatment Duration (weeks)

Type A :- Avg. Treatment Duration (Week) is high for Male

Type B :- Avg. Treatment Duration (Week) is high for Female

Type C:-  Avg. Treatment Duration (Week) is high for Female


---
*Patient Satisfaction depends upon the various factors, including perceived effectiveness, wait times, and side effects.*

***Perceived Effectiveness can be improved ***: 
Clear Communication with the Patient, this includes explaining the treatment plan in details, expected outcomes.

Follow-up Care: implement a Follow-up Plan from the Patients.


***Reduce Wait Time***:
Appointment Scheduling: Optimize appointment scheduling to minimize gaps.

Communication: Keep patients informed about any delays Or any wait time.


***Lower Side Effect Rating***:
Preventive Measures: inform patient to side effect if may occurs. This could involve pre-screening for risk factors, personalized treatment plans.

Monitoring and Reporting: Monitor and reporting of Each patient during the treatment so we can analysis about any side effect occur.

Patient Counseling: Discussion with the Patients regarding potential side effects before starting a new treatment.
---


Contributor: Vinay Mudgal
Contact: insightfulvinay@gmail.com
Date: March 4, 2024
