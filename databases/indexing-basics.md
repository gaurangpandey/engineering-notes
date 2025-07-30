# Database Indexing – Basics

Indexes are used to improve query performance by reducing
the amount of data scanned during query execution.

## When Indexes Help
- WHERE clauses on frequently filtered columns
- JOIN conditions
- ORDER BY operations on indexed columns

## When Indexes Hurt
- Frequent INSERT/UPDATE operations
- Low-cardinality columns (e.g., boolean flags)

## Common Mistakes
- Over-indexing tables
- Assuming index always improves performance
- Ignoring execution plans

## Practical Tip
Always analyze query execution plans before and after
adding an index.
