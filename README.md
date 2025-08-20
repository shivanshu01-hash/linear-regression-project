# 📊 Salary Prediction App  

This project is a **Streamlit web application** that predicts salary based on **years of experience** using a **Simple Linear Regression model**.  

---

## 🚀 Features
- User-friendly Streamlit interface  
- Input field for entering **Years of Experience**  
- Predicts salary instantly using a pre-trained regression model (`linear_regression_model.pkl`)  
- Displays prediction results clearly  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Streamlit** (UI)  
- **Scikit-learn** (Machine Learning model)  
- **NumPy**  
- **Pickle** (for saving/loading model)  

---

## 📂 Project Structure
```
.
├── app.py                     # Streamlit app code
├── linear_regression_model.pkl # Trained model
├── requirements.txt            # Dependencies
└── README.md                   # Project documentation
```

---

## ▶️ How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/salary-prediction-app.git
   cd salary-prediction-app
   ```

2. **Create & activate virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate    # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

5. Open the local URL in your browser (default: http://localhost:8501).
