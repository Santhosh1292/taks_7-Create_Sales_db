# taks_7-Create_Sales_db
# Sales Data Analysis with SQLite and Pandas

This project demonstrates a simple data analysis workflow using **SQLite** for storing and querying mock sales data, and **Pandas + Matplotlib** for data manipulation and visualization—all executed in Google Colab.

## 🔧 Steps Performed

1. **Environment Setup**
   - Python libraries installed: `pandas`, `matplotlib`
   - Used an in-memory SQLite database for quick access

2. **Database Creation**
   - Created a `sales` table with fields: `id`, `date`, `region`, `product`, `quantity`, `price`
   - Populated it with sample sales data

3. **SQL Queries**
   - Fetched all records from the table
   - Calculated total sales per region
   - Found the most sold product by quantity

4. **Data Analysis with Pandas**
   - Loaded SQL results into a DataFrame
   - Computed a new `total` column (`quantity * price`)
   - Grouped and summarized sales by region

5. **Data Visualization**
   - Created a bar chart using Matplotlib to show **Total Sales by Region**


## 🚀 Tools Used
- Google Colab
- Python 3
- SQLite
- Pandas
- Matplotlib
- ![Screenshot 2025-06-15 200115](https://github.com/user-attachments/assets/b3627bd1-0f11-4916-a090-1b5e73d4774e)
