# SQL
We need to sanitize sql statements
DO NOT string interpolate with data received from a user

Make sure id is the first column in table

Adding foreign key constraints
`FOREIGN KEY (albumId) REFERENCES albums(id) ON DELETE CASCADE`
The delete cascade helps prevent orphaned data in the database.

`UNIQUE` constraints can be used to limit row entries based on the field constrained