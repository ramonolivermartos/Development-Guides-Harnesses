# # Development Guides & Harnesses

**Practical guides, structured workflows, and AI-assisted development harnesses.**

---

## # Development Guides & Harnesses

![Documentation](https://img.shields.io/badge/Documentation-Development_Guides-111111)
![Format](https://img.shields.io/badge/Format-Interactive_HTML-737373)
![Focus](https://img.shields.io/badge/Focus-Software_Engineering-FACC15?labelColor=111111&color=FACC15)

**Practical guides, structured workflows, and AI-assisted development harnesses.**

---

## Introduction

A collection of interactive resources covering software project preparation, version control, and AI-assisted development.

These guides are designed to provide structured starting points, encourage sound engineering practices, and support the development of maintainable software projects.

All guides are independent resources stored in the [guides and harnesses](guides%20and%20harnesses/) folder. Choose the guide that fits your needs; no reading order is required.

## Table of Contents

- [Introduction](#introduction)

- [Available Guides](#available-guides)
  
  - [Project Foundations (Bones)](#project-foundations)
  
  - [Git and GitHub](#git-and-github)
  
  - [OpenCode — AI Development Harness](#ai-development-harness)
  
  - [Spec-Driven Development (SDD)](#spec-driven-development)
  
  - [Spring Boot — Request Journey and Security](#spring-boot-request-journey-and-security)

- [Adaptation and Configuration](#adaptation-and-configuration)

- [How to Use](#how-to-use)

- [Repository Structure](#repository-structure)

- [Disclaimer](#disclaimer)

---

## Available Guides

### Project Foundations

**Project Planning & Architecture**

**File:** [Bones.html](guides%20and%20harnesses/Bones.html)

An interactive guide covering the preparation of a software project, from the initial idea to Git initialization.

**Topics covered:**

- Brainstorming, requirements, and MVP definition.

- Domain modeling and software architecture.

- UML diagrams and database design.

- REST API contracts and OpenAPI.

- Project documentation and technical decisions.

- Initial environment and project setup.

**Scope:** From concept to `git init`.

---

### Git and GitHub

**Version Control & Collaboration**

**File:** [Git.html](guides%20and%20harnesses/Git.html)

A practical guide to Git and GitHub, covering repository initialization, development workflows, common operations, and troubleshooting.

**Topics covered:**

- Repository initialization and configuration.

- Branching strategies and commit management.

- Pull requests, code reviews, and merges.

- Everyday Git commands and operations.

- Conflict resolution and error recovery.

- Repository maintenance.

**Scope:** From the first commit to established Git workflows.

---

### AI Development Harness

**AI Agents & Development Automation**

**File:** [Opencode.html](guides%20and%20harnesses/Opencode.html)

An interactive implementation guide for configuring a specific multi-agent software development environment using OpenCode, Codex, Claude, and Gemini.

**Topics covered:**

- Agent architecture, roles, and responsibilities.

- Subagents and orchestration.

- Configuration files and permissions.

- AI-assisted implementation and code review.

- Automated development logs.

- Monitoring scripts and coordinated workflows.

- Validation and operational procedures.

**Scope:** A project-specific AI development harness, intended for adaptation rather than direct replication.

---

### Spec-Driven Development

**Specifications & AI-Assisted Development**

**File:** [Spec-Driven Development explained.html](guides%20and%20harnesses/Spec-Driven%20Development%20explained.html)

An interactive guide explaining Spec-Driven Development (SDD), where the specification defines the expected behavior and guides planning, tasks, implementation, and validation.

**Topics covered:**

- Specification-driven development compared with coding from a short prompt.

- The cycle of specifying, planning, breaking work into tasks, and implementing.

- Clear requirements, testable acceptance criteria, and explicit uncertainties.

- An interactive task API example linking requirements to criteria and implementation tasks.

- When to use SDD and tools that support the approach.

**Scope:** Understanding the SDD workflow and writing specifications that guide AI-assisted development.

---

### Spring Boot Request Journey and Security

**Request Flow & Application Security**

**File:** [Spring Boot - the journey of a request with security.html](guides%20and%20harnesses/Spring%20Boot%20-%20the%20journey%20of%20a%20request%20with%20security.html)

An interactive guide following a request through a Spring Boot application, showing how authentication, authorization, validation, and the application layers work together.

**Topics covered:**

- The request and response journey through the client, JWT filter, controller, service, mapper, repository, and database.

- Five scenarios: a valid request, a missing token, an insufficient role, an invalid request body, and access to another user's order.

- Authentication and authorization at the route, method, and data levels.

- DTOs and mappers for separating the API contract from persistence entities.

- Layer responsibilities, password and secret handling, and consistent error responses.

**Scope:** Understanding request flow and security boundaries through a simplified example using Spring Boot 3, Spring Security 6, and stateless JWT authentication.

---

## Adaptation and Configuration

**These guides are starting points, not universal procedures or rigid development standards.**

Every software project has its own architecture, technologies, constraints, and requirements.

When applying these guides:

- Some steps may be unnecessary.

- Additional steps may be required.

- Procedures may need to be modified or reordered.

- Configuration files and scripts must be adapted to the target environment.

- Agent roles, permissions, and automation mechanisms must be reviewed individually.

- Technical decisions must be validated against project-specific requirements.

**Understand the process. Evaluate its relevance. Adapt the implementation.**

The goal is to encourage informed engineering decisions, not mechanical execution of predefined instructions.

---

## How to Use

The guides are distributed as interactive HTML documents in the [guides and harnesses](guides%20and%20harnesses/) folder.

1. Select a guide from the [Available Guides](#available-guides) section.

2. Download the corresponding HTML file.

3. Open it in a modern web browser.

4. Follow the instructions and use the interactive checklists.

5. Adapt the procedures, examples, and configurations to your project.

Each guide can be consulted independently, in any order.

---

## Repository Structure

```
Development-Guides-Harnesses/
├── .gitattributes
├── .gitignore
├── README.md
├── guides and harnesses/
│   ├── Bones.html
│   ├── Git.html
│   ├── Opencode.html
│   ├── Spec-Driven Development explained.html
│   └── Spring Boot - the journey of a request with security.html
└── assets/
    ├── banner.svg
    └── divider.svg
```

---

## Disclaimer

These resources are provided for educational and reference purposes.

Tooling, dependencies, APIs, and security requirements may change over time. Examples and configurations are not guaranteed to be suitable for every project or environment.

Review and validate all technical instructions before applying them.

---

**Development Guides & Harnesses** · Learn · Understand · Adapt
