# Queries to Practice

### Select nth highest salary (replace N with desired number)

```bash
SELECT TOP 1 * FROM (SELECT TOP N * FROM Employee ORDER BY salary DESC) ORDER BY salary ASC;
```

