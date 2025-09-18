# Impact-of-Payment-Methods-on-Cab-Driver-Revenue
# 🚖 Impact of Payment Methods on Cab Driver Revenue  

## 📌 Problem Statement  
Cab drivers often overlook how payment methods influence their earnings. Passenger choices between cash or card may affect both average fare amounts and overall revenue patterns. This project analyzes trip data to uncover whether payment type significantly impacts fare values, providing data-driven insights that can help drivers and platforms optimize revenue strategies.  

---

## 🎯 Objectives  
- To examine the relationship between payment methods (cash, card) and fare amounts using statistical analysis and A/B testing.  
- To determine whether payment type has a significant impact on driver revenue.  
- To provide data-driven recommendations that help cab drivers prioritize the most profitable payment methods.  
- To enable actionable insights for improving driver income strategies and enhancing overall revenue optimization.  

---

## ❓ Research Question  
Does the choice of payment method (cash vs. card) significantly impact fare amounts and driver revenue, and how can these insights be used to optimize earning strategies for cab drivers?  

---

## 📊 Exploratory Data Analysis (Key Insights)  

### 🔹 Plot 1: Boxplot (Fare, Trip Duration, Trip Distance)  
- Fare amount and trip distance show **high variation and outliers**.  
- Long and expensive trips skew the distribution, but most rides fall within a normal range.  
- Outliers may represent genuine long rides or data quality issues.  

---

### 🔹 Plot 2: Distribution of Fare Amount & Trip Distance by Payment Type  
- **Fare Amount:** Card payments dominate higher fare ranges, while cash appears more in smaller fares.  
- **Trip Distance:** Both card and cash are used for long trips, but **card dominates over cash** in longer rides.  
- 👉 Passengers **prefer using card payments more often**, especially for high-value and longer trips.  

---

### 🔹 Plot 3: Pie Chart of Payment Type Preference  
- **Card payments = 63.8%**  
- **Cash payments = 34.2%**  
- 👉 Majority of passengers prefer **card transactions**, reflecting a strong shift toward digital payments.  

---

### 🔹 Plot 4: Stacked Bar (Fare Range vs. Payment Type)  
- Across all fare ranges, **card payments dominate**.  
- In the lowest fare category: **53% card vs. 30% cash**.  
- Even as fares increase, card continues to lead in share.  
- 👉 Passengers **trust and use card payments consistently**, regardless of fare size.  

---

## 🧪 Hypothesis Testing (A/B Test)  

- **Null Hypothesis (H₀):** There is no significant difference in average fare amount between cash and card payments.  
- **Alternative Hypothesis (H₁):** There is a significant difference in average fare amount between cash and card payments.  
- **Result:** p-value ≈ 0.0 (< 0.05) → Reject H₀.  
- ✅ **Conclusion:** Payment type **does impact fare amount**, with card transactions statistically linked to higher fares.  

---

## 💡 Final Business Impact  
- **Card brings higher revenue per trip** → drivers earn more when passengers use cards.  
- **Cash brings ride volume**, but at lower fare amounts.  
- **Passenger preference is shifting to digital** (63.8% card usage).  
- **Revenue Maximization Strategy:** Drivers should encourage card payments to achieve **higher, more consistent earnings across all fare ranges**.  

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **Techniques:** Exploratory Data Analysis (EDA), A/B Testing, Hypothesis Testing  

---

## 📌 Key Takeaway  
👉 While cash payments provide more trips, **card payments dominate in preference, longer distances, and higher fares**.  
For cab drivers, focusing on card transactions is the most effective way to **maximize revenue and ensure income stability**.  

---
