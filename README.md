# 🧮 TP: Dask SQL – TPC-H Benchmark Analysis

Benchmarks provide standardized, repeatable, and comparable evaluations of decision support system technologies such as databases, data warehouses, and OLAP tools. 
**TPC-H** (Transaction Processing Performance Council – Decision Support Benchmark H) is an industry-standard benchmark used to evaluate the performance of decision support systems and data warehouses. 
- Goal: Measure the ability of a system to handle complex analytical queries and large volumes of data.
- Data Model: Based on a product supplier and sales business schema.

---

## 📂 Project Structure
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
