### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a database management system that helps web developers manage data and use it to integrate within their websites.

- What is the difference between SQL and PostgreSQL?
SQL is a language that is used to mangage relational databases such as Postgre. Postgre uses SQL syntax to manage its databses and supports SQL as its query language.
- In `psql`, how do you connect to a database?
You can use "\c database" or "psql database" Data base being what your database is called.

- What is the difference between `HAVING` and `WHERE`?
WHERE is used to filter individuals rows
HAVING is used to filter GROUP BY rows

- What is the difference between an `INNER` and `OUTER` join?
INNER join is used to join two tables that have join on a condition, if it is true, the result set includes only the matching rows from both tables

OUTER join has 3 different types of joins
1. LEFT OUTER Join
   - Joins the entire left table and matching rows from the right table.
   - If there is no match, the value is set to NULL 
2. RIGHT OUTER Join
   - Joins the entire right table and matching rows from the left table.
   - If there is no match, the value is set to NULL
3. FULL OUTER JOIN
   - Joins both all rows from both tables. If there is no match than the value of NULL is set for those rows.
  
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
LEFT OUTER will include everything from the left table and whatever matches from the right table, vice versa

- What is an ORM? What do they do?
ORM stands for object relational mapping.
ORM is a programming technique to build the "bridge" between your application and database management system. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
Typically AJAX requests is used to make asynchronous HTTP requests from the client side browser environment, providing a interactive and dynamic user experience.
On the other hand, a library like requests is typically used to make HTTP requests from the server to a external API to fetch data and than used for the website.

- What is CSRF? What is the purpose of the CSRF token?
- CSRF stands for Cross-Site Request Forgery
- CSRF token is typically used to reduce CSRF attacks. 
- The token is a unique and random value assigned to a user session, and is included in each request that modifies the state of the application.
  
- What is the purpose of `form.hidden_tag()`?
This is a ability used in FLASK, with WTForms.
This is used in conjuction with the CSRF token. This is used to help transfer the CSRF Token safely and to gain access to modifying applications. It helps protect against CSRF attacks, so they cant forge or tamper with form submissions.