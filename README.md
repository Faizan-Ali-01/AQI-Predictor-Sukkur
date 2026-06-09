# 🌍 Sukkur AQI Predictor

A professional, automated Air Quality Index (AQI) prediction and monitoring system for Sukkur, Pakistan. This project fetches real-time AQI data, trains machine learning models, and provides a beautiful Streamlit dashboard for live monitoring and forecasting.

---

## 🚀 Features
- **Current AQI display** with color-coded health status
- **AQI health alerts** for dangerous air quality
- **Current pollutants** (PM2.5, PM10, NO₂, SO₂, O₃, CO)
- **3-Day AQI forecast** (hourly predictions)
- **Feature importance analysis** (see what drives AQI)
- **Historical 30-day AQI trend**
- **Model comparison chart** (RMSE, MAE, R²)
- **Automated data fetching and model retraining** via GitHub Actions

---

## 🛠️ Tech Stack
| Technology      | Purpose                                  |
|----------------|-------------------------------------------|
| Python         | Core programming language                 |
| Scikit-learn   | Random Forest, Ridge Regression models    |
| XGBoost        | Gradient boosting model                   |
| Streamlit      | Interactive dashboard                     |
| Plotly         | Data visualization                        |
| SHAP           | Feature importance (explainability)       |
| Pandas, Numpy  | Data manipulation and analysis            |
| AQICN API      | Real-time AQI data source                 |
| GitHub Actions | Automation for data/model updates         |

---

## 📁 Project Structure
```
aqi-predictor-sukkur/
├── data/                  # CSV data files (current, historical, model results)
├── models/                # Trained ML models and metadata
├── notebooks/             # Jupyter notebooks (optional)
├── 1_fetch_data.py        # Fetches AQI data from AQICN API
├── 2_train_models.py      # Trains and evaluates ML models
├── 3_dashboard.py         # Streamlit dashboard
├── requirements.txt       # Python dependencies
├── .env                   # API keys and config (not committed)
├── .github/workflows/     # GitHub Actions automation
│   ├── fetch_data.yml     # Hourly data fetch workflow
│   └── train_models.yml   # Daily model retrain workflow
├── SETUP.md               # API key setup instructions
└── README.md              # Project documentation
```

---


## 🏆 Model Comparison Results
| Model            | RMSE   | MAE    | R²    |
|------------------|--------|--------|-------|
| Random Forest    | ...    | ...    | ...   |
| Ridge Regression | ...    | ...    | ...   |
| XGBoost          | ...    | ...    | ...   |

_See `data/model_comparison.csv` for latest results._

---

## 🚧 Future Improvements
- Add support for more cities
- Deploy dashboard online (Streamlit Cloud, Heroku, etc.)
- Add user authentication for dashboard
- Integrate weather data for better predictions
- Add notifications/alerts (email, SMS)
- Improve model explainability and reporting
- Dockerize the project for easy deployment

---

## 📄 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
# aqi-predictor-sukkur
AQI Prediction System for Sukkur using ML
