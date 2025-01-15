# Analyzing EV Charging Habits

This project analyzes data from shared and private EV charging sessions to uncover user habits and charging station performance. The main goals include identifying the most active garages, the most popular charging times, and users with long charging durations.\

## Key Insights
- **Most active garages:** Analyzed garages based on the number of unique users.
- **Popular charging times:** Identified peak hours for shared charging sessions.
- **Users with long sessions:** Highlighted users with average charging durations over 10 hours.

## Project Highlights
- SQL queries were used to extract meaningful insights from the dataset.
- The analysis focused on user habits and garage performance metrics.

## How to Use
1. Clone this repository.
2. Open the provided Jupyter Notebook to review the queries and results.

## Dataset
The analysis is based on the `charging_sessions` table, which contains data on EV charging sessions, including user types, charging durations, and station usage.\

## Results
- The results are saved as three separate queries in the notebook:
  - `unique_users_per_garage`
  - `most_popular_shared_start_times`
  - `long_duration_shared_users`

Feel free to explore the code and adapt it to your own analysis needs.
