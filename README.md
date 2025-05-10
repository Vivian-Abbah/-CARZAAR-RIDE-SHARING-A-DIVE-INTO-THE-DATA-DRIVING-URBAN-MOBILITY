# -CARZAAR-RIDE-SHARING-A-DIVE-INTO-THE-DATA-DRIVING-URBAN-MOBILITY

Data tells stories only if you’re ready to listen. And with ride-sharing data, the narrative unfolds across streets, seasons, and screens.

INTRODUCTION

When I first opened the Carzaar Ride Sharing dataset, I didn’t just see columns and rows. I saw people, movement, decisions, and friction. This wasn’t just about drivers and passengers, it was about behaviors, patterns, and business impact. As urban mobility evolves, ride-sharing platforms have become pivotal in shaping commuter experiences. Carzaar, a growing ride-sharing company, aims to optimize user satisfaction, increase operational efficiency, and maximize revenue. This report explores key performance indicators across user behavior, payment methods, driver performance, and external factors like weather and surge pricing that will unearth insights, solve real-world problems, and guide smarter transportation strategies. Let’s take the ride.

![Ride Sharing Dashboard](https://github.com/user-attachments/assets/6ef993bb-d1a4-4b42-8146-38b89db80766)
 
🎯 OBJECTIVE

The goal of this project was to analyze Carzaar’s ride-sharing data from multiple perspectives, rider behavior, fare patterns, driver performance, payment methods, and weather impact to deliver actionable insights through an Excel-powered interactive dashboard.

PROBLEM STATEMENT

Despite a high number of rides and considerable fare revenue, Carzaar faces fluctuating user ratings, uneven driver performance, and varied ride demand under different conditions. The company seeks to:
•	Enhance the user experience and loyalty
•	Improve operational strategies based on data-driven insights
•	Address issues affecting ride durations and fare fluctuations

TOOLS AND METHODOLOGIES

Data Source: Internal Carzaar ride logs (Jan 1 - Jan 7)
Tool Used: Microsoft Excel (for dashboard visualization)
Analysis Approach: Exploratory Data Analysis (EDA), Trend Analysis, Segmentation, and Comparative Analysis

PRE-ANALYSIS

Before diving into the metrics, an initial analysis revealed:
•	Total Rides: 10,000
•	Total Fare Revenue: $600,938.35
•	Average Ride Distance: 35 km
•	Average User Rating: 39.97%
These statistics suggested a robust demand but hinted at potential service quality and customer satisfaction concerns.

IN-ANALYSIS

User Rating Trend
![image](https://github.com/user-attachments/assets/193bcfe1-eac6-452a-8c05-475fb00b7a4e)

The user rating trend over the first week of January shows mild volatility, with daily averages ranging from 3.70 to 3.79. The peak on January 5 (3.79) indicates a successful day in terms of service quality or external conditions like favorable weather or high driver availability. Conversely, the dip on January 3 (3.71) and January 6 (3.71) could suggest issues such as ride delays, unavailability, or service inconsistency. This variation, though small, is significant when scaled to thousands of users and reflects a need to stabilize the user experience.
Interpretation: Ratings are an indirect but powerful signal of overall customer satisfaction. Even small changes can result in churn if negative experiences stack up.

Ride Duration by Distance
![image](https://github.com/user-attachments/assets/9b558f66-a5b4-4b33-a28c-b68d0e714ac5)

Ride durations decrease steadily with the distance brackets:
33 mins for longest trips (137–151 km)
3 mins for shortest trips (2–16 km)
This proportionality shows that the algorithm for matching and routing is functioning efficiently. However, the jump between certain brackets (e.g., 62–76 km and 47–61 km) where the duration drops more sharply might indicate variations in traffic density or road infrastructure.
Interpretation: Monitoring and optimizing these transition points could further improve time predictions and scheduling.

Fare by Weather Condition
![image](https://github.com/user-attachments/assets/fbda1d0c-3928-4884-be08-5bbc1413feb9)
 
Clear Weather rides generated the highest revenue ($386,623.15)—indicative of higher demand or uninterrupted ride operations. In Rainy and Foggy conditions, revenue drops substantially. Snowy and Thunderstorm conditions yield the least fare, under $30K, likely due to safety concerns or decreased user demand.
Interpretation: Weather strongly affects ride demand and supply dynamics. Proactive planning around these conditions can prevent lost revenue.

Payment Method Analysis
![image](https://github.com/user-attachments/assets/ce15e7c9-2f00-4150-9fe9-9426b3f665b6)
 
Credit Cards contributed nearly 50% of the total fare. Mobile Wallets are growing, with $183,392.63, showing promise among tech-savvy users. Cash is the least used, possibly due to urban preferences and convenience.
Interpretation: Digital payment systems are preferred. Leveraging this with offers or loyalty points can improve customer stickiness.

Surge Pricing by Traffic
![image](https://github.com/user-attachments/assets/a3c76be7-a187-4142-bea3-7d64c9d7bb67)
 
Medium traffic conditions yielded the highest revenue $302,045.61 and number of rides (5030). Low traffic had more rides than high traffic but significantly lower revenue. High traffic areas saw the fewest rides and lower fare recovery.
Interpretation: The medium-traffic scenario is the most efficient balance of speed, ride count, and fare volume. This sweet spot should be the focus of operational deployment and marketing.

Pickup Locations
![image](https://github.com/user-attachments/assets/0ab7f582-08d6-4521-910b-e80a17cb1ed9)
 
Suburbs, Malls, Midtown, and University zones dominate pickup requests. The airport, Financial District, and Downtown are also active but slightly less.
Interpretation: These insights can guide placement of drivers during peak hours and promotional campaigns based on geography.

User Status
![image](https://github.com/user-attachments/assets/007db1de-cb09-4521-9a0a-da832a3e66c0)
 
Returning Users: 39.97% Frequent Users: 30.61% New Users: 29.42%. The platform is attracting new users at a lower rate, but higher returning and frequent user percentages indicate a very healthy user retention.
Interpretation: Retention strategies like ride credits, push notifications, or follow-up feedback collection should be explored.

Driver Rating by Experience
![image](https://github.com/user-attachments/assets/74893fbb-688f-4f68-9b1c-c7dda1b5bdfa)
 
Drivers with 6–9 years of experience have the highest number of top ratings. While less experienced drivers (0–3 years) consistently receive lower ratings, especially those in the 1–2-year range (975 to 973 ratings).
Interpretation: Experience correlates with higher service quality. Newer drivers might be struggling with navigation, customer handling, or time management.

KEY FINDINGS AND INSIGHTS

1. User satisfaction is inconsistent, with the highest rating not exceeding 3.79.
2. Weather impacts fares, significantly clear days are most profitable.
3. Digital payments dominate, simplifying the transaction process.
4. High new user influx, but retention seems weak—needs improvement.
5. Driver experience matters as less experienced drivers negatively impact user ratings.
6. Medium traffic areas are revenue sweet spots, requiring strategic positioning of rides.

RECOMMENDATIONS 

1. Launch Structured Driver Onboarding and Upskilling Program
Create a mentorship system where experienced drivers guide new recruits. Offer simulations, customer service modules, and traffic handling workshops. Incentivize improvement in performance with bonuses.
Why: Improves consistency in rider experience and reduces the rating gap.
2. Loyalty Program for New and Returning Users
Introduce tiered rewards (e.g., Silver, Gold, Platinum) based on ride frequency. Provide discounts or ride credits for referrals or bulk bookings.
Why: Encourages repeat use, helps shift more users from "new" to "frequent" category.
3. Geo-Targeted Promotions in Medium Traffic Zones
Use real-time traffic data to deploy drivers and push offers where medium traffic is predicted. Offer limited time "fast pickup" guarantees in those zones.
Why: Maximizes profitability and operational efficiency in areas already showing high ROI.
4. Dynamic Weather-Based Pricing and Rider Bonuses
Implement surge multipliers or ride discounts based on forecasted weather. Encourage drivers with weather hardship bonuses to remain active during light rain or fog.
Why: Controls supply gaps during adverse conditions and preserves rider availability.
5. Incentivize Digital Payments via Mobile Wallet
Offer cashback, loyalty coins, or bonus rides for users choosing mobile wallets. Partner with e-wallet companies for promotional campaigns.
Why: Reduces cash handling issues and encourages repeat business through app engagement.

ACTIONABLE PLAN

Objective	Action         	Timeline	         Owner             	KPI

Improve driver ratings   	Launch training for new drivers   	2 weeks   	Operations Manager	Avg driver rating > 4.0

Boost user retention	Launch loyalty program	1 month	Marketing	Increase return rate by 10%

Maximize revenue in clear weather	Deploy weather-based promotions	1 week	Product Team	+15% fare during clear days

Balance driver allocation	Real-time reallocation to medium traffic	Ongoing	Tech Team	Reduce waiting time by 10%

Enhance mobile wallet usage	
Offer cashback on mobile payments	3 weeks	Finance Team	+20% mobile wallet usage


CONCLUSION

Carzaar has a solid foundation with high ride demand and effective digital payment adoption. However, user experience and driver performance require focused improvement. Leveraging weather patterns, traffic data, and user behavior insights can significantly enhance profitability and customer satisfaction.

LIMITATIONS

Data spans only 7 days—long-term trends may vary.
External factors like fuel prices, local events, or competitor actions weren’t considered.
Lack of demographic data limits user segmentation.

FURTHER RESEARCH

Analyze ride cancellation patterns and causes.
Study impact of vehicle types on ride satisfaction.
Develop predictive models for surge pricing optimization.

REFERENCES

1. Gartner (2024). Trends in AI-based route optimization and driver support systems.
2. World Bank Urban Mobility Report (2023). Weather and transport service performance.
3. Internal Carzaar Ride Data Dashboard (Jan 1 – Jan 7, 2025), Microsoft Excel Export.

