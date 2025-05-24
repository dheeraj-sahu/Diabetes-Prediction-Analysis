# Diabetes-Prediction-Analysis
This repository contains a comprehensive analysis and modeling pipeline for predicting the onset of diabetes using clinical and diagnostic data. The primary objective is to explore the dataset, perform preprocessing and feature engineering, train multiple machine learning models, and evaluate their performance to identify the best approach for accurate prediction.

Table of Contents
1. Project Overview
2. Dataset
3. Installation
4. Usage
5. Project Structure
6. Analysis Workflow
7. Results
8. Contributing
9. License

# Project Overview
Prediabetes and diabetes affect millions worldwide. Early detection can help in timely intervention and management. In this project, we leverage the PIMA Indians Diabetes dataset (or similar clinical dataset) to build classification models that predict whether a patient is likely to develop diabetes based on diagnostic measurements.

Key goals:
1. Perform exploratory data analysis (EDA) to understand feature distributions and detect anomalies.
2. Clean and preprocess data, handling missing or zero values.
3. Engineer new features to improve model performance.
4. Train and compare several machine learning algorithms.
5. Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.


# Dataset
The dataset used in this analysis includes the following attributes:
- `Pregnancies`  
- `Glucose`  
- `BloodPressure`  
- `SkinThickness`  
- `Insulin`  
- `BMI`  
- `DiabetesPedigreeFunction`  
- `Age`  
- `Outcome` (0 = No diabetes, 1 = Diabetes)


## ⚙️ Technologies & Libraries

- **Python** 3.x  
- **Data handling & viz**: pandas, NumPy, matplotlib, seaborn  
- **Modeling**: scikit-learn

  ## 🚀 Pipeline Overview

1. **Data Loading & Exploration**
     ![image](https://github.com/user-attachments/assets/65fbf120-0088-4d1b-a0e7-8648ba1cbc9a)
     ![boxPlot (1)](https://github.com/user-attachments/assets/1d208cbb-df8b-4dfe-a200-aa8f9a3f49bb)


3. **Data Cleaning & Imputation**
     ![co-relation co-efficient](https://github.com/user-attachments/assets/8182823c-399d-4b89-a02f-3408db0011d3)
      ![image](https://github.com/user-attachments/assets/5a2ab821-ce64-4c03-8a44-9773cb31bef1)
     ![image](https://github.com/user-attachments/assets/b1655d95-3bfd-4a80-be1b-ddaf29c913d7)
     ![image](https://github.com/user-attachments/assets/4b45f8c2-7fde-43ea-a4d5-03eebf150596)
     ![image](https://github.com/user-attachments/assets/f97ccfa5-1dd4-4069-937b-8adf03cc8674)
     ![image](https://github.com/user-attachments/assets/8f29058e-785e-41c2-a6cf-0287d7be2cc3)
     ![image](https://github.com/user-attachments/assets/171df2d0-25f5-477d-b3f6-74c586f73d2c)
     ![image](https://github.com/user-attachments/assets/97e63d6d-7d9e-42b0-8751-ed9a335cc77a)
     ![image](https://github.com/user-attachments/assets/ea1e13fa-be90-42d9-b758-a1d414d2543e)


    ![image](https://github.com/user-attachments/assets/cffa3ffb-2fd6-4859-9788-f1d8db49691c)

   

4. **Feature Scaling**
     ![image](https://github.com/user-attachments/assets/40e24027-1517-4681-aa42-3f84c566d48a)
    ![image](https://github.com/user-attachments/assets/bbec9fad-73ee-4619-8b57-126099f5f922)
    ![image](https://github.com/user-attachments/assets/07fe96fb-634f-47d3-9ea6-5fb185c529ff)
    ![boxPlot_After_Normalization](https://github.com/user-attachments/assets/c77d6074-e230-4bea-9a02-51890b315278)


6. **Model Training**  
   - **Logistic Regression**
         ![image](https://github.com/user-attachments/assets/fad4ce87-f316-429f-b199-22bd7171b6c0)

7. **Model Evaluation**
         ![image](https://github.com/user-attachments/assets/edb6a56c-6f7e-49fb-82d4-a97b76bcfa38)
         ![image](https://github.com/user-attachments/assets/0483320f-e14d-40f0-bb32-3ec495e0605c)
   - Accuracy score
        ![image](https://github.com/user-attachments/assets/c6de56b7-8e0a-476b-a5c3-af77d622cdab)
     
   - Confusion matrix
         ![image](https://github.com/user-attachments/assets/c46a05c8-0cc4-4a45-88e4-66df249c70c8)

   - Classification report
         ![image](https://github.com/user-attachments/assets/7cbdca96-3319-48ed-a3d5-ea9662785a62)


## 🛠 How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-analysis.git
   cd diabetes-prediction-analysis

2. **Create & activate a virtual environment**
     -python3 -m venv venv
     -source venv/bin/activate   # macOS/Linux
     -venv\Scripts\activate      # Windows
3. **Install dependencies**
     -pip install -r requirements.txt
4. **Launch the notebook**
     -jupyter notebook Diabetes_Prediction_Analysis.ipynb
   

