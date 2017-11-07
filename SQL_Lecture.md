Information is sent to a server where is is stored on a hard drive.
These servers run web server software that allows them to utilize the
HTTP protocol (which is used to collect requests from web browsers i.e. chrome).

# SQL

## Databases

The variables, functions, and objects you create during the lifetime of your program will
die when that program closes. To save (or **persist**) data, you need to
write the data to permanent storage, like the hard disk.

Most Apps require rich relationships between pieces of
data. Consider a blogging system:
users have many posts,
posts have many tags, 
users may be following other users,
etc.

Relational databases (also sometimes referred to as RDBMS, relational
database management systems) were developed to provide a means of
organizing data and their relationships, persisting that data, and
querying that data.

## Tables

Relational databases organize data in tables.

| id            | name          | age  |
| ------------- | ------------- | ---- |
|1|Elle Faraday |22| 





Each row is a single entity in the table. Each column houses an
additional piece of data for that entity.

| id            | name          | dept_id  |
| ------------- | ------------- | ---- |
|1|Elle Faraday |2|
|2|Jukay Hsu|2|
|3|Will Kenney|3|
|4|Bob Johnson|1|
|5|Lucy Liu |1|
|6|Mary J. Blige|1|


Every row in a database table will have a **primary key** which will
be its unique identifier in that table row. By convention, the primary
key is simply `id`. Most relational database systems have an
auto-increment feature to ensure that the primary keys are always
unique.

| id            | department_name |
| ------------- | ------------- |
|1|Teaching|
|2|Management|
|3|Operations|


Breaking your domain down into database tables & columns is an
important part of developing any application. Each table will house
one type of resource: `people`, `houses`, `blog_posts`, etc. The
columns in the table will house the data associated with each instance
of the resource.

## Database Schemas

Your database **schema** is a description of the organization of



