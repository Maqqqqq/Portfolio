# Markus Stamm

Software developer building practical tools across backend, frontend, and security-focused coursework.

This portfolio collects the projects worth reviewing first. I prefer small, working systems with clear behavior, runnable setup, and direct documentation.

## Featured Projects

### Match-me
Full-stack matchmaking platform built as a complete product, not just a CRUD demo.

- Stack: Java 17, Spring Boot, React 19, Vite, PostgreSQL, STOMP/WebSocket, Docker Compose
- Scope: JWT auth, profile management, recommendations, chat, uploads, seeded test data
- Why it matters: strongest end-to-end application here, with real backend state, realtime features, and a multi-service setup
- Details: [projects/match-me.md](./projects/match-me.md)
- Repo: https://github.com/Maqqqqq/match-me

### Digital Detective
CLI for OSINT-style lookups across usernames, IP addresses, and people search data.

- Stack: Python, Typer, requests, Rich-style CLI output, external APIs
- Scope: username checks, IP enrichment, name search, sequential combined lookups
- Why it matters: good example of input validation, external integration, and building a usable command-line workflow
- Details: [projects/digital-detective.md](./projects/digital-detective.md)
- Repo: https://github.com/Maqqqqq/digital-detective

### InvisiBits
Web app for steganography and lightweight digital forensics workflows.

- Stack: Python, Flask, HTML/CSS, Docker
- Scope: hide and recover text in images/audio, optional password protection, compression, detection heuristics, downloadable output
- Why it matters: most distinctive security project in the set, with a concrete user interface and clear domain focus
- Details: [projects/invisibits.md](./projects/invisibits.md)
- Repo: https://github.com/Maqqqqq/invisibits

### Racetrack
Realtime racetrack operations system for front desk, race control, and live status views.

- Stack: Node.js, Express, Socket.IO, Sequelize, SQLite
- Scope: role-based access, lap tracking, race timers, live dashboards, session-backed workflows
- Why it matters: strong operations-style app with multiple user roles and realtime coordination
- Details: [projects/racetrack.md](./projects/racetrack.md)
- Repo: https://github.com/Maqqqqq/racetrack

### DotJS Framework
Custom frontend framework project with runtime and example application.

- Stack: JavaScript, browser runtime, workspace-based monorepo
- Scope: framework runtime, routing, documentation, sample app
- Why it matters: shows lower-level frontend thinking beyond app assembly
- Details: [projects/dotjs-framework.md](./projects/dotjs-framework.md)
- Repo: https://github.com/Maqqqqq/dotjs-framework

### Tronitron 9000
Browser multiplayer survival game inspired by Tron.

- Stack: JavaScript, Node.js, Express, Socket.IO
- Scope: browser-based multiplayer sessions, keyboard controls, host flow, realtime gameplay
- Why it matters: demonstrates event-driven state handling and game-oriented interaction logic
- Details: [projects/tronitron-9000.md](./projects/tronitron-9000.md)
- Repo: https://github.com/Maqqqqq/tronitron-9000

## Additional Projects

### Port Prowler
Network scanning CLI for TCP, UDP, and stealth-style probing.

- Stack: Python
- Scope: port ranges, multithreaded scanning, terminal reporting, optional export
- Value: good systems/networking exercise with a practical CLI surface
- Details: [projects/port-prowler.md](./projects/port-prowler.md)
- Repo: https://github.com/Maqqqqq/port-prowler

### Encrypt-o-matic
File encryption utility with multiple algorithms and operational options.

- Stack: Python, cryptography
- Scope: AES/ChaCha20/Twofish, compression, padding, password-derived keys, timed restore workflow
- Value: strong applied-security exercise with clear feature boundaries
- Details: [projects/encrypt-o-matic.md](./projects/encrypt-o-matic.md)
- Repo: https://github.com/Maqqqqq/encrypt-o-matic

### Binary Fusion
Utility for combining two ELF executables into a single runnable output.

- Stack: Python, GCC, LIEF, Linux ELF tooling
- Scope: executable fusion, binary handling, linker/runtime constraints
- Value: niche and technically interesting systems project
- Details: [projects/binary-fusion.md](./projects/binary-fusion.md)
- Repo: https://github.com/Maqqqqq/binary-fusion

### Movie-API
Backend API for movies, genres, and actors.

- Stack: Java, Spring Boot
- Scope: entity relationships, persistence, API endpoints, Postman-based testing
- Value: useful baseline backend project showing Java fundamentals before larger systems
- Details: [projects/movie-api.md](./projects/movie-api.md)
- Repo: https://github.com/Maqqqqq/movie-api

### Itinerary Prettifier
Java CLI that transforms raw itinerary text into readable airport and time output using lookup data.

- Stack: Java, file I/O, CSV parsing, date/time formatting
- Scope: airport code expansion, date formatting, time conversion, batch text processing
- Value: compact example of parsing, transformation, and command-line problem solving
- Details: [projects/itinerary-prettifier.md](./projects/itinerary-prettifier.md)
- Repo: https://github.com/Maqqqqq/itinerary-prettifier

## What I Would Review First

If I were screening this portfolio as an engineer, I would open projects in this order:

1. Match-me
2. InvisiBits
3. Digital Detective
4. Racetrack
5. DotJS Framework
6. Tronitron 9000

That set shows the best range:

- full-stack product work
- security/domain-specific tooling
- realtime systems
- framework-level frontend thinking
- interactive browser programming

## Public Portfolio Notes

Projects intentionally not included in the public portfolio:

- `audit/`
- any repo containing classroom audit material
- anything that depends on private keys, live secrets, or unsafe public positioning

Projects I would keep private or de-emphasize unless carefully reframed:

- `shifty-shell`
- `bug-bounty`

Reason:
- public portfolio should optimize for professionalism
- security work should stay clearly defensive, educational, or lab-scoped

## Next Improvements

Before publishing, each project repo should have:

- a short outcome-focused README opening
- 1 screenshot or terminal capture
- exact run steps
- tech stack
- 2 to 4 implementation highlights
- one short section on tradeoffs or lessons learned

## Contact

- GitHub: https://github.com/Maqqqqq
- LinkedIn: `add-link`
- Email: `add-email`
