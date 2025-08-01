# Heart_Disease-Prediction
🫀 Heart Disease Prediction Project
This project uses machine learning to predict whether a patient has heart disease based on medical attributes. It includes data preprocessing, model training, evaluation, and a Flask-based web application for real-time predictions.

📌 Features
Built a logistic regression model to predict heart disease with cross-validation.

Preprocessed data with 20% missing values to improve model accuracy.

Deployed a web app using Flask and REST API for user-friendly predictions.

Jupyter Notebook for training and analysis included.

🧰 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib

Framework: Flask

Platform: Google Colab

🗂️ Repository Structure
php
Copy
Edit
├── Heart_Disease_Prediction.ipynb    # Model training and analysis (Colab Notebook)
├── app.py                            # Flask backend for prediction
├── templates/
│   └── index.html                    # Frontend UI
├── static/
│   └── style.css                     # Styling
├── dataset.csv                       # Heart disease dataset
└── README.md                         # Project documentation
🚀 How to Run Locally
Clone the repo:

bash
Copy
Edit
git clone https://github.com/MahimaGupta12/Heart_Disease-Prediction-Project.git
cd Heart_Disease-Prediction-Project
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
python app.py
Open http://localhost:5000 in your browser.

📊 Dataset Description
The dataset contains medical information such as:

Age, Sex, Chest Pain Type

Resting Blood Pressure

Serum Cholesterol

Maximum Heart Rate Achieved

ST Depression, Exercise Induced Angina, etc.


