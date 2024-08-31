# Zomato-Data-Analysis-Project

## Introduction
This project involves analyzing a dataset from Zomato, which includes information about various restaurants, such as their names, online ordering capabilities, table booking options, ratings, votes, approximate cost for two people, and the type of listing. The goal is to perform data cleaning, preprocessing, and visualization to gain insights into the restaurant data.

## Dataset
The dataset used in this project is titled Zomato data.csv and contains the following columns:

name: Name of the restaurant.
online_order: Whether the restaurant accepts online orders (Yes/No).
book_table: Whether the restaurant allows table booking (Yes/No).
rate: The rating of the restaurant (e.g., 4.1/5).
votes: Number of votes received by the restaurant.
approx_cost(for two people): Approximate cost for two people.
listed_in(type): The type of listing (e.g., Buffet).

## Project Structure
### Step 1 - Importing Libraries
Required libraries such as pandas, numpy, matplotlib, and seaborn are imported for data manipulation and visualization.

### Step 2 - Create the Data Frame
The dataset is loaded into a Pandas DataFrame for analysis.

### Data Preprocessing
The rate column, originally stored as a string (e.g., 4.1/5), is converted to a numeric format to facilitate analysis.

### Data Visualization
Various visualizations are created to explore the data, such as the distribution of restaurant types.

## Setup Instructions
To run this project locally, follow these steps:

### Clone the Repository (if applicable):
git clone https://github.com/Nizam704/Zomato-Data-Analysis-Project.git

### Install Required Libraries:
pip install pandas numpy matplotlib seaborn

Run the Jupyter Notebook:

Open the notebook Zomato Project.ipynb using Jupyter Notebook or Jupyter Lab.
Execute the cells to perform the analysis.

## Conclusions

The data shows a diverse range of restaurant types, with varying popularity indicated by the number of votes and ratings.
The visualizations provide insights into the distribution and characteristics of restaurants listed on Zomato.
