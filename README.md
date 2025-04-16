# Remove Duplicate Records using SQL - Data Cleaning

This project demonstrates how to identify and remove duplicate records from a relational database using SQL scripts. Duplicate data can lead to inconsistencies in reporting, inaccurate data analysis, and increased storage requirements. This SQL script provides an efficient solution to clean your data by targeting and deleting duplicate rows based on specific criteria.

![image](https://github.com/user-attachments/assets/c4021174-9100-4725-bcbe-42f9aa66164e)


## 🧠 Project Objective

To develop a clean, reusable SQL script that identifies and removes duplicate rows from a database table while preserving original entries.

## 📂 Files Included

- `Remove Duplicate Data.sql`: Contains the SQL queries for detecting and removing duplicates from a sample table.

## ⚙️ Technologies Used

- SQL (Structured Query Language)
- Any SQL-compliant RDBMS (e.g., MySQL, PostgreSQL, Oracle, SQL Server)

## 🛠️ How It Works

The SQL script performs the following tasks:
1. Detects duplicate records based on selected column(s).
2. Retains only the first occurrence using ROW_NUMBER or similar logic.
3. Deletes the extra occurrences to maintain clean data.

## 🚀 How to Use

1. Clone this repository or download the `.sql` file.
2. Connect to your database using your preferred SQL client.
3. Backup your data (recommended).
4. Run the script against your database table.
5. Verify the results.

## 📌 Example Use Case

Suppose you have a table `employees` where multiple entries of the same employee exist. This script will remove all duplicate rows while keeping one original record.

## ✅ Best Practices

- Always back up your data before running delete operations.
- Test the script on a small subset of data first.
- Modify the column criteria in the script according to your table's structure.

## 📧 Contact

For any queries or suggestions, feel free to reach out!

---

