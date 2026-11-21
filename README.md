## Dataset Download Instructions

The dataset used in this project is the **Dirty Cafe Sales Dataset**, available on Kaggle.

**Dataset Source:** [Cafe Sales – Dirty Data for Cleaning Training (Kaggle)](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

### Steps to Download

1. Visit the Kaggle dataset link provided above.
2. Log in to your Kaggle account.
3. Click the **Download** button to download the dataset.
4. Extract the downloaded ZIP file.
5. Locate the file named `dirty_cafe_sales.csv`.
6. Place the CSV file in your project directory or note its location.

### Update the Dataset File Path

After downloading the dataset, open `Data_Cleaning.ipynb` and update the dataset loading code according to the location where you saved the CSV file.

**Example:**

```python
import pandas as pd

df = pd.read_csv("path/to/dirty_cafe_sales.csv")
```

**Windows example:**

```python
df = pd.read_csv(r"C:\Users\YourName\Downloads\dirty_cafe_sales.csv")
```

**If the dataset is placed in the same folder as the notebook:**

```python
df = pd.read_csv("dirty_cafe_sales.csv")
```

**Note:** Make sure the file path points to the correct location of `dirty_cafe_sales.csv` before executing the notebook. The original dataset is not included in this repository and must be downloaded separately from Kaggle.
