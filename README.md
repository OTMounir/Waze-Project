# Waze Project
 Churn project on the Waze data

 Waze’s free navigation app makes it easier for drivers around the world to get to where they want to go. Waze’s community of map editors, beta testers, translators, partners, and users helps make each drive better and safer. Waze partners with cities, transportation authorities, broadcasters, businesses, and first responders to help as many people as possible travel more efficiently and safely. 

The goal is to collaborate with your Waze teammates to analyze and interpret data, generate valuable insights, and help leadership make informed business decisions. A new project to help prevent user churn on the Waze app is starting. Churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. This project focuses on monthly user churn. 

This project is part of a larger effort at Waze to increase growth. Typically, high retention rates indicate satisfied users who repeatedly use the Waze app over time. Developing a churn prediction model will help prevent churn, improve user retention, and grow Waze’s business. An accurate model can also help identify specific factors that contribute to churn and answer questions such as: 

Who are the users most likely to churn?

Why do users churn? 

When do users churn? 

For example, if Waze can identify a segment of users who are at high risk of churning, Waze can proactively engage these users with special offers to try and retain them. Otherwise, Waze may lose these users without knowing why. 

The insights will help Waze leadership optimize the company’s retention strategy, enhance user experience, and make data-driven decisions about product development.

The dataset contains:

14,999 rows – each row represents one unique user 

13 columns



ID(int)

A sequential numbered index

label(obj)

Binary target variable (“retained” vs “churned”) for if a user has churned anytime during the course of the month 

sessions(int)

The number of occurrence of a user opening the app during the month

drives(int)

An occurrence of driving at least 1 km during the month

device(obj)

The type of device a user starts a session with

total_sessions(float)

A model estimate of the total number of sessions since a user has onboarded

n_days_after_onboarding(int)

The number of days since a user signed up for the app

total_navigations_fav1i(nt)

Total navigations since onboarding to the user’s favorite place 1

total_navigations_fav2(int)

Total navigations since onboarding to the user’s favorite place 2

driven_km_drives(float)

Total kilometers driven during the month

duration_minutes_drives(float)

Total duration driven in minutes during the month

activity_days(int)

Number of days the user opens the app during the month 

driving_days(int)

Number of days the user drives (at least 1 km) during the month