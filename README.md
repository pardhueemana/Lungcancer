Lung Cancer Prediction using Machine Learning
📌 Project Overview

This project is a Lung Cancer Prediction System built using Machine Learning and deployed with Streamlit. The application predicts the likelihood of lung cancer based on user-provided health and lifestyle information. It provides an easy-to-use web interface where users can enter their details and receive an instant prediction.

🚀 Features
User-friendly Streamlit web application
Real-time lung cancer prediction
Machine Learning-based classification model
Simple and interactive interface
Fast prediction results
🛠️ Technologies Used
Python
Streamlit
Scikit-learn
Pandas
NumPy
Pickle
📂 Project Structure
Lung-Cancer-Prediction/
│
├── app.py
├── lungcancer_model.sav
├── prepocessed_lungs_data.csv
├── survey lung cancer.csv
├── LungCancerPrediction.ipynb
├── requirements.txt
└── README.md
📊 Dataset

The dataset contains various health and lifestyle attributes such as:

Age
Gender
Smoking Habit
Yellow Fingers
Anxiety
Peer Pressure
Chronic Disease
Fatigue
Allergy
Wheezing
Alcohol Consumption
Coughing
Shortness of Breath
Swallowing Difficulty
Chest Pain

These features are used to predict the likelihood of lung cancer.

⚙️ Installation
Clone the Repository
git clone https://github.com/yourusername/Lung-Cancer-Prediction.git
cd Lung-Cancer-Prediction
Create Virtual Environment (Optional)
python -m venv venv
Activate Virtual Environment
Windows
venv\Scripts\activate
Linux/Mac
source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
▶️ Running the Application

Run the Streamlit application using:

streamlit run app.py

The application will start locally at:

http://localhost:8501
📈 Machine Learning Model

The prediction model was trained using a supervised machine learning algorithm on preprocessed lung cancer survey data. The trained model is stored as:

lungcancer_model.sav

and loaded into the Streamlit application for real-time predictions.

🌐 Deployment

This project can be deployed using:

Streamlit Community Cloud
Render
Railway
AWS
Azure
Streamlit Cloud Deployment
Push the project to GitHub.
Sign in to Streamlit Community Cloud.
Create a new app.
Select your GitHub repository.
Set the main file as:
app.py
Click Deploy.
📷 Application Workflow
User enters health-related details.
Data is processed and converted into model input.
The trained machine learning model predicts the result.
The prediction is displayed instantly on the screen.
🎯 Future Enhancements
Improved model accuracy
Enhanced UI/UX
Model explainability using SHAP
Support for additional medical features
Cloud database integration
👨‍💻 Author

Pardhu

Graduate | Machine Learning & AI Enthusiast

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

📄 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this project for educational and research purposes.
