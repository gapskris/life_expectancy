# life_expectancy

Life Expectancy Prediction
This project predicts the life expectancy of individuals in different countries using historical health, economic, and social indicators. The aim is to assist governments, NGOs, and researchers in understanding the key factors influencing longevity and to support data-driven policy decisions.

📊 Problem Statement
Life expectancy is a critical measure of a nation's health. Accurately predicting it based on socio-economic, demographic, and health-related factors can:

Help inform public health policies

Guide international development initiatives

Reveal key factors affecting global life expectancy

📁 Dataset
The dataset is sourced from the WHO (World Health Organization) and includes features such as:

Feature	Description
Country	Name of the country
Year	Year of observation
Status	Developed or Developing
Life expectancy (target)	Target variable in years
Adult Mortality	Adult death rate (per 1000 population)
Infant deaths	Number of infant deaths per 1000 births
Alcohol	Alcohol consumption (litres per capita)
BMI	Average body mass index
HIV/AIDS	HIV/AIDS death rate
GDP	Gross Domestic Product per capita
Schooling	Average years of schooling
...	Other health/economic indicators

Source: Kaggle - Life Expectancy (WHO)

⚙️ Technologies Used
Python 3.x

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

XGBoost / LightGBM

Jupyter Notebook / Streamlit (for UI)

🧠 Model Workflow
Exploratory Data Analysis (EDA)

Identify trends and missing values

Visualize correlations and distributions

Data Preprocessing

Impute missing values (mean/median or KNN)

Encode categorical features (Status)

Feature scaling (StandardScaler / MinMaxScaler)

Modeling

Linear Regression (baseline)

Random Forest Regressor

Gradient Boosting / XGBoost / LightGBM

Hyperparameter tuning with GridSearchCV

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

🧪 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/gapskris/life_expectancy.git
cd life-expectancy-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Life_Expectancy_Prediction.ipynb
(Optional) Launch Streamlit app:

bash
Copy
Edit
streamlit run app.py
📊 Results
Best Model: XGBoost Regressor

RMSE: ~1.9 years

R² Score: ~0.97

Key Features: Adult Mortality, Schooling, HIV/AIDS, Income, BMI

🔍 Insights
Schooling and GDP have a strong positive impact on life expectancy.

HIV/AIDS and Adult Mortality strongly reduce life expectancy.

Developed countries consistently show higher average life expectancy.

🚀 Future Work
Add regional breakdowns and visual dashboards

Deploy REST API with FastAPI

Incorporate time-series analysis or forecasting (e.g., ARIMA, Prophet)

Add SHAP or LIME for model interpretability

👨‍💻 Author
Your Name
GitHub | LinkedIn

📜 License




Tools


