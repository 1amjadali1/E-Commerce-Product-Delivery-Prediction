**E-Commerce Product Delivery Prediction**

**Project Overview:**
This project focuses on predicting whether products from an international e-commerce company will be delivered to customers on time. It also examines key factors that influence delivery performance and analyzes customer behavior. The company primarily deals in electronic products.

---

### **Data Dictionary**

The dataset consists of **10,999 records** and **12 variables**, described below:

| Variable                | Description                                               |
| ----------------------- | --------------------------------------------------------- |
| **ID**                  | Unique customer ID                                        |
| **Warehouse_block**     | Warehouse location (A, B, C, D, E)                        |
| **Mode_of_Shipment**    | Shipment type (Ship, Flight, Road)                        |
| **Customer_care_calls** | Number of customer service calls                          |
| **Customer_rating**     | Rating given by customers (1–Lowest, 5–Highest)           |
| **Cost_of_the_Product** | Product cost in USD                                       |
| **Prior_purchases**     | Total previous purchases                                  |
| **Product_importance**  | Importance level (low, medium, high)                      |
| **Gender**              | Customer gender (Male, Female)                            |
| **Discount_offered**    | Discount applied to the product                           |
| **Weight_in_gms**       | Product weight in grams                                   |
| **Reached.on.Time_Y.N** | Target variable (1 = Late delivery, 0 = On-time delivery) |

---

### **Conclusion**

The project successfully predicted delivery timeliness and provided insights into the factors influencing delivery outcomes and customer behavior.

**Key Findings:**

* **Product Attributes:**

  * Weight and cost significantly affect delivery time.
  * Products weighing **2500–3500 grams** and costing **below $250** were more likely to arrive on time.
  * Most items shipped from **Warehouse F via ship**, indicating its closeness to a seaport.

* **Customer Behavior:**

  * Higher numbers of customer-care calls were associated with delayed deliveries.
  * Customers with **more prior purchases** showed better on-time delivery rates, reflecting higher loyalty.
  * Products with **0–10% discounts** were more prone to late delivery, while those with **more than 10% discount** had improved on-time performance.

* **Model Performance:**

  * **Decision Tree Classifier** achieved the highest accuracy: **69%**.
  * **Random Forest** and **Logistic Regression** followed with **68%** and **67%**, respectively.
  * **K-Nearest Neighbors (KNN)** had the lowest accuracy at **65%**.

---


