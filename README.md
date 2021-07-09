# Appointments No-Shows Data Investigation

## Overview
The goal of this project is to investigate a dataset of appointment records for Brazilian public hospitals. he data includes some attributes of patients and status if the patients showed up to appointments or not. 
The analysis should be focused on finding trends influencing patients to show or not show up to appointments. 
Using **descriptive statistics** the following question should be answered: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? Predictive analytics is out of the scope of this project.

The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/

This project was completed as part of Udacity's 'Data Analyst Nanodegree' certification.

## Details
I have looked into the dataset and managed a few problems like unifying names, removing wrong data, adding new features based on existing data. I have also investigated most of the independent variables in the dataset and made a few observations comparing them to each other as well as to the dependent one (no_show). As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.


## Questions and Findings:

The most important findings are:

>**Research Question 1: Which Gender is most likely to have a No-Show?**<br>
Females are most likely to not show to an appointment than Males. But this doesn't imply a proper causation. We don't really know the exact reasoning per say.<br>
******************************************************************************************************************************** 

>**Research Question 2: Is Time waited after scheduling related to No-Shows?**<br>
We discovered that the longer the waiting time the patient has to wait for, the higher the probability of not showing for an appointment.<br> 
********************************************************************************************************************************
>**Research Question 3: Patients with history of Alcoholism resulted in No-Shows?**<br>
>**Research Question 4: Diabetes patients most likely having No-Shows?**<br>
>**Research Question 5: Hypertension patients most likely having a No-Show?**<br>
People with history with Alcoholism, Hypertension and diabetes are more likely to show up to the appointment probably related to following up on some accompaning health effects, they need the constant follow up.<br>
********************************************************************************************************************************
>**Research Question 6: Does sending a reminder through an SMS before the appointment affect No-show frequency?**<br>
Looks like whether an SMS was sent before the appointment or not, there is still a significant no-shows, thus, it is not an affecting factor.<br>
********************************************************************************************************************************
>**Research Question 7: Patients that have a scholarship will most likely No-show as they are not paying full expense?**<br>
The results show that people with scholarships has a bigger % of noshows. most likely because they are not paying full price for the appointment, thus care less.<br>
********************************************************************************************************************************
>**Research Question 8: Which Age group would most likely result in a No-Show?**<br>
Adults are the most likely category for a No-show due to having a busy life as well as work commitment.<br>
********************************************************************************************************************************
>**Research Question 9: The appointment being a weekday or weekend affects the frequency of No-shows?**<br>
It seems that there is an almost even distribution of noshows along the weekdays except for Saturday where this is only 1 no-show in the whole data set. It means that during weekdays, people are quite busy and on Sunday, people are tired and preparing for Monday for work.<br>
********************************************************************************************************************************
>**Research Question 10: Appointment time (early morning or night) affects the amount of No-shows? (before 12 pm and after 6 pm)**<br>
We noticed that the amount of no-shows of Night appointments are quite less than the rest of the day. It means that people would rather not miss appointments if it is after work time. <br>
********************************************************************************************************************************
>**Research Question 11: Location of the hospital affects the amount of No-shows? (Accessability)**<br>
It seems that 'Jardim Camburi', 'Maria Ortiz' and 'Itarare' have the most numbers of noshows, most likely due to accessibility and transportation.
On the other hand, 'Aeroporto', 'Ilha do frade' and 'Ilhas Oceanicas De Trindade' have the least numbers of no-shows, thus, convenient to reach and accessible for everyone.<br>
********************************************************************************************************************************
>**Research Question 12: Which age group are most likely to apply for a scholarship?**<br>
Adults are most likely to have scholarships.<br>
********************************************************************************************************************************
>**Research Question 13: What is the relation between Age and the patient having hypertension/diabetes/alcoholism?**<br>
Majority of people suffering from alcoholism are 'Adults'. Majority of the people suffering from Diabetes are Seniors. However, the majority of Both Seniors and Adults are suffering Hypertension.<br>
********************************************************************************************************************************
>**Research Question 14: Location of the hospital affects the amount of No-shows for seniors? (Accessability)**<br>
That means that JARDIM CAMBURI, JARDIM DA PENHA and MARIA ORTIZ neighbourhoods might have an accessiblity for seniors. requires further investigation.<br>
********************************************************************************************************************************
>**Research Question 15: Location of the hospital affects the amount of No-shows for Handicapped? (Accessability)**<br>
We notice that there is a handicap inaccessibility for some locations like SANTO ANTONIO, ANDORINIHAS and DA PENHA. Therefore these places need to check for accessibility for disabled.<br>
********************************************************************************************************************************
>**Research Question 16: Which variable has the most numbers of No_shows?**<br>
We noticed that SMS_received has the most % of No shows in all the variables.<br>
********************************************************************************************************************************



## Statistical Analysis Scope
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data visualizations
- Conclusions and limitations

## Tools
- Python, libraries: numpy, pandas, matplotlib, seaborn
- Jupyter Lab
