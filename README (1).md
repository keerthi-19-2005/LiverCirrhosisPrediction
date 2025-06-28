LiverCirrhosisPrediction
Liver Cirrhosis Prediction using Machine Learning
A machine learning-based web application that predicts whether a patient is suffering from liver cirrhosis using clinical, diagnostic, and demographic information.

📌 Project Title Revolutionizing Liver Care: Predicting Liver Cirrhosis using Advanced Machine Learning Techniques

📊 Dataset
Source: Collected healthcare data related to liver conditions.

Format: .xlsx Excel file with 41 columns (including 1 target column and 40 input features).

Target:
1 = Patient has liver cirrhosis

0 = Patient does NOT have liver cirrhosis

Features include: Demographics: Age, Gender, Location

Alcohol Usage: Duration & Quantity

Viral infections: Hepatitis B & C

Health indicators: Diabetes, Obesity, Blood Pressure

Lab results: RBC, WBC, Hemoglobin, Bilirubin, SGOT, SGPT, etc.

Full list in the Dataset Description.

🛠️ Technologies Used
Frontend: HTML, CSS, Bootstrap (in index.html)

Backend: Flask (Python Web Framework)

ML Model: Random Forest Classifier

Libraries: Pandas, NumPy, scikit-learn, joblib

⚙️ How It Works
The user enters patient details through a web form.

The Flask backend processes the input and sends it to the trained model.

The model predicts whether the patient has liver cirrhosis.

The result is displayed to the user.

🚀 Getting Started
Prerequisites Python 3.9+

Install dependencies:
bash Copy Edit pip install -r requirements.txt Running the App Train the model:

bash Copy Edit cd training python train.py Launch the Flask app:

bash Copy Edit cd ../app python app.py Visit: http://127.0.0.1:5000/ in your browser.

🧠 Model Details
Algorithm: RandomForestClassifier

Pipeline:

Categorical features → OneHotEncoding

Numerical features → StandardScaler

Evaluation: Accuracy, Confusion Matrix (optional extension)

✅ Future Enhancements
Add user authentication

Deploy on cloud (e.g., Heroku or Render)

Add EDA and model explainability (SHAP/LIME)

📬 Contact
karneti keerthi St. Ann's College of Engineering and Technology
