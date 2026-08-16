# 🏋️ Gym Members Data Analysis

An exploratory data analysis (EDA) project examining gym members' workout
habits, biometric data, and performance patterns, built as part of an NTI
(National Telecommunication Institute) data science training project.

## 📋 Overview

This project analyzes a dataset of gym members to uncover patterns and
relationships between demographics, workout behavior, and physical
performance. The goal is to turn raw fitness-tracking data into insights
that could help gyms and trainers design better, more personalized
programs.

## 📊 Dataset

**File:** `gym_members_massive.csv`

The dataset includes records for gym members with attributes such as:

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
| Workout_Type | Cardio, Strength, HIIT, Yoga, etc. |
| Fat_Percentage | Body fat percentage |
| Water_Intake (liters) | Daily water intake |
| Workout_Frequency (days/week) | Number of gym visits per week |
| Experience_Level | Beginner / Intermediate / Advanced |

> Note: adjust this table to match the exact columns in your CSV if they differ.

## 🎯 Objectives

- Clean and prepare the raw dataset for analysis
- Explore relationships between demographics and workout performance
- Identify which factors most influence calories burned
- Compare workout types, experience levels, and outcomes
- Visualize trends and communicate findings clearly

## 🛠️ Tools & Technologies

- **Python 3**
- **Pandas** & **NumPy** — data cleaning and manipulation
- **Matplotlib** & **Seaborn** — data visualization
- **Jupyter Notebook** — analysis environment

## 📁 Project Structure

```
omar___mostafa/
├── Project_GYM_NTI___.ipynb   # Main analysis notebook
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
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Launch the notebook
   ```bash
   jupyter notebook Project_GYM_NTI___.ipynb
   ```

## 🔍 Analysis Steps

1. **Data loading & inspection** — checking shape, types, and missing values
2. **Data cleaning** — handling nulls, duplicates, and outliers
3. **Exploratory analysis** — summary statistics and distributions
4. **Visualization** — comparing variables across workout types, gender, and
   experience level
5. **Correlation analysis** — identifying the strongest predictors of
   calories burned and performance
6. **Insights & conclusions** — summarizing key findings

## 📈 Key Findings

*(Fill in with your actual results once finalized, e.g.:)*
- Session duration and average heart rate show the strongest correlation
  with calories burned
- Members with higher experience levels tend to have lower resting heart
  rates
- Workout type has a noticeable effect on calorie burn efficiency

## 👤 Author

**Omar Mostafa**
Project completed as part of the NTI Data Science / Analytics training track.

## 📄 License

This project is for educational purposes.
