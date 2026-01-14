# Heart Disease Prediction

This project applies machine learning techniques to predict the presence of heart disease using patient medical data.

## Overview
Heart disease is a leading cause of mortality worldwide. Early detection can help improve treatment outcomes.  
This project builds and compares multiple classification models to predict heart disease.

## Dataset
The dataset contains medical attributes such as:
- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol  
- Fasting blood sugar  
- Maximum heart rate  
- Exercise-induced angina  
- ST depression  
- Target label (0 = No disease, 1 = Disease)

Total records: **300+**  
Total features: **13+**

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## Project Workflow
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Feature analysis and visualization  
4. Model training  
5. Performance evaluation  

## Models Implemented
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  
- Decision Tree Classifier  

## Results

| Model | Accuracy |
|------|----------|
| KNN | **84.48%** |
| Random Forest | **82.5%** |
| Decision Tree | **78.51%** |

KNN achieved the highest accuracy among the tested models.

## Evaluation Metrics
- Accuracy score  
- Confusion matrix  
- Classification metrics  

## How to Run
1. Clone the repository  
```bash
git clone https://github.com/prathisg/Heart-Disease-Prediction.git
2.open in Jupter notebook and run all cells
