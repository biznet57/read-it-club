# Security & Privacy Engineering
Books that build security thinking into engineering work: threat modeling, secure design, crypto basics that matter, and the practical problems attackers exploit.

## Start here

### *Threat Modeling* — Adam Shostack
**Tags:** `beginner` `security` `threat-modeling` `secure-coding`

**Why we recommend it:** Shostack teaches a structured way to ask: what can go wrong, and what do we do about it. He frames threat modeling as an engineering activity you can schedule and repeat, not as a scary one-time audit. Teams like this book because it fits real delivery. You can run a threat modeling session in an afternoon and leave with an actionable list.

**What you get:**
- A repeatable threat modeling process that teams can adopt
- Ways to identify assets, attackers, entry points, and trust boundaries
- Practical mitigation thinking tied to design decisions
- Techniques for making security discussions less emotional and more concrete

**Good to know:** Start with a small system, then apply the method to bigger services. Keep it lightweight so teams actually do it.

**Pair it with:** *Designing Secure Software* for secure design decisions in code.

## Recommended

### *Designing Secure Software* — Loren Kohnfelder
**Tags:** `intermediate` `security` `secure-coding` `architecture`

**Why we recommend it:** Kohnfelder focuses on the engineering side of security: how design choices create or reduce risk. He explains common security problems in a way that fits software architecture work. You can use the book as a checklist during design reviews, and it will catch issues before you write code. That saves time and avoids painful fixes later.

**What you get:**
- Security design patterns and common attack paths
- Threat modeling thinking applied to real software components
- Guidance on authentication, authorization, and trust boundaries
- A practical way to connect requirements to security controls

**Good to know:** Security changes fast, yet the attack patterns stay familiar. Validate specific best practices against current standards in your ecosystem.

**Pair it with:** *Threat Modeling* to run structured sessions with your team.

### *Security Engineering* — Ross Anderson
**Tags:** `advanced` `security` `security` `architecture`

**Why we recommend it:** Anderson covers security across systems, organizations, and real adversaries. He moves beyond app-level bugs and looks at incentives, physical constraints, economics, and operational reality. This book suits readers who want deep grounding. It will improve your judgment when you design systems that handle money, identity, or safety.

**What you get:**
- Security thinking across technical and human systems
- Concepts that explain why attacks succeed in practice
- A broad view: hardware, networks, protocols, and operations
- A base for reading deeper security research with confidence

**Good to know:** It’s big and dense. Use it as a reference: read chapters that match your current work.

**Pair it with:** *Threat Modeling* for a lighter, project-focused workflow.

### *Real-World Cryptography* — David Wong
**Tags:** `intermediate` `security` `crypto` `secure-coding`

**Why we recommend it:** Wong explains cryptography as engineers actually meet it: TLS, signatures, hashing, randomness, and protocol design mistakes. He writes for builders who need enough crypto to avoid dangerous errors. If you work with authentication, tokens, encryption, or secure channels, this book gives you the right mental safety rails.

**What you get:**
- Practical crypto foundations without heavy math overhead
- How modern protocols use primitives, and where they fail
- Common implementation mistakes and how to avoid them
- A clearer way to review crypto-related code and designs

**Good to know:** Don’t treat it as permission to invent your own crypto. Use it to understand what libraries do and how to use them safely.

**Pair it with:** *Serious Cryptography* for more depth on primitives and their properties.

### *Serious Cryptography* — Jean-Philippe Aumasson
**Tags:** `intermediate` `security` `crypto` `architecture`

**Why we recommend it:** Aumasson explains crypto primitives with clarity: block ciphers, stream ciphers, MACs, hashes, and key exchange. He helps you reason about what a primitive guarantees and what it does not. That skill matters when you review designs that claim “encryption” without defining threat models. You’ll spot weak assumptions faster.

**What you get:**
- A clear tour of modern crypto primitives and their uses
- Threat-model-driven thinking about what security claims mean
- Practical guidance on choosing primitives responsibly
- Better intuition for protocol and system design reviews

**Good to know:** Crypto stays tricky. Use the book to understand, then rely on mature libraries and current guidance for implementation choices.

**Pair it with:** *Real-World Cryptography* for protocol-focused applied examples.

### *The Tangled Web* — Michal Zalewski
**Tags:** `advanced` `security` `web-security` `secure-coding`

**Why we recommend it:** Zalewski explains how browsers and web platforms behave, where they break, and why web security feels weird. He covers same-origin policy, cookies, session handling, and the edge cases attackers love. If you build web apps, you will recognize your own bugs in these pages. The book teaches you to think like the platform and like an attacker.

**What you get:**
- A deep understanding of browser security models and pitfalls
- Common web attack paths and the mechanics behind them
- Practical thinking about sessions, origins, and user-driven flows
- A stronger foundation for secure front-end and back-end design

**Good to know:** Parts reflect older browser eras. Still, many conceptual traps remain. Pair it with current platform docs for modern specifics.

**Pair it with:** *Designing Secure Software* for a broader secure design view.

### *Securing DevOps* — Julien Vehent
**Tags:** `intermediate` `devops` `devsecops` `security`

**Why we recommend it:** Vehent bridges security and operations without turning it into bureaucracy. He covers secure CI/CD, infrastructure hardening, logging, incident response, and security monitoring that supports real operations. If your org fights about “security slowing us down”, this book gives practical compromise: automate controls, measure outcomes, ship safely.

**What you get:**
- Security practices for pipelines, infrastructure, and deployment workflows
- Logging and monitoring approaches that support detection and response
- Practical guidance on access control and secrets handling
- A delivery-friendly view of security controls

**Good to know:** Security tooling changes quickly. Keep the principles, then map them to your current platform and services.

**Pair it with:** *The DevOps Handbook* for broader delivery practices.

