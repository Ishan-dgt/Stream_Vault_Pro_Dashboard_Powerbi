# 🎬 StreamVault Pro — OTT Intelligence Dashboard

An interactive OTT analytics dashboard built using **HTML, CSS, and JavaScript**, designed to analyze streaming platform content across multiple dimensions like platform, genre, rating, country, and release year.

---

## 📊 Project Overview

**StreamVault Pro** is a visually rich, dark-themed dashboard that provides insights into OTT content distribution across 6 major platforms.

- 📺 Platforms: Netflix, Amazon Prime, Hotstar, Sony LIV, Apple TV+, ZEE5  
- 🎬 Total Titles: 70  
- 🌍 Countries: USA, India, UK, Spain, South Korea  
- 📅 Time Range: 2014 – 2023  

The dashboard replicates a **Power BI-style experience using pure frontend technologies**.

---

## 📂 Data Source

- Excel Dataset: `StreamVault_PowerBI_Ready.xlsx` (user-provided)
- Dashboard Source Reference: `mymovies_updated-1.csv` :contentReference[oaicite:0]{index=0}  

### Dataset Features:
- Title  
- Genre  
- Release Year  
- Rating (TV-MA, PG-13, etc.)  
- Country  
- Platform  
- Duration (minutes) :contentReference[oaicite:1]{index=1}  

---

## 🚀 Features

### 🔍 Interactive Filters (Slicers)
- Platform (logo-based selection)
- Genre selection
- Rating filter
- Country filter
- Year range slider
- Reset all filters button :contentReference[oaicite:2]{index=2}  

---

### 📈 KPI Metrics
- Total Titles
- Active Platforms
- Average Duration
- Country Distribution
- Adult Content % :contentReference[oaicite:3]{index=3}  

---

### 📊 Visualizations

- 📊 Titles by Platform (Bar Chart)
- 🎭 Genre Distribution Grid
- 🌍 Country-wise Donut Chart
- ⭐ Rating Distribution Bars
- ⏱️ Avg Duration by Platform
- 📈 Yearly Trend Analysis
- 🔥 Insights Section (Key Findings) :contentReference[oaicite:4]{index=4}  

---

## 🧠 Key Insights

- Netflix dominates with ~28.5% content share  
- India & USA contribute ~90% of total content  
- 2020 is the peak content release year  
- TV-MA is the most common rating  
- Action & Drama are the most popular genres :contentReference[oaicite:5]{index=5}  

---

## 🛠️ Tech Stack

- **HTML5** — Structure  
- **CSS3** — Advanced UI (dark theme, gradients, animations)  
- **JavaScript (Vanilla)** — Filtering, state management, dynamic updates  

---

## ⚙️ How It Works

- Dataset is embedded directly in JavaScript (`DATA` array)  
- Filters update a global state object  
- UI dynamically refreshes based on filtered data  
- No backend required (fully client-side) :contentReference[oaicite:6]{index=6}  

---

## 📁 Project Structure
