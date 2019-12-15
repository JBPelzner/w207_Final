# w207_Final

## Introduction/Business Problem

With the rise of new regulations, such as GDPR, privacy compliance organizations will need to forecast their future workflows. In order to complete and review permissions requests for mobile applications worldwide, privacy compliance organizations will need to hire compliance analysts, which affects their labor expenditures. We want to help these organizations with these forecasting tasks. We decided to focus on android apps in particular.

## Data Cleaning

We imported our data, and upon viewing the first 5 rows, observed that a blank column named "unnamed 6" contained null values. As such, we removed that column. We also observed that the data was out of order. As such, we merged our data and organized it by renaming some of the columns associated with post gdpr data. With the data merged accordingly, we are ready for EDA

## EDA
Our data contains the following variables: 

package_name: name of the app company
country: United States, Germany, or South Korea
category: Ages 5 & Under, Lifestyle, Social
pre_google_rank: The apps popularity rank according to the Google Play Store
pregdpr.permissions:	Types of permissions requested by the app company before GDPR was enacted.
pre_permission_count:	Number of permissions requested made by the app company before GDPR was enacted.
post_gdpr.permissions: Types of permissions requested by the app company after GDPR was enacted.
post_permission_count: Number of permissions requested made by the app company after GDPR was enacted.


### Model 1
The goal of our first model is to predict the number of permissions requests. 


### Model 2
The goal of our second model is to predict the number of dangerous permissions requests.


