# Hotel Booking Demand, Customer Behaviour and Cancellation Analysis

### Exploratory Data Analysis (EDA) Project

**Project Domain:** Data Analytics  
**Training Programme:** Data Science Training & Internship  
**Organization:** BLEEP Education  
**Dataset:** Hotel Booking Demand Dataset – Kaggle
## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the **Hotel Booking Demand Dataset** using Python. It analyses hotel booking patterns, customer behaviour, cancellation trends, seasonal demand and Average Daily Rate (ADR).

The analysis focuses on two hotel categories:
- City Hotel
- Resort Hotel

The objective is to identify meaningful patterns in booking behaviour and understand how different factors are associated with cancellations and room pricing.

## Dataset Information

- **Dataset:** Hotel Booking Demand
- **Total Records:** 119,390
- **Original Features:** 32
- **Hotel Categories:** City Hotel and Resort Hotel

The dataset contains information about booking status, arrival dates, guest details, stay duration, market segments, distribution channels, room types, deposit types and ADR.

**Dataset source:** [Hotel Booking Demand Dataset – Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

## Objectives

- Understand the structure and characteristics of hotel booking data.
- Identify missing values, duplicate records and unusual observations.
- Analyse booking and customer characteristics.
- Compare City Hotel and Resort Hotel.
- Investigate cancellation patterns and associated factors.
- Examine booking demand and seasonal variations.
- Analyse ADR across different booking categories.
- Derive insights to support hotel reservation and pricing decisions.

## Tools and Technologies

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib and Seaborn** – Data visualisation in the analysis notebook
- **Jupyter Notebook** – Development environment

## Project Workflow

The project is divided into six major sections:

### 1. Data Loading, Inspection and Preprocessing
- Dataset loading and structural inspection
- Data types and variable classification
- Missing-value analysis
- Duplicate record identification
- Data validation and feature creation

### 2. Univariate Analysis – Booking and Customer Characteristics
- Lead-time and ADR analysis
- Guest composition and stay duration
- Meal and customer preferences
- Market segments and distribution channels
- Deposit types and special requests

### 3. Hotel-wise Comparative Analysis
- Booking volume comparison
- Cancellation rates by hotel type
- ADR and lead-time comparison
- Stay duration and guest composition
- Customer preferences and room allocation

### 4. Cancellation Analysis
- Overall cancellation rate
- Cancellation patterns by hotel type
- Lead-time-based cancellation analysis
- Market segment and distribution channel analysis
- Deposit type and customer type analysis
- Repeat guests and previous cancellation history
- Room allocation and country-wise cancellation patterns

### 5. Time-Series Analysis and Seasonality
- Monthly booking demand
- Monthly cancellation rates
- ADR variations across months
- Weekday and weekend stay patterns
- Arrival day and week analysis
- Year-month booking trends
- Seasonal lead-time analysis

### 6. Revenue Management and ADR Analysis
- ADR comparison by hotel type
- ADR across months and customer categories
- ADR and lead-time relationship
- Market segment and distribution channel pricing
- Room-type ADR analysis
- ADR and length-of-stay relationship
- Estimated lodging value analysis
- ADR data-quality assessment

## Key Findings

Some important findings from the analysis include:

- City Hotel accounts for **66.45%** of total bookings, while Resort Hotel accounts for **33.55%**.
- The overall booking cancellation rate is **37.04%**.
- City Hotel has a higher cancellation rate (**41.73%**) than Resort Hotel (**27.76%**).
- August records the highest monthly booking volume, with **13,877 bookings**.
- August also records the highest average ADR of approximately **140.11**.
- January has the lowest monthly booking volume, with **5,929 bookings**.
- Repeat guests have a considerably lower cancellation rate than non-repeat guests.
- Longer booking lead times are associated with higher cancellation rates.
- City Hotel has a higher median ADR, whereas Resort Hotel has a longer average stay.

## Analytical Techniques

- Descriptive statistics
- Frequency and percentage analysis
- Grouping and aggregation
- Comparative analysis
- Pearson and Spearman correlation
- Time-series and seasonal analysis
- Data-quality assessment

## Project Structure

```text
Hotel-Booking-Demand-Analysis/
│
├── Hotel_Booking_Analysis.ipynb
├── Hotel Booking Analysis.pdf
├── hotel_bookings.csv
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Ensure Python and Jupyter Notebook are installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Keep `hotel_bookings.csv` in the same directory as the notebook.
5. Open Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Hotel_Booking_Analysis.ipynb` and run the cells sequentially.

## Limitations

- The analysis is based on historical booking data from July 2015 to August 2017.
- Missing values and unusual observations may affect selected analyses.
- The analysis identifies associations and patterns, not causal relationships.
- Estimated lodging value is calculated using ADR multiplied by total nights and should not be interpreted as actual realised revenue.

## Conclusion

This project demonstrates how Python-based exploratory data analysis can be used to understand hotel booking behaviour, cancellation patterns, seasonal demand and room pricing.

The findings highlight differences between City Hotel and Resort Hotel and provide insights that may support reservation management, demand planning and pricing decisions.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Hospitality Analytics | Data Analytics  
**Language:** Python
