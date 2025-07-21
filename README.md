# 🧠 Machine Learning-Based Patient Risk Identifier

This project uses machine learning to predict the mental health risk level of students based on survey data. It includes a complete end-to-end pipeline — from data analysis to model training and deployment — along with a user-friendly web interface for real-time predictions.

---

## 📌 Project Overview

- ✅ Identifies students at risk of mental health challenges.
- ✅ Built using supervised machine learning.
- ✅ Integrated web interface using Flask and HTML.
- ✅ Complete Exploratory Data Analysis (EDA).
- ✅ Final presentation included in PowerPoint format.

---

## 📁 Folder Structure
patient-risk-identifier-v2/  
├── templates/  
│   └── index.html # Web interface for predictions  
├── Project_Notebook.ipynb # Jupyter notebook with EDA and model pipeline  
├── my_model.pkl # Trained machine learning model  
├── app.py # Flask backend to serve the model  
├── Student Mental health.csv.xlsx # Original dataset used  
└── Machine Learning-Based Patient Risk Identification for Mental Health.pptx # Final project presentation

---

## 🧪 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** (for data visualization)
- **Scikit-learn** (for ML model training)
- **Flask** (for backend web deployment)
- **HTML/CSS** (for the frontend form)
- **Jupyter Notebook**

---

## 🔍 Key Features

- **Exploratory Data Analysis (EDA):** Gain insights into the mental health dataset before modeling.
- **Machine Learning Pipeline:** Data preprocessing, model training, evaluation, and saving using `joblib`.
- **Web App:** A simple form that lets users input data and receive a prediction instantly.
- **Presentation-Ready:** Includes a professional PowerPoint deck summarizing the project and findings.

---

## 📁 Flask Template Note

Flask automatically looks for HTML files inside a folder named `templates/` (lowercase and plural).  
Make sure your `index.html` file is located at:

patient-risk-identifier-v2/  
├── templates/  
│ └── index.html  

Otherwise, you may get a `TemplateNotFound` error when running the app.

---

## ⚙️ How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Idani27/patient-risk-identifier-v2.git
   cd patient-risk-identifier-v2
   
2. **Install Dependencies**  
pip install pandas numpy scikit-learn flask matplotlib seaborn

4. **Run the Flask App**  
python app.py

6. **Access the Web Interface**  
Open your browser and go to:
http://127.0.0.1:5000/

---

📊 Dataset
The project uses a real-world student mental health dataset, formatted as:

Excel file: Student Mental health.csv.xlsx

Contains demographic, academic, and mental health-related fields.

---

📽️ Presentation
You can find the final project presentation here:  

Machine Learning-Based Patient Risk Identification for Mental Health.pptx

---

⚠️ Disclaimer
This tool is developed strictly for educational and research purposes. It is not intended to provide medical or psychological diagnoses. Always consult licensed professionals when dealing with mental health concerns.

---

📄 License
This repository is open-source and free to use for educational, non-commercial projects.

---

📫 Contact  
For questions, feedback, or collaboration:  

email: singoidani7@gmail.com


