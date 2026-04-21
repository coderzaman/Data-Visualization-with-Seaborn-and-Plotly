# Data Visualization with Seaborn and Plotly 📊

A comprehensive guide and codebase exploring data visualization in Python. This repository demonstrates how to build structural layouts using Matplotlib, create beautiful statistical graphics with Seaborn, and build interactive web-ready charts using Plotly.

## 🌟 Overview
This project serves as both a tutorial and a reference guide for mastering Python data visualization. It breaks down the often-confusing relationship between Matplotlib (the engine) and Seaborn (the high-level interface), and transitions into Plotly for modern, interactive dashboards.

## 🚀 Key Concepts Covered

### 1. The Core Architecture (Matplotlib + Seaborn)
* **Figure-Level vs. Axes-Level Plots:** Understanding the structural difference between `sns.scatterplot()` (building blocks) and `sns.relplot()` (FacetGrid managers).
* **Mastering Grid Layouts:** Using `plt.subplots(nrows, ncols)` to build custom dashboards.
* **Canvas Sizing:** Understanding how `figsize=(width, height)` calculates the exact inches allocated to each subplot to avoid squished graphs.

### 2. Statistical Visualization (Seaborn)
* **Distributions:**
  * `sns.countplot()`: Tallying categorical data.
  * KDE (Kernel Density Estimates): Understanding how individual data points stack to create smooth curves.
* **Aggregations & Confidence:**
  * `sns.barplot()`: Calculating averages and understanding error bars (variance/spread).
* **Trend Analysis:**
  * `sns.regplot()` vs `sns.lmplot()`: Single regression trendlines vs. categorized multi-model trendlines.
* **Exploratory Data Analysis (EDA) Power Tools:**
  * `sns.jointplot()`: Deep-diving into the relationship between two variables while analyzing their 1D marginal distributions.
  * `sns.pairplot()`: Generating a massive grid to find hidden correlations across an entire dataset.

### 3. Interactive Web Charts (Plotly Express)
* **Dynamic Bubble Charts:** Using `px.scatter` with `size` and custom `hover_data` tooltips.
* **Time-Series Analysis:** Plotting trends with `px.line` and modifying visual elements using `fig.update_traces()`.
* **Stacked Histograms:** Creating rich, interactive distribution charts with `px.histogram`.

## 🛠️ Technologies Used
* **Python 3.x**
* **Pandas** (Data manipulation)
* **Matplotlib** (Core rendering engine & grid layouts)
* **Seaborn** (Statistical data visualization)
* **Plotly Express** (Interactive graphing)

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/Data-Visualization-with-Seaborn-and-Plotly.git](https://github.com/your-username/Data-Visualization-with-Seaborn-and-Plotly.git)
   cd Data-Visualization-with-Seaborn-and-Plotly
