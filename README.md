# What Actually Drives a Restaurant's Rating in Bangalore?
### An EDA of 51,717 Zomato restaurants

## 🎯 TL;DR
Cost weakly predicts rating (r ≈ 0.38). Location and service features 
matter more. Premium neighborhoods (Koramangala, Indiranagar) 
consistently outperform. Online ordering correlates with slightly 
higher ratings, but the effect is small.

## ❓ The Question
Is rating driven more by **cost**, **location**, **cuisine**, or 
**service features** (online ordering, table booking)?

## 📊 Data
- **Source:** Zomato Bangalore Restaurants (Kaggle)
- **Size:** 51,717 restaurants × 17 columns
- **Time:** Snapshot (current as of dataset publish)

## 🔍 Key Findings

| # | Finding |
|:-:|:---|
| 1 | Ratings cluster between **3.5 and 4.2** — very few below 3.0 |
| 2 | Cost vs rating correlation: **r ≈ 0.38** (moderate, not strong) |
| 3 | Premium locations (**Koramangala, Indiranagar, Lavelle Road**) lead in avg rating |
| 4 | Online ordering → slightly higher median rating (~0.1–0.2 stars) |
| 5 | **North Indian & Chinese** dominate; South Indian trails (delivery skew) |

## 🛠️ Tools Used
- Python 3.x
- Pandas, NumPy — data cleaning & analysis
- Matplotlib, Seaborn, Plotly — visualization
- Jupyter Notebook (VS Code)

## 📂 Project Structure