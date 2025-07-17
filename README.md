# 📊 Flipkart Smartphone Analysis Dashboard

This project showcases an **interactive Power BI dashboard** analyzing **Flipkart smartphone listings**. The aim is to help identify trends in **sales, ratings, discounts, and brand performance** based on customer interaction data.

---

## 📁 Dataset Overview

The data was collected in **Excel format** and consists of key smartphone attributes, including:

* `Name` – Product title
* `Brand` – Manufacturer brand
* `Ratings` – Average user rating
* `No_of_ratings` – Number of user ratings
* `No_of_reviews` – Number of user reviews
* `Product_features` – Key technical specs
* `MSP` – Market Selling Price
* `MRP` – Maximum Retail Price
* `Discount` – Percentage discount applied

---

## 🧹 Data Preparation in Power BI

Performed using **Power Query**:

* Removed duplicate entries
* Converted rating/review fields to numeric types
* Cleaned pricing (e.g., removed commas)
* Extracted discount metrics
* Parsed and simplified product features

---

## 📐 Key DAX Measures Used

* `Total Sales` = MSP × No\_of\_ratings
* `Average Discount %`
* `Average Ratings`
* `Total No. of Mobiles`
* `Top Brands by Rating / Review / Discount / Sales`
* Brand and mobile-wise slicers

---

## 📊 Power BI Dashboard

The final **dashboard** includes:

* Total KPIs (Sales, Mobiles, Ratings, Brands)
* Top 5 brands and mobiles by:

  * Ratings
  * Reviews
  * Discounts
* Brand market shares (Pie Charts)
* Price and rating distribution
* Interactive **Brand** and **Mobile** filters

### 🔻 Dashboard Preview:

![Flipkart Power BI Dashboard](./Flipkart%20Dashboard.png)

---

## 💡 Key Insights

* **10M+ Total Sales** tracked through user interactions
* **realme**, **Redmi**, and **POCO** dominate customer engagement
* **Redmi** leads in reviews and number of ratings
* **POCO C31** has one of the highest discounts and strong performance
* Higher rated phones often fall in the **₹7,000 – ₹13,000** range

---

## 🚀 How to Run This Project

1. Clone the repo or download the files
2. Open the `.pbix` file in **Power BI Desktop**
3. (Optional) Load Excel data if not embedded
4. Explore using slicers and charts

---

## 📬 Contact

Made by **Aishwarya Burde**
🔗 www.linkedin.com/in/aishwarya-burde | ✉️ aishwaryaburde2000@gmail.com

---

Would you like help packaging this into a ready-to-upload GitHub structure (`README.md`, image file, and folders)?

