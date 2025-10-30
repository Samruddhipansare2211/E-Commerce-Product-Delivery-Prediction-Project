# 📦 E-Commerce Product Delivery Prediction

![E-Commerce Delivery](https://globalskylogistics.com/wp-content/uploads/2018/04/THE-CHANGING-NATURE-OF-E-COMMERCE-DELIVERY.jpg)

## 📘 Overview
The **E-Commerce Product Delivery Prediction** project aims to predict whether products from an international e-commerce company will reach customers **on time** or **be delayed**.  
In addition to delivery prediction, the project analyzes key factors influencing delivery performance and studies **customer behavior patterns**.  
The company primarily deals in **electronic products** and operates multiple warehouses using various shipment modes.

---

## 📊 Dataset Description
The dataset contains **10,999 observations** and **12 variables** related to shipment details, product attributes, and customer interactions.

| Variable | Description |
|-----------|-------------|
| **ID** | Unique ID of each customer |
| **Warehouse_block** | The warehouse block from where the product is dispatched (A, B, C, D, E) |
| **Mode_of_Shipment** | Shipment method used (Ship, Flight, Road) |
| **Customer_care_calls** | Number of calls made to customer care regarding the shipment |
| **Customer_rating** | Customer satisfaction rating (1 = Lowest, 5 = Highest) |
| **Cost_of_the_Product** | Product cost in USD |
| **Prior_purchases** | Number of previous purchases by the customer |
| **Product_importance** | Importance level of the product (Low, Medium, High) |
| **Gender** | Gender of the customer (Male, Female) |
| **Discount_offered** | Discount percentage on the product |
| **Weight_in_gms** | Weight of the product (in grams) |
| **Reached.on.Time_Y.N** | Target variable → 1: Late Delivery, 0: On-Time Delivery |

---

## 🧠 Project Objectives
- Predict whether a product will be delivered on time or not.  
- Analyze major factors influencing delayed deliveries.  
- Study customer behavior and satisfaction trends.  
- Identify relationships between product attributes, warehouse logistics, and delivery outcomes.

---

## 🔍 Exploratory Data Analysis (EDA) Insights
- **Product Weight & Cost:** Products weighing **2500–3500 g** and costing **under $250** are more likely to be delivered on time.  
- **Warehouse F & Shipment Mode:** Most deliveries originate from **Warehouse F**, usually via **ship**, suggesting a coastal location advantage.  
- **Customer Behavior:**
  - More customer care calls → higher probability of **late deliveries**.  
  - Loyal customers (with more prior purchases) have a **higher on-time delivery rate**.  
- **Discount Impact:** Deliveries with **>10% discount** tend to be **on time**, whereas **0–10% discounts** correlate with delays.

---

## 🤖 Machine Learning Models Used
| Model | Accuracy |
|--------|-----------|
| **Decision Tree Classifier** | 69% |
| **Random Forest Classifier** | 68% |
| **Logistic Regression** | 67% |
| **K-Nearest Neighbors (KNN)** | 65% |

The **Decision Tree** model achieved the best performance with an accuracy of **69%**, making it the most effective for predicting product delivery timeliness in this dataset.

---

## 🧩 Technologies Used
- **Programming Language:** Python 3.10+  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook  

---

## ⚙️ How to Run the Project

Clone the repository:
```bash
git clone https://github.com/yourusername/ecommerce-delivery-prediction.git
```

Navigate to the project folder:
```bash
cd ecommerce-delivery-prediction
```

Install required dependencies:
```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:
```bash
jupyter notebook Ecommerce_Delivery_Prediction.ipynb
```

---

## 📈 Conclusion
- **Goal:** Predict delivery timeliness and analyze influencing factors.  
- **Best Model:** Decision Tree Classifier (69% Accuracy).  
- **Key Findings:** Product weight, cost, discount percentage, and customer interactions strongly affect delivery time.  
- **Insight:** Improving logistics for **mid-weight, low-cost items** and optimizing shipment routes can enhance on-time delivery rates.

---

## 🔮 Future Scope
- Incorporate **real-time tracking data** for improved accuracy.  
- Implement **XGBoost or Deep Learning models** to enhance predictive performance.  
- Develop **Power BI / Tableau dashboards** for interactive analytics and visualization.  

---

## 👩‍💻 Author

**Samruddhi Pansare**  
[LinkedIn](https://www.linkedin.com/in/samruddhi-pansare-b34371328) • [GitHub](https://github.com/Samruddhipansare2211)  
📧 **Email:** [pansaresamruddhi11@gmail.com](mailto:pansaresamruddhi11@gmail.com)
