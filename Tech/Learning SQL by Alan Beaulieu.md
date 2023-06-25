Specifiy db to use upon launching mysql: `mysql -u root -p yourDB`

Show current time and date: `now()`

In order to query some db servers you will have to include `from` keyword. For example to use `now()` with Oracle Database, you will need to add `from dual` to your query (which is a table with a single column and a single entry). the query `select now() from dual` is a valid MYSQL query for compatability reasons with Oracle Database.

If data suprasses the size of the type, it will be truncated.

Trailing spaces are recorded in character data types.

date and time types are called temporal types.

To limit input:
`someCol varchar(30) CHECK (someCol IN ("someValue", "someOtherValue, "andSoOn"))`

MYSQL offers a data type called ENUM that has a CHECK constraint integrated. The equivalent SQL statement would be:
`someCol ENUM("someValue, "someOtherValue, "andSoOn"))`

`desc` is short for `describe`.

to alter pk which have fk referencing them, you need to disable first fk checks using `SET foreign_key_checks=0` to do that. Afterwards enable fk constraints again using `SET foreign_key_checks=1`.

it is recommended that date entries are inserted via `str_to_date()` function that includes formatting. You can look up the date formatters.

When executing a statement, the following tests are made in order:
1. Check if you have permission to execute the statement
2. Check if you have permission to access the data
3. Check the syntax

If the 3 tests pass, your statement will be taken to the query optimizer to figure out the most efficient execution plan.

Types of tables:
1. permanent: created by `create table`
2. dervied: ones that are used in subqueries
3. temporary: ones created with `create temporary table`
4. virtual (called views): ones that are created with `create view`

In most dbs, temporary tables are dropped after the session is closed except Oracle DB which keeps their definition for future sessions.

Virtual tables are ones that are created by a query.

When giving a range (>= 3 AND <= 5) you can opt for `BETWEEN 3 AND 5` instead. You must always specify the lower bound before the BETWEEN keyword. Oh and BETWEEN/AND includes the bounds.

Say you want a sort of case of statement in SQL. You can go with: `...WHERE someCol IN ("someValue", "someOtherValue"..)`

Wild cards in SQL:
- `-`: matching exactly one character.
- `%`: matching 0 or more characters.

You can instead work with regular expressions as follow in MYSQL: `...WHERE first_name REGEXP 'yourRegex'`

An expression can be null, but is never equal to null. Using `...WHERE something = NULL `does not work.

To compare with null, we can `...WHERE something IS NULL`.

If you only provide the keyword `JOIN`, it will be interpreted as `INNER JOIN`. You should get into the habit of including which type of join your statement is.

An older join syntax: 
`SELECT c.name, a.address FROM customer c, address a WHERE c.address_id = a.address_id`
Though it is best to use the newer SQL92 version syntax which separates join conditions (using `JOIN`) from filtering ones (using `WHERE`)