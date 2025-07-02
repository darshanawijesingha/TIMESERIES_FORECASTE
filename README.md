# 🔮 Time Series Forecasting: 4 Types of Water (Next 60 Days)

This project performs time series forecasting for **four different types of water** using a single dataset. It predicts future demand for the next **60 days** using historical daily data.

---
![TYPE1](img.png)
![TYPE1](img.png)
![TYPE1](img.png)
![TYPE1](img.png)
![TYPE1](img.png)
![TYPE1](img.png)
## 📁 Data

The project uses one CSV file: `water_data.csv`

### 🔢 Data Format

The CSV must contain:

| date       | 1       | 2        | 3    | 4       |
|------------|---------|----------|------|---------|
| 2024-01-01 | 120     | 95       | 240  | 88      |
| 2024-01-02 | 130     | 100      | 235  | 90      |
| ...        | ...     | ...      | ...  | ...     |

- **date**: Date of record (YYYY-MM-DD)
- **1**, **2**, **3**, **4**: daily values for each water type

> ⚠️ Make sure the file has no missing dates or null values.

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
