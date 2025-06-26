# FUTURE_DS_02
# 📈 Social Media Campaign Performance Tracker

An interactive analytics dashboard built using [Streamlit](https://streamlit.io/) and [Plotly](https://plotly.com/python/), designed to help digital marketers and analysts visualize and evaluate the performance of Facebook Ads campaigns.


## 📊 Features

- 💰 **KPI Metrics**: Total spend, impressions, clicks, conversions
- 📆 **Date Filtering**: Analyze campaigns by date range
- 👥 **Demographic Breakdown**: Filter by gender and age group
- 📢 **Campaign-wise Performance**: Visualize spend and CTR per campaign
- 📈 **CTR Trends**: Track click-through rate over time
- 🧮 **Conversion Insights**: Compare approved vs. total conversions
- 🧊 **Bubble Chart**: Clicks vs. Impressions with spend as size
- ⬇️ **Interactive & Expandable**: Built with Streamlit and Plotly


## 🧠 Dataset Overview

This dashboard uses a **Facebook Ads Performance Dataset** with the following columns:


**Dataset Source**:  
[Facebook Ads Performance on Kaggle](https://www.kaggle.com/) *(insert actual link if known)*

> **Note**: The dataset file should be saved as `data.csv` in the root directory of this project.


## 📁 Project Structure

📦 facebook-ads-dashboard/
├── data.csv # Your Facebook Ads dataset
├── facebook_ads_dashboard.py # Streamlit dashboard app
├── README.md # Project documentation
└── requirements.txt # Python dependencies (optional)

## 🚀 Getting Started

1. **Install Dependencies**

```bash
pip install streamlit pandas plotly
✅ Example Metrics Displayed
Total Spent: $25,000.00

Total Clicks: 12,540

Avg CTR: 3.12%

Approved Conversions: 865

🔧 Future Enhancements
📤 Export filtered data as CSV

🌎 Add location-based breakdowns

📱 Device & platform targeting analysis

📊 ROI computation (if revenue data available)

🧑‍💻 Author
Mohd Shami
Built as a hands-on Streamlit + Data Analytics project for showcasing Facebook ad campaign performance.
