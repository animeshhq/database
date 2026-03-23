## Postgresql commands

### Basic commands

- SELECT datname FROM pg_database; ( selecting names from database )
- CREATE database <database_name>; ( create a new database )
- \c <database_name>               ( change a database )
- DROP database <db_name>;         ( delete database )

### CRUD Operations

- CREATE TABLE <table_name> (
    <column_name> <datatype>,
    <column_name> <datatype>,
    <column_name> <datatype>,
    ......
  );
