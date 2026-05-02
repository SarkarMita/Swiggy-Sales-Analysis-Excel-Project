# 🍔 Swiggy Sales Insights Dashboard — Excel Analytics Project

> **An end-to-end Sales & Revenue Analysis project built on real Swiggy order data — covering 1,97,430 orders across 28 Indian states, using Microsoft Excel for data cleaning, pivot analysis, and interactive dashboard creation.**

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Dataset Description](#dataset-description)
- [KPIs Tracked](#kpis-tracked)
- [Charts & Visualisations](#charts--visualisations)
- [Key Findings & Insights](#key-findings--insights)
- [Recommendations](#recommendations)
- [Key Learnings](#key-learnings)
- [Project Structure](#project-structure)
- [How to Use This File](#how-to-use-this-file)
- [Tools Used](#tools-used)
- [Author](#author)

---

## 📖 Project Overview

This project analyses Swiggy's food delivery order data to understand how sales are distributed across time, geography, food type, and customer behaviour. The goal was to build a clean, interactive Excel dashboard that any business stakeholder — not just a data analyst — could open and immediately understand.

The project follows a standard analytics workflow: raw data → cleaning → pivot analysis → KPI calculation → visualisation → insight generation.

---

## 🧩 Problem Statement

Swiggy operates across dozens of Indian cities, handling hundreds of thousands of orders every month. With so much data flowing in, the business needs answers to questions like:

- Which months and days are driving the most revenue?
- Are vegetarian or non-vegetarian orders contributing more to sales?
- Which cities and states are the top performers?
- How is quarterly performance trending in terms of sales, ratings, and order volumes?
- Are there any weekly patterns in customer ordering behaviour?

This project was built to answer exactly these questions — using nothing but Excel, pivot tables, and a well-structured dashboard.

---

## 📂 Dataset Description

| Field | Description |
|---|---|
| **State** | Indian state where the order was placed |
| **City** | City of the order |
| **Order Date** | Date of the transaction |
| **Day** | Day of the week (Mon–Sun) |
| **Week** | Week number of the year |
| **Quarter** | Business quarter (Q1, Q2, Q3) |
| **Restaurant Name** | Name of the restaurant |
| **Location** | Locality/neighbourhood |
| **Category** | Food category (e.g., Main Course, Desserts, Snacks) |
| **Dish Name** | Name of the specific dish ordered |
| **Food Type** | Veg or Non-Veg |
| **Price (INR)** | Order value in Indian Rupees |
| **Rating** | Customer rating for that order |
| **Rating Count** | Number of reviews received |

**Dataset Size:** 1,97,430 rows × 14 columns  
**Time Period:** January 2025 – August 2025 (Q1 to Q3)  
**Geographic Coverage:** 28 states, 28 cities across India

---

## 📊 KPIs Tracked

| KPI | Value |
|---|---|
| 💰 Total Sales | ₹5.30 Crore (₹53.01M) |
| ⭐ Average Rating | 4.34 / 5 |
| 🛒 Average Order Value | ₹268.51 |
| 📝 Total Rating Count | 55.91 Lakh (5.59M) |
| 📦 Total Orders | 1,97,430 |

---

## 📈 Charts & Visualisations

### 1. Monthly Sales Trend
Shows how total revenue fluctuates month by month. Helps identify seasonal peaks and slower months that may need promotional support.

### 2. Daily Sales Trend
Highlights order and revenue variations across each day of the week. Essential for understanding when customers are most active — critical for staffing and marketing decisions.

### 3. Total Sales by Food Type (Veg vs Non-Veg)
Compares the revenue contribution from vegetarian and non-vegetarian orders. Gives a quick picture of what the majority of Swiggy's customer base is ordering.

### 4. Total Sales by State (Map Visualisation)
Displays state-wise revenue distribution on an India map. Helps leadership see at a glance which regions are performing well and where there is untapped potential.

### 5. Quarterly Performance Summary
Combines Sales, Ratings, and Orders into a single table by quarter (Q1, Q2, Q3). Useful for tracking business growth and understanding if quality is being maintained as volumes grow.

### 6. Top 5 Cities by Sales
Identifies the leading cities contributing the most revenue. Useful for resource allocation, targeted campaigns, and expansion planning.

### 7. Weekly Sales Trends
Monitors weekly fluctuations in sales throughout the year to identify consistency or peak periods. Helps operations teams plan delivery capacity week by week.

---

## 🔍 Key Findings & Insights

### Sales & Revenue
- Total revenue for the period (January–August 2025) stood at **₹53.01 Million (₹5.30 Crore)**, which is a strong performance across just three quarters.
- The **Average Order Value of ₹268.51** suggests customers are placing mid-sized orders, not just single-item snack orders. There is headroom to push this higher through bundling and combo strategies.

### Monthly Trends
- **January was the highest-grossing month** at ₹68.25 Lakh, followed closely by August (₹67.91L) and May (₹67.93L).
- **February had the lowest sales** at ₹62.69 Lakh — likely due to a shorter month. Still, the dip is worth monitoring.
- Overall, monthly sales stayed **quite consistent** between ₹62L and ₹68L, pointing to a stable, loyal customer base rather than a heavily seasonal business.

### Daily Patterns
- **Saturday is the single biggest sales day** of the week at ₹77.82 Lakh — Indians love ordering food on weekends, and this data confirms it.
- **Sunday comes in second** at ₹76.38 Lakh, making the weekend as a whole the strongest two-day window.
- **Tuesday is the weakest day** at ₹73.59 Lakh. Mid-week ordering intent dips — a Tuesday discount campaign could lift this meaningfully.

### Food Type (Veg vs Non-Veg)
- **Vegetarian orders dominate** with ₹3.41 Crore in sales — that is **64.5% of total revenue**.
- Non-Veg contributed ₹1.88 Crore (35.5%).
- This reflects India's large vegetarian population and the wide variety of veg options available across cuisines.

### City & State Performance
- **Bengaluru is India's food delivery capital** — with ₹54.56 Lakh in sales, it is almost ₹14 Lakh ahead of the second-placed city.
- **Lucknow, Hyderabad, Mumbai, and New Delhi** round out the top 5, each sitting between ₹28L and ₹31L.
- There is a notable gap between Bengaluru and the rest, suggesting strong city-level concentration of Swiggy's business.

### Quarterly Performance
- **Q1 (January–March):** ₹1.96 Crore | Rating: 4.34 | Orders: 73,096
- **Q2 (April–June):** ₹1.99 Crore | Rating: 4.34 | Orders: 74,163
- **Q3 (July–August only):** ₹1.34 Crore | Rating: 4.34 | Orders: 50,171
- Q3 looks lower because it covers only two months, not a full quarter — context matters here.
- The **most important takeaway is consistency** — the average rating held steady at **4.34 across all three quarters**, meaning quality did not drop even as volumes grew.

### Customer Ratings
- With **55.91 Lakh rating submissions** and an average of 4.34 out of 5, customer satisfaction is high.
- This consistency across 28 cities and hundreds of restaurant partners signals that Swiggy's quality standards are working at scale.

---

## 💡 Recommendations

**1. Double down on weekends**  
Saturday and Sunday together account for a disproportionate share of weekly sales. Premium offers, new restaurant launches, and marketing pushes should be concentrated around weekends to ride the natural demand spike.

**2. Fix the Tuesday slump with targeted nudges**  
Tuesday is the softest day of the week. A simple "Tuesday Special" notification — even a flat ₹20–₹30 discount on select restaurants — could lift mid-week order volume without burning much margin.

**3. Bengaluru deserves its own strategy**  
Bengaluru is not just the top city — it is in a league of its own with 75% more sales than the #2 city. This market warrants dedicated restaurant partnerships, exclusive menus, and loyalty rewards that do not yet exist in other cities.

**4. Grow the Non-Veg segment intentionally**  
With Veg commanding 64.5% of sales, Non-Veg restaurants are slightly underrepresented. Onboarding more quality Non-Veg partners — especially in northern cities like Lucknow and New Delhi where meat-based cuisine is deeply popular — is a clear opportunity.

**5. Push Average Order Value from ₹268 to ₹300+**  
With smart cross-sell tactics — "add a dessert for ₹49", "complete your meal with a beverage" — pushing AOV to ₹300+ is realistic and would add significant revenue without acquiring a single new customer.

**6. Expand into high-potential states**  
Several large Indian states show low sales contribution. States like Bihar, Odisha, Jharkhand, and the Northeast represent untapped markets. Early mover advantage in Tier-2 cities within these states could pay off significantly.

**7. Protect the 4.34 rating as a business KPI**  
Rating consistency is a competitive moat. Every operational decision — delivery time, packaging, partner onboarding — should be stress-tested for its impact on ratings before being rolled out.

---

## 🎓 Key Learnings

**On the technical side:**
- **Pivot Tables are the backbone of Excel analytics.** Once raw data is clean and structured, pivot tables can answer almost any business question in minutes. Slicing the same pivot by time, geography, and category is a skill that pays off every time.
- **Data structure matters more than data volume.** This dataset had nearly 2 lakh rows but because each column was clearly defined and consistently formatted, the analysis was fast and clean. Messy data at 10,000 rows is harder than clean data at 2 lakh.
- **Map visualisations in Excel are underused.** Most people default to bar and pie charts. The India map in this dashboard communicates geographic distribution in a way no table ever could.
- **KPI cards give instant context.** Having five headline numbers visible at all times means anyone opening the file immediately understands the scale of what they are looking at.

**On the analytical side:**
- **Consistency is as interesting as spikes.** People usually look for the highs and lows. But here, the 4.34 rating holding steady across all quarters was actually one of the most meaningful findings — and it almost got missed.
- **Always look at absolute numbers AND percentages.** Q3 looks weak at ₹1.34 Crore but it only covers two months. Comparing it directly to Q1 and Q2 without this context leads to a wrong conclusion.
- **City-level data unlocks operational insight.** The state map is great for a high-level view, but the city breakdown is where real decisions get made. The Bengaluru gap is an entire strategic story on its own.

---

## 🗂️ Project Structure# Swiggy-Sales-Analysis-Excel-Project
