# Business-License-Analytics-NYC-Chicago-Washington-DC
Overview Most businesses — including motor vehicle sales, service &amp; repair shops, and home improvement contractors — are required to obtain a Business License from their local Department of Licensing and Consumer Protection. Many cities publish this licensing data through Open Data portals, making it available for public analysis.

This project ingests business license datasets (TSV format) from New York City, Chicago, and Washington DC, normalizes the schema across all three sources, and builds an analytical model to surface actionable insights about licensing activity, geographic concentration, industry trends, and renewal behavior.

Data Sources
City              Format   Portal
New York City      TSV     NYC Open Data
Chicago            TSV     Chicago Data Portal
Washington DC      TSV     DC Open Data

Analytical Objectives
1. License Status Distribution
Quantify active vs. inactive business licenses — both per city and aggregated across all three cities.
2. Predominant Industries
Identify the top industries for which business licenses are most frequently granted.
3. Geographic Hotspots
Determine the top 5 areas (by zip code and by street name) within each city with the highest license issuance volume.
4. Issuance Trends Over Time
Analyze the historical trend of new business license issuances to identify growth or contraction patterns.
5. License Abandonment Trends
Track the rate and trajectory of license expirations, revocations, and non-renewals over time.
6. Seasonal Patterns
Detect seasonal or monthly variations in license issuance to uncover cyclical business formation behavior.
7. Urgency Classification
Categorize and count businesses by urgency tier — Immediate, High, Medium, and Low — across all cities.
8. Renewal Reminder Targeting
Identify inactive businesses (with available contact details) by city to enable targeted renewal reminder outreach.
9. Top Franchise Organizations
Rank the top 10 organizations by franchise ownership count within each city.
10. License Age Distribution
Analyze the distribution of businesses based on the number of years elapsed since their license was originally issued.

Tech Stack
Databricks DQX
E/R diagram (Dimensional Model - Star schema)
