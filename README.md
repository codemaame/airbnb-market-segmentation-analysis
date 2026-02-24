NYC Airbnb Market Segmentation: A PCA & Clustering Analysis
Project Overview
As a Business Analyst for StaySmart Consulting, I conducted this study to help property managers differentiate their listings in the competitive New York City market. The goal was to move beyond simple spreadsheets and use machine learning to identify natural groupings of properties, informing data-driven pricing, amenity bundles, and marketing strategies.

Tools & Technologies
Language: Python 3.x

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn (StandardScaler, OneHotEncoder, PCA, KMeans, AgglomerativeClustering)

Mathematical Analysis: SciPy (Dendrograms and Linkage)

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook / Google Colab

Key Technical Features
Dimensionality Reduction: Utilized Principal Component Analysis (PCA) to "de-noise" the dataset, identifying that 14 components capture 90% of the variance while focusing the model on the most significant drivers of value.

Unsupervised Learning: Applied and compared K-Means and Hierarchical Clustering (Complete Linkage) to segment the market.

Model Evaluation: Used the Elbow Method and Silhouette Analysis to justify the selection of 4 distinct, cohesive clusters.

The Market Segments
Cluster 0: Luxury Listings

Profile: High-capacity "Entire Home" properties with the highest average price points.

Strategy: Focus on "Luxury Bundles" including full kitchens and premium linens.

Cluster 1: Budget & Solo Travel

Profile: Affordable private rooms focused on value and high occupancy.

Strategy: High-volume bookings; emphasize essentials like high-speed Wi-Fi and self-check-in.

Cluster 2: Prime Location

Profile: Properties with the highest proximity to the city center (Manhattan) and high availability.

Strategy: Dynamic pricing based on local events; highlight proximity to transit and business districts.

Cluster 3: Outer-Borough Value

Profile: Listings that trade location for lower costs and a quieter residential feel.

Strategy: Target long-term guests; focus on "home-away-from-home" comforts like laundry and parking.

Actionable Business Insights
This analysis provides a strategic framework for:

Dynamic Pricing: Implementing cluster-specific rate adjustments (e.g., premium surge pricing for Luxury vs. long-stay discounts for Budget).

Amenity Bundling: Identifying which features matter most to specific guest purposes (e.g., workspace setups for Prime Location).

Targeted Marketing: Developing tailored messaging that resonates with the specific demographic and travel purpose of each segment.
