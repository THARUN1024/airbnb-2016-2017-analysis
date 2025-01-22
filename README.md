# airbnb-2016-analysis
# Airbnb Data Analysis (2016)

## Project Overview
This project analyzes Airbnb listing data of 2016 using Tableau for visualization and insights. The dataset includes listings and calendar data, which were processed and joined to provide a comprehensive view of Airbnb performance metrics such as price per bedroom, revenue trends, and price distributions across zip codes. The aim is to help stakeholders make data-driven decisions regarding pricing, property investments, and market analysis.

---

## Datasets

### 1. Listings Dataset
The `listings` dataset contains detailed information about each Airbnb listing, including:
- Property details (e.g., `id`, `name`, `description`, `zipcode`, `property_type`, `room_type`)
- Host information (e.g., `host_id`, `host_name`, `host_location`)
- Pricing and amenities (e.g., `price`, `cleaning_fee`, `square_feet`)
- Location data (e.g., `latitude`, `longitude`, `neighbourhood`)

### 2. Calendar Dataset
The `calendar` dataset includes daily availability and pricing for each listing:
- `listing_id`: Unique identifier for each property
- `date`: Calendar date
- `available`: Availability status (Yes/No)
- `price`: Daily price of the listing

### Data Preprocessing
- The `reviews` dataset was excluded as it was deemed unnecessary for this analysis.
- Listings and calendar datasets were **inner joined** on `listing_id` for a unified analysis.

---

## Key Insights

### 1. **Average Price Per Bedroom**
- Visualized the relationship between the number of bedrooms and average price.
- Observed trends:
  - 1-bedroom properties: Average price of $96.2
  - 6-bedroom properties: Average price of $584.8

### 2. **Price Distribution by Zip Code**
- Analyzed average pricing across various zip codes.
- Key findings:
  - Zip code `98177` has the highest average price ($842).
  - Zip code `98122` has an average price of $122.3.

### 3. **Revenue Trends for the Year**
- Mapped weekly revenue trends for 2016.
- Significant growth in revenue observed during peak seasons.

---

## Technologies Used

### Tools
- **Tableau**: For data visualization and dashboard creation.

### Dataset
The Airbnb dataset consists of:
- Listings data
- Calendar data (availability and pricing)

---

## Visualizations
The following visualizations were created using Tableau:

1. **Average Price Per Bedroom**
   - Bar chart showing average price vs. number of bedrooms.
2. **Price Per Zip Code**
   - Choropleth map displaying average prices by zip code.
3. **Revenue for the Year**
   - Line graph illustrating revenue trends over 2016.
