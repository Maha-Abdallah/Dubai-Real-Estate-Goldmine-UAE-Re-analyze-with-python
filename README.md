# Dubai-Real-Estate-Goldmine-UAE-Re-analyze-with-python

# Introduction

This dataset presents a comprehensive overview of rental property listings across multiple cities in the United Arab Emirates, including Abu Dhabi, Dubai, Sharjah, Ajman, Ras Al Khaimah, Umm Al Quwain, and Al Ain. Compiled from bayut.com, it is a valuable resource for Data Analysts, Data Scientists, and Researchers looking to explore real estate trends, rental pricing patterns, or urban development studies in the UAE.

# Dataset Overview

Each entry in the dataset represents a rental property listing with details about the property's features, rental terms, and location specifics. This primary and unique dataset is designed for analysis and can be used to generate insights into the rental market dynamics of the UAE.

# Usage

This dataset is open for public use and is particularly suited for:

Analyzing trends in the rental market. Studying the geographical distribution of rental properties. Comparing rental prices across different cities and property types. Developing machine learning models to predict rental prices or classify property types.

# More Information

1-Dataset Structure:

The dataset consists of 73,742 rows and 17 columns.

2-Main Features of Interest:

The primary features of interest in this dataset are:

Address: Full address of the property.

Rent: The annual rent price in AED.

Beds: Number of bedrooms in the property.

Baths: Number of bathrooms in the property.

Type: Type of property (e.g., Apartment, Villa, Penthouse).

Area_in_sqft: Total area of the property in square feet.

Rent_per_sqft: Rent price per square foot, calculated as Rent divided by Area_in_sqft.

Rent_category: Categorization of the rent price (Low, Medium, High) based on thresholds.

Frequency: Rental payment frequency, which is consistently 'Yearly'.

Furnishing: Furnishing status of the property (Furnished, Unfurnished).

Purpose: The purpose of the listing, typically 'For Rent'.

Posted_date: The date the property was listed for rent.

Age_of_listing_in_days: The number of days the listing has been active since it was posted.

Location: A more specific location within the city where the property is located.

City: City in which the property is situated.

Latitude, Longitude: Geographic coordinates of the property.

3-Supporting Features:

The following features are likely to be helpful in further investigating the features of interest:

City: City in which the property is situated.

Number of Properties: This can provide insights into market trends and availability.

Latitude, Longitude: Geographic coordinates for spatial analysis.

Address: Specific location details.

Furnishing: Furnishing status of the property.

Type: Type of property (e.g., Apartment, Villa, Penthouse).

# Questions

We will use this visualization to answer the following questions:

What is the number of rental properties in each city?

Where are the rental properties located within the UAE?

Which city has the highest average rent?

How does the type of property affect the rent price?

# Conclusion

From these results, we can conclude that:

Dubai has the highest number of rental properties and the highest average rent, while Fujairah has the lowest number of rental properties and the lowest average rent.

Within Dubai, the map shows that the highest rent is 1,100,000 AED in Umm Al Quwain Marina, Umm Al Quwain, and the lowest rent is 14,000 AED in Jebel Ali. Therefore, Umm Al Quwain Marina, Umm Al Quwain, appears to be the most profitable area for renters.

It is evident that villas are the most common type of property available for rent.

