# Stroke Prediction Project

This repository contains a Jupyter Notebook developed by **Group 10** for predicting strokes using machine learning techniques.  
The notebook demonstrates data preprocessing, exploratory data analysis (EDA), model training, and evaluation of different classifiers to predict stroke occurrence.


## Group 10 members

-John Peter Nuwagaba
-Imenyo Emillie Natalie
-Bridget Evelyn Masaba
-Patience Burani
-Ritah Natukwatsa
-Winifred Nakawunde 
-Charlotte Murungi
-Atubo Ellian Chelsea
 

## Dataset

The dataset used in this project contains patient health records with attributes such as:
- Gender, age, and marital status  
- Hypertension and heart disease indicators  
- Work type and residence type  
- Average glucose level and BMI  
- Smoking status  
- Stroke occurrence (target variable)

The dataset is typically obtained from publicly available stroke prediction datasets (e.g., Kaggle).  


## Methodology

1. **Data Preprocessing**  
   - Handled missing values (e.g., BMI).  
   - Encoded categorical variables.  
   - Normalized numerical features.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of features such as age, glucose level, and BMI.  
   - Examined stroke prevalence across different demographic groups.  

3. **Model Training**  
   - Applied machine learning algorithms (e.g., Logistic Regression, Random Forest, Decision Tree, SVM).  
   - Performed train-test split to validate models.  
   - Balanced the dataset using resampling techniques to handle class imbalance.  

4. **Model Evaluation**  
   - Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.  
   - Compared performance across models to identify the best-performing classifier.  


## Results

- Logistic Regression and Random Forest achieved strong predictive performance.  
- Random Forest showed higher accuracy and recall, making it more suitable for stroke prediction.  
- Important features influencing stroke occurrence included **age**, **hypertension**, **heart disease**, and **average glucose level**.  


## Conclusion

This project highlights how machine learning can be applied to healthcare data for early detection of strokes.  
By identifying high-risk individuals based on health indicators, the model can assist in **preventive care and medical decision-making**.  


## Installation

1. Clone the repository or download the notebook.
   

## Usage

1. Open the notebook:  
 
   jupyter notebook Final_StrokePrediction_Group_10_Presentations.ipynb
   
2. Run all cells step by step to:  
   - Preprocess and explore the dataset  
   - Train machine learning models  
   - Evaluate and compare results  


## Project Structure

- Final_StrokePrediction_Group_10_Presentations.ipynb`: Main notebook with analysis, models, and results.  


*Group 10 Project — Stroke Prediction*
