# **COVID-19 Positivity Analysis in Chile**

## **Project Overview**
This project is part of the **Python for Data Science** course in a master's degree program. The objective was to analyze **COVID-19 positivity rates across different regions in Chile**, focusing on **data processing, visualization, and the implementation of a function to calculate positivity rates** based on publicly available datasets.

## **Objectives**
### **Function**
Develop a function that calculates the **positivity rate by region in Chile** for a specific date provided as an input. The calculation is based on three datasets:
- **Product 3**: Total Cases by Region
- **Product 7**: PCR Tests Conducted
- **Product 87**: Antigen Tests Conducted

The positivity rate is computed using the following formula:

$$
\text{Positivity Rate (%) } = \frac{\text{Positive Tests Conducted on the Day}}{\text{Total Tests Conducted}} \times 100
$$

### **Visualizations**
The following visualizations were created:
- **Total Cases by District**: A comparison of two districts (District 17 and District 18 in the Maule Region).
- **Rate of Contagion**: A comparison of the incidence rates for the two districts.
- **Positivity by Region**: A comparison between the Maule and Coquimbo regions.

**Note:** No publicly available datasets provide test count information at the municipal level for calculating positivity.

### **Data Sources**
The datasets used in this analysis were obtained from the **Ministry of Science's GitHub repository**, specifically:
- **Product 1**: Total Cases by Municipality
- **Product 3**: Total Cases by Region
- **Product 6**: Total Cases by Municipality with Incidence Information
- **Product 7**: PCR Tests Conducted
- **Product 87**: Antigen Tests Conducted

## **Key Findings**
### **Total and Daily New Cases Analysis**
- **District 17 has a higher total number of cases** than District 18, mainly due to its **larger population (762,147 vs. 336,982 inhabitants)**.
- **Daily new cases** initially followed a similar trend in both districts but later **diverged, with District 17 reporting significantly higher daily cases**.

### **Rate of Contagion Analysis**
- **Cumulative incidence** (cases per 100,000 inhabitants) was similar until March 2021 but later **diverged, with District 17 showing a higher incidence rate by mid-2021**.
- **Instantaneous incidence** (three-day average cases per 100,000 inhabitants) was comparable in 2020 but increased significantly in District 17 during **early 2021**, peaking at **over 150 cases per 100,000 inhabitants**.
- A significant **decline in incidence was observed by July-August 2021**, likely influenced by the **vaccination campaign**.

### **Positivity Rate Interpretation**
- **Coquimbo had a higher positivity rate during the first wave (June-August 2020)**, with values exceeding **10% until September**, while **Maule dropped below 10% earlier**.
- In the **second wave (February 2021 onward)**, **Maule recorded higher positivity rates than Coquimbo**, with peaks above **30%**.
- By mid-2021, **positivity rates declined significantly**, and Coquimbo appeared to **control virus transmission more effectively than Maule**.

### **Conclusions and Recommendations**
- **The pandemic affected different regions at different times**, with some regions experiencing higher positivity rates than others.
- **Further analysis is needed to investigate the factors that led to higher positivity in Maule by mid-2021**.
- **District-level analysis within each region** is recommended to identify **high-incidence or high-positivity areas** and inform **targeted health policies**.

## **Usage**
### **Requirements**
To run this project, you need:
- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `datetime`
- Jupyter Notebook or any Python IDE

## **Acknowledgments**
This project is based on open-source datasets provided by the **Ministry of Science of Chile**.  
The analysis and insights were developed as part of an academic research initiative.

