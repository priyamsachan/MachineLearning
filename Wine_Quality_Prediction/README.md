# 🍷 Wine Quality Prediction using Machine Learning  

## 📌 Overview  
This project predicts the quality of red wine based on its **physicochemical properties** using **machine learning techniques**. The goal is to build an **accurate prediction model** and identify the key factors that influence wine quality.  

## 📊 Dataset  
The dataset contains various chemical properties of red wine samples along with their corresponding quality ratings. It includes features such as:  
- **Acidity levels (fixed, volatile, citric acid)**
- **Sugar content**
- **pH levels**
- **Sulfur dioxide concentration**
- **Alcohol percentage**
- **Density & other key factors**  

## 🔍 Project Workflow  
### 1️⃣ Data Loading & Exploration  
- Load and inspect the dataset  
- Identify missing values & data inconsistencies  
- Perform statistical analysis  

### 2️⃣ Data Cleaning & Preprocessing  
- Handle missing values using **mean imputation**  
- Normalize and scale numerical features  
- Perform feature selection based on correlation analysis  

### 3️⃣ Data Visualization  
- Generate **histograms, scatter plots, and box plots** to analyze relationships between features and wine quality  
- Identify **key factors impacting quality**  

### 4️⃣ Model Training & Optimization  
- **Splitting dataset** into training and test sets  
- Implement **Random Forest Regression** for prediction  
- **Optimize hyperparameters** using **GridSearchCV**  

### 5️⃣ Model Evaluation  
- Assess model performance using:  
  - **R-squared (R²)**  
  - **Root Mean Squared Error (RMSE)**  
  - **Mean Absolute Error (MAE)**  

## 🛠️ Tech Stack & Skills  
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- **Machine Learning** (Random Forest Regression)  
- **Data Preprocessing & Feature Engineering**  
- **Data Visualization & Analysis**  
- **Hyperparameter Tuning & Model Optimization**  

## 🚀 How to Run  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/priyamsachan/MachineLearning/Wine_Quality_Prediction.git 
cd Wine_Quality_Prediction
```
2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```
3️⃣ Run the **Jupyter Notebook**:  
```bash
jupyter notebook
```
4️⃣ Open `Wine_Quality_Prediction_Analysis.ipynb` and execute the cells step by step.

## 📌 Results & Insights  
- **Key physicochemical factors influencing wine quality** were identified.  
- The **Random Forest Regression model achieved high accuracy**, making it effective for wine quality prediction.  
- The project provides insights that **could assist winemakers and consumers** in making informed decisions.  

## 🎯 Future Improvements  
- Experimenting with **other ML models** (e.g., XGBoost, Neural Networks)  
- Enhancing feature engineering techniques  
- Deploying the model as a **web-based application**  

## 📢 Contributing  
Pull requests are welcome! Feel free to **fork** the repository and contribute improvements.  

## 📜 License  
This project is licensed under the **MIT License**.  

---

Let me know if you'd like to modify or add anything! 🚀
