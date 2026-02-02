# Eda-Project
---

# Area-Wise Hotel Price Analysis Using Web Scraping & EDA

## Project By

**Name:** Mandla Ashok
**Batch:** 456

---

## Project Overview

This project focuses on analyzing hotel pricing patterns across different areas using **web scraping** and **Exploratory Data Analysis (EDA)**.
Hotel data is collected from **Booking.com** using Selenium and analyzed to understand how prices vary based on **location, room type, ratings, and reviews**.
The goal is to help travelers make **cost-effective and informed booking decisions**.

---

## Business Problem

Travelers visiting unfamiliar cities often overpay for hotels due to:

* Lack of area-wise price comparison
* Over-reliance on ratings and reviews
* No structured dataset showing affordable zones

This project addresses the gap by providing **data-driven insights into hotel pricing behavior**.

---

## Objectives

* Scrape hotel data from Booking.com using Selenium
* Clean and preprocess real-world scraped data
* Analyze hotel prices across different locations
* Study relationships between price, ratings, reviews, and room types
* Identify budget-friendly and overpriced areas
* Provide actionable recommendations for travelers

---

## Data Source

* **Website:** Booking.com
* **City Covered:** Hyderabad
* **Data Type:** Hotel booking listings

---

## Dataset Description

The dataset includes the following features:

* **Hotel Name** – Name of the hotel
* **Location** – Area/locality within the city
* **Rating** – Average customer rating
* **Review Count** – Number of customer reviews
* **Original Price** – Listed price before discount
* **Discounted Price** – Final offered price
* **Room Type** – Category of accommodation

---

## Tools & Technologies Used

* **Python**
* **Selenium** – Web scraping
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Data visualization
* **ANOVA & Correlation Tests** – Statistical analysis

---

## Data Cleaning Steps

* Removed missing and duplicate values
* Converted prices and review counts to numeric format
* Standardized location and room type names
* Handled missing ratings and prices
* Prepared final dataset for analysis

---

## Exploratory Data Analysis (EDA)

### Univariate Analysis

* Most hotels fall in affordable to mid-range pricing
* Luxury hotels appear as price outliers
* Ratings are generally high across hotels
* Prices show high variability

### Bivariate Analysis

* Hotels with similar ratings have different prices
* Location influences price more than ratings
* Review count has limited impact on pricing

### Multivariate Analysis

* Hotels segmented into **budget, mid-range, and premium**
* Affordable hotels exist even in premium locations
* Strong correlation between original and discounted prices
* Weak correlation between reviews and price

---

## Hypothesis Testing

### Hypothesis 1: Price vs Room Type (ANOVA)

* **Result:** Significant difference in prices
* **Conclusion:** Reject Null Hypothesis

### Hypothesis 2: Price vs Location (ANOVA)

* **Result:** Significant price variation by location
* **Conclusion:** Reject Null Hypothesis

### Hypothesis 3: Price vs Review Score (Correlation)

* **Result:** Weak correlation
* **Conclusion:** Fail to reject Null Hypothesis

### Hypothesis 4: Price vs Review Count (Correlation)

* **Result:** Very weak correlation
* **Conclusion:** Fail to reject Null Hypothesis

---

## Key Insights & Recommendations

* Location is the **strongest driver** of hotel pricing
* Ratings alone do not determine hotel price
* Budget hotels exist even in high-demand areas
* Travelers often overpay due to lack of price awareness
* Booking platforms should recommend hotels based on **price-to-rating ratio**

---

## Challenges Faced

* Dynamic website content during scraping
* Missing and inconsistent real-world data
* Handling multiple room types and pricing formats

---

## Conclusion

This project demonstrates how **web scraping combined with EDA and statistical analysis** can uncover meaningful insights in real-world pricing data.
The findings help travelers identify affordable hotel zones and support smarter booking decisions.

