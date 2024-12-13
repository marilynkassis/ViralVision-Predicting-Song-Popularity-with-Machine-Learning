# ViralVision-Predicting-Song-Popularity-with-Machine-Learning
A machine learning project leveraging advanced classification techniques to predict the success of songs based on features like artist popularity, acoustic properties, and song metadata.

# ViralVision: Predicting Song Popularity with Machine Learning

ViralVision is a machine learning-based solution aimed at predicting the success of songs in the music industry. This project explores the relationship between musical features, artist popularity, and song metadata to identify key factors contributing to a track's success. By applying advanced classification models, the project empowers record labels to make data-driven decisions, maximizing return on investment and minimizing risks.

## Project Overview

In the music industry, predicting a song's success is vital for optimizing marketing strategies and resource allocation. ViralVision employs cutting-edge machine learning models, including CatBoost, Random Forest, and Decision Tree, to analyze various features and predict song popularity with high accuracy.

### Key Features:
- **Advanced Machine Learning Models:** Utilizes models like CatBoost and Random Forest for robust and accurate predictions.
- **Feature Engineering:** Key features like artist popularity, acousticness, speechiness, liveness, and danceability were engineered for maximum impact.
- **Custom Binning Techniques:** Applied data-driven strategies (e.g., Decision Tree Binning) to optimize classification accuracy.

## Methodology

1. **Data Preprocessing:** Cleaned and transformed data by handling null values and removing non-relevant features such as track name and album name.
2. **Feature Engineering:** Created new features such as average genre popularity and transformed categorical variables into binary features.
3. **Modeling and Evaluation:** Compared multiple classification models, including Decision Trees, Random Forest, and CatBoost, to identify the best-performing model.
4. **Feature Importance Analysis:** Used SHAP plots to interpret the influence of features on the model's predictions.

## Results

- **Model Performance:** CatBoost emerged as the best-performing model with an accuracy of approximately 78% and superior F1-score and ROC-AUC metrics.
- **Key Predictive Features:** Artist popularity, acousticness, liveness, and song duration played a significant role in predicting success.
- **Business Impact:** Potential to increase marketing ROI by 15-35% and streamline decision-making processes by 30-50%.

## Benefits

ViralVision offers the following advantages:
- Improved marketing and promotional ROI.
- Enhanced strategic decision-making for artist development and production.
- Risk mitigation by identifying high-probability hits.
- Catalog optimization for re-promoting sleeper hits.

## Visuals and Insights

- **Popularity Distribution:** Analyzed trends in song popularity over time to identify patterns.
- **Feature Importance:** Visualized the top features contributing to predictions using SHAP plots.
- **Model Evaluation Metrics:** Heatmaps comparing models across accuracy, precision, recall, and F1-score.


