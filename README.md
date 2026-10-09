# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI. It explores customer demographics, purchasing patterns, product categories, discounts, and spending behavior to derive meaningful business insights.

The project follows an end-to-end data analytics workflow, from raw data exploration and cleaning to database analysis and visualization.

## Dataset

**Dataset:** `customer_shopping_behavior.csv`

The dataset contains customer demographics, product categories, purchase amounts, review ratings, discount information, and purchase frequency.

## Tools & Technologies

- **Python** – Data analysis and preprocessing
- **Pandas** – Data manipulation and cleaning
- **Jupyter Notebook** – Analysis and documentation
- **PostgreSQL** – Database storage and SQL analysis
- **SQLAlchemy & Psycopg2** – Database connectivity
- **Power BI** – Interactive dashboards and visualizations
- **Gamma** – Presentation creation

## Project Workflow

1. Load the dataset into Python using Pandas.
2. Perform Exploratory Data Analysis (EDA).
3. Identify and handle missing values.
4. Clean and standardize column names.
5. Perform feature engineering.
6. Load the cleaned dataset into PostgreSQL.
7. Execute SQL queries to answer business questions.
8. Build an interactive Power BI dashboard.
9. Prepare a project report and presentation using Gamma.

## Data Cleaning & Feature Engineering

- Examined dataset structure, data types, and missing values.
- Handled missing review ratings using category-wise median values.
- Standardized column names for easier analysis.
- Created customer age groups for segmentation.
- Converted purchase frequency categories into numerical day values.
- Removed redundant columns where appropriate.

## SQL Analysis

SQL queries are used to explore customer purchasing behavior and answer business questions:

- What is the total purchase amount by gender?
- Which product categories have the highest purchase amounts?
- What is the average purchase amount?
- How does spending vary across age groups?
- Which customers purchase most frequently?
- How are discounts associated with purchasing behavior?
- Which product categories receive the highest ratings?

## Power BI Dashboard

The dashboard is designed to present key metrics and visualizations, including:

- Total Purchase Amount
- Average Purchase Amount
- Customer Distribution by Gender
- Customer Segmentation by Age Group
- Purchase Amount by Product Category
- Average Review Ratings
- Purchase Frequency Distribution
- Discount Usage Analysis

Interactive filters and slicers enable users to explore different customer segments and purchasing patterns.

## Results & Business Insights

The analysis aims to identify customer spending patterns, compare product categories, understand purchase frequency, and explore differences across customer segments.

**Key findings:** Add the actual numerical results and insights after completing the SQL analysis and Power BI dashboard.

## Project Report & Presentation

The project report documents the methodology, data preparation, SQL analysis, visualizations, and business findings.

A presentation created using Gamma summarizes the project objectives, analytical workflow, dashboard, and key insights.

## How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Customer-Shopping-Behavior-Analysis
```

### 2. Install Dependencies

```bash
pip install pandas sqlalchemy psycopg2-binary jupyter
```

### 3. Add the Dataset

Place `customer_shopping_behavior.csv` in the project directory.

### 4. Run the Notebook

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells sequentially.

### 5. Configure PostgreSQL

Create a PostgreSQL database named `customer_behavior` and configure your database credentials.

```python
from sqlalchemy import create_engine

engine = create_engine(
    "postgresql+psycopg2://username:password@localhost:5432/customer_behavior"
)
```

Run the database-loading section of the notebook to load the cleaned dataset.

**Security:** Never commit database passwords or other sensitive credentials to GitHub.

### 6. Build the Power BI Dashboard

1. Open Power BI Desktop.
2. Select **Get Data → PostgreSQL database**.
3. Enter your server and database details.
4. Load the customer table.
5. Create visualizations, filters, and slicers.
6. Save the dashboard as a `.pbix` file.

## Skills Demonstrated

Python | Pandas | EDA | Data Cleaning | Feature Engineering | SQL | PostgreSQL | Power BI | Data Visualization | Business Analytics

## Author

**GUNDU HARSHITH**

- GitHub: https://github.com/HARSHITH-GUNDU
