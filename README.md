# AirBnb-Data-visualization-Tableau
This repository contains the data set of AirBnb. This seeks to leverage Tableau Desktop/Tableau Public visual analytics capabilities to uncover and illustrate the shared attributes, disparities, and distinctive patterns inherent to Airbnb's presence in these cities, thus elevating the depth and insightfulness of the study.

Airbnb, a prominent online platform, enables individuals to reserve accommodations spanning a spectrum from beds and rooms to apartments and entire homes across global locales. This user-centric platform serves as a conduit for seamless property rentals, negating the need for intricate intermediaries or substantial capital outlays. Notably, users can secure lodgings at significantly competitive rates relative to traditional hotels. Distinctively, Airbnb extends its reach to regions where convectional hotel presence might be limited, offering an avenue for lodging acquisition in underserved locales. Moreover, the inclination towards immersive local experiences often steers individuals towards selecting accommodations embedded within native communities, fostering a distinctive preference for authenticity and cultural engagement.

Airbnb Statistics • Over 4 million listings worldwide • 150 million users in 191 countries • Worldwide value is $32 billion • Global growth rate since 2009 - 153%

**Key Attributes**:

1. id: Unique identifier for each listing.
2. name: The title or name of the listing.
3. host_id: Unique identifier for the host of the property.
4. host_name: Name of the host.
5. neighbourhood_group: The broader area or group that the neighbourhood belongs to.
6. neighbourhood: Specific neighbourhood where the property is located.
7. latitude: Latitude coordinate of the property.
8. longitude: Longitude coordinate of the property.
9. room_type: Type of room (e.g., Private room, Entire home/apt, Shared room).
10. price: Price of the listing per night.
11. minimum_nights: Minimum number of nights required for booking.
12. number_of_reviews: Total number of reviews received for the listing.
13. last_review: Date of the last review.
14. reviews_per_month: Average number of reviews per month.
15. availability_365: Number of days the listing is available for booking in a year.

**Problem Areas to Explore:**

1. Which are the popular neighbourhoods, their average prices and no. of listings?
2. What is the percent share of different property types and room types?
3. How the pricing is varying with location, property type, and reviews?
4. What are the different correlations between type of hosts and factors like- reviews & price?

**How to proceed with the dashboard:**

1. **Data Cleaning**
Begin by addressing the disorder and inconsistency within the dataset. Utilise Jupyter Notebook and Tableau Desktop/Tableau Public/PowerBI Prep to systematically cleanse the data, rectifying discrepancies, eliminating duplicates, and standardising formats.

2. **Data Transformation**
Generate supplementary columns by utilising pre-existing categorical data. These columns will be derived from extensive descriptive text, which, in its original form, proved arduous to comprehend and unsuitable for visualisation purposes. The extra columns that we created gave a much clear sense of how to approach and make an effective visualisation.

3. **Tableau Desktop/Tableau Public/PowerBI**
Employ Tableau Desktop/Tableau Public/PowerBI Prep to leverage its distinctive "Group and Replace" feature. Under the column denoted as Neighbourhood there are instances where identical entities are variably represented due to disparities in letter casing, spelling variations, or phonetic similarity. The "Group and Replace" algorithm inherent to Tableau Desktop/Tableau Public/PowerBI Prep proved instrumental in mitigating this issue.
