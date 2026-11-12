# SQL Zero to Hero — Master Curriculum

Nov 11, 2026 · @Bit

A complete, cross-platform SQL curriculum covering Microsoft SQL Server (T-SQL), PostgreSQL (PL/pgSQL), and MySQL — from absolute beginner to enterprise-level professional.

## 12-Level Curriculum Overview

Twelve progressive levels take you from zero database knowledge to enterprise-level expertise, platform by platform.

| Level | Title | Core Focus |
| --- | --- | --- |
| 1 | Computer and Database Foundations | What data is, what a DBMS is, relational theory, tables/rows/keys, SQL history, installation |
| 2 | SQL Fundamentals | SELECT, WHERE, ORDER BY, filtering, NULL handling, data types, aliases, arithmetic |
| 3 | Intermediate SQL | Aggregates, GROUP BY/HAVING, all JOIN types, string/date functions, CASE, subqueries, UNION/INTERSECT/EXCEPT |
| 4 | Advanced SQL | CTEs, recursive CTEs, window functions, ranking, LAG/LEAD, correlated subqueries, EXISTS, PIVOT, analytics |
| 5 | Database Design | ERD, relational modeling, constraints, normalization (1NF–5NF), denormalization, index design, OLTP vs OLAP |
| 6 | Advanced Database Programming | Stored procedures, UDFs, triggers, views, transactions, temp tables, dynamic SQL, error handling, cursors, JSON/XML |
| 7 | Database Internals | Storage engines, query parsing and execution, optimizers, execution plans, buffer pools, WAL, MVCC, locking, deadlocks, isolation levels |
| 8 | Performance Engineering | Index architecture (B-tree, hash, clustered, nonclustered, GIN/GiST/BRIN), query optimization, statistics, SARGability, execution plan reading |
| 9 | Database Administration | Installation, users/roles/permissions, authentication, encryption, backup/restore, disaster recovery, replication, HA, monitoring, maintenance |
| 10 | Data Analytics and Data Engineering | Data cleaning, ETL/ELT, data warehousing, star/snowflake schemas, SCDs, BI, reporting, Python integration, Power BI |
| 11 | Enterprise Database Architecture | Distributed databases, partitioning, sharding, replication strategies, cloud databases, migration, production troubleshooting, reliability engineering |
| 12 | Expert Projects and Certification Prep | Capstone projects, 500+ exercises, 100+ interview questions, system design, portfolio development, certification readiness |

### What you will be able to do by the end

After completing all 12 levels you will be able to independently design, build, optimize, secure, and manage production-grade relational databases in SQL Server, PostgreSQL, and MySQL; pass technical SQL interviews at senior level; and perform data engineering work (ETL, warehousing, analytics) across all three platforms.

### How each lesson is structured

Every lesson follows the same 16-step teaching sequence:

1. Concept and definition
2. Explanation from first principles
3. Visual illustration
4. General SQL syntax
5. SQL Server implementation (T-SQL)
6. PostgreSQL implementation (PL/pgSQL)
7. MySQL implementation (Stored Programs)
8. Expected outputs
9. Real-world applications
10. Performance considerations
11. Common mistakes
12. Beginner exercises
13. Intermediate exercises
14. Advanced challenges
15. Interview questions
16. Knowledge check

No level begins until sufficient understanding of the previous level is demonstrated.

## 12-Month Roadmap

Schedule: 2 hours/day, 6 days/week (12 hours/week, \~48 hours/month). One rest day per week. Total: \~576 hours.

