
Title:
Heart Disease Prediction Dashboard

README
Project Overview
The Heart Disease Prediction Dashboard is an interactive web application designed to predict the likelihood of heart disease based on user input. Built using Streamlit, this tool allows users to input clinical parameters and receive real-time predictions using a pre-trained Random Forest model.

The primary objective of this application is to assist medical professionals and individuals in assessing the risk of heart disease, providing a user-friendly and accessible interface for predictions.

Features
User-Friendly Input Form:
Enter key clinical parameters such as age, sex, blood pressure, cholesterol, and more.
Real-Time Predictions:
Receive instant predictions based on a machine learning model trained on heart disease data.
Interactive Design:
Use dropdowns, sliders, and input boxes to customize data entry.
Technologies Used
Python: Core programming language.
Streamlit: Framework for creating the interactive dashboard.
Scikit-Learn: Machine learning library used to train and load the prediction model.
Joblib: Library for model and encoder serialization.
How to Run the Dashboard
Prerequisites:

Python 3.7 or higher
Install the required Python libraries using:
bash
Copy code
pip install streamlit scikit-learn pandas
Files Included:

final_random_forest_model.pkl: Trained Random Forest model.
label_encoder.pkl: Label encoder for categorical variables like sex.
app.py: Main application script for the Streamlit dashboard.
Run the Application:
Navigate to the directory containing app.py and run:

bash
Copy code
streamlit run app.py
Access the Dashboard:

Open the URL displayed in your terminal (usually http://localhost:8501) in a web browser.
User Input Parameters
Parameter	Description	Input Type
age	Age of the individual (years).	Numeric Input
sex	Biological sex (Male or Female).	Dropdown
cp	Chest pain type (0-3).	Dropdown
trestbps	Resting blood pressure (mm Hg).	Numeric Input
chol	Serum cholesterol (mg/dl).	Numeric Input
fbs	Fasting blood sugar > 120 mg/dl (0: False, 1: True).	Dropdown
restecg	Resting electrocardiographic results (0-2).	Dropdown
thalach	Maximum heart rate achieved.	Numeric Input
exang	Exercise-induced angina (0: No, 1: Yes).	Dropdown
oldpeak	Depression induced by exercise relative to rest (numeric, typically between 0.0 and 6.0).	Numeric Input
slope	Slope of the peak exercise ST segment (0-2).	Dropdown
ca	Number of major vessels (0-3) colored by fluoroscopy.	Dropdown
thal	Thalassemia (3: Normal, 6: Fixed defect, 7: Reversible defect).	Dropdown
Prediction
The model predicts the following outcomes:

1: High risk of heart disease.
0: Low or no risk of heart disease.
Credits
Developed by a passionate data scientist to promote awareness and prevention of heart disease through technology.

Feel free to reach out for questions or suggestions!
