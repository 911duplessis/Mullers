# GitHub Identity Consolidation — `iamstiaan` → `911duplessis`

Audit and migration recommendation, produced alongside the PROSTARS brand blueprint (see `03_PROKIDS/SUMMARY.md` and `911duplessis/ProStars/docs/`).

## Audit scope and a access limitation
This session's GitHub access is scoped to `911duplessis/mullers` and `911duplessis/prostars`. Adding a repo from a second GitHub identity (`iamstiaan`) mid-session was attempted and rejected by the platform ("cross-tier adds are not supported... session already has repos from owner(s) 911duplessis") — cross-account repo access needs a session started fresh with the `iamstiaan` repo as the initial source. This audit is therefore based on: (a) this hub's own prior research in `03_PROKIDS/ASSETS/README.md`, and (b) a live fetch of the deployed prototype site itself, which is public.

## What's in `iamstiaan/Proteus`
- Two HTML files: `proteus-kids-sports-brand-overview.html` and `proteus-logo-mascot-guide.html`, deployed live via GitHub Pages at iamstiaan.github.io/Proteus.
- Content (confirmed by fetching the live page): brand name "Proteus Kids Sports," tagline "Play. Learn. Grow. Together.," a lion mascot, six generic sport disciplines (football, basketball, tennis, swimming, athletics, cricket), a merch store, and a gamified app concept. Built quickly in May 2026 (per `03_PROKIDS/TIMELINE.md`) to give the early strategy conversation a visual home — not a finished brand decision.
- No other content was found referencing the `iamstiaan` identity anywhere in the WhatsApp chat archive or this hub's research; `Proteus` appears to be the only project on that account relevant to the Muller/du Plessis businesses.

## Recommendation: do not migrate this content forward as-is
The new PROSTARS brand (`911duplessis/ProStars/docs/BRAND_IDENTITY.md`) deliberately supersedes the Proteus prototype rather than extending it — same reasoning as the Master Plan's "where this comes from" section: the lion mascot, six-sport menu, and merch-store framing are generic sports-franchise defaults, not the differentiated "Inner Readiness" positioning the founder's own strategy work (and lived Playball experience) points to. Copying that prototype's code into `911duplessis` would import the wrong starting point.

**Recommended action:**
1. Treat `911duplessis/ProStars` as the sole canonical repo for this business going forward — already done as of this update.
2. Leave `iamstiaan/Proteus` where it is, untouched, as a historical record of the May 2026 exploration — it costs nothing to keep and documents the brand's actual journey (Proteus → ProKids → PROSTARS), which is genuine, useful founder-story material (see `PROSTARS_MASTER_PLAN.md` §1).
3. If full account consolidation (not just this one project) is wanted later, the practical path is: open a session with `iamstiaan/Proteus` as the initial repo source, confirm there's nothing else of value on that identity, and either transfer repo ownership to `911duplessis` via GitHub's own "Transfer ownership" setting (Settings → Danger Zone, on the `iamstiaan` side) or simply leave it as an archived footnote — there's no functional code worth porting.

## Consolidated structure (current state, as of this update)
```
911duplessis/Mullers   — documentation/index hub for all in-flight projects (this repo)
911duplessis/ProStars  — canonical PROSTARS repo: brand blueprint (/docs), images, source chat archive
911duplessis/Kira-Lee  — live fundraiser site (unrelated project, already correctly placed)
iamstiaan/Proteus      — archived historical prototype, left in place, superseded by ProStars
```
No further repo creation or migration is needed for the PROSTARS project specifically — see `911duplessis/ProStars/README.md` for the canonical entry point.
