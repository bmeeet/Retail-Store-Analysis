# Retail Store Sales Analysis

## Overview

This project provides an in-depth analysis of retail store sales data, leveraging Python and the Plotly library for interactive visualizations. The analysis covers key aspects such as sales and profit trends across different categories, sub-categories, time periods (monthly), and customer segments. The goal is to extract actionable insights that can help improve business strategies and decision-making.

## Key Features

-   **Descriptive Statistics:** Comprehensive overview of the dataset's statistical properties.
-   **Date-Based Analysis:** Extraction of key temporal features (month, year, day of week) from order dates to facilitate time-series analysis.
-   **Monthly Sales and Profit Trends:** Interactive line charts illustrating monthly sales and profit variations.
-   **Category and Sub-Category Analysis:** Detailed breakdown of sales and profit by product category and sub-category using pie and bar charts.
-   **Customer Segment Analysis:** Comparative analysis of sales and profit across different customer segments.
-   **Sales-to-Profit Ratio Analysis:** Calculation and examination of the sales-to-profit ratio for each customer segment to identify the most profitable segments.

## Technologies Used

-   **Python:** The primary programming language used for data manipulation and analysis.
-   **pandas:** A powerful data analysis library for data manipulation and handling.
-   **Plotly:** An interactive visualization library for creating dynamic and informative charts.

## Setup and Installation

1.  **Prerequisites:**
    -   Python
    -   pip (Python package installer)

2.  **Install Dependencies:**

    Clone the repository and navigate to the project directory:

    ```bash
    git clone [repository_url]
    cd [project_directory]
    ```

    Install the required Python packages using pip:

    ```bash
    pip install pandas plotly
    ```

3.  **Dataset:**

    -   Ensure that the dataset file (`Sample - Superstore.csv`) is located in the same directory as the analysis notebook.

## Data Description

The dataset (`Sample - Superstore.csv`) contains transactional data for a retail store. Key columns include:

-   `Order Date`: Date when the order was placed.
-   `Ship Date`: Date when the order was shipped.
-   `Category`: Category of the product.
-   `Sub-Category`: Sub-category of the product.
-   `Sales`: Sales amount.
-   `Profit`: Profit amount.
-   `Segment`: Customer segment.

## Usage

1.  **Open the Analysis Notebook:**

    -   Open the `Retail Store Sales.ipynb` file using Jupyter Notebook, VS Code, or any other compatible environment.

2.  **Execute the Notebook Cells:**

    -   Run the notebook cells sequentially to perform the analysis and generate the visualizations.
    -   Each cell contains code and markdown explanations to guide you through the analysis process.

## Analysis Steps

1.  **Data Loading and Inspection:**

    -   Load the dataset using pandas.
    -   Display the first few rows of the dataset to understand its structure.
    -   Check the data types and missing values.

2.  **Data Preprocessing:**

    -   Convert the `Order Date` and `Ship Date` columns to datetime format.
    -   Extract temporal features such as `Order Month`, `Order Year`, and `Order Day of Week`.

3.  **Exploratory Data Analysis (EDA):**

    -   **Monthly Sales Analysis:**
        -   Group sales data by month and visualize the monthly sales trend using a line chart.
    -   **Sales Analysis by Category:**
        -   Group sales data by category and visualize the sales distribution using a pie chart.
    -   **Sales Analysis by Sub-Category:**
        -   Group sales data by sub-category and visualize the sales distribution using a bar chart.
    -   **Monthly Profit Analysis:**
        -   Group profit data by month and visualize the monthly profit trend using a line chart.
    -   **Profit Analysis by Category:**
        -   Group profit data by category and visualize the profit distribution using a pie chart.
    -   **Profit Analysis by Sub-Category:**
        -   Group profit data by sub-category and visualize the profit distribution using a bar chart.
    -   **Sales and Profit Analysis by Customer Segment:**
        -   Group sales and profit data by customer segment and visualize the sales and profit distribution using a grouped bar chart.
    -   **Sales-to-Profit Ratio Analysis:**
        -   Calculate the sales-to-profit ratio for each customer segment.
        -   Display the results in a table.


## Visualizations

The project includes the following interactive visualizations:

-   **Line Charts:**
    -   Monthly Sales Trend
    -   Monthly Profit Trend
-   **Pie Charts:**
    -   Sales Distribution by Category
    -   Profit Distribution by Category
-   **Bar Charts:**
    -   Sales Distribution by Sub-Category
    -   Profit Distribution by Sub-Category
    -   Sales and Profit by Customer Segment

## Results and Insights

The analysis provides several key insights into the retail store's sales performance:

-   Identification of the most profitable months, categories, sub-categories, and customer segments.
-   Understanding of the sales-to-profit ratio for different customer segments.
-   Trends and patterns in sales and profit over time.
