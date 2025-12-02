# Hotel Booking Analysis

## Project Overview

The **Hotel Booking Analysis** project analyzes a dataset of hotel bookings with the goal of providing valuable insights into booking behavior, cancellation patterns, and customer preferences. This analysis will help hotel management optimize pricing, reduce cancellations, and improve guest satisfaction by understanding key trends and patterns.

## Objectives

- **Understand booking trends:** Analyze seasonality and identify peak booking months.
- **Cancellation analysis:** Explore the factors that contribute to booking cancellations and the cancellation rate.
- **ADR (Average Daily Rate) analysis:** Investigate how the price of rooms varies over time.
- **Geographical insights:** Discover the most common countries where guests come from.
- **Correlation Analysis:** Examine correlations between different numerical features and cancellations.

## Key Findings

1. **Cancellation Rates:** A significant portion of bookings are canceled. Further analysis is required to understand the drivers behind cancellations (e.g., lead time, room type).
2. **Seasonality:** Peak booking times are during the summer months (July and August), which suggests higher demand during holidays.
3. **ADR Insights:** The average daily rate (ADR) tends to fluctuate based on the season, with higher rates during peak months.
4. **Geographic Insights:** Guests from Portugal (PRT) are the most frequent visitors, followed by guests from other European countries.
5. **Booking Behavior:** Direct bookings are more frequent than those through agents or third-party channels.

## Data Cleaning and Preprocessing

The dataset was cleaned by:
- Dropping unnecessary columns with too many missing values.
- Filling missing values in columns like `country` and `agent` with appropriate replacements.
- Removing bookings where no guests were present (i.e., no adults, children, or babies).
- Filtering out canceled bookings to focus only on actual guest stays for certain analyses.

## Tools and Libraries Used

- **Python**: Programming language used for analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For interactive code execution and analysis.

# Power BI Model

   You can see a model of Power BI that upload with .pbix format 

## How to Run the Project

1. Clone this repository:


bash
   git clone https://github.com/farzadjenab/Hotel-Booking-Analysis.git
   
   
2. Install the necessary libraries:

content_copy
bash
   pip install pandas matplotlib seaborn
   
3. Open the hotel_bookings_analysis.ipynb notebook and run the cells to begin your analysis.

##Key Visualizations

...Cancellation Rate Distribution: Visualizes the proportion of canceled versus non-canceled bookings.
...Hotel Type Popularity: Compares the number of bookings for resort and city hotels.
...Monthly Booking Trends: Shows how the number of bookings changes throughout the year.
...ADR Trend: Displays how the average daily rate fluctuates month-to-month.
...Geographical Insights: Bar plot showing the top countries of origin for hotel guests.

##How to Contribute
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.


