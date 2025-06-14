# 🏍️ Burnout MotoGP Datathon - HackHero 🏁

This repository contains the analysis and modeling work for the **Burnout MotoGP Datathon - HackHero**, a data science competition focused on understanding rider performance, team efficiency, and track impact using MotoGP data.

📌 [Original Notebook on Kaggle](https://www.kaggle.com/code/pradeepkumara2211/notebooke5e47c5528)

---

## 📊 Project Overview

The goal of the datathon is to explore and model data from MotoGP races. By analyzing data from races, riders, and conditions, we aim to uncover patterns and build predictive models that can assist with race strategies and performance predictions.

---

## 📁 Dataset

The dataset includes the following files:

- `circuits.csv`: Information about circuits (tracks).
- `constructors.csv`: Information about bike manufacturers.
- `lap_times.csv`: Individual lap time data.
- `races.csv`: Details of each MotoGP race.
- `results.csv`: Final results of each race.
- `weather.csv`: Weather conditions for each race.
- `qualifying.csv`: Qualifying session results.
- `status.csv`: Final status (e.g., finished, accident) of each rider.

---

## 🛠️ Tools & Technologies

- **Python** (main programming language)
- **Pandas**, **NumPy** – for data analysis
- **Matplotlib**, **Seaborn** – for visualization
- **Scikit-learn**, **XGBoost** – for machine learning models
- **Kaggle Notebooks** – development environment

---

## 🔍 Key Analysis Highlights

- Explored the popularity of different circuits and constructors.
- Evaluated lap performance trends under different weather conditions.
- Investigated the influence of qualifying performance on final race results.
- Built classification models to predict race outcomes.

---

## 🤖 Model Building

- LightGBM Regression

**Performance Metrics**: Accuracy, Precision, Recall, F1-Score

---

## 📈 Results
- Unique ID and RMSE Values

---

## 🚀 Future Improvements

- Include telemetry or bike sensor data for more accurate modeling.
- Try deep learning models for time-series data from lap times.
- Perform clustering of riders based on styles and outcomes.
