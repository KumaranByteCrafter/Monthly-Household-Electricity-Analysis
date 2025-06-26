# ⚡ Monthly Household Electricty Analysis

This project analyzes household electricity usage by estimating appliance-wise energy consumption, comparing estimated usage with actual units, and providing recommendations to reduce energy usage and save costs.

---

## 🎯 Objectives
- Estimate appliance-wise energy usage using assumed wattages and actual usage times.
- Compare estimated usage with actual units consumed.
- Identify high-consuming appliances.
- Visualize monthly trends and seasonal peaks.
- Provide actionable recommendations for cost and energy optimization.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** (Data analysis)
- **Matplotlib / Seaborn** (Data visualizations)
- **Jupyter Notebook**

---

## 📁 Dataset
The dataset contains:
- `Month`: Date
- `Units_Used`: Actual kWh consumed
- `Bill_Amount`: Total cost
- `People`: Number of household members
- `Fan_Hours`: Hours fans were used
- `AC_Hours`: Hours AC units were used
- `Fridge_Watt`: Fridge wattage
- `Washing_Hours`: Washing machine usage
- `Cooking_Mins`: Cooking time (minutes)

---

## ⚡️ Methodology
1. **Conversion of wattage to kWh**:
    ```
    Energy (kWh) = (Power (W) * Usage Time (h) * Days) / 1000
    ```
2. **Visualization**:
    - Compare actual vs estimated usage
    - Visualize appliance contributions
    - Identify top-consuming appliances
3. **Cost Estimation**:
    ```
    Cost = Estimated_kWh * Unit_rate
    ```
    Unit rate assumed: **₹8 per kWh**.

---

## 📊 Results
- Compared actual units vs estimated usage across months
- Created trend lines, bar charts, and heatmaps
- Identified top-consuming appliances:
    - **AC** (~₹36,420 monthly cost at average usage rate)
    - **Fan** (~₹24,007.50 monthly cost)
    - **Washing Machine** (~₹570)
    - **Fridge** (~₹368.64)
    - **Cooking** (~₹360.33)

---

## 💡 Recommendations
1. **Optimize AC Usage**: Set to 24 °C, use for fewer hours.
2. **Use Energy-Efficient Fans**: Maintain regular cleaning or upgrade old units.
3. **Optimize Cooking Time**: Reduce cooking durations and use energy-efficient appliances.
4. **Regular Maintenance**: Ensure fridges and washing machines operate efficiently.

---

## 🚀 Getting Started
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/KumaranByteCrafter/Monthly Household Electricity Analysis.git
    ```

2. **Run the Notebook**:
    ```bash
    jupyter notebook ebill.ipynb
    ```

---

## 📈 Visualizations
- **Monthly Usage vs Estimated Usage**
- **Appliance-wise Average Consumption Bar Graph**
- **Monthly Appliance Usage Heatmap**

---


## 📄 License
MIT License
