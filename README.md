# 🧠 ADHD & Sex Prediction Model — Machine Learning Project

## 🎯 Project Overview

This project aims to develop a predictive machine learning model capable of:

1. **Predicting a person's sex**, and  
2. **Determining whether the person may suffer from ADHD**,  

...based on a rich set of features extracted from **socio-demographic**, **emotional**, and **parenting** questionnaires.

The dataset contains multidimensional information that is preprocessed, analyzed, and used to train multiple models in a two-stage pipeline designed to improve performance and generalization.

---

## 🧱 Project Structure

### 🔹 Stage 1 – Data Preprocessing & Feature Engineering

In the first stage, the project:

- Cleans the dataset:  
  - Removes unnecessary features  
  - Handles missing values (NaNs)  
- Performs **exploratory data analysis (EDA)** through:  
  - Count plots  
  - Box plots  
  - Correlation matrices  
- Scales the features using a preferred scaler  
- Applies **skewness correction**  
- Reduces dimensionality using **PCA (Principal Component Analysis)**  
- Outputs clean **training and test sets**, ready for modeling

### 🔹 Stage 2 – Model Training & Evaluation

The second stage is focused on building, training, and evaluating the models:

- Applies **Cross-Validation**, **Data Augmentation**, and **Ensembling** to tackle class imbalance and improve robustness
- Trains **four different base models** to handle the four prediction classes
- Builds a **meta-model** to generalize predictions across different patient data
- Includes a detailed **performance analysis** of the trained models, identifying strengths and weaknesses

---

## ⚙️ How to Run the Project

To run this project successfully, follow these steps:

### 1. Make sure the following files are in the same folder as the notebooks:

- `METADATA_A.xlsx`  
- `METADATA_B.xlsx`  
- `FUNCTIONAL_CONNECTOME_MATRICES.csv`  
- `LABELS.xlsx`

### 2. Run the Preprocessing Notebook

Execute `DS_Stage1_JVelasquez.ipynb` (or `DS_Stage1_Version2.ipynb`, depending on your version).  
This will generate the processed datasets required for model training.

### 3. Run the Model Training Notebook

Once preprocessing is complete, run `DS_Stage2_JVelasquez.ipynb` to train the models and evaluate performance.

---

## 💻 Technologies Used

- Python 3  
- Jupyter Notebook  
- pandas, NumPy, scikit-learn  
- matplotlib, seaborn  
- PCA, data augmentation & ensembling techniques

---

## 📌 Notes

This project was part of an academic machine learning challenge, with a real-world application in understanding behavioral and neurological patterns. It focuses on interpretability, rigorous preprocessing, and thoughtful modeling — essential steps in building reliable health-related AI systems.

---

## 📬 Contact

Project developed by **J. Velasquez**  
Feel free to reach out with questions, feedback, or ideas for collaboration!

