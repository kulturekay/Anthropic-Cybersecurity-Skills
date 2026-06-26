# Kanelo Labs — Initial ICP & First-Client Go-to-Market Research

**Prepared:** 26 June 2026
**Question:** Which Ideal Customer Profile is most likely to produce Kanelo Labs' first 1–5 paid clients (30–90 days) for the *AI Usage & Data Exposure Review* — not the biggest long-term market.
**Method:** Multi-agent web research (6 angles, 25 primary sources fetched, 121 claims extracted, 25 adversarially verified). Confidence labels used throughout:
- **[VERIFIED]** — survived 2–3 independent refutation votes during the research run.
- **[VERIFIED-DIRECT]** — re-checked by fetching the primary source and confirming the exact figure (verification pass, 26 Jun 2026).
- **[SOURCED]** — drawn from a named primary source but not independently re-verified.
- **[JUDGMENT]** — analytical inference from the evidence, not a single cited fact.

> **Verification note (26 Jun 2026):** the load-bearing stats below were re-checked against their primary sources. One figure was corrected (an unsupported "44% data leakage" claim was removed) and one was added back (UK Copilot deployment — see Red Flags). The Prodrive IT 15% figure, the ShareGate survey figures, the Microsoft/Censuswide shadow-AI figures, the PI-insurer questions, and the FRC/ICAEW dates are all now confirmed direct from source.

> **Headline:** The original hypothesis is *directionally right but mis-sized and under-targeted.* The evidence points to **narrowing by vertical (UK law firms first, accountancy/advisory second) and going SMALLER than 150–1,000 staff — to ~15–200 staff** — where the partner/owner is both the pain-feeler and the economic buyer, regulatory + PI-insurance + client-assurance triggers are live, and there is no internal security team to compete with or slow you down.

---

## 1. Executive Summary

**Best ICP (target first): UK law firms, ~15–150 fee-earners, Microsoft 365-heavy, no in-house security lead.**
The only ICP where the *exact* Kanelo offer is already being monetised by others, the pain is quantified, and three independent buying triggers stack (regulatory, professional-indemnity, client confidentiality). A UK MSP (Prodrive IT) publicly states that **"over 15% of your firm's confidential files are potentially at risk from oversharing, over-permissioning and erroneous access when using Copilot"** [VERIFIED-DIRECT]. Law firms carry acute confidentiality duties (SRA), face AI-hallucination scrutiny in court filings, and are now being asked about AI governance by their PI insurers at renewal [VERIFIED-DIRECT].

**Best secondary ICP: UK accountancy / advisory firms, ~15–150 staff.**
Same M365 + sensitive-client-data + regulatory profile (FRC *AI in Audit* guidance, 26 June 2025; ICAEW 2025 Code of Ethics technology provisions in force 1 July 2025, adding self-interest/self-review "threats associated with the use of technology") [VERIFIED-DIRECT]. Critically, **accountants are themselves the #1 referral hub for SMEs** — winning a few accountancy clients buys a referral engine, not just revenue.

**Best channel strategy:** Warm intros + partner referrals (legal/finance-specialist MSPs, DPO/compliance consultants, and accountants) feeding a **productised, fixed-price review** — *not* cold enterprise outreach and *not* a free consultation. Layer in vertical-specific LinkedIn content and one narrowly-targeted webinar ("Copilot without leaking client files — for law firms"). Speaking at a Law Society / regional law-society or accountancy-network event is the highest-trust accelerant if accessible.

**What to avoid (for the first 5 clients):**
- **Enterprise / 1,000+ staff** — that's where Darktrace and RiverSafe live (sales-led, "speak to sales", named refs like Vodafone/Swedbank) [VERIFIED]. A founder-led consultancy cannot win there yet.
- **Charities, healthcare/NHS, education, public sector** — high pain but low budget and/or long procurement; wrong for a 30–90-day close [JUDGMENT].
- **SaaS-adding-AI** — different pain (product security), wrong offer-fit [JUDGMENT].
- **The free-consultation-only model** (RiverSafe) [VERIFIED] — productise and charge a real (if modest) fee to qualify buyers and create urgency.

