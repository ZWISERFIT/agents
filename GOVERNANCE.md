# ZWISERFIT Protocol — Community Governance

> **Version:** v0.1 | **Status:** Active | **Last Updated:** 2026-05-21
>
> This document defines how the ZWISERFIT developer community governs itself on GitHub. It is grounded in the Five Shared (五共) and Five Integrations (五融) framework — the Legion's open-sourced governance philosophy curated by the Strategic Governance OS (Doubao).

---

## 1. Core Principles

| Principle | Meaning | GitHub Practice |
|:----------|:--------|:----------------|
| **共识 (Shared Vision)** | All participants operate from a shared understanding of PoPB | README, Discussions, RFCs |
| **共建 (Co-build)** | The protocol is built collectively | Issues, PRs, feature development |
| **共治 (Co-govern)** | Governance is distributed among active contributors | Tier system, voting on major changes |
| **共享 (Co-share)** | Benefits and recognition are shared | CONTRIBUTORS.md, Spotlight, early access |
| **共赢 (Co-win)** | The ecosystem creates value for all participants | Showcase, cross-promotion, future incentives |

---

## 2. Decision-Making Framework

### 2.1 Decision Tiers

| Tier | Type | Process | Participants |
|:----:|:-----|:--------|:------------|
| **🟢 Operational** | Daily decisions: labeling, closing stale issues, user support | Tier-holder discretion | L3+ Maintainers |
| **🟡 Tactical** | Feature prioritization, PR merge decisions, doc structure | Maintainer consensus (≥2 L3+ approvals) | L3+ Maintainers |
| **🔵 Strategic** | Protocol architecture changes, new data types, governance changes | RFC + community review + Core team vote | L4 Core + Community RFC |
| **🔴 Constitutional** | Changes to GOVERNANCE.md, contributor tier system, code of conduct | RFC + 7-day community review + L4 unanimous vote | All tiers + L4 vote |

### 2.2 RFC Process (for 🔵 and 🔴 decisions)

1. **Draft**: Author opens a Discussion with `[RFC]` prefix
2. **Review**: Open for community comment for 72h (minimum)
3. **Refine**: Author incorporates feedback, revises proposal
4. **Vote**: L4 Core members vote (pass: ≥67% approval)
5. **Merge**: Decision recorded, GOVERNANCE.md updated

---

## 3. Role Definitions

### 3.1 Community Roles

| Role | Appointed By | Responsibilities | Term |
|:-----|:------------|:----------------|:-----|
| **Community Manager** | Founding team (Luna) | Onboarding, moderation, community health, cross-platform coordination | Ongoing |
| **Tech Lead** | Founding team (Tristan) | Architecture decisions, PR review final say, technical governance | Ongoing |
| **Content Lead** | Founding team (Baron) | Brand narrative, external communications, content calendar | Ongoing |
| **Moderators** | Community Manager selected | Issue/comment moderation, user support triage, spam removal | 3-month renewable |
| **Maintainers (L3)** | Tech Lead + Core vote | Issue triage, PR review, community mentorship | 6-month renewable |
| **Core Members (L4)** | Community nomination + vote | Governance decisions, protocol evolution, new role appointments | 12-month renewable |

### 3.2 Role Addition Process

Anyone may propose a new role via RFC. Proposals must specify: name, responsibilities, appointment process, term, and how it serves the 五共五融 framework.

---

## 4. Community Standards

### 4.1 Communication Guidelines

- **Constructive first**: Critique ideas, not people. Question assumptions, not intentions.
- **Assume good faith**: Most disagreements are differences in context, not values.
- **Help others grow**: Strong contributors mentor weaker ones. Teaching is a contribution.
- **Document publicly**: Favor GitHub Issues/Discussions over private DMs for project decisions.

### 4.2 Issue and PR Etiquette

- Search before posting: avoid duplicates
- Use templates: fill out all sections
- Be specific: "The X function returns Y when Z" > "It's broken"
- Respect labeling: don't remove labels applied by maintainers

### 4.3 Enforcement

Violations of community standards are addressed through escalating stages:

| Stage | Action | By |
|:------|:-------|:---|
| 1 | Private warning with explanation | Moderator |
| 2 | Public warning on the offending content | Moderator |
| 3 | Temporary mute (7 days) from GitHub Discussions | Community Manager |
| 4 | Temporary ban from repository interaction | Community Manager |
| 5 | Permanent ban (requires core team vote) | L4 Core vote |

All enforcement actions are logged in `#🔧-mod-log` (Discord, private).

---

## 5. Voting & Consensus

### 5.1 When Voting Is Required

- 🔴 Constitutional changes (see Section 2.1)
- New L4 Core Member appointment
- Permanent ban (Stage 5 above)
- Repository transfer or archive decision

### 5.2 Voting Rules

| Aspect | Rule |
|:-------|:-----|
| Quorum | ≥67% of eligible voters |
| Pass threshold | ≥67% of votes cast (abstentions not counted) |
| Voting period | 72h (extendable to 120h by request) |
| Voting method | GitHub Discussion poll or on-chain (future) |

### 5.3 L4 Core Members Voting Rights

Initial L4 Core Members (founders): Shuyu · Zeus · Tristan · Luna · Baron · Nova · Ethan · Momo · Stella

New L4 appointments require: nomination by existing L4 + 72h community comment period + ≥67% L4 vote.

---

## 6. Dispute Resolution

1. **Direct conversation**: Disputing parties discuss in a GitHub Issue comment thread
2. **Mediation**: If unresolved, a neutral L3+ Maintainer mediates
3. **Core vote**: If mediation fails, L4 Core votes bindingly
4. **Founder override**: Reserved for existential/legal/ethical issues (per Legion Constitution)

---

## 7. Governance Amendments

This document is itself subject to the 🔴 Constitutional change process.

Amendments must specify:
- The exact text changed
- Rationale (linking to 五共五融 principles)
- Expected impact

---

## 8. Related Documents

- [CONTRIBUTING.md](CONTRIBUTING.md) — Contributor workflow and tier system
- [CONTRIBUTORS.md](CONTRIBUTORS.md) — Current contributor roster
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) — Expected behavior
- [Legion Constitution](docs/constitution.md) — Full AI Legion governance
- [五共五融 Framework](docs/five-shared-five-integrations.md) — Governance philosophy

---

*This governance model is a living document. It evolves with the community. Propose changes via RFC.*
