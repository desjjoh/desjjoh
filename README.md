# John Desjardins

**Senior Full-Stack Software Engineer** focused on building secure, maintainable, production-minded application systems across frontend and backend boundaries.

My primary experience is in TypeScript application development with React, Vue, Node.js, NestJS, and Express, alongside cross-ecosystem work in Python/FastAPI and Java/Spring.

## QuickReference

**QuickReference** is a family of cross-framework and cross-domain reference projects exploring how consistent software-engineering principles translate across different technologies and types of applications.

Rather than making every implementation identical, each project applies the conventions and strengths of its ecosystem while preserving the underlying engineering goals.

The family currently includes:

* **QuickAPI** — backend APIs and application services;
* **QuickFE** — frontend applications and reusable UI/application architecture;
* **QuickGame** — planned real-time and game-software reference projects.

Future QuickReference series may explore other software domains where the same principles can be applied meaningfully.

Across the family, the projects focus on concerns such as:

* clear application and architectural boundaries;
* explicit ownership of state and behavior;
* validated, typed contracts where appropriate;
* deliberate persistence and data lifecycle management;
* security, robustness, and runtime safeguards;
* structured logging, diagnostics, health, and observability;
* meaningful automated testing at the appropriate layers;
* CI-enforced quality gates;
* reproducible builds and deployment or distribution artifacts;
* documentation of architecture, behavior, and engineering decisions.

Not every concern applies equally to every software domain. Part of QuickReference is demonstrating how engineering priorities change with the problem rather than forcing the same architecture everywhere.

## Start Here

### [QuickAPI-NestJS](https://github.com/desjjoh/QuickAPI-NestJS) + [QuickFE-Vue3](https://github.com/desjjoh/QuickFE-Vue3)

The primary backend and frontend projects in the QuickReference family, developed as a matching application platform.

**QuickAPI-NestJS** demonstrates a larger production-oriented backend with identity, account management, sessions, authorization, auditing, background work, observability, testing, and deployment concerns.

**QuickFE-Vue3** is its frontend counterpart, with typed API integration, authentication/session behavior, reusable application and interaction primitives, localization, responsive application shells, and account-oriented workflows.

## QuickReference Projects

| Project                                                         | Series       | Status                | Focus                                                                                                                                      |
| --------------------------------------------------------------- | ------------ | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [QuickAPI-NestJS](https://github.com/desjjoh/QuickAPI-NestJS)   | **QuickAPI** | **Mature / Active**   | Primary backend reference and the most complete QuickAPI implementation.                                                                   |
| [QuickFE-Vue3](https://github.com/desjjoh/QuickFE-Vue3)         | **QuickFE**  | **Mature / Active**   | Primary frontend reference and companion application for QuickAPI-NestJS.                                                                  |
| [QuickAPI-Express](https://github.com/desjjoh/QuickAPI-Express) | **QuickAPI** | **Stable**            | Deliberately small Express/TypeScript API demonstrating architecture, persistence, migrations, observability, testing, CI, and deployment. |
| [QuickAPI-FastAPI](https://github.com/desjjoh/QuickAPI-FastAPI) | **QuickAPI** | **Polishing**         | Async Python/FastAPI reference API applying the same engineering principles through Python and FastAPI conventions.                        |
| [QuickFE-React](https://github.com/desjjoh/QuickFE-React)       | **QuickFE**  | **In Progress**       | React/TypeScript frontend reference focused on reusable application structure and frontend engineering practices.                          |
| [QuickAPI-Spring](https://github.com/desjjoh/QuickAPI-Spring)   | **QuickAPI** | **Early Development** | Java/Spring Boot implementation of the QuickAPI engineering standard.                                                                      |

## What's Next

The current focus is completing the existing **QuickReference** web application set rather than adding additional frameworks:

1. finish the remaining persistence and deployment work in **QuickAPI-FastAPI**;
2. bring **QuickFE-React** and **QuickAPI-Spring** up to the same engineering standard as the mature reference implementations;
3. continue developing **QuickAPI-NestJS + QuickFE-Vue3** as the deepest paired example in the family.

After that, **QuickGame** will expand QuickReference beyond conventional web applications.

The first planned QuickGame project will use **Godot** to explore how the same engineering philosophy applies to real-time software, including:

* game and session state ownership;
* input abstraction;
* simulation and frame-time behavior;
* entity and scene lifecycles;
* persistence;
* diagnostics and debugging;
* automated testing;
* CI;
* reproducible game exports.

The game itself will remain deliberately small so the emphasis stays on software design and engineering practice rather than content volume.

## Engineering Focus

I am particularly interested in how robust engineering principles change across software domains: turning ambiguous requirements into systems with clear ownership, predictable behavior, maintainable boundaries, appropriate validation and testing, and enough operational or diagnostic visibility to understand the software after it leaves the development environment.
