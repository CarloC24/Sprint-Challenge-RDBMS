# Project Features

#Projects

=== http://localhost:9000/projects ===

GET , POST , PUT , DELETE , GET by id with context

POST/PUT SCHEMA
{
"p_name": "Im Project 1",
"p_description": "Im Project 1 with the following descriptions",
}

#Actions

=== http://localhost:9000/actions ===

GET , POST , PUT , DELETE , GET by id

POST/PUT SCHEMA
{
"a_notes": "Action 1 updated",
"a_description": "Action 1 updated"
}

# Questions - Self Study

You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future.

1.  Explain the difference between `RDBMS` and `SQL`.

Relational Database Management Systems are Systems like Knex or Php My Admin used to write sql to query data for endpoints.

1.  Why do tables need a `primary key`?

Every table needs a unique identifier.

1.  What is the name given to a table column that references the primary key
    on another table.

A foreign key.

1.  What do we need in order to have a _many to many_ relationship between two
    tables.

A many to many relationship in a table is only a table with multiple one to many relationship.

1.  What SQL statement is used to retrieve data from a table?

SELECT statement.

1.  What SQL clause is used to filter the results of a query?

WHERE clause.
