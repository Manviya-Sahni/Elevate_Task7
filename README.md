# Elevate_Task7

---

## Sales Summary with SQLite and Python

This project demonstrates how I built a basic sales analysis tool using:

- SQLite database
- Python (`sqlite3`, `pandas`, `matplotlib`)
- Jupyter Notebook (or a Python script)

---

### Features

- Created a small SQLite database (`sales_data.db`)
- Inserted mock sales data into a `sales` table
- Wrote SQL queries to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Loaded SQL results into a Pandas DataFrame
- Visualized the data using a bar chart with Matplotlib

---

### Technologies Used

| Tool         | Purpose                        |
|--------------|--------------------------------|
| Python       | Scripting and logic            |
| SQLite3      | Lightweight embedded database  |
| Pandas       | Data analysis and manipulation |
| Matplotlib   | Data visualization             |
| Jupyter      | Step-by-step execution         |

---

### Project Files

```
sales-summary-project/
├── sales_data.db           # SQLite database file
├── sales_chart.png         # Bar chart output
├── sales_summary.ipynb     # Jupyter Notebook version
├── sales_summary.py        # Python script version (optional)
└── README.md               # Project documentation
```

---

### How to Run

#### Option 1: Using Jupyter Notebook

1. Open terminal and run:
   ```
   jupyter notebook
   ```
2. Open `sales_summary.ipynb`
3. Run each cell in order to:
   - Create the database
   - Execute SQL queries
   - Generate the chart

#### Option 2: Using Python Script

1. Run the script using:
   ```
   python sales_summary.py
   ```

---

### Sample Console Output

```
  product  total_qty  revenue
0   Apple         17     42.5
1  Banana         13     13.0
2  Orange          8     24.0
```

---

### Chart Output

The bar chart displays revenue by product.

---

### Additional Notes

- The sales data used was small and created only for demonstration.
- The table can be extended to include additional fields such as `date`, `region`, or `category` for more complex analysis.

---

###Submitted by: Manviya Sahni

### Learning Outcomes

- Used SQL inside Python to perform queries
- Converted SQL results into a Pandas DataFrame
- Created a visual summary using a basic bar chart
- Practiced integrating SQLite with Python
