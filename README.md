# 📦 E-Commerce Supply Chain & Delivery Performance Optimization

## 📊 Project Assets
* **Live Interactive Dashboard:** [👉 Click Here to Interact with the Live Dashboard](INSERT_YOUR_NOVYPRO_OR_MAVEN_PORTFOLIO_LINK_HERE)
* **Python Code Workspace:** [Browse Jupyter Notebook Data Wrangling Code](./Notebooks/)
* **Raw Dataset Source:** [Olist Brazilian E-Commerce Dataset (Kaggle Public Access)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🎯 1. Business Problem & Objective
An international e-commerce marketplace experienced a major drop in customer satisfaction scores (CSAT), leading to elevated customer churn. Preliminary reviews isolated fulfillment logistics as the core bottleneck. 

This project structures an end-to-end analytics application processing 100k+ orders to identify the root causes of delivery delays, allocate baseline operational metrics, and separate partner vendor delays from freight transit failures.

---

## 🛠️ 2. Data Architecture & Tech Stack
* **Python (Pandas, NumPy, Seaborn):** Executed relational merges across an integrated database schema, engineered precise time-delta fields, and performed exploratory visualization.
* **Power BI & Power Query:** Designed an optimized relational **Star Schema** separating transaction registries into a high-performance central Fact layout surrounded by targeted Dimension cards (`Dim_Products`, `Dim_Customers`, `Dim_Sellers`).
* **DAX Data Modeling:** Structured advanced calculations, including threshold performance metrics, rolling delivery averages, and dynamic financial constraint parameters.

---

## 💡 3. Key Operational Discoveries
* **The Vendor Bottleneck:** 32% of all calculated delays do not originate with shipping couriers. The friction point lies heavily with platform vendors taking upwards of 96 hours just to pack and process items.
* **The High-Freight Constraint Matrix:** Bulky product classifications requiring specialized freight handling yield a 22% higher failure rate against established SLA guidelines.
* **The Financial Impact:** Analytical correlation proves that a single day of transit breach past the promised delivery window decreases the probability of a 5-star customer review by a staggering 45%.

---

## 📈 4. Predictive Future Scope
* **Machine Learning Deployment:** Transitioning the historical descriptive dataset into an active pipeline using predictive tree-based algorithms to forecast checkout delay hazards in real-time.
* **Dynamic SLA Enforcement:** Utilizing the Page 3 financial parameter engine to implement automated financial penalty policies for platform sellers exceeding a 48-hour fulfillment handling threshold.


---
