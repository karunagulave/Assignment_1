# Assignment_1
# 🚗 Car Analysis Using Python & Pandas

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a car dataset using **Python** and the **Pandas** library. The dataset contains detailed information about different car brands, models, prices, fuel types, transmission types, engine specifications, and other features.

The main objective is to clean, analyze, and extract meaningful insights from the dataset using Pandas operations.

---

## 📂 Dataset

The dataset includes information such as:

- Car Brand
- Model Name
- Year
- Price
- Fuel Type
- Transmission
- Engine Size
- Mileage
- Horsepower
- Number of Seats
- Body Type
- Other vehicle specifications

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Jupyter Notebook / VS Code
- Matplotlib (Optional)
- Seaborn (Optional)

---

## 📊 Features & Analysis Performed

The project includes various data analysis tasks such as:

- Importing datasets using Pandas
- Displaying dataset information
- Checking dataset shape
- Viewing column names
- Handling missing values
- Removing duplicate records
- Data cleaning
- Filtering data
- Sorting records
- Grouping data
- Finding unique values
- Statistical analysis
- Value counts
- Aggregations (mean, max, min, sum)
- Query-based analysis
- Data visualization (if included)

---

## 📁 Project Structure

```
Car-Analysis/
│
├── Dataset/
│   └── cars.csv
│
├── notebooks/
│   └── Car_Analysis.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## 📈 Sample Pandas Operations

```python
import pandas as pd

# Load Dataset
df = pd.read_csv("cars.csv")

# Display first five rows
df.head()

# Dataset Information
df.info()

# Summary Statistics
df.describe()

# Check Missing Values
df.isnull().sum()

# Remove Duplicates
df.drop_duplicates()

# Filter Cars by Brand
df[df["Brand"] == "Toyota"]

# Average Price by Brand
df.groupby("Brand")["Price"].mean()

# Sort by Price
df.sort_values(by="Price", ascending=False)
```

---

## 📌 Key Insights

Some examples of insights that can be obtained:

- Most popular car brands
- Average price by brand
- Highest priced cars
- Fuel type distribution
- Transmission comparison
- Engine size analysis
- Mileage comparison
- Brand-wise statistics

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/car-analysis.git
```

2. Navigate to the project folder

```bash
cd car-analysis
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook

```bash
jupyter notebook
```

or run the Python script.

---

## 📦 Requirements

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🎯 Learning Objectives

This project demonstrates:

- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis (EDA)
- Pandas Functions
- Data Filtering
- GroupBy Operations
- Statistical Analysis
- Python Programming

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, make improvements, and submit a pull request.

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👩‍💻 Author

**Karuna Gulave**

