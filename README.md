# multi-agent-portfolio-manager

# 🧠 Multi-Agent Portfolio Manager

An AI-powered portfolio optimization system using autonomous agents built with LangChain, Groq (LLaMA 3.3 70B), and yfinance.

## 🏗️ Architecture

- **Technical Analysis Agent** — RSI, MACD, Bollinger Bands
- **Fundamental Analysis Agent** — Sharpe Ratio, drawdown, volatility
- **Portfolio Manager Agent** — LLM-based allocation optimizer (LLaMA 3.3 70B via Groq)

## 📊 Output

- Optimal portfolio allocation in JSON
- Performance chart vs SPY benchmark (1-year backtest)

## ⚙️ Stack

- Python 3.9
- LangChain + Groq API
- yfinance, pandas, numpy, matplotlib, ta

## 🚀 Setup

```bash
pip install -r requirements.txt
# Add your GROQ_API_KEY in a .env file
jupyter notebook notebooks/portfolio_agent.ipynb
