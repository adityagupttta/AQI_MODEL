# 🌫️ AQI Prediction using Environmental and Demographic Data

This project predicts Air Quality Index (AQI) of New Delhi using various environmental and demographic features including temperature, humidity, rainfall, population, and car count. The data was collected from multiple sources like Government portals , reports , Media briefs etc .Then Data is cleaned , EDA on Data shows major features and their relation with the target i.e. AQI used to train three machine learning models that include Random Forest(77%) , Linear regression(63%) and Decision Tree(47%).

---

## 📂 Dataset Description

The dataset contains the following features:

- `AQI` – Air Quality Index (target variable)
- `Temprature` – Temperature in °C
- `Humidity` – Relative humidity (%)
- `Rainfall` – Rainfall (mm)
- `Population` – Estimated population
- `Car count` – Estimated vehicle count

---
## 🧹 Data Cleaning

- Removed null values and duplicates
- Set `Date` as index
- Standardized column names
- Selected relevant features for analysis and modeling

---

## 📊 Exploratory Data Analysis (EDA)

### 1. **Temperature vs AQI**

- **Observation:** As temperature increases, AQI tends to decrease slightly, but the relationship is not strongly linear.

### 2. **Rainfall vs AQI**

- **Observation:** Higher rainfall shows a **strong inverse** relationship with AQI – rainfall likely clears pollutants.

### 3. **Population vs AQI**

- **Observation:** No clear visual correlation between population and AQI in this dataset.

### 4. **Car Count vs AQI**

- **Observation:** Moderate correlation observed. Higher car count areas show higher AQI values.

### 5. **Humidity vs AQI**

- **Observation:** Slight inverse relationship – increased humidity may help trap particles and reduce AQI.


## 📈 Models Used

Three models were trained to predict AQI:

| Model                 | Accuracy (R² Score) |
|----------------------|---------------------|
| ✅ Random Forest      | **77%**             |
| 📉 Linear Regression  | 63%                 |
| 🌳 Decision Tree      | 46%                 |

---  

##  How to Use

1. Open the `.ipynd` file in Google colab.
2. To view Visualisations , Open the screenshots folder on this repo
3. To access the Dataset refer to AQI.csv
---

## 🚀 Future Improvements

-Integrate real-time AQI data using APIs or web scraping
-Add more features like wind speed, PM2.5, and industrial emissions

---
## 🧠 What I Learned from This Project
-How to collect and clean real-world data from multiple sources
-Performed exploratory data analysis (EDA) to uncover trends and correlations
-Built and evaluated multiple regression models using scikit-learn
-Learned the impact of environmental features on air pollution
-Improved my skills in data visualization and interpretation

---

## About me 

I’m an aspiring Data Analyst and Data Engineer, passionate about transforming raw data into actionable insights. This project showcases my ability to collect, clean, analyze, visualize data, and build predictive 
models to solve real-world problems using machine learning.

---

##  Feedback

Feel free to reach out with suggestions, improvements, or collaboration ideas!
