Airbnb Listing Data Analysis for Business Growth
This repository contains an analysis of Airbnb listing data. The primary goal is to derive actionable insights from the dataset to answer key business questions and help inform strategic decisions for business growth.

📝 Table of Contents
Project Overview

Key Business Questions
Analysis & Insights
Tools & Libraries
Conclusion & Recommendations

🎯 Project Overview
As a data-driven company, Airbnb aims to leverage its vast dataset to understand market dynamics, user behavior, and growth opportunities. This analysis explores a sample dataset of listings to uncover patterns in pricing, property types, geographic distribution, and user engagement.

❓ Key Business Questions
This analysis seeks to answer the following questions:
What is the distribution of listing prices?
How are the different room types distributed?
How are listings distributed across different neighbourhoods?
What is the relationship between price and room type?
How has the number of reviews changed over time?

📊 Analysis & Insights
1. What is the distribution of listing prices?
Analysis: A histogram was generated to view the frequency distribution of listing prices.
Insight: The price distribution is heavily right-skewed. The vast majority of listings are concentrated in the lower price range (e.g., $50 - $200 per night), with a long tail of high-priced, luxury properties.
Business Implication: The core of our business caters to budget-conscious and mid-range travelers. Marketing campaigns should focus on affordability. We can also create a premium or "Luxe" category to better segment and market the high-end listings.

2. How are the different room types distributed?
Analysis: A pie chart was used to show the proportion of each room_type.
Insight: The most common listing is Entire home/apt, followed by Private room. Shared room and Hotel room make up a very small fraction of the inventory.
Business Implication: Customers show a strong preference for privacy. We should encourage hosts to list entire homes and apartments. For hosts with private rooms, we can provide resources on how to enhance guest privacy and comfort to stay competitive.

3. How are listings distributed across different neighbourhoods?
Analysis: A bar chart was created to display the total number of listings in the top neighbourhoods.
Insight: Listings are highly concentrated in a few popular, central neighbourhoods. Many other neighbourhoods have significantly fewer listings, indicating an underserved market.
Business Implication: There is a significant opportunity for growth in less saturated areas. We should launch targeted host acquisition campaigns in these neighbourhoods, potentially offering sign-up bonuses or enhanced visibility for new hosts in these zones.

4. What is the relationship between price and room type?
Analysis: A box plot was used to compare the price distributions across different room types.
Insight: As expected, Entire home/apt has the highest median price, followed by Private room, and then Shared room. The price variation within the Entire home/apt category is also the largest.
Business Implication: This confirms our pricing structure is aligned with customer value perception. This data can be used to refine our smart-pricing suggestion tool for hosts, helping them price their listings competitively based on room type and neighbourhood averages.

5. How has the number of reviews changed over time?
Analysis: A time-series line plot was generated to show the cumulative number of reviews over the years.
Insight: The number of reviews shows a strong, near-exponential upward trend over time. This indicates a consistent growth in bookings and user engagement on the platform. Seasonal peaks (e.g., summer months) are also visible.
Business Implication: The platform's growth is healthy and accelerating. We can leverage the understanding of seasonal trends to plan marketing pushes, offer off-season discounts to smooth out demand, and ensure our infrastructure is prepared for peak traffic.

🛠️ Tools & Libraries
Language: Python
Libraries:
Pandas (Data Manipulation)
Matplotlib (Plotting)
Seaborn (Statistical Visualisation)

💡 Conclusion & Recommendations
The analysis reveals several key opportunities for strategic growth:
Focus on the Core Market: Double down on marketing efforts that highlight affordable and mid-range listings, as this is our largest segment.
Incentivize Desired Inventory: Encourage the listing of Entire home/apt as it is the most popular and highest-earning category.
Expand Geographically: Launch targeted campaigns to attract new hosts in underserved neighbourhoods to diversify our offerings and capture new markets.
Empower Hosts: Enhance our pricing tools to provide data-driven recommendations to hosts, helping them maximize their earnings and occupancy rates.
Leverage Seasonality: Use insights from review trends to launch targeted seasonal marketing campaigns and promotions.
