# Australian Domestic Flight Reliability Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20|%20Seaborn%20|%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Executive Summary
In the high-stakes world of aviation, **reliability is currency**. This project analyzes historical data from Australia's top 5 domestic flight routes to identify operational bottlenecks, seasonal disruption patterns, and airline performance benchmarks.

The goal is to provide **data-driven recommendations** for travelers and operational teams to minimize the impact of flight cancellations.

---

## Key Business Insights

### 1. The "Winter Crunch" (Seasonality Analysis)
* **Finding:** Flight cancellations spike significantly during the Australian winter months (**June & July**).
* **Impact:** The **Sydney ↔ Melbourne** route is the most heavily affected, with cancellation rates reaching up to **11%** due to weather conditions.
* **Strategic Recommendation:** Operational buffers (standby crews/aircraft) should be increased by 15% during Q2/Q3 on southern routes.

### 2. Airline Reliability Benchmarking
* **Top Performers:** **Qantas** and **Virgin Australia** demonstrate the highest stability with minimal variance in schedule adherence.
* **High Variance:** **Jetstar** and **Tigerair** show a wider spread in cancellation rates, indicating higher operational risk.
* **Traveler Advice:** For time-sensitive business travel, legacy carriers (Qantas/Virgin) are the statistically safer choice.

---

## Visualizations

### 1. Cancellation Distribution
*Most flights run smoothly, but the "long tail" of outliers reveals days of major disruption.*
![Distribution Plot](PLACEHOLDER_FOR_HISTOGRAM_IMAGE_LINK)

### 2. Airline Performance Comparison
*A side-by-side comparison showing Qantas's stability vs. Jetstar's variability.*
![Boxplot](PLACEHOLDER_FOR_BOXPLOT_IMAGE_LINK)

### 3. Heatmap of Disruption (Route vs. Month)
*The "Red Zone" in June/July clearly marks the winter operational challenge.*
![Heatmap](PLACEHOLDER_FOR_HEATMAP_IMAGE_LINK)

---

## Tech Stack & Methodology
* **Python:** Core programming language.
* **Pandas:** Data manipulation, pivot tables, and aggregation.
* **Seaborn & Matplotlib:** Advanced data visualization and statistical graphics.
* **Jupyter Notebook:** Interactive development environment.

**Key Techniques Used:**
* Data Cleaning & Preprocessing.
* Feature Engineering (Calculated `Cancellation_Rate`).
* Exploratory Data Analysis (EDA).
* Statistical Analysis (Distribution & Outlier Detection).

---

## How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/DiaaShousha/Australian-Flight-Reliability-Analysis.git](https://github.com/DiaaShousha/Australian-Flight-Reliability-Analysis.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas seaborn matplotlib
    ```
3.  Open the notebook:
    ```bash
    jupyter notebook Australian_Flight_Reliability_Analysis.ipynb
    ```

---

## Author
**Diaa Shousha**
* **Role:** Data Analyst & AI Engineer
* **Focus:** Turning raw data into strategic business stories.
* [LinkedIn Profile](https://www.linkedin.com/in/abdelrahman-diaa-080496334/)
