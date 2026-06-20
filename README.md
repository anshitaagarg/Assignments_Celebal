# Weekly Assignments

## Assignment 1 – Basic Data Exploration and Cleaning using Pandas

**Dataset:** [Shopping Dataset – Kaggle](https://www.kaggle.com/datasets/anvitkumar/shopping-dataset)  
**Tools:** Python, Pandas, Google Colab

**Steps Performed:**
- Loaded `Combined_dataset.csv` (1000 rows × 24 columns)
- Explored data: head/tail, shape, columns, dtypes
- Handled missing values: filled with defaults, dropped nulls in `seller_name`
- Filtered rows (rating ≥ 4.0) and selected key columns
- Removed duplicates
- Created derived column: `total_amount = initial_price × ratings_count`
- Saved cleaned dataset as `cleaned_shopping_data.csv`

**Output:** `Assignment1.ipynb` + `cleaned_shopping_data.csv`

---
