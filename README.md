
 SQL Query Optimization Internship Project

 Project Overview
This project demonstrates SQL query optimization using PostgreSQL. The main focus is to analyze query performance using EXPLAIN ANALYZE and improve execution time using indexing and query optimization techniques.

The project compares query performance before and after optimization on large datasets.

---

 Objective
- To analyze SQL query performance
- To identify slow queries using EXPLAIN ANALYZE
- To optimize queries using indexing
- To compare execution time before and after optimization

---

 Tools Used
- PostgreSQL
- pgAdmin
- SQL (EXPLAIN ANALYZE)
- SQLAlchemy (for ORM optimization concept)

---

 Database Details
- Database Name: internship_task11
- Tables:
  - candidates
  - interview_sessions

---

 Key Operations Performed
- Created large datasets (500,000+ records)
- Executed complex SQL JOIN and GROUP BY queries
- Analyzed query execution plans
- Applied indexing for performance improvement
- Compared execution time before and after optimization

---

Query Optimization Summary

### Query 1
- JOIN with filtering conditions
- Index applied on (status, started_at)
- Execution time reduced after optimization

### Query 2
- GROUP BY query optimization
- Index applied on status column

### Query 3
- JOIN between candidates and interview_sessions
- Index applied on candidate_id

---

Key Learning
- Understanding of query execution plans
- Importance of indexing in performance tuning
- How PostgreSQL optimizer chooses execution strategies
- Real-world database performance improvement techniques

--
Screenshots
Screenshots of EXPLAIN ANALYZE outputs (before and after optimization) are included in the repository.

---

Conclusion
The project successfully demonstrates how SQL query performance can be improved using indexing and optimization techniques. Execution time was significantly reduced for most queries after applying proper indexing strategies.

---

 Author
Internship Project Submission
