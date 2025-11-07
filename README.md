# India's-Airbnb-Gems-Project
🎯 1. Project Objective

The goal of this project was to analyze the top 500 Airbnb listings across India to understand how factors like room type, Superhost status, city, and ratings influence pricing and customer satisfaction.

The focus was on using SQL for data cleaning and Python (EDA) for exploring insights — without relying on visualization tools like Power BI or Tableau.

This project helps answer questions like:

What types of listings are most common in India?

Do Superhosts really charge more?

Which cities have the most and the costliest Airbnb stays?

What’s the overall guest satisfaction level in India’s Airbnb market?

📊 2. Key Insights (Results After EDA)

💰 Pricing:

Most listings are priced under ₹5,000 per night, showing India’s Airbnb market is mainly budget and mid-range.

A small group of luxury villas in Goa and metro areas charge between ₹20,000–₹35,000 per night.

⭐ Ratings:

The average rating is 4.7 stars, showing high guest satisfaction.

Superhosts have slightly higher ratings (~4.8) compared to regular hosts (~4.6).

🏡 Room Type:

“Entire place” dominates (≈ 65% of listings), followed by private rooms and farm stays.

Travelers prefer privacy and exclusive use stays.

👨‍💼 Superhosts:

Only 16% of hosts are Superhosts, but they earn nearly 2x higher prices and receive better reviews.

🏙️ Cities:

Goa (especially Candolim, Anjuna, Calangute) is India’s Airbnb hotspot.

Gurugram, Lonavala, Jaipur, and Udaipur also rank high in listings and average prices.

⚙️ 3. Tech Stack & Tools Used
Tool	Purpose	Why It Was Used
MySQL	Data cleaning, removing duplicates, fixing missing values	For accurate, structured, and query-based data preparation
Python (Pandas, NumPy)	Data manipulation, exploration	Easy to handle structured data for analysis
Matplotlib & Seaborn	Data visualization	To visualize patterns, correlations, and distributions clearly
Jupyter Notebook	Development & presentation	For clean code execution, graph display, and storytelling
📈 4. EDA (Graphs) — Purpose and Business Value
Graph / Analysis	Business Goal	What It Shows
Price Distribution	Understand pricing spread and affordability	Shows most Airbnbs are budget-friendly, few are premium
Ratings Distribution	Measure guest satisfaction levels	Ratings mostly 4.5–5.0, meaning strong customer experience
Room Type Popularity	Identify popular property types	“Entire place” dominates the Indian Airbnb market
Superhost vs Regular Host	Compare pricing and ratings by host type	Superhosts charge more and maintain better ratings
Top 10 Cities by Listings	Find market concentration areas	Goa, Delhi, and Lonavala are the most active Airbnb zones
Price vs Rating (Scatter)	Analyze correlation between price and satisfaction	Ratings don’t strongly influence pricing — location matters more

🧠 Business Understanding:
The EDA helps Airbnb or property owners understand how to price their listings, identify profitable cities, and what type of properties guests prefer most in India.

🗂️ 5. Dataset

Name: Airbnb_India_Top_500.csv

Source: Kaggle – [Airbnb India Top 500 Listings](https://www.kaggle.com/datasets/kanchana1990/indias-airbnb-gems-2024-trending-picks?utm_source=chatgpt.com)

Size: 500 rows × 9 columns

Columns Include:

address – Property location

isHostedBySuperhost – Whether host is a Superhost or not

location_lat, location_lng – Coordinates

name – Listing name/title

numberOfGuests – Guest capacity

price_inr – Price per night in INR

roomType – Type of room or property

stars – Average customer rating

🧩 Final Outcome

A clean, analysis-ready Airbnb dataset with 498 verified listings and clear insights on India’s pricing trends, room preferences, and Superhost impact — created using only SQL + Python.

📊 The project highlights how data cleaning and EDA can reveal actionable business insights for travel and hospitality sectors.
