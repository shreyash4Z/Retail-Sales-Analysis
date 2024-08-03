# Retail-Sales-Analysis

## Project Overview

This project involves analyzing supermarket sales data to derive insights and trends. The data is sourced from a CSV file containing detailed sales records. The analysis includes data cleaning, transformation, and visualization to understand various aspects of the sales data.

## Dataset

The dataset contains the following columns:

- *Invoice ID*: Unique identifier for each invoice
- *Branch*: Branch of the supermarket (A, B, C)
- *City*: City where the branch is located
- *Customer type*: Type of customer (Member, Normal)
- *Gender*: Gender of the customer
- *Product line*: Category of products purchased
- *Unit price*: Price per unit of the product
- *Quantity*: Number of units purchased
- *Tax 5%*: Tax amount (5% of the total price)
- *Total*: Total amount paid (including tax)
- *Date*: Date of purchase
- *Time*: Time of purchase
- *Payment*: Payment method used (Cash, Credit card, Ewallet)
- *COGS*: Cost of goods sold
- *Gross margin percentage*: Gross margin percentage
- *Gross income*: Gross income from the sale
- *Rating*: Customer rating of the purchase experience

## Data Cleaning and Preparation

The data cleaning steps include:

- Handling missing values
- Converting data types
- Removing duplicates (if any)
- Normalizing date and time formats

## Data Visualization

The visualization step includes creating various plots to understand:

- Sales distribution across different branches and cities
- Sales trends over time
- Customer demographics (gender and customer type)
- Popular product lines
- Payment methods used

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python (>= 3.6)
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/supermarket-sales-analysis.git
   
2. Navigate to the project directory:
   ```bash
   cd supermarket-sales-analysis
   
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Project-2.ipynb
   
2. Run the cells sequentially to perform data cleaning and visualization.

## Results

The analysis reveals insights such as:

- The most popular product lines
- Sales trends over different times and days
- Payment methods preferred by customers
- Customer satisfaction ratings.
