# 🏥 Hospital Emergency Room (ER) Performance Analysis - Power BI & Excel  

## 📌 Overview  
This **Power BI-based data analysis project** examines **hospital emergency room (ER) performance** from **April 1, 2019, to October 30, 2020**. The project provides key insights into:  

✅ **Total patient visits and trends over time**  
✅ **Average waiting times and satisfaction scores**  
✅ **Demographics of patients by age, race, and department**  
✅ **Department-wise performance analysis**  
✅ **Factors influencing patient satisfaction**  

Using **Power BI for visualization and Excel for data processing**, this project helps **hospital administrators optimize ER efficiency, improve patient satisfaction, and reduce wait times**.  

---

## 📂 Dataset Details  
This project uses **three main files**:  

1. **Hospital ER.csv**  
   - Contains **patient visit data** from 2019-2020.  
   - **Key columns:** `Patient ID`, `Department`, `Waiting Time`, `Satisfaction Score`, `Gender`, `Race`, `Admin Flag`, `Visit Date`  

2. **Hospital ER Project.pbix**  
   - **Power BI dashboard** for data visualization.  

3. **Hospital ER Project.pdf**  
   - **Summary report** of the dashboard insights.  

---

## 🏗️ Data Cleaning Process  

✅ **Missing Data Handling:**  
- Verified that patient records **did not have missing department or waiting time values**.  
- Replaced **null satisfaction scores** with the **department's median value**.  

✅ **Standardization:**  
- Converted **waiting times** to uniform units (minutes).  
- Categorized **age groups** into `Infancy`, `Early Childhood`, `Middle Childhood`, `Teenager`, and `Adult`.  

✅ **Data Validation:**  
- Ensured that all **patient records fell within the valid time range** (April 2019 - October 2020).  

---

## 📊 Key Insights & Trends  

### 1️⃣ **Total ER Visits (April 2019 - October 2020)**  
✅ **Total Patients:** **9,216**  
✅ **Year-to-Date Patients (YTD):** **4,878**  
✅ **Last Year YTD:** **3,385**  
✅ **Increase in Patients:** **+44%**  

📊 **Findings:**  
- **ER visits increased significantly over time**, indicating **higher demand for emergency care**.  
- **Possible reasons for patient increase:** seasonal illnesses, population growth, or hospital reputation.  

---

### 2️⃣ **Average Waiting Time & Satisfaction Score Trends**  
✅ **Overall Average Waiting Time:** **35.26 minutes**  
✅ **Year-to-Date Waiting Time:** **35.47 minutes**  
✅ **Change in Waiting Time:** **+1% from last year**  

✅ **Overall Satisfaction Score:** **5.47 (out of 10)**  
✅ **Year-to-Date Satisfaction Score:** **5.50**  
✅ **Change in Satisfaction Score:** **+1% from last year**  

📊 **Findings:**  
- **Longer waiting times slightly decrease patient satisfaction**.  
- **Efficient departments had better satisfaction ratings**.  
- **Peak waiting hours contributed to lower satisfaction scores**.  

---

### 3️⃣ **Department-wise Patient Volume & Satisfaction**  
✅ **Most Visited Departments:**  
1️⃣ **General Practice**  
2️⃣ **Orthopedics**  
3️⃣ **Physiotherapy**  
4️⃣ **Cardiology**  
5️⃣ **Neurology**  

✅ **Highest Satisfaction Scores by Department:**  
- **Physiotherapy (Avg. 6.02)**  
- **Gastroenterology (Avg. 5.7)**  
- **Cardiology (Avg. 5.6)**  

✅ **Departments with the Longest Waiting Times:**  
- **Neurology (~37 mins)**
- **Cardiology (~36 mins)**
- **General Practice (~35 mins)**  

📊 **Findings:**  
- **Physiotherapy had the highest patient satisfaction, possibly due to longer session-based treatments**.  
- **Departments with specialized care had longer waiting times, impacting satisfaction**.  

