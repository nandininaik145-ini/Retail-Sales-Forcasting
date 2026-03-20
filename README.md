🛒 Retail Sales Forecasting: End-to-End ML Project
Domain: Machine Learning & Time Series Analysis

Academic Level: BCA Final Year Internship Project

Duration: 8 Weeks (Accelerated)

📌 Project Overview
This project focuses on predicting daily sales for 1,115 Rossmann Store outlets. The goal is to help the retail chain manage inventory and avoid overstocking or understocking by providing a data-driven forecasting system.

🛠️ Tech Stack & Tools
Language: Python 3.x

Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn, XGBoost (Regression)

Time Series: Statsmodels (ARIMA/SARIMA), Facebook Prophet

Deployment: Streamlit (Interactive Dashboard)

Environment: Google Colab / VS Code

📅 Internship Journey (Step-by-Step)
🔹 Week 1 & 2: Data Engineering & Cleaning
Merged train.csv (Sales) with store.csv (Metadata).

Handled missing values in CompetitionDistance using Median Imputation.

Extracted Date features: Year, Month, Day, and WeekOfYear.

🔹 Week 3: Exploratory Data Analysis (EDA)
Discovered that Promotions increase sales by over 40% on average.

Identified Weekly Seasonality (Sales peak on Mondays and Fridays).

Analyzed the impact of State and School holidays.

🔹 Week 4: Regression Modeling (XGBoost)
Built a Gradient Boosting model to capture non-linear relationships.

Achieved a baseline accuracy with competitive RMSE and MAE scores.

🔹 Week 5 & 6: Time Series Mastery (ARIMA & Prophet)
Implemented ARIMA for statistical trend analysis.

Used Facebook Prophet to automatically handle holiday effects and yearly seasonality.

Compared Regression vs. Time Series performance.

🔹 Week 7 & 8: Dashboard & Final Report
Developed an interactive Streamlit Dashboard allowing users to select a Store ID and view future forecasts.

Generated a final technical report summarizing the most accurate model.

📊 Key Results
Best Model: XGBoost/Prophet Hybrid

Observation: The model accurately predicts sales spikes during "Promo" periods with an average error margin of ~10-12%.

🚀 How to Use
Clone the Repo: git clone https://github.com/YOUR_USERNAME/retailsales.git

Install Dependencies: pip install -r requirements.txt

Run Notebook: Open retailsales.ipynb in Google Colab to see the full training pipeline.

Launch Dashboard: streamlit run app.py

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
