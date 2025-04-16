# Data_Analyst_Portfolio
# 👋 Hello! I'm Dishni
I thrive on transforming complex data into meaningful insights and developing impactful solutions using tools such as Excel, SQL, Python, Power BI, and Tableau. As an Oracle technical developer with over 6 years of experience, I specialize in the implementation, design, development, testing, and support of Oracle Apps R12/11i. My expertise spans critical modules, including Order Management (OM), Purchasing (PO), Accounts Receivable (AR), Accounts Payable (AP), Installed Base (IB), and Advanced Pricing (QP), where I consistently deliver innovative and efficient solutions to optimize enterprise processes.

I’m passionate about predictive modelling, exploratory data analysis, and bridging enterprise resource planning with actionable analytics.

---

## 🧠 Machine Learning Projects
I specialize in building models for classification, regression, and forecasting tasks. Here are a few of my ML projects:

# 🔬 [Wine Quality Prediction](Wine_Quality_Prediction.ipynb)
## 🔍 Project Overview

### 🧩 Problem Statement
This project focuses on predicting the quality of wine using machine learning classification models. Based on physicochemical properties of red wine samples, the goal is to classify the wine as good or bad quality. 

### 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and evaluation

### 🤖 Models Used
#### 🔸 Random Forest Classifier
#### 🔸 SVC with GridSearchCV for hyperparameter tuning and optimization

### ✨ Key Highlights
- Data preprocessing included encoding categorical labels and scaling features.
- Quality labels were binarized into good and bad using custom thresholds.
- Feature importance and correlation heatmaps were generated for deeper insights.
- Hyperparameter tuning was applied to SVC using GridSearchCV to improve accuracy.
- Cross-validation used for model performance validation.
- Visualizations included barplots, confusion matrices, and performance metrics.

### 🔍 Insights
- Random Forest achieved a cross-validation accuracy of 91.17%
- Tuned SVC achieved a close 90.85% accuracy
- Both models performed competitively, with Random Forest slightly ahead.
- Features such as alcohol, volatile acidity, and sulphates had a notable influence on wine quality prediction.
  
- ---
# 📈 [Tesla Stock Price Prediction](Stock_price_prediction_XGB.ipynb) 
## 🔍 Project Overview

### 🧩 Problem Statement
The aim is to forecast Tesla’s closing stock prices using historical market data. Stock prices are sequential in nature, and understanding past trends is critical for accurate prediction. 

### 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Plotly** for data visualization
- **Scikit-learn** for preprocessing and evaluation

### 🤖 Models Used

#### 🔸 XGBoost Regressor
- Uses only the **closing price** as input
- Treats each record as an independent observation
- Fast to train and easy to interpret
- Fails to account for time-based dependencies
- ➡️ Result: **Higher RMSE**, unstable predictions

#### 🔹 LSTM Neural Network
- Uses **multiple features**: `open`, `high`, `low`, `close`, and `volume`
- Considers the past **60 days** of data to predict the next day
- Designed for **sequential, time series data**
- Captures historical trends and seasonality
- ➡️ Result: **Lower RMSE**, more accurate and smooth predictions

### ✨ Key Highlights
- Demonstrates the difference between **tabular modeling vs. time series modeling**
- Shows how LSTM leverages sequential data to outperform traditional models
- Uses real Tesla stock data and performs **feature scaling**, **model evaluation**, and **forecast visualization**
- A strong portfolio example of combining **classical ML and deep learning** for financial forecasting

---

# 🧬 [Cancer Prediction](Cancer_prediction.ipynb)
## 🔍 Project Overview

### 🧩 Problem Statement
This project involves building a machine learning model to classify tumors as **benign** or **malignant** based on various medical attributes. The goal is to aid in early detection and diagnosis of breast cancer using interpretable models like Decision Trees.

## 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and evaluation

## 🧪 Models Used
#### 🔸 Decision Tree Classifier
  A rule-based, tree-structured model that splits the data on feature thresholds. Offers transparency and interpretability—critical in healthcare domains.
  
#### 🔸Cross-Validation
  Used to evaluate model generalization across different depths of the tree. Helps in choosing the optimal complexity and avoiding overfitting.

