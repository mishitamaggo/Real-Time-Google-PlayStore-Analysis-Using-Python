# 📱 Google Play Store Apps Analysis Dashboard

This repository contains a comprehensive data analysis and visualization project based on the **Google Play Store Apps Dataset**. The goal is to extract business insights from mobile app data using Python libraries such as Pandas, NumPy, and Plotly, and visualize it through time-sensitive interactive charts in a Google Colab notebook.

---

## 📂 Repository Contents

| File/Folder                  | Description                                                                 |
| `Playstore_Analysis.ipynb`  | Google Colab notebook containing data cleaning, analysis, and visualizations. |
| `README.md`                 | This file — provides project overview, setup, and usage instructions.      |

---

## 📊 Visualizations Overview

### 1. **Scatter Plot**  
Visualizes the relationship between **Revenue and Number of Installs** for **paid apps** with:
- Trendline (linear regression)
- Points color-coded by app category

### 2. **Grouped Bar Chart**  
Compares **average rating** and **total review count** for the **top 10 categories** by installs, **only if:**
- Rating ≥ 4.0
- Size > 10 MB
- Last updated in **January**
- Visible **only from 3 PM to 5 PM IST**

### 3. **Bubble Chart**  
Analyzes the relationship between **app size and average rating** with:
- Bubble size = number of installs
- Categories filtered (Game, Beauty, Business, Comics, etc.)
- Filters: rating > 3.5, reviews > 500, app name must **not** contain "S", installs > 50k, sentiment subjectivity > 0.5
- **Language translation** for select categories (e.g., Beauty → Hindi, Business → Tamil)
- Game category highlighted in pink
- Visible **only from 5 PM to 7 PM IST**

---

## ⚙️ Technologies Used

- 🐍 Python
- 📊 Plotly (interactive visualizations)
- 📈 Pandas, NumPy (data manipulation)
- 🕒 datetime, pytz (timezone filtering)
- 🧠 Google Colab (execution environment)

---

## 🚀 Getting Started

### 🔧 Setup Instructions

1. Clone the repo:
   ```bash
   git clone [https://github.com/yourusername/google-play-analysis.git](https://github.com/mishitamaggo/Real-Time-Google-PlayStore-Analysis-Using-Python)
