🏡 HOUSE PRICE ANALYSIS

📌 Project Overview  
This project analyzes house prices using Python, focusing on **data cleaning, feature engineering, exploratory data analysis (EDA), and visualization**. The goal is to understand factors affecting house prices and extract meaningful insights.  

---

🔍 Process Overview  

1️⃣ **Data Cleaning & Preprocessing**  
✔ Checked for **missing values** and handled them appropriately  
✔ Identified and removed **duplicate entries**  
✔ Standardized **data types** (e.g., converting `date` column to datetime)  
✔ Detected and removed **outliers** using the **IQR method**  

2️⃣ **Feature Engineering**  
✔ Created **`price_per_sqft`** to normalize pricing based on house size  
✔ Extracted **year and month** from the `date` column for trend analysis  
✔ Categorized houses based on **price segments**  

3️⃣ **Exploratory Data Analysis (EDA)**  
✔ **Univariate Analysis** – Distribution of house prices, square footage, and other features  
✔ **Bivariate Analysis** – Relationship between `price` and key variables like `sqft_living`, `bathrooms`, and `waterfront`  
✔ **Multivariate Analysis** – Correlation heatmap to identify strongest predictors of house price  

4️⃣ **Geospatial Analysis**  
✔ Mapped house prices using **latitude and longitude**  
✔ Grouped **price per sqft by zip code** to identify expensive vs. affordable areas  
✔ Used **color-coded scatter plots** for price variations across locations  

5️⃣ **Visualization & Insights**  
✔ **Boxplots** – To analyze how categorical factors (`condition`, `grade`, `waterfront`) impact price  
✔ **Line plots & histograms** – To observe price trends over time  
✔ **Heatmaps** – To visualize geographic price variations  

 🚀 Conclusion  
1) House prices tend to increase over time**, but location plays a critical role  
2) Larger living spaces (`sqft_living`) strongly correlate with higher prices
3) Waterfront properties have significantly higher prices than non-waterfront homes 

