****A 6 weeks  virtual internship organised by EDUNET in collaration with IBM SkillBuild.****

# 📊 Employee Salary Prediction with Random Forest

A machine learning-powered **web application** that predicts employee salary categories based on demographic and professional attributes. Built with **Streamlit** and powered by a trained **Random Forest Classifier**, this app offers users a quick and interactive way to classify salaries.

🧠 What This App Does
👤 User Input
Through a friendly web form interface, the user provides key information about a person such as:
- Age
- Occupation
- Education
- Work class
- Hours-per-week
- Other personal and job-related details

### 🔍 Model Prediction
- The app uses a **pre-trained machine learning model** (`best_model.pkl`)
- The model predicts the likely **salary category** (e.g., `50K`)
- Built using **Scikit-learn** Random Forest, optimized with accuracy/recall

### 💡 Use Cases
- HR analytics tools
- Showcase ML projects in interviews/portfolios
- Experimental platform for custom salary modeling

## 🖥️ Local Setup Instructions

 1. Clone This Repository
    
git clone https://github.com//salary-prediction-app.git
===============================cd salary-prediction-app
2. Install Required Libraries
Use a virtual environment (recommended) or your Python installation:
======================== pip install -r requirements.txt
 3. Run the App Locally
=========================streamlit run app.py

👉 Open your browser and go to: [http://localhost:8501](http://localhost:8501)

## 🌐 Deploy on Streamlit Cloud (Free)

You can deploy and share your app online in under 5 minutes!

### ✅ Steps:

1. **Push your code to GitHub.**  
   Include:
   - `app.py`
   - `best_model.pkl`
   - `requirements.txt`

2. **Create a Streamlit Cloud Account:**  
   Go to [https://streamlit.io/cloud](https://streamlit.io/cloud) and sign in with GitHub.

3. **Deploy Your App:**  
   - Click **"New app"**  
   - Select your GitHub repo
   - Set the Python file to run: `app.py`
   - Click **Deploy**

4. ✅ Done! Your app is now live online!  
Copy & share your custom Streamlit link anywhere.

## 📁 Project Structure
📁 salary-prediction-app/
├── app.py                    # Streamlit app
├── best_model.pkl           # Saved ML model (RandomForestClassifier)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

## 🧪 Tech Stack

| Tech             | Role                          |
|------------------|-------------------------------|
| **Python 3.10+**  | Programming Language           |
| **Streamlit**     | Web App Interface Framework    |
| **scikit-learn**  | ML model training & inference  |
| **Joblib**        | Model serialization            |
| **Pandas**        | Data wrangling & pre-processing|

## 🧠 Model Details

- Trained on modified **Adult Income Dataset**
- Binary classification (`50K`)
- Model: **Random Forest Classifier**
- Preprocessing: Label Encoding / One-hot encoding
- Accuracy optimized and saved to `best_model.pkl`

## 📈 Future Improvements

- ✅ File upload support for batch predictions
- ✅ Visual analytics dashboard (bar, pie charts)
- 🔒 User input validation & typos correction
- 🌐 Multilingual input support
- 🧾 Download prediction report as PDF/CSV
..
