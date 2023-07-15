### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  PostgreSQL is an open source relationship database that supports SQL and JSON querying. It is highly stable and has
  been around for 20+ years.

- What is the difference between SQL and PostgreSQL?
  SQL is relational database management system, from Microsoft, runs on Microsoft of Linux. PostgreSQL is object-relational database management system, open source, runs on most OS's and uses standard SQL.

- In `psql`, how do you connect to a database?
  Launch terminal window, type psql > <database name>.

- What is the difference between `HAVING` and `WHERE`?
  Having filters values from a group and WHERE filters records before a group is made.

- What is the difference between an `INNER` and `OUTER` join?
  An INNER join returns only the rows that both tables have in common. An OUTER join returns all rows from both tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  A LEFT OUTER returns all matches in the left table even if it has no matches in the right. A RIGHT OUTER contains all records in the right table even if it has not matches in the left.

- What is an ORM? What do they do?
  ORM stands for object relational mapping and it aligns programming code with database structures.

- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?
  AJAX requests don't need to reload the page.

- What is CSRF? What is the purpose of the CSRF token?
  CSRF stands for cross-site request forgery and it happens when a bad actor tries to impersonate a real website to gain personal information. A CSRF token is a shared secret between the client and ther server that makes sure the request is authorized. It is contained in a hidden field in an HTML form. It is random and unique and the bad actor can't predict the value to do their evil deeds.

- What is the purpose of `form.hidden_tag()`?
  It creates the hidden field where the token is stored to protect against CSRF attacks.
