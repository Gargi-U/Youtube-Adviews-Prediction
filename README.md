
# YouTube AdView Prediction Project

## Overview

In the dynamic world of YouTube content creation, advertisers pay creators based on the number of adviews and clicks on the ads for products and services showcased. Accurately estimating adviews is crucial for optimizing advertising budgets and strategies. This project focuses on building and selecting the best regression model to predict the number of adviews based on various YouTube video metrics like comments, likes, views, and more.

## Data Description

The dataset, `train.csv`, encompasses metrics and details for approximately 15,000 YouTube videos. This includes metrics like the number of views, likes, dislikes, comments, and the target variable, adviews. Additionally, details such as the video's publish date, duration, and category are also included. To ensure the quality and effectiveness of the prediction models, the data will undergo rigorous cleaning and refinement.

### Attribute Information

- `vidid`: A unique identifier for each video.
- `adview`: The number of adviews for each video.
- `views`: The number of unique views for each video.
- `likes`: The number of likes for each video.
- `dislikes`: The number of dislikes for each video.
- `comment`: The number of unique comments for each video.
- `published`: The date when the video was uploaded.
- `duration`: The total length of the video in minutes and seconds.
- `category`: The category or niche of each video.

## Objective

The primary goal is to engineer a sophisticated machine learning regression model that can predict the number of adviews for YouTube videos accurately. By leveraging the available metrics, the model aims to provide advertisers and creators with precise predictions to make informed decisions.

## Getting Started

Before diving into model building, ensure the data is clean and formatted correctly for optimal performance. Consider feature engineering and selection to enhance model predictions and evaluate various regression models to determine the most effective approach for this particular dataset. The end objective is a reliable, accurate model that stands as a testament to the power of machine learning in media and advertising analytics.
