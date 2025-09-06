# 🏏 Cricket Score Predictor  

A **machine learning-based T20 cricket score predictor** using **XGBoost**. This project predicts the **final score of a batting team** given the current state of a match.  

📊 **Dataset**: [CricSheet – A Retrosheet for Cricket (T20s)](https://www.kaggle.com/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s)  

---

## 🚀 Features  
✅ Predicts **final team score** in a T20 match  
✅ Built with **XGBoost Regressor** for high accuracy  
✅ **Interactive Streamlit web app** for predictions  
✅ Input options include:  
- Batting Team  
- Bowling Team  
- City / Venue  
- Current Score  
- Overs Completed  
- Wickets Out  
- Runs Scored in Last 5 Overs  

---

## 📂 Project Structure  
├── app.py # Streamlit app for prediction
├── data-extraction.ipynb # Notebook for data extraction & cleaning
├── feature-extraction.ipynb# Notebook for feature engineering & model training
├── pipe.pkl # Saved trained XGBoost model
├── README.md # Project documentation

---

## ⚙️ Installation  

### 1️⃣ Clone this repository  
```bash
git clone https://github.com/your-username/cricket-score-predictor.git
cd cricket-score-predictor
pip install -r requirements.txt
streamlit run app.py

