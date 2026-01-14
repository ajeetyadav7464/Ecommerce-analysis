## 🛒 Ecommerce Sales Data Analysis 📊

This project involves an in-depth analysis of an eCommerce dataset stored in a MySQL database using Python. The primary objective is to extract meaningful business insights from raw transactional data to guide business decisions and highlight key sales trends.

### 📌 Key Features

- 🔗 Connected Jupyter Notebook to a MySQL database using `mysql-connector-python`.
- 📦 Analyzed six core tables: `customers`, `orders`, `order_items`, `sellers`, `payments`, and `products`.
- 🧼 Handled missing data by applying logical imputation techniques:
  - Replaced null product categories with "others"
  - Assigned "not defined" to missing dimension fields
- 📈 Generated visual insights:
  - Yearly and monthly sales trends
  - Drop in September order count with hypothesized causes
  - Category and regional sales performance
- 🐼 Used `pandas` for data wrangling and transformation
- 🧠 Used `matplotlib` and `seaborn` for creating insightful visualizations

### 🛠 Technologies Used

- MySQL (Database)
- Python (Jupyter Notebook)
- Pandas
- MySQL Connector
- Matplotlib
- Seaborn

> ⚠️ Note: Year 2016 was partially excluded due to incomplete data across all months.

