# automobile-sales-analysis
Dashboard and data analysis project for visualizing automobile sales trends and recession impacts using Pandas, Seaborn, Plotly, and Dash.


# Automobile Sales Analysis Dashboard

This project is a complete data analysis and interactive dashboard built with **Pandas**, **Seaborn**, **Matplotlib**, **Plotly**, and **Dash** to visualize automobile sales data over time and analyze the impact of economic factors like recessions and unemployment.

---

## 📊 Part 1: Data Analysis (Jupyter Notebook)

In the notebook, we:

- Visualized yearly automobile sales
- Compared sales across vehicle types during recession vs. non-recession periods
- Built seaborn boxplots, scatter plots, line charts, and pie charts
- Analyzed the relationship between unemployment and vehicle sales

Notebook file: [`Automobile_Sales_Analysis_Complete.ipynb`](Automobile_Sales_Analysis_Complete.ipynb)

---

## 📈 Part 2: Interactive Dashboard (Dash App)

The Dash application allows users to:

- Select between _Recession Report_ and _Yearly Report_
- Choose a specific year (for Yearly report)
- View multiple plots: line, bar, and pie charts
- Analyze advertising spend, sales volumes, vehicle types, and economic influence

### 🚀 To Run the App:

Make sure you have the required libraries:

```bash
pip install dash plotly pandas
