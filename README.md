# 42-North-Dental--Patient-and-Operational-Data-analysis

## Introduction:
42 North Dental, previously known as Gentle Dental Partners, has a rich history spanning 40+ years in the dental industry. Founded on the principle that doctors produce better outcomes when they spend more time treating patients and less on administrative tasks, this Dental Support Organization (DSO) provides support to dental practices. Their offerings encompass services, resources, and administrative support, with a keen focus on professional development and business growth.

## Objective:
The overarching aim of this project was to analyze patient data for 42 North Dental to derive insights that could help improve their marketing strategies and overall business understanding. Key issues revolved around patient loyalty, appointment consistency, and active patient metrics.

## 1. Problem Overview:
**Appointment Missed and Cancelled (M/C):**
Objective: To ascertain how M/C rates are linked to patient attributes and vary across different offices.

**Patient Loyalty and Active Status:**
Objective: Define metrics for loyalty and active patient statuses and study their varied behaviors.

**Solution Approach:**
Leverage machine learning models and visualization tools (like Tableau) to depict insights.

**End Goal:**
To enable 42 North Dental to attain a deeper understanding of their customer behaviors and detect overarching business patterns.

## 2. Data Processing:

**Data Source:** Data was procured directly from 42 North Dental's internal databases.

**Processing Steps:**
Data importation.
Introduction of new KPIs.
Data merging.
Data filtration.
Missing value treatment.
Data standardization.

<img width="1274" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/45074431-0caf-4649-81fe-41c4a06a9ba7">
<img width="748" alt="Screenshot 2023-10-20 at 3 39 27 PM" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/bc4ed110-2945-4b1d-84ad-d2e7bd595c2b">


## 3. Analysis & Insights:

### a. Missing & Cancel (M/C) Rate Analysis:

Analyzed correlations among patient attributes.
Studied distribution across different offices.
Tracked time trends.

<img width="664" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/9eb30c0a-adca-4c03-b94d-76bbf24b8abc">


**Key Findings:**
Higher M/C rates observed for operations involving an Orthodontist, Director, or Oral Surgeon.
Offices in Newbury, Malden, and Braintree recorded higher M/C rates compared to other locations.
Females displayed a slightly higher M/C rate than males and uni-sex individuals.
The age group of 30-40 showed a notably higher M/C rate.

### b. Patient Loyalty Analysis:

Defined loyal patients as those visiting every 9 months.

<img width="1238" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/7d2c7727-c8c4-41e9-a9bc-d33bd1d8e42f">

Used two formulas for comprehensive analysis:
Proportion of loyal patients in each group.
For every group, calculate the ratio of loyal to disloyal patients.
Employed Random Forest for feature importance determination.
The most important features are appointment length, age, appointment type and specialty (director)

<img width="1250" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/b8837e06-7f68-438a-a82f-55da31d3d008">


**Key Insights:**
Most loyal age groups: 20-30 and 30-40.
Offices with the highest proportion of loyal patients: Newbury, Chelmsford, and Cambridge.
Insurance emerged as the dominant responsible party type.

### c. Active Patient Analysis:

Defined active patients as those visiting more than once within any 18-month period, while lapse patients visit less frequently.
Investigated the influence of various patient features on active patient status.
Mapped distribution across different offices and analyzed visit time distribution.

<img width="649" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/a28d3b7d-1932-41fd-82a5-bf277fe37e01">
<img width="493" alt="image" src="https://github.com/Sarashang1/42-North-Dental--Patient-and-Operational-Data-analysis/assets/115900641/b5dd12a6-b55a-4979-b3a6-03bfe2afb664">

Key Observations:
Active patients predominantly opt for insurance (57.45%) over cash (27.09%).
Age group 20-30 showed the highest activity.
Newbury, Chelmsford, and Cambridge offices had the most active patients.

## Conclusion:
The analysis provided crucial insights into patient behavior, loyalty, and activity patterns. These insights are pivotal for 42 North Dental to tailor their marketing strategies and ensure enhanced patient satisfaction and engagement. The next steps would involve integrating these insights into actionable marketing and operationa
