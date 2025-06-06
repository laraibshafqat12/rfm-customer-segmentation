
# Customer Segmentation using RFM Analysis (2024)

This project performs customer segmentation using **RFM Analysis** (Recency, Frequency, Monetary) on a real-world **E-Commerce Dataset (2024)** from Kaggle.

---

##  Dataset Overview

- Source: [Kaggle - E-Commerce Sales Data 2024](https://www.kaggle.com/datasets/datascientist97/e-commerece-sales-data-2024)
- Files used:

  - `E-commerce sales data.csv`
 

---

##  RFM Segmentation Logic

- **Recency (R):** How recently a customer purchased
- **Frequency (F):** How often they purchased
- **Monetary (M):** How much they spent

---

##  Key Findings

| Segment               | Description                                  | Count |
|-----------------------|----------------------------------------------|--------|
| **Champions**          | Recent, frequent, and big spenders           | 229    |
| **Potential Loyalists**| Recent and frequent buyers                   | 210    |
| **Loyal Customers**    | Frequent buyers (not always recent)          | 188    |
| **At Risk**            | Previously loyal, now inactive               | 124    |
| **Needs Attention**    | Low-value or disengaged customers            | 104    |

---

##  Files in this Repo

- `RFM_Customer_Segmentation.ipynb` – Full Python code
- ` Segmentation Using RFM Analysis in Python .pdf` – Visual summary of findings
- `README.md` – Project description

---

##  How It's Different from Basic Analysis

This project goes **beyond simple demographics** (like gender, city, or spend amount) by performing **behavioral segmentation** using RFM, which gives actionable insights into customer loyalty and re-engagement strategies.

---

##  Tools Used

- Python (Pandas, Matplotlib)
- Google Collab
- Kaggle E-commerce Dataset (2024)
