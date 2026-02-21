# Databases & Data Modeling
Books for engineers who want better data decisions: query performance, storage engines, transactions, modeling for OLTP and OLAP, and the practical realities of running databases.

## Start here

### *SQL Performance Explained* — Markus Winand
**Tags:** `beginner` `data` `sql` `performance`

**Why we recommend it:** Winand teaches query performance without hand-wavy advice. He explains indexes, execution plans, and how SQL engines actually use your schema. The style stays clear and direct. If you ever guessed at indexing, then prayed, this book will feel like a relief.

**What you get:**
- How indexes work and when they help
- How to read execution plans with confidence
- Schema and query patterns that avoid hidden slow paths
- A mindset for testing performance changes safely

**Good to know:** Examples focus on SQL fundamentals, so they translate across major databases. Still, check your engine’s specifics when you tune edge cases.

**Pair it with:** *Database Internals* when you want deeper engine mechanics.

## Recommended

### *Database Internals* — Alex Petrov
**Tags:** `advanced` `data` `databases` `performance`

**Why we recommend it:** Petrov explains how database engines store data, build indexes, and guarantee durability and consistency. The book connects algorithms to the code paths that real engines use. When you debug performance issues or design storage-heavy systems, this knowledge pays back fast. You stop treating the database as a black box.

**What you get:**
- Storage engines: B-trees, LSM trees, compaction, write paths
- Transactions, locking, MVCC, and durability mechanics
- Replication and distributed storage building blocks
- A foundation for comparing databases beyond marketing claims

**Good to know:** It asks for focus. Read one chapter, then map it to your database’s behavior. That practice will stick.

**Pair it with:** *Systems Performance* for end-to-end bottleneck hunting.

### *Seven Databases in Seven Weeks* — Eric Redmond, Jim R. Wilson
**Tags:** `intermediate` `data` `sql` `nosql`

**Why we recommend it:** This book gives a guided tour of multiple database models: relational, key-value, document, graph, columnar, and more. You learn what each model optimizes for, and what it sacrifices. It suits teams that face technology sprawl or want to choose a database with clear reasoning.

**What you get:**
- Hands-on exposure to different data models and query styles
- A clearer view of tradeoffs: consistency, flexibility, performance
- Vocabulary for evaluating databases in architecture reviews
- Enough context to avoid bad tool choices

**Good to know:** Treat it as a sampler, not a mastery path. After a chapter, pick one database and study it in depth with its official docs.

**Pair it with:** *Designing Data-Intensive Applications* to tie models to distributed constraints.

### *The Data Warehouse Toolkit* — Ralph Kimball, Margy Ross
**Tags:** `intermediate` `data` `data-modeling` `olap`

**Why we recommend it:** Kimball and Ross explain dimensional modeling with a focus on analytics and reporting. They show how to design star schemas, manage slowly changing dimensions, and build data marts that serve business questions. If your dashboards feel unreliable or your analysts fight the model, this book gives practical structure.

**What you get:**
- Dimensional modeling fundamentals and schema design patterns
- Guidance on facts, dimensions, and slowly changing dimensions
- A business-question-first approach to warehouse design
- A shared language for data teams and stakeholders

**Good to know:** Tooling changed a lot since early editions, yet dimensional modeling keeps showing up in modern stacks. Apply the modeling approach with your warehouse platform.

**Pair it with:** *Inspired* for product-level thinking about what data should answer.

### *Transaction Processing* — Jim Gray, Andreas Reuter
**Tags:** `advanced` `data` `databases` `architecture`

**Why we recommend it:** Gray and Reuter explain transactions as a foundation for reliable systems. The book covers ACID properties, concurrency control, logging, recovery, and system design for transactional workloads. It’s demanding, yet it rewards you when you build systems that must not lose money, state, or trust.

**What you get:**
- A deep view of concurrency control and recovery
- Concepts that clarify what ACID really means in practice
- Design constraints for high-integrity transactional systems
- A strong base for reasoning about correctness

**Good to know:** It reads like a serious engineering text. Pair it with modern case studies to connect the ideas to today’s databases.

**Pair it with:** *Designing Data-Intensive Applications* for modern distributed context.

### *High Performance MySQL* — Baron Schwartz, Peter Zaitsev, Vadim Tkachenko (and contributors)
**Tags:** `intermediate` `backend` `mysql` `performance`

**Why we recommend it:** This book helps engineers run MySQL with fewer surprises. It covers schema design, indexing, query patterns, replication, and operational tuning. Many teams use MySQL for years without learning how it behaves under load. This book closes that gap, and it gives you a debugging playbook.

**What you get:**
- Practical indexing and query tuning guidance
- Replication concepts and common operational failure modes
- Schema and workload patterns that improve stability
- Tools and metrics that help you diagnose issues faster

**Good to know:** MySQL versions change, so validate configuration details against your release. Still, the diagnostic approach stays valuable.

**Pair it with:** *SQL Performance Explained* for the indexing and plan fundamentals.

### *Designing Data-Intensive Applications* — Martin Kleppmann
**Tags:** `intermediate` `data` `distributed-systems` `data-modeling`

**Why we recommend it:** DDIA earns a second spot here because it connects data modeling to system behavior under failure. It ties together storage engines, replication, stream processing, and consistency. If you design data flows across services, you need this mental model. It will save you from costly “works on my machine” architecture.

**What you get:**
- How data models affect throughput, latency, and correctness
- Replication and partitioning tradeoffs for real workloads
- A clear way to think about streams, logs, and processing
- Language to communicate data tradeoffs across teams

**Good to know:** The book demands attention. Take notes. You will reuse them for years.

**Pair it with:** *Microservices Patterns* when data boundaries turn into service boundaries.

