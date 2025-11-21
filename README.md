# 📱 Phone Sales Analytics

This project explores a **dataset of mobile phone sales**, analyzing pricing, specifications, and sales performance.
Using Python and popular data science libraries, it uncovers correlations between phone features, pricing, and market demand.

---

## 🚀 Project Overview

The goal of this analysis is to:

* Clean and prepare phone sales data.
* Explore correlations between:

  * Price and features (RAM, storage, camera, CPU, battery)
  * Price and units sold
* Visualize trends in specifications, pricing, and sales performance.
* Identify high-performing and budget-friendly phones.

---

## 📂 Dataset Description

The dataset includes **161 unique mobile phones** with the following features:

| Column       | Description                    |
| ------------ | ------------------------------ |
| Product_id   | Unique identifier of the phone |
| Price        | Retail price in USD            |
| Sale         | Units sold                     |
| weight       | Weight of the phone (grams)    |
| resoloution  | Screen resolution (inches)     |
| ppi          | Pixel density                  |
| cpu core     | Number of CPU cores            |
| cpu freq     | CPU frequency (GHz)            |
| internal mem | Internal storage (GB)          |
| ram          | RAM size (GB)                  |
| RearCam      | Rear camera resolution (MP)    |
| Front_Cam    | Front camera resolution (MP)   |
| battery      | Battery capacity (mAh)         |
| thickness    | Phone thickness (mm)           |

---

## 🧹 Data Cleaning Steps

* Checked and removed duplicates.
* Verified no missing values exist.
* Ensured data types are correct.
* Identified highest and lowest-priced phones.

---

## 📊 Visualizations & Insights

### ✔ Price Distribution & Feature Correlation

* Heatmap showing correlations of all features with price.
* Pair plots for feature relationships.

### ✔ Price vs Features

* Scatter plots for each feature vs price (RAM, internal memory, CPU, cameras, battery, weight, thickness).

### ✔ Key Observations

* RAM, PPI, and internal memory have the highest positive correlation with price.
* Thickness negatively correlates with price.
* Some high-priced phones sell fewer units, while mid-range phones often have higher sales.
* Camera resolution, battery, and CPU cores significantly influence pricing.

---

## 🛠 Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## 📁 Project Structure

```
📦 phone-sales-analytics
│
├── Cellphone.csv
├── phone_sales_analysis.ipynb
├── README.md   ← (You are here)
```

---

## 📈 Key Findings

* RAM, PPI, and internal storage are the strongest price drivers.
* Phones with extreme prices (very low or very high) behave differently in terms of units sold.
* CPU frequency, camera specs, and battery capacity play a role in pricing.
* Mid-range phones may be the sweet spot for sales.

---

## 📬 Contact

For questions or suggestions on data analysis or expanding this project, feel free to reach out.

---
