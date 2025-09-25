# Ethiopian-wheat-forecasting-by-SARIMAX-model
This project applies time series forecasting to model and predict Ethiopia’s wheat production using FAOSTAT data. The study explores the relationship between area harvested (predictor) and production quantity (target) through SARIMAX models.  
# 📊 Data Source

FAOSTAT (Food and Agriculture Organization of the United Nations)

Variables used:

Area harvested (ha)

Yield (kg/ha)

Production quantity (tons)

# 🛠️ Methodology

Data Collection & Cleaning (FAOSTAT wheat dataset for Ethiopia).

# Exploratory Data Analysis (EDA):

# Trend visualization

 # Correlation analysis (Area vs. Yield, r ≈ 0.87).

# Modeling:

SARIMAX: Production ~ Area harvested

Baseline ARIMA for comparison

 # Evaluation:

# Root Mean Square Error (RMSE)

Normalized RMSE (% of mean production).

 # Forecasting:

Predicting future production with projected area harvested.

# Results

Mean Production: ~5.5 million tons

SARIMAX RMSE: ~299,455 tons

Error as % of Mean: ~5.4% → Good predictive accuracy

# Key Insight

📈 Ethiopia’s wheat production shows a strong upward trend, largely explained by increases in area harvested.
🔮 SARIMAX provides reliable forecasts for future production, helping inform land use, input allocation, and food security policies.
