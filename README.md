# LiverCirrhosisPrediction
 Liver Cirrhosis Prediction using Machine LearningMore actions
# Liver Cirrhosis Prediction using Machine Learning
A machine learning-based web application that predicts whether a patient is suffering from liver cirrhosis using clinical, diagnostic, and demographic information.

📌 Project Title
Revolutionizing Liver Care: Predicting Liver Cirrhosis using Advanced Machine Learning Techniques

📁 Project Structure
bash
Copy
Edit
LiverCirrhosisPrediction/
├── app/                  # Flask web app
│   ├── app.py            # Flask backend
│   ├── templates/
│   │   ├── index.html    # Form for user input
│   │   └── result.html   # Display prediction
├── training/
│   ├── train.py          # Model training script
│   ├── model.pkl         # Trained model
│   ├── train_columns.joblib  # Feature columns
├── Data/
│   └── HealthCareData.xlsx  # Dataset
└── README.md             # Project documentation
📊 Dataset

# 📊 Dataset
Source: Collected healthcare data related to liver conditions.

Format: .xlsx Excel file with 41 columns (including 1 target column and 40 input features).

Target:
# Target:

1 = Patient has liver cirrhosis

@@ -47,7 +31,7 @@ Lab results: RBC, WBC, Hemoglobin, Bilirubin, SGOT, SGPT, etc.

Full list in the Dataset Description.

🛠️ Technologies Used
# 🛠️ Technologies Used
Frontend: HTML, CSS, Bootstrap (in index.html)

Backend: Flask (Python Web Framework)
@@ -56,7 +40,7 @@ ML Model: Random Forest Classifier

Libraries: Pandas, NumPy, scikit-learn, joblib

⚙️ How It Works
# ⚙️ How It Works
The user enters patient details through a web form.

The Flask backend processes the input and sends it to the trained model.
@@ -65,11 +49,11 @@ The model predicts whether the patient has liver cirrhosis.

The result is displayed to the user.

🚀 Getting Started
# 🚀 Getting Started
Prerequisites
Python 3.9+

Install dependencies:
# Install dependencies:

bash
Copy
@@ -92,7 +76,7 @@ cd ../app
python app.py
Visit: http://127.0.0.1:5000/ in your browser.

🧠 Model Details
# 🧠 Model Details
Algorithm: RandomForestClassifier

Pipeline:
@@ -103,13 +87,13 @@ Numerical features → StandardScaler

Evaluation: Accuracy, Confusion Matrix (optional extension)

✅ Future Enhancements
# ✅ Future Enhancements
Add user authentication

Deploy on cloud (e.g., Heroku or Render)

Add EDA and model explainability (SHAP/LIME)

📬 Contact
# 📬 Contact
Mohana priya kalva
St. Ann's College of Engineering and Technology
