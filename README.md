# MySQL Introduction

MySQL is an open-source relational database management system which makes it easy to manage our database via the provided queries of it and it is written in C and C++ programming language.

**Database** − A database is a collection of tables, with related data.

**Table** − A table is a matrix with data. A table in a database looks like a simple spreadsheet.

**Column** − One column (data element) contains data of one and the same kind, for example the column postcode.

**Row** − A row (= tuple, entry or record) is a group of related data, for example the data of one subscription.

**Redundancy** − Storing data twice, redundantly to make the system faster.

**Primary Key** − A primary key is unique. A key value can not occur twice in one table. With a key, you can only find one row.

**Foreign Key** − A foreign key is the linking pin between two tables.

**Compound Key** − A compound key (composite key) is a key that consists of multiple columns, because one column is not sufficiently unique.

**Index** − An index in a database resembles an index at the back of a book. Primary key and Unique key does not require Indexing because of its index. Should avoid NULL values columns. ID(Clustered Index, which are in Sequence). When data is not in Sequence or we are applying an index on Multiple columns together that is a non-cluster index.

**Referential Integrity** − Referential Integrity makes sure that a foreign key value always points to an existing row.
**Port** - Default port of MySQL is 3306.