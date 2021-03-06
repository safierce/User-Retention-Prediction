User Retention Prediction

Dataset description
- city: city this user signed up in
- phone: primary device for this user
- signup_date: date of account registration; in the form ‘YYYY­MM­DD’
- last_trip_date: the last time this user completed a trip; in the form ‘YYYY­MM­DD’ 
- avg_dist: the average distance *(in miles) per trip taken in the first 30 days after signup 
- avg_rating_by_driver: the rider’s average rating over all of their trips 
- avg_rating_of_driver: the rider’s average rating of their drivers over all of their trips 
- surge_pct: the percent of trips taken with surge multiplier > 1
- avg_surge: The average surge multiplier over all of this user’s trips 
- trips_in_first_30_days: the number of trips this user took in the first 30 days after signing up
- luxury_car_user: True if the user took an luxury car in their first 30 days; False otherwise
- weekday_pct: the percent of the user’s trips occurring during a weekday

Data EDA
- Numeric variables
  Histograms
    Interpret the key results for Histogram
    Step 1: Assess the key characteristics
    Peaks and spread, Symmetry
    Step 2: Look for multiple modes and outliers
    Multiple modes, outliers
    Step 3: Fit a theoretical distribution
    Distribution fit
    Step 4: Assess and compare groups
    Centers Spreads
  Scatter Plots
    Interpret the key results for Scatter Plots
    Step 1: Look for model relationships and assess the strength
    Step 2: Look for group-related patterns
    Step 3: Look for other patterns
-Categorical variables
  Bar Chart
    Interpret the key results for Bar Chart
    Step 1: Compare groups
    Step 2: Compare groups within groups
