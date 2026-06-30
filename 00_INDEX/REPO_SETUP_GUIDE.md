# Repo Setup Guide

This `Mullers` repo is the **documentation/index hub only** — no project code lives here. Each distinct business/project below gets its own GitHub repository.

> Note: my GitHub access in this session is scoped only to `911duplessis/mullers`, so I cannot create these repos for you. Run the commands below yourself (GitHub CLI, or use the GitHub web UI "New repository" with matching name/visibility/description).

## Repos to create

```bash
# P1 — EM Muller Services (PRIMARY COMPANY) — police clearance website code
gh repo create 911duplessis/EM-Muller-Services --public \
  --description "E.M. Muller Services – SA Police Clearance & Fingerprinting (Christchurch NZ)"

# P2 — Fundraiser for Mila & Lienka (due today — build this first)
gh repo create 911duplessis/Fundraiser-Mila-Lienka --public \
  --description "Fundraiser – Mila & Lienka – $3000 target"

# P3 — ProKids / Proteus (Elanza's children's program)
gh repo create 911duplessis/ProKids --public \
  --description "ProKids / Proteus – Inner Readiness Programme for Children, Canterbury NZ"

# P5 — AME Bishop's projects (Nigeria Bible School platform + Zambia Uber system)
gh repo create 911duplessis/AME-Projects --private \
  --description "AME 14th Episcopal District – Bible School platform + Zambia Uber system"

# P6 — PrimeTurf Digital (Leon + Mechanne's business)
gh repo create 911duplessis/PrimeTurf-Digital --private \
  --description "PrimeTurf – Digital transformation, SEO, ads (Leon & Mechanne's business)"
```

## Already exists — keep as-is
```
911duplessis/Kira-Lee   ← Kira-Lee's hockey tour fundraiser, live at
                            https://911duplessis.github.io/Kira-Lee/
                            Use this as the working template/pattern for
                            Fundraiser-Mila-Lienka (same fundraiser category).
```

## Stays in this hub repo (no separate repo)
```
04_GRATITUDE_CONTENT/   ← Personal recovery/confession videos + AME church
                            photos/videos. Storytelling/personal-brand content,
                            not a standalone product or business — kept as
                            documentation + asset references here.
05_PENDING_CLASSIFICATION/ ← Trading account, InsightForge/Tedani, Connection
                            Network. Not enough evidence yet to justify a
                            dedicated repo each — revisit once more chat/data
                            clarifies scope.
```

## Suggested order of operations
1. Create `Fundraiser-Mila-Lienka` first — it's the most overdue item (see `HOT_QUEUE.md` #1).
2. Create `EM-Muller-Services` next — primary company, site already exists at sapspoliceclearance.com but its code/source should be tracked properly.
3. Create `ProKids`, `AME-Projects`, `PrimeTurf-Digital` as those projects become actionable.
4. Once each repo exists, update the "Repo (separate code repo)" column in `00_INDEX/MASTER_PROJECT_MAP.md` from "(to be created)" to the live link.
