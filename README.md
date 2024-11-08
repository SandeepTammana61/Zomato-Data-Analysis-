Zomato Data Analysis Project
Project Overview
This project focuses on analyzing a dataset containing information about various restaurants listed on Zomato. The primary goal is to explore and understand trends, customer behavior, and preferences through data preprocessing, cleaning, and visualization.

Dataset Information
The dataset contains information on:

Restaurant names
Availability of online orders and table booking
Customer ratings and votes
Approximate cost for two people
Restaurant type (e.g., Buffet, Dining, Cafes)
Key Steps and Findings
1. Data Preprocessing & Cleaning
Converted the rate column from a string format (e.g., 4.1/5) to a numeric float value for analysis.
Verified the data structure using dataframe.info() and checked for null values.
2. Analysis & Visualizations
Majority Restaurant Type
Visualization: Used a countplot to display the distribution of restaurant types.
Finding: The majority of restaurants are categorized as "Dining."
Voting Analysis by Category
Visualization: Grouped data by listed_in(type) and summed votes for each category, visualized with a line plot.
Finding: "Dining" restaurants received the highest number of votes.
Rating Distribution
Visualization: Created histograms to show the distribution of restaurant ratings, using bins of 5 and 20.
Finding: Most ratings fall between 3.5 and 4.
Expenditure Analysis
Visualization: Used a count plot to analyze the distribution of approximate costs for two people.
Finding: Couples typically spend around 300 currency units, with occasional spending reaching 950 units.
Online vs. Offline Ratings
Visualization: Used a boxplot to compare ratings for online and offline orders.
Finding: Online orders generally receive higher ratings compared to offline ones.
Offline vs. Online Orders by Type
Visualization: Created a heatmap to visualize the distribution of online and offline orders across restaurant types.
Finding: Dining restaurants primarily cater to offline orders, while cafes tend to receive more online orders.
Tools Used
Libraries:
pandas for data manipulation and analysis
numpy for numerical operations
matplotlib and seaborn for data visualization
How to Run the Project
Clone the repository.
Install the required libraries:
Copy code
pip install pandas numpy matplotlib seaborn
Run the Python script or Jupyter Notebook containing the code.
Conclusions
Most restaurants in the dataset are "Dining" establishments.
Dining restaurants tend to receive the most votes.
The majority of restaurant ratings lie between 3.5 and 4.
Couples generally spend around 300 currency units, with rare high spending cases.
Online orders receive higher ratings compared to offline ones.
Dining restaurants tend to have more offline orders, while cafes receive more online orders.