## 🌟 Key Highlights
- Performed EDA with visualizations for class balance and feature importance.
- Used label encoding to convert categorical diagnosis ('M', 'B') to numerical.
- Removed irrelevant columns like `id` for cleaner data.
- Trained Decision Trees with different depths and used 10-fold cross-validation to assess model stability.
- Plotted training vs. validation accuracy to visualize the effect of depth.

## 🔍 Insights
- The model performs well on distinguishing benign from malignant tumors.
- **Depth tuning** is critical: shallow trees underfit, deep trees overfit.
- Key predictors included: `radius_mean`, `concavity_mean`, and `texture_mean`.

---

# ☁️ [Weather Prediction](Weather_Prediction.ipynb)
## 🔍 Project Overview

### 🧩 Problem Statement
This project uses historical weather data to predict future weather conditions (e.g., sun, rain, fog) using the XGBoost classification algorithm. It involves preprocessing, normalization, label encoding, hyperparameter tuning, and visual performance evaluation.

### 🛠️ Tech Stack
- **Python** for development
- **Pandas** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and evaluation

### 🤖 Models Used
#### 🔸 XGBoost Classifier

## 🌟 Key Highlights
- Used Seattle weather data, including features like precipitation, temp_max, temp_min, and wind.
- Normalized continuous variables to ensure even scaling across all features.
- Encoded categorical weather labels (sun, rain, fog, drizzle, snow) using LabelEncoder.
- Performed hyperparameter tuning with GridSearchCV to find optimal learning_rate and gamma.
- Visualized actual vs predicted classes using original labels for better interpretability.

## 🔍 Insights
- Balanced Predictions for Major Classes:
    The model performs well on classes like rain and snow, with predicted counts closely matching actual values.
- Underprediction of Rare Classes:
    Fogs are consistently underpredicted.
    This suggests the model may struggle to detect fogs accurately, potentially due to overlapping patterns in temperature or precipitation with other classes.
- Overprediction of Certain Conditions:
    There may be slight overprediction for sun

### 📊 [Market Campaign Analysis](Marketing_Analysis.ipynb)
## 🔍 Project Overview

### 🧩 Problem Statement
This project involves building a machine learning model to classify tumors as **benign** or **malignant** based on various medical attributes. The goal is to aid in early detection and diagnosis of breast cancer using interpretable models like Decision Trees.

## 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and evaluation
  
## 🧪 Models Used
#### 🔸 Decision Tree Classifier
  A rule-based, tree-structured model that splits the data on feature thresholds. Offers transparency and interpretability—critical in healthcare domains.

## 🌟 Key Highlights
- Created a custom feature balance_class to group customers into meaningful financial segments.
- Applied stratified sampling to preserve class balance during model training.
- Used GridSearchCV to find optimal parameters for Decision Tree performance.
- Visualized the final decision tree to understand customer segmentation logic.

## 🔍 Insights
- Customers with higher balances (Class A & B) are more likely to respond positively.
- A large portion of negative responses comes from Class D and E (lower balance clients).
- Housing and loan status play a notable role in campaign outcomes.
- Decision Trees offer interpretability, making them suitable for financial marketing use cases.

---

## 📊 Power BI Projects

I turn business data into beautiful and insightful dashboards using Power BI. These dashboards enable data-driven decision-making and performance analysis.

### 🚚 [Supply Chain Analysis Dashboard](https://github.com/yourusername/powerbi-supplychain-analysis)
- Visualizes supplier performance, delivery times, and order costs.
- Insights into supply chain bottlenecks and cost optimizations.

### 🛍️ [Superstore Sales Dashboard](https://github.com/yourusername/powerbi-superstore-analysis)
- Built on the Superstore dataset to analyze sales and profitability across segments, categories, and regions.
- Includes KPIs, slicers, and actionable visuals.
---

## 📬 Let’s Connect

- 💼 [LinkedIn](www.linkedin.com/in/dishni-ananthan-36aba162)
- ✉️ dishni90@gmail.com

---

> *“Without data, you're just another person with an opinion.” – W. Edwards Deming*

Thanks for visiting! Feel free to explore, fork, or star any project that interests you 🌟

