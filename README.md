# task-4-supply-chain
Supply Chain Optimization using Linear Programming (PuLP) to minimize transportation cost from warehouses to stores.
# Supply Chain Optimization using PuLP

## Project Overview
This project implements a **Supply Chain Optimization** problem using **Linear Programming** with Python's **PuLP** library.  
The goal is to **minimize transportation costs** while distributing products from multiple warehouses to multiple retail stores, ensuring that:

- Warehouse supply limits are not exceeded  
- Store demands are fully satisfied  

This models a realistic business scenario for logistics and distribution planning.


## Data
- **Warehouses (Supply):**
  - W1 = 40 units
  - W2 = 60 units
  - W3 = 50 units

- **Stores (Demand):**
  - S1 = 30 units
  - S2 = 50 units
  - S3 = 35 units
  - S4 = 25 units

- **Transportation cost (₹ per unit):**

| From \ To | S1 | S2 | S3 | S4 |
|-----------|----|----|----|----|
| **W1**    | 4  | 6  | 9  | 5  |
| **W2**    | 5  | 4  | 7  | 6  |
| **W3**    | 6  | 3  | 4  | 8  |


## How to Run
1. Open `Supply_Chain_Optimization.ipynb` in **Google Colab**.  
2. Run all cells in order.  
3. View results and the shipment visualization.


## Results
- **Optimal shipment plan:**
  - Ship 30 units from W1 to S1  
  - Ship 10 units from W1 to S4  
  - Ship 35 units from W2 to S2  
  - Ship 15 units from W2 to S4  
  - Ship 15 units from W3 to S2  
  - Ship 35 units from W3 to S3  

- **Total Transportation Cost:** ₹585  

- **Visualization:** Bar chart showing units shipped from each warehouse to each store.


## Tools Used
- Python  
- Google Colab  
- PuLP (Linear Programming library)  
- Matplotlib & Pandas for visualization

## Business Impact
This model demonstrates how **optimization techniques** can help a company efficiently allocate inventory, meet demand, and **reduce transportation costs**.  
It can be extended to larger datasets, include vehicle capacity constraints, or integrate real distances between warehouses and stores.
