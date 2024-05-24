# Yelp Dataset Analysis

## Overview
This project analyzes the Yelp dataset to derive insights about businesses, users, and reviews. It includes two parts: data profiling and inferential analysis.

## Part 1: Data Profiling

### Data Overview
- **Total Records**: Each table has 10,000 records.
- **Distinct Records**:
  - **Business**: 10,000
  - **Hours**: 1,562
  - **Category**: 2,643
  - **Attribute**: 1,115
  - **Review**: 10,000 (id), 8,090 (business_id), 9,581 (user_id)
  - **Checkin**: 493
  - **Photo**: 10,000 (id), 6,493 (business_id)
  - **Tip**: 3,979 (business_id), 537 (user_id)
  - **User**: 10,000
  - **Friend**: 11
  - **Elite_years**: 2,780

### Null Values
- No null values in the Users table.

### Statistical Insights
- **Review (Stars)**: min: 1, max: 5, avg: 3.71
- **Business (Stars)**: min: 1, max: 5, avg: 3.65
- **Tip (Likes)**: min: 0, max: 2, avg: 0.01
- **Checkin (Count)**: min: 1, max: 53, avg: 1.94
- **User (Review_count)**: min: 0, max: 2,000, avg: 24.3

### Top Cities by Reviews
1. Las Vegas: 82,854 reviews
2. Phoenix: 34,503 reviews
3. Toronto: 24,113 reviews

### Star Rating Distribution
- **Avon**: Stars range from 1.5 to 5.0
- **Beachwood**: Stars range from 2.0 to 5.0

### Top Users by Reviews
1. Gerald: 2,000 reviews
2. Sara: 1,629 reviews
3. Yuri: 1,339 reviews

### Review Correlation with Fans
- More reviews correlate with more fans. Users with over 100 reviews have an average of 20.98 fans.

### Love vs. Hate in Reviews
- "Love" appears in 1,780 reviews, while "Hate" appears in 232 reviews.

### Top Users by Fans
1. Amy: 503 fans
2. Mimi: 497 fans
3. Harald: 311 fans

## Part 2: Inferential Analysis

### Las Vegas Restaurants: 2-3 Stars vs. 4-5 Stars
- **Hours**: Similar distribution.
- **Reviews**: More reviews for 4-5 stars group.
- **Location**: No significant neighborhood trends.

### Open vs. Closed Businesses
- **Count**: More open businesses.
- **Ratings**: Higher average ratings for open businesses.

### Most Satisfactory Business Category
- **Top Category**: Automotive with an average rating of 4.5.
- **Criteria**: Categories with at least 5 businesses and 100 reviews.
