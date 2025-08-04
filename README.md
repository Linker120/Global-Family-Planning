# 🌐 Global Family Planning Dashboard: Patterns, Insights & Clustering

---

## 👩‍💼 Author Profile

- **Name**: Akimana Janviere  
- **Student ID**: 26769  
- **Supervisor**: Mr. Maniraguha Eric  
- **Project Title**: _Global Family Planning Progress & Patterns_

---

## 📝 Executive Summary

This project investigates global satisfaction levels with modern family planning methods across countries from 1989 to 2019. By combining data wrangling, statistical exploration, and K-Means clustering, the study uncovers patterns in adoption, satisfaction, and demographic distribution. Rwanda serves as a key focus, highlighting its progress within global trends.

The analysis is conducted using **Python** for data cleaning, clustering, and visualization, and **Power BI** for designing an interactive dashboard.

---

## 🎯 Objectives

- Understand how satisfaction with modern family planning varies globally
- Examine Rwanda’s historical trends (1989–2019)
- Apply K-Means clustering to discover behavioral groupings among countries
- Present findings using an interactive dashboard for stakeholder communication

---

## 📦 Dataset Overview

**Main File**:[RELAY_WHS (5).csv](https://github.com/user-attachments/files/21575651/RELAY_WHS.5.csv)

| Column Name         | Description                                          |
|---------------------|------------------------------------------------------|
| `IND_ID`            | Indicator ID (Family planning)                      |
| `DIM_TIME`          | Year of record (e.g., 2004, 2015)                    |
| `GEO_NAME_SHORT`    | Name of country or region                           |
| `DIM_SEX`           | Gender (e.g., FEMALE)                               |
| `DIM_AGE`           | Age group category (e.g., Y15T49)                   |
| `RATE_PER_100_N`    | % of population satisfied with modern methods       |

---

## 🔬 Python Analytics Workflow

### 1️⃣ Data Loading & Validation
- Loaded data using Pandas
- Ensured completeness (0% missing values)
- Filtered Rwanda data for analysis between 1989–2019

📸 **Screenshoot**: 
![a1](https://github.com/user-attachments/assets/20063ed6-0f88-4696-a1a3-e2ec00e9a848)

![a2](https://github.com/user-attachments/assets/0109e351-e493-48d5-b6f4-6b7c70a5348a)

![a3](https://github.com/user-attachments/assets/2daea691-e47d-45cd-b0fe-f0bc730e1d8a)


### 2️⃣ Exploratory Data Analysis (EDA)
- Line chart to track Rwanda’s satisfaction trend
- Boxplot comparing rate distributions within clusters
- Cluster-wise breakdown by sex and country

📸 **Screenshoots**: 
![a4](https://github.com/user-attachments/assets/86886a2b-7f83-40ed-a26b-68d74a214d3f)

![b1](https://github.com/user-attachments/assets/937e2d60-7acd-493c-8408-5142ba961af7)

![b2](https://github.com/user-attachments/assets/9594ebb1-688d-457d-9034-a60fc5c702f9)

![b3](https://github.com/user-attachments/assets/c93d56df-5d0e-4fdb-8673-192530938736)

![b4](https://github.com/user-attachments/assets/46e5af8e-a80e-44ba-8ff6-646c6d956cb0)

![b4](https://github.com/user-attachments/assets/1d8d0154-efae-48e9-808a-5c6319e85ced)



### 3️⃣ K-Means Clustering
- Scaled numerical columns for fair distance-based grouping
- Optimal clusters discovered using silhouette scores
- Cluster characteristics explored through top contributors

  ![sktlearn](https://github.com/user-attachments/assets/68eac083-66e0-4576-ad16-4a414b2f0a32)

  ![kmeans](https://github.com/user-attachments/assets/7b2f011b-fc56-4205-8070-e9617a27d3ad)

  ![visualization](https://github.com/user-attachments/assets/95b01893-db26-4bfb-92ca-77a6fdba4ffa)



### 4️⃣ Data Export
- Final dataset saved as `cleaned_familyplanning.csv`
- Used for Power BI dashboard creation

---

## 📊 Power BI Dashboard Summary

### 📌 Key Features:
- Time Slicer to interactively explore historical trends
- Country-based geography filter
- Donut chart visualizing record share by country
- Bar charts for cluster-based metrics
- Historical line chart for Rwanda satisfaction

📸 **Dashboard Screenshot Placeholder**: 

![Dashboard](https://github.com/user-attachments/assets/56d7d340-4b5a-4f7f-8831-9dcb9197aee6)


---
POWER BI DOWNLOADABLE FILE:https://drive.google.com/file/d/1LxbXCZSLnEmXpdfkyzJWI6p_8rwBCujF/view?usp=sharing


POWERPOINT FILE: https://docs.google.com/presentation/d/1n01_FMf4c_0gDnu4_d4-F7qnIk1jGvQX/edit?usp=sharing&ouid=116861627677071882792&rtpof=true&sd=true

> 🔗 GitHub Repository: https://github.com/Linker120/Global-Family-Planning
>
> Thank you for your support throughout the course.  
>
> Kind regards,  
> **Akimana Janviere**  
> Student ID: 26769

---

## ✅ Final Deliverables & Outcomes

- ✔ Cleaned, validated dataset ready for analysis
- ✔ EDA and clustering insights using modular Python code
- ✔ Interactive Power BI dashboard for stakeholders
- ✔ Presentation summarizing methodology and findings

