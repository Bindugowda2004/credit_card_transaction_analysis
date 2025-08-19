# Credit Card Transactions Analysis Project

### Overview
This project analyzes credit card transactions in India to provide insights into consumer spending behavior. The dataset contains various attributes such as city, date, card type, expense type, gender, and transaction amount. We used SQL within Python (using `sqlite3`) to answer several analytical questions about the data, leveraging SQL functions, window functions, and common table expressions (CTEs).

### Dataset
The dataset (`dataset_transactions.csv`) includes the following columns:
- **City**: The city where the transaction took place.
- **Date**: The date of the transaction.
- **Card Type**: The type of credit card used (Gold, Silver, Platinum, etc.).
- **Exp Type**: The type of expense (Bills, Fuel, etc.).
- **Gender**: The gender of the cardholder.
- **Amount**: The amount spent in the transaction.

### Tasks Completed
1. **Top 5 Cities by Spending**  
   We calculated the top 5 cities with the highest total spending and their percentage contribution to the overall spend.
   
2. **Highest Spending Month by Card Type**  
   For each card type, we identified the month with the highest spending and the total amount spent in that month.

3. **Cumulative Spend of 1,000,000 per Card Type**  
   We retrieved the transaction details where the cumulative spend reached 1,000,000 for each card type.

4. **Lowest Percentage Spend for Gold Card**  
   The city with the lowest percentage contribution to total spending using Gold cards was identified.

5. **Highest and Lowest Expense Type per City**  
   For each city, we extracted the expense type with the highest and lowest total spend.

6. **Female Spending Contribution by Expense Type**  
   We calculated the percentage contribution of female cardholders' spending for each expense type.

7. **Highest Month-over-Month Growth in January 2014**  
   We identified the card type and expense type combination that saw the highest month-over-month spending growth in January 2014.

8. During weekends which city has highest total spend to total no of transaction's ratio?

9. Which city took least number of days to reach its 500th transaction after first transaction in that city?


### Technologies Used
- **Python**: To manipulate and analyze the dataset using libraries like `pandas` and `sqlite3`.
- **SQL**: For querying and aggregating the dataset within a local SQLite database.
- **Jupyter Notebook**: Used to write and run the Python code.

### Files
- **dataset_transactions.csv**: The dataset used in the project.
- **output_task1.csv - output_task7.csv**: The results of each task, saved as CSV files after querying the data.

Conclusion
This project demonstrates how SQL can be effectively used within Python for data analysis on large datasets. Through SQL queries, we were able to extract key insights about credit card usage patterns, helping us understand consumer behavior in terms of city, card type, and expense type. 

---

Feel free to explore the code and dataset to dive deeper into credit card transaction analytics!!
