# 🪔 Diwali Sales Data Analysis using Python 📊

This project presents an exploratory data analysis (EDA) of a Diwali sales dataset using Python libraries such as Pandas, Matplotlib, and Seaborn. The objective is to derive insights about customer purchasing behavior across various demographics, occupations, and regions during the Diwali festival season.

## 🔍 Overview

The dataset contains transactional data of sales made during the Diwali festival, including customer demographic details, product categories, order values, and regional information.

Through this project, we:

- Clean the dataset by handling null values and removing irrelevant columns
- Convert and standardize data types for consistency
- Analyze sales distribution by Gender, Age Group, Marital Status, Occupation, State, Product Category, and Product ID
- Visualize trends using insightful bar plots and aggregations

## 📁 Dataset

The dataset used is named: `Diwali Sales Data.csv`

| Column Name       | Description                                      |
|-------------------|--------------------------------------------------|
| User_ID           | Unique ID of the customer                        |
| Gender            | Gender of the customer                           |
| Age               | Age of the customer                              |
| Age Group         | Binned Age range (e.g., 0-17, 18-25, etc.)       |
| Marital_Status    | Marital status (0 = single, 1 = married)         |
| Occupation        | Profession of the customer                       |
| Product_Category  | Type/category of product purchased               |
| Product_ID        | Unique ID of the product                         |
| State             | State where the order was placed                 |
| Orders            | Number of units ordered                          |
| Amount            | Total amount spent in INR                        |

## 📊 Key Insights

- **Gender**: Female customers placed more orders and had a higher total spending than males.
- **Age Group**: Most buyers are in the **26–35** age group, with females dominating the sales.
- **States**: Majority of the orders and revenue came from **Uttar Pradesh**, **Maharashtra**, and **Karnataka**.
- **Marital Status**: Married women have shown higher purchasing power.
- **Occupation**: Customers working in **IT**, **Healthcare**, and **Aviation** are major contributors to sales.
- **Product Category**: Highest selling categories include **Food**, **Clothing**, and **Electronics**.
- **Top Products**: Top 10 most sold products have been identified by order count.

## 🛠 Tools and Technologies

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

## 📌 How to Run

1. Clone this repository:

   git clone https://github.com/your-username/diwali-sales-analysis.git
   cd diwali-sales-analysis

2. Install required libraries:

   pip install pandas numpy matplotlib seaborn

3. Open the Jupyter Notebook:

   jupyter notebook

4. Load `Diwali Sales Data.csv` and run the notebook cells to view the analysis.

## 📈 Visualizations

Some of the visualizations included:

* Count plots by Gender, Age Group, Occupation, and Product Category
* Bar plots showing total `Amount` and `Orders` by various demographics
* Top selling products by order volume

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
