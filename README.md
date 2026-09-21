# British Airways Passenger Satisfaction Analysis

An interactive **Passenger Satisfaction Dashboard** developed using **Microsoft Power BI** to analyze British Airways passenger reviews and understand customer satisfaction, service quality, aircraft performance, traveller preferences, and feedback trends.

## 📊 Project Overview

This project transforms passenger review data into meaningful business insights through an interactive Power BI dashboard.

The analysis focuses on:

* Passenger satisfaction
* Aircraft performance
* Service quality
* Traveller types
* Cabin classes
* Customer feedback trends
* Geographical distribution of reviews

The dashboard helps identify service strengths, detect potential improvement areas, and support data-driven decision-making.

## 🎯 Business Problem

British Airways receives customer feedback from passengers travelling across different routes, aircraft, and cabin classes.

Due to the large volume of review data, manually identifying customer satisfaction trends, service issues, and passenger preferences can be difficult.

This project addresses the problem by creating an interactive dashboard that consolidates passenger feedback into meaningful visual insights.

## 🎯 Project Objectives

* Analyze passenger satisfaction using customer review data
* Evaluate aircraft performance based on passenger ratings
* Compare service quality across different categories
* Identify customer satisfaction trends over time
* Analyze passenger feedback across traveller and cabin types
* Provide interactive visualizations for business analysis
* Generate actionable business insights

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel**

## 📂 Dataset

The project uses two datasets:

### Passenger Reviews

Contains passenger review information including:

* Author
* Date
* Place
* Date Flown
* Traveller Type
* Seat Type
* Aircraft
* Route
* Overall Rating
* Seat Comfort
* Cabin Staff Service
* Food & Beverage
* Ground Service
* Entertainment
* Value for Money
* Recommended
* Verified Review
* Country

### Countries Dataset

A country mapping dataset was used to map country codes to country names for geographical analysis.

## 🧹 Data Cleaning & Transformation

Power Query was used to prepare the datasets for analysis.

Key data preparation steps included:

* Removing duplicate records
* Handling missing and invalid values
* Correcting numerical and date data types
* Standardizing aircraft names
* Cleaning categorical fields
* Validating data using Column Quality, Column Distribution, and Column Profile

The **Countries** table was connected with the **Passenger Reviews** table using the **Country** field.

**Relationship:** One-to-Many (1:*)

## 📊 Dashboard Features

### Key Performance Indicators

The dashboard includes:

* Average Overall Rating
* Recommendation Rate
* Total Reviews
* Verified Review Rating
* Total Aircraft Types

### Interactive Filters

Users can filter the dashboard by:

* Country
* Aircraft
* Traveller Type
* Seat Type
* Trip Verified
* Date Flown

### Visualizations

The dashboard contains:

* Country-wise Filled Map
* Monthly Rating Trend
* Aircraft Performance Bar Chart
* Service Quality Comparison
* Traveller Type Distribution
* Seat Type Satisfaction

## 🔍 Key Insights

The analysis identified several notable patterns in the passenger review data:

### Aircraft Performance

The Boeing 747-400 recorded the highest average customer satisfaction in the analyzed dataset.

### Most Frequently Reviewed Aircraft

The Airbus A320 had the highest number of passenger reviews in the dataset.

### Service Quality

Cabin Staff Service received the highest ratings among the analyzed service categories, while Food & Beverage and Entertainment had comparatively lower ratings.

### Cabin Class

Business and First Class passengers reported higher satisfaction levels compared with Economy Class passengers.

### Customer Feedback

Reviews were distributed across multiple countries and traveller types, providing different perspectives on passenger experience.

## 💡 Business Recommendations

Based on the dashboard analysis, the project recommends:

1. **Improve Food & Beverage**

   * Enhance meal quality and provide more diverse menu options.

2. **Upgrade Entertainment Services**

   * Improve in-flight entertainment systems and content.

3. **Improve Economy Class Comfort**

   * Focus on seat comfort and onboard amenities.

4. **Maintain Cabin Crew Standards**

   * Continue staff training and maintain strong cabin service quality.

5. **Use Customer Feedback Continuously**

   * Regularly monitor passenger feedback to identify service gaps and support data-driven decisions.

## 📸 Dashboard Preview

￼<img width="1682" height="850" alt="image" src="https://github.com/user-attachments/assets/2e2eb756-4d0d-4526-b2dc-52dbc45713bd" />


## 📁 Project Structure

## 📁 Project Structure

```text
British-Airways-Passenger-Satisfaction-Analysis/
│
├── README.md
│
├── Dataset/
│   ├── ba_reviews.csv
│   └── Countries.csv
│
└── Dashboard/
    └── British_Airways_Dashboard.pbix
```

## 📌 Project Type

**Interactive Business Intelligence Dashboard**

## 👤 Author

**Mohan Choudhari**

### Tools Used

Power BI • Power Query • DAX • Microsoft Excel

---

## ⭐ Conclusion

This project demonstrates how **Business Intelligence and Data Analytics** can transform customer review data into actionable business insights.

Using Power BI, the project provides an interactive view of passenger satisfaction across aircraft, traveller types, cabin classes, service categories, and geographical regions.
