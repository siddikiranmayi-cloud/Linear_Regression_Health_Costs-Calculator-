## Linear Regression Health Costs Calculator


Overview

This project is part of the Machine Learning with Python certification by freeCodeCamp. The goal is to build a machine learning model that predicts individual healthcare expenses using demographic and lifestyle information.

Objective

Develop a regression model that can accurately estimate medical insurance costs based on the following features:

- Age
- Sex
- Body Mass Index (BMI)
- Number of children
- Smoking status
- Region

The project meets the freeCodeCamp requirement of achieving a Mean Absolute Error (MAE) below $3500 on the test dataset.

Dataset

The dataset contains health insurance records with the following columns:

- "age"
- "sex"
- "bmi"
- "children"
- "smoker"
- "region"
- "expenses" (target variable)

Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Google Colab

Project Workflow

1. Load the insurance dataset.
2. Convert categorical features into numerical values using one-hot encoding.
3. Split the dataset into 80% training data and 20% testing data.
4. Separate the target ("expenses") from the input features.
5. Normalize the input data.
6. Build and train a neural network regression model.
7. Evaluate the model using Mean Absolute Error (MAE).
8. Visualize predicted versus actual healthcare costs.

Results

- Successfully trained a regression model for healthcare cost prediction.
- Achieved the required MAE below $3500, satisfying the freeCodeCamp project requirements.

Repository Structure

├── health_cost_prediction.ipynb
├── README.md
└── insurance.csv

How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries if needed.
4. Run all notebook cells in order.
5. Evaluate the trained model and view the prediction graph.

Learning Outcomes

- Data preprocessing
- Feature encoding
- Data normalization
- Regression using TensorFlow/Keras
- Model evaluation with MAE
- Visualization of predictions

Acknowledgements

This project was completed as part of the Machine Learning with Python certification by freeCodeCamp.
