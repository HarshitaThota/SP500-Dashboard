# SP500-Dashboard

📈 S&P 500 Analytics Dashboard
This Colab notebook loads historical S&P 500 fundamentals (Real Price & Dividend) and walks through a complete finance analytics workflow:

🔧 Libraries & Tools

Data wrangling: pandas, numpy
Static visualization: matplotlib, seaborn
Interactive visualization: plotly.express
Regression: Seaborn’s regplot / sklearn.linear_model
📊 KPIs Computed

Average Daily Return
Volatility (Std Dev of daily returns)
Cumulative Return
Max Drawdown
Return vs Dividend Yield Correlation
📈 Visualizations

Line chart: S&P 500 price over time
Bar chart: Average monthly return (last 5 years)
Interactive scatter + regression: Daily return vs. dividend yield (hover for exact values)
🚀 Workflow

Load & clean data
Compute returns, dividend yield, and core KPIs
Render static charts with Matplotlib/Seaborn
Build an interactive Plotly chart with tooltips
Annotate insights (drawdowns, volatility, correlations)
Feel free to scroll down to the interactive section at the end to explore point-and-hover details on each observation!