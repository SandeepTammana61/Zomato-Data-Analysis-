Zomato Data Analysis Project
Project Overview
This project focuses on analyzing restaurant data from Zomato to gain insights into customer behavior, restaurant ratings, expenditure patterns, and preferences for online vs. offline orders. The analysis includes data preprocessing, cleaning, and visualization to uncover meaningful trends and patterns.

Dataset Information
The dataset contains information on:

name: Restaurant name
online_order: Indicates if online ordering is available (Yes/No)
book_table: Indicates if table booking is available (Yes/No)
rate: Customer rating, converted to a numeric value for analysis
votes: Number of customer votes
approx_cost(for two people): Approximate cost for two people
listed_in(type): Type of restaurant (e.g., Buffet, Dining, Cafes)
Project Steps and Key Findings
1. Data Preprocessing and Cleaning
Converted the rate column from a string format (e.g., 4.1/5) to a numeric float value for analysis.
Verified the data structure and checked for null values.
2. Data Analysis and Visualizations
Majority Restaurant Type
Used visualization to show the distribution of restaurant types.
Finding: Most restaurants are categorized under "Dining."
Voting Analysis by Category
Grouped data by restaurant type to analyze total votes received by each category.
Finding: "Dining" restaurants received the highest total votes.
