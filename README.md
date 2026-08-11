# 📱 Mobile Phone Price Predictor

A machine learning project that predicts **mobile phone prices based on device specifications and features**. The project compares **Linear Regression** and **Random Forest Regression** models and applies feature selection and hyperparameter tuning to improve prediction performance.

## 🎯 Project Objectives

* Develop a machine learning model to predict mobile phone prices.
* Compare the performance of **Linear Regression** and **Random Forest Regression**.
* Improve prediction accuracy through **feature selection** and **hyperparameter tuning**.
* Identify the most influential features affecting mobile phone prices.
* Build a reusable trained prediction model using a serialized `.pickle` file.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas** – Data preprocessing and analysis
* **NumPy** – Numerical computation
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and model evaluation
* **Pickle** – Model serialization

## 📂 Project Structure

```text
Mobile-Phone-Price-Predictor/
│
├── Cellphone.csv
├── MobilePricePredictor.ipynb
├── predictor.pickle
└── README.md
```

### Files

| File                         | Description                                                                                          |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| `Cellphone.csv`              | Dataset containing mobile phone specifications and prices (Download from Kaggle)                                          |
| `MobilePricePredictor.ipynb` | Jupyter Notebook containing data analysis, preprocessing, model training, evaluation, and prediction |
| `predictor.pickle`           | Serialized trained machine learning model                                                            |
| `README.md`                  | Project documentation                                                                                |

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Linear Regression
   ↓
Random Forest Regression
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Price Prediction
```

## 🤖 Machine Learning Models

### 1. Linear Regression

Linear Regression is used as a baseline model to learn the relationship between mobile phone features and their prices.

### 2. Random Forest Regression

Random Forest Regression combines multiple decision trees to capture complex relationships between phone specifications and price.

The models are compared based on their prediction performance to determine which approach is more suitable for the dataset.

## 📊 Features

The model uses mobile phone specifications as input features to estimate the expected price.

Examples of relevant phone characteristics include:

* Battery capacity
* RAM
* Internal storage
* Camera specifications
* Screen/display characteristics
* Other hardware specifications available in the dataset

## 🔍 Feature Selection

Feature selection is performed to identify the variables that contribute most to mobile phone price prediction.

This helps to:

* Reduce unnecessary features
* Improve model performance
* Reduce model complexity
* Understand which phone specifications have the greatest impact on price

## ⚙️ Hyperparameter Tuning

The Random Forest model can be optimized by tuning parameters such as:

* Number of trees
* Maximum tree depth
* Minimum samples required for splitting
* Minimum samples required at leaf nodes

Hyperparameter tuning helps identify a model configuration that provides better prediction performance.

## 📈 Model Evaluation

The trained models are evaluated using appropriate regression metrics to compare their prediction performance.

Typical evaluation metrics include:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

The evaluation results help determine which regression model provides better predictions for mobile phone prices.

## 💡 Key Insights

The project also analyzes the importance of different mobile phone specifications in determining price.

Feature importance analysis can provide useful insights into questions such as:

* Which specifications have the greatest effect on price?
* Does higher RAM contribute significantly to price?
* How does storage capacity affect phone prices?
* Which hardware characteristics are most useful for prediction?

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/KumeshaRashmi/Mobile-Phone-Price-Predictor.git
```

### 2. Navigate to the Project

```bash
cd Mobile-Phone-Price-Predictor
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook MobilePricePredictor.ipynb
```

Run the notebook cells sequentially to perform data preprocessing, model training, evaluation, and price prediction.

## 🔮 Future Improvements

* Develop a web-based prediction interface.
* Deploy the trained model as a REST API.
* Add more recent mobile phone datasets.
* Experiment with advanced regression algorithms such as Gradient Boosting and XGBoost.
* Implement automated model selection and tuning.
* Add real-time mobile phone price prediction.
* Deploy the application using cloud services.


