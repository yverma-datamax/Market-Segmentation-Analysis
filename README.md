# Market-Segmentation-Analysis
Marketing Segmentation Analysis using an unsupervised machine learning algorithm, K-means clustering to group all the customers in few categories that could be analyzed and understood for marketers. 

This project performs a market segmentation analysis of the smartwatch industry using survey data. The objective was to identify distinct consumer segments, analyze their characteristics, and recommend marketing strategies for Intel’s potential smartwatch launch.
Tools Used: Python (for clustering and discriminant analysis), Excel (for data cleaning and analysis), and  charts for visualization.

Methodology
Data Preparation

Survey dataset from PSU students (includes variables like innovation, style, communication, wellness, and price perception).
Scaled numeric variables to account for differing ranges (e.g., price vs. 1–7 scale survey variables).

Segmentation Analysis

Applied K-Means clustering for 3, 4, and 5 clusters.
Used the elbow method to determine optimal cluster number (k=3 chosen based on inertia).
Analyzed cluster characteristics via average variable values.
Linear Discriminant Analysis (LDA) is used to identify variables that best differentiate clusters.

Cluster Naming and Attractiveness
Cluster	Name	Description	Attractiveness (1–7)
0	No-nonsense / Real Athletes	Moderate users, basic smartwatch functionality, socially connected	4
1	Value Seekers / White Collar	Price-driven, focused on utility and task management	5
2	Trend Enthusiasts / Tech-Savvy	Image-conscious, innovative, willing to pay premium	7

Competitor Analysis
Compared Apple Watch, Fitbit, and Samsung Galaxy across variables such as innovation, wellness, task management, style, and price willingness.
Identified which segments each brand is best positioned for.

Marketing Recommendations
Target Segment: Cluster 2 – Trend Enthusiasts / Tech-Savvy.

Marketing Mix:

Product: Sleek, lightweight design, advanced health analytics, AI-powered fitness suggestions, compatible with Android productivity tools.
Price: Mid-premium pricing, subscription-based AI health insights.
Place: Intel website, Amazon, Best Buy, selective retail, and HR wellness programs.
Promotion: LinkedIn and YouTube tech campaigns, fitness events, corporate partnerships, bundled promotions with Google products.

Recommended partner: Google for ecosystem integration and AI capabilities; optional collaboration with Casio G-Shock for credibility and durability.

Key Insights
Optimal segmentation: 3 clusters; adding more segments did not significantly improve marketing insights.
Segment 2 has the highest purchase potential due to tech adoption, innovation, and premium willingness.
Intel’s previous smartwatch (Basis Peak) lacked ecosystem and style appeal; targeting tech-savvy users with advanced AI features is most promising.
Potential limitations: PSU student sample may overrepresent tech-savvy users, and price perception may not reflect real-life willingness to pay.

Conclusion

The analysis provides actionable insights for smartwatch market segmentation and a strategic go-to-market plan for Intel if it were to re-enter the market. While the data suggests potential opportunities, the highly competitive landscape and dominant incumbents (Apple, Samsung) pose significant barriers.
