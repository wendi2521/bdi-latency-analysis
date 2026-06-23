# Genie Latency Analysis Dashboard

Interactive dashboard for analyzing Genie tool call latency with comprehensive visualizations.

## 📊 View Live Dashboard

**[View Interactive Dashboard](https://[YOUR-USERNAME].github.io/genie-latency-analysis/genie_latency_analysis_with_boxplots.html)**

*(Replace [YOUR-USERNAME] with your GitHub username after enabling GitHub Pages)*

## 📈 Features

- **Combined Box Plot Visualization**: Compare asking_ai, pending_warehouse, and Execution stages side-by-side
- **Logarithmic Scale**: Better visibility of median/mean values despite outliers
- **Statistical Analysis**: Comprehensive metrics including median, mean, min, max, and percentiles
- **High Duration Analysis**: Detailed breakdown of queries taking >50 seconds
- **Tool-Level Breakdown**: Performance analysis for each tool:
  - query_genie
  - get_data_aggregation
  - get_data_aggregation_edfx
  - PSAnalysisResults
  - get_benchmark
  - query_cbmo_portfolio_loan_review
- **Interactive Visualizations**: Powered by Plotly.js with responsive charts

## 🚀 Key Insights

- **Query Execution** dominates total time at 49.8% (mean: 20.26s)
- **Warehouse Wait** accounts for 31.7% (mean: 12.92s)
- **AI Processing** takes 20.4% (mean: 8.30s)
- 24.3% of queries exceed 50 seconds, with execution being the bottleneck in 81.2% of these cases

## 📊 Data Overview

- **Total Records**: 1,331 tool call records
- **Median Time**: 35.31s
- **Mean Time**: 40.72s
- **P90 Time**: 74.45s

## 🛠️ Technical Details

The dashboard uses:
- **Plotly.js** for interactive visualizations
- **Box plots** with logarithmic scale to handle outliers effectively
- **Responsive design** for viewing on any device

---

*Analysis Date: June 2026*
