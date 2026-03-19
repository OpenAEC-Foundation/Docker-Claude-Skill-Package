# Docker Claude Skill Package

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Docker](https://img.shields.io/badge/Docker-Engine%2024%2B-2496ED?logo=docker&logoColor=white)](https://docs.docker.com)
[![Compose](https://img.shields.io/badge/Docker%20Compose-v2-2496ED?logo=docker&logoColor=white)](https://docs.docker.com/compose/)
[![OpenAEC](https://img.shields.io/badge/OpenAEC-Foundation-blue)](https://github.com/OpenAEC-Foundation)

**A comprehensive Docker and Docker Compose skill package for Claude** — covering Dockerfile best practices, multi-stage builds, Compose orchestration, container security, networking, storage, and debugging patterns.

Built for Docker Engine 24+ and Docker Compose v2.

---

## What Is This?

This repository contains a curated collection of **Claude skills** that give Claude deep, actionable knowledge about Docker and Docker Compose. Each skill provides deterministic, best-practice guidance that Claude can use when helping you with containerization tasks.

### Who Is This For?

- **Developers** who want Claude to write production-grade Dockerfiles and Compose files
- **DevOps engineers** who want Claude to understand container orchestration patterns
- **Teams** adopting Docker who want consistent, security-aware container configurations
- **Open-source LLM users** who need structured Docker knowledge for less capable models

---

## Package Contents

| Category | Skills | Coverage |
|----------|--------|----------|
| `docker-syntax` | TBD | Dockerfile instructions, Compose directives, CLI commands |
| `docker-impl` | TBD | Multi-stage builds, CI/CD integration, registry workflows |
| `docker-errors` | TBD | Build failures, runtime debugging, networking issues |
| `docker-core` | TBD | Security hardening, networking, storage, architecture |
| `docker-agents` | TBD | Dockerfile generation, Compose validation, security audits |

**Current Progress:** Phase 1 — Infrastructure & Planning (50%)

---

## Installation

Add the skills to your Claude workspace:

```bash
# Clone the repository
git clone https://github.com/OpenAEC-Foundation/Docker-Claude-Skill-Package.git

# Add to your Claude project's skill path
# Reference skills from skills/source/docker-*/
```

---

## Technology Coverage

| Technology | Version | Coverage |
|------------|---------|----------|
| Docker Engine | 24+ | CLI, API, runtime configuration |
| Docker Compose | v2 | Service definitions, networking, volumes, secrets |
| BuildKit | Default builder | Cache mounts, secret mounts, heredocs |
| Dockerfile | Current spec | All instructions, multi-stage, security |

---

## Project Documentation

| Document | Purpose |
|----------|---------|
| [CLAUDE.md](CLAUDE.md) | Protocols and instructions for Claude sessions |
| [ROADMAP.md](ROADMAP.md) | Project status and progress tracking |
| [REQUIREMENTS.md](REQUIREMENTS.md) | Quality guarantees and per-area requirements |
| [DECISIONS.md](DECISIONS.md) | Architectural decisions with rationale |
| [SOURCES.md](SOURCES.md) | Approved documentation sources |
| [WAY_OF_WORK.md](WAY_OF_WORK.md) | 7-phase methodology and skill standards |
| [LESSONS.md](LESSONS.md) | Lessons learned during development |
| [CHANGELOG.md](CHANGELOG.md) | Version history |

---

## Methodology

This package follows the **7-phase research-first development methodology** proven across multiple OpenAEC Foundation skill packages:

1. **Infrastructure & Planning** — Repository setup, core files, protocols
2. **Research (Vooronderzoek)** — Broad technology research and gap analysis
3. **Masterplan & Skill Design** — Skill inventory, dependencies, batch planning
4. **Topic Research** — Deep per-skill research with source verification
5. **Skill Development** — Batch creation with quality gates
6. **Validation & Quality** — Full quality audit against requirements
7. **Publication** — GitHub release with documentation and branding

---

## Related Skill Packages

| Package | Technology |
|---------|-----------|
| [ERPNext Skill Package](https://github.com/OpenAEC-Foundation/ERPNext_Anthropic_Claude_Development_Skill_Package) | ERPNext / Frappe Framework |
| [Blender-Bonsai Skill Package](https://github.com/OpenAEC-Foundation/Blender-Bonsai-ifcOpenshell-Sverchok-Claude-Skill-Package) | Blender, Bonsai, IFC |
| [Tauri 2 Skill Package](https://github.com/OpenAEC-Foundation/Tauri-2-Claude-Skill-Package) | Tauri 2.x (Rust + TypeScript) |

---

## License

MIT License — Copyright (c) 2026 [OpenAEC Foundation](https://github.com/OpenAEC-Foundation)

---

## Contributing

This skill package is developed using the meta-orchestrator pattern with Claude Code. Contributions are welcome via pull requests. Please ensure all skills meet the quality standards defined in [REQUIREMENTS.md](REQUIREMENTS.md).
