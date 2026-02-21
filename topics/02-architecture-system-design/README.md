# Architecture & System Design
Books about shaping systems that survive growth: boundaries, tradeoffs, domain modeling, and change over time. Expect fewer “patterns as trivia”, more decision thinking.

## Start here

### *Fundamentals of Software Architecture* — Mark Richards, Neal Ford
**Tags:** `beginner` `architect` `architecture` `design`

**Why we recommend it:** Richards and Ford teach architecture as a set of tradeoffs you choose on purpose. They explain common architectural styles, how to evaluate them, and how to reason about qualities like scalability and deployability. Teams like this book because it gives structure to messy debates. You stop arguing opinions and start comparing constraints.

**What you get:**
- A framework for architectural characteristics and tradeoffs
- A practical tour of common styles and when they fit
- Guidance on fitness functions and architecture governance
- A vocabulary that helps in system design interviews and real design reviews

**Good to know:** Use it as a map, then dive deeper into a style you actually run. It won’t replace hands-on experience, it will speed it up.

**Pair it with:** *Building Evolutionary Architectures* for change-friendly systems.

## Recommended

### *Domain-Driven Design* — Eric Evans
**Tags:** `advanced` `backend` `ddd` `architecture`

**Why we recommend it:** Evans wrote the book that made many teams take domain language seriously. He shows how domain modeling drives code structure, not just diagrams. When your system turns into a mess of “service” classes and unclear responsibilities, DDD offers a way out: bounded contexts, ubiquitous language, and models that match business reality.

**What you get:**
- Techniques to align code and domain language with stakeholders
- Patterns for boundaries: aggregates, entities, value objects
- Guidance for splitting domains into bounded contexts
- A model-first way to reduce accidental complexity

**Good to know:** The book expects patience. Read slowly, discuss with teammates, then try one DDD tactic in a real project.

**Pair it with:** *Implementing Domain-Driven Design* for a more hands-on path.

### *Implementing Domain-Driven Design* — Vaughn Vernon
**Tags:** `advanced` `backend` `ddd` `architecture`

**Why we recommend it:** Vernon turns DDD from concept into working code and team practices. He shows concrete building blocks, then connects them to messaging, persistence, and service boundaries. If you like DDD but struggle to apply it without overengineering, this book helps you pick a sane slice and ship it.

**What you get:**
- Step-by-step guidance for applying DDD patterns in code
- Practical advice on bounded contexts and context mapping
- Examples of domain events and messaging in real systems
- A clearer path from model to implementation

**Good to know:** Examples use specific stacks, so translate the structure rather than copy-paste. Keep an eye on scope and avoid turning every module into a cathedral.

**Pair it with:** *Microservices Patterns* when your boundaries become services.

### *Patterns of Enterprise Application Architecture* — Martin Fowler
**Tags:** `intermediate` `backend` `architecture` `design`

**Why we recommend it:** Fowler catalogs patterns that show up in real business software: transactions, data access, layering, and integration. The book helps when you inherit an enterprise codebase and need to understand why it looks the way it does. It also helps you avoid repeating old mistakes, like mixing domain logic into persistence glue.

**What you get:**
- Patterns for organizing application layers and domain logic
- Data access approaches and their tradeoffs
- Concepts that clarify transactions and consistency
- A reference you can return to during design work

**Good to know:** Some patterns reflect older enterprise stacks. Still, the forces behind them remain familiar. Read it as architecture history with practical payoffs.

**Pair it with:** *Refactoring* when you need to change an enterprise codebase safely.

### *Building Evolutionary Architectures* — Neal Ford, Rebecca Parsons, Patrick Kua
**Tags:** `intermediate` `architect` `architecture` `reliability`

**Why we recommend it:** This book treats architecture as something that changes, because reality changes. The authors show how to guard system qualities with automation, tests, and measurable signals. That approach prevents “architecture by slide deck”. You build guardrails, then you let teams move fast without breaking the system.

**What you get:**
- Fitness functions: measurable checks for architectural qualities
- Practical ways to keep design aligned with delivery
- Techniques to manage change in large systems over time
- A delivery-centered view of architecture governance

**Good to know:** You need some CI discipline to get full value. Start small: one fitness check, one critical quality, one team.

**Pair it with:** *Accelerate* for delivery metrics that support the same goal.

### *Microservices Patterns* — Chris Richardson
**Tags:** `intermediate` `backend` `microservices` `architecture`

**Why we recommend it:** Richardson focuses on the hard parts of microservices: data, transactions, communication, and failure. He explains patterns like saga, event sourcing, and API composition in a way that connects design to operations. If your team plans a microservices move, read this book before you draw boxes on a whiteboard.

**What you get:**
- Concrete patterns for service communication and data ownership
- Guidance on distributed transactions and sagas
- Approaches to service discovery, gateways, and integration
- A realistic view of operational complexity and failure modes

**Good to know:** Microservices add overhead. The book helps you choose them for the right reasons, not because it sounds modern.

**Pair it with:** *Designing Data-Intensive Applications* for the data and consistency foundations.

### *Clean Architecture* — Robert C. Martin
**Tags:** `intermediate` `backend` `architecture` `design`

**Why we recommend it:** Martin argues for boundaries that protect business logic from frameworks and I/O noise. The style fits teams who want testable core logic and flexible delivery options. You may disagree with some opinions, yet the boundary thinking remains useful. It helps you reason about coupling and dependency direction without fancy tooling.

**What you get:**
- A clear boundary model: entities, use cases, interfaces, drivers
- Guidance on dependency direction and testability
- Patterns to keep frameworks from owning your code
- A way to teach architecture basics inside teams

**Good to know:** Treat the diagrams as guidance, not doctrine. The best result looks simple in your stack, not like a textbook clone.

**Pair it with:** *A Philosophy of Software Design* for a complexity-focused viewpoint.

