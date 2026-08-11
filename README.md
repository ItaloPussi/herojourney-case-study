# Herojourney — Engineering a Personal Operating System

A public engineering case study for **Herojourney**, a private personal operating system designed and engineered by [Italo Pussi](https://www.linkedin.com/in/italopussi/).

**Live case study:** https://italopussi.github.io/herojourney-case-study/

## What this repository is

This repository intentionally contains the **public case study only**, not Herojourney's private application source code.

The case study focuses on the engineering decisions behind the system:

- domain-driven modular monolith architecture;
- explicit module ownership and integration seams;
- preservation of historical meaning and temporal consistency;
- versioned, privacy-aware analytical exports;
- security-conscious external integrations;
- CI/CD, verified backups and rollback-oriented self-hosted operations;
- AI-assisted development constrained by architecture and quality guardrails.

## Product

Herojourney separates **intention, planning, commitment, evidence, outcome and historical memory** instead of flattening them into a generic task model.

The application includes modules for Planning, Daily Commitments, Goals, Review, Habits, Fitness, Nutrition, Weight, Library and Entertainment while keeping domain ownership explicit.

## Stack

**Frontend:** React, Vite, TypeScript, TanStack Query, Recharts, Tailwind  
**Backend:** Bun, Elysia, Prisma, SQLite, Better Auth  
**Quality:** Vitest, Biome, architecture checks, ADR lifecycle checks, domain glossary checks, schema-drift verification  
**Operations:** Docker, GitHub Actions, GHCR, Tailscale, Caddy, VPS

## Public case-study implementation

The portfolio page itself intentionally stays simple:

- semantic HTML;
- CSS;
- vanilla JavaScript;
- inline SVG architecture diagrams;
- optimized WebP screenshots;
- lightweight EN / PT-BR localization.

No frontend framework or runtime dependency is required to render this repository.

## Source availability

Herojourney's application source remains private. This repository documents selected architectural, security and delivery decisions without exposing private source code, user data or operational secrets.

---

Designed & engineered by **Italo Pussi**.
