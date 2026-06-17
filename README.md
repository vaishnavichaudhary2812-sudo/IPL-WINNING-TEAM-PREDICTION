# IPL 1st Innings Score Prediction Using Machine Learning

## Overview

This project predicts the first innings score of an IPL (Indian Premier League) match using Machine Learning techniques. The model is trained on ball-by-ball IPL match data from Seasons 1 to 10 (2008–2017) and uses match statistics such as current runs, wickets, overs, and recent performance to estimate the final first innings score.

## Dataset

The dataset contains ball-by-ball information of IPL matches played between 2008 and 2017.

### Features Used

* Match ID
* Batting Team
* Bowling Team
* Current Runs
* Wickets Fallen
* Overs Completed
* Runs Scored in Last 5 Overs
* Wickets Fallen in Last 5 Overs

### Target Variable

* Total First Innings Score

## Project Workflow

### 1. Data Collection

* Loaded IPL ball-by-ball dataset.
* Explored dataset structure and features.

### 2. Data Preprocessing

* Selected relevant features.
* Filtered consistent IPL teams.
* Removed records before 5 overs.
* Applied One-Hot Encoding to categorical features.

### 3. Exploratory Data Analysis (EDA)

* Distribution of First Innings Scores
* Batting Team Analysis
* Bowling Team Analysis
* Runs vs Overs Visualization
* Wickets vs Total Score Analysis
* Correlation Heatmap

### 4. Model Building

Implemented Linear Regression for score prediction.

### 5. Model Evaluation

Evaluated model performance using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab / Jupyter Notebook

## Visualizations

The project includes multiple visualizations for better understanding of the dataset:

* Score Distribution Plot
* Team-wise Analysis
* Scatter Plots
* Correlation Heatmap
* Actual vs Predicted Score Plot

## Results

The model successfully predicts IPL first innings scores based on current match conditions and historical match patterns.

## Project Structure

```text
IPL-Score-Prediction/
│
├── IPL_Score_Prediction.ipynb
├── ipl.csv
├── README.md
└── requirements.txt
```

## Future Improvements

* Implement Random Forest Regressor
* Implement XGBoost Regressor
* Hyperparameter Tuning
* Deploy using Streamlit or Flask
* Real-time IPL Score Prediction System

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning Model Development
* Model Evaluation Techniques
* Sports Analytics

## Author

**Vaishnavi Chaudhary**

Summer Internship Project | Machine Learning
