what is a view ?

In SQL, a view is a virtual table whose contents are defined by a SELECT query. Unlike a regular table, a view does not store data itself; instead, it dynamically generates its content by executing the underlying SELECT statement whenever it is referenced.
it helps  from writing complex queries again and again.


Example:You want a view that only shows the product name and revenue, hiding the sensitive sale_id, quantity, and specific month.
