# Software Engineering Craft
Books that sharpen day-to-day engineering work: naming, design pressure, refactoring, testing habits, and the boring details that decide quality.

## Start here

### *The Pragmatic Programmer* — Andrew Hunt, David Thomas
**Tags:** `beginner` `backend` `craft` `design`

**Why we recommend it:** Hunt and Thomas write like working engineers who ship code, fix mistakes, then ship again. The book nudges you toward small habits that compound: automation, readable code, sharp feedback loops, and calm decision-making under deadline pressure. It avoids theory cosplay. You can apply a chapter the same day you read it, and your team will notice.

**What you get:**
- A mental checklist for everyday choices: code structure, naming, boundaries
- A practical view of automation and tooling that saves time fast
- Guidelines for taking ownership without turning into a control freak
- Ideas for learning deliberately, not randomly

**Good to know:** Some examples reflect older tooling, so map the principle to your stack. Read it as a book of habits, not a catalog of technologies.

**Pair it with:** *Code Complete* for deeper engineering mechanics.

### *Code Complete* — Steve McConnell
**Tags:** `beginner` `backend` `craft` `testing`

**Why we recommend it:** McConnell treats software construction as a discipline, not vibes. He breaks down design, coding, debugging, and testing into choices you can measure. Many teams skip these basics, then wonder why they burn time in rewrites. This book gives you language to argue for quality without sounding preachy.

**What you get:**
- Concrete guidance on code construction: complexity, readability, defensive practices
- Practical debugging techniques and error prevention habits
- A clear view of testing and quality gates in everyday work
- A shared vocabulary for code reviews and engineering standards

**Good to know:** It’s long. Skim sections that repeat what you already do, then go deep on the chapters that hit your pain points.

**Pair it with:** *Software Engineering at Google* for process at scale.

## Recommended

### *Clean Code* — Robert C. Martin
**Tags:** `beginner` `backend` `craft` `design`

**Why we recommend it:** This book pushes a simple claim: messy code taxes your team every single week. Martin shows what “clean” looks like in practice, with examples you can debate in code review. Some sections feel opinionated, and that’s fine. Use it to train your eye, then adapt the rules to your domain.

**What you get:**
- Rules-of-thumb for naming, functions, and class structure
- A framework for code reviews that focuses on maintainability
- Guidance on tests as part of design, not an afterthought
- Smell detection: spot trouble before it grows

**Good to know:** Treat it as a style guide starter, not a law book. Some examples use Java-era conventions that you may translate to modern patterns.

**Pair it with:** *Refactoring* for structured change work.

### *Refactoring* — Martin Fowler
**Tags:** `intermediate` `backend` `refactoring` `design`

**Why we recommend it:** Fowler makes refactoring a repeatable skill instead of a risky weekend project. He names the moves, explains why they work, and shows how to keep behavior stable while you reshape code. Engineers reach for this book when they face a system that “works” yet blocks new features.

**What you get:**
- A catalog of refactorings you can apply in small steps
- Techniques for keeping behavior stable during change
- A clearer sense of what to test before and after edits
- A mindset shift: improvement as steady routine, not heroics

**Good to know:** You need tests or at least safety nets to refactor fast. If your codebase lacks them, read *Working Effectively with Legacy Code* next.

**Pair it with:** *Working Effectively with Legacy Code* when tests feel missing.

### *Working Effectively with Legacy Code* — Michael Feathers
**Tags:** `intermediate` `backend` `refactoring` `testing`

**Why we recommend it:** Feathers speaks to anyone who inherits a codebase and feels trapped by it. He shows how to create seams, add tests around scary areas, then change code safely. The advice fits enterprise apps, startups, scripts, and everything in between. It turns “legacy” from an insult into a solvable engineering state.

**What you get:**
- Techniques to add tests when code resists testing
- Practical steps to break dependencies and create seams
- Strategies to reduce risk in high-change modules
- Language to plan and justify cleanup work

**Good to know:** Some examples look dated, yet the constraints stay the same: tight coupling, hidden side effects, and fear-driven development.

**Pair it with:** *Refactoring* for a systematic set of transformations.

### *A Philosophy of Software Design* — John Ousterhout
**Tags:** `intermediate` `backend` `design` `craft`

**Why we recommend it:** Ousterhout argues for one main goal: reduce complexity aggressively. He writes from experience building large systems, and he treats complexity as a cost you can see and manage. The book gives crisp advice on interfaces, modules, and naming that improves your architecture without a massive rewrite.

**What you get:**
- A practical definition of complexity and how it spreads
- Guidelines for module boundaries and interface design
- Advice on comments that help, not noise
- A way to talk about design tradeoffs with your team

**Good to know:** Some readers disagree with parts of his style guidance. That’s normal. Test the ideas on your own code and keep what works.

**Pair it with:** *Fundamentals of Software Architecture* for system-level tradeoffs.

### *Software Engineering at Google* — Titus Winters, Tom Manshreck, Hyrum Wright
**Tags:** `intermediate` `backend` `testing` `craft`

**Why we recommend it:** This book explains how Google thinks about engineering work at scale: code health, reviews, testing, ownership, and long-term maintenance. You don’t need Google’s size to benefit. The value comes from the framing: you manage a codebase for years, so you optimize for sustainability and clarity.

**What you get:**
- Clear principles behind code review, testing, and design choices
- A strong argument for code health as a product feature
- Guidance for building social processes that support quality
- Useful terms for discussing technical debt without drama

**Good to know:** The organization examples reference big-company reality, yet the core ideas translate to smaller teams if you keep them lightweight.

**Pair it with:** *Code Complete* for construction-level depth.

