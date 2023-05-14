# Android-App-Market-Analysis-on-Google-Play

## Project Overview

This project analyzes the Android app market on Google Play using Python libraries such as pandas, matplotlib, plotly, and seaborn. The following steps were taken to clean and explore the dataset:

## Data Cleaning

Inaccurate data symbols were removed from the Installs and Price columns of the dataset.

## Correcting Data Types

The Installs and Price columns were converted to numeric data type.

## Exploring App Categories

The data was grouped together based on categories to answer the following questions:

- Which category has the highest share of (active) apps in the market?
- Is any specific category dominating the market?
- Which categories have the fewest number of apps?

## Distribution of App Ratings

The average ratings and distribution of ratings across all apps were found.

## Size and Price of an App

The correlation between the size and price of an app was determined to answer the following questions:

- Does the size of an app affect its rating?
- Do users prefer light-weighted apps?
- Does the price of an app affect its rating?
- Do users always prefer free apps over paid apps?

It was found that the majority of top-rated apps (rating over 4) range from 2 MB to 20 MB, and the vast majority of apps price themselves under $10.

## Relation between App Category and App Price

The correlation between app category and app price was found, and it was observed that Medical and Family apps are the most expensive. Some medical apps extend even up to $80! All game apps are reasonably priced below $20.

## Filter out "Junk" Apps

Junk apps, which are priced over $100, were filtered out from the dataset.

## Popularity of Paid Apps vs Free Apps

It was found that paid apps are actually installed less than free apps.

## Sentiment Analysis of User Reviews

Sentiment analysis was performed on user reviews to determine how people feel about the apps. By plotting sentiment polarity scores of user reviews for paid and free apps, it was observed that free apps receive a lot of harsh comments, as indicated by the outliers on the negative y-axis. Reviews for paid apps appear never to be extremely negative. This may indicate something about app quality, i.e., paid apps being of higher quality than free apps on average. The median polarity score for paid apps is a little higher than free apps, thereby syncing with our previous observation.

Overall, this project provides insights into the Android app market on Google Play and can be useful for app developers and marketers.
