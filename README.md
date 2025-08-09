# Crash Predictor with Statistical Edge Detection

This is a Streamlit app that helps detect statistically favorable moments to place "Above 2.0x" bets in crash multiplier games. It uses historical multiplier data to determine when there's a potential short-term edge.

## 🔍 Features

- Upload or manually enter crash multiplier history
- Predict whether the next multiplier will be over or under 2.0x
- Detect statistically significant patterns in recent rounds
- Track flat and fixed betting strategies
- View prediction accuracy and SOL balances

## 🧠 Statistical Edge Detector

Uses:
- Rolling average of last 10 multipliers
- Count of under-2.0x crashes in recent rounds
- Z-score for deviation from expected behavior

Signals when recent crashes show statistically unusual patterns that may favor a rebound.

## 🚀 How to Run

1. Clone this repo or upload to Streamlit Cloud.
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the app:

```
streamlit run app.py
```

## 📁 Files

- `app.py` – Main Streamlit app
- `requirements.txt` – Python dependencies

## 📝 License

This project is for educational and entertainment use only. Gambling involves risk. There is no guaranteed way to beat the house.

---
Built with ❤️ using Streamlit.