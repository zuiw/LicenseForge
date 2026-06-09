# Database License, Version 1.0 (DBL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license designed for database schemas, database structures, data models,
and database-related scripts, clarifying the relationship between the schema
license and the data stored within it.

## Preamble

Databases present a unique licensing challenge: the schema (structure,
tables, relationships) and the data (the content stored in those structures)
are separate creative works.  The DBL licenses the schema under copyleft
terms while clarifying that the data stored using the schema is not subject
to the license.  Modified schemas must be shared, but the data remains the
data owner's property.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Database License (DBL-1.0).

"The Schema" means the database schema, table definitions, indexes, views,
stored procedures, triggers, data models, and migration scripts licensed
under this License.

"Schema Data" means the structural metadata defined by the Schema, including
table and column definitions, relationships, and constraints.

"User Data" means the actual data records, entries, or content stored within
a database instance that uses the Schema.

"Derived Schema" means a Schema that is based on, modified from, or adapted
from the original Schema.

### 1. Schema License.

The Schema is licensed under copyleft terms.  You may use, modify, and
distribute the Schema, provided that:
- Modified or Derived Schemas are licensed under this License;
- You retain all copyright notices;
- You include a copy of this License.

### 2. Data Exclusion.

User Data stored in a database using the Schema is not subject to this
License.  The data owner retains all rights to their data.  This License
does not require disclosure of User Data, even if the Schema is modified.

### 3. Combined Works.

A software application that uses the Schema (to store or retrieve data) is
not a combined work with the Schema for the purposes of this License.

### 4. Migration Scripts.

Database migration scripts that modify the Schema are considered Derived
Schemas and must be licensed under this License.

### 5. Termination.

Violation of the copyleft requirements (section 1) terminates rights under
this License.  A 60-day cure period applies for a first violation.

### 6. Disclaimer of Warranty.

THE SCHEMA IS PROVIDED "AS IS", WITHOUT WARRANTY OF FITNESS FOR ANY
PARTICULAR DATA OR USE CASE.

### 7. Limitation of Liability.

IN NO EVENT SHALL THE SCHEMA AUTHOR BE LIABLE FOR DATA LOSS OR CORRUPTION.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in the schema file or migration script:

```
-- <Database name> Schema
-- Copyright (C) <year> <author>
-- Licensed under the Database License, version 1.0 (DBL-1.0).
-- User data is not covered by this license.
-- Full terms: <URL>.
```
