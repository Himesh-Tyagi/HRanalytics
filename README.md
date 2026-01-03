# 📊 HR Analytics & Employee Attrition Prediction

## 💡 Project Overview
HR Analytics & Employee Attrition Prediction is a data science and machine learning project designed to analyze employee data and predict the likelihood of employee attrition. The project helps organizations understand key factors influencing employee turnover and supports data-driven decision-making for retention strategies.

This project also includes a simple web application to interact with the trained model and generate real-time attrition predictions.

---

## 🎯 Objectives
- Analyze HR data to identify patterns and trends
- Predict employee attrition using machine learning
- Provide actionable insights for HR teams
- Build an interactive web app for prediction

---

## 📁 Repository Structure
```
HRanalytics/
│
├── hr_analytics code with web app.ipynb   # Data analysis, model building & app logic
├── hrapp.py                              # Web application script
├── hrdataset (1).csv                     # HR employee dataset
├── hr.pkl                                # Trained machine learning model
├── schr.pkl                              # Saved scaler / preprocessing object
├── requirements.txt                      # Project dependencies
└── README.md                             # Project documentation
```

---

## 📊 Dataset Description
The dataset contains employee-related information such as:
- Age
- Gender
- Job Role
- Monthly Income
- Years at Company
- Performance Rating
- Work-Life Balance
- Attrition (target variable)

---

## 🧠 Machine Learning Workflow
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Evaluation
- Model Serialization (`.pkl` files)
- Web App Integration

---

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Streamlit (for web app)**
- **Jupyter Notebook**

---

## 🚀 How to Run the Project

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/Himesh-Tyagi/HRanalytics.git
cd HRanalytics
```

### 🔹 Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Run the Jupyter Notebook
```bash
jupyter notebook "hr_analytics code with web app.ipynb"
```

### 🔹 Step 4: Run the Web Application
```bash
python hrapp.py
```
Open the local server URL shown in the terminal to access the web app.

---

## 📈 Key Outcomes
- Identified major factors affecting employee attrition
- Built a predictive ML model for attrition
- Enabled real-time predictions through a web interface
- Improved understanding of HR analytics concepts

---

## 🔮 Future Enhancements
- Add advanced models (Random Forest, XGBoost)
- Deploy application on cloud platforms
- Create interactive dashboards for HR KPIs
- Improve model accuracy with feature tuning

---

## 👨‍💻 Author
**Himesh Tyagi**  
Data Analytics & Machine Learning Enthusiast  

---

⭐ If you find this project useful, don’t forget to star the repository! ⭐
