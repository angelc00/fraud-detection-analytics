# Fraud Detection Analytics
**Python & SQL | Consumer Operations | Fintech**

End-to-end fraud detection project using 284,807 real credit card transactions.
Built to simulate the work of a Consumer Operations Data Analyst in a fintech environment.

## Skills Demonstrated
- **Python**: pandas, numpy, matplotlib, automated pipelines
- **SQL**: GROUP BY, HAVING, CASE WHEN, CTE, JOIN, Window Functions (LAG, ROW_NUMBER, SUM OVER)
- **Anomaly Detection**: IQR method, behavioral pattern flagging, alerting systems
- **Data Visualization**: 4-panel operations dashboard

## Project Structure
```
fraud-detection-analytics/
├── fraud_detection_analytics.ipynb   # Main notebook
├── fraud_dashboard.png               # Output dashboard
└── README.md
```

## Dataset
- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions | 473
 fraud cases | 0.173% fraud rate

## How to Run
1. Open `fraud_detection_analytics.ipynb` in Google Colab
2. Upload `creditcard.csv` from Kaggle
3. Run all cells

## Key Results
- Fraud capture rate: 122% (multi-method detection)
- Peak fraud hour: 02:00 (1.45% fraud rate — 8x average)
- Critical alert triggered: 2,935 high-value transactions flagged
- SQL: 7 queries from basic to advanced window functions

---
*Angel Chiang | IMT Atlantique M2 IT & Cybersécurité | angelchiang00@gmail.com*
