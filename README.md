# ❤️ Heart Disease Prediction App

A web-based application to predict the risk of heart disease using machine learning. Built with **Python**, **Streamlit**, and a **Gradient Boosting**, this tool provides users with a quick health risk assessment based on personal health indicators.

---


## 🚀 Features

- Predict heart disease risk based on 16 health-related inputs
- Built using a trained Random Forest machine learning model
- Interactive web UI using Streamlit
- Real-time probability feedback (High Risk , Moderate Risk and Low Risk)
- Lightweight and user-friendly

---

## 🧠 Machine Learning Model

- Algorithm: `GradientBoosting`
- Framework: `scikit-learn`
- Trained on a structured dataset with health records
- Model is saved as `heart_disease_GradientBoosting.pkl`

---

## 🛠️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/Prediction_HeartDisease.git
cd Prediction_HeartDisease


### 2. Create and activate a virtual environment

python -m venv .venv
source .venv/bin/activate  # For Windows: .venv\Scripts\activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Train and save the model (if not already saved)
Skip this step if heart_disease_GradientBoosting.pkl already exists.

Run the training script:
# train_model.py (create a script to train your model)

## ▶️ Run the App
streamlit run streamlit_app.py

Access the app in your browser at:
http://localhost:8501

## 📦 Project Structure
Prediction_HeartDisease/
│
├── streamlit_app.py             # Streamlit app code
├── heart_disease_RandomForest.pkl  # Trained ML model
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
├── LICENSE                      # (Optional) License file
└── your_dataset.csv             # (Add your CSV dataset if applicable)

## 📌 Inputs Used in the Prediction
- BMI
- Smoking / Alcohol Drinking / Stroke History
- Physical & Mental Health
- Difficulty Walking
- Sex / Age Category
- Diabetic / Physical Activity
- General Health / Sleep Time
- Asthma / Kidney Disease / Skin Cancer

## ⚠️ Disclaimer
This app is intended for educational purposes only and should not be used as a substitute for professional medical diagnosis or advice.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

## 📄 License
This project is open source and available under the MIT License.

## 👩‍💻 Author
Afrida Rahman
GitHub Profile
