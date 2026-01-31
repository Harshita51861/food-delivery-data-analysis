# Food Delivery Data Analysis

##  Project Overview
This project analyzes food delivery data by integrating multiple data sources including CSV, JSON, and SQL files. The goal is to understand customer behavior, revenue trends, and restaurant performance using Python and Pandas.

---

## Dataset Description
The project uses the following datasets:

- `orders.csv` – Contains order and transaction details  
- `users.json` – Contains user profile and membership information  
- `restaurants.sql` – Contains restaurant details such as cuisine and ratings  

These datasets are merged using appropriate keys to create a unified dataset.

---

##  Data Integration
The datasets are merged using the following keys:

- `orders.user_id` → `users.user_id`  
- `orders.restaurant_id` → `restaurants.restaurant_id`  

A **Left Join** is used to ensure all order records are retained.

---

## Tools & Technologies
- Python  
- Pandas  
- SQLite  
- Matplotlib  
- Jupyter Notebook  

---

## Analysis Performed
The following analyses were carried out:

- Order trends over time  
- User behavior patterns  
- City-wise and cuisine-wise performance  
- Membership impact (Gold vs Regular)  
- Revenue distribution and seasonality  

---

##  Files in This Repository
- `final_food_delivery_dataset.csv` – Merged dataset  
- `analysis.ipynb` – Jupyter Notebook with analysis  
- `README.md` – Project documentation  

---

##  How to Run the Project
1. Clone or download this repository.
2. Open the Jupyter Notebook file (`analysis.ipynb`).
3. Run the cells in sequence to perform data analysis.
4. Ensure required libraries are installed.

---

##  Key Insights
- Gold members show higher average order value.
- Certain cities and cuisines generate higher revenue.
- Revenue shows seasonal patterns.
- High-rated restaurants contribute significantly to total revenue.

---

##  Author
**Harshita**

---

## License
This project is created for academic and learning purposes.