| Month | Weeks | Level | Weekly Focus | Deliverable |
| --- | --- | --- | --- | --- |
| 1 | 1–4 | 1–2 | Databases fundamentals, installation of all three systems, SELECT/WHERE/ORDER BY/DISTINCT, data types, NULL handling | Working lab environment; 50 SELECT queries across SQL Server, PostgreSQL, MySQL |
| 2 | 5–8 | 2–3 | Aggregates, GROUP BY/HAVING, all JOIN types (INNER, LEFT, RIGHT, FULL, CROSS, SELF), string functions, date functions | Library Management System database — schema + 30 queries |
| 3 | 9–12 | 3–4 | CASE expressions, subqueries, UNION/INTERSECT/EXCEPT, CTEs, recursive CTEs | Student Management System — schema + 40 queries including recursive org chart |
| 4 | 13–16 | 4 | Window functions (ROW\_NUMBER, RANK, DENSE\_RANK, NTILE, LAG, LEAD, FIRST\_VALUE, LAST\_VALUE), PIVOT, correlated subqueries, EXISTS | Employee and Payroll Database — 50 advanced analytics queries |
| 5 | 17–20 | 5 | ERD, relational modeling, normalization (1NF–5NF), constraints, index design, OLTP vs OLAP design | Fully normalized Hospital Management Database design + DDL in all three systems |
| 6 | 21–24 | 6 | Stored procedures, UDFs, triggers, views, transactions (ACID), error handling, dynamic SQL, cursors | Banking Transaction System with procedures, triggers, and error handling in all three systems |
| 7 | 25–28 | 7 | Storage engines, query parsing, execution plans, buffer pools, WAL, MVCC, locking, isolation levels, deadlocks | Written analysis of 5 execution plans; deadlock reproduction and resolution |
| 8 | 29–32 | 8 | Index architecture, clustered vs nonclustered, covering indexes, GIN/GiST/BRIN (PostgreSQL), InnoDB indexing, SARGability, statistics | E-commerce Platform database — benchmark before/after index optimization |
| 9 | 33–36 | 9 | Users, roles, permissions, backup/restore, replication setup, high availability, monitoring, maintenance | Full DBA runbook for one platform of choice; backup/restore drill |
| 10 | 37–40 | 10 | Data cleaning, ETL/ELT, star schema design, fact/dimension tables, SCDs, Power BI or Python reporting | Sales Analytics Data Warehouse — star schema + ETL pipeline + 3 reports |
| 11 | 41–44 | 11 | Partitioning, sharding concepts, cloud databases (Azure SQL, AWS RDS, Cloud SQL), migration, reliability engineering | Multi-database Migration Project — migrate schema and data between two platforms |
| 12 | 45–48 | 12 | Capstone projects, mock technical interviews, portfolio review, certification preparation | 2 capstone projects (one OLTP, one analytics); GitHub portfolio; certification mock exams |

### Weekly structure (template)

- **Day 1:** Theory — read concept, diagrams, comparisons
- **Day 2:** SQL Server implementation — write and run queries
- **Day 3:** PostgreSQL implementation — same queries, platform differences noted
- **Day 4:** MySQL implementation — same queries, platform differences noted
- **Day 5:** Exercises — beginner + intermediate problems
- **Day 6:** Advanced challenge + project work + weekly review quiz

### Milestone assessments

| Milestone | When | Format |
| --- | --- | --- |
| Foundations check | End of Month 1 | 20 written SQL queries, no hints |
| Intermediate SQL check | End of Month 2 | JOIN + aggregate problems, timed 60 min |
| Advanced SQL check | End of Month 4 | Window functions + CTE challenge, timed 90 min |
| Design and programming check | End of Month 6 | Build a schema + stored procedures from spec |
| Performance check | End of Month 8 | Diagnose and fix 5 slow queries |
| Capstone | End of Month 12 | End-to-end enterprise project, oral defense |

## Platform Comparison: SQL Server vs PostgreSQL vs MySQL

Fifty-plus dimensions comparing the three systems. Use this table as a reference throughout the curriculum.

