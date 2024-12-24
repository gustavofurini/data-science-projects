# Air Quality and Pollution Assessment

This project leverages machine learning to predict air quality levels based on environmental and demographic factors. The analysis spans data exploration to model optimization, classifying air quality into four levels: **Good**, **Moderate**, **Poor**, and **Hazardous**.

## 🎯 Project Objectives

- **Identify critical factors** influencing air quality.
- **Develop robust machine learning models** to classify air quality.
- **Provide actionable insights** to mitigate pollution.

## 🌍 Context and Business Problem

Air pollution poses significant challenges to public health and the environment, impacting millions globally. This project aims to predict air quality, enabling proactive strategies to reduce pollution.

- **Analyzed factors**: Temperature, humidity, PM2.5, PM10, NO2, SO2, CO, proximity to industrial areas, and population density.
- **Expected impact**:
  - Improve decision-making by environmental agencies.
  - Issue alerts for hazardous conditions.
  - Support long-term sustainability strategies.

## 🗂️ Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment)
- **Key features**:
  - Temperature (°C), Humidity (%), PM2.5, PM10, NO2, SO2, CO.
  - Proximity to industrial areas (km) and population density (people/km²).
  - **Target variable**: Air quality classification into Good, Moderate, Poor, and Hazardous.
- **Dataset size**: 5,000 samples.

## ⚙️ Technologies and Libraries

- **Language**: Python
- **Libraries**:
  - Data manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Modeling: `scikit-learn`
  - Others: `warnings`

## 🚀 Methodology

1. **Data preprocessing**:
   - Checked for null and duplicate values.
   - Conducted exploratory analysis and visualized correlations.

2. **Model training**:
   - Models used: Logistic Regression, Random Forest, Gradient Boosting, SVM, KNN, and Naive Bayes.
   - Optimization: Feature selection with RFE and hyperparameter tuning with GridSearchCV.

3. **Evaluation metrics**:
   - Precision, recall, F1-score, and confusion matrix.

4. **Model optimization**:
   - The optimized Random Forest model achieved an **accuracy of 95%**.

## 🔑 Key Findings

- **Key pollution factors**:
  - High concentrations of PM2.5, PM10, NO2, SO2, and CO.
  - Proximity to industrial areas increases the likelihood of **Poor** or **Hazardous** air quality.
  - Areas with high population density show wide air quality variations.

- **Actionable insights**:
  - Develop strategies to reduce pollutants in industrial areas.
  - Monitor densely populated regions for preventive measures.

## 📊 Results

The optimized Random Forest model achieved:
- **Accuracy**: 95%
- **Macro F1-score**: 0.92

## 📌 Conclusion

This project demonstrated the potential of machine learning to predict and analyze air quality, supporting data-driven decision-making. The approach can be expanded to other scenarios, promoting sustainability and public health.

## 🛠️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/air-quality-assessment.git
