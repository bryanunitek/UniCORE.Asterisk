# UniCORE.Asterisk

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 14:50 UTC.**

---

## What this repository is

`bryanunitek/UniCORE.Asterisk` is the **Asterisk** family member: On-prem-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source PBX, telephony, and IVR platform. Asterisk delivers voice routing, conferencing, SIP trunking, and IVR flows on UniCORE-deployed infrastructure.

**Role in UniCORE:** Telephony substrate — UniCORE.GVB substrate-services consume Asterisk to deliver enterprise voice communications on customer-premise and SaaS deployments.

---

## Upstream

- **Upstream project:** [https://github.com/asterisk/asterisk](https://github.com/asterisk/asterisk)
- **Upstream licence:** GPL-2.0 (with Asterisk Linking Exception)
- **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our code additions carry the same GPL-2.0 (copyleft requirement); our documentation additions sit under CC BY 4.0.

The merge discipline that governs how this repository absorbs upstream changes without losing UniCORE additions is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) at the root of this repository.

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

UniCORE.Asterisk is published as a **four-repo family**:

- `bryanunitek/UniCORE.Asterisk` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Asterisk` — public SaaS-deployment-shape gift surface
- `bryanunitek/UniCORE.Asterisk-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Asterisk-Claw` (private) — SaaS-shape working repository

**This repository is the `UniCORE.Asterisk` member of the family.**

Sister repos:

- [`UniSaaS.UniCORE.Asterisk`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Asterisk) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Asterisk))
- `UniCORE.Asterisk-Claw (private)`
- `UniSaaS.UniCORE.Asterisk-Claw (private)`

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04 14:50 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown and what is and is not in this initial scaffold.

---

## Files in this scaffold commit

- [`README.md`](README.md) — this file
- [`LICENSE.md`](LICENSE.md) — licence for UniCORE additions (GPL-2.0 for code; CC BY 4.0 for docs)
- [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim upstream licence (renamed from original `LICENSE`)
- [`README.upstream.md`](README.upstream.md) — verbatim upstream README (renamed from original `README.md`)
- [`STATUS.md`](STATUS.md) — explicit scaffold-anchor status with what's pending
- [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline
- [`AI-AUTHORSHIP.md`](AI-AUTHORSHIP.md) — AI authorship disclosure

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://git.unitek-systems.com/UniCORE/UniVERSE) (mirror: [GitHub](https://github.com/bryanunitek/UniVERSE)) — programme
- [`TrueAI`](https://git.unitek-systems.com/UniCORE/TrueAI) (mirror: [GitHub](https://github.com/bryanunitek/TrueAI)) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://git.unitek-systems.com/UniCORE/UniCORE-AI) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE-AI)) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://git.unitek-systems.com/UniCORE/UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE)) — on-prem-shape
- [`UniSaaS.UniCORE`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE)) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.GVB)) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB)) — SaaS-shape

**Forked-upstream building blocks:**
- UniCORE.Avalonia family (4 repos) — cross-platform UI
- UniCORE.DNN family (4 repos) — CMS platform
- UniCORE.Asterisk family (4 repos) — telephony ← **this family**
- UniCORE.Jitsi family (4 repos) — video conferencing
- UniCORE.Signal family (4 repos) — secure messaging
- UniCORE.XCP family (4 repos) — virtualisation

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE.Asterisk/discussions) (public repos only)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
