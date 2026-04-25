🩺 Multiple Disease Prediction System


A Machine Learning-based web application that predicts the likelihood of multiple diseases:
- Diabetes
- Heart Disease
- Parkinson’s Disease
This project integrates multiple trained ML models into a single user-friendly interface using Streamlit.


🚀 Features

🔍 Predicts multiple diseases in one platform
🧠 Uses different ML algorithms for better accuracy
💻 Interactive web interface using Streamlit
⚡ Real-time predictions
📦 Pre-trained models for fast performance


🗂️ Project Structure


├── saved_models/

│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav

├── app.py
├── Multiple disease prediction system - diabetes.ipynb
├── Multiple disease prediction system - heart.ipynb
├── Multiple disease prediction system - Parkinsons.ipynb

├── datasets/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv

├── requirements.txt
└── README.md


⚙️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- Streamlit

  
🧠 Machine Learning Models

1. Diabetes Prediction
   
- Algorithm: Support Vector Machine (SVM)
- Dataset: PIMA Diabetes Dataset
- Accuracy:
    - Training: ~78%
    - Testing: ~77%
 
      
2. Heart Disease Prediction
   
- Algorithm: Logistic Regression
- Dataset: Heart Disease Dataset
- Accuracy:
     - Training: ~85%
     - Testing: ~82%
 
       
4. Parkinson’s Prediction
   
- Algorithm: Support Vector Machine (SVM)
- Dataset: Parkinson’s Dataset
- Accuracy:
     - Training: ~87%
     - Testing: ~87%
 
       
💻 Web Application

The application is built using Streamlit and provides:
- Sidebar navigation for selecting disease
- Input fields for medical parameters
- Instant prediction results

  
▶️ How to Run the Project

1. Clone the Repository
Bash
git clone https://github.com/your-username/multiple-disease-prediction-ml-app.git
cd multiple-disease-prediction-ml-app
2. Install Dependencies
Bash
pip install -r requirements.txt
3. Run the Application
Bash
streamlit run app.py


🧪 Input Parameters

Diabetes

- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
  
Heart Disease

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Heart Rate
- And other clinical features

Parkinson’s

- Voice frequency measures
- Jitter and Shimmer values
- Other biomedical voice features

  
⚠️ Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical advice or diagnosis.


📌 Future Improvements

Add more disease prediction models
Improve accuracy using advanced algorithms
Deploy the app online
Add user authentication and history tracking


👨‍💻 Author
Kousik Chakraborty
