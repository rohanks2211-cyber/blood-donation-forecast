# Blood Donation Forecast - XGBoost (AUC 0.7365)

Predicts if blood donors return using RFMTC data (748 samples).

## Results
- **Test AUC**: 0.7365
- **Features**: Recency, Frequency, Monetary(log), Time  
- **Class balance**: 76% No / 24% Yes
- **Improvements**: Log normalization + SMOTE oversampling

![Importance](importance_plot.png)  # From your notebook

## Run
```bash
pip install -r requirements.txt
jupyter notebook blood_donation_forecast.ipynb
