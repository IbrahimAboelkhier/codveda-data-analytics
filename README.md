# Codveda Data Analytics Internship
**#CodvedaJourney | #CodvedaExperience | #FutureWithCodveda | #CodvedaAchievements | #CodvedaProjects**

> A complete data analytics internship portfolio covering three progressive skill levels using real-world datasets.

---

## 📁 Repository Structure

```
codveda-data-analytics/
│
├── Level1_Basic/
│   ├── task1_data_cleaning.ipynb       # Data Cleaning & Preprocessing
│   ├── task2_eda.ipynb                 # Exploratory Data Analysis
│   └── task3_visualization.ipynb       # Basic Data Visualization
│
├── Level2_Intermediate/
│   ├── task1_regression.ipynb          # Regression Analysis — House Prices
│   ├── task2_timeseries.ipynb          # Time Series Analysis — AAPL Stock
│   └── task3_clustering.ipynb          # K-Means Clustering — Iris
│
├── Level3_Advanced/
│   ├── task1_classification.ipynb      # Churn Prediction — Random Forest
│   └── task3_nlp_sentiment.ipynb       # NLP Sentiment Analysis
│
├── requirements.txt
└── README.md
```

---

## 📊 Datasets Used

| Dataset | Tasks |
|---|---|
| `1_iris.csv` | L1-T2 EDA, L1-T3 Visualization, L2-T3 Clustering |
| `2_Stock_Prices_Data_Set.csv` | L2-T2 Time Series (AAPL) |
| `3_Sentiment_dataset.csv` | L3-T3 NLP Sentiment Analysis |
| `4_house_Prediction_Data_Set.csv` | L2-T1 Regression (Boston Housing) |
| `churnbigml80.csv` | L1-T1 Data Cleaning, L3-T1 Classification (train) |
| `churnbigml20.csv` | L3-T1 Classification (test) |

---

## 🟢 Level 1 — Basic

### Task 1: Data Cleaning and Preprocessing
- **Dataset:** Customer Churn (`churnbigml80.csv`)
- **Skills:** Missing value imputation (median/mode), deduplication, type standardization, feature engineering
- **Key outputs:** `churn_cleaned.csv`, audit reports

### Task 2: Exploratory Data Analysis (EDA)
- **Dataset:** Iris (`1_iris.csv`)
- **Skills:** Summary statistics (mean, median, mode, std), histograms, boxplots, violin plots, pairplot, correlation heatmap
- **Key insight:** Petal features are the strongest species discriminators (r ≈ 0.96)

### Task 3: Basic Data Visualization
- **Dataset:** Iris (`1_iris.csv`)
- **Skills:** Bar charts, line charts, scatter plots, pie charts, composite report figure
- **Key output:** 6-panel composite visualization ready for reports

---

## 🔵 Level 2 — Intermediate

### Task 1: Regression Analysis
- **Dataset:** Boston Housing (`4_house_Prediction_Data_Set.csv`)
- **Skills:** Linear regression, train/test split, StandardScaler, R², MSE, RMSE, MAE, 5-fold cross-validation
- **Key result:** R² ≈ 0.74; RM and LSTAT are the strongest predictors

### Task 2: Time Series Analysis
- **Dataset:** AAPL Stock Prices (`2_Stock_Prices_Data_Set.csv`)
- **Skills:** Moving averages (MA-20/50/200), Bollinger Bands, seasonal decomposition (statsmodels), monthly return patterns
- **Key insight:** Clear long-term uptrend with mild annual seasonality

### Task 3: K-Means Clustering
- **Dataset:** Iris (`1_iris.csv`)
- **Skills:** Elbow method, silhouette scores, K=3 final model, PCA 2D projection, Adjusted Rand Index
- **Key result:** ARI ≈ 0.90 — clusters closely match true species labels

---

## 🟠 Level 3 — Advanced

### Task 1: Predictive Modeling (Classification)
- **Dataset:** Customer Churn (80/20 split)
- **Skills:** Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, StratifiedKFold, GridSearchCV, ROC-AUC, learning curves
- **Best model:** Tuned Random Forest — F1 ≈ 0.92, AUC ≈ 0.97

### Task 3: NLP — Sentiment Analysis
- **Dataset:** Social Media Sentiment (`3_Sentiment_dataset.csv`)
- **Skills:** NLTK tokenization, stopword removal, lemmatization, TextBlob polarity/subjectivity, WordCloud, platform heatmap
- **Key result:** ~60% positive sentiment; platform-level sentiment breakdown included

---

## ⚙️ Setup and Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/codveda-data-analytics.git
cd codveda-data-analytics

# 2. Install dependencies
pip install -r requirements.txt

# 3. Place your CSV datasets in the same directory as the notebooks

# 4. Open any notebook
jupyter notebook Level1_Basic/task1_data_cleaning.ipynb
```

---

## 📦 Requirements

```
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
scikit-learn>=1.3.0
statsmodels>=0.14.0
nltk>=3.8.0
textblob>=0.17.0
wordcloud>=1.9.0
```

Install all at once:
```bash
pip install -r requirements.txt
```

---

## 🔗 LinkedIn Posts

Posted one update per level with video walkthroughs during the internship.
Tags used: `@Codveda Technology`
Hashtags: `#CodvedaJourney` `#CodvedaExperience` `#FutureWithCodveda` `#CodvedaAchievements` `#CodvedaProjects`

---

*Completed as part of the Codveda Technology Data Analytics Internship Program.*
