<h1 align="center">Hi, I'm James Miller</h1>
<p align="center">full-stack engineer · CS graduate, University of Queensland</p>

## Who Am I?
- full stack software engineer, with an interest in traditional machine learning techniques and concurrency + distributed systems.
- My main goals are to improve my coding skills and build meaningful projects to demonstrate them.
- When I'm not coding I can be found: scuba diving, painting warhammer models, reading or jogging.
  
## Projects
### Tutorlink - [Live Demo](https://tutorlink.dev) · [Frontend](https://github.com/jameswilmiller/TutorLinkFrontEnd) · [Backend](https://github.com/jameswilmiller/TutorLinkBackEnd)
A full-stack tutoring marketplace connecting students with tutors

**Stack:** React · Spring Boot · PostgreSQL · AWS

**Built:**
- JWT auth with refresh-token rotation and a token-revocation flow
- Paginated, database-backed tutor search with indexed lookups
- Global exception handling for consistent, safe API error responses
- Rate limiting, file-upload validation, and async email delivery
- Structured logging plus a Spring Actuator health endpoint for observability
- JUnit test suites across the service layer

### Bash Royale - [repo](https://github.com/bilooty/bash-royale)
Led a team of five to the Best Game prize at UQCS-2026 Hackathon, building a real-time lane-battler (a clone of clash royale) in C# in 48 hours.

**Stack:** C# 

**Built:**
- Deterministic lockstep multiplayer on a fixed tick, using integer-only position and damage maths so two clients advance identical state with no authoritative server
- Targeting system with separate aggro and attack ranges, air/ground layer rules, target persistence between ticks, and stable tie-breaking by unit ID
- A* pathfinding over rectangular unit footprints rather than point positions, so large units path and collide correctly
- Unit and spell behaviours composed from a small set of reusable behaviour types instead of hardcoding each card
- Custom terminal renderer: full frame composed into a buffer and written in a single pass to avoid flicker, with non-blocking input polling so the simulation never stalls on a keypress
- backend built with no rendering or I/O dependencies, so the whole game can be run headless in tests or migrated to a different frontend in future
  
## Open Source  
- [microsoft/vscode-pull-request-github #8840](https://github.com/microsoft/vscode-pull-request-github/pull/8840) — added a feature to easily compare commit SHAs in the commit tree, still awaiting review (first open source contribution!)
