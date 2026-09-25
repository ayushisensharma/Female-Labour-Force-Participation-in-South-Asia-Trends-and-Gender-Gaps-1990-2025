# Gender Gaps in Labour Force Participation: A Comparative Analysis of South Asia, 1990–2025

## 📌 Overview

This project examines trends in labour force participation among males and females, with a particular focus on the gender participation gap in India. The analysis is further extended to selected South Asian countries to compare changes in female labour force participation over time.

Using World Bank labour force participation data, the project demonstrates data cleaning, transformation, exploratory analysis, calculation of economic indicators, and visualization using Python.

---

## 🎯 Objectives

The main objectives of this project are to:

- Analyze female labour force participation in India from 1990 to 2025.
- Compare male and female labour force participation rates in India.
- Measure the gender gap in labour force participation.
- Examine changes in female labour force participation across different time periods.
- Compare female labour force participation trends across selected South Asian countries.
- Identify differences in participation patterns between 1990 and 2025.

---

## 📊 Dataset

### Source

**World Bank – World Development Indicators**

### Indicators Used

- Labour force participation rate, female (% of female population ages 15+)
- Labour force participation rate, male (% of male population ages 15+)

### Countries

The South Asian comparison includes:

- 🇮🇳 India
- 🇧🇩 Bangladesh
- 🇳🇵 Nepal
- 🇵🇰 Pakistan
- 🇱🇰 Sri Lanka

### Time Period

**1990–2025**

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Google Colab / Jupyter Notebook**

---

## 🔍 Methodology

### 1. Data Collection

The labour force participation datasets were obtained from the World Bank's World Development Indicators database.

Separate datasets were used for female and male labour force participation rates.

### 2. Data Cleaning

The following data preparation steps were performed:

- Imported the World Bank datasets using Pandas.
- Selected the required countries.
- Selected observations from 1990 to 2025.
- Extracted India-specific observations for the gender-gap analysis.
- Checked for missing values.
- Converted year variables into integer format.
- Converted labour force participation values into numeric format.

### 3. Data Transformation

The original datasets were provided in wide format, with years represented as columns.

The data were converted into long format using Pandas `melt()` to facilitate time-series analysis and visualization.

### 4. Data Integration

The male and female datasets for India were merged using the year variable.

This created a combined dataset containing:

- Female labour force participation
- Male labour force participation
- Gender gap
- Female-to-male participation ratio

---

## 📐 Calculated Indicators

### Gender Gap

The gender gap in labour force participation was calculated as:

Gender Gap = Male LFPR - Female LFPR

A larger value indicates a larger difference between male and female labour force participation rates.


### Female-to-Male Participation Ratio

The female-to-male participation ratio was calculated as:

Female to Male Ratio = Female LFPR / Male LFPR

The ratio was also converted into percentage form for interpretation.

### Annual Change

Annual changes in female labour force participation were calculated using:

Annual change = current year LFPR - previous year LFPR

Percentage changes were also calculated to examine year-to-year movements.

---

## 📊 Analysis & Visualizations
1. Female Labour Force Participation in India: The analysis shows that female labour force participation increased during the 1990s and reached its highest observed level in 2005. It subsequently declined, reaching its lowest level in 2020, before recovering toward the end of the study period.

2. Male vs Female Labour Force Participation : Male labour force participation remained substantially higher than female participation throughout the study period. The comparison highlights the persistent gender difference in labour force participation in India.

3. Gender Gap Over Time: The gender gap declined from approximately 53.75 percentage points in 1990 to 45.20 percentage points in 2025. Although the gap narrowed, a substantial difference between male and female participation remained.

4. Average Female Participation by Period: Average female labour force participation was highest during 2000–2009 and lowest during 2010–2019. The 2020–2025 period shows a recovery compared with the previous decade.

5. Average Gender Gap by Period: The average gender gap decreased from 52.49 percentage points during 1990–1999 to 46.93 percentage points during 2020–2025. This indicates a reduction in the average difference between male and female participation over the study periods.

6. South Asian Comparison: The analysis compares India with Bangladesh, Nepal, Pakistan, and Sri Lanka to examine differences in female labour force participation across South Asia.The countries show different long-term trajectories. Bangladesh and Pakistan recorded substantial increases, while Sri Lanka experienced a decline. India recorded a smaller positive change over the period.

7. 1990 vs 2025 Comparison :The comparison of 1990 and 2025 shows considerable variation across countries. Bangladesh and Pakistan recorded large increases, Nepal also increased, India experienced a smaller increase, while Sri Lanka recorded a decline.
