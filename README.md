\# 📊 Pandas Learning Project (6 Days)

This repository contains a **6-day hands-on learning journey with Pandas**, designed to build practical data analysis skills from basic data structures to real-world dataset analysis.

---

## 🚀 Topics Covered

### **Day 1: Pandas Series & DataFrames**
- Understand the difference between Series (1D) and DataFrames (2D)  
- Create Series from lists (e.g., fruits, exam scores)  
- Create DataFrames from dictionaries (e.g., student info)  
- Perform basic exploration: `.head()`, `.tail()`, `.describe()`, `.dtypes`

### **Day 2: Import/Export Data**
- Read CSV and Excel files using `pd.read_csv()` and `pd.read_excel()`  
- Export DataFrames using `.to_csv()` and `.to_excel()`  
- Experiment with parameters like `index_col`, `sep`, and `header`

### **Day 3: Indexing & Filtering**
- Access rows/columns with `.loc[]` and `.iloc[]`  
- Apply conditional filtering and boolean indexing  
- Slice DataFrames to extract subsets  
- Example: Filter Titanic passengers by age, class, or survival status

### **Day 4: Grouping & Aggregation**
- Summarize data by categories using `.groupby()`  
- Apply aggregation functions like `sum`, `mean`, `count`  
- Use `.agg()` for multiple aggregations at once  
- Example: Analyze average exam scores by subject or survival rates by passenger class

### **Day 5: Merging & Joining Datasets**
- Combine datasets with `pd.merge()` (inner, outer, left, right)  
- Stack DataFrames with `pd.concat()`  
- Handle duplicate keys and overlapping columns  
- Example: Merge student info with exam scores or Titanic passenger data with cabin info

### **Day 6: Titanic Dataset Project**
- Apply all skills learned: import, explore, filter, group, merge  
- Analyze survival rates by gender/class, average age of survivors  
- Create visual summaries using `.plot()` or `matplotlib`

---

## 📁 Dataset
- Titanic dataset (used for practice):  
[https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- Matplotlib (for visualization)

---
