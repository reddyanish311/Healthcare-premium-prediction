🏥 Healthcare Premium Prediction
This project predicts annual healthcare insurance premiums based on user demographics and lifestyle details. It leverages machine learning models and is deployed as an interactive Streamlit web application.

🔗 Live Demo: [Try the App](https://healthcare-predict.streamlit.app/)

📌 Project Features
Predicts insurance premiums for two user groups:

Young individuals (typically under a defined age threshold)

Rest of the population

Input-driven prediction via a user-friendly web interface

Separate models and scalers optimized for different user types

Built using XGBoost, scikit-learn, and Streamlit

🗂️ Repository Structure
bash
Copy
Edit
├── artifacts/
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib
├── app.py                   # Streamlit frontend logic
├── requirements.txt         # Project dependencies
└── README.md
⚙️ How to Run Locally
Clone the repository

bash
Copy
Edit
git clone [https://github.com/reddyanish311/healthcare-premium-predictor.git](https://github.com/reddyanish311/Healthcare-premium-prediction.git)
cd healthcare-premium-predictor
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
📦 Requirements
joblib==1.3.2

pandas==2.0.2

streamlit==1.22.0

numpy==1.25.0

scikit-learn==1.3.0

xgboost==2.0.3

📈 Model Details
Models were trained using features such as age, BMI, smoking status, number of children, etc.

Feature scaling applied using StandardScaler from scikit-learn

Two separate XGBoost models trained for performance optimization across different age groups

🙌 Acknowledgements
This project was developed as part of a portfolio to demonstrate end-to-end ML deployment using Streamlit.

