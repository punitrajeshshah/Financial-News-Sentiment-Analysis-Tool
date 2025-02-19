# 📊 Financial News Sentiment Analysis Tool

## 📌 Project Overview   
The **Financial News Sentiment Analysis Tool** is an automated system that **scrapes financial news, performs sentiment analysis, and predicts stock trends**. This tool helps traders and investors track market sentiment by analyzing news data from **MoneyControl**, classifying it as **positive, negative, or neutral**, and exporting results into an easy-to-use **Excel dashboard**.

## 💡 Features  
- 🔄 **Automated News Scraping**: Extracts financial news articles via RSS feeds.  
- 🔍 **Sentiment Analysis**: Uses **VADER (Valence Aware Dictionary and Sentiment Reasoner)** to classify news sentiment.  
- 🌟 **Stock Mention Extraction**: Identifies companies referenced in news articles.  
- 📈 **Excel Integration**: Stores processed insights in an Excel dashboard.  
- 🎨 **Word Cloud Visualization**: Displays sentiment trends at a glance.

## 📂 Repository Structure  
```
Financial-News-Sentiment-Analysis-Tool/
│── README.md                 # Project Overview  
│── LICENSE                   # BSD 3-Clause License  
│── .gitignore                # Ignore unnecessary files  
│  
├── data/  
│   └── NIFTY_500_sheet.xlsx   # Processed stock data (Excel output)  
│  
├── notebooks/  
│   ├── GroupProject.ipynb     # Financial Data Scraper (NIFTY 500)  
│   ├── GroupProjectPro.ipynb  # News Extraction & Sentiment Analysis  
│   ├── GroupProjectPro1.ipynb # Full Article Scraper  
│  
├── reports/  
│   ├── NEWS-PPRO.pdf  # Project Report  
│   ├── NEWS-PPRO.pptx # Presentation  
```

## 🛠️ How to Run  
### **1️⃣ Install Dependencies**  
```bash  
pip install beautifulsoup4 pandas openpyxl feedparser wordcloud matplotlib vaderSentiment spacy  
python -m spacy download en_core_web_sm  
```

### **2️⃣ Run the Notebooks**  
- **Financial Data Scraper:** `GroupProject.ipynb`  
- **News Sentiment Analysis:** `GroupProjectPro.ipynb`  
- **Full Article Scraper:** `GroupProjectPro1.ipynb`  

## 📊 Results  
- **Best Predictors of Stock Movements:** News sentiment and financial metrics.  
- **Sentiment Trends:** Positive/negative news impacts stock prices.  
- **Traders' Benefit:** Helps in **timely, data-driven investment decisions**.  

## 🔍 Future Enhancements  
- **Machine Learning Sentiment Models** for better accuracy.  
- **Real-Time Alerts** for sentiment shifts.  
- **Integration with Trading Platforms** for automated action.  



