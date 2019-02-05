INTRODUCTION TO PREDICTIVE ANALYSIS ON BIG DATA

The objective was to determine the feasibility of the use big data analytics to solve the problem of predictive Accident inspection which involves
predicting accident data on the basis of gender and age and check age group causes most of the accidents and which gender group causes most of the
accidents.
The goal of the project was to evaluate the feasibility to use Big Data analysis solutions for government to reduce accidents in particular area.
Our task was to analyze accident history data and predict Accidents happened in past. The Big Data Analytics project was chartered with the
goal in mind of evaluating the feasibility of the use of Big Data analytics solutions to solve different operation.
The type of data mining and analytics that deals with extracting information from data and using it to predict trends and behavior patterns is
known as Predictive Analytics. In order to predict the probability of an outcome a Predictive Model must be created or chosen. Technically a
model is a mathematical equation that determines the probabilistic relationship between data elements. Predictive models typically use
classification algorithms to predict an outcome, which requires having a training set of data whose outcomes and accident data are already known.
For this project, we had accident history data.

UNDERSTANDING OF DATA

Here we are using past data for future prediction. Accident data includes columns like Gender, Age, IsValidLicence, Name, Accident Area. On the
basis of these data we can make predictions on different age group and on different gender group.
Data can be of 100 rows, it can be 10,00,000 rows or so on i.e First of all we will save data in text file. And with the help of hadoop we can fetch data
from the text file due to its HDFS property. After fetching the data we have to process the data on the basis of our requirement.
After processing the data will store in text format again. But with the help of HBase we can store data in HBase also. So we can check data from
HBase later. On the basis of data we have to predict age group met more accident and which gender group met more accident. If we get Male met more accident
then we have to find out how many male have valid license. On the basis of result we have to give some prescription as a result to user.
For effective prediction data should be in rows and columns so that to effective result.
And also we have to add prediction file. We have two prediction files. One is for age prediction and other for gender prediction, which contains
different groups of ages and genders. For example age prediction file contains age less than 20, age greater than 20 and gender predictions like
Male and Female.
