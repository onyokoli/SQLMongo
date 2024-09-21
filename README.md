# SQLMongo


## Overview

SQLMongo is a powerful tool that enables seamless interaction between MongoDB and SQL databases.


## Usage

To use SQLMongo, simply run the command:


```bash
$ sqlmongo

SQLMongo CLI
-------------------

> help

Available commands:
  help         Display available commands
  exit         Exit the CLI
  version      Display version information
  sql          Execute a SQL query on a MongoDB database
  mongo        Execute a MongoDB query on a SQL database
  connect      Connect to a MongoDB or SQL database
  disconnect   Disconnect from the current database

> connect mongodb://localhost:27017

Connected to MongoDB database

> sql SELECT * FROM users

Executing SQL query on MongoDB database...

> mongo { find: 'users', filter: { name: 'John' } }

Executing MongoDB query on SQL database...

> exit

Exiting SQLMongo CLI...
