# 🌾 Crop Prediction Using Environment

This project utilizes machine learning to predict crop yield based on environmental and geographical factors. The system assists farmers, agronomists, and policy makers by providing data-driven insights to enhance agricultural planning and productivity.

---

## 📌 Objective

The goal of this project is to develop a predictive model that estimates crop yield (in hectares) using inputs like:
- Crop type
- Country
- Year
- Average temperature
- Rainfall
- Pesticide usage

---

## 🛠️ Tools & Technologies

- **Python** – Core language for data processing and modeling
- **scikit-learn** – For preprocessing and Random Forest model
- **TensorFlow** – For deep learning model (DNN)
- **Flask** – For deploying the prediction web application
- **Pickle** – Model serialization
- **HTML/CSS** – Frontend of the web interface

---

## 🔍 Methodology

1. **Data Collection**
   - Sourced from FAO, World Bank, and national agriculture databases.
2. **Preprocessing**
   - Handled missing values, normalized data, and applied OneHotEncoding.
3. **Model Training**
   - Tested Random Forest Regressor and Deep Neural Networks.
   - Evaluated using MAE, MSE, and R² Score.
4. **Deployment**
   - Integrated model into a Flask web app for user-friendly prediction.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crop-prediction.git
   cd crop-prediction
pip install -r requirements.txt
python app.py
http://127.0.0.1:5000/

