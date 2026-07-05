Stress Level Prediction System
Project Overview

The Stress Level Prediction System is a machine learning application developed to predict an individual's stress level based on user-provided information. The project uses two supervised machine learning algorithms—K-Nearest Neighbors (KNN) and Decision Tree—to classify stress levels accurately. The application features an interactive web interface built with Streamlit, allowing users to enter their details and receive instant predictions.

Features
Predicts stress levels using machine learning.
Supports both KNN and Decision Tree algorithms.
Interactive and user-friendly interface developed with Streamlit.
Real-time prediction based on user inputs.
Fast and efficient performance.
Easy to extend with additional models and features.
Technologies Used
Python
Streamlit
Scikit-learn
Pandas
NumPy
Joblib
Machine Learning Models
K-Nearest Neighbors (KNN)

KNN is a supervised learning algorithm that classifies a new data point by comparing it with its nearest neighbors in the training dataset. The predicted class is determined by the majority vote of the nearest neighbors.

Decision Tree

Decision Tree is a supervised learning algorithm that predicts the output by creating a tree-like structure of decisions. It splits the data based on feature values and follows decision rules until a final prediction is reached.

How the System Works
The user opens the Streamlit web application.
The user enters the required input values.
The input data is preprocessed.
The selected machine learning model (KNN or Decision Tree) analyzes the data.
The application predicts the user's stress level.
The prediction is displayed instantly on the screen.
Project Structure
app.py – Streamlit application.
train_model.py – Script used to train the machine learning models.
knn_model.pkl – Saved KNN model.
decision_tree.pkl – Saved Decision Tree model.
dataset.csv – Dataset used for training and testing.
requirements.txt – List of required Python libraries.
README.md – Project documentation.
Installation
Clone or download the project.
Install the required libraries using:
pip install -r requirements.txt
Run the Streamlit application:
streamlit run app.py
Expected Input

The application accepts user information such as:

Age
Gender
Sleep Duration
Working Hours
Physical Activity
Study Hours
Screen Time
Social Interaction
Other stress-related features included in the dataset
Output

The application predicts the user's stress level, such as:

Low Stress
Moderate Stress
High Stress
Advantages
Simple and easy-to-use interface.
Quick and accurate stress prediction.
Compares two popular machine learning algorithms.
Suitable for educational and research purposes.
Can be expanded with additional features and models.
Future Enhancements
Improve prediction accuracy with advanced algorithms.
Add graphical visualizations of results.
Deploy the application online using Streamlit Cloud.
Store user prediction history.
Include more health and lifestyle parameters for better prediction.
