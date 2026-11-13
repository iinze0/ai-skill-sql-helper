---
name: sql-helper
description: "Write, optimize, debug, and explain SQL queries. Use for SELECT, JOINs, aggregations, performance, and query understanding."
type: workflow
lifecycle: active
---

# SQL Helper

Assist with writing and improving SQL.

## Core Workflow

1. Understand the goal and available schema (ask if missing).
2. Write a clear, correct query.
3. Optimize for performance when relevant (indexes, avoid SELECT *, proper joins).
4. Explain the query logic in plain language.
5. Suggest alternatives or improvements.
6. Note potential issues (nulls, cartesian products, locking, etc.).

## Common Patterns

- Aggregations with GROUP BY / HAVING
- Window functions
- CTEs for readability
- Proper JOIN types

Always consider database dialect if specified (PostgreSQL, MySQL, SQL Server, etc.).
