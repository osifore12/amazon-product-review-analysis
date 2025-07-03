# Amazon-Product-Review-Analysis
# 🛒 Case Study Overview: Amazon Product Review Analysis
RetailTech Insights, a growing e-commerce analytics company, provides strategic support to sellers on platforms like Amazon. Amid growing competition and the need for enhanced customer understanding, our team was tasked with analysing Amazon product and review data to uncover patterns, evaluate product performance, and draw actionable insights that can help improve marketing, pricing, and engagement strategies.
As a Junior Data Analyst, I conducted an in-depth Excel-based analysis to explore trends in pricing, discounts, ratings, and customer engagement.
## 🎯 Objectives
* Identify average discount percentage by product category
* Quantify product listings per category
* Analyse review volume and ratings by category
* Determine top-rated and most-reviewed products
* Compare actual vs. discounted prices across categories
* Assess distribution of product ratings
* Evaluate potential revenue by category
* Bucket products by price ranges
* Explore correlation between discounts and ratings
* Build an interactive dashboard for stakeholders
## 📁 Dataset Description
* *Source*: Scraped data from Amazon product listings
* *Rows*: 1,465 unique products
* *Fields*: 16 columns including category, product name, actual price, discount %, rating, and review count
* *Type*: Aggregated product-level data
* *Format*: CSV/Excel
## 🧹 Data Cleaning & Transformation
Before analysis, the following steps were taken:
1. Converted percentage and price fields to numeric format
2. Split and parsed comma-separated values into separate columns (where applicable)
3. Removed duplicates and blank rows
4. Created calculated columns for:
 * Discounted price
   * Revenue (actual\_price × rating\_count)
   * Rating-discount ratio
   * Price range buckets (e.g., <₹200, ₹200–₹500, >₹500)
## 📊 Analysis & Insights
### 1. *Discount Analysis by Category*
* Calculated average discount per category using pivot tables
* Identified categories with the highest promotional pricing
### 2. *Product Count per Category*
* Used pivot tables to count how many products fall under each category
### 3. *Review Volume*
* Total number of reviews calculated per category
* Top categories for customer engagement identified
### 4. *Top Rated Products*
* Filtered products with average ratings above 4.5
* Sorted by highest rating and review volume
### 5. *Price Comparisons*
* Compared average actual prices vs. discounted prices across categories
* Visualized gaps using bar charts
### 6. *Highly Reviewed Products*
* Identified products with 10,000+ reviews
* Flagged as high-performing SKUs
### 7. *Deep Discounts*
* Counted products with ≥50% discount
* Flagged categories with aggressive discounting strategies
### 8. *Rating Distribution*
* Created rating histogram to show how many products fall under each star rating (e.g., 3.0, 4.0, 4.5)
### 9. *Revenue Potential*
* Used formula: Actual Price × Review Count to approximate potential revenue per category
### 10. *Price Bucketing*
* Created 3 price bands:
 * <₹200
 * ₹200–₹500
 * >₹500
* Counted unique products in each bucket
### 11. *Discount-Rating Relationship*
* Used scatter plots to explore how ratings correlate with discount levels
### 12. *Low-Engagement Products*
* Counted how many products had fewer than 1,000 reviews
* Possible candidates for promotional focus
### 13. *Highest Discount Categories*
* Identified categories offering deepest average discounts
### 14. *Top 5 Products Overall*
* Created combined score using: Rating × Number of Reviews
* Ranked top 5 products based on this weighted score
## 📈 Dashboard Highlights (Excel)
* *KPI Cards* for Average Discount, Total Reviews, Top Category
* *Bar Charts*: Discounts & Ratings by Category
* *Pivot Tables*: Review counts, Ratings, Price Buckets
* *Scatter Plot*: Ratings vs. Discount %
* *Interactive Slicers*: Filter by Category, Rating, and Price Bucket
* *Top Product Table*: Dynamic list of highest-rated & reviewed product
## 🛠 Tools & Technologies
* *Microsoft Excel*
 * Pivot Tables
  * Calculated Columns & Formulas
  * Conditional Formatting
  * Slicers for interactivity
* *Data Visualization*
* Bar, Column, Scatter plot
## ✅ Recommendations
* *Look into categories with big discounts but low ratings
* *Try to boost sales of mid-priced products
* *Use the revenues estimates to know which categories can bring in the most money
* *Focus more on categories with lots of reviews and good ratings.
* *Promote products wih high ratings but low reviews.
## 📂 Project File
* *AmazonReviewDashboard.xlsx* – Final interactive dashboard & analysis sheet

