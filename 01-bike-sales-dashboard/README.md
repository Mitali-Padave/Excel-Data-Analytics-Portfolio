# Bike Sales Dashboard

## Project Overview

Interactive Excel dashboard analyzing bike purchase patterns across customer demographics to identify high-value customer segments and optimize marketing strategies for a bicycle retail company.

<br>

## Business Problem

A bicycle retail company needed data-driven insights to answer:

- Which customer segments have the highest purchase rates?
- What demographic factors influence bike purchasing decisions?
- How does commute distance affect purchase likelihood?
- Where should marketing budgets be allocated for maximum ROI?

<br>

## Dataset Information

- **Source**: Kaggle - Bike Sales Dataset
- **Total Records**: 1,000 customer records
- **Key Variables**: 
  - Demographics (Age, Gender, Income, Education)
  - Commute Distance
  - Region
  - Marital Status
  - Purchase Status

<br>

## Tools & Technologies

- **Microsoft Excel** - Data cleaning, analysis, and visualization
- **PivotTables** - Multi-dimensional data analysis
- **PivotCharts** - Interactive visualizations
- **Slicers** - Dynamic filtering and user interactivity

<br>

## Analysis Process

### 1. Data Cleaning & Preparation

- Removed duplicate customer records
- Standardized categorical values (Marital Status: M→Married, S→Single)
- Created age brackets for demographic segmentation (Adolescent, Middle Age, Old)
- Validated data integrity and corrected inconsistencies
- Formatted income fields for proper calculations

### 2. Exploratory Data Analysis

Used PivotTables to analyze:
- Purchase rates across income levels by gender
- Age distribution of bike buyers vs non-buyers
- Commute distance impact on purchase decisions
- Regional and educational segment performance

### 3. Dashboard Development

Built an interactive dashboard featuring:
- **4 Dynamic Slicers**: Marital Status, Region, Education, Purchase Status
- **3 Key Visualizations**: Income analysis, age brackets, commute patterns
- **Clean Design**: Professional layout with consistent color scheme
- **User-Friendly Interface**: Easy filtering for stakeholder exploration

<br>

## 💡 Key Business Insights

### 1. Income & Gender Analysis

- **Male purchasers** average income: **$56,208**
- **Female purchasers** average income: **$55,774**
- Both genders show similar income profiles for bike buyers
- Non-purchasers have a lower average income across both genders (~$53,000)

> **Insight**: Income level is a strong predictor of purchase likelihood

### 2. Age Demographics - Critical Finding

- **Middle Age (31-54)** customers show the **HIGHEST** purchase rate
- Peak purchasing occurs in the middle age bracket for both buyers and the consideration set
- Adolescent and older demographics show significantly lower engagement

> **Insight**: Core target market is professionals aged 31-54

### 3. Commute Distance - Strongest Predictor

| Commute Distance | Purchases | Pattern |
|-----------------|-----------|---------|
| 0-1 Miles | ~200 | **HIGHEST** |
| 1-2 Miles | ~100 | 50% drop |
| 2-5 Miles | ~100 | Maintained |
| 5-10 Miles | ~125 | Slight increase |
| 10+ Miles | ~25 | **LOWEST** (88% drop) |

**Critical Pattern**: Inverse relationship between commute distance and purchase likelihood

> Short commuters (0-1 mile) are **8x more likely** to purchase than long commuters (10+ miles)

### 4. Customer Segmentation Insights

Through slicer analysis:
- **Education**: Higher education levels correlate with increased purchases
- **Region**: North America and Europe show the strongest performance
- **Marital Status**: Both married and single customers show healthy purchase rates

<br>

## 🎯 Strategic Recommendations

### Marketing Strategy

- **Primary Target**: Middle-aged professionals (31-54) with short commutes (0-5 miles)
- **Messaging Focus**: Position bikes as convenient, eco-friendly commute solutions
- **Geographic Priority**: Concentrate campaigns in North America and Europe
- **Income Targeting**: Focus on customers earning $55K+ annually

### Product & Sales Approach

- **Urban Focus**: Prioritize urban markets where short commutes are common
- **Commuter Product Line**: Develop specialized bikes for 0-5 mile daily commutes
- **Corporate Partnerships**: Partner with companies for employee bike programs in urban centers
- **Financing Options**: Offer payment plans to make bikes accessible to middle-income segments

### Budget Allocation

- **High Priority**: Urban areas with a high concentration of short-distance commuters
- **Medium Priority**: Suburban markets with 2-5 mile average commutes
- **Low Priority**: Rural/distant suburban markets with 10+ mile commutes

<br>

## Dashboard Features

✅ **Interactive Filtering** - 4 slicers for dynamic data exploration

✅ **Multi-Dimensional Analysis** - Cross-tabulation of demographics and purchase behavior

✅ **Visual Insights** - Clear charts showing purchase patterns

✅ **Professional Design** - Clean, stakeholder-ready presentation

✅ **Actionable Metrics** - Data translated into business recommendations

<br>

## How to Use

1. Download the Excel dashboard file
2. Enable macros/content if prompted
3. Use the slicers to filter data by:
   - Marital Status
   - Region
   - Education Level
   - Purchase Status
4. Explore interactive charts to gain insights

<br>

## Contact

**Author**: Mitali Padave

[LinkedIn] https://www.linkedin.com/in/mitali-padave-581a2a242/ 

---

⭐ If you found this project helpful, please consider giving it a star!
