# 📊 Insurance Data Analysis Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing insurance data using **SQL Server** and **Power BI** to generate interactive dashboards and business insights.

It covers:
- Data ingestion & transformation  
- Dashboard development  
- Deployment & automation  
- Security (Row-Level Security)  
- Sentiment analysis on customer feedback  

---

## 🛠️ Tech Stack
- **Database:** Microsoft SQL Server  
- **Visualization:** Power BI Desktop & Power BI Service  
- **ETL:** Power Query  
- **Language:** SQL  

---

## 📂 Dataset
- `InsuranceData.csv`  
- `Insurance Customer Feedback.xlsx`  

---

## 🚀 Project Workflow

### 🔹 1. Data Setup (SQL Server + Power BI Connection)
- Installed and configured MSSQL Server  
- Imported CSV & Excel datasets into SQL Server  
- Connected Power BI Desktop to SQL Server  

<img width="1918" height="975" alt="image" src="https://github.com/user-attachments/assets/3f1679b6-6a6a-495f-8810-ed1048a15d16" />

---

### 🔹 2. Data Cleaning & Profiling
- Performed data profiling in Power BI  
- Handled missing/null values  
- Applied transformations using Power Query  

<img width="1916" height="977" alt="image" src="https://github.com/user-attachments/assets/4b7a248b-19a2-404a-a24e-395551418d34" />

---

### 🔹 3. Dashboard Development (Visuals & UI)
Created an interactive dashboard using:
- KPI Cards (Total Customers, Revenue, Claims)  
- Slicers for filtering  
- Bar Chart & Line Chart (trend analysis)  
- Ribbon Chart (category comparison)  
- Donut Chart (distribution insights)  
- Matrix Visual (detailed view)  
- Multi-row cards for grouped metrics  

<img width="1382" height="757" alt="image" src="https://github.com/user-attachments/assets/91d85bdf-296d-4604-9b63-a1fd20f8d166" />


---

### 🔹 4. Advanced Features
- Implemented Drill-through filters for detailed analysis  
- Enabled interactive navigation across visuals  

<img width="1895" height="1005" alt="image" src="https://github.com/user-attachments/assets/ced6e16e-a959-42b8-98ce-b2038daff3c3" />

---

### 🔹 5. Sentiment Analysis
- Processed customer feedback using Power Query  
- Classified sentiment (Positive / Neutral / Negative)  
- Added sentiment-based visuals
  
Run a python script and filter out redundant data
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/ef2042bf-fd50-4f81-a018-44a13d216303" />

Create sentiment report
<img width="1371" height="772" alt="image" src="https://github.com/user-attachments/assets/f8eeebaf-b266-4557-80bb-536aa52f79f6" />




### 🔹 6. Deployment & Automation
- Published report to Power BI Service  
- Configured Scheduled Refresh  
- Tested and validated refresh cycles  

Publish after creating a workspace
<img width="1918" height="992" alt="image" src="https://github.com/user-attachments/assets/fa7b404e-e233-4a8c-99ac-18e3e42d0e33" />
<img width="1821" height="860" alt="image" src="https://github.com/user-attachments/assets/78022b0f-78ea-4874-b5be-8d0934b86e92" />


Create Scheduled Refresh
(Here this report contains a python script so it cant be scheduled for refresh in power BI services )
<img width="1905" height="972" alt="image" src="https://github.com/user-attachments/assets/837458bb-8839-4dac-a808-b06c530a4df3" />


---

### 🔹 7. Security Implementation (RLS)
- Created roles in Power BI Desktop  
- Applied Row-Level Security (RLS)  
- Assigned users and tested in Power BI Service  

<img width="1918" height="1030" alt="image" src="https://github.com/user-attachments/assets/89234b8f-787f-4224-9331-814341f1e5bf" />

<img width="1916" height="775" alt="image" src="https://github.com/user-attachments/assets/2e5228cc-ccfc-427d-86aa-45d8bda4cec4" />

---

### 🔹 7. Create Dashboard
- Create a Dashboard
<img width="1903" height="970" alt="image" src="https://github.com/user-attachments/assets/71f77efc-0dd1-44d9-a737-2f62bd0a49a6" />




## 📊 Key Insights
- Customer segmentation patterns  
- Claims distribution trends  
- Revenue & premium analysis  
- Customer sentiment insights  

---

## 🔐 Security Features
- Row-Level Security (RLS) implemented  
- Department-level data access control  

---

## 📈 Future Improvements
- Advanced DAX measures  
- Predictive analytics  
- Real-time data integration  

---

## 📎 Project Files
- `InsuranceData.csv`  
- `Insurance Customer Feedback.xlsx`  
- `Proj2.pbix`  

---

## ▶️ How to Run
1. Import dataset into SQL Server  
2. Open `.pbix` file in Power BI Desktop  
3. Refresh data  
4. Publish to Power BI Service  

---
