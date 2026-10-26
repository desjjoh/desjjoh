# John Desjardins

**Full-Stack Software Engineer** focused on building secure, maintainable, production-minded application systems across frontend and backend boundaries.

My primary experience is in TypeScript application development with React, Vue, Node.js, NestJS, and Express, alongside cross-ecosystem work in Python/FastAPI and Java/Spring.

## QuickReference

**QuickReference** is a family of cross-framework and cross-domain reference projects exploring how consistent software-engineering principles translate across different technologies and types of applications.

Rather than making every implementation identical, each project applies the conventions and strengths of its ecosystem while preserving the underlying engineering goals.

The family currently includes:

- **QuickAPI** — backend APIs and application services;
- **QuickFE** — frontend applications and reusable UI/application architecture;

Future QuickReference series may explore other software domains where the same principles can be applied meaningfully.

Across the family, the projects focus on concerns such as:

- clear application and architectural boundaries;
- explicit ownership of state and behavior;
- validated, typed contracts where appropriate;
- deliberate persistence and data lifecycle management;
- security, robustness, and runtime safeguards;
- structured logging, diagnostics, health, and observability;
- meaningful automated testing at the appropriate layers;
- CI-enforced quality gates;
- reproducible builds and deployment or distribution artifacts;
- documentation of architecture, behavior, and engineering decisions.

Not every concern applies equally to every software domain. Part of QuickReference is demonstrating how engineering priorities change with the problem rather than forcing the same architecture everywhere.

## Start Here

### [QuickAPI-NestJS](https://github.com/desjjoh/QuickAPI-NestJS) + [QuickFE-Vue3](https://github.com/desjjoh/QuickFE-Vue3)

The primary backend and frontend projects in the QuickReference family, developed as a matching application platform.

**QuickAPI-NestJS** demonstrates a larger production-oriented backend with identity, account management, sessions, authorization, auditing, background work, observability, testing, and deployment concerns.

**QuickFE-Vue3** is its frontend counterpart, with typed API integration, authentication/session behavior, reusable application and interaction primitives, localization, responsive application shells, and account-oriented workflows.

## QuickReference Projects

### QuickAPI

Backend API and application-service reference implementations.

| Project                                                | Status                  | Focus                                                                                                                                                                                    |
| ------------------------------------------------------ | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [NestJS](https://github.com/desjjoh/QuickAPI-NestJS)   | **Flagship / Active**   | Full application backend covering identity, authorization, auditing, media, persistence, observability, testing, and hardened release delivery.                                |
| [Express](https://github.com/desjjoh/QuickAPI-Express) | **Advanced / Active**   | Focused Express and TypeScript service demonstrating explicit middleware boundaries, MySQL persistence, migrations, operational safeguards, layered testing, and container verification. |
| [FastAPI](https://github.com/desjjoh/QuickAPI-FastAPI) | **Advanced Foundation** | Async Python service applying the QuickAPI principles through Pydantic, SQLAlchemy, ASGI middleware, lifecycle management, layered tests, and container CI.                              |
| [Spring](https://github.com/desjjoh/QuickAPI-Spring)   | **Early Development**   | Initial Java and Spring Boot implementation establishing validated configuration and the foundation for a future QuickAPI architecture.                                                  |

### QuickFE

Frontend application and reusable UI/application architecture reference implementations.

| Project                                           | Status                | Focus                                                                                                                                                                          |
| ------------------------------------------------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Vue3](https://github.com/desjjoh/QuickFE-Vue3)   | **Flagship / Active** | Application frontend paired with QuickAPI-NestJS, covering typed integration, secure session behavior, reusable UI architecture, accessibility, testing, and runtime delivery. |
| [React](https://github.com/desjjoh/QuickFE-React) | **In Progress**       | React and TypeScript foundation focused on reusable components, design tokens, themes, localization, routing, and accessible interaction patterns.                             |

## Engineering Focus

I am particularly interested in how strong engineering principles apply across different kinds of software. I enjoy taking requirements that are still unclear and turning them into systems with clear responsibilities, predictable behavior, and boundaries that remain easy to understand as the software grows.

I care about choosing the right level of validation, testing, documentation, and operational visibility for each project. The goal is to build software that is not only functional during development, but remains understandable and dependable once it is running in a real environment.
