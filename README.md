# Airbnb Hospitality Intelligence Hub Analysis

## Project Overview

Airbnb is a global leader in online accommodation marketplaces, offering diverse lodging options across neighborhoods in New York City and beyond. To improve its business operations, Airbnb developed a cutting-edge **Hospitality Intelligence Hub**. This tool uses MySQL to analyze data, providing insights into trends in customer preferences, pricing, and neighborhood performance.

The goal of this project is to leverage Airbnb data to uncover actionable insights that can optimize pricing strategies, enhance occupancy rates, and improve customer satisfaction.

---

## Dataset Description

This analysis uses two key datasets provided in `.csv` format:

### `Listings` Table:
- **`id`**: A unique identifier for each listing.
- **`name`**: The name of the listing.
- **`host_id`**: A unique identifier for the host of the listing.
- **`host_name`**: The name of the host.
- **`neighbourhood_group`**: The group of neighborhoods where the listing is located.
- **`neighbourhood`**: The specific neighborhood name.
- **`room_type`**: The type of room (e.g., private room, entire apartment).

### `Booking_Details` Table:
- **`listing_id`**: A unique identifier for each listing.
- **`price`**: The nightly price of the listing.
- **`minimum_nights`**: The minimum number of nights required for booking.
- **`number_of_reviews`**: The total number of reviews received.
- **`reviews_per_month`**: The average number of reviews received per month.
- **`calculated_host_listings_count`**: The total number of listings associated with the host.
- **`availability_365`**: The total number of days the listing is available in a year.

---

## Insights and Results

### Key Findings:
1. **Neighborhood Trends**:
   - Popular neighborhoods for bookings and their price ranges.
   - Correlation between `neighbourhood_group` and occupancy rates.

2. **Pricing Patterns**:
   - Price trends by room type (e.g., private rooms, entire apartments).
   - Identification of neighborhoods with underpriced or overpriced listings.

3. **Customer Preferences**:
   - Frequently booked room types.
   - Impact of reviews and availability on booking patterns.

4. **Host Insights**:
   - Host performance based on the number of listings and reviews.
   - Optimization strategies for hosts with multiple listings.

---

## Tools Used
- **MySQL**: For querying and analyzing the datasets.

---

## Conclusion

The analysis provided actionable insights that Airbnb can use to:
- Optimize pricing strategies to maximize occupancy rates in various neighborhoods.
- Improve customer satisfaction by aligning listings with customer preferences.
- Assist hosts in understanding market demand and improving listing performance.

This project demonstrates the value of data-driven decision-making in the hospitality industry, helping Airbnb maintain a competitive edge by continuously enhancing customer experiences.
