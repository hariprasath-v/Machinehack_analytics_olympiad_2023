# Machinehack_analytics_olympiad_2023

### Competition hosted on <a href="https://machinehack.com/hackathons/analytics_olympiad_2023/overview">Machinehack</a>

# About

### Create a machine learning model to determine the likelihood of a customer defaulting on a loan based on credit history, payment behavior, and account details.

### The Final Competition score is 1.0

### Leaderboard Rank is 5/158

### The Evaluation Metric is roc_auc_score.

### File information
 
 * analytics-olympiad-2023-eda.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/analytics-olympiad-2023-eda)
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* machinehack-analytics-olympiad-2022-model.ipynb [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/analytics-olympiad-2023-model)
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * catboost
        * shap
     #### The Catboost model was trained separately for both targets, using default parameters.
     #### The model was evaluated at each iteration using validation data.
     #### The model's performance was assessed using an accuracy score. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/Machinehack_analytics_olympiad_2023/blob/main/Analytics%20Olympiad%202023.pdf)
     

### Catboost – SHAP feature importance for primary close flag
![Alt text](https://github.com/hariprasath-v/Machinehack_analytics_olympiad_2023/blob/main/EDA_and_Model_Interpretation_Visualization/SHAP_Global_feature_importance_Primary_close_flag.png)

### Catboost – SHAP feature importance for final close flag
![Alt text](https://github.com/hariprasath-v/Machinehack_analytics_olympiad_2023/blob/main/EDA_and_Model_Interpretation_Visualization/SHAP_Global_feature_importance_Final_close_flag.png)
