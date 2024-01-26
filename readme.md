# RDBMS Reading list

## Books

- [The Art of PostgreSQL](https://theartofpostgresql.com/)

- [The Art of SQL](https://www.oreilly.com/library/view/the-art-of/0596008945/)

- [SQL Performance Explained](https://sql-performance-explained.com/)

- [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)

- [PostgreSQL 14 Internals](https://postgrespro.com/community/books/internals)

- [PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries 2nd ed. Edition ](https://www.amazon.com/PostgreSQL-Query-Optimization-Ultimate-Efficient/dp/B0CK5GWWQ1)

- [PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://www.oreilly.com/library/view/postgresql-query-optimization/9781484268858/)

## Websites and tutorials

- [PostgreSQL Exercises](https://pgexercises.com/): Nicely organized tutorial for beginner-level, PostgreSQL-flavored SQL. A single dataset is used to present the basics such as querying, joins, DML and aggregates. One shortcoming is that an old version of PostgreSQL is targeted (9.5; for example, it is assumed that columns cannot be in `group by` clauses).

- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)

- [Modern SQL](https://modern-sql.com/)

- [The Internals of PostgreSQL](http://www.interdb.jp/pg/index.html)

## Videos

- [B-tree indexes - learn more about the heart of PostgreSQL](https://www.youtube.com/watch?v=n5-xEEQFqPY)

- [Markus Winand - The Mother of all Query Languages: SQL in the 21st Century](https://www.youtube.com/watch?v=8Fb5Qgpr03g): This talk is on how SQL has changed through the standards published in 1999, 2003 and 2016. It is also a bit sobering as Winand mentions features present in latest SQL standard but did not yet get implemented in PostgreSQL, even after 7 years.

- [EXPLAIN Explained](https://www.youtube.com/watch?app=desktop&v=mCwwFAl1pBU)

## Blog posts

- [10 Easy Steps to a Complete Understanding of SQL](https://blog.jooq.org/10-easy-steps-to-a-complete-understanding-of-sql/): This classic blog post is a good review of the most important differences of SQL and relational differences to the most commonly used class of development language, imperative languages. It's a very good starting point for developers who can't wrap their heads around SQL, and need a frame for reorienting their understanding of relational data technologies.

- [10 Postgres tips for beginners](https://postgres.ai/blog/20230722-10-postgres-tips-for-beginners) is a list of useful tips for those working with PostgreSQL as developers and who want to get the most out of it. Each tip also links to a detailed discussion on the Postgres.fm podcast, with even more links.

- [Choosing a Postgres Primary Key](https://supabase.com/blog/choosing-a-postgres-primary-key)

- [What is the deal with NULLs?](http://thoughts.davisjeff.com/2009/08/02/what-is-the-deal-with-nulls/)

- [Transaction ID Wraparound in Postgres](https://blog.sentry.io/transaction-id-wraparound-in-postgres/)

- [Alembic: How to add a non-nullable field to a populated table](https://archive.is/JY4lq)

- [Don't Do This](https://wiki.postgresql.org/wiki/Don%27t_Do_This)

- [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)

- [Modern SQL in Open Source and Commercial Databases](https://www.slideshare.net/MarkusWinand/modern-sql) is a set of slides from another talk by Markus Winand as the one linked above.

- [My Favorite PostgreSQL Queries and Why They Matter](https://severalnines.com/blog/my-favorite-postgresql-queries-and-why-they-matter)

- [10 Things I Hate About PostgreSQL](https://rbranson.medium.com/10-things-i-hate-about-postgresql-20dbab8c2791)

- [Why Uber Engineering Switched from Postgres to MySQL](https://www.uber.com/en-GB/blog/postgres-to-mysql-migration/)

## Postgresql Wiki and Documentation

- [Information about the SSI implementation for the SERIALIZABLE transaction isolation level in PostgreSQL](https://wiki.postgresql.org/wiki/Serializable)

- [Documentation of Serializable Snapshot Isolation (SSI) in PostgreSQL compared to plain Snapshot Isolation (SI)](https://wiki.postgresql.org/wiki/SSI)

## Specific topics and tips

- [The Many Faces of DISTINCT in PostgreSQL](https://hakibenita.com/the-many-faces-of-distinct-in-postgre-sql) is a great blog post explaining four different uses of `DISTINCT` in PostgreSQL. I didn't even know there were that many different `DISTINCT` ways. One of them, `DISTINCT ON`, is particularly elegant and useful.

- [Beware of JSON fields in SQLAlchemy](https://amercader.net/blog/beware-of-json-fields-in-sqlalchemy/)

## Advanced

- [Divided We Stand: The SQL of Relational Division](https://www.red-gate.com/simple-talk/databases/sql-server/t-sql-programming-sql-server/divided-we-stand-the-sql-of-relational-division/)
