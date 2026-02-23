# SQL: Security Event Investigation

## Project Description
Tasked with enhancing system security, I used SQL to investigate potential security breaches and audit employee machine access.

## Queries & Logic
- **After-Hours Investigation:** Filtered failed login attempts using `WHERE login_time > '18:00' AND success = FALSE`.
- **Date-Specific Audit:** Investigated activity on specific dates using `WHERE login_date = '2022-05-09' OR login_date = '2022-05-08'`.
- **Location Tracking:** Filtered login attempts from outside the US using `WHERE country NOT LIKE 'USA%'`.
- **Department Audit:** Identified machines in 'Finance' or 'Sales' using the `OR` operator and identified all non-IT staff using `NOT department = 'Information Technology'`.

## Skills Demonstrated
- SQL Filtering (AND, OR, NOT)
- Pattern Matching (LIKE, %)
- Security Log Analysis
