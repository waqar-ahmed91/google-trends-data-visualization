# 🔍 Google Trends vs Real-World Indicators

Can what people search online reveal what's happening in the real world?

This project explores whether **Google search popularity** reflects or predicts real-world metrics like the **unemployment rate**, **Tesla stock price**, or **Bitcoin price**. By aligning search data from Google Trends with official statistics and market data, we examine if public interest can uncover deeper patterns.

---

## 📌 Objective

We investigate questions like:
- Does search volume for **"Unemployment Benefits"** correlate with the actual **unemployment rate**?
- Can spikes in searches for **"Tesla"** relate to **TSLA's stock price**?
- Is there a connection between search interest in **"Bitcoin"** and its **market value**?

---

## 📊 Data Sources

- **Google Trends**  
  - Search interest for: `"Unemployment Benefits"`, `"Tesla"`, `"Bitcoin"`

- **FRED (Federal Reserve Economic Data)**  
  - Monthly **Unemployment Rate** (U.S.)

- **Yahoo Finance**  
  - Daily closing prices for:
    - **Tesla Stock (TSLA)**
    - **Bitcoin (BTC-USD)**

---

## 🧰 Tools Used

This project was kept intentionally minimal and clean:
- `pandas` for data loading and manipulation
- `matplotlib.pyplot` for plotting trends
- `matplotlib.dates` for handling time series formatting

No machine learning, external APIs, or complex libraries—just clear, visual exploration.

---

## 📈 Analysis Highlights

- **Time-Aligned Trends**: Search interest and real-world data were plotted side by side to reveal visual correlations.
- **Simple, Insightful Visuals**: Using only Python’s essential plotting tools, we visualized how public attention aligns with market or economic movement.
- **Observational Insights**: Noticed several periods where peaks in search volume preceded or coincided with major real-world events (like unemployment spikes or price surges).

---

## 🗂️ File Structure

```
├── unemployment_vs_trends.ipynb
├── tesla_vs_trends.ipynb
├── bitcoin_vs_trends.ipynb
├── data/
│   ├── google_trends.csv
│   ├── unemployment_rate.csv
│   ├── tesla_stock.csv
│   └── bitcoin_price.csv
└── README.md
```

---

## ✅ Summary

Google Trends isn't just a reflection of curiosity — it might hold clues about what’s to come. This project offers a simple, visual approach to exploring those clues with real data.

---

## 📜 License

This project is released under the MIT License.