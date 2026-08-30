This repository is a personal collection of SQL reference notes for **MySQL** and **PostgreSQL** — terminal commands, data types, constraints, and query statements, with side-by-side comparisons between the two engines where they differ.

> **Important:** Some commands (mostly service management, e.g. `systemctl`) are specific to Linux, but most commands should work the same across different operating systems.

## Structure

The project is organized as plain-text notes, split by database engine:

```
SQL/
├── MySQL/
│   ├── mysql_commands.txt              # Terminal/shell commands: connecting, users, privileges, service management
│   ├── data_types_and_constraints.txt  # Data types (numeric, text, date/time, binary) and table constraints
│   └── statements.txt                  # SQL statements: CREATE, INSERT, SELECT, UPDATE, DELETE, ALTER, etc.
└── PostgreSQL/
    ├── postgresql_commands.txt              # psql commands, roles, privileges, service management
    ├── data_types_and_constraints.txt       # Data types and constraints (noting differences from MySQL)
    └── statements.txt                       # SQL statements, with PostgreSQL-specific syntax called out
```

Each file is a standalone set of numbered notes with explanations and examples, so you can jump straight to the topic you need.

## How it's built

There is no build step — this is a documentation-only repository made of plain `.txt` files, meant to be read directly on GitHub or in a text editor. There are no dependencies to install and nothing to compile or run.

To use the examples, you just need a working MySQL or PostgreSQL installation.
