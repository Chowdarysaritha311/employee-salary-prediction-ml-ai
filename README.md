Employee Salary Prediction System 🚀

This project predicts employee salaries based on multiple factors using Machine Learning and Artificial Intelligence with Python.

📌 Project Overview

An interactive Streamlit Web App that allows users to input experience, education, job role, location, and skills to predict estimated salaries using trained ML models.

📂 Folder Structure

employee-salary-prediction-advanced/
├── data/
│   ├── employee_data_basic.csv
│   └── employee_data_large.csv
├── models/
│   ├── linear_model.pkl
│   └── randomforest_model.pkl
├── notebooks/
│   └── eda_model_training.ipynb
├── streamlit_app.py
├── requirements.txt
├── README.md
└── images/
    └── app_screenshot.png

📝 Features

Linear Regression and Random Forest models

Basic and large datasets for training

Interactive Streamlit App for easy salary predictions

Clean, responsive UI

Ready-to-run notebook for training & evaluation


💻 Installation & Running the Project

Clone the Repository

git clone https://github.com/your-username/employee-salary-prediction-ml-ai.git
cd employee-salary-prediction-ml-ai

Install Dependencies

pip install -r requirements.txt

Run Streamlit App

streamlit run streamlit_app.py

📊 Dataset Description

employee_data_basic.csv : 100 rows basic dataset

employee_data_large.csv : 1000 rows larger dataset


Each dataset includes:

Experience (Years)

Education Level (Bachelors, Masters, PhD)

Job Role (Software Engineer, Data Scientist, Manager, HR, Others)

Location (Urban, Suburban, Rural)

Skills (Technical & soft skills)

Salary (Target column)


⚙️ Model Details

Linear Regression for basic prediction

Random Forest Regressor for more accurate prediction

Pickle files for direct model loading


📸 Screenshots



🚀 Deployment Options

Local Machine via Streamlit

Deployment-ready for Render or Heroku (free deployment)


🤝 Contribution

Feel free to fork this repo, improve datasets, enhance UI, or introduce more advanced models!

📢 Acknowledgement

Based on an enhanced version of the open-source project by mdsohaib.


---

Made with ❤️ using Python, Scikit-learn, and Streamlit.

