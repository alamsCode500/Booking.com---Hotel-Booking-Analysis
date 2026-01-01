# 🏨 Booking.com – Hotel Booking Analysis

Exploratory Data Analysis (EDA) | Python | Pandas | Data Visualization

# 📌 Project Overview

This project focuses on analyzing hotel booking data from Booking.com to uncover insights related to cancellations, pricing strategies, customer behavior, and revenue optimization.

Using Python-based Exploratory Data Analysis (EDA), I analyzed over 119,000 hotel bookings to help stakeholders:

* Reduce cancellation rates

* Optimize Average Daily Rate (ADR)

* Improve customer segmentation

* Enhance operational and pricing strategies

This project simulates a real-world business analytics use case commonly faced in the hospitality and travel industry.

# 🎯 Business Objective

To help hotels:

* Understand booking and cancellation behavior

* Optimize pricing and lead-time strategies

* Identify high-value customer segments

* Improve occupancy, revenue, and guest experience

# 📊 Dataset Information

* Source: Booking.com hotel booking data

* Rows: 119,390

* Columns: 32

* Hotel Types: City Hotel & Resort Hotel

# Key Features:

* Booking status & cancellation

* Lead time & stay duration

* Guest composition

* Market segments & distribution channels

* Average Daily Rate (ADR)

* Special requests & parking needs

# 🛠️ Tools & Technologies

* Python

* Pandas & NumPy

* Matplotlib & Seaborn

* Jupyter Notebook / Google Colab

* Data Cleaning & Feature Engineering

* Statistical & Visual Analysis

# 🔧 Data Cleaning & Feature Engineering

Key transformations performed:

* Handled missing values (country, agent, company, children)

* Converted date fields to datetime

* Optimized categorical columns using category dtype

* Removed unrealistic records (zero stay, invalid lead time)

* Removed ADR outliers using quantile-based filtering

* Created new features:

* * total_guests

* * total_stay

* * total_bookings

* * Boolean conversion for repeated guests

# 📈 Key Insights & Findings

# 🔴 Cancellation Analysis

* Overall Cancellation Rate: 37.48%

* Cancellations increase significantly with longer lead time

* Guests booking far in advance are more likely to cancel

# 💰 Pricing (ADR) Insights

* City Hotels have a higher ADR than Resort Hotels

* * City Hotel ADR: 106.18

* * Resort Hotel ADR: 92.36

* Most bookings fall within the ADR range of 40–150

* Improper pricing outside this range may reduce demand or revenue

# 🌐 Market Segment Behavior

* Online Travel Agents dominate bookings

* Online bookings are more than 2× offline bookings

* Strong opportunity to optimize digital marketing channels

# 👨‍👩‍👧 Guest & Stay Patterns

* Guest composition insights help target:

* * Families

* * Business travelers

* Stay duration patterns help plan:

* * Inventory

* * Staffing

* * Seasonal pricing

# 📊 Visualizations Included

* ADR distribution (Histogram + KDE)

* Booking & cancellation trends

* Market segment analysis

* Lead time vs cancellation

* Hotel type comparisons

* Correlation heatmap

* Pair plots for multivariate relationships

* (20+ business-focused charts)

# 💡 Business Recommendations

# ✔ Reduce Cancellations

* Introduce non-refundable or partial refund options for long lead-time bookings

* Maintain engagement with early bookers via reminders & offers

# ✔ Optimize Pricing

* Dynamic pricing based on lead time and seasonality

* Premium pricing for City Hotels with value-added services

# ✔ Improve Customer Segmentation

* Target repeat guests with loyalty benefits

* Personalize offers by customer and market segment

# ✔ Seasonal & Operational Planning

* Adjust inventory and staffing during peak months

* Use booking trends to forecast demand accurately

# 👤 Author

Tauseef Alam

Aspiring Data Analyst / Data Scientist

Python | SQL | EDA | Data Visualization
