# EDA-WebScraping-Project
# 📊 Leveraging Climate Data to Optimize Travel Recommendation

Exploratory Data Analysis (EDA) Project

# 📌 Project Overview

This project focuses on analyzing historical and real-time climate data to help travelers choose destinations based on comfortable temperature preferences.
By leveraging weather data across multiple countries and time periods, the project aims to reduce unpleasant travel experiences caused by extreme weather conditions.

# ❓ Problem Statement

Travelers often struggle to select suitable destinations due to:

Rapidly changing weather conditions

Climate data scattered across multiple web pages

Difficulty in manually analyzing temperature trends

This makes it hard to identify destinations that match personal climate comfort.

# 💼 Business Problem

Most travel recommendation platforms:

Ignore real-time and historical climate conditions

Recommend destinations without temperature-based personalization

This leads to:

Unexpected extreme weather experiences

Trip cancellations

Lower customer satisfaction and repeat bookings

# 🎯 Project Objectives

Analyze historical and real-time temperature data

Match destinations with traveler climate preferences

Reduce trip cancellations caused by unfavorable weather

Improve travel comfort and overall customer satisfaction

# 🛠️ Tools & Technologies Used

Selenium – Dynamic web scraping

Python – Data processing and analysis

Regex – Pattern matching and text extraction

Pandas – Data cleaning and manipulation

Matplotlib & Seaborn – Data visualization

# 📥 Data Collection

Data scraped from an online Date and Time weather website

Temperature data collected for capital cities

Data collected over 7 consecutive days

Dynamic scraping handled using Selenium

# 🧹 Data Preprocessing

Removed missing and duplicate values

Standardized date and time formats

Created derived features:

Hour

Time_Slot (Morning, Afternoon, Evening, Night)

Coolest indicator column

# 📊 Exploratory Data Analysis (EDA)
Univariate Analysis

Temperature distribution shows mostly moderate, travel-friendly climates

Extreme hot and cold temperatures are relatively rare

Bivariate Analysis

Temperature varies significantly by hour of the day

Average temperature differs across countries and cities

Multivariate Insights

Comfortable travel times often occur during early mornings and evenings

Climate patterns vary strongly by geographical location

# 📐 Hypothesis Testing

ANOVA tests confirmed:

Significant temperature differences across time slots

Significant variation between cities

Night-time temperatures are significantly cooler than daytime

All null hypotheses were rejected at α = 0.05.

# ✅ Key Findings

Temperature patterns vary by both time and location

Moderate climate countries offer better comfort for general travelers

Tropical destinations are suitable for users preferring warmer climates

# 💡 Recommendations

Recommend moderate-temperature countries (e.g., Hungary, Lesotho, Norway) for comfort-focused travelers

Suggest tropical destinations (e.g., Aruba, Kiribati, Saint Kitts and Nevis) with optimal travel timings

Use climate-based personalization to improve travel satisfaction and reduce cancellations

# 🚀 Future Scope

Integrate live weather APIs

Add seasonal and monthly trend analysis

Build a recommendation system or dashboard

Include user preference inputs for personalization

# 👤 Author

Kandela Vamshi  
🎓 Currently pursuing Master of Computer Applications (MCA)
🏫 NRIM College
📌 Passionate about transforming data into meaningful insights

🔗 LinkedIn: https://www.linkedin.com/in/kandela-vamshi-2b4457258

💻 GitHub: https://github.com/Vamshikandela/Vamshikandela
