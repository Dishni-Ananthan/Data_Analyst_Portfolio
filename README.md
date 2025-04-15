# Data_Analyst_Portfolio
# 👋 Hello! I'm Dishni
I thrive on transforming complex data into meaningful insights and developing impactful solutions using tools such as Excel, SQL, Python, Power BI, and Tableau. As an Oracle technical developer with over 6 years of experience, I specialize in the implementation, design, development, testing, and support of Oracle Apps R12/11i. My expertise spans critical modules, including Order Management (OM), Purchasing (PO), Accounts Receivable (AR), Accounts Payable (AP), Installed Base (IB), and Advanced Pricing (QP), where I consistently deliver innovative and efficient solutions to optimize enterprise processes.

I’m passionate about predictive modelling, exploratory data analysis, and bridging enterprise resource planning with actionable analytics.

---

## 🧠 Machine Learning Projects
I specialize in building models for classification, regression, and forecasting tasks. Here are a few of my ML projects:

# 🔬 [Wine Quality Prediction](https://github.com/yourusername/wine-quality-prediction)
## 🔍 Project Overview

### 🧩 Problem Statement
This project focuses on predicting the quality of wine using machine learning classification models. Based on physicochemical properties of red wine samples, the goal is to classify the wine as good or bad quality. 

### 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Plotly** for data visualization
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
# Tesla Stock Price Prediction 📈
## 🔍 Project Overview

### 🧩 Problem Statement
The aim is to forecast Tesla’s closing stock prices using historical market data. Stock prices are sequential in nature, and understanding past trends is critical for accurate prediction. 

### 🛠️ Tech Stack
- **Python** for development
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Plotly** for data visualization
- **Scikit-learn** for preprocessing and evaluation
- **XGBoost** for classical machine learning
- **TensorFlow / Keras** for deep learning (LSTM)

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


### 🧬 [Cancer Prediction](https://github.com/yourusername/cancer-prediction)
- **Problem**: Predict whether a tumor is benign or malignant.
- **Dataset**: Breast Cancer Wisconsin Dataset
- **Model**: KNN, SVM, Random Forest
- **Highlights**: Accuracy over 95%, cross-validation.

### ☁️ [Weather Prediction](https://github.com/yourusername/weather-prediction)
- **Problem**: Forecast weather (temperature, rainfall, etc.)
- **Model**: Regression trees and Random Forest Regressors
- **Highlights**: Real-world dataset and exploratory data analysis.

### 📊 [Market Campaign Analysis](https://github.com/yourusername/marketing-analysis-decision-tree)
- **Problem**: Predict if a customer will respond to a marketing campaign.
- **Model**: Decision Tree Classifier
- **Highlights**: EDA, visualized decision tree, model interpretation.
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

## 🐍 Python Projects

I love automating tasks, solving algorithmic challenges, and building mini-apps. Here are some fun and functional Python scripts:

### 🌐 [Web Scraping: Wikipedia – Top Companies by Revenue](https://github.com/yourusername/webscraping-wikipedia-revenue)
- Scrapes Wikipedia to extract data of Fortune 500 companies by revenue.
- Uses `BeautifulSoup` and `pandas` for data extraction and formatting.

### 🔍 [Binary Search Implementation](https://github.com/yourusername/binary-search)
- A clean, efficient implementation of the classic binary search algorithm.
- Includes test cases and step-by-step logic explanation.

### ♈ [Zodiac Sign Calculator](https://github.com/yourusername/zodiac-sign-finder)
- Enter your birthdate and get your zodiac sign!
- Fun utility project using Python’s `datetime` module.

### ✊ [Rock Paper Scissors Game](https://github.com/yourusername/rock-paper-scissors)
- Command-line implementation of Rock Paper Scissors.
- Includes logic for game loop, user vs computer, and score tracking.
---

## 🛠️ Tools & Technologies

| Machine Learning | Python | Data Visualization | Others |
|------------------|--------|---------------------|--------|
| Scikit-learn, pandas, NumPy | Jupyter Notebook, VS Code | Power BI, Matplotlib, Seaborn | Git, Excel, BeautifulSoup |

---

## 📬 Let’s Connect

- 💼 [LinkedIn](www.linkedin.com/in/dishni-ananthan-36aba162)
- ✉️ dishni90@gmail.com

---

> *“Without data, you're just another person with an opinion.” – W. Edwards Deming*

Thanks for visiting! Feel free to explore, fork, or star any project that interests you 🌟

