# 9-1-1 Emergency Call Service 
![911](911_pic.jpg)

# Overview 
The crime rates have been increasing in recent times and so is the volume of 911 calls made. In such circumstance, a quick response to any 911 call is crucial. Keeping this in mind, it becomes critical to quickly and correctly process any 911 calls made and be ready for any kind of situations. This can be achieved by finding out patterns between time and day of the week and the type of calls made. The dataset I am using is about 911 calls and is available through kaggle. In this project I had the opportunity to look into 911 calls closely, which areas are affected the most and their corresponding reason. 911 is an important resource and data analytics of this would be helpful for communities and 911 operators. I used fully connected layer to check how well my model works and though experimental results the model gives 99% validation accuracy and very low validation loss.

# Project Goal
As per my study, a lot of cases have been reported through 911. The goal of my research project was to check which of the problems out of these 3 i.e. Fire, Traffic and EMS, has highest number of calls. I accomplished this goal by using TensorFlow Neural Network and one of the techniques Exploratory Data Analysis. This research will prove helpful to guide current services for improvement in their respective domains.

# Motivation & Background
With the present 911 call system, citizen has to remember only one number during all types of emergencies. However, with more people using this system, it has become difficult to effectivly process each call with minimum response time. Thus, the accuracy of the algorithm and speed of analysis are important factors. It is essential to use the right processing technique to empower our forces with the correct information in anticipation of any situation that might need immediate attention. A good understanding of these calls will help with resource allocation and also might help reduce the stress of 911 operators.

# Repository Navigation 

Table of Contents -

Technical Notebook               : [FinalProject](https://github.com/sanashar/911_emergency_calls/blob/main/Technical%20Notebook/FinalProject.ipynb)

Summary Report       : [FinalReport](https://github.com/sanashar/911_emergency_calls/blob/main/Summary%20Report/FinalProjectReport.ipynb)

Dataset          : [Data](https://www.kaggle.com/mchirico/montcoalert)

# Data Summary
The 911 calls dataset contains calls to 911 emergency service in Montgomery County Pennsylvania and is available through [kaggle](https://www.kaggle.com/mchirico/montcoalert) that has data from 2016 to 2020. It has 50000 rows and 9 columns. Most emergency calls are for Fire, Traffic, EMS for Montgomery County, PA.

The data contains the following fields:

1. lat : String variable, Latitude
2. lng: String variable, Longitude
3. desc: String variable, Description of the Emergency Call
4. zip: String variable, Zipcode
5. title: String variable, Title
6. timeStamp: String variable, YYYY-MM-DD HH:MM:SS
7. twp: String variable, Township
8. addr: String variable, Address
9. e: String variable, Dummy variable (always 1)

# Project Info & Software Requirements
DATA 602 Final Project - Sana Sharma

Languages    : Python 2.7

Tools/IDE    : Google Colabratory

Libraries    : pandas, matplotlib, statsmodels, keras, seaborn
