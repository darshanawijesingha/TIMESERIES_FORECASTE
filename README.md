# 🔮 Time Series Forecasting: 4 Types of Water (Next 60 Days)
## IN THE PREPROCESSING REMOVE OUTLIRE AND NULL VALUES.
## AFTER THAT THE TIME COLUMN MAKES AS INDEX 
![TYPE1](vegetables.png)
This project performs time series forecasting for **four different types of water** using a single dataset. It predicts future demand for the next **60 days** using historical daily data.
## forecast using below all the models.
---
![TYPE1](keelshomepage.png)

---
## sameple of the best model forecasting 
![TYPE1](forecast_total_sale.png)

## according to the we find the best model for each 
![TYPE1](forecast_order_count.png)

## finally need to save with supply chani special requrement bout buffer and need to keeping special order requirments 
![TYPE1](forecast_next_month.png)

-----

# final forecasted images

![TYPE1](forecast_plot_005160.png)
![TYPE1](forecast_plot_005161.png)
![TYPE1](forecast_plot_005162.png)
![TYPE1](forecast_plot_005163.png)

## 📁 Data

The project uses one CSV file: `60.csv`

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
