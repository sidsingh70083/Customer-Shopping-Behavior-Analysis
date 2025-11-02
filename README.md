# Customer Shopping Behavior Analysis (End-to-End Project)

<img width="2292" height="1276" alt="Screenshot 2025-11-02 162133" src="https://github.com/user-attachments/assets/21c715be-1549-4a09-828d-2cd50dbabf2b" />

---

## 🎯 1. Business Objective

This project analyzes a retail dataset of 3,900 purchases to understand customer shopping behavior and drive strategic decisions. The primary goal is to uncover insights into spending patterns, product preferences, and customer segments to help the business improve sales, customer satisfaction, and loyalty.

## 🛠️ 2. Tools & Methodology

* **Tools:** Python (Pandas), MySQL, Power BI
* **Methodology:**
    1.  **Data Cleaning & Preparation (Python):** Loaded the dataset; handled 37 missing `Review Rating` values by imputing the median rating per category; standardized column names (e.g., to `snake_case`).
    2.  **Feature Engineering (Python):** Created a `age_group` column (Young Adult, Adult, Middle-aged, Senior) for demographic analysis.
    3.  **Database Integration:** Loaded the cleaned DataFrame into a MySQL database for analysis.
    4.  **Data Analysis (SQL):** Answered 10 key business questions using complex SQL queries (e.g., aggregations, segmentation).
    5.  **Dashboarding (Power BI):** Visualized the findings in an interactive dashboard to present KPIs and insights to stakeholders.

## 🔍 3. Key Analyses & Insights (from SQL)

My SQL analysis focused on answering specific business questions:

* **Subscriber Impact:** Non-subscribers (2,847 customers) generate over 2.5x the total revenue ($170,436) of subscribers (1,053 customers, $62,645).
* **Top Revenue Segment:** The "Young Adult" age group is the most valuable demographic, contributing the highest total revenue ($62,143).
* **Customer Loyalty:** The vast majority of the customer base is "Loyal" (3,116 customers), with a very small segment of "New" customers (83).
* **Revenue by Gender:** Male customers generated significantly more revenue ($157,890) than female customers ($75,191).
* **Shipping Preferences:** Customers using "Express" shipping have a slightly higher average purchase amount ($60.48) than those using "Standard" shipping ($58.46).
* **Discount Strategy:** Discounts are highly concentrated on specific products. "Hat" (50.00%) and "Sneakers" (49.66%) have the highest discount rates.
* **Top Products:** The most purchased items by category are:
    * **Accessories:** Jewelry (171 orders)
    * **Clothing:** Blouse & Pants (171 orders each)
    * **Footwear:** Sandals (160 orders)
    * **Outerwear:** Jacket (163 orders)

## 💡 4. Business Recommendations

Based on the analysis, I recommend the following:

1.  **Re-evaluate the Subscription Program:** Since non-subscribers spend more, the business should analyze *why*. The program should be redesigned with exclusive benefits to attract and retain high-value "Loyal" customers who are not currently subscribed.
2.  **Focus Marketing on "Young Adults":** Target marketing campaigns and product assortments towards the "Young Adult" demographic, as they are the highest-revenue segment.
3.  **Optimize Discount Policy:** Review the discount strategy for items like "Hat" and "Sneakers". The business may be sacrificing margins on products that could sell without such deep or frequent discounts.
4.  **Boost New Customer Acquisition:** The low number of "New" customers (83) is a risk. The business should launch campaigns focused on attracting new buyers to build a healthier customer pipeline.

## 🛠️ 5. Skills Demonstrated

* **Technical:** Python (Pandas), SQL (Aggregations, Subqueries, CTEs, CASE statements), Power BI (Dashboarding, DAX measures)
* **Analytical:** Data Cleaning, Feature Engineering, Customer Segmentation, Revenue Analysis, Product Performance Analysis
