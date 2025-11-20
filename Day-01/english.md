### What is data?
->Data is the information we collect, like students’ marks or names, which helps us understand or solve a problem.
->Data refers to raw facts, figures, or information collected for reference or analysis.
->Collection of raw Bytes text,images and integers.
->Data can be recorded and does not have any meaning unless processed
---
### What is information?
->Information is the meaningful result we get after processing data, like finding the class topper after checking all students’ marks.
->It provides context of the the data enables decision making.
---
### What is a database?
->A database is a place where we store data in an organized way, so we can easily add, search, and manage information.
---
### What is DBMS?
->A DBMS (Database Management System) is software that helps us store and manage data.
->It allows adding, updating, deleting, and searching data easily.
->It is a set of Programs.
->DBMS also takes care of security, backup, and controlling who can access the data.
->It makes handling large amounts of data easy and reliable.
Examples include MySQL, Oracle, and MongoDB.
---
### DBMS vs File System 

# 1. Data Storage & Organization
 File System

Advantage: Data is stored in simple files (text, CSV, etc.), easy to create.

Disadvantage: No structured format; becomes messy when data grows.

DBMS

Advantage: Stores data in tables, rows, and columns — very well organized.

Disadvantage: Requires learning and installation of DBMS software.

# 2. Data Redundancy (Duplicate Data)
File System

Advantage: None (simple, but no control).

Disadvantage: Same data appears in many files, causing confusion and storage wastage.

DBMS

Advantage: Reduces duplicate data using normalization and relationships.

Disadvantage: Normalization and table design need proper planning.

# 3. Data Consistency
File System

Advantage: No major advantage here.

Disadvantage: Hard to maintain consistency when multiple files contain the same data.

DBMS

Advantage: Ensures consistent and correct data across the system.

Disadvantage: Needs proper constraints and rules to be set by developers.

# 4. Data Security
File System

Advantage: Very basic security (password on file).

Disadvantage: No fine-grained security; anyone with file access can see or modify data.

DBMS

Advantage: Strong security — user roles, permissions, encryption, access control.

Disadvantage: Requires admin to manage security settings.

# 5. Backup & Recovery
File System

Advantage: You can manually copy files.

Disadvantage: No automatic recovery; if data is corrupted, it’s lost.

DBMS

Advantage: Built-in backup and automatic recovery in case of system failure.

Disadvantage: Maintaining backups consumes time and storage.

# 6. Concurrency Control (Multiple Users Accessing Data)
File System

Advantage: Works fine for single-user or small tasks.

Disadvantage: Cannot handle many users editing data at the same time; leads to conflicts.

DBMS

Advantage: Allows multiple users to safely access the same data at once using locking.

Disadvantage: More complex internally due to concurrency handling.

# 7. Data Integrity
File System

Advantage: No advantage; depends completely on the programmer.

Disadvantage: Hard to ensure valid and correct data.

DBMS

Advantage: Provides rules (constraints, keys) that keep data accurate.

Disadvantage: Designing these rules requires planning.

# 8. Querying & Data Retrieval
File System

Advantage: Simple for small data using search or custom code.

Disadvantage: Hard to search, filter, or combine data without writing long programs.

DBMS

Advantage: Powerful querying using SQL (SELECT, JOIN, WHERE, etc.).

Disadvantage: Requires knowledge of SQL.

# 9. Scalability
File System

Advantage: Works for small apps or personal use.

Disadvantage: Fails when data becomes large or millions of users join.

DBMS

Advantage: Easily handles huge databases and multiple users.

Disadvantage: Needs good hardware and maintenance.