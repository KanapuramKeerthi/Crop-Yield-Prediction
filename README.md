# 🌾 Crop-Yield-Prediction

Predict crop production using Machine Learning models based on climatic, soil, and historical agricultural data.  
Developed by **K Keerthi**.

---

## 📌 Problem Statement

The goal of this project is to implement a machine learning model that predicts crop yields based on climate conditions, soil quality, and historical agricultural data. The model will help farmers make informed decisions on crop production to increase productivity.

---

## 🎯 Business Understanding

Traditional methods of crop yield prediction are often manual and inaccurate. By leveraging machine learning, this project aims to:

- Improve prediction accuracy.
- Enable farmers to optimize productivity.
- Offer advanced solutions for agricultural decision-making.

---

## 📉 Present Situation

Crop yield prediction currently relies on manual analysis or outdated methods. With the integration of modern data science techniques like machine learning, we can achieve more accurate and scalable predictions.

Methods commonly used in modern systems include:

- Machine Learning Models
- Remote Sensing
- Crop Simulation Models
- Sensor Technology

This project addresses these needs by building an advanced predictive model.

---

## 🎯 Goals

- Build an accurate machine learning model to predict crop yields.
- Evaluate and compare three different models: Random Forest, XGBoost, and LightGBM.
- Implement the model for practical use in the agricultural sector, aiding farmers in crop production decision-making.

---

## 🛠️ Project Plan

1. **Data Collection & Preprocessing**: 
   - Dataset: [Kaggle - Indian Crop Production](https://www.kaggle.com/datasets/sriharikatare/indian-crop-production?resource=download)
   
2. **Model Development**: 
   - Train and compare three machine learning models: Random Forest, XGBoost, and LightGBM.

3. **Data Transformations**: 
   - One-hot encoding for categorical variables.
   - Box-Cox transformation for numerical features to stabilize variance and make the data more suitable for modeling.

4. **Model Evaluation**: 
   - Evaluate models using metrics such as MSE, RMSE, and R² score.

5. **Deployment**: 
   - Develop a system for integrating the trained models into applications like web or mobile for real-time crop prediction.

---

## 📂 Dataset Description

The dataset used includes information such as:

- **State_Name**: The state in India.
- **Crop_Type** and **Crop**: The type of crop and the specific crop being grown.
- **Soil and Climate Data**: Various factors affecting crop growth.
- **Production_in_tons**: The target variable, representing the crop yield in tons.

---

## 🔁 Model Comparisons

### 1. **Random Forest Regressor**
Random Forest was trained on the dataset and tested against the hold-out test data. It consistently produced good results with strong predictive accuracy and was selected as the best model based on evaluation metrics.

### 2. **XGBoost Regressor**
XGBoost was trained and tested on the same data. It showed competitive performance but was outperformed by Random Forest in terms of error metrics.

### 3. **LightGBM Regressor**
LightGBM provided reliable predictions as well, though it did not outperform Random Forest after all evaluations.

---

## 🔃 Data Transformations

- **One-Hot Encoding for Categorical Variables**:  
   Categorical variables such as `State_Name`, `Crop_Type`, and `Crop` were one-hot encoded to convert them into a numerical format suitable for model training.

- **Box-Cox Transformation for Numerical Variables**:  
   A Box-Cox transformation was applied to numerical attributes to stabilize variance and normalize the data, improving model performance. This transformation is especially useful for handling skewed data distributions.

---

## ✅ Conclusion

- **Best Performing Model**: Random Forest Regressor
- **Impact of Transformations**: The Box-Cox transformation helped improve the accuracy of the models, particularly for Random Forest.
- **Result**: The final model is capable of accurately predicting crop yields based on a variety of input features, providing valuable insights for farmers.

---

## 📌 Future Scope

- Integration with real-time weather data.
- Development of a user-friendly web application for farmers.
- Extension to support multi-crop and multi-region predictions.

---

## 👩‍💻 Developed By

**K Keerthi**  
Computer Science Engineer | AI & ML Enthusiast
