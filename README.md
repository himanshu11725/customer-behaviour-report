# customer-behaviour-report
data analytics project showcasing customer behaviour analysis using python, SQL, and power BI
# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, and business opportunities. It follows an end-to-end data analytics workflow, starting with data loading and exploratory data analysis (EDA) in Python, followed by data cleaning, SQL analysis using MySQL Server, and interactive dashboard development in Power BI.

The project also includes a detailed analytical report and a presentation created using Gamma to communicate key findings and business recommendations.

**Objective:** Transform raw customer data into meaningful insights that support data-driven business decisions.

## Dataset

The dataset contains customer shopping information, including demographic details, purchase history, product categories, discounts, shipping preferences, subscription status, and review ratings.

- **Total records:** 3,900
- **Total columns:** 18
- **Missing values:** 37 in the review rating column

The dataset was explored and prepared before conducting further analysis.

## Tools & Technologies

- **Python:** Data loading, exploration, cleaning, and transformation
- **Pandas & NumPy:** Data manipulation and analysis
- **Matplotlib & Seaborn:** Data visualization during EDA
- **MySQL Server:** SQL queries, aggregations, and business analysis
- **Power BI:** Interactive dashboard development
- **Gamma:** Presentation creation
- **Microsoft Word:** Analytical report documentation
- **Jupyter Notebook:** Python development environment
- **GitHub:** Project documentation and version control

## Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Inspected the dataset structure, column names, and data types.
- Reviewed initial records and summary statistics.

### 2. Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical variables.
- Identified missing values and potential data quality issues.
- Examined customer demographics, purchasing patterns, and product preferences.
- Identified trends and potential outliers.

### 3. Data Cleaning & Preparation
- Handled missing review ratings using category-wise median imputation.
- Standardized column names.
- Created an age-group feature for customer segmentation.
- Transformed purchase-frequency information for analysis.
- Reviewed redundant columns and prepared the cleaned dataset for SQL analysis.

### 4. SQL Analysis Using MySQL Server
- Loaded the cleaned data into MySQL Server.
- Used SQL queries to answer business questions.
- Applied filtering, aggregation, grouping, sorting, and ranking techniques.
- Analyzed revenue by gender and age group.
- Compared subscribers with non-subscribers.
- Identified frequently purchased products and products with high average ratings.
- Examined discount usage, shipping preferences, and repeat customers.

### 5. Power BI Dashboard
- Connected the analyzed customer data to Power BI.
- Created KPI cards and interactive charts.
- Developed visualizations for customer demographics, revenue, product categories, and subscription status.
- Added slicers to explore results by gender, category, subscription status, and shipping type.

### 6. Report & Presentation
- Prepared a structured analytical report documenting the methodology, findings, and recommendations.
- Created a presentation using Gamma to communicate the project outcomes in a clear and visual format.

## Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior.

**Key Performance Indicators (KPIs):**
- Total customers: 3,900
- Average purchase amount: $59.76
- Average review rating: 3.75 out of 5

**Dashboard Highlights:**
- Revenue distribution across customer segments.
- Purchasing patterns across age groups and genders.
- Product popularity and customer review ratings.
- Subscription status and repeat purchasing behavior.
- Discount usage and shipping preferences.

> **Dashboard Preview:** Add a screenshot of your Power BI dashboard here.

## Key Results & Insights

- The dataset contains 3,900 customer purchase records and 18 columns.
- Young Adult customers generated the highest total revenue among the age groups analyzed.
- Male customers contributed higher total revenue than female customers in the dataset.
- Non-subscribers represented approximately 73% of the customer records.
- Subscribers and non-subscribers had similar average purchase amounts.
- Gloves had the highest average review rating among the five products highlighted in the analysis.
- Hats had the highest discount usage rate among the products compared.
- Loyal customers represented the largest group under the project's customer segmentation.
- Express-shipping customers had a slightly higher average purchase amount than Standard-shipping customers.

These findings can help a business investigate customer engagement, promotional strategies, product positioning, and potential subscription growth opportunities.

## Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Improve subscription conversion:** Test relevant subscription benefits for non-subscribers.
2. **Strengthen customer loyalty:** Explore loyalty programs for repeat customers.
3. **Optimize discount strategies:** Evaluate discount effectiveness alongside profitability.
4. **Promote popular products:** Use product ratings and purchase volumes to guide campaigns.
5. **Personalize marketing:** Investigate customer segments and purchasing preferences to develop targeted campaigns.

These recommendations should be validated using additional business data and performance tracking.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_data.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_analysis_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Behavior_Analysis_Report.docx
│
├── presentation/
│   └── customer_behavior_presentation.pdf
│
└── README.md
```

*Update the folder and file names to match the actual contents of your repository.*

## How to Run

### Prerequisites
- Python 3.x
- Jupyter Notebook
- MySQL Server
- Power BI Desktop
- Required Python libraries

### Step 1: Clone the repository

```bash
git clone <your-github-repository-url>
cd Customer-Shopping-Behavior-Analysis
```

### Step 2: Install Python libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy mysql-connector-python
```

### Step 3: Load and analyze the dataset

Open Jupyter Notebook and run the notebook in the `notebooks/` folder.

Perform data exploration, handle missing values, clean the data, and prepare the final dataset.

### Step 4: Connect to MySQL Server

- Start MySQL Server.
- Create a database for the project.
- Import the cleaned dataset into a table.
- Update the database connection settings in your Python or SQL workflow.
- Execute the SQL queries provided in the `sql/` folder.

**Security note:** Keep database credentials private. Use environment variables or a local configuration file excluded from GitHub instead of committing passwords.

### Step 5: Open the Power BI dashboard

- Open Power BI Desktop.
- Load the provided `.pbix` file or connect to your MySQL database.
- Update the data source settings if required.
- Refresh the data to view the dashboard.

### Step 6: Review the report and presentation

Open the report in Microsoft Word and the presentation in a compatible PDF or PowerPoint viewer.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Python and Pandas
- SQL querying and business analysis
- MySQL database integration
- Data visualization and dashboard development
- KPI analysis and customer segmentation
- Business reporting and presentation
- Data-driven decision-making

## Conclusion

This project demonstrates an end-to-end data analytics workflow by combining Python, MySQL Server, Power BI, and business reporting. It highlights the ability to transform raw data into structured analysis, communicate findings effectively, and recommend practical actions based on customer shopping behavior.
