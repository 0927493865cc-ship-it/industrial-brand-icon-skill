# Industrial Icon Skill Quality Gates Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Upgrade the industrial icon skill with silent semantic and series quality gates, revision locking, abstract-feature handling, and regression tests based on recent real failures.

**Architecture:** Keep `SKILL.md` as a concise router and execution contract. Move conditional guidance into focused references, split legacy and new evaluation cases, and validate the repository structure plus every explicit design requirement before syncing.

**Tech Stack:** Markdown Agent Skill, Git, Python skill validator, shell-based structural assertions.

**Spec:** `docs/superpowers/specs/2026-09-16-icon-skill-quality-gates-design.md`

## Global Constraints

- GitHub `main` is the only implementation baseline.
- Default output remains white transparent PNG plus identical white-background black icons.
- Internal scoring stays hidden during normal generation.
- No production guidance is added before its failing evaluation case exists.
- Existing diagnostic-six acceptance assets and their scoped meaning remain unchanged.
- Current task does not authorize subagent delegation.

---

### Task 1: Establish RED evaluation coverage

**Files:**
- Create: `industrial-brand-icon-design/evals/recent-failure-cases.md`
- Create: `industrial-brand-icon-design/evals/regression-cases.md`
- Modify: `industrial-brand-icon-design/evals/cases.md`

**Interfaces:**
- Consumes: Existing Case 1–14 and the approved design spec.
- Produces: Case 15–24 plus a stable regression suite and evaluation router.

- [ ] Copy Case 1–14 unchanged into `regression-cases.md`.
- [ ] Add Case 15–24 to `recent-failure-cases.md` with explicit pass and fail criteria.
- [ ] Rewrite `cases.md` as the three-layer evaluation entrypoint.
- [ ] Run structural assertions proving the current Skill lacks the new routed guidance; record the expected failures.
- [ ] Commit the RED evaluation changes.

### Task 2: Add quality gates and conditional workflows

**Files:**
- Create: `industrial-brand-icon-design/references/quality-gates.md`
- Create: `industrial-brand-icon-design/references/abstract-semantics.md`
- Create: `industrial-brand-icon-design/references/revision-locking.md`

**Interfaces:**
- Consumes: Case 15–24.
- Produces: Authoritative scoring, retry, abstract-semantics, and revision-locking rules referenced by `SKILL.md`.

- [ ] Write the semantic/series/simplicity scoring contract and hard vetoes.
- [ ] Write the silent retry and actual-image reinspection flow with stopping conditions.
- [ ] Write the observable-behavior ladder for abstract features.
- [ ] Write hard-lock, visual-anchor, redesign states and seven-field fingerprints.
- [ ] Run assertions for thresholds, hard vetoes, retry limit, and lock states.
- [ ] Commit the focused reference files.

### Task 3: Refactor the entrypoint and existing guides

**Files:**
- Modify: `industrial-brand-icon-design/SKILL.md`
- Modify: `industrial-brand-icon-design/references/semantic-guide.md`
- Modify: `industrial-brand-icon-design/references/style-guide.md`
- Modify: `industrial-brand-icon-design/references/reference-learning.md`

**Interfaces:**
- Consumes: New focused references and evaluation routes.
- Produces: Minimal task-aware loading and non-duplicated authoritative rules.

- [ ] Replace the long entrypoint with a compact execution contract and routing table.
- [ ] Add semantic collision and observable-direction language to the semantic guide.
- [ ] Clarify optical consistency, small-size adaptation, and real-alpha verification in the style guide.
- [ ] Add The Noun Project learning boundaries and evidence-level handling to reference learning.
- [ ] Search for contradictory old rules and remove or qualify them.
- [ ] Run link and required-phrase assertions.
- [ ] Commit the refactor.

### Task 4: Validate behavior and repository integrity

**Files:**
- Verify: all changed Skill files
- Verify: `industrial-brand-icon-design/assets/acceptance/*`

**Interfaces:**
- Consumes: The complete upgraded skill.
- Produces: Fresh evidence for structural validity, regression coverage, and requirement coverage.

- [ ] Run the official `quick_validate.py` against the skill directory.
- [ ] Run all structural assertions with zero failures.
- [ ] Review Case 1–14 line by line against the new routing and references.
- [ ] Review Case 15–24 line by line against the new routing and references.
- [ ] Confirm acceptance assets are byte-identical to baseline.
- [ ] Inspect `git diff --check`, repository status, and the full diff.
- [ ] Commit any validation-only fixes.

### Task 5: Sync the completed branch

**Files:**
- No content changes expected.

**Interfaces:**
- Consumes: Verified commits on `upgrade/quality-gates`.
- Produces: A pushed GitHub branch containing the upgraded Skill.

- [ ] Re-run the full verification command immediately before push.
- [ ] Push `upgrade/quality-gates` to `origin`.
- [ ] Report the branch, commits, tests, and any limitations without claiming unrun visual generations.