| Dimension | SQL Server (T-SQL) | PostgreSQL | MySQL (InnoDB) |
| --- | --- | --- | --- |
| Language | T-SQL | Standard SQL + PL/pgSQL | Standard SQL + Stored Program language |
| License | Commercial (free Express edition) | Open source (PostgreSQL License) | Open source (GPL) + commercial |
| Primary use case | Enterprise Windows/Azure | General-purpose, analytics, geospatial | Web apps, LAMP/LEMP stack |
| Auto-increment IDs | IDENTITY(1,1) | SERIAL / BIGSERIAL / GENERATED ALWAYS AS IDENTITY | AUTO\_INCREMENT |
| String delimiters | Single quotes for values | Single quotes for values | Single or double quotes for values |
| Identifier quoting | Square brackets \[table\_name\] | Double quotes "table\_name" | Backticks `table_name` |
| Top N rows | SELECT TOP 10 | SELECT ... LIMIT 10 | SELECT ... LIMIT 10 |
| Procedural language | T-SQL BEGIN...END blocks | PL/pgSQL DO blocks | Stored Program BEGIN...END |
| Stored procedures | CREATE PROCEDURE | CREATE PROCEDURE / CREATE FUNCTION | CREATE PROCEDURE |
| Triggers | AFTER, INSTEAD OF (views too) | BEFORE, AFTER, INSTEAD OF; uses a trigger function | BEFORE, AFTER (no INSTEAD OF) |
| CTE support | Yes, including recursive | Yes, including recursive | Yes from MySQL 8.0 |
| Window functions | Full support | Full support | Full support from MySQL 8.0 |
| JSON support | JSON (text storage) | JSON and JSONB (binary, indexed) | JSON (text storage) |
| Full-text search | Full-text indexes and predicates | tsvector/tsquery with GIN index | Full-text indexes (InnoDB) |
| Regular expressions | LIKE only; PATINDEX partial | POSIX regex operators \~, ~~\*, !~~ | REGEXP / RLIKE |
| String concatenation | + or CONCAT() | pipe-pipe or CONCAT() | CONCAT() |
| Date/time types | DATE, TIME, DATETIME, DATETIME2, DATETIMEOFFSET | DATE, TIME, TIMESTAMP, TIMESTAMPTZ, INTERVAL | DATE, TIME, DATETIME, TIMESTAMP, YEAR |
| Date current timestamp | GETDATE(), SYSDATETIME() | NOW(), CURRENT\_TIMESTAMP | NOW(), CURDATE() |
| NULL-safe comparison | IS NULL, IS NOT NULL | IS NULL, IS DISTINCT FROM | IS NULL, null-safe equals operator |
| COALESCE / ISNULL | COALESCE(), ISNULL() | COALESCE(), NULLIF() | COALESCE(), IFNULL(), NULLIF() |
| Conditional expression | CASE WHEN...END, IIF(), CHOOSE() | CASE WHEN...END | CASE WHEN...END, IF() |
| Storage engine | Single: SQL Server Database Engine | Single: PostgreSQL storage | Pluggable; InnoDB is default |
| Default isolation level | READ COMMITTED | READ COMMITTED | REPEATABLE READ |
| Isolation levels | Read Uncommitted, Read Committed, Repeatable Read, Serializable, Snapshot | Read Uncommitted, Read Committed, Repeatable Read, Serializable | Read Uncommitted, Read Committed, Repeatable Read, Serializable |
| MVCC | Snapshot isolation via row versioning in tempdb | Native MVCC via tuple versioning | Native MVCC in InnoDB |
| Transaction log | Transaction Log (.ldf) | Write-Ahead Log (WAL) | Redo log + undo log |
| Locking | Row, page, table; lock escalation | Row (tuple) level; MVCC avoids most read locks | Row-level in InnoDB; table-level in MyISAM |
| Deadlock handling | Auto detection; victim chosen by cost | Auto detection; one transaction rolled back | Auto detection; one transaction rolled back |
| Index types | Clustered, nonclustered, covering, filtered, full-text, columnstore, spatial | B-tree, Hash, GiST, GIN, SP-GiST, BRIN, partial, expression | B-tree (clustered in InnoDB), full-text, spatial |
| Clustered index | One per table (PK by default) | No traditional clustered index; CLUSTER command for physical order | Table IS the clustered index (PK = cluster key) |
| Partial indexes | Filtered indexes (WHERE clause) | Partial indexes (WHERE clause) | Not supported natively |
| Expression indexes | Computed column index | Expression index on function | Functional indexes from MySQL 8.0 |
| Execution plan | Graphical plan in SSMS; SET STATISTICS IO ON | EXPLAIN, EXPLAIN ANALYZE, EXPLAIN (ANALYZE, BUFFERS) | EXPLAIN, EXPLAIN ANALYZE (8.0+), EXPLAIN FORMAT=JSON |
| Query Store | Built-in since SQL Server 2016 | pg\_stat\_statements; built-in Query Store since PG 15 | Query performance schema; sys.query\_store since 8.3 |
| Statistics | Auto-updated; UPDATE STATISTICS | ANALYZE; autovacuum updates; pg\_statistic | ANALYZE TABLE; InnoDB persistent statistics |
| Replication | Transactional, Merge, Snapshot; Always On | Streaming (physical), Logical replication | Binary log; GTID; Group Replication |
| High availability | Always On Availability Groups; FCI | Patroni, Repmgr, streaming HA | InnoDB Cluster; Group Replication; MHA |
| Cloud version | Azure SQL Database / Managed Instance | Amazon Aurora (PG-compatible); Google Cloud SQL | Amazon Aurora (MySQL-compatible); Google Cloud SQL; PlanetScale |
| Partitioning | Partition functions and schemes | Declarative (RANGE, LIST, HASH) from PG 10 | RANGE, LIST, HASH, KEY |
| Backup tools | BACKUP DATABASE; SQL Server Agent; SSMS wizard | pg\_dump, pg\_dumpall, pg\_basebackup, WAL archiving | mysqldump, mysqlpump, MySQL Shell, XtraBackup |
| Scheduler | SQL Server Agent | pg\_cron extension | MySQL Event Scheduler |
| Extensions | Linked servers; CLR integration | 1,000+ via CREATE EXTENSION (PostGIS, pg\_trgm, etc.) | Plugins; UDFs via shared libraries |
| GIS/spatial | Geometry and Geography types | PostGIS extension (industry standard) | Spatial data types and indexes |
| Array type | Not native (use JSON/XML/table) | Native array INT\[\], TEXT\[\], etc. | Not native |
| UPSERT syntax | MERGE statement | INSERT ... ON CONFLICT DO UPDATE | INSERT ... ON DUPLICATE KEY UPDATE |
| Pagination | OFFSET ... FETCH NEXT ... ROWS ONLY (2012+) | LIMIT ... OFFSET ...; keyset pagination | LIMIT ... OFFSET ... |
| Temp tables | #local and ##global in tempdb | CREATE TEMP TABLE (session-scoped) | CREATE TEMPORARY TABLE (session-scoped) |
| Table variables | DECLARE @t TABLE (...) | No direct equivalent; CTEs or temp tables | No direct equivalent |
| Error handling | TRY...CATCH...THROW | BEGIN...EXCEPTION...RAISE (PL/pgSQL) | DECLARE HANDLER FOR (procedures) |
| Dynamic SQL | EXEC() or sp\_executesql | EXECUTE format(...) in PL/pgSQL | PREPARE...EXECUTE...DEALLOCATE |
| Case sensitivity | Case-insensitive by default (CI\_AS collation) | Case-sensitive identifiers and collation | Case-insensitive on Windows; case-sensitive on Linux |
| Schema concept | Schema within database (dbo, custom) | Schema within database | No schema; DATABASE is the equivalent |
| System catalog | sys.\* views (sys.tables, sys.columns, etc.) | information\_schema.*, pg\_catalog.*, pg\_class | information\_schema.\*, performance\_schema, sys |
| Performance monitoring | Dynamic Management Views (sys.dm\_\*) | pg\_stat\_\* views; pg\_locks; pg\_activity | performance\_schema; sys schema; SHOW STATUS |
| Connection pooling | Built-in pool | PgBouncer or Pgpool-II recommended | MySQL Router; ProxySQL |
| Default port | 1433 | 5432 | 3306 |
| Vacuum / dead row cleanup | No manual vacuum needed; ghost records auto-cleaned | VACUUM and AUTOVACUUM required | No manual vacuum; InnoDB handles internally |
| Table inheritance | Not supported | Supported (single-table hierarchies) | Not supported |

