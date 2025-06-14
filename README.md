# Association Rule Mining using Apriori and FP-Growth

This project demonstrates the use of **Apriori** and **FP-Growth** algorithms to discover **frequent itemsets** and generate **association rules** from transaction data. The implementation is done in Python using the `mlxtend` and `pandas` libraries.

## Objective

To find meaningful patterns and associations between items in a dataset using:
- Apriori algorithm
- FP-Growth algorithm
- Association Rule Mining (Confidence, Support, Lift)

## Sample Data

The project includes two approaches:
1. Binary dataset (manually encoded)
2. Transactional dataset using one-hot encoding via `TransactionEncoder`

Example transaction:
```python
['laptop', 'mouse', 'charger', 'USB', 'HDMI']
