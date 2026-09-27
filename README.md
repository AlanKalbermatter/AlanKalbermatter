### Alan Kalbermatter — Senior AI Software Engineer

I build AI agents that do real engineering work inside large, long-lived codebases, along with the backend systems they run against.
6+ years in backend and distributed systems (Java/Spring, event-driven architectures). Lately my focus has been on making LLM agents reliable on legacy code, where context is scarce and a mistake is expensive.

#### Selected impact

- **AI development agent for a legacy platform.** Designed and built an agent that analyzes the codebase, implements changes and manages its own long-term memory, on a custom architecture made for a large legacy system. It **raised team output 2–4× over two quarters**.
- **MCP tooling for the engineering team.** Built a suite of six MCP servers that connect AI coding agents to internal systems and team workflows, so agents act on real data instead of guesses.

#### What I focus on

- **Context engineering:** deciding what an agent should read, what it should skip, and what it should remember between sessions.
- **Validation boundaries:** matching each agent's autonomy to how strongly its output can be verified.
- **Clean integration:** evolving legacy systems through small, reviewable changes instead of large rewrites.

#### Selected work

| Project | What it shows |
|---|---|
| [event-saga-kafka](https://github.com/AlanKalbermatter/event-saga-kafka) | Distributed transactions using Saga choreography on Kafka, with 6 Spring Boot services and Kafka Streams read models |
| [heavy-algorithm](https://github.com/AlanKalbermatter/heavy-algorithm) | Top-K over unbounded streams: min-heap vs TreeMap trade-offs, measured with benchmarks |
| [timetotrack](https://github.com/AlanKalbermatter/timetotrack) | Vert.x modular monolith behind a JWT-validating gateway, DB-enforced invariants, Testcontainers-tested, one-command Docker setup |
| [shootage](https://github.com/AlanKalbermatter/shootage) | Genetic algorithm that evolves targets to dodge the player: selection, crossover, mutation and fitness shaping |
| [utn-frre-organizer](https://github.com/AlanKalbermatter/utn-frre-organizer) | Rules engine checked against official regulations, with 53 tests and CI, [live on GitHub Pages](https://alankalbermatter.github.io/utn-frre-organizer/) |
| [portfolio-service](https://github.com/AlanKalbermatter/portfolio-service) | Spring Boot 3 REST API with PostgreSQL/H2 profiles, containerized with Docker Compose |

Most of my production work lives in private repositories.

#### Stack

**Languages:** Java · TypeScript · Python  
**Backend & data:** Spring Boot · Vert.x · Kafka · PostgreSQL · MongoDB  
**AI engineering:** LLM agents · MCP · context engineering · agent memory  
**Delivery:** Docker · AWS · GitHub Actions · Jenkins

#### Contact

[LinkedIn](https://www.linkedin.com/in/alan-kalbermatter-81a3b1124/) · alan.kalbermatter.dev@gmail.com