## Installation and Configuration Guide

Set up all three systems on your machine (Windows, macOS, or Linux). Docker is recommended for clean isolated environments. Native installs are also documented.

### Option A: Docker (recommended for learning)

Docker lets you run all three databases simultaneously without conflicts, delete and recreate them freely, and match production versions exactly.

**Install Docker Desktop:** https://www.docker.com/products/docker-desktop/

**SQL Server on Docker:**

```
docker pull mcr.microsoft.com/mssql/server:2022-latest
docker run -e ACCEPT_EULA=Y -e SA_PASSWORD=YourStrong@Password123 \
  -p 1433:1433 --name sqlserver2022 -d \
  mcr.microsoft.com/mssql/server:2022-latest
```

**PostgreSQL on Docker:**

```
docker pull postgres:16
docker run --name postgres16 \
  -e POSTGRES_PASSWORD=yourpassword \
  -p 5432:5432 -d postgres:16
```

**MySQL on Docker:**

```
docker pull mysql:8.0
docker run --name mysql80 \
  -e MYSQL_ROOT_PASSWORD=yourpassword \
  -p 3306:3306 -d mysql:8.0
```

### Option B: Native installation

| System | Download | Notes |
| --- | --- | --- |
| SQL Server 2022 | https://www.microsoft.com/en-us/sql-server/sql-server-downloads | Use Developer Edition (free, full features) |
| PostgreSQL 16 | https://www.postgresql.org/download/ | Use the interactive installer; include pgAdmin |
| MySQL 8.0 | https://dev.mysql.com/downloads/mysql/ | Use MySQL Community Server; include MySQL Workbench |

