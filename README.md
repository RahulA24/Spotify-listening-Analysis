# Spotify Listening Habits Analysis, Predictive Modeling, and Listener Clustering

## Project Summary

This project analyzes personal Spotify streaming history to uncover trends in listening habits such as peak activity times, favorite artists/songs, and skip behavior. It includes a predictive modeling component using Random Forest to forecast song skips and K-means clustering to categorize listeners into distinct behavioral groups. Interactive visualizations and actionable insights help better understand music consumption patterns.

## Tools & Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Imbalanced-learn  
- Joblib  
- Jupyter Notebook  

## Main Features

### Visualizations

- Top 10 artists and songs by play count and total listening time  
- Heatmaps for hourly, weekly, and monthly listening activity  
- Listening duration distributions segmented by daypart and weekday  
- ROC curves and confusion matrices to evaluate model performance  
- Cluster analysis visualizations (e.g., “Late Night Skippers”, “Morning Focused Listeners”)  

### Machine Learning

- **Random Forest Classifier** to predict skip behavior  
  - Achieved ~80% accuracy and AUC of 0.82  
  - Feature importance showed playtime, hour, and month as top predictors  
- Hyperparameter tuning for optimal performance  
- Class imbalance handled using SMOTE (Synthetic Minority Over-sampling Technique)  

### Key Insights

- **Cluster 0: “Late Night Skippers”** had a 100% skip rate—likely due to shorter listening sessions  
- Android was the **most-used platform** across all listener clusters  
- **Evening hours (18:00–21:00 IST)** showed the highest user engagement  

## How to Run

1. **Install Requirements**  
   ```bash
   pip install pandas matplotlib seaborn scikit-learn imbalanced-learn joblib
