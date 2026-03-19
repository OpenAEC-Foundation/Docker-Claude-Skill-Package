# Docker Claude Skill Package — Sources

> Approved documentation sources, verification rules, and last-verified dates.

---

## Verification Rules
1. ONLY use sources listed below (or add new ones here first)
2. Use WebFetch to verify documentation is current during research
3. Cross-reference between primary docs and source code when in doubt
4. Update "Last Verified" date after each verification session

---

## Approved Sources

### Primary Documentation
| Source | URL | Domain | Last Verified |
|--------|-----|--------|---------------|
| Docker Documentation | https://docs.docker.com | All Docker topics | Not yet verified |
| Dockerfile Reference | https://docs.docker.com/reference/dockerfile/ | Dockerfile instructions | Not yet verified |
| Compose Specification | https://docs.docker.com/compose/compose-file/ | Compose file format | Not yet verified |
| Docker CLI Reference | https://docs.docker.com/reference/cli/docker/ | CLI commands | Not yet verified |
| Docker Compose CLI | https://docs.docker.com/reference/cli/docker/compose/ | Compose commands | Not yet verified |
| BuildKit Documentation | https://docs.docker.com/build/buildkit/ | BuildKit features | Not yet verified |

### Source Code Repositories
| Source | URL | Domain | Last Verified |
|--------|-----|--------|---------------|
| Docker Engine (Moby) | https://github.com/moby/moby | Engine source | Not yet verified |
| Docker Compose | https://github.com/docker/compose | Compose source | Not yet verified |
| BuildKit | https://github.com/moby/buildkit | BuildKit source | Not yet verified |
| Docker CLI | https://github.com/docker/cli | CLI source | Not yet verified |

### Best Practices & Security
| Source | URL | Domain | Last Verified |
|--------|-----|--------|---------------|
| Dockerfile Best Practices | https://docs.docker.com/build/building/best-practices/ | Build optimization | Not yet verified |
| Docker Security | https://docs.docker.com/engine/security/ | Security hardening | Not yet verified |
| Docker Scout | https://docs.docker.com/scout/ | Image scanning | Not yet verified |

### Supplementary Sources
| Source | URL | Domain | Last Verified |
|--------|-----|--------|---------------|
| OCI Image Spec | https://github.com/opencontainers/image-spec | Image format standard | Not yet verified |
| OCI Runtime Spec | https://github.com/opencontainers/runtime-spec | Runtime standard | Not yet verified |
| Docker Hub | https://hub.docker.com | Official images | Not yet verified |

---

## Source Quality Tiers
1. **Tier 1 (Authoritative):** docs.docker.com — always preferred
2. **Tier 2 (Source):** github.com/moby, github.com/docker — for implementation details
3. **Tier 3 (Supplementary):** OCI specs, Docker Hub — for standards and image references
4. **Never use:** Unverified blog posts, outdated tutorials, Stack Overflow answers without verification