### Client tools

| Tool | For | Download |
| --- | --- | --- |
| SQL Server Management Studio (SSMS) | SQL Server | https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms |
| Azure Data Studio | SQL Server, PostgreSQL (extension), MySQL | https://azure.microsoft.com/en-us/products/data-studio |
| pgAdmin 4 | PostgreSQL | https://www.pgadmin.org/download/ |
| MySQL Workbench | MySQL | https://dev.mysql.com/downloads/workbench/ |
| DBeaver (optional) | All three in one tool | https://dbeaver.io/download/ |
| VS Code + SQLTools extension | All three | https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools |

### Sample databases to install

| Database | For | Source |
| --- | --- | --- |
| AdventureWorks | SQL Server | https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure |
| Northwind | SQL Server / PostgreSQL / MySQL | https://github.com/pthom/northwind\_psql (PG); various MySQL ports |
| Pagila / Sakila | PostgreSQL / MySQL | https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/ |
| World database | MySQL | https://dev.mysql.com/doc/index-other.html |

### Verify your installations

After installing, run these commands to confirm each system is working:

**SQL Server (SSMS or Azure Data Studio):**

```
SELECT @@VERSION;
SELECT GETDATE() AS current_time;
```

**PostgreSQL (psql or pgAdmin):**

```
SELECT version();
SELECT NOW() AS current_time;
```

**MySQL (MySQL Workbench or mysql CLI):**

```
SELECT VERSION();
SELECT NOW() AS current_time;
```

### Git and GitHub setup

1. Install Git: https://git-scm.com/downloads
2. Create a GitHub account: https://github.com
3. Create a repository named `sql-zero-to-hero`
4. Organize folders: `/level-01`, `/level-02`, ... `/level-12`; `/projects`; `/exercises`
5. Commit your SQL scripts after every session

## Diagnostic Assessment

Complete this assessment honestly before starting the curriculum. It establishes your baseline and determines the right entry point. No time limit — answer from memory only, no searching.

### Part 1: Conceptual questions (no SQL required)

1. What is a database? How is it different from a spreadsheet?
2. What does RDBMS stand for? Name two examples.
3. What is a primary key? What rules must it follow?
4. What is a foreign key? What problem does it solve?
5. What is NULL in SQL? Is NULL equal to zero or to an empty string?
6. What is the difference between DELETE and DROP in SQL?
7. What is normalization? Can you name any normal forms?
8. What is a transaction? Can you name its four properties?
9. What is an index? Why would you add one to a table?
10. What is the difference between a clustered and a nonclustered index?

### Part 2: SQL writing questions

For each question, write the SQL from memory. Do not worry about which platform — write whatever SQL you know.

11. Write a query that returns all rows from a table called `employees`.
12. Write a query that returns only employees whose `department` is 'Sales'.
13. Write a query that returns the number of employees in each department, sorted from largest to smallest.
14. Write a query that returns all employees and their manager's name. The manager is also in the `employees` table (a self-join).
15. Write a query that returns the top 5 highest-paid employees.
16. Write a query using a subquery that returns employees who earn more than the average salary.
17. Write a query that uses a CTE to calculate the running total of monthly sales from a `sales` table.
18. Write a window function query that ranks employees by salary within each department.
19. Write a stored procedure (in any syntax you know) that accepts a department name and returns all employees in that department.
20. What would you do if a query was running slowly? List the steps you would take to investigate.

### Scoring guide

