Bangkok Airbnb Accommodation Prices Analysis

By Baila Zwiebel

Introduction

This project investigates several key questions about Airbnb accommodations in Bangkok, with the primary objective of predicting accommodation prices for the year 2025 and identifying optimal listing prices based on various property features.
Research Questions

Main questions:

    Can we predict accommodation prices in Bangkok for 2025?
    Can we predict what price a property in Bangkok should be listed at based on different features?

Additional questions:

    What is the cheapest neighborhood in Bangkok?
    What is the cheapest season for each neighborhood?
    How do seasons affect the pricing and availability of listings?
    What are the common characteristics of highly rated listings?
    Which types of properties are most commonly booked?
    How do the lengths of stays vary by season and what impact does this have on pricing?
    Can seasonal availability data predict pricing trends for peak and off-peak seasons?
    Which neighborhoods show the highest variability in pricing within the same house type?

Methodology
Data Analysis

    Linear Regression: Used to predict prices but showed poor model performance.
    Time Series Analysis (ARIMA): Forecasted pricing trends up to 2025 with some degree of predictability.
    Multiple Regression Models: Analyzed with full and reduced sets of features. Random Forest and Extra Trees Regressors highlighted.
    Classification Models: Employed to predict price bins; Random Forest and Extra Trees Classifiers showed the best performance.

Additional Techniques

    DBSCAN & Dendrogram: Attempted but unsuccessful in clustering data effectively.
    K-means: Successfully clustered data based on latitude and longitude, focusing on neighborhoods.

Key Findings

    Cheapest Neighborhood: Bang Khae emerged as the most affordable.
    Seasonal Pricing: Winter typically offers the lowest prices, varying by neighborhood.
    High Demand: Entire homes have the lowest average days available, indicating higher demand.
    Tourist Hotspots: Vadhana shows high popularity with limited average availability.
    Seasonal Demand Fluctuations: Prices peak during dry months (April and October) and dip during the monsoon season (June to September).

Conclusion

The project faced challenges in addressing the main research questions directly due to model limitations and external factors affecting predictability. However, classification models provided insights into price bin predictions based on property features.

Property owners can use this analysis to decide on pricing strategies, while renters can identify the best times and neighborhoods for cost-effective travel. The variability within neighborhoods based on room types and other features provides further granularity to optimize decision-making for both hosts and guests in Bangkok's Airbnb market.
