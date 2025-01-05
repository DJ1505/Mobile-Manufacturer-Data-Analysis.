# Mobile Manufacturer Data Analysis  
This project showcases advanced SQL-based data analysis performed on a mobile manufacturer dataset. The analysis answers various business queries, providing insights into sales performance, customer behavior, and manufacturer trends.  

## Table of Contents  
- [Project Overview](#project-overview)  
- [Database Structure](#database-structure)  
- [Key Queries and Insights](#key-queries-and-insights)  
- [Setup Instructions](#setup-instructions)  
- [Technologies Used](#technologies-used)  
- [License](#license)  

---

## Project Overview  
The aim of this project is to analyze mobile manufacturing data using SQL and answer business-critical questions. This includes identifying top-performing manufacturers, customer spending patterns, sales trends, and more.  

The dataset includes the following tables:  
- **dim_manufacturer**: Manufacturer details.  
- **dim_model**: Mobile model details.  
- **dim_customer**: Customer information.  
- **dim_location**: Sales location data.  
- **dim_date**: Date and time details.  
- **fact_transactions**: Transaction data including quantities, prices, and sales.  

---

## Database Structure  
The analysis is based on a star schema design:  
- **Fact Table**: `fact_transactions`  
- **Dimension Tables**:  
  - `dim_manufacturer`  
  - `dim_model`  
  - `dim_customer`  
  - `dim_location`  
  - `dim_date`  

---

## Key Queries and Insights  

1. **States with Transactions (2015-Present)**  
   - Query: Identifies states with transactions between 2015 and today.  
   - Insight: Helps in understanding geographic sales distribution.  

2. **Top State for Samsung Sales**  
   - Query: Determines the state with the highest Samsung sales.  
   - Insight: Identifies key markets for Samsung.  

3. **Transaction Count by Model and Location**  
   - Query: Counts transactions per model, ZIP code, and state.  
   - Insight: Highlights high-demand regions for specific models.  

4. **Lowest Priced Model**  
   - Query: Fetches the model with the lowest unit price.  
   - Insight: Useful for price-based marketing strategies.  

5. **Top 5 Manufacturers and Average Model Price**  
   - Query: Finds the top 5 manufacturers and their average model price.  
   - Insight: Assesses competitive pricing strategies.  

6. **High-Spending Customers (2009)**  
   - Query: Identifies customers with average spending above $500 in 2009.  
   - Insight: Recognizes valuable customer segments.  

7. **Top Models Consistently Popular (2008-2010)**  
   - Query: Identifies models in the top 5 sales list for 2008, 2009, and 2010.  
   - Insight: Shows consistently high-performing models.  

8. **Manufacturer with Highest Revenue**  
   - Query: Finds the manufacturer generating the highest total revenue.  
   - Insight: Highlights dominant players in the market.  

9. **Manufacturers Active in 2010 but Not 2009**  
   - Query: Lists manufacturers active in 2010 but absent in 2009.  
   - Insight: Tracks new entrants or re-entries into the market.  

10. **Customer Average Spending and Quantity (2005 vs. 2018)**  
    - Query: Compares average spending and quantity purchased per customer between 2005 and 2018.  
    - Insight: Analyzes customer behavior changes over time.  

---

## Setup Instructions  

1. **Database Setup**  
   - Ensure you have access to an SQL database (e.g., MySQL, PostgreSQL).  
   - Load the provided dataset into the database using the table structures and sample data.  

2. **Execute Queries**  
   - Copy and paste the provided SQL queries into your database client (e.g., MySQL Workbench, pgAdmin) to analyze the data.  

3. **Results**  
   - Visualize or export the results for further interpretation.  

---

## Technologies Used  
- **SQL**: For data analysis and querying.  
- **Database Management Systems**: MySQL/PostgreSQL.  
- **Data Visualization**: Use tools like Tableau or Power BI for presenting results (optional).  

---

## License  
This project is open-source and available under the [MIT License](LICENSE).  

---

## Contact  
For further inquiries or collaboration opportunities, please reach out to:  
- **Email**: [Dhananjaykumartyagi@gmail.com](mailto:Dhananjaykumartyagi@gmail.com)  
- **LinkedIn**: [Dhananjay Tyagi](https://www.linkedin.com/in/dhananjaytyagi/)  

