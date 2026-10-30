🛒 E-commerce Customer Spending Prediction using Polynomial Regression

📌 Project Overview

This project uses Machine Learning to predict the yearly amount spent by e-commerce customers based on their online shopping behavior and membership details.

A Polynomial Regression model is developed to understand non-linear relationships between customer activity and yearly spending.

🎯 Project Objectives

- Analyze e-commerce customer data.
- Understand customer shopping behavior.
- Identify factors related to yearly spending.
- Build a Polynomial Regression model.
- Predict the yearly spending of customers.
- Evaluate the model's prediction performance.

📂 Dataset Information

- Dataset: Ecommerce Customers Dataset
- Total Records: 500 customers
- Input Features:
  - Average Session Length
  - Time on App
  - Time on Website
  - Length of Membership
- Target Variable: Yearly Amount Spent

🛠️ Technologies and Libraries

- Python
- Pandas – Data handling and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine Learning
- Joblib – Model saving
- Google Colab – Development environment

🤖 Machine Learning Algorithm

Polynomial Regression

Polynomial Regression is a regression technique that models non-linear relationships between input features and a numerical target variable.

In this project, it is used to predict the yearly amount spent by customers.

⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the e-commerce customer dataset.
3. Explore and understand the dataset.
4. Select input features and the target variable.
5. Split the dataset into training and testing sets.
6. Apply Polynomial Feature Transformation.
7. Train the Linear Regression model.
8. Generate predictions.
9. Evaluate model performance.
10. Visualize the actual and predicted results.
11. Save the trained model and transformer.

📊 Model Evaluation

The model is evaluated using:

- MAE (Mean Absolute Error): Measures the average absolute prediction error.
- MSE (Mean Squared Error): Measures the average squared prediction error.
- R² Score: Measures how well the model explains variations in customer spending.

Refer to the notebook for the actual evaluation results.

📁 Project Structure

Ecommerce-Customer-Polynomial-Regression/
│
├── Ecommerce_Polynomial_Regression.ipynb
├── README.md
└── requirements.txt

▶️ How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries.
3. Load the dataset.
4. Run the notebook cells in sequence.
5. View the predictions and evaluation results.

💡 Key Learning Outcomes

- Understanding Polynomial Regression.
- Working with customer datasets.
- Performing feature transformation.
- Training and evaluating regression models.
- Making numerical predictions.
- Saving trained Machine Learning models.

🔮 Future Improvements

- Experiment with different polynomial degrees.
- Compare different regression algorithms.
- Improve prediction performance through feature engineering.
- Test the model with new customer data.

📝 Conclusion

This project demonstrates how Polynomial Regression can be applied to e-commerce data to predict customer yearly spending. It provides practical experience in data preprocessing, feature transformation, model training, evaluation, and prediction using Python.

---

Project Category: Machine Learning | Regression
Level: Beginner
Environment: Google Colab
