# Docker Claude Skill Package — Architectural Decisions

> Numbered decisions with rationale. Immutable once recorded.

---

## D-001: 7-Phase Development Methodology
**Date:** 2026-03-19
**Decision:** Follow the proven 7-phase research-first development methodology.
**Rationale:** Successfully applied in ERPNext, Blender-Bonsai, and Tauri 2 skill packages. Ensures systematic coverage and quality.
**Phases:** Infrastructure → Research → Masterplan → Topic Research → Skill Development → Validation → Publication

## D-002: ROADMAP.md as Single Source of Truth
**Date:** 2026-03-19
**Decision:** ROADMAP.md is the single source of truth for project status, progress percentages, and next steps.
**Rationale:** Prevents status fragmentation across multiple files. Every session starts by reading ROADMAP.md.

## D-003: English-Only Content
**Date:** 2026-03-19
**Decision:** All skill content, code comments, and documentation within skills MUST be in English.
**Rationale:** Skills are published internationally via OpenAEC Foundation. English ensures maximum accessibility. Project management files (PROMPTS.md) may contain Dutch per user preference.

## D-004: MIT License
**Date:** 2026-03-19
**Decision:** Project is licensed under MIT License, copyright OpenAEC Foundation.
**Rationale:** Consistent with all OpenAEC Foundation skill packages. Maximum permissiveness for adoption.

## D-005: Docker Engine 24+ and Compose v2 Only
**Date:** 2026-03-19
**Decision:** Target Docker Engine 24+ and Docker Compose v2 exclusively. No legacy docker-compose v1 support.
**Rationale:** Engine 24+ is the current stable line with BuildKit as default. Compose v2 is the maintained version integrated into the Docker CLI. Legacy v1 is EOL.

## D-006: SKILL.md Under 500 Lines
**Date:** 2026-03-19
**Decision:** Every SKILL.md file MUST be under 500 lines. Heavy content goes in references/ subdirectory.
**Rationale:** Keeps skills scannable and fast to load. Proven effective in other skill packages.

## D-007: WebFetch for Source Verification
**Date:** 2026-03-19
**Decision:** Use WebFetch tool during research phases to verify documentation is current.
**Rationale:** Docker documentation updates frequently. WebFetch ensures we consult the latest version rather than relying on training data.
