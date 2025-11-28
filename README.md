🌾 Crop Recommendation System

A Machine Learning–based project that recommends the best crop to grow based on soil and environmental conditions such as NPK values, temperature, humidity, pH, and rainfall.

📌 Project Overview

The Crop Recommendation System helps farmers make data-driven decisions.
It analyzes soil nutrients and climate conditions, and predicts the most suitable crop using trained machine learning models.

This project uses:

Python

Machine Learning (Random Forest / Decision Tree / SVM)

Flask (optional, for web interface)

Pandas, NumPy, Scikit-learn

Dataset: Crop Recommendation CSV from Kaggle

🚀 Features

✔️ Predicts the best crop to grow
✔️ Clean user interface (if using Flask)
✔️ Preprocessing of soil & climate data
✔️ Trained ML model with high accuracy
✔️ Easy to integrate with web apps

🧠 How the Model Works

The ML model takes the following inputs:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH

Rainfall

Based on these features, it predicts the most suitable crop such as rice, maize, cotton, coffee, etc.

🗂️ Project Structure
crop-recommendation/
│── dataset/
│   └── Crop_recommendation.csv
│── model/
│   └── crop_model.pkl
│── app.py  (Flask app)
│── model_training.ipynb
│── requirements.txt
└── README.md

🔧 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Flask (optional)

Pickle for model saving

🛠️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/crop-recommendation.git
cd crop-recommendation

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Train the model (optional)

Run the Jupyter notebook:

model_training.ipynb

4️⃣ Run the Flask app
python app.py


Then open the browser and go to:
👉 http://127.0.0.1:5000

📊 Model Performance

Accuracy: 90–95% (varies by model)

Best performing model: Random Forest Classifier
