# 💓 Heart Disease Prediction

This project uses machine learning algorithms to predict the likelihood of a person having heart disease based on various medical parameters. It aims to assist in early diagnosis by analyzing health data and providing accurate predictions.

---

## 📊 Dataset

- **Source**: UCI Heart Disease Dataset
- **Attributes Used**:
  - Age
  - Sex
  - Chest Pain Type (cp)
  - Resting Blood Pressure (trestbps)
  - Cholesterol (chol)
  - Fasting Blood Sugar (fbs)
  - Resting ECG (restecg)
  - Max Heart Rate (thalach)
  - Exercise Induced Angina (exang)
  - ST Depression (oldpeak)
  - Slope of ST Segment (slope)
  - Number of Vessels Colored (ca)
  - Thalassemia (thal)
  - Target (0 = No disease, 1 = Disease)

---

## 🧠 Algorithms Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Support Vector Machine  

Models are trained and evaluated based on **accuracy, precision, recall, and F1-score**.

---

## 📌 Features

- Clean and preprocessed dataset
- Exploratory Data Analysis (EDA)
- Model training and comparison
- Prediction on user input
- Accuracy and metric reporting

---

## 🚀 Getting Started

2. Create a virtual environment
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
Copy
Edit
pip install -r requirements.txt
4. Run the project
You can open and run the Jupyter Notebook or Python script:

Copy
Edit
jupyter notebook
📁 Project Structure
Copy
Edit
Heart-Disease-Prediction/
├── data/                     # Dataset files
├── models/                   # Trained models (if any)
├── notebooks/                # Jupyter Notebooks
├── src/                      # Python scripts
├── submission.md             # Summary of approach and learnings
├── README.md                 # This file
└── requirements.txt          # Dependencies
✅ Results
The best-performing model achieved XX% accuracy on the test set (update with actual result). Performance metrics like precision, recall, and confusion matrix are also provided.

🙋‍♂️ Author
Mitravind Samantara
mitravind07@gmail.com

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.
