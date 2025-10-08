# **🏥 Patients Wait List Analytics**

## **📖 Project Overview**
**Patients Wait List Analytics** is an interactive Power BI project designed to analyze and visualize historical data of hospital patients waitlist.  
The project aims to uncover patterns, bottlenecks, and key performance indicators (KPIs) that affect patient waiting times — empowering healthcare organizations to enhance efficiency, resource allocation, and service delivery.

---

## **🎯 Project Objectives**

- 📊 **Visualize** patient waiting lists across multiple years to identify trends and fluctuations.  
- 🏥 **Evaluate** different case types and specialty-level performance in managing waiting times for hospital patients.  
- ⏱️ **Analyze** average waiting duration and its variation across different demographics and specialties.  
- 🧠 **Identify** potential areas of improvement in healthcare management using data-driven insights.  
- 📈 **Support** decision-making by presenting a clear, interactive dashboard summarizing key indicators.

---

## **🗂️ Dataset Information**

**Source:** This is a publicly available historical dataset (from 2018–2021) obtained from [Kaggle: Hospital Waiting List Management Dataset](https://www.kaggle.com/datasets/michaelbeanie/hospital-waiting-list-management-dataset)  

**Size:** 
- **Records:** 453,119
- **Fields:** 8  

### **Feilds Details:**

| **Field Name** | **Description** |
|-----------------|-----------------|
| **Archive_Date** | Date when data is archived and aggregated at the end of each month |
| **Specialty_HIPE** | Specialty Hospital In-Patient Enquiry — the unique identifiers representing medical specialties using the HIPE coding system |
| **Specialty_Name** | Name of the medical treatment specialty (e.g., Cardiology, Orthopedics, Neurology) |
| **Case_Type** | Type of patient case, such as *Inpatient*, *Day Case*, or *Outpatient* |
| **Adult_Child** | Specifies whether the patient is an *Adult* or *Child* |
| **Age_Profile** | Categorized age groups of patients (e.g., 0–15, 16–45, 46–65, 65+) |
| **Time_Band** | Waiting time interval of patients (e.g., 3–6 months, 12–15 months, 18–24 months) |
| **Total_Patients** | Total number of patients recorded for each category at the archive date |

### **Key Terms:**  
- **Inpatient:** Patients admitted in hospital for medical treatment for more than 1 day  
- **Day Case:** Patients admitted in hospital and descharged on same day after being treated  
- **Outpatient:** Patients who receive medical treatment without being admitted in the hospital  

---

## **📊 Dashboards Summary**

### 📈 **Page 1 – Patients Analytics**
![Patients Analytics Page](images/Patients_Analytics_Page.png)

**Summary:**  
Offers a high-level overview dashboard of patients waitlist trends from 2018 to 2021. It provides an interactive analysis of patient volumes, waiting durations, and specialty comparisons.

**Key Highlights:**
- **KPI Card:** Shows current year's total patients comparison with previous year's.
- **Metrics:** Average and median patients metric card. 
- **Line Chart:** Displays monthly trends of total patients by different case types and also shows medical specialty breakdown in the Tooltip.  
- **Bar Chart:** Compares patient volumes across *Time Bands* and *Age Profiles*.   
- **Donut Chart:** Breaks down waiting time distribution by *Case Types*.  
- **Slicers:** Allow filtering by dates, specialties, and case type for dynamic exploration.  

🔍 *Purpose:* Enables healthcare managers to understand the overall load, track yearly and monthly progress, and assess changes in waiting patterns across patient categories.

---

### 🔬 **Page 2 – Granular Analysis**
![Granular Analysis Page](images/Granular_Analysis_Page.png)

**Summary:**  
Provides an in-depth view of specialty and demographic-level insights. It allows users to drill down into specific departments or patient groups to evaluate performance variations in detail.

**Key Highlights:**
- **Specialty-Level Analysis:** Identifies which medical specialties have the longest waiting times or highest patient volumes.  
- **Age Split:** Examines waiting time differences among various age groups.    
- **Trend Visuals:** Track month-on-month patient counts and waiting times for each specialty.  
- **Interactive Filters:** Allow users to analyze data by specific years, patients type, or treatment categories.  

🔍 *Purpose:* Helps pinpoint high-pressure specialties, understand demographic imbalances, and support targeted policy or operational improvements.

---

## **💡 Key Insights & Takeaways**

- 📆 **Monthly Trends:** A consistent rise in outpatient cases from 2018–2021, highlighting growing healthcare demand for outpatient cases.
- 🏨 **Case Type Split:** Outpatient cases cover approx 72% of total patients wait list, showing the significant proportion of outpatient treatment in healthcare.
- 👥 **Demographic Variation:** Age group of 16-64 years experienced most prolonged waiting times of 18+ months for treatments.  
- ⏳ **Top Specialty:** *Paediatric Dermatology* dominated as top specialty with highest average patients, while *Accident & Emergency* dominated with highest median patients. Patients under these medical specialties experienced prolonged wait durations due to high volumes.  
- 🚀 **Actionable Insight:** Prioritizing resource reallocation to high-demand specialties (Paediatric Dermatology & Paediatric ENT) and case types (Outpatients) can substantially reduce overall waiting times.

---

## **👩‍💻 Author Information**

**👤 Name:** Syeda Hadiqah Fatima    
**📧 Email:** hadiqah.fatima02@gmail.com  
**🔗 LinkedIn:** [linkedin.com/in/s-hadiqah-f](https://www.linkedin.com/in/s-hadiqah-f)  
**📍 Location:** Karachi, Pakistan  

---

⭐ **If this project helped you, please give it a star!** ⭐  
> 💬 *"Turning data into decisions!"*
