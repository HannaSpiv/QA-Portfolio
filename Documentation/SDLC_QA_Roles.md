# 🧩 QA Role in SDLC (Software Development Life Cycle)

This document describes the QA responsibilities and artifacts across different SDLC models: **Waterfall, V-Model, and Agile (Scrum)**.

---

## 🔹 1. SDLC Overview

| Phase | Description | QA Focus |
|-------|--------------|-----------|
| Requirements | Define system goals and user needs | Review requirements for clarity, consistency, and testability |
| Design | System and component architecture | Identify risks, plan test strategy, prepare test data requirements |
| Implementation | Code development | Support unit testing, review pull requests, create test cases |
| Testing | Verify system meets requirements | Execute functional, regression, and non-functional tests |
| Deployment | Release to production | Perform smoke/sanity testing, validate environment |
| Maintenance | Support and bug fixes | Regression testing after fixes, impact analysis |

---

## 🔹 2. QA in Waterfall Model

**Key idea:** sequential flow — each phase starts after the previous one is completed.  
**QA Involvement:** mostly after development.

| Phase | QA Responsibilities | Artifacts |
|-------|----------------------|------------|
| Requirements | Review for testability and completeness | Comments, clarified requirements |
| Design | Prepare high-level test plan | Test plan draft |
| Implementation | Support developers, start writing test cases | Test cases, checklists |
| Testing | Execute system and regression tests | Test reports, bug reports |
| Maintenance | Verify bug fixes, regression | Regression suite, reports |

---

## 🔹 3. QA in V-Model

**Key idea:** each dev phase corresponds to a specific test level (tracing from requirements to tests).  

| Development Phase | Corresponding Test Level | QA Responsibilities | Artifacts |
|--------------------|--------------------------|----------------------|------------|
| Requirements | Acceptance Testing | Define acceptance criteria, support UAT | UAT checklist, sign-off notes |
| System Design | System Testing | Define end-to-end and non-functional tests | System test plan, test report |
| Detailed Design | Integration Testing | Test data flow and module interfaces | Integration test cases, API logs |
| Coding | Unit Testing | Support and review unit tests | Unit test checklist, code review notes |

---

## 🔹 4. QA in Agile (Scrum)

**Key idea:** QA is part of the development team — testing within each sprint.

| Sprint Stage | QA Responsibilities | Artifacts |
|---------------|----------------------|------------|
| Backlog Grooming | Clarify acceptance criteria, identify risks | Notes, updated user stories |
| Sprint Planning | Define test scope, plan environments, test data | Test tasks on board, data checklist |
| Development | Create test cases, test API/UI, pair testing | Test cases, Postman collections |
| Build / CI | Run smoke tests, monitor build status | Build verification report |
| Testing | Execute all types of tests, report bugs | Bug reports, screenshots, logs |
| Review / Retro | Demo critical flows, analyze quality metrics | Feedback log, improvement actions |

---

## 🔹 5. Summary

| Model | QA Involvement | Advantage | Risk |
|--------|----------------|------------|------|
| Waterfall | After dev phase | Clear structure | Late bug discovery |
| V-Model | Parallel to dev phase | Traceability between requirements and tests | Requires strong planning |
| Agile | Continuous (each sprint) | Fast feedback, flexibility | Requires high communication & automation |

---

📌 *Created by Hanna Spivachuk as part of ISTQB FL Week 1 Practice (SDLC & QA Roles).*
