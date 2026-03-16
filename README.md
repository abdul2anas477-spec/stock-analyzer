# Stock Risk Analyzer — Setup Guide

## Requirements
- Python 3.8+
- A FREE Groq API key from https://console.groq.com

## Setup (run once)
pip install -r requirements.txt

## Add your Groq API key
Open app.py in Notepad, find this line:
  GROQ_API_KEY = "YOUR_GROQ_KEY_HERE"
Replace YOUR_GROQ_KEY_HERE with your key from console.groq.com

## Run the app
python app.py

Then open browser at: http://localhost:5000

## Supported tickers
- US stocks:     AAPL, TSLA, MSFT, NVDA, GOOGL
- Indian stocks: RELIANCE.NS, TCS.NS, INFY.NS, HDFCBANK.NS
- Any Yahoo Finance ticker works!

## Groq is 100% free
- Sign up at https://console.groq.com
- Click API Keys → Create API Key
- No credit card needed
