 SELECT DATASET COLUMNS

## 📌 Project Overview

This project demonstrates how to select specific rows and columns from a dataset using the Pandas library in Python.

The Iris dataset is used to understand different methods of selecting data from a Pandas DataFrame.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## 📊 Concepts Covered

- Loading a dataset
- Creating a Pandas DataFrame
- Selecting data using `.loc`
- Selecting data using `.iloc`
- Selecting a single column
- Selecting multiple columns

## 🔍 Difference Between loc and iloc

| loc | iloc |
|-----|------|
| Uses labels and column names | Uses integer positions |
| Example: `df.loc[0:4, ["column_name"]]` | Example: `df.iloc[0:5, 0:2]` |

## 📂 Dataset Used

The Iris dataset from Scikit-learn is used in this project.

## 🎯 Conclusion

This project helped in understanding how to access and select specific parts of a Pandas DataFrame using different indexing methods.
