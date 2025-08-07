# SQL Project 1 – Customer and Product Analysis

This project uses Microsoft SQL Server and the AdventureWorksLT sample database (`SalesLT` schema) to perform key business analyses on customers, orders, and products.

## 🔍 Key Analyses

- **Customer Revenue Segmentation**: Using NTILE to divide customers into 4 segments based on total revenue.
- **Most Recent Orders**: Identifying products sold in the latest order date.
- **Reusable View**: Creating a view for customer segmentation to simplify repeated queries.
- **Top Products by Category**: Using RANK() to find the top 3 revenue-generating products in each category.

## 💾 Technologies Used

- Microsoft SQL Server
- T-SQL (Transact-SQL)
- AdventureWorksLT Sample Database



## 📊 Example Output

Segmented customers with total revenue:
| CustomerID | Name           | Revenue  | Segment |
|------------|----------------|----------|---------|
| 29825      | John Smith     | 4500.00  | 1       |
| 29826      | Jane Doe       | 2300.00  | 2       |

## 📈 Future Improvements

- Add stored procedures for automation.
- Connect to a BI tool (e.g., Power BI) for visualization.

---

