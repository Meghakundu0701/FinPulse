# ⚡ FinPulse · Real-Time Market Intelligence

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/)
[![Author](https://img.shields.io/badge/Author-Megha%20Kundu-blue.svg)](https://github.com/Meghakundu0701)
[![GitHub](https://img.shields.io/badge/GitHub-Meghakundu0701-181717.svg?logo=github)](https://github.com/Meghakundu0701)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

FinPulse is a high-frequency financial intelligence and cryptocurrency market dashboard engineered with **Streamlit**, **Plotly**, and real-time market feeds. Designed with deep Indian Rupee (INR) localization and global dollar valuation, it provides instant insights into market trends, volatility, sentiment, and risk indexes.

Developed by **[Megha Kundu](https://github.com/Meghakundu0701)**.

---

## 🌟 Key Features

- **Live Market Ticker**: Animated real-time ticker tape displaying 24h price action for top global digital assets.
- **Dual Currency Mode (INR & USD)**: Dynamic currency converter with live USD/INR exchange rates.
- **Fear & Greed Index**: Sentiment analysis tracker with interactive gauges and 30-day historical sentiment analysis.
- **Interactive Technical Charts**: High-resolution 30-day price trend graphs with high/low watermark markers for Bitcoin (BTC) and Ethereum (ETH).
- **India Market Spotlight**: Focused metrics with sparklines and 7-day movement for leading assets in INR.
- **Top 10 Breakdown Table**: Real-time sorted table with 1-hour, 24-hour, and 7-day percentage variations, volume, and market capitalization.
- **Resilient Fallback Engine**: Seamless graceful degradation ensures zero downtime even during public API rate-limiting.

---

## 🚀 Quick Start (Run Locally)

### 1. Clone the repository
```bash
git clone https://github.com/Meghakundu0701/FinPulse.git
cd FinPulse
```

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App
```bash
streamlit run app.py
```

The app will launch in your browser at `http://localhost:8501`.

---

## 🌐 Deploy Live on Streamlit Cloud

To share your dashboard publicly:

1. Push this repository to your GitHub account (`https://github.com/Meghakundu0701/FinPulse`).
2. Visit **[share.streamlit.io](https://share.streamlit.io)** and sign in with your GitHub account.
3. Click **"New App"**.
4. Select your repository `Meghakundu0701/FinPulse`, branch `main`, and main file path `app.py`.
5. Click **"Deploy"** — your live dashboard will be online in seconds!

---

## 🛠️ Tech Stack

- **Framework**: [Streamlit](https://streamlit.io/)
- **Visualizations**: [Plotly Graph Objects](https://plotly.com/python/)
- **Data Manipulation**: [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/)
- **APIs**: [CoinGecko API](https://www.coingecko.com/en/api), [Alternative.me Fear & Greed API](https://alternative.me/crypto/fear-and-greed-index/)

---

## 👩‍💻 Author

**Megha Kundu**
- GitHub: [@Meghakundu0701](https://github.com/Meghakundu0701)
- Repository: [FinPulse](https://github.com/Meghakundu0701/FinPulse)

Made with ❤️ in India 🇮🇳
