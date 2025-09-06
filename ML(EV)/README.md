# ⚡ Probabilistic Forecasting of Flexible Regulation Capabilities in Electric Vehicles  

This project explores how **Electric Vehicles (EVs)** can contribute to the **smart grid** by providing flexible charging and discharging (V2G: Vehicle-to-Grid). Using real-world charging session data, we build **machine learning and deep learning models** to forecast the **flexible regulation capacity (kW)** that EVs can provide at any given time.  

## 📌 Objectives
- Predict how much energy EVs can discharge back to the grid without affecting user mobility.  
- Explore **time-series forecasting models** (ARIMA, Prophet) and compare them with **ML/DL models** (XGBoost, LightGBM, LSTM, GRU).  
- Provide a **probabilistic forecast** to capture uncertainty in predictions, useful for grid operators.  

## 📂 Project Structure
EV_Flexible_Regulation/
│── notebooks/
│ ├── 01_data_exploration.ipynb # Explore dataset
│ ├── 02_preprocessing.ipynb # Clean & preprocess data
│ ├── 03_baseline_models.ipynb # ARIMA, Prophet (classical forecasting)
│ ├── 04_ml_models.ipynb # XGBoost, LightGBM (tree-based ML)
│ ├── 05_dl_models.ipynb # MLP, LSTM, GRU (deep learning)
│ ├── 06_probabilistic_forecast.ipynb # Uncertainty-aware models
│ ├── 07_evaluation.ipynb # Compare all models
│
│── results/
│ ├── processed_ev_data.csv # Preprocessed dataset


## ⚙️ Tech Stack
- **Languages**: Python  
- **ML/DL Frameworks**: scikit-learn, XGBoost, LightGBM, TensorFlow/Keras  
- **Time-Series**: ARIMA, Prophet  
- **Visualization**: matplotlib, seaborn  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Run the notebooks in order (01 → 07)  
4. Compare results in the evaluation notebook  

---

## 📖 Single Paragraph Detail

This project focuses on forecasting the **flexible regulation capacity** of electric vehicles, which represents the potential for EVs to discharge energy back to the grid without affecting drivers’ mobility needs. By leveraging a real-world EV charging dataset, the work applies a range of models — from traditional time-series methods like **ARIMA** and **Prophet** to advanced **machine learning (XGBoost, LightGBM)** and **deep learning (MLP, LSTM, GRU)** approaches. The project not only compares model accuracy but also emphasizes **probabilistic forecasting** to capture uncertainty in predictions, making the results more useful for **grid operators and energy planners** aiming to integrate EVs into smart grid regulation strategies.  

---