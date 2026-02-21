# Distributed Systems & Scalability
Books about systems that run across machines: consistency, failure, latency, throughput, and the unpleasant truth that networks lie. Read these if you build services people depend on.

## Start here

### *Designing Data-Intensive Applications* — Martin Kleppmann
**Tags:** `intermediate` `backend` `distributed-systems` `data`

**Why we recommend it:** Kleppmann explains how modern systems store, move, and process data under real constraints: failures, concurrency, replication, and load. He writes with care, cites research, and connects theory to production systems. Engineers recommend this book because it upgrades your mental model. After you read it, “eventually consistent” stops sounding like magic.

**What you get:**
- Clear explanations of replication, partitioning, transactions, and consensus
- Tradeoffs between logs, queues, streams, and databases
- How to reason about correctness when systems fail
- A strong foundation for architecture and system design work

**Good to know:** It’s dense. Read with notes. Try mapping each chapter to something you run in production.

**Pair it with:** *Distributed Systems* (Tanenbaum/van Steen) for deeper theory.

## Recommended

### *Release It!* — Michael T. Nygard
**Tags:** `intermediate` `devops` `reliability` `backend`

**Why we recommend it:** Nygard writes from scars. He names failure patterns that hit production systems: slow responses, resource leaks, cascading failures, and nasty dependency chains. The book also gives stability patterns you can implement: circuit breakers, bulkheads, timeouts, and sane capacity planning. It reads like a field guide for keeping services alive.

**What you get:**
- Failure patterns that explain real incidents
- Stability patterns you can implement in apps and platforms
- Practical thinking about capacity and dependency risk
- A reliability mindset that pairs well with on-call work

**Good to know:** Some tech examples look old, but the failure patterns repeat in every era. Focus on the forces, not the libraries.

**Pair it with:** *Site Reliability Engineering* for operational practice at scale.

### *Systems Performance* — Brendan Gregg
**Tags:** `advanced` `backend` `performance` `devops`

**Why we recommend it:** Gregg teaches you how to diagnose performance problems methodically. He covers CPUs, memory, disks, kernels, networks, then shows how to connect metrics to user pain. Engineers love this book because it stops random tuning. You learn to form hypotheses, measure, and act with confidence.

**What you get:**
- A method for performance investigation across the full stack
- Tools and techniques for tracing latency and throughput issues
- A deep understanding of operating system behavior
- A way to avoid pointless optimization work

**Good to know:** You need patience and a lab mindset. Start with the methodology chapters, then go to the tool sections as needed.

**Pair it with:** *SQL Performance Explained* when the bottleneck lives in queries.

### *Understanding Distributed Systems* — Roberto Vitillo
**Tags:** `intermediate` `backend` `distributed-systems` `architecture`

**Why we recommend it:** Vitillo explains distributed systems with modern, readable examples and a strong emphasis on intuition. He focuses on the questions engineers ask at work: why do retries hurt, why does consensus cost latency, why does ordering matter. This book suits readers who want clarity without drowning in math.

**What you get:**
- Straight explanations of coordination, replication, and consensus
- Common failure modes: partitions, clock issues, retries, overload
- Practical guidance for system design discussions
- A bridge between intro material and deeper references

**Good to know:** Use it to build intuition, then validate details with DDIA or a more formal text when you design critical systems.

**Pair it with:** *Designing Data-Intensive Applications* for breadth and depth.

### *Distributed Systems* — Maarten van Steen, Andrew S. Tanenbaum
**Tags:** `advanced` `backend` `distributed-systems` `architecture`

**Why we recommend it:** This book gives a formal grounding in distributed systems: models, algorithms, and engineering constraints. It supports deeper learning when you want to understand why an approach works, not only how people implement it. If you study for architecture roles or research-heavy teams, it’s a solid anchor.

**What you get:**
- A rigorous view of distributed system models and algorithms
- Concepts that clarify consistency, coordination, and fault tolerance
- A base for reading research papers with less friction
- Strong mental structure for complex system design

**Good to know:** It reads like a textbook. Mix it with practical case studies so you connect theory to production reality.

**Pair it with:** *Release It!* for the production failure perspective.

### *The Art of Scalability* — Martin L. Abbott, Michael T. Fisher
**Tags:** `intermediate` `backend` `scalability` `devops`

**Why we recommend it:** Abbott and Fisher show scalability as an org and architecture problem, not only a tech trick. They cover patterns for scaling teams, systems, and operations together. The book helps when growth turns simple systems into bottlenecks. It also helps you plan the “next step” without panic rewrites.

**What you get:**
- A practical set of scaling patterns and organizational approaches
- Capacity planning and growth forecasting guidance
- Ways to reduce risk during scaling transitions
- A systems view that connects architecture with operations

**Good to know:** Some content reflects specific eras of infrastructure, yet the planning logic remains valuable. Apply the principles to your platform.

**Pair it with:** *Accelerate* to connect scaling work with delivery outcomes.

### *Site Reliability Engineering* — Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Richard Murphy (editors)
**Tags:** `intermediate` `devops` `sre` `reliability`

**Why we recommend it:** SRE introduced a vocabulary that helps teams balance speed and stability: error budgets, service levels, and blameless incident learning. This book explains that operating model with concrete practices. Even if you never adopt “SRE” as a job title, you can use the ideas to run services with less chaos.

**What you get:**
- Service level objectives and error budgets as decision tools
- Incident response and postmortem practices that improve systems
- Operational patterns for automation and reliability work
- A reliable way to discuss tradeoffs between features and stability

**Good to know:** It reflects a large-organization context. Pull what fits your team size, then keep it lightweight.

**Pair it with:** *The SRE Workbook* for exercises and implementation details.