| Score | Entry point |
| --- | --- |
| 0–5 correct | Start at Level 1 (absolute beginner) |
| 6–10 correct | Start at Level 2 (SQL fundamentals) |
| 11–14 correct | Start at Level 3 (intermediate SQL review) |
| 15–17 correct | Start at Level 4 (advanced SQL) |
| 18–20 correct | Start at Level 5 or beyond — discuss with instructor |

Share your answers and I will score them, identify gaps, and assign your starting level.

## Lesson 1: Introduction to Databases and RDBMS

**Level 1 — Module 1 of 7** | Prerequisites: none | Estimated time: 2 hours

---

### 1. Concept and definition

A **database** is an organized collection of related data stored and accessed electronically. A **Database Management System (DBMS)** is the software that manages that data — storing it, retrieving it, securing it, and ensuring its integrity.

A **Relational Database Management System (RDBMS)** is a DBMS where data is organized into **tables** (also called relations). Tables are linked to each other through shared values, allowing complex questions to be answered by combining data from multiple tables.

SQL Server, PostgreSQL, and MySQL are all RDBMSs. They all use SQL — Structured Query Language — as their primary language, but each has its own extensions and behaviors.

---

### 2. Explanation from first principles

Imagine a school. The school needs to track students, courses, and which students are enrolled in which courses.

Without a database you might use spreadsheets:

- Spreadsheet 1: students (name, age, email)
- Spreadsheet 2: courses (course name, teacher)
- Spreadsheet 3: enrollments (student name, course name)

Problems immediately appear. If a student changes their email, you must find and update every spreadsheet where their email appears. If two people have the same name, you cannot tell them apart. If someone deletes a row, the data is gone.

A relational database solves all of this. Each entity (student, course, enrollment) lives in its own table. Tables are linked by **keys** rather than by repeated data. Changes in one place automatically keep everything consistent.

---

### 3. Core concepts

**Table (Relation):** A grid of rows and columns. Each table represents one type of entity — students, orders, products.

**Row (Record / Tuple):** One instance of the entity. One student. One order. One product.

**Column (Attribute / Field):** One property of the entity. A student's name. An order's date. A product's price.

**Primary Key:** A column or set of columns that uniquely identifies each row in a table. No two rows can have the same primary key value. No primary key can be NULL.

**Foreign Key:** A column in one table that refers to the primary key of another table. This is how tables are linked. It enforces referential integrity — you cannot have an enrollment for a student who does not exist.

**Schema:** The structure of the database — the definition of tables, columns, data types, and constraints. The schema describes what the data looks like; the data itself is the content.

---

### 4. DBMS versus RDBMS

| Feature | DBMS (generic) | RDBMS |
| --- | --- | --- |
| Data storage | Any structure (files, hierarchical, network) | Tables (relations) |
| Relationships | Not required | Defined through keys |
| Data redundancy | Often high | Minimized through normalization |
| SQL support | Not always | Required |
| ACID transactions | Not always | Yes |
| Examples | Early file systems, some NoSQL stores | SQL Server, PostgreSQL, MySQL, Oracle, SQLite |

---

### 5. The relational model — a brief history

Edgar F. Codd published "A Relational Model of Data for Large Shared Data Banks" in 1970. His model proposed that data should be stored in simple two-dimensional tables, with relationships expressed through shared values rather than physical pointers or file links. This was revolutionary — it separated the logical structure of data from its physical storage.

