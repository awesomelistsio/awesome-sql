# Awesome SQL [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of SQL databases, tools, clients, query builders, learning resources, extensions, and ecosystem utilities for working with structured data and relational databases.

## Contents

- [Databases](#databases)
- [GUI Clients](#gui-clients)
- [CLI Tools](#cli-tools)
- [Extensions](#extensions)
- [Drivers](#drivers)
- [ORMs & Query Builders](#orms--query-builders)
- [SQL Linters & Formatters](#sql-linters--formatters)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Databases

- **PostgreSQL** – Powerful open-source relational database.  
  https://www.postgresql.org/

- **MySQL** – Widely used relational database.  
  https://www.mysql.com/

- **MariaDB** – Community-driven fork of MySQL.  
  https://mariadb.org/

- **SQLite** – Lightweight, file-based SQL database.  
  https://sqlite.org/

- **SQL Server** – Microsoft’s relational database engine.  
  https://www.microsoft.com/sql-server/

- **CockroachDB** – Distributed SQL database with PostgreSQL compatibility.  
  https://github.com/cockroachdb/cockroach

- **TiDB** – Distributed SQL database compatible with MySQL.  
  https://github.com/pingcap/tidb

- **DuckDB** – In-process OLAP SQL database optimized for analytics.  
  https://github.com/duckdb/duckdb

## GUI Clients

- [DBeaver](https://github.com/dbeaver/dbeaver) – Universal database tool supporting all major SQL systems.
- [TablePlus](https://tableplus.com/) – Fast, modern database GUI (commercial).
- [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) – Open-source cross-platform SQL editor.
- [DataGrip](https://www.jetbrains.com/datagrip/) – JetBrains SQL IDE.
- [DB Browser for SQLite](https://github.com/sqlitebrowser/sqlitebrowser) – SQLite visual interface.

## CLI Tools

- [psql](https://www.postgresql.org/docs/current/app-psql.html) – PostgreSQL command-line client.
- [mysql CLI](https://dev.mysql.com/doc/refman/8.0/en/mysql.html) – MySQL client.
- [duckdb CLI](https://duckdb.org/) – DuckDB SQL shell.
- [LiteCLI](https://github.com/dbcli/litecli) – Enhanced SQLite CLI.
- [pgcli](https://github.com/dbcli/pgcli) – Autocompletion and syntax highlighting for PostgreSQL.
- [mycli](https://github.com/dbcli/mycli) – MySQL client with autocomplete.

## Extensions

- [PostGIS](https://postgis.net/) – GIS and geospatial SQL processing for PostgreSQL.
- [pgvector](https://github.com/pgvector/pgvector) – Vector search extension for PostgreSQL.
- [TimescaleDB](https://github.com/timescale/timescaledb) – Time-series database built on PostgreSQL.
- [SQLCipher](https://github.com/sqlcipher/sqlcipher) – Encrypted SQLite.
- [DuckDB Extensions](https://duckdb.org/extensions/) – Analytics functions, Parquet, Iceberg, etc.

## Drivers

### JavaScript / TypeScript
- [pg](https://github.com/brianc/node-postgres) – PostgreSQL driver.
- [mysql2](https://github.com/sidorares/node-mysql2) – MySQL client.
- [better-sqlite3](https://github.com/WiseLibs/better-sqlite3) – SQLite client.

### Python
- [psycopg](https://github.com/psycopg/psycopg) – PostgreSQL driver.
- [mysqlclient](https://github.com/PyMySQL/mysqlclient) – MySQL driver.
- [sqlite3](https://docs.python.org/3/library/sqlite3.html) – Built-in SQLite driver.

### Go
- [lib/pq](https://github.com/lib/pq) – PostgreSQL driver.
- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) – MySQL driver.
- [mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) – SQLite driver.

### Rust
- [sqlx](https://github.com/launchbadge/sqlx) – Async SQL framework.
- [postgres](https://github.com/sfackler/rust-postgres) – PostgreSQL driver.

## ORMs & Query Builders

### JavaScript / TypeScript
- [Prisma](https://github.com/prisma/prisma) – Type-safe ORM with SQL migrations.
- [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) – SQL-first TypeScript ORM.
- [Sequelize](https://github.com/sequelize/sequelize) – Mature ORM for SQL databases.
- [Kysely](https://github.com/koskimas/kysely) – Type-safe SQL query builder.

### Python
- [SQLModel](https://github.com/tiangolo/sqlmodel) – FastAPI-focused ORM.
- [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) – Leading Python ORM.
- [Peewee](https://github.com/coleifer/peewee) – Lightweight ORM.

### Go
- [GORM](https://github.com/go-gorm/gorm) – Go ORM built on top of database/sql.
- [sqlc](https://github.com/sqlc-dev/sqlc) – Generate type-safe Go code from SQL.

### Rust
- [Diesel](https://github.com/diesel-rs/diesel) – Type-safe ORM.
- [SeaORM](https://github.com/SeaQL/sea-orm) – Async ORM with migrations.

## SQL Linters & Formatters

- [SQLFluff](https://github.com/sqlfluff/sqlfluff) – Popular SQL linter and formatter.
- [pgFormatter](https://github.com/darold/pgFormatter) – PostgreSQL SQL formatter.
- [sqlfmt](https://github.com/tconbeer/sqlfmt) – SQL formatter for modern codebases.
- [Prettier Plugin SQL](https://github.com/prettier/plugin-sql) – Prettier support for SQL.

## Learning Resources

- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/) – Beginner–advanced PostgreSQL learning.
- [SQLBolt](https://sqlbolt.com/) – Interactive SQL lessons.
- [Mode SQL Tutorials](https://mode.com/sql-tutorial/) – Practical SQL training.
- [W3Schools SQL](https://www.w3schools.com/sql/) – Intro to SQL.
- [LeetCode Database Problems](https://leetcode.com/problemset/database/) – SQL problem-solving practice.
- [SQL Style Guide](https://www.sqlstyle.guide/) – Best practices and conventions.
- [QueryCase](https://querycase.com) - Browser-based SQL learning game with detective-themed cases covering SELECT through window functions.

## Related Awesome Lists

- [Awesome Databases](https://github.com/awesomelistsio/awesome-db)
- [Awesome SQLite](https://github.com/awesomelistsio/awesome-sqlite)
- [Awesome PostgreSQL](https://github.com/awesomelistsio/awesome-postgres)
- [Awesome MySQL](https://github.com/awesomelistsio/awesome-mysql)
- [Awesome DB Tools](https://github.com/awesomelistsio/awesome-db-tools)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
