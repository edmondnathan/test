# How to Documnet

```sql
SELECT
  customer_id,
  customer_name,
  city,
  SUM(sales) AS total_sales
FROM orders
WHERE citty LIKE '%A'
GROUP BY customer_id, customer_name, city
```

```python
print("Hello World")
```


