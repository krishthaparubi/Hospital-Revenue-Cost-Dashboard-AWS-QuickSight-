# 🏥 Hospital Revenue & Cost Dashboard (AWS QuickSight)

## 📘 Overview
This project analyzes hospital performance metrics using a dataset containing multiple years of patient information.  
While the dataset included various years, my primary focus was on comparing **2017 vs. 2018** to uncover year-over-year trends in **revenue**, **profit**, and **cost by category**.  

I performed the initial data cleaning and transformation in **Excel**, stored and processed the data using **AWS**, and built an **interactive dashboard** in **Amazon QuickSight** to visualize financial and operational performance.

---

## 🧹 Data Source & Preparation
- **Dataset:** `Patient-Info.csv`, containing hospital function, cost, revenue, and profit data across multiple years.  
- **Focus Years:** 2017 and 2018 were selected for detailed comparative analysis.  
- **Cleaning & Transformation:**  
  - Removed duplicate records and standardized date formats.  
  - Handled missing or inconsistent categorical values.  
  - Aggregated yearly metrics (revenue, profit, and cost) by hospital category.  
- **Tools Used:** Excel (cleaning), AWS S3/RDS (data storage), and AWS QuickSight (visualization).

---

## 📊 Key Insights

### **1️⃣ Revenue & Profit Trends**
- **Revenue increased by 8.26%** — from **$4.29M (2017)** to **$4.65M (2018)**.  
- **Profit decreased by 7.64%** — from **$382K** to **$353K**, suggesting higher operational costs despite revenue growth.

### **2️⃣ Top Cost Drivers**
The five highest-cost categories in 2018 were:
1. **Surgical — $15,223**  
2. **Medical — $13,240**  
3. **Critical Care — $7,934**  
4. **Step Down — $5,690**  
5. **Psychology — $2,880**

### **3️⃣ Category-Level Insights**
- **Critical Care** costs more than doubled (**$36.5K → $78K**, +113%), showing rapid service expansion.  
- **Psychology** grew by **244%**, reflecting investment in mental health resources.  
- **Surgical** costs decreased by **~29%**, possibly due to improved efficiency.  
- **Labor & Delivery** had a sharp revenue drop, showing potential inefficiencies or data anomalies in 2018.

### **4️⃣ Summary**
- Revenue growth in 2018 did not translate into higher profits — indicating **margin pressure** and **cost control challenges**.  
- Categories like **Critical Care** and **Psychology** highlight **shifting hospital priorities** toward complex and behavioral care.  
- The analysis provides actionable insight into **operational efficiency** and **financial strategy** across departments.

---

## ☁️ AWS QuickSight Dashboard

The **interactive dashboard** was built and hosted on **AWS QuickSight**, allowing users to filter by hospital type, region, and category to explore metrics dynamically.  
🖥️ *Please note:* The **PDF version** included in this repository is a **static export** — it does not include the interactive functionality available in the AWS-hosted version.

### 🔗 **How to View the Live Dashboard**
This dashboard is hosted on **AWS QuickSight** and requires access approval.

📧 **To request access:**  
Email me at **[krishthapaunt@gmail.com](mailto:krishthapaunt@gmail.com)** and I’ll send you an invitation.

Once approved, you can access the live version here:  
👉 [**Click to View on AWS QuickSight**](https://us-east-1.quicksight.aws.amazon.com/sn/accounts/149465616674/dashboards/09546335-6509-463a-b0dc-cdf1224ace18?directory_alias=krishthapaAWS)

If you don’t have access, you can still explore the static version:  
📄 **[Download PDF Dashboard Report](./Dashboard_Report.pdf)**

---

## 🛠️ Tools & Technologies
- **Excel** — Data cleaning and transformation  
- **AWS S3 / RDS** — Cloud data storage  
- **AWS QuickSight** — Interactive data visualization  
- **GitHub** — Version control and project documentation  

---

## 📈 Skills Demonstrated
- Data cleaning & transformation  
- Exploratory data analysis (EDA)  
- Cloud analytics using AWS  
- KPI tracking and visualization  
- Financial and operational reporting  
- Data storytelling for business impact  

---

## 📂 Repository Contents