**Key evidence (most load-bearing):**
- Confidence-vs-reality gap: **29% of organisations report AI tools surfaced sensitive data that shouldn't have been accessible** (UK-specific: 26%) despite 93–97% stated confidence in governance — the gap *is* the sales pitch [VERIFIED-DIRECT].
- **71% of UK employees use unsanctioned AI tools at work; 51% use them weekly** (Microsoft-commissioned Censuswide survey of 2,003 UK staff, Oct 2025) [VERIFIED-DIRECT].
- **Live trigger is near-universal in the UK: 94% of UK organisations have deployed Copilot to some degree, 63% fully** (vs 56% globally) [VERIFIED-DIRECT].
- **Only 51% have run an org-wide governance review since enabling Copilot; 47% of UK firms say they're very likely to bring in an external partner — and ~8 in 10 globally** — to assess AI governance before scaling [VERIFIED-DIRECT].
- Competitor wedge already exists and is productised (Atech's *Copilot Readiness Assessment*, *M365 Security Assessment*, *Data Security Engagement*) [VERIFIED] — validating the offer *and* showing the gap (those are framed adoption-first, by an MSP, to their own M365 base).
- Pricing anchor for a micro-consultancy: **£500–£2,000 per assessment** is an established UK band [SOURCED].

> **Bottom line up front:** *For the next 30 days, target small/mid UK law firms (15–150 fee-earners) through warm intros and legal-IT/DPO partner referrals, with a fixed-price (£1,500–£4,000) "AI Usage & Data Exposure Review" framed around protecting client confidentiality before Copilot rollout.*

---

## 2. ICP Ranking Table

Scores 1–5 (5 = most favourable). "Competition" is scored as **headroom** (5 = least crowded for a founder-led entrant). Scores are **[JUDGMENT]** grounded in the cited evidence; they are decision aids, not measurements.

| # | ICP | Pain | Urgency/ trigger | Ability to pay | DM access | Trust path | Comp. headroom | Delivery conf. | Offer fit | Partner referral | Close 30–90d | Expansion | Long-term fit | **Total /60** |
|---|-----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 1 | **Law firms (15–150)** | 5 | 4 | 4 | 4 | 4 | 3 | 5 | 5 | 4 | 4 | 4 | 4 | **50** |
| 2 | **Accountancy/advisory (15–150)** | 4 | 4 | 4 | 4 | 4 | 3 | 5 | 5 | 5 | 4 | 4 | 4 | **50** |
| 3 | Insurance brokers / FS support | 4 | 3 | 4 | 3 | 3 | 3 | 4 | 4 | 3 | 3 | 4 | 4 | **42** |
| 4 | Professional-services consultancies (generic) | 4 | 3 | 4 | 3 | 3 | 3 | 4 | 4 | 3 | 3 | 4 | 4 | **42** |
| 5 | Recruitment agencies | 4 | 3 | 3 | 4 | 3 | 4 | 4 | 4 | 3 | 4 | 3 | 3 | **42** |
| 6 | Healthcare / healthtech | 5 | 3 | 3 | 2 | 2 | 3 | 3 | 4 | 2 | 2 | 4 | 4 | **37** |
| 7 | Education / training providers | 3 | 2 | 2 | 3 | 3 | 3 | 3 | 3 | 3 | 2 | 3 | 3 | **33** |
| 8 | Charities / nonprofits | 4 | 2 | 2 | 3 | 3 | 4 | 4 | 2 | 3 | 2 | 2 | 2 | **33** |
| 9 | SaaS adding AI features | 3 | 3 | 3 | 3 | 2 | 3 | 2 | 2 | 2 | 3 | 3 | 2 | **31** |
| — | AI consultancies / automation agencies | 2 | 2 | 3 | 3 | 3 | 3 | 2 | 2 | 2 | 4 | 3 | 3 | *Treat as CHANNEL, not ICP* |
| — | MSPs / M365 partners | — | — | — | — | — | — | — | — | — | — | — | — | *CHANNEL (see §4–5)* |
| — | DPO / data-protection consultancies | — | — | — | — | — | — | — | — | — | — | — | — | *CHANNEL (see §4–5)* |

**Rationale highlights:**
- **Law & accountancy tie at the top** for different reasons: law has the sharpest *pain + monetised-proof*; accountancy has the strongest *referral leverage*. Lead with law for the first 1–2 clients; pivot accountancy in as your referral flywheel.
- **Recruitment** is the most *reachable* (founder-owners, no procurement, high shadow-AI use putting candidate PII into ChatGPT) but **price-sensitive and assurance-light** — good for a fast cheap win, weaker for expansion.
- **Healthcare** has the highest raw pain but the worst access/cycle for a founder-led firm (procurement, DSPT, NHS frameworks) — a *later* market.
- **SaaS / AI-builders** score lowest on **offer fit** — their pain is product/model security, not staff M365 exposure. Wrong wedge.
- **MSPs, DPO firms, and AI agencies are mis-classified as ICPs in the brief** — the evidence says they are **channels** (they have the client relationships and the gap Kanelo fills). Reclassifying them is one of this report's main corrections.

---

## 3. Best ICP Deep Dive — UK Law Firms (and the near-identical Accountancy playbook)

**Exact company profile**
- **Size:** ~15–150 fee-earners / ~20–200 total staff. Below ~15 there's no budget; above ~200 you start hitting an IT director, procurement, and sometimes an internal security hire — which slows the close and erodes the "CISO-light" advantage.
- **Tech:** Microsoft 365 / SharePoint / Teams / OneDrive as the document spine; Copilot rolled out, in pilot, or under active pressure to adopt. Often a generalist (not legal-specialist) IT MSP, or a thin internal IT function.
- **Geography:** UK (England & Wales SRA-regulated firms first; Scotland/NI as adjacent).
- **Sectors within scope:** general practice, conveyancing, private client, employment, commercial, family — all confidentiality-heavy. Mirror profile for **accountancy/advisory**: audit, tax, outsourced finance, advisory.

**Buyer titles**
- **Economic buyer / signer:** Managing Partner, Senior/Equity Partner, Practice Director, COO, or Finance Partner. In a 15–150 firm these are reachable individuals, not a committee.
- **Pain-feeler first:** the Partner accountable for client confidentiality / the "innovation" partner running the Copilot pilot, plus the Risk/Compliance Partner or (often outsourced) DPO.
- **Blocker:** the incumbent IT/MSP (may feel territorial or say "we've got this"), and cost-conscious partners who see it as discretionary.

**Pain triggers (what makes them buy *now*)**
1. **Copilot/AI rollout decision** — "we're about to turn this on and don't know what it can see." (Oversharing is the #1 fear: AI doesn't create oversharing, it *exposes* it — [SOURCED, helloitsliam/ShareGate].)
2. **PI-insurance renewal** — insurers now ask professional-services firms detailed questions about AI usage, data handling and governance, including verbatim: *"Have you adapted existing privacy policies, security protocols and technical and organisational security measures to account for AI usage?"* and *"What governance and human oversight will be used?"*; with a law-firm-specific set on monitoring AI "hallucinations" and human review of AI output before submission to courts [VERIFIED-DIRECT, Browne Jacobson, 26 Feb 2026]. A blank answer is a commercial problem.
3. **Client security questionnaire / DDQ** — a corporate client asks "how do you govern staff AI use with our data?" and the firm has no answer.
4. **Regulatory pressure** — SRA confidentiality duties; AI-hallucination incidents in court filings; (accountancy: FRC June 2025 + ICAEW Code July 2025) [SOURCED].
5. **A near-miss / shadow-AI scare** — someone pasted a client document into ChatGPT.

**Words they use** (use these verbatim in messaging): *"client confidentiality," "are we exposed," "what can Copilot actually see," "we don't have a policy," "oversharing/over-permissioned," "people are using ChatGPT," "before we turn Copilot on," "what do we tell our insurer / our client."* They do **not** say "AI governance framework," "EU AI Act compliance," or "DLP posture" — that's enterprise/vendor language (RiverSafe's register) [VERIFIED] and it will not resonate.

**Budget source**
- **Risk/compliance or professional-indemnity budget**, or **partner discretionary spend**, or folded into the **Copilot/IT project budget**. It is *not* a line item — which is why a **fixed-price, named deliverable** (not a day-rate consulting engagement) is essential to get it approved fast.

**Likely objections & responses**
- *"Our IT/MSP handles security."* → "They keep the lights on; this is a one-off independent check of what AI and Copilot can actually reach across your client files — the thing your insurer and clients now ask about. I'll give your MSP the fix list."
- *"We're not even using Copilot yet."* → "That's the best time — the review tells you what to fix *before* you switch it on, so day one is safe."
- *"Is this just a sales funnel for a big retainer?"* → "No. Fixed price, fixed deliverable, you own the report. Most firms fix it themselves or with their MSP."
- *"Too expensive."* → anchor against a confidentiality breach / PI claim / lost client tender.

**Best message angle:** *Protect client confidentiality before you scale AI.* Risk/assurance-led, not productivity-led — which is precisely the **gap competitors leave open**: Atech and most MSPs frame Copilot as adoption/"AI transformation/supercharge your workforce" [VERIFIED]; RiverSafe frames it as enterprise EU-AI-Act compliance with no mention of M365/Copilot/SharePoint [VERIFIED]. Kanelo owns the practical middle: *"what is your staff's AI actually exposing, in your Microsoft 365, right now."*

**Best offer framing:** A productised, fixed-scope **"AI Usage & Data Exposure Review"** delivered in ~1–2 weeks: (1) what AI tools staff actually use (shadow AI), (2) what sensitive client data Copilot/M365 permissions expose (oversharing/over-permissioning scan), (3) policy/control gaps, (4) a prioritised fix list. One readable report + a 1-hour partner-level readout. **Price £1,500–£4,000** (anchored on the established £500–£2,000 micro-assessment band [SOURCED], priced up for the regulated-data context and partner-level audience).

**Best first outreach channel:** Warm intro → partner referral (legal-IT MSP / DPO / accountant) → narrow LinkedIn + one vertical webinar. (Detailed plan in §5.)

**Proof needed (credibility assets to build first):**
- A **sample/redacted report** and a one-page **methodology** (what you inspect, what you don't).
- A crisp **"what we found" anonymised example** (e.g., "in a 40-person firm we found X% of files reachable by Copilot that shouldn't be").
- Relevant **certifications/credentials** the founder holds; alignment to **NCSC/Cyber Essentials** language for instant SME trust.
- 1–2 **design-partner case studies** (offer the first review at a discount in exchange for a logo + quote).

**Delivery risks (be honest about these):**
- **Tenant access** — you need read access to M365/SharePoint permissions; scope this cleanly (read-only, time-boxed) or use a tooling partner. Competitors automate this (e.g., **Cloudiway** scans an M365 tenant in ~90 min and scores oversharing/permission sprawl [SOURCED]) — consider partnering for the scan so you sell the *interpretation + roadmap*, which is the defensible part.
- **Scope creep** into full remediation — hold the line: the review is the wedge; remediation is a separate engagement.
- **MSP relationship** — bring the incumbent MSP in as ally, not adversary, or they'll kill the deal.
- **"So what" risk** — a list of findings without a prioritised, plain-English fix path won't justify the fee. The roadmap is the product.

---

## 4. Competitor Acquisition Map

| Firm | Targets | Lead offer | Sells | Pricing | Primary route to market | Trust/proof | Tier |
|------|---------|-----------|-------|---------|------------------------|-------------|------|
| **Darktrace (Secure AI)** | Enterprise security teams | Continuous AI-monitoring **platform** (prompts, sessions, shadow AI, agent identities; covers Copilot/M365) | Platform / managed | None public; **"Speak to sales"** | Enterprise sales-led + partner channel | Brand, scale, named enterprise refs | **Enterprise** [VERIFIED] |
| **RiverSafe** | Large/regulated enterprise (Vodafone, Swedbank, Exabeam) | **Free 30-min consultation** → bespoke AI Governance & Secure Adoption | Consulting/services | None public | Consultative, enterprise references | Big-logo case studies | **Enterprise** [VERIFIED] |
| **Atech** | Their own UK M365/cloud customer base (mid-market) | **Copilot Readiness Assessment** + M365 Security Assessment + Data Security Engagement | Productised **assessments/workshops** → managed services | Not public (engagement-based) | MSP cross-sell, workshops/events, Microsoft co-funding | Microsoft accreditation | **Mid-market** [VERIFIED] |
| **CyberSmart** | UK **SMEs** | **Cyber Essentials** certification + monitoring | **Subscription product** | **Published — from £999+VAT/yr, self-serve "Buy Now"** | Product-led + **partner/MSP channel** | Transparent pricing, "UK's leading SME solution" | **SME** [VERIFIED] |
| **JC Cyber Security** | Very small UK firms, sole traders | **Free email/firewall/pen-test scans** → paid assessment → roadmap | Founder-led consultancy | Not public | Free-scan lead-gen wedge | Founder ("outsourced security dept") | **Micro/SME** [SOURCED] |
| **Cloudiway** | M365 admins pre-Copilot | **Automated AI-readiness scan** (~90 min, CAF score, oversharing/permission sprawl) | Tooling/platform | n/a | Product/SEO | Speed + objective score | **Tooling** [SOURCED] |
| **Prodrive IT** | **UK law firms** | Copilot security & confidentiality content/services ("15% of files at risk") | MSP services | Not public | **Vertical content/SEO** | Vertical specificity | **SME legal** [SOURCED] |
| **DPO Centre** | Orgs needing DPO/privacy | Copilot privacy/compliance advisory | DPO services / advisory | Not public | Content + retained DPO base | Privacy authority | **SME–mid** [SOURCED] |

**Patterns that matter for Kanelo:**
1. **Two camps, one gap.** Enterprise players (Darktrace, RiverSafe) sell *platforms/bespoke governance* to *big regulated* buyers with *no public price* and *no productised SME assessment*. SME players (CyberSmart, MSPs) sell *Cyber Essentials/adoption*, **not AI data-exposure risk**. **Nobody is cleanly selling a productised, risk-led AI-exposure review to small/mid professional-services firms.** That's Kanelo's lane.
2. **The assessment-as-wedge pattern is proven** (Atech's productised assessments; JC's free scans) [VERIFIED/SOURCED] — but it's framed *adoption-first* by *MSPs to their own base*. Kanelo can run the same play *risk-first* and *vertical-first*.
3. **Free vs. paid entry split:** RiverSafe and JC use **free** entry (consultation/scan); CyberSmart sells a **paid productised** subscription. For a founder-led firm needing *cash + qualified buyers fast*, the **paid-but-modest fixed-price** review beats free-consultation (which attracts tyre-kickers and signals "we'll upsell you").
4. **Vertical specificity wins SME trust** — Prodrive IT's law-firm-specific framing ("15% of files at risk") is far more compelling to a law firm than generic "AI governance."

---

## 5. Channel Recommendation — 30-Day First-Client Plan

**Channel scoring** (1–5; "Now?" = use in first 30 days):

| Channel | Speed | Trust | Cost (5=cheap) | Buyer access | Repeatable | Founder-fit | Competitor-used | **Now?** |
|---|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **Warm intros** | 5 | 5 | 5 | 4 | 2 | 5 | — (universal) | **YES** |
| **Partner referrals (MSP/DPO/accountant)** | 3 | 5 | 4 | 5 | 5 | 4 | CyberSmart, Atech, MSPs | **YES — build now** |
| **Vertical LinkedIn content** | 3 | 3 | 5 | 3 | 4 | 4 | many | **YES (support)** |
| **Webinar / workshop (1, niche)** | 3 | 4 | 4 | 4 | 3 | 3 | Atech | **YES (one)** |
| **Events / speaking (law/accountancy networks)** | 2 | 5 | 3 | 4 | 3 | 3 | Atech | If accessible |
| **Cyber Essentials / IASME / NCSC ecosystem** | 2 | 4 | 4 | 3 | 4 | 4 | CyberSmart | Later (assoc. now) |
| **Direct hot outreach (narrow, personalised)** | 3 | 2 | 4 | 3 | 4 | 3 | most | Selective |
| **Microsoft partner ecosystem** | 2 | 4 | 3 | 3 | 4 | 3 | Atech | Later |
| **Darktrace-style vendor partner route** | 1 | 4 | 3 | 2 | 3 | 2 | Darktrace | Later |
| **Chambers / local business networks** | 2 | 3 | 4 | 3 | 3 | 4 | — | Optional |
| **SEO** | 1 | 3 | 3 | 2 | 5 | 3 | Prodrive, Cloudiway | Later |
| **Marketplaces** | 1 | 3 | 3 | 2 | 4 | 2 | — | No |
| **Paid ads** | 2 | 2 | 2 | 2 | 4 | 2 | some | No |

**Why this ordering:** the strongest first-client evidence is unambiguous — *first clients come from trust, reputation and warm network, not cold outreach, and you must carve a narrow niche* (ventureinsecurity, a security operator's candid breakdown) [SOURCED]; and *"your best referral partners already exist — happy clients, fractional CFOs/COOs, accountants, vendors, local business groups"* (MSP growth playbooks) [SOURCED]. SEO/ads/marketplaces are repeatable but **slow** and wrong for a 30–90-day goal.

### The 30-day plan

**Week 1 — Productise & arm.**
- Finalise the fixed-scope **AI Usage & Data Exposure Review** (scope, deliverable, £1,500–£4,000 price, ~1–2 week turnaround).
- Build credibility assets: redacted **sample report**, one-page **methodology**, a **positioning one-pager** for law firms (swap "law" → "accountancy" variant).
- Decide the **tenant-scan approach** (manual read-only vs. tooling partner like Cloudiway) so delivery is real on day one.
- List **20 warm contacts** + **15 candidate partners** (legal-IT MSPs, outsourced DPOs, accountants).

**Week 2 — Activate warm network + recruit 2 design partners.**
- Personal asks to all 20 warm contacts (script in §6). Goal: **2 design-partner reviews** (discounted in exchange for logo + quote + referral).
- Open **partner conversations** with 5 legal-IT MSPs and 3 DPO consultants: "you don't sell this, I do; I hand the fix list back to you; rev-share or referral fee."
- Publish **2 LinkedIn posts** in the law-firm-confidentiality angle (use the verbatim pain words from §3).

**Week 3 — Deliver + create proof.**
- Run the first design-partner review end-to-end. Capture an anonymised **"what we found"** stat.
- Host **one 30-minute webinar/clinic**: *"Turning on Copilot without leaking client files — a 5-point check for law firms."* Invite warm list + partners' clients.
- Convert webinar attendees to **paid reviews** with a time-boxed offer.

**Week 4 — Convert + systematise referrals.**
- Close **1–2 paid reviews**. Ask every delivered client for **one intro** (to a peer firm and to their accountant).
- Formalise **1–2 partner referral agreements**.
- Line up an **accountancy-network or local-law-society speaking slot** for month 2.

**30-day success metric:** 1–2 paid reviews delivered or signed, 2 design-partner case studies, 2 active referral partners, a webinar pipeline. That is a realistic first-5-clients trajectory.

---

## 6. Messaging Kit

**A. Partner outreach (to a legal-IT MSP or outsourced DPO)**
> Subject: a piece you don't sell, that your clients now need
> Hi [Name] — you look after IT/data protection for several law firms. With Copilot rolling out, those firms are getting asked by *clients and PI insurers* how they govern staff AI use and what Copilot can actually see across their files. I run a fixed-price **AI Usage & Data Exposure Review** that answers exactly that — and I hand the prioritised fix list straight back to you to deliver. I don't compete with you; I create remediation work for you. Worth a 15-minute call on a simple referral arrangement?

**B. Direct prospect outreach (to a Managing/Risk Partner)**
> Subject: what can Copilot see across your client files?
> Hi [Name] — most firms turning on Copilot discover it can surface client documents that were quietly over-shared for years — and that's now a question on PI renewal forms and client security questionnaires. I run a fixed-price **AI Usage & Data Exposure Review** for firms your size: what AI tools your people actually use, what client data Copilot/M365 permissions expose, the policy gaps, and a prioritised fix list — one readable report, ~1–2 weeks. Would a 15-minute call to see if it's relevant be useful?

**C. Warm-intro ask (to your network)**
> Quick favour — I've launched Kanelo Labs, helping firms adopt AI without leaking sensitive data. My first clients are **small/mid law and accountancy firms** rolling out Microsoft Copilot. If anyone in your network is a **partner, COO, or practice manager** at a firm like that — or runs IT/DPO for them — a quick intro would mean a lot. Happy to send a one-line forwardable blurb.

**D. Call-opening script**
> "Thanks for the time. Quick context, then I'll listen. Most firms your size are under pressure to roll out Copilot, but it inherits whatever file permissions already exist — so it can surface client documents nobody meant to share. That's now showing up in PI renewals and client security questionnaires. Before I assume anything — where are you with AI and Copilot right now, and has client confidentiality or staff use of tools like ChatGPT come up internally?"

**E. Positioning statement**
> *"Kanelo Labs helps professional-services firms adopt AI without exposing client data. Our AI Usage & Data Exposure Review shows leadership exactly what AI tools their staff use, what sensitive data Microsoft 365 and Copilot can reach, and the highest-priority fixes — in one fixed-price, two-week engagement. We make AI adoption safe to switch on."*

---

## 7. Red Flags & Where the Hypothesis May Be Wrong

**Corrections to the original hypothesis ("CISO-light, M365-heavy UK firms, 150–1,000 staff"):**
1. **Size is probably too big.** At 150–1,000 staff you increasingly meet an IT director, procurement, and sometimes an internal security hire — slower close, weaker "CISO-light" advantage. The founder-led sweet spot for a 30–90-day close is **~15–200 staff**. *Test:* if your first discovery calls keep surfacing a dedicated security/IT-director gatekeeper, you're too high.
2. **"M365-heavy + sensitive data + AI pressure" is necessary but not sufficient** — it doesn't narrow enough to be sellable. **Vertical is the missing axis.** Law and accountancy convert the generic profile into a buyer with named triggers (SRA/FRC/ICAEW, PI insurance, client DDQs). Lead vertical-first.
3. **Buyer ≠ CISO; buyer = Partner/COO.** "CISO-light" is right, but the corollary is that you sell to a *business* owner of risk, in *business* language — not a security buyer. Security-jargon messaging (the RiverSafe register) will underperform [VERIFIED].

**Where the *recommended* ICP could be wrong — what would invalidate it:**
- **If law firms won't grant tenant access** to a new, unknown founder (confidentiality paranoia cuts both ways), delivery stalls. *Mitigation:* tooling-partner scan + read-only scoping; lead with a lighter "interview + policy-gap" version first.
- **If incumbent legal-IT MSPs already bundle this** for free, the wedge narrows. Evidence says they frame Copilot *adoption-first*, not *risk-first* [VERIFIED] — but verify per-target.
- **Buying-trigger figures are now confirmed** — the PI-insurer questions, the ShareGate survey figures (29%/47%/51%/~80%), the Microsoft/Censuswide shadow-AI figures (71%/51%), and the FRC/ICAEW dates were re-checked direct from source on 26 Jun 2026 [VERIFIED-DIRECT]. The direction *and* the specifics now hold.
- **Two stat corrections from verification (use the right numbers):**
  - **"93% have deployed Copilot" is wrong — do not use it.** That 93% is *confidence that M365 governance is ready for AI*, not deployment. The **correct** deployment figure is **94% of UK organisations have deployed Copilot to some degree, 63% fully** (ShareGate/Centiment, 850+ leaders). Use the corrected version.
  - **"44% of organisations report data leakage from shadow AI" could not be confirmed** in the cited source and has been **removed**. The supportable shadow-AI figures are 71% use / 51% weekly (Microsoft/Censuswide) and 29% of orgs reporting AI surfaced sensitive data (ShareGate). Don't quote the 44%.
- **If recruitment converts faster in practice** (most reachable, no procurement), it may beat law for the *very first* cash win even though it ranks lower on expansion. Worth a parallel test if law-firm access proves slow.

**General evidence caveats:**
- ICP **scores are analytical [JUDGMENT]**, not measured — directional, not precise.
- First-client GTM examples are **principles** (niche + warm network + paid productised wedge), not Kanelo-specific case studies.
- US/EU competitor coverage is lighter than UK; the UK picture is well-evidenced, the rest less so.

---

## 8. Source List (primary-source-weighted)

**Demand / pain evidence**
1. ShareGate — *93% confident in AI governance, but nearly 1 in 3 report data exposure* (29% surfaced sensitive data; sensitive-data categories). https://sharegate.com/blog/93-of-it-leaders-are-confident-in-their-ai-governance-but-nearly-1-in-3-report-data-exposure-incidents **[VERIFIED]**
2. SecurityBrief UK — *UK firms face AI data exposure despite Copilot confidence* (21 Apr 2026; ShareGate/Centiment, 850+ leaders: 29% data exposure, 94% UK Copilot deployment / 63% full, 51% governance review, 47% UK very likely to bring external partner, ~8 in 10 globally). https://securitybrief.co.uk/story/uk-firms-face-ai-data-exposure-despite-copilot-confidence **[VERIFIED-DIRECT]**
3. AICerts — *UK shadow AI surge: 71% use unapproved tools at work* (3 Nov 2025; Microsoft-commissioned Censuswide survey of 2,003 UK staff: 71% use, 51% weekly). https://www.aicerts.ai/news/uk-shadow-ai-surge-71-use-unapproved-tools-at-work/ **[VERIFIED-DIRECT]**
4. Prodrive IT — *How UK law firms can maintain security & client confidentiality using Copilot* (6 Nov 2025, Bruce Penson; "over 15% of your firm's confidential files are potentially at risk"). https://www.prodriveit.co.uk/blog/how-uk-law-firms-can-maintain-security-client-confidentiality-using-copilot **[VERIFIED-DIRECT]**
5. helloitsliam.com — *Fix oversharing in SharePoint and OneDrive before Copilot deployment* ("AI doesn't create oversharing, it exposes it"). https://helloitsliam.com/2025/12/10/fix-oversharing-in-sharepoint-and-onedrive-before-copilot-deployment/ **[SOURCED]**
6. CFOtech UK — *UK SMEs turn to AI before accountants* (accountancy disruption signal). https://cfotech.co.uk/story/uk-smes-turn-to-ai-before-accountants-survey-finds **[SOURCED]**

**Regulatory / buying-trigger evidence**
7. Browne Jacobson — *Questions PI insurers should be asking about clients' AI usage* (26 Feb 2026, Joanna Wallens; verbatim insurer questions on adapted privacy policies/security measures and human oversight; dedicated law-firm section on AI "hallucinations" and human review). https://www.brownejacobson.com/insights/the-word-february-2026/pi-insurers-questions-about-clients-ai-usage **[VERIFIED-DIRECT]**
8. FRC — *AI in Audit / Generative and Agentic AI Guidance* (illustrative example & documentation guidance published 26 June 2025). https://www.frc.org.uk/library/standards-codes-policy/audit-assurance-and-ethics/guidance/ai-in-audit/ • announcement: https://www.frc.org.uk/news-and-events/news/2025/06/frc-publishes-landmark-guidance-providing-clarity-to-audit-profession-on-the-uses-of-ai/ **[VERIFIED-DIRECT]**
9. ICAEW — *Code of Ethics: impact of technology* (2025 Code in force 1 July 2025; new tech-threat provisions, e.g. ss. 200.6/206.A2). https://www.icaew.com/technical/trust-and-ethics/ethics/code-of-ethics/impact-of-technology **[VERIFIED-DIRECT]**
10. ICO — *Guidance on AI and data protection* (accountability, DPIA, special-category data). https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/ **[SOURCED]**
11. DPO Centre — *Microsoft Copilot privacy & compliance tips*. https://www.dpocentre.com/blog/microsoft-copilot-privacy-compliance-tips/ **[SOURCED]**
12. TechSpire — *AI usage policy for UK SMEs 2026*. https://techspireit.co.uk/ai-usage-policy-for-uk-smes-2026/ **[SOURCED]**

**Competitor / acquisition evidence**
13. Atech — *Copilot Readiness Assessment* (3-phase). https://atech.cloud/workshops/atech-copilot-readiness-assessment/ **[VERIFIED]**
14. Atech — *Workshops/assessments menu*. https://atech.cloud/workshops/ **[VERIFIED]**
15. RiverSafe — *AI Governance & Secure AI Adoption* (enterprise refs; free consult; EU AI Act framing). https://riversafe.co.uk/cyber-security/ai-governance-and-ai-secure-adoption-services/ **[VERIFIED]**
16. Darktrace — *Secure AI* (platform; "speak to sales"; covers Copilot/M365). https://www.darktrace.com/products/secure-ai **[VERIFIED]**
17. CyberSmart — *Plans/pricing* (£999+VAT/yr; Cyber Essentials; SME; partner). https://cybersmart.co.uk/plans/ **[VERIFIED]**
18. JC Cyber Security — founder-led; free-scan wedge. https://www.jc-cybersecurity.co.uk/ **[SOURCED]**

**Channel / first-client / GTM evidence**
19. Venture in Security — *Starting a cybersecurity consulting practice* (niche + warm network lessons). https://ventureinsecurity.net/p/starting-a-cybersecurity-consulting **[SOURCED]**
20. MSP360 — *How to get managed service clients*. https://www.msp360.com/resources/blog/how-to-get-managed-service-clients/ **[SOURCED]**
21. Foxcrow Group — *MSP referral partner program* (referral partners already exist). https://www.foxcrowgroup.com/insights/msp-referral-partner-program/ **[SOURCED]**
22. IASME — *Cyber Essentials* (sole NCSC delivery partner; 400+ certification bodies; Cyber Advisor scheme). https://iasme.co.uk/cyber-essentials/ **[SOURCED]**
23. Microsoft Learn — *Solutions Partner for Security designation* (Microsoft partner ecosystem). https://learn.microsoft.com/en-us/partner-center/membership/solutions-partner-security **[SOURCED]**
24. Compare the Cloud — *How a 5-person UK MSP can build a Cyber Essentials practice and charge £500–£2,000 per assessment* (pricing anchor). **[SOURCED]**

**Segmentation / context**
25. Prospeo — *SMB vs mid-market*. https://prospeo.io/s/smb-vs-mid-market **[SOURCED]**
26. ZoomInfo Pipeline — *SMB vs mid-market vs enterprise*. https://pipeline.zoominfo.com/sales/difference-between-smb-midmarket-enterprise-account-executives **[SOURCED]**
27. Danish Lead Co — *Outbound for cybersecurity firms selling into mid-market*. https://danishleadco.io/blog/outbound-for-cybersecurity-firms-selling-into-mid-market **[SOURCED]**
28. The Smarketers — *Buying-committee / ABM*. https://thesmarketers.com/blogs/buying-committee-marketing-abm/ **[SOURCED]**

*Additional competitor surfaced in research, not separately fetched:* Cloudiway (automated M365 AI-readiness scan, ~90 min) — corroborates the tooling-partner option for delivery.

---

### Final directive

> **For the next 30 days, target small/mid UK law firms (15–150 fee-earners, Microsoft 365-heavy, no internal security lead) through warm intros and legal-IT-MSP / DPO partner referrals, with a fixed-price (£1,500–£4,000) "AI Usage & Data Exposure Review" positioned as: protect client confidentiality before you scale Copilot. Run accountancy/advisory as the fast-follow secondary ICP and referral flywheel.**
