# Pagination: SQL vs JPA

Pagination is essential for handling large datasets efficiently.
There are key differences between database-level pagination and
pagination handled by ORM frameworks like JPA.

## SQL-Level Pagination
- Uses LIMIT / OFFSET or ROW_NUMBER()
- Faster for large datasets
- Reduces memory usage
- Better control over execution plans

## JPA Pagination
- Implemented using Pageable
- Easier to implement
- Can cause performance issues if queries are complex
- Depends heavily on underlying SQL generation

## Key Takeaway
For large tables and performance-critical APIs, prefer database-level
pagination and carefully inspect generated SQL when using JPA.