---

### 4️⃣ **Demographics: Patients by Age, Race, and Admin Flag**  
✅ **50% of Patients were flagged as "Admin" cases.**  
✅ **Most ER visits were from Adults, followed by Teenagers.**  
✅ **Race Distribution:**  
- **Majority:** White (largest proportion of ER patients).  
- **Other groups:** African American, Asian, Two or More Races.  

📊 **Findings:**  
- **Teenagers & Adults dominated ER visits** due to injuries and common illnesses.  
- **Understanding racial diversity helps improve hospital inclusivity & outreach programs**.  

---

### 5️⃣ **Satisfaction Scores by Hour & Weekday**  
✅ **Peak Satisfaction Hours:** **Early mornings (6 AM - 8 AM)**  
✅ **Lowest Satisfaction Hours:** **Late nights (10 PM - 2 AM)**  

📊 **Findings:**  
- **Late-night shifts had lower satisfaction scores, possibly due to staff shortages**.  
- **Weekends saw increased patient dissatisfaction**, likely from higher ER congestion.  

📈 **Heatmap Analysis:**  

| Hour | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday | Sunday |  
|------|--------|---------|-----------|----------|--------|----------|--------|  
| 6 AM | 6.22   | 5.40    | 5.67      | 6.10     | 6.00   | 5.90     | 6.00   |  
| 12 PM | 7.17  | 5.67    | 6.36      | 6.00     | 3.85   | 6.86     | 6.50   |  
| 11 PM | 5.14  | 5.80    | 7.13      | 5.67     | 4.29   | 5.46     | 5.10   |  

📊 **Key Observations:**  
- **Patients visiting before noon had better experiences than those visiting at night**.  
- **Tuesdays and Fridays had lower satisfaction scores overall**.  

---

## 🔍 **Key Recommendations**  

📌 **Reduce Waiting Times**  
🔹 Increase **staff availability during peak hours** to optimize efficiency.  
🔹 **Improve scheduling strategies** to distribute patient flow evenly.  

📌 **Enhance Patient Satisfaction**  
🔹 **Improve late-night ER services** by adding more staff and expediting triage.  
🔹 **Enhance Physiotherapy & General Practice departments**, as they show high patient demand.  

📌 **Optimize Department Operations**  
🔹 **Reduce wait times in Neurology & Cardiology** through better triaging and appointment management.  
🔹 **Expand outreach programs for minority communities** to ensure **equal access to ER services**.  

---

## 📊 Power BI Dashboard Features  
The **interactive Power BI dashboard** provides:  
✅ **Total ER Visits & Trends** (Yearly & Monthly Analysis)  
✅ **Waiting Time & Satisfaction Score Correlation**  
✅ **Demographics Breakdown (Age, Race, Gender)**  
✅ **Department-wise Performance Metrics**  
✅ **Peak Hours & Weekday Analysis for Satisfaction Scores**  

📌 **Download the Power BI File:** [Hospital ER Project.pbix](https://github.com/Eden1029/PowerBI_HospitalERProject/blob/main/Hospital%20ER%20Project.pbix)  
📌 **View the Dashboard Report:** [Hospital ER Project.pdf](https://github.com/Eden1029/PowerBI_HospitalERProject/blob/main/Hospital%20ER%20Project.pdf)  

---

## 🚀 Future Improvements  
🔹 **Predict patient arrival times using AI-based forecasting models**.  
🔹 **Enhance real-time ER tracking to monitor patient inflow & congestion**.  
🔹 **Implement a mobile app for estimated waiting times & satisfaction feedback**.  

---

## 🤝 Connect with Me  
📧 **Email:** eden.vietnguyen@gmail.com  
🔗 **LinkedIn:** [www.linkedin.com/in/eden-nguyen](https://www.linkedin.com/in/eden-nguyen)  
🌐 **Portfolio Website:** [eden-nguyen.vercel.app](https://eden-nguyen.vercel.app/)  
