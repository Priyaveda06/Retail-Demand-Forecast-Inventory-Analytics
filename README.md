# Retail Demand Forecast & Inventory Analytics

## 📌 Overview

Analyzed **73,100 retail sales and inventory records** to evaluate demand forecast accuracy, identify inventory risks, and generate business recommendations.

The analysis identified a persistent **over-forecasting bias** and applied a bias-correction approach to improve forecast accuracy.

## 🛠️ Tools

**Python | Pandas | NumPy | Matplotlib | Statistical Analysis | Exploratory Data Analysis (EDA) | Forecast Accuracy Metrics | Root Cause Analysis**

## 🔍 Analysis

- Evaluated forecast accuracy using **MAPE, MAE, and Forecast Bias**
- Performed root-cause analysis across **stores, products, promotions, seasonality, pricing, and time**
- Analyzed inventory coverage to identify **low- and high-coverage risks**
- Applied a bias-correction approach to calibrate demand forecasts

## 📊 Key Results

| Metric | Original | Corrected |
|---|---:|---:|
| MAPE | 24.72% | **22.13%** |
| MAE | 8.34 | **7.50** |
| Forecast Bias | -5.03 units | **~0 units** |

- Improved MAPE by **10.51%**
- Identified a persistent systematic over-forecasting bias
- Found approximately **50% of records** required inventory review due to low or high coverage

## 💡 Business Recommendations

- Monitor forecast bias, MAPE, and MAE regularly
- Apply forecast calibration to reduce systematic errors
- Prioritize low-coverage inventory for replenishment
- Review high-coverage and no-sales inventory for potential reallocation or excess stock
