# Kanelo Labs — AI Usage & Data Exposure Review
## Sample Report (redacted) + Methodology One-Pager

> Two assets in one file:
> **Part 1** — a redacted *sample deliverable* you can show prospects so they know exactly what they'll receive.
> **Part 2** — a one-page *methodology* (what we inspect, what we don't, how access works) to pre-empt the trust/security objection.
>
> Placeholders in `[BRACKETS]` are filled per engagement. The findings below are **illustrative**, modelled on the documented pattern that *"over 15% of a firm's confidential files are potentially at risk from oversharing, over-permissioning and erroneous access when using Copilot"* (Prodrive IT, 2025) and that *"every oversharing group and forgotten permission is one Copilot prompt away from becoming a real incident"* (ShareGate/Centiment, 2026). They are **not** real client data.

---

# PART 1 — SAMPLE REPORT

<div align="center">

## AI Usage & Data Exposure Review
### `[CLIENT NAME]` — Private & Confidential
**Prepared by Kanelo Labs · `[DATE]` · Reference `[REF]`**
*Scope: Microsoft 365 tenant + staff AI usage · Read-only assessment · `[DD–DD MONTH]`*

</div>

---

### 1. Executive summary (for the partners)

`[CLIENT NAME]` is rolling out / has enabled Microsoft 365 Copilot across `[N]` users. Copilot inherits each user's existing access — so it can surface anything those users could already reach, instantly and through plain-English prompts. This review answers three questions leadership asked:

1. **What AI tools are our people actually using?** (including unsanctioned "shadow AI")
2. **What sensitive client data can Copilot / M365 reach that it shouldn't?**
3. **What do we fix first — before this becomes a confidentiality, insurer, or client-assurance problem?**

**Overall exposure rating: `[AMBER]`** — *material, fixable risk; do not expand Copilot access further until Priority-1 items are closed.*

| What we found | Result |
|---|---|
| Staff AI tools in use (sanctioned + shadow) | `[12]` tools; `[4]` unsanctioned, incl. `[consumer ChatGPT, …]` |
| Files reachable by Copilot that appear over-shared | **`[~17%]` of scanned documents** |
| "Everyone"/"all staff"/anonymous-link exposures | `[N]` SharePoint sites, `[N]` shared links |
| Sensitive items in over-shared locations | `[client matters, payroll, board papers]` |
| Written AI acceptable-use policy in place | **`[No]`** |
| Copilot/data-governance owner named | **`[No]`** |

> **The one-line version for the managing partner:** *roughly one in six documents we sampled is reachable more widely than it should be, your staff are already pasting work into consumer AI tools, and there's no policy or named owner yet — all fixable in `[X]` weeks with the plan in §5.*

---

### 2. AI usage — what staff are actually doing

| Tool | Sanctioned? | Used for | Data risk |
|---|---|---|---|
| Microsoft 365 Copilot | Yes (`[pilot]`) | Drafting, summarising, email | Inherits all user permissions → see §3 |
| `[Consumer ChatGPT]` | **No (shadow AI)** | `[Drafting letters, summarising client docs]` | `[Client data leaving the tenant]` |
| `[Otter / Fireflies meeting AI]` | **No (shadow AI)** | `[Auto-joining client calls]` | `[Recording/transcribing privileged calls]` |
| `[Grammarly / other]` | `[Partly]` | `[Editing]` | `[Text sent to third-party servers]` |

**Context:** 71% of UK employees use AI tools at work without IT approval, 51% weekly (Microsoft/Censuswide, Oct 2025). `[CLIENT NAME]` is consistent with this pattern. The risk is not the tools — it's that `[client-confidential]` content is leaving the firm's controlled environment with no policy, logging, or training.

**Findings**
- `F-01` — `[N]` staff confirmed pasting `[client documents / case details]` into consumer ChatGPT. **No DPA, no data-residency control.**
- `F-02` — `[Meeting-transcription AI]` auto-joined `[N]` calls including `[client / privileged]` meetings.
- `F-03` — No acceptable-use guidance exists, so staff are self-deciding what is safe.

---

### 3. Data exposure — what Copilot / M365 can reach

We scanned `[N]` SharePoint sites, `[N]` Teams, and OneDrive sharing across `[N]` users (read-only — see Methodology).

| Exposure type | Count | Example (redacted) | Severity |
|---|---|---|---|
| Sites shared with "Everyone / Everyone except external" | `[N]` | `[/sites/HR — payroll & contracts]` | **P1** |
| "Anyone with the link" (anonymous) live links | `[N]` | `[Board pack Q2 — anonymous edit link]` | **P1** |
| Over-permissioned client/matter folders | `[N]` | `[Client X litigation visible to all fee-earners]` | **P2** |
| Dormant external guests with access | `[N]` | `[Ex-counterparty guest, last login 14mo]` | **P2** |
| Sensitive files with no sensitivity label | `[~%]` | `[Unlabelled client contracts]` | **P3** |

**Headline:** **`[~17%]` of sampled documents are reachable more broadly than their content warrants** — meaning a single Copilot prompt by `[any staff member]` could surface `[client-confidential, HR, or board]` material to someone who shouldn't see it. This mirrors the documented sector pattern (Prodrive IT: 15%+). The permissions were already there; Copilot just makes them trivially searchable.

---

### 4. Policy & control gaps

| Control | Status | Gap |
|---|---|---|
| AI acceptable-use policy | ❌ Missing | No written rules on what tools/data are allowed |
| Named AI/data-governance owner | ❌ Missing | No accountable person (insurer + ICO expect one) |
| Copilot access scoping / sensitivity labels | ⚠️ Partial | Labels exist but inconsistently applied |
| SharePoint sharing controls | ⚠️ Weak | Anonymous links and broad sharing permitted |
| Staff AI training / awareness | ❌ Missing | No guidance issued |
| Logging / oversight of AI use | ❌ Missing | Cannot answer "what did staff put into AI?" |
| Evidence for PI insurer / client DDQ | ❌ Missing | No documented governance to point to |

---

### 5. Prioritised fix list (what to do first)

| # | Action | Owner | Effort | Priority |
|---|---|---|---|---|
| 1 | Disable anonymous/"anyone" sharing links; remove "Everyone" access on `[N]` sensitive sites | IT/MSP | `[1–2 days]` | **P1 — before further Copilot use** |
| 2 | Issue a 1-page AI acceptable-use policy + name a governance owner | Partners | `[1 day]` | **P1** |
| 3 | Lock down `[client-matter / HR / board]` folders to least-privilege | IT/MSP | `[2–4 days]` | **P1** |
| 4 | Remove `[N]` dormant external guests | IT/MSP | `[½ day]` | **P2** |
| 5 | Apply/auto-apply sensitivity labels to client-confidential content | IT/MSP | `[ongoing]` | **P2** |
| 6 | 30-min staff briefing on approved vs banned AI tools | Kanelo/Partners | `[½ day]` | **P2** |
| 7 | Turn on AI/Copilot usage logging & quarterly permission review | IT/MSP | `[ongoing]` | **P3** |

> **What this buys you:** a defensible answer to your PI insurer and clients, Copilot you can safely expand, and the highest-risk exposures closed in `[X]` weeks. We hand items 1, 3–5, 7 to `[your MSP]` as a ready-to-action checklist.

---

### 6. What we did *not* do (scope honesty)
- We did **not** read the contents of your client files. We assessed *who can reach what*, not what's inside.
- We did **not** make any changes to your environment — this was read-only.
- We did **not** assess `[network security / endpoint / email security]` — out of scope for this review.

**Next step:** a `[60-minute]` partner readout to walk through this report and agree owners for the Priority-1 items. Remediation can be done by your own IT/MSP, or scoped separately with Kanelo.

*Kanelo Labs · `[contact]` · This document is confidential to `[CLIENT NAME]`.*

---
---

# PART 2 — METHODOLOGY ONE-PAGER

<div align="center">

## How the AI Usage & Data Exposure Review works
**Fixed scope · Fixed price · ~1–2 weeks · Read-only · One report + partner readout**

</div>

### What you get
A plain-English report for leadership covering **(1)** what AI tools staff actually use (including shadow AI), **(2)** what sensitive data Microsoft 365 / Copilot / SharePoint / Teams / OneDrive permissions expose, **(3)** the policy and control gaps, and **(4)** a prioritised, owner-assigned fix list — plus a 60-minute partner readout.

### The five steps
1. **Scope & access (Day 0–1).** We agree scope in writing and set up **read-only** access (or run a tenant scan via a tooling partner). Time-boxed, revocable, least-privilege.
2. **AI usage discovery (Day 1–3).** Short structured interviews + tenant signals to map sanctioned and unsanctioned ("shadow") AI tools and where firm/client data is going.
3. **Exposure scan (Day 2–5).** Read-only assessment of SharePoint/Teams/OneDrive sharing and permissions — broad sharing, anonymous links, over-permissioned client/HR/board content, dormant guests, missing sensitivity labels, and what Copilot can therefore reach.
4. **Gap & policy analysis (Day 4–7).** Benchmark against what your PI insurer, clients, and the ICO now expect: an AI acceptable-use policy, a named governance owner, oversight, and evidence.
5. **Report & readout (Day 7–10).** One readable report + prioritised fix list, delivered in a 60-minute partner session. Fix list is formatted to hand straight to your IT/MSP.

### How we handle *your* security (the objection, pre-answered)
- **Read-only.** We do not change settings or remediate during the review.
- **We assess access, not content.** We look at *who can reach what*, not what's inside your client files.
- **Least-privilege, time-boxed access**, revoked on completion. Scope and access are documented before we start.
- **Independent of your IT/MSP** — we give them the fix list; we don't replace them.
- **Mutual NDA** as standard. Founder credentials/certifications: `[list]`.

### What it costs & how long
- **Fixed price: `[£1,500–£4,000]`** depending on user count and number of SharePoint sites/Teams in scope.
- **Timeline: ~1–2 weeks** from access granted.
- **No lock-in.** You own the report. Remediation is yours, your MSP's, or a separate Kanelo engagement.

### Who it's for
Microsoft 365-heavy firms of ~15–200 staff — especially **law firms and accountancy/advisory firms** — that are rolling out or have enabled Copilot and need to know they're not exposing client data before they scale.

*Kanelo Labs — helping professional-services firms adopt AI without exposing client data.*
