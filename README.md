# Project Description
> You will get **a machine learning model that predicts gym workout types**

Alternative options:
- You will get **a complete ML classification project on gym members' data**
- You will get **a trained KNN model that classifies gym workout types**
- You will get **an end-to-end machine learning pipeline for fitness data**

## Full description

I built a complete machine learning classification project using a
real-world dataset of 10,000 gym members, predicting each member's
workout type (Cardio, Strength, HIIT, Yoga) from their demographic,
biometric, and workout data.

The project covers the full ML pipeline: data cleaning, exploratory data
analysis, feature encoding and scaling, and model building. I trained and
compared multiple models — Logistic Regression, K-Nearest Neighbors (KNN),
Decision Tree, and a Gaussian Mixture clustering model — then tuned the
KNN model's hyperparameter (K) to reach the best performance. Model
evaluation included accuracy, precision, recall, F1-score, and confusion
matrix analysis. Built in Python with Pandas, NumPy, Scikit-learn,
Matplotlib, and Seaborn inside a Jupyter Notebook.

You will receive:
- A fully documented, ready-to-run Jupyter Notebook
- Cleaned and preprocessed dataset
- Trained and evaluated classification models with comparison
- Visualizations (EDA charts, confusion matrix, model tuning curve)
- A short written summary of results and key findings

Ideal for anyone who wants a hands-on example of a complete supervised
learning workflow — from raw data to a tuned, evaluated model.

# 🏋️ Gym Workout Type Classification (Machine Learning)

A supervised machine learning project that predicts a gym member's workout
type (Cardio, Strength, HIIT, Yoga) from demographic, biometric, and
workout-session data. Built as part of an NTI (National Telecommunication
Institute) data science training project.

## 📋 Overview

Using a dataset of 10,000 gym members, this project builds and compares
several classification models to predict `Workout_Type`, then tunes the
best-performing model for optimal accuracy. It also includes an
unsupervised clustering experiment (Gaussian Mixture Model) to explore
natural groupings in the data.

## 📊 Dataset

**File:** `gym_members_massive.csv` — 10,000 rows, 15 columns

| Column | Description |
|---|---|
| Age | Member's age |
| Gender | Male / Female |
| Weight (kg) | Body weight |
| Height (m) | Height |
| BMI | Body Mass Index |
| Max_BPM | Maximum heart rate during workout |
| Avg_BPM | Average heart rate during workout |
| Resting_BPM | Resting heart rate |
| Session_Duration (hours) | Length of workout session |
| Calories_Burned | Calories burned per session |
| Workout_Type | Target — Cardio, Strength, HIIT, Yoga |
| Fat_Percentage | Body fat percentage |
| Water_Intake (liters) | Daily water intake |
| Workout_Frequency (days/week) | Gym visits per week |
| Experience_Level | Beginner / Intermediate / Advanced |

## 🎯 Objectives

- Clean and prepare the raw dataset for modeling
- Explore relationships between features via EDA
- Encode categorical variables and scale numeric features
- Train and compare multiple classification models
- Tune hyperparameters to improve performance
- Evaluate models with accuracy, precision, recall, F1, and confusion matrix

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas** & **NumPy** — data cleaning and manipulation
- **Scikit-learn** — modeling, scaling, encoding, evaluation
- **Matplotlib** & **Seaborn** — data visualization
- **Jupyter Notebook** — analysis environment

## 📁 Project Structure

```
omar___mostafa/
├── Project_GYM_NTI___.ipynb   # Main analysis & modeling notebook
├── gym_members_massive.csv    # Raw dataset
└── README.md                  # Project documentation
```

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/omar38406-blip/omar___mostafa.git
   cd omar___mostafa
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. Launch the notebook
   ```bash
   jupyter notebook Project_GYM_NTI___.ipynb
   ```

## 🔍 Workflow

1. **Data loading & inspection** — shape, types, missing values, summary stats
2. **Exploratory data analysis** — distributions, correlations, comparisons
   across workout type, gender, and experience level
3. **Preprocessing** — label encoding for categorical features, one-hot
   encoding, feature scaling with `StandardScaler`, 80/20 train-test split
4. **Modeling** — trained and compared:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree Regressor
   - Gaussian Mixture Model (unsupervised clustering)
5. **Hyperparameter tuning** — tested K values from 1–20 for KNN and
   selected the best-performing K
6. **Evaluation** — accuracy, precision, recall, F1-score, confusion matrix

## 📈 Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 30.3% |
| KNN (K=5) | 55.7% |
| **KNN (tuned, best K)** | **68.4%** |

The tuned KNN model was the best performer, showing that workout type can
be predicted reasonably well from a member's biometric and session data,
with room for further improvement through additional feature engineering.

## 👤 Author

**Omar Mostafa**
Project completed as part of the NTI Data Science / Machine Learning
training track.

## 📄 License

This project is for educational purposes.
