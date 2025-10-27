# 🧮 TP: Dask SQL – TPC-H Benchmark Analysis

This project demonstrates how to use **Dask SQL** to execute and analyze **TPC-H benchmark queries** for distributed data processing and performance evaluation.  
The notebook illustrates how Dask SQL enables scalable analytics by combining the flexibility of Python with the power of SQL for large datasets.

---

## 🚀 Features
- Execution of **TPC-H benchmark queries (Q1–Q22)** using Dask SQL  
- Comparison between **Dask SQL** and traditional SQL engines  
- Exploration of **distributed computing concepts**  
- Performance metrics and query optimization techniques  

---

## 🛠️ Requirements
Before running the notebook, install the following dependencies:

```bash
pip install dask dask-sql pandas numpy matplotlib jupyter
```

📂 Project Structure
```graphql
RanaDaskSQL_tpch.ipynb   # Main notebook containing code and analysis
README.md
```

## ▶️ How to Run
- Open the notebook:

```bash
jupyter notebook RanaDaskSQL_tpch.ipynb
```

- Run all cells in sequence to:

- Initialize the Dask SQL context

- Load TPC-H tables (e.g., lineitem, orders, customer, etc.)

- Execute benchmark queries

- Visualize query results and performance

## 📊 Example Output
- Query execution times for multiple datasets

- Result previews for benchmark queries

- Comparative visualizations of distributed vs. local execution

## 📚 License
This project is for educational purposes only.