# 📈 AlphaMind Analytics

**AlphaMind Analytics** is an AI-powered financial intelligence and stock market analysis platform. It integrates **real-time stock data**, **technical & fundamental analysis**, **market sentiment**, and **RAG-based AI predictions** into a fully interactive Streamlit dashboard.
---

## 🔹 Features

- **Real-Time Stock Data**: Fetches live and historical stock prices using Yahoo Finance (`yfinance`).
- **Technical Analysis**:
  - Moving Averages (20-day, 50-day)
  - RSI Indicator
  - Trading Signals (Bullish, Bearish, Neutral)
- **Sentiment Analysis**:
  - Evaluates news, social media, analyst reports, and options activity
  - Generates an overall sentiment score and label
- **Fundamental Analysis**:
  - Company info, market cap, P/E, P/B, ROE, Debt-to-Equity, Profit Margin, Dividend Yield
- **RAG System (Retrieval-Augmented Generation)**:
  - Combines AI models with a knowledge database for context-aware predictions
  - Stores financial knowledge, news, and market insights for rapid retrieval
- **AI Price Predictions**:
  - Forecast future stock prices for a chosen horizon
  - Includes confidence intervals and expected return
- **Interactive Dashboard**:
  - Responsive Streamlit layout
  - Candlestick charts with moving averages
  - Tabs for Technical, Sentiment, Fundamental, and Prediction analyses

---

## 🗄️ Data Sources

- **Yahoo Finance (`yfinance`)**: Historical stock prices, fundamental data, company info.
- **Simulated Sentiment Data**: AI-generated sentiment scores for news, social media, analysts, and options.
- **RAG Knowledge Base**: Contextual financial knowledge stored for AI retrieval and reasoning.
- **Optional External APIs**: News API, Alpha Vantage, or other financial data providers.

---

## 🛠️ Libraries Used

- **Data Handling & Analysis**: `pandas`, `numpy`
- **Finance & Technical Analysis**: `yfinance`, `ta`
- **Visualization**: `plotly`, `dash`, `seaborn`
- **AI / ML / RAG**:
  - `torch`, `transformers`, `sentence-transformers`
  - `faiss-cpu`, `chromadb`, `langchain`, `openai`
- **Web & Deployment**: `streamlit`, `pyngrok`
- **Utilities**: `scikit-learn`, `newsapi-python`, `alpha_vantage`

> These libraries allow the system to gather data, analyze it, visualize trends, and generate AI-augmented insights.

---

## 👩‍💻 Authors

- **Hala Omary** – Project Lead & Frontend Developer  
  GitHub: [Hala AL Omary](https://github.com/HalaAl-Omary)

- **Sarah Abu Mandeel** – Co-Developer & AI Specialist  
  GitHub: [Sarah Abu Mandeel](https://github.com/Sarah111-AHM)

---

## 🚀 Running the App

1. Install dependencies:

```bash
pip install streamlit pyngrok yfinance pandas numpy plotly ta
pip install torch torchvision torchaudio transformers sentence-transformers faiss-cpu chromadb langchain openai newsapi-python alpha_vantage scikit-learn seaborn
