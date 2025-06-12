# Restaurant Data Insights 

This project explores and visualizes key trends in restaurant data, including customer reviews, pricing, and food types. It uses Python libraries to clean, analyze, and draw insights from real-world food service data.

##  Dataset

The dataset used is a cleaned CSV file: `resturantsframe-Clean.csv`, containing fields such as:

- `restaurant_name`
- `review_score`
- `number_of_reviews`
- `price_range`
- `food_type`

##  Data Preprocessing

Before visualizations, the notebook performs the following:
- Cleans `review_score` to numeric float format.
- Converts `number_of_reviews` to integer.
- Parses `price_range` into `price_min`, `price_max`, and `price_avg`.
- Drops rows with missing key fields.

##  Visual Analysis Goals

- Relationship between **average price** and **review score**
- Popular **food types**
- Correlation between **number of reviews** and **restaurant rating**
- Outlier detection and trends in pricing

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

