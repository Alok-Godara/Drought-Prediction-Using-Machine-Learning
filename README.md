# 🌾 Drought Prediction Using Machine Learning for Agricultural Land in Rajasthan

This project aims to forecast drought conditions in Rajasthan using advanced machine learning techniques. Given the region's dependence on agriculture and vulnerability to drought, the system provides early warnings to help farmers, policymakers, and water resource managers make informed decisions.

## 📌 Project Highlights

- **Location**: Rajasthan, India
- **Goal**: Predict drought conditions 3–6 months in advance using machine learning
- **Techniques Used**: Logistic Regression, LSTM, XGBoost, Prophet
- **Dataset**: Climate and hydrological data from meteorological and remote sensing sources

---

## 🔍 Problem Statement

Rajasthan frequently suffers from drought due to highly variable rainfall and harsh climatic conditions. Traditional forecasting systems often rely solely on precipitation, which is not always reliable.

**Objective**: Build a model that integrates meteorological, hydrological, and oceanic features to predict drought with improved accuracy.

---

## 🧠 ML Models Implemented

| Model               | Purpose                                 |
|--------------------|-----------------------------------------|
| `Logistic Regression` | Classify drought vs. non-drought using SPI |
| `LSTM`               | Time-series forecasting of SPI values     |
| `XGBoost`            | Ensemble model for tabular feature learning |
| `Prophet`            | Time-series trend & seasonality modeling  |

All models are implemented in Jupyter notebooks provided in this repository.

---

## 📊 Features Considered

### 🌦 Meteorological
- Rainfall (mm)
- Temperature (Min/Max/Avg °C)
- Humidity (%)
- Wind Speed (m/s)
- Solar Radiation (W/m²)
- Evapotranspiration (ET)

### 💧 Hydrological
- Soil Moisture (%)
- Groundwater Levels (m)
- Reservoir Water Levels (m³)
- River Discharge (m³/s)

### 📉 Drought Indices
- Standardized Precipitation Index (SPI)
- Palmer Drought Severity Index (PDSI)

### 🌊 Oceanic Indicators
- ENSO (El Niño–Southern Oscillation)
- Indian Ocean Dipole (IOD)

---

## 💡 Why This Model Is Better

✅ **Multisource Data Integration**  
✅ **Time-Series Forecasting (LSTM, Prophet)**  
✅ **Non-linear Pattern Recognition (XGBoost)**  
✅ **Supports Early Warning Systems**  

---

## 🧾 Files in This Repository

| File/Notebook                   | Description                                   |
|--------------------------------|-----------------------------------------------|
| `dataset_final_wre.xlsx`       | Final cleaned dataset                         |
| `WRE_Logistic_Classification.ipynb` | Logistic Regression model for SPI classification |
| `WRE_LSTM.ipynb`               | LSTM time-series model for SPI forecasting    |
| `XGBoost.ipynb`                | XGBoost model for drought classification      |
| `WRE_Prophet.ipynb`            | Prophet model for trend-based SPI forecasting |
| `Drought Prediction Using Machine Learning.pdf` | Project documentation PDF |

---

## 🧪 How to Run

1. Clone this repository
2. Install dependencies (pandas, sklearn, tensorflow, prophet, xgboost, etc.)
3. Run the notebooks in order or explore them individually

---

## 🚀 Future Improvements

- Integrate real-time IoT data for continuous updates
- Expand training data with satellite imagery
- Improve LSTM architecture for better long-term accuracy

---

## 🤝 Acknowledgements

- IMD, CPC-NOAA, and NASA for open climate datasets
- Faculty & mentors at IIT JODHPUR
- Open-source contributors for libraries like Prophet, TensorFlow, XGBoost

---

## 📬 Contact

For queries or collaboration opportunities:  
**ALOK GODARA** – b22ci004@iitj.ac.in  
