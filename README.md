#  Employment Data Analysis — UN Gender Statistics

This project explores employment data using Python for data analysis and visualization.  
The dataset focuses on gender-based employment statistics sourced from the **United Nations** database.

---
This dataset is publicly available for non-commercial use under the United Nations Data Terms of Use.
For details, visit the official site: data.un.org
Repository Structure
 Employment-Data-Analysis
 ┣  README.md
 ┣  UNdata_Export_20251103_133927481.csv
 ┣  FDS_project.ipynb
 ┗  /images  ← (optional visualizations folder)
.
## Dataset Information

**Dataset Name:** UN Gender Employment Statistics  
**Source:** [United Nations Data Portal](https://data.un.org/Data.aspx?q=employment&d=GenderStat&f=inID%3a101)  
**File:** `UNdata_Export_20251103_133927481.csv`  

The dataset contains gender-based employment indicators across multiple countries and years.  
It includes details such as:
- Employment rate by gender
- Labor force participation
- Economic activity distribution
- Country-wise and year-wise employment data

---

##  Project Description

The goal of this project is to:
1. Load and preprocess the dataset.
2. Perform **exploratory data analysis (EDA)** using `NumPy` and `pandas`.
3. Visualize trends using **Matplotlib**.
4. Derive insights about global and regional gender employment patterns.

---

##  Technologies Used

- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

##  Notebook

All analysis and visualizations are implemented in the Jupyter Notebook:

 [`FDS_project.ipynb`](./FDS_project.ipynb)

This notebook includes:
- Data loading and cleaning
- Correlation analysis
- Visualizations (bar charts, line plots, scatter plots, etc.)
- Summary insights

---
DONE by
- Niranjana krishnakumar-(RA2411027010003)

- Pati Venkata Sai Surya-(RA2411027010006)

- Talari Geethika -(RA2411027010028)


##  Example Visualization

Example plots include:
- Employment trends over time  
- Gender comparison by country  
- Correlation heatmap of employment metrics
  

```python
plt.figure(figsize=(8,6))
plt.imshow(corr, cmap='coolwarm', interpolation='none')
plt.colorbar(label='Correlation Coefficient')
plt.title("Correlation Heatmap (Matplotlib)")
plt.show()

