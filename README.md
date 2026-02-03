# Boston House Prices: Non-Linear Regression Prediction
<!-- Titolo principale del progetto -->

This project analyzes and predicts Boston housing prices using **Non-Linear (Polynomial) Regression** techniques.  
The goal is to explore how various socio-economic and structural features influence property values,  
with a particular focus on the **number of rooms (RM)** and the **socio-economic status of the population (LSTAT)**.


## 📂 Project Structure
<!-- Spiega i file e la struttura della repository -->
- **boston.csv**: Original dataset containing 506 samples and 14 variables (Target: `MEDV`).  
- **Boston_house_predictions.ipynb**: Main notebook with **Exploratory Data Analysis (EDA)**, **data preprocessing**, and **polynomial regression implementation**.  
- **CH04_SEC05_1_CrossValidate.ipynb**: Notebook dedicated to **model validation** using **Cross-Validation** techniques.  
- **Final_Report_Boston_Houses.pdf**: Comprehensive report documenting the full workflow, from **data cleaning** to **final conclusions**.  

---

## 🛠️ Tech Stack
<!-- Elenco delle librerie e tecnologie usate -->
- **Python**  
- **Pandas & NumPy**: Data manipulation and numerical computations  
- **Scikit-Learn**: Data scaling, polynomial feature generation, and regression modeling  
- **Matplotlib & Seaborn**: Data visualization and 3D plotting  

---

## 📈 Methodology
<!-- Spiega il workflow del progetto -->
1. **Data Preprocessing**  
   - Correlation analysis and feature scaling using `StandardScaler`.  
2. **Feature Selection**  
   - Identify the most influential variables (**RM** and **LSTAT**) using correlation matrices.  
3. **Modeling**  
   - Comparison of **Linear vs. Polynomial Regression**  
   - Degree 2 polynomial models to capture **non-linear relationships**  
4. **Visualization**  
   - 3D plots to compare the **prediction plane** with actual data distribution  
5. **Validation**  
   - Performance assessment using **Mean Squared Error (MSE)** and **Cross-Validation**  

---

## 🚀 Key Results
<!-- Evidenzia i risultati principali -->
- **Correlation**: Strong positive correlation between number of rooms (**RM**) and price; strong negative correlation with percentage of lower-status population (**LSTAT**).  
- **Performance**: Polynomial regression outperformed linear regression, achieving **higher R²** and **lower MSE**, effectively capturing the curvature in real-world data.  

---

## 🔧 Installation & Usage
<!-- Istruzioni per installare ed eseguire il progetto -->
1. Clone the repository:  
```bash
git clone https://github.com/your-username/boston-house-predictions.git
