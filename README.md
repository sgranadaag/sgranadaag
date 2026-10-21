<h1 align="center">Hi, I'm Santiago</h1>


This profile groups open-source examples and implementations covering software development practices, design, patterns, and technologies. Each one is meant to be freely replicated, with a thorough write-up of what it does and why, so anyone can use it as a reference or a starting point.

Feel free to use, fork, or build on any of it. If you do, I'd appreciate being credited as a co-author on the resulting implementation — not required, just appreciated.

---

### About me

Senior Software Developer with 5+ years of experience. Detailed experience lives on [LinkedIn](https://www.linkedin.com/in/sgranadaag/)

---

### Featured Projects
 
| Project | Description | Tech |
|---|---|---|
| [**next-template**](https://github.com/sgranadaag/next-template) | Reusable Next.js microfrontend template with a pluggable state layer, UI kit, SCSS design system, and multi-stage Docker build. Used as the base architecture for new microfrontends. | `Next.js` `React` `TypeScript` `SCSS` `Jest` `Docker` |
| [**nest-template**](https://github.com/sgranadaag/nest-template) | Reusable NestJS service template: one worked example kept on parallel branches, one per architecture — modular, pragmatic hexagonal, and layered — over Postgres or MongoDB through TypeORM, with unit and e2e tests and lint, standards, and git-hook quality gates. | `NestJS` `TypeScript` `PostgreSQL` `MongoDB` `Jest` `Docker` |
| [**hexagonal**](https://github.com/sgranadaag/hexagonal) | Hexagonal architecture (DDD + Ports & Adapters) template and guide around a Library/Author/Book domain, on two branches: a pure implementation with REST and GraphQL over the same use cases, and a pragmatic one closer to how a team would maintain it. Postgres via TypeORM. | `NestJS` `TypeScript` `GraphQL` `PostgreSQL` |
| [**event-driven**](https://github.com/sgranadaag/event-driven) | Event-driven architecture example, one branch per broker. The RabbitMQ branch shows how each exchange type routes — direct, topic, fanout, and headers — from a producer to specialized consumers, with an architecture diagram, a Postman collection, and a one-command Docker setup. | `NestJS` `TypeScript` `RabbitMQ` `Docker` |
| [**oauth**](https://github.com/sgranadaag/oauth) | Pure OAuth 2.0 (RFC 6749) implementation built from scratch to show how the flows work and why: authorization code, client credentials, and refresh token rotation across a public client, a login app, and an authorization server — with sequence diagrams and a one-command Docker setup. | `NestJS` `Next.js` `TypeScript` `MongoDB` `Docker` |
| [**claude-specs-manager**](https://github.com/sgranadaag/claude-specs-manager) | Portable, stack-agnostic spec-driven development toolkit for Claude Code: a spec-first requirements → design → tasks → implement → commit → verify workflow, enforced by a hook. Each repository keeps its own specs, with shared contracts to keep interfaces between services in sync. | `Claude Code` `Bash` `Markdown` |
| [**claude-jobs-finder**](https://github.com/sgranadaag/claude-jobs-finder) | Claude Code workflow for job hunting: a scout subagent finds and scores offers against a profile, then one subagent per offer tailors the CV — reorganizing real experience, never inventing any — and fills the application form in Chrome, stopping before the final submit. | `Claude Code` `Node.js` `Markdown` |
