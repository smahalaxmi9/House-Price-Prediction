# 🏡 House Price Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict house prices using Machine Learning techniques. A Linear Regression model is trained using the Kaggle House Prices dataset to estimate house prices based on different property features.

## 🎯 Objective
To build a Machine Learning model that predicts house prices using important property characteristics.

## 📂 Dataset
**Source:** Kaggle – House Prices: Advanced Regression Techniques

The dataset contains information about residential properties, including:
- Overall Quality
- Ground Living Area
- Garage Capacity
- Total Basement Area
- Full Bathrooms
- Year Built

**Target Variable:** SalePrice

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Joblib

## ⚙️ Project Workflow
1. Import required libraries.
2. Load the housing dataset.
3. Explore and understand the dataset.
4. Identify and handle missing values.
5. Select important numerical features.
6. Split the dataset into training and testing sets.
7. Train a Linear Regression model.
8. Predict house prices.
9. Evaluate model performance.
10. Visualize actual vs predicted prices.
11. Save the trained model using Joblib.

## 🤖 Machine Learning Algorithm
**Linear Regression**

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

## 📊 Model Evaluation
The model is evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

Actual evaluation results are available in the project notebook.

## 📈 Visualization
The project includes an Actual vs Predicted House Prices scatter plot to compare model predictions with actual values.

## 💾 Model Saving
The trained model is saved as:

`house_price_model.pkl`

It can be loaded later using Joblib for making new predictions.

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/smahalaxmi9/House-Price-Prediction.git
   ```

2. Navigate to the project folder.

3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn joblib jupyter
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `House_Price_Prediction.ipynb` and run the cells.

## 🔮 Future Improvements
- Experiment with Decision Tree and Random Forest Regression.
- Improve feature selection.
- Handle categorical variables.
- Tune model parameters to improve prediction performance.
- Develop a simple web application for house price prediction.

## 👩‍💻 Author
**Mahalaxmi Sudalaimuthu**

Computer Science and Engineering Student

Interested in Artificial Intelligence and Machine Learning.
