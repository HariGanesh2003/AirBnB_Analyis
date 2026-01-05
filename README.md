# Airbnb Market Intelligence: France vs. Seattle 🌍🏠
## 📌 Project Overview
This Capstone project is a deep-dive comparative analysis of two major Airbnb markets: France (National level) and Seattle (City level). Using a combination of exploratory data analysis (EDA), statistical testing, and predictive modeling, this project uncovers the unique drivers of pricing and guest satisfaction in diverse geographic regions.

## 🛠️ Tech Stack & Skills
Languages: Python (Pandas, NumPy, Scikit-Learn, Scipy)

Database: MySQL (SQLAlchemy for Seattle data extraction)

Visualization: Matplotlib, Seaborn

Statistics: Hypothesis Testing (Z-tests, P-value analysis)

Machine Learning: Linear/Multi-Linear Regression, Logistic Regression, KNN, K-Means Clustering

## 📊 Comprehensive Analysis Sections
The project is structured into 8 distinct analysis modules:

Host Performance: Identification of "Power Hosts" and listing concentration.

Geospatial Trends: Pricing heatmaps for Paris districts and Seattle neighborhoods.

Customer Satisfaction: Sentiment and review frequency analysis.

Property & Amenities: Measuring the ROI of specific features (e.g., AirCon, Kitchen).

Host Behavior: Categorizing professional vs. casual hosting patterns.

Seasonality: Tracking growth and onboarding spikes (Peak years 2013-2015).

Policy & Risk: Impact of cancellation strictness and security deposits.

Market Competitiveness: Identifying high-ROI zones for potential investors.

## 🧪 Research & Modeling Results
## 1. Statistical Hypothesis Testing
We utilized Z-tests to validate market trends with 95% confidence:

Market Growth: Confirmed significant year-on-year growth in host counts.

Service Level: Proved that "Entire Homes" offer statistically more amenities than "Private Rooms."

Engagement: Validated that guest review volume is consistently increasing over time.

## 2. Machine Learning Implementation
We built and evaluated 5 core models to automate market insights:

Simple/Multi-Linear Regression: Found that Accommodation Capacity is the #1 predictor of price.

Logistic Regression: Achieved ~85% accuracy in classifying property types.

KNN (K-Nearest Neighbors): Provided localized pricing by comparing listings to their closest "neighbors."

K-Means Clustering: Segmented the market into 3 tiers: Economy, Standard, and Luxury.

## 📈 Key Findings
Seattle: A premium, high-satisfaction urban market where location is the primary driver of price. Average ratings are exceptionally high (94%+).

France: A massive, volume-driven market where privacy (Entire Homes) is the core expectation.

Automation: Our models allow hosts to automate pricing and categorization with over 85% accuracy, reducing manual error.

## 📁 How to Use This Repo
Data Cleaning: View the preprocessing steps in both .ipynb files, including outlier treatment and currency standardization.

Run Analysis: Execute the notebooks to see live visualizations and statistical outputs.

Report: Read the Airbnb_Comparative_Analysis_Report.docx for a business-ready summary of the project.

## 👤 Author
Hari Ganesh S A

Data Science Student | Capstone Project
