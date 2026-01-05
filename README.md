
📈 Apple Stock Price Prediction

1️⃣ Problem Statement
Forecast Apple stock prices using historical data with a time series model.

2️⃣ Dataset
- File:  projectDATASET.csv
- Columns: Date, Open, High, Low, Close, Volume
  
3️⃣ EDA
- Converted Date to datetime & sorted
- Check for null and missing value 
- Visualized closing prices for trends & seasonality

4️⃣ Model Choice
- SARIMA selected for capturing trend + seasonal patterns in financial time series.
  
5️⃣ Preprocessing
- Removed missing values
- Removed outliers 
- Target: Close Price
- Applied scaling
  
6️⃣ Model Training
- Train/test split
- Tuned SARIMA parameters
- Saved model
  
7️⃣ Streamlit App
- Interactive web app (app.py)
- Shows historical data + future predictions
- Visualizations for better insights
  
8️⃣ Deployment
- Deployed on Streamlit Cloud
  
9️⃣ Repository Structure
- Apple stock price prediction.ipynb → EDA & training
- app.py (App deplyoment) → Streamlit frontend
- Apple Stock price predection PPT → Presention Of all work  
- PRoject  DATASET.csv → Dataset
  
🔟 Achievements
- End-to-end forecasting pipeline
- SARIMA statistical modeling
- Real-time Streamlit app
- Successful cloud deployment


