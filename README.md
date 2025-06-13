# 🏆 Champions League Match Outcome Predictor

This project uses machine learning to predict the outcomes of UEFA Champions League matches. It involves data collection through web scraping, feature engineering, and training multiple classification models to forecast match results (win/draw/loss).

## 🚀 Features

* Web scraping of historical match statistics and live data using **BeautifulSoup** from fbref.com
* Data preprocessing and feature engineering with **Pandas** and **NumPy**
* Multiple ML models: **Logistic Regression**, **SVM**, and **XGBoost**
* Model evaluation using accuracy, confusion matrix, and F1 score
* Visualization of predictions and performance metrics

## 🧠 Algorithms Used

* Logistic Regression
* Support Vector Machines (SVM)
* XGBoost Classifier

## 🛠️ Tech Stack

* **Python**
* **Scikit-learn**
* **XGBoost**
* **BeautifulSoup**
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**

## 📁 Project Structure

```
├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter Notebooks for exploration and modeling
├── scraper/             # Web scraping scripts
├── models/              # Trained model files (optional)
├── utils/               # Helper functions
├── main.py              # Main script for training and prediction
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

## 📊 Sample Output

> Predicted: **Win**
> Actual: **Draw**
> Confidence: **78%**

## ⚽ Future Improvements

* Integrate live odds data for better prediction accuracy
* Deploy as a web app using Streamlit or Flask
* Add player-level features and injury data

thank you fbref.com for not blocking me from your website too many times