SQL was developed in the 1970s at IBM to manipulate relational data. It became an ANSI standard in 1986 and an ISO standard in 1987. Despite each vendor adding proprietary extensions (T-SQL, PL/pgSQL, MySQL's dialect), the core SELECT statement you will write today would be recognizable to a database programmer from 1990.

---

### 6. The three platforms you will learn

**Microsoft SQL Server** was first released in 1989. It runs primarily on Windows and Azure. Its extension language is T-SQL (Transact-SQL). It is widely used in enterprises, financial institutions, healthcare organizations, and government. Its management tool is SQL Server Management Studio (SSMS).

**PostgreSQL** (pronounced "post-gres-Q-L") is open source, first released in 1996 as a rewrite of an earlier academic system called Ingres. It is known for standards compliance, extensibility, and advanced features (arrays, JSON, geospatial via PostGIS). It runs on all major operating systems. Its management tool is pgAdmin.

**MySQL** was first released in 1995, acquired by Sun Microsystems in 2008, and then by Oracle in 2010. It is the most widely deployed open-source database in the world, powering most web applications. Its management tool is MySQL Workbench. MariaDB is a community fork of MySQL and largely compatible.

---

### 7. Your first SQL queries — the SELECT statement

SQL has four main categories of commands:

- **DQL** (Data Query Language): SELECT — retrieves data
- **DML** (Data Manipulation Language): INSERT, UPDATE, DELETE — changes data
- **DDL** (Data Definition Language): CREATE, ALTER, DROP — changes structure
- **DCL** (Data Control Language): GRANT, REVOKE — controls access

The simplest possible SQL query:

```
SELECT 'Hello, SQL World!';
```

SQL Server:

```
SELECT 'Hello, SQL Server!';
```

PostgreSQL:

```
SELECT 'Hello, PostgreSQL!';
```

MySQL:

```
SELECT 'Hello, MySQL!';
```

All three return one row with one column containing the string. This is your first SQL program.

---

### 8. Real-world applications

Every meaningful digital system relies on a database:

- An online banking app: your account balance, transactions, and transfer history live in a database.
- A hospital: patient records, prescriptions, appointments, and test results.
- An e-commerce site: products, customers, orders, and inventory.
- A university: students, courses, grades, and schedules.

SQL is the universal language for all of these systems. A developer who cannot write SQL is like an engineer who cannot read blueprints.

---

### 9. Common mistakes at this stage

- Confusing SQL (the language) with a specific database system. SQL is a standard; T-SQL, PL/pgSQL, and MySQL SQL are dialects of that standard.
- Thinking NULL means zero or empty string. NULL means unknown or missing. It is not equal to anything, including itself.
- Treating a database like a spreadsheet. Spreadsheets are for humans to read; databases are for programs to query. Structure matters.

---

### 10. Beginner exercises

Complete these in all three systems:

1. Run `SELECT @@VERSION` (SQL Server) / `SELECT version()` (PostgreSQL) / `SELECT VERSION()` (MySQL) and record the version of each system.
2. Run `SELECT GETDATE()` (SQL Server) / `SELECT NOW()` (PostgreSQL and MySQL) and compare the output format.
3. Write a SELECT that returns two columns: your first name and your last name, as literal strings.
4. Write a SELECT that calculates 15% of 1500 (a tip calculation) as a single number.
5. Run `SELECT 1 + 1` on all three systems. Same result? Note any syntax differences.

---

### 11. Intermediate exercises

6. Look up the `INFORMATION_SCHEMA.TABLES` view in your installed database. Write a query that lists all tables in your sample database (AdventureWorks, Pagila, or Sakila).
7. Write a query that returns the current date only (not time), the current time only (not date), and the current timestamp — all in one SELECT, as three separate columns.
8. Research: what is the maximum size of a VARCHAR in SQL Server, PostgreSQL, and MySQL? Write down the differences.

---

### 12. Advanced challenge

9. Without running any code, predict the result of this query in all three systems:

```
SELECT NULL = NULL;
```

Then run it. What does each system return? What does this tell you about NULL?

10. Write a query that returns the number of days between January 1, 2000 and today, using each platform's native date arithmetic. Write it three ways — one per platform.

---

### 13. Interview questions

- What is the difference between a DBMS and an RDBMS?
- What are the four properties of a relational database table (or of a relation in Codd's model)?
- What is the difference between a primary key and a unique key?
- What does NULL mean in SQL? Can a primary key be NULL?
- Name three differences between SQL Server, PostgreSQL, and MySQL.

---

### 14. Knowledge check

Before moving to Lesson 2, you should be able to:

- [ ] Explain what a database, DBMS, and RDBMS are in plain language
- [ ] Name the differences between DBMS and RDBMS
- [ ] Explain primary key and foreign key
- [ ] Explain what NULL means
- [ ] Connect to all three database systems from their client tools
- [ ] Run a basic SELECT query on all three systems
- [ ] Explain what SQL, T-SQL, and PL/pgSQL are and how they relate

**Lesson 2** covers: SELECT in depth — FROM, WHERE, comparison operators, logical operators, BETWEEN, IN, LIKE, and NULL handling.
