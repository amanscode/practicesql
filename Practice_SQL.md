# Queries to Practice

### Select Top nth salary (replace N with desired number)

```bash
SELECT TOP 1 * FROM (SELECT TOP N * FROM Orders WHERE OrderID>0 ORDER BY OrderID DESC) ORDER BY OrderID ASC;
```

