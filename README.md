# Test Data Engineering Toolkit

> **Status: Incubating supporting project — not part of the six flagship repositories.**

A planned Quality Engineering toolkit for creating, protecting, validating, and operating test data across UI, API, integration, performance, and AI-quality workflows.

## Why this project exists

Enterprise test automation often fails because test data is treated as static fixture files rather than an engineered capability. A mature approach needs reproducibility, referential integrity, privacy controls, environment portability, deterministic generation, cleanup, and evidence that the data itself is valid.

## Planned engineering scope

- Schema-aware synthetic data generation
- Deterministic factories and seeded reproducibility
- Boundary, negative, combinatorial, and risk-based data generation
- PII-safe masking and synthetic replacement patterns
- Referential-integrity validation across related entities
- API-driven setup and cleanup workflows
- Database seeding and teardown patterns
- Dataset versioning and provenance
- Parallel-safe test isolation
- Performance-test data preparation
- AI/RAG evaluation dataset preparation
- CI/CD validation and reusable quality gates

## Intended role signal

This repository will support the broader portfolio by demonstrating **test-data architecture**, not by adding another generic faker library. The target is a small number of production-style workflows with measurable evidence, clear security/privacy boundaries, and reusable interfaces.

## Portfolio context

For current architect-level evidence, start with the main profile and flagship portfolio:

- [GitHub profile](https://github.com/ashokmanohar-ai)
- [Portfolio Evidence Index](https://github.com/ashokmanohar-ai/ashokmanohar-ai/blob/main/PORTFOLIO_EVIDENCE.md)
- [Playwright Enterprise Test Framework](https://github.com/ashokmanohar-ai/playwright-enterprise-test-framework)
- [Enterprise AI Quality Engineering Platform](https://github.com/ashokmanohar-ai/enterprise-ai-quality-engineering-platform)

This repository will move out of **Incubating** status only when it has reproducible implementation evidence, automated validation, documented limitations, and a recruiter-ready proof path.
