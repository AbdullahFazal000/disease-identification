🧬 Disease Identification System
This project is a Machine Learning-powered disease prediction system that identifies three diseases
— Cholera, Jaundice, and Typhoid
— based on user input features. It provides a simple Streamlit-based web interface for prediction.

📌 Features
🎯 Predicts likelihood of:

Cholera using SVM

Jaundice using Logistic Regression

Typhoid using K-Nearest Neighbors (KNN)

📊 Scales input using StandardScaler for accurate predictions

🖥️ Interactive web app built using Streamlit

🧠 Trained using real-world medical symptoms/features (demo/sample)

🚀 Getting Started

 Step-by-Step Guide to Run the Project
1. Install Python
Make sure you have Python 3.8–3.11 installed.
Check with: python --version

2. Set Up a Virtual Environment (Recommended)
cd DiseaseIdentification
python -m venv venv

Activate it:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate

3. Install Required Packages
pip install -r requirements.txt

4. Run the Streamlit App
streamlit run app.py

