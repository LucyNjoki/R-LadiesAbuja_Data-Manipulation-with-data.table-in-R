# R-LadiesAbuja - Data Manipulation with data.table in R

## March 19, 2022

**Learning Objectives:**

- How to install `data.table` package
- How to load the `data.table`package
- Assessing the **structure** of a `data.table` object
  - **Printing** `data.table` objects
  - Use `head()` and `tail()` to view the **first (and last) five rows**
  - Use `View()` to **view an entire** `data.table` object
  - Use `str()` to view the **structure** of `data.table` object
  - Use `tables()` to **show all loaded `data.table` objects**
- **Sorting** and **ordering** rows using `setorder()` and `order()`
- How to **remove information**:
  - **Selecting rows**: `DT[i,j, by]`
  - Selecting rows based on a **condition satisfied by column(s)**
  - Selecting rows using **helper functions**: `%like%` and `%between%`
  - Selecting columns: `DT[i, j, by]`
   - **Renaming** columns
- How to **add information**:
  - Making **new columns while preserving the existing ones using** `:=`
  - Making **new columns while dropping existing ones**
- How to **reduce information**:
  - **Summarising rows**: `DT[i, j, by]`
  - **Grouping** by one or more variables
- How to **combine information**:
  - **Joining two `data.table` objects** using `merge()` and `data.table` syntax
   - **Full join**; **Inner join**; **Left join**; **Right join**  
