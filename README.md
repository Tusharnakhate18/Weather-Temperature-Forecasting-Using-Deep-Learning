# 🌦️ Weather Temperature Forecasting Using Deep Learning

This project focuses on predicting temperature using deep learning-based
time series models such as **LSTM**, **SimpleRNN**, and **GRU**.
Historical weather data is analyzed to compare the performance of
different recurrent neural networks.

---

## 📌 Features
- Exploratory Data Analysis (EDA)
- Time series preprocessing
- Temperature forecasting
- Comparison of LSTM, RNN, and GRU models
- Performance evaluation using MSE, MAE, and R²

---

## 🧠 Models Used
- LSTM (Long Short-Term Memory)
- SimpleRNN
- GRU (Gated Recurrent Unit)

---

## 📊 Dataset
- Weather data from Excel file: `Akola.xlsx`
- Parameters include:
  - Temperature
  - Humidity
  - Pressure
  - Wind Speed
  - Wind Direction

---

## 🛠️ Technologies
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

## 📈 Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

---

## ▶️ How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/Weather-Temperature-Forecasting.git

   
2. Install dependencies
   ```bash
   pip install -r requirements.txt

3. Run the notebook or Python script

---   

## 🎯 Objective
To compare different recurrent neural network models for temperature
forecasting and identify the most effective architecture.

## 📄 License
This project is for academic and research purposes


Click **Commit changes**

---

# 📁 Step 3: Upload Your Project Files

Click **Add file → Upload files**

Upload:
- `weather_forecasting.py` (your main code)
- `Akola.xlsx` (dataset)
- `requirements.txt`

---


# 💻 Step 4: (Optional) Upload Using Git Command Line

- git clone https://github.com/your-username/Weather-Temperature-Forecasting.git
- cd Weather-Temperature-Forecasting
- git add .
- git commit -m "Initial commit - weather forecasting project"
- git push origin main

---

## ✅ Conclusion

In this project, temperature forecasting was performed using deep learning
time-series models, including LSTM, SimpleRNN, and GRU. Historical weather
data was preprocessed, analyzed, and used to train the models for predicting
future temperature values.

The experimental results show that **LSTM and GRU models outperform the
SimpleRNN model**, as they are better at capturing long-term temporal
dependencies in weather data. Among all models, the LSTM/GRU achieved
lower prediction error and higher R² score, indicating better accuracy
and stability.

This study demonstrates that recurrent neural networks are effective tools
for weather forecasting and can be extended to multivariate inputs and
longer prediction horizons. The proposed approach can be useful for
applications in agriculture, climate analysis, and environmental monitoring.

---
