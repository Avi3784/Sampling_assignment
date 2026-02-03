# Sampling Techniques on Imbalanced Credit Card Dataset 102303726

## Introduction
This project explores the impact of different sampling techniques on an imbalanced credit card fraud detection dataset. Imbalanced datasets often lead to biased machine learning models, making it difficult to correctly predict minority class instances. Sampling methods are used to address this issue and improve overall model performance.

---

## Dataset
The dataset contains credit card transaction records categorized into two classes:
- Class 0: Legitimate transactions  
- Class 1: Fraudulent transactions  

The dataset is highly imbalanced, making it suitable for studying the effectiveness of sampling techniques.

---

## Sampling Techniques Used
The following sampling techniques are applied in this project:
- Random Over Sampling  
- Random Under Sampling  
- SMOTE (Synthetic Minority Oversampling Technique)  
- SMOTE with Tomek Links  
- No Sampling (Baseline)

---

## Machine Learning Models
Five machine learning models are trained and evaluated:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine  
- Naive Bayes Classifier  

Each model is trained using different sampling techniques to compare performance.

---

## Evaluation Metric
Model performance is evaluated using **Accuracy Score**, which measures the proportion of correctly classified instances.

---

## How to Run
1. Install all required Python libraries listed in the requirements file.
2. Run the Python program to train and evaluate the models.
3. Review the generated accuracy results for comparison.

---

## Results
The project produces an accuracy comparison table showing the performance of each machine learning model under different sampling techniques. It also highlights the best sampling method for each model.

---

## Conclusion
The results demonstrate that sampling techniques significantly influence model performance on imbalanced datasets. No single sampling method performs best across all models, emphasizing the importance of selecting appropriate techniques based on the algorithm and data characteristics.

---

## Requirements
All required Python libraries are specified in the requirements file.

---

## Author
Aviral Bhargava
