# Zomato Restaurant Trend Analysis — Bangalore
![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)
![Dataset](https://img.shields.io/badge/Dataset-50K%2B%20Records-red)

## Overview
End to end data analysis project on 50,000+ restaurant listings 
from Zomato's Bangalore dataset. The goal is to uncover trends 
in cuisines, pricing, ratings, and locality patterns.

## Tools Used
Python | Pandas | Matplotlib | Seaborn | Jupyter Notebook | Power BI

## Dataset
Zomato Bangalore Restaurants — Kaggle (Himanshu Poddar)
51,717 rows, 17 columns

## Project Structure
- `notebooks/` — Jupyter notebook with full analysis and markdown documentation
- `visuals/` — Power BI dashboard file
- `data/` — Cleaned datasets

## Project Phases

### Phase 1 — Data Cleaning
- Fixed rate column stored as string (e.g. "4.1/5" → 4.1)
- Fixed cost column with commas (e.g. "1,200" → 1200.0)
- Handled 7,775 missing ratings — dropped for analysis, not replaced
- Removed duplicate listings — maintained two dataframes for different analyses
- Renamed long column names for cleaner code

### Phase 2 — Exploratory Data Analysis

| Analysis | Chart Type | Key Finding |
|---|---|---|
| Top 10 Cuisines | Horizontal Bar | North Indian dominates |
| Rating Distribution | Histogram | Peak at 3.8 |
| Online Order vs Rating | Bar Chart | 0.3 rating difference |
| Top 10 Locations | Horizontal Bar | Whitefield leads |
| Cost Distribution | Histogram | 80% under ₹1,000 |
| Restaurant Type | Horizontal Bar | Quick Bites dominates |
| Cost vs Rating | Scatter Plot | No strong correlation |
| Votes vs Rating | Scatter Plot | Threshold at 2,000 votes |

### Phase 3 — Power BI Dashboard
Interactive dashboard with:
- 4 KPI cards — Total Restaurants, Average Rating, Average Cost, Most Popular Cuisine
- Top 10 Cuisines and Rating Distribution charts
- Top 10 Locations and Restaurant Type Breakdown
- Online Order vs Rating comparison
- Location and Online Order slicers for interactive filtering

## Business Insights

| Insight | Recommendation |
|---|---|
| North Indian and Chinese most competitive | New owners should consider Biryani or Desserts for less competition |
| Whitefield most crowded | Bellandur and Jayanagar offer less competition with high footfall |
| Online ordering linked to higher ratings | New restaurants should enable online ordering from day one |
| Bars and microbreweries rate highest | Start as a bar, scale to microbrewery for maximum customer satisfaction |
| 80% restaurants under ₹1,000 | Premium dining above ₹2,000 is an untapped market opportunity |

## Key Findings
1. North Indian and Chinese cuisines dominate with 3,000+ restaurants each
2. Most restaurants are rated between 3.5 and 4.0 with a peak at 3.8
3. Restaurants with online ordering rate 0.3 higher on average
4. Whitefield is the most competitive location with 820 restaurants
5. 80% of restaurants are priced under ₹1000 for two people
6. Quick Bites dominates with 4,900+ listings driven by Bangalore's IT culture
7. Bars and microbreweries have the highest average rating above 4.5
8. Restaurants with 2,000+ votes consistently rate above 4.0
