Select Top nth salary (replace N with desired number):
SELECT TOP 1 * FROM (SELECT TOP N * FROM Orders WHERE OrderID>0 ORDER BY OrderID DESC) ORDER BY OrderID ASC;
