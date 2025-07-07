🏦 Customer Churn Prediction Using Deep Learning
This project is an end-to-end deep learning solution to predict customer churn in a bank. It uses an Artificial Neural Network (ANN) built with TensorFlow/Keras, and is deployed as an interactive web application with Streamlit. The goal is to help banks identify customers who are likely to leave, allowing them to take proactive retention measures.

📊 Dataset
The dataset comes from a simulated bank customer churn scenario, containing 10,000 customer records with the following features:

CreditScore: Customer credit score

Geography: Country of residence (France, Spain, Germany)

Gender: Male/Female

Age: Customer age

Tenure: Years with the bank

Balance: Account balance

NumOfProducts: Number of products the customer has with the bank

HasCrCard: Whether the customer has a credit card (1 or 0)

IsActiveMember: Whether the customer is an active member (1 or 0)

EstimatedSalary: Estimated yearly salary

Exited: Target variable — 1 if the customer churned, 0 otherwise

⚙️ Tech Stack
✅ Data Processing & Modeling

Python

Pandas, NumPy

scikit-learn

TensorFlow / Keras

✅ Model Deployment

Streamlit

✅ Artifacts & Versioning

Pickle for encoders/scalers

HDF5 (model.h5) for the trained ANN

