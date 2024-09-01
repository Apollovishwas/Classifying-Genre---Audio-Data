# Music Genre Classification: Hip-Hop vs. Rock

## Project Overview

This project aims to classify songs as either 'Hip-Hop' or 'Rock' based on audio features, without actually listening to the music. We use a dataset compiled by The Echo Nest, which includes various metrics derived from raw audio data. The project demonstrates data cleaning, exploratory data visualization, feature reduction, and the application of machine learning algorithms for classification.

## Dataset

The project uses two main datasets:

1. Track metadata (CSV format)
2. Audio features (JSON format)

Key features include:
- Danceability
- Acousticness
- Energy
- Instrumentalness
- Liveness
- Valence
- Loudness
- Speechiness
- Tempo

## Methodology

1. **Data Loading and Preprocessing**:
   - Load CSV and JSON files into pandas DataFrames
   - Merge datasets to combine features and labels
   - Handle missing values and data type conversions

2. **Exploratory Data Analysis**:
   - Visualize distributions of audio features
   - Analyze correlations between features
   - Compare feature distributions across genres

3. **Feature Engineering and Selection**:
   - Identify most relevant features for classification
   - Perform feature scaling if necessary

4. **Model Development**:
   - Split data into training and testing sets
   - Implement and train multiple models:
     - Decision Trees
     - Logistic Regression
   - Perform cross-validation and hyperparameter tuning

5. **Model Evaluation**:
   - Use metrics such as accuracy, precision, recall, and F1-score
   - Compare performance of different models

6. **Interpretation and Insights**:
   - Analyze feature importance
   - Interpret model decisions

## Tools Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning models and evaluation