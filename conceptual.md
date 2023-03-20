### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source relational database management system that encompasses the capabilities of SQL and extends it to additional features

- What is the difference between SQL and PostgreSQL?

PostgreSQL is open source while SQL is commercial software. Both are used to manage relational databases. PostgreSQL extends SQL's capabilities as well.

- In `psql`, how do you connect to a database?

```\c DATABASE_NAME```

- What is the difference between `HAVING` and `WHERE`?

HAVING is a conditional statement used with the GROUP BY clause to filter records according to groups that satisfy the conditional statement. WHERE is used to filter records from the table and/or join tables; it does not need to be used with the GROUP BY clause.

- What is the difference between an `INNER` and `OUTER` join?

INNER joins tables based on shared values in common, while OUTER joins tables based on values not in common.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

LEFT OUTER will contain everything from the first table and only non-shared elements from the second table. RIGHT OUTER will combine only non-shared rows from the first table with all records from the second table .

- What is an ORM? What do they do?

ORM is Object Relational Mapping -- it is a wrapper library for relational SQL commands for ease of programming and integration with app development languages like Python.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  
An HTTP request will reload the page because it is like a 'submission' from the browser. An AJAX request is done via JavaScript and does not reload the page.

- What is CSRF? What is the purpose of the CSRF token?

CSRF is Cross-Site Request Forgery -- it is a type of unauthorized access (and potentially attack) where a web app resource is called from an external source not intended or associated with the app/website. The token helps ensure that the source of the request is only from the intended application.

- What is the purpose of `form.hidden_tag()`?

It generates a hidden form field that can be used to secretly (unseen to the user) send information along with a form submission such as a CSRF token, ensuring that the source of the request is your form/page.
