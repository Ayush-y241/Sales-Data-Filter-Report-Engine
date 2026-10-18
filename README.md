# Sales-Data-Filter-Report-Engine#

## Project Overview

This project simulates one year of sales data for **10 stores** across **12 months** using **NumPy**. It demonstrates various NumPy operations such as slicing, boolean masking, fancy indexing, and data analysis. The project also visualizes the sales data using **Matplotlib**.

The project is designed to run on **Google Colab** and covers all the NumPy concepts required in the assignment.

---

## Objectives

- Simulate yearly sales data.
- Perform data analysis using NumPy.
- Filter records using Boolean Masking.
- Select specific records using Fancy Indexing.
- Slice data into quarters.
- Generate monthly and store-wise reports.
- Visualize data using different charts.

---

## Technologies Used

- Python 3
- Google Colab
- NumPy
- Matplotlib

---

## NumPy Concepts Covered

- `np.arange()`
- `np.linspace()`
- `np.random.randint()`
- `reshape()`
- 2D Array Slicing
- Boolean Masking
- Logical Operators (`&`, `|`, `~`)
- Fancy Indexing
- Aggregation Functions (`sum()`, `mean()`, `max()`, `min()`)

---

## Project Workflow

### Step 1
Generate month labels using:

```python
np.arange(1,13)
```

### Step 2
Generate random sales data for:

- 10 Stores
- 12 Months

### Step 3
Slice sales data into:

- Quarter 1
- Quarter 2
- Quarter 3
- Quarter 4

### Step 4
Perform Boolean Masking to find:

- Sales greater than target
- Stores below average
- Combined conditions using `&`
- Combined conditions using `|`
- Negation using `~`

### Step 5
Use Fancy Indexing to:

- Select stores [2,5,8]
- Find best-performing months

### Step 6
Generate:

- Monthly Report
- Store-wise Report

### Step 7
Create Growth Targets using:

```python
np.linspace()
```

### Step 8
Visualize the data using Matplotlib.

---

## Charts Included

- 📈 Line Chart (Monthly Average Sales vs Growth Target)
- 📊 Bar Chart (Store-wise Total Sales)
- 🔥 Heatmap (Sales Distribution)
- 🥧 Pie Chart (Quarter-wise Sales Distribution)

A reusable function `plot_chart()` is implemented to display charts based on user input.

Example:

```python
plot_chart("line")
plot_chart("bar")
plot_chart("heatmap")
plot_chart("pie")
```

or

```python
chart = input("Enter chart type: ")
plot_chart(chart)
```

---

## Folder Structure

```
Sales-Analysis/
│
├── Sales_Analysis.ipynb
├── README.md
└── images/ (optional)
```

---

## Sample Output

- Sales Data Matrix (10 × 12)
- Quarterly Sales
- Monthly Average Sales
- Store-wise Total Sales
- Boolean Filter Results
- Fancy Indexed Data
- Monthly Report
- Store Report
- Line Chart
- Bar Chart
- Heatmap
- Pie Chart

---

## Learning Outcomes

After completing this project, you will understand:

- Creating NumPy arrays
- Working with multidimensional arrays
- Data slicing and indexing
- Boolean masking techniques
- Fancy indexing
- Statistical analysis using NumPy
- Data visualization using Matplotlib
- Writing reusable functions in Python

---

## Future Improvements

- Read sales data from a CSV file.
- Add yearly comparison reports.
- Create interactive dashboards using Plotly.
- Export reports to Excel or PDF.
- Add more statistical analysis such as median and standard deviation.

---

## Author

**Name:** *Your Name*

**Course:** Python Programming with NumPy and Matplotlib

**Platform:** Google Colab

---

## License

This project is created for educational purposes only.
