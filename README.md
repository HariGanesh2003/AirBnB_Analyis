#🏡 Airbnb France Data Analysis Project
## 📌 Project Overview

This project focuses on an exploratory data analysis (EDA) of Airbnb listings in France to uncover insights related to host behavior, property characteristics, amenities, pricing, demand, cancellation policies, and market competitiveness.

The analysis is designed to simulate real-world business intelligence use cases, helping understand how different factors influence competitiveness and demand in the Airbnb marketplace.

# 🎯 Objectives

Analyze host growth and experience trends

Understand property and room-type dynamics

Evaluate the impact of amenities on price, ratings, and demand

Study cancellation and security policies

Identify market competitiveness across cities, room types, and hosts

Use data-driven insights to simulate strategic decision-making

# 🗂 Dataset Description

The dataset contains Airbnb listings across France with the following major attributes:

👤 Host Information

host_id

host_name

host_since

host_response_rate

host_total_listings_count

🏠 Property Details

property_type

room_type

accommodates

bathrooms

bedrooms

beds

amenities

💰 Pricing

price

cleaning_fee

security_deposit

extra_people

guests_included

⭐ Reviews & Demand Indicators

number_of_reviews

reviews_per_month

review_scores_rating

📍 Location

city

state

zipcode

📜 Policies

cancellation_policy

# 🔍 Key Analyses Performed
## 1️⃣ Host Analysis

Host growth by year, month, and week

New vs experienced hosts

Host competitiveness using host_total_listings_count

## 2️⃣ Property & Room Type Analysis

Average price by room and property type

Ratings and reviews by room type

Guest capacity comparison

## 3️⃣ Amenities Analysis

Most common amenities

Amenities driving:

Higher prices

Better ratings

Higher demand (reviews)

Amenities processed using split & explode (industry-standard approach)

## 4️⃣ Cancellation & Security Policy Analysis

Policy distribution across:

Room types

Property types

Guest capacity

Cities

Stacked bar charts using groupby + unstack

Policy impact on pricing and ratings

## 5️⃣ Demand & Seasonal Trends (Proxy-Based)

Demand estimated using reviews_per_month

City-wise and room-type demand patterns

⚠️ Booking dates were not available; hence demand was analyzed using accepted proxy metrics.

## 6️⃣ Market Competitiveness Analysis

Price competitiveness by city and room type

Demand competitiveness using reviews

Supply competition across room types

Composite Competitiveness Score:

(rating × reviews_per_month) / price

# 📊 Tools & Technologies Used

Python

Pandas – data manipulation

Matplotlib – visualizations

Seaborn (used selectively)

Jupyter Notebook

## 📈 Visualization Style

Bar charts, horizontal bars, pie charts, stacked columns

Consistent subplot-based layouts

Groupby-based aggregations (no SQL-style shortcuts)

Clean, reproducible plotting format

## 🧠 Key Insights

High-demand cities show strong competitiveness even with moderate pricing

Entire homes dominate supply but face higher competition

Amenities like WiFi, Kitchen, and Heating strongly influence ratings

Flexible cancellation policies tend to attract better reviews

Hosts with larger portfolios dominate competitive segments

## 🚀 Future Improvements

Integrate booking calendar data for real seasonal analysis

Apply clustering for market segmentation

Build a Power BI / Tableau dashboard

Develop a pricing recommendation model

# 👨‍💻 Author

## Hari Ganesh
