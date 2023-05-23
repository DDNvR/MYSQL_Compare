# README

## What is mysqlcompare?
mysqlcompare is a lightweight script to compare two database schemas. It supports MySQL, MS SQL Server and PostgreSQL.

[ Main settings ]
; Possible DATABASE_DRIVER: 'mysql', 'pgsql', 'dblib', 'oci'.
; Please use 'dblib' for Microsoft SQL Server
DATABASE_DRIVER = mysql
DATABASE_ENCODING = utf8
SAMPLE_DATA_LENGTH = 100

[ Primary connection params ]
DATABASE_HOST = localhost
DATABASE_PORT = 3306
DATABASE_NAME = localhost_dev
DATABASE_USER = root
DATABASE_PASSWORD =
DATABASE_DESCRIPTION = Developer database

[ Secondary connection params ]
DATABASE_HOST_SECONDARY = localhost
DATABASE_PORT_SECONDARY = 3306
DATABASE_NAME_SECONDARY = localhost_dev
DATABASE_USER_SECONDARY = root
DATABASE_PASSWORD_SECONDARY =
DATABASE_DESCRIPTION_SECONDARY = Production database
```

where 

`DATABASE_DRIVER` - database driver, possible value

- `mysql` - for MySQL database
- `pgsql` - for PostgreSQL database
- `dblib` - for Microsoft SQL Server database
- `oci`   - for Oracle database

