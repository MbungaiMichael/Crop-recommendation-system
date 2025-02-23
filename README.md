# **Crop Recommendation System**

## **Overview**
The Crop Recommendation System is designed to help farmers select the most suitable crops based on key agricultural parameters, including soil nutrients (Nitrogen, Phosphorus, Potassium), temperature, humidity, pH, and rainfall. The objective of this project is to enhance agricultural decision-making by providing data-driven crop recommendations, reducing uncertainty, and improving farm productivity. It leverages the Naïve Bayes machine learning algorithm, which is effective for classification tasks with continuous numerical features. This system offers several benefits, Increased crop yield by helping farmers choose the most suitable crops for their land. Cost efficiency by reducing wasted resources on unsuitable crops, and Sustainable farming practices by optimizing soil health and minimizing environmental impact. By integrating AI into agriculture, this project empowers farmers with precise insights, leading to smarter and more profitable farming decisions.

## Database Schema
The dataset consists of 8 columns:

[data information here](https://github.com/MbungaiMichael/Crop-recommendation-system/blob/main/Crop_recommendation.csv)🔗

| Columns | Description|
|---|---|
|N|ratio of Nitrogen content in soil - kg/ha.|
|P|ratio of Phosphorous content in soil - kg/ha|
|K|ratio of Potassium content in soil - kg/ha|
|temperature|temperature in degree Celsius|
|humidity|relative humidity in %|
|ph|ph value of the soil|
|rainfall|rainfall in mm|

## **Procedure**
- Clean the data and check for missing values.
- standardize the dataset.
- Train and Test the model.

## **Result**
- The crop recommendation system using Gaussian Naïve Bayes achieved an impressive accuracy of 99.45% (0.9945).This high accuracy indicated that the model is highly effective in correctly predicting the most suitable crop based on input parameters like Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall. [project here](https://github.com/MbungaiMichael/Crop-recommendation-system/blob/main/Crop%20recommendation%20system.ipynb)🔗


