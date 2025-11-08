<h1 align="center">✨ Pretty Tech | Sales Forecasting System (ARIMA) ✨</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Model-ARIMA-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Language-Python_3.12-yellow?style=flat-square">
  <img src="https://img.shields.io/badge/IDE-VS_Code-purple?style=flat-square">
  <img src="https://img.shields.io/badge/Framework-Statsmodels-orange?style=flat-square">
</p>

---

### 🧠 Project Overview
The **Sales Forecasting System** predicts monthly company sales using an **ARIMA model** to support warehouse expansion and inventory management.  
It detects trends, seasonality, and noise to forecast future performance and growth.

---

### 🧩 Dataset Details
- **File:** `sales.csv`
- **Columns:** `date`, `sales`
- **Tensor (Time Unit):** Monthly
- **Trend:** Upward 📈  
- **Stationarity:** Non-stationary (requires differencing)  
- **Noise:** Moderate 🌤️  

---

### ⚙️ Steps Performed
1. Loaded and cleaned sales data  
2. Visualized time-series trend  
3. Tested stationarity (ADF Test)  
4. Tuned and trained ARIMA model `(p,d,q)`  
5. Forecasted test data  
6. Evaluated RMSE  
7. Saved trained model to `models/arima_sales_model.pkl`

---

### 🧮 Model Evaluation

| Metric | Description | Result |
|---------|--------------|--------|
| RMSE | Root Mean Square Error | ≈ 215.4 |
| AIC | Akaike Information Criterion | ≈ 1280.56 |
| Best Order | ARIMA (1,1,1) | ✅ |
| Forecast Horizon | 6 Months | 📊 |



### 📊 Visualization Example

<img width="1287" height="767" alt="0df7ab91-ca52-4c06-b041-3f216559f3ff" src="https://github.com/user-attachments/assets/823ce22c-f5cb-4e42-a4f0-c37022977a83" />



| Feature       | Description                                  |
| ------------- | -------------------------------------------- |
| 🧠 SARIMAX    | Handle seasonality and regressors            |
| ⚡ Auto-ARIMA  | Automate parameter tuning                    |
| 🧬 LSTM       | Deep learning version                        |
| 📊 Dashboard  | Interactive Gradio/Streamlit forecast viewer |
| ☁️ Deployment | Deploy API via HuggingFace or Render         |



🧰 Project Structure
├── sales.csv
├── sales_forecast.ipynb
├── models/
│   └── arima_sales_model.pkl
├── README.md
└── requirements.txt



👩🏽‍💻 Author
Tenika Powell
🌸 Data Science & Machine Learning Engineer | Pretty Tech Founder

🌐 GitHub: @Nikkilabesf

💌 Email: powell.tenika.n@gmail.com

💫 Portfolio: Coming soon

“Where data meets design — Pretty Tech projects blend analytics with aesthetics.”


<p align="center"> <img src="https://img.shields.io/badge/Made_with💖by-PrettyTech_Team-pink?style=for-the-badge"> </p> `
