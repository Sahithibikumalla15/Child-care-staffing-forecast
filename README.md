# 🧒 Childcare Staffing Forecast

This project predicts 30-minute interval staffing needs for childcare rooms based on historical student check-in and check-out data from the Child Saving Institute (Omaha). The forecasts help optimize staffing decisions, improve cost-efficiency, and ensure compliance with age-based student-to-staff ratios.

---

## 💡 What the Project Does

- Forecasts student counts per room in 30-minute intervals for:
  - A “typical week”
  - The next calendar week after the data ends
- Converts student counts into staffing estimates using age-specific ratios
- Compares two time series forecasting models:
  - Prophet
  - Holt-Winters (Exponential Smoothing)
- Visualizes results in an interactive Streamlit dashboard

---

## 🌟 Why It’s Useful

Childcare centers need to staff rooms efficiently to:
- Meet regulatory ratios (e.g., 4:1 for infants)
- Avoid overstaffing or understaffing
- Adapt to fluctuating attendance patterns
- Justify staffing budgets using data-driven forecasts

---

## 🚀 How to Get Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/staffing-forecast.git
   cd staffing-forecast
