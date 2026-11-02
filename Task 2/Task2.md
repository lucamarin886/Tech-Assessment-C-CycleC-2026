1. Open SQL Server Management Studio (or an equivalent SQL Management Software)
2. Connect to Northwind DB (Same DB as you used in Geek Week)
3. Write a query that shows each employee’s first name and the number of orders they have placed. Group the results by employee’s first name.

Please add your SQL query below AND add explanation of the query: 

```
---get  employee's first name,as well as number of 
--orders placed, group by employee's first name

select firstName, quantity,

from orders o
	join customer.id on o.OrderID
```

4. For submission commit and push this .md file to Github
