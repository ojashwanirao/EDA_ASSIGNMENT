📊 Exploratory Data Analysis (EDA) Projects
This repository features four diverse Exploratory Data Analysis (EDA) projects spanning the automotive, e-commerce, and music industries. Each project highlights essential EDA techniques including data cleaning, statistical analysis, and visualization to uncover actionable insights.

🗂️ Projects Overview
Project Name	Dataset Source	Key Focus Areas	Tools Used
Bike Resale Analysis	Used Bike Listings	Pricing trends, ownership impact	Pandas, Seaborn, IQR
Car Sales Analysis	Used Car Sales Data	Dealer pricing, demographic trends	Plotly, Correlation Analysis
Amazon Sales Analysis	Amazon Product Reviews	Discounts, ratings, and popularity factors	Matplotlib, Text Analysis
Spotify Hip-Hop Analysis	Spotify Tracks	Artist popularity, track duration patterns	Seaborn, Box Plots

🚴‍♂️ 1. Bike Resale Analysis
Dataset: 1,061 used bike listings including brand, price, km driven, and ownership.

Key Insights:
💰 Median selling price: ₹52,000
🧍 Individual sellers account for 75% of listings
📉 Bikes older than 2015 depreciate 30% faster
🚫 Outliers (in km driven) removed using the IQR method

Visualizations:
Scatter plot: selling_price vs. km_driven
Heatmap: Correlation between numerical features

🚗 2. Car Sales Analysis
Dataset: Used car sales data including price, dealer type, customer income, and engine type.
Key Insights:
🚘 Toyota shows highest price variation (SD: $8,200)
⚙️ Automatic cars are 20% costlier than manual
🏆 Honda Civic is the top-selling model (15% of total sales)

Visualizations:
Box plot: Price distribution by transmission type
Geographic heatmap: Sales volume by region

🛒 3. Amazon Sales Analysis
Dataset: 1,000+ Amazon products with ratings, discounts, and review text.
Key Insights:
📱 Electronics have the highest average rating (4.2/5)
🔻 Discounts >50% correlate with lower average ratings (3.4/5)
🔍 Most common keyword in reviews: "value for money"

Visualizations:
Bar chart: Average discount % by category
Scatter plot: Discounted price vs. Rating

🎵 4. Spotify Hip-Hop Analysis
Dataset: 500 top hip-hop tracks including artist, track duration, and popularity.
Key Insights:
🎤 Drake has the most tracks (42 entries)
⏱️ Average track duration: 3.2 minutes
🔄 No correlation found between duration and popularity

Visualizations:
Violin plot: Popularity distribution by artist
Pair plot: Multi-variable relationships

🛠 Technical Stack
Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly

Methods:
IQR-based outlier detection
Correlation analysis
Text mining for keyword extraction
