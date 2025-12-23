# 🏏 Cricket Team Optimization Dashboard

## 📌 Project Overview
This project focuses on building a **data-driven cricket team selection dashboard** using data scraped from **ESPNcricinfo**. The primary goal is to identify the **best possible players** for forming a **powerful and balanced team** capable of winning matches, based on well-defined performance parameters.

The dashboard is built in **Power BI** and allows users to dynamically filter and analyze players using performance metrics derived from real match data. The entire pipeline—from data collection and preprocessing to visualization and decision-making—is covered in this project.

---

## 🎯 Objective
- Scrape real-world cricket data from ESPNcricinfo
- Clean, preprocess, and transform raw data into analysis-ready format
- Define **player selection parameters** based on cricketing logic
- Build an **interactive Power BI dashboard** to:
  - Identify top-performing players
  - Compare players role-wise
  - Filter players to form an optimal playing XI

---

## 🧩 Project Components

### 1️⃣ Data Source
- **Website:** ESPNcricinfo
- **Data Type:** Player statistics (batting, bowling, strike rate, economy, consistency, etc.)
- **Format:** Scraped raw data (processed using Python)

---

### 2️⃣ Data Preprocessing (Python)
The preprocessing stage is handled using a Python Jupyter Notebook:

📄 **File:** `preprocessing.ipynb`

#### Key Steps Performed:
- Data cleaning (handling missing values, duplicates)
- Feature engineering (calculating derived metrics)
- Standardizing column names
- Role-based classification (Batsman, Bowler, All-Rounder, Wicketkeeper)
- Exporting clean datasets for Power BI consumption

#### Tools & Libraries Used:
- Python
- Pandas
- NumPy
- Jupyter Notebook

This step ensures that the dashboard works with **accurate, consistent, and analysis-ready data**.

---

### 3️⃣ Player Selection Parameters
📄 **File:** `parameters.pdf`

This document defines the **rules and thresholds** used to filter players in the dashboard.

#### Examples of Parameters:
- Minimum batting average
- Strike rate thresholds
- Bowling economy limits
- Minimum matches played
- Role-specific performance benchmarks

These parameters are crucial in:
- Removing underperforming players
- Ensuring fair comparison across roles
- Building a realistic and competitive team

The Power BI dashboard directly uses these parameters for filtering and slicing data.

---

### 4️⃣ Power BI Dashboard
📊 **File:** `dashboard.pbix`

#### Dashboard Features:
- Interactive slicers for roles, teams, and performance metrics
- Player comparison visuals
- Best XI selection logic
- Role-wise top performers
- KPI cards for quick insights

#### What the Dashboard Explains:
- Which players consistently perform better
- How players compare across key performance metrics
- How a **balanced and winning team** can be formed using data

This dashboard transforms raw statistics into **actionable cricketing insights**.

---

## 🛠️ Tech Stack
- **Data Scraping & Processing:** Python (Pandas, NumPy)
- **Data Visualization:** Power BI
- **Documentation:** PDF & Markdown
- **Data Source:** ESPNcricinfo

---

## 📈 Key Insights
- Data-backed player selection reduces bias
- Role-specific metrics are essential for fair evaluation
- Interactive dashboards improve decision-making
- Real-world sports analytics can closely resemble professional team selection strategies

---

## 🚀 How to Use the Project
1. Review `preprocessing.ipynb` to understand data cleaning & transformation
2. Read `parameters.pdf` to understand filtering logic
3. Open `dashboard.pbix` in Power BI
4. Interact with slicers to build your optimal team

---

## 📚 Learning Outcomes
- Practical web-scraped data handling
- End-to-end data analytics workflow
- Power BI dashboard design best practices
- Sports analytics and decision modeling

---

## 🙌 Conclusion
This project demonstrates how **data analytics can be applied to sports** to make smarter, unbiased, and performance-driven decisions. By combining Python preprocessing with Power BI visualization, the dashboard provides a powerful tool for selecting the best possible cricket team.

---

📌 *Note: This project is for educational and analytical purposes only.*

