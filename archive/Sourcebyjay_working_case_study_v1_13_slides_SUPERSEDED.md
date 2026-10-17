# Working Case Study Page MD V1

> **Reusable project workflow / operating skill** for the **fan pages** Project and the **Sourcebyjay — Reverse Engineering Case Study Script**.
>
> **Version:** 1.0 · **Created:** October 12, 2026 · **State:** Active workflow; individual case studies require editorial QC.
>
> **Primary activation phrase:** `Let's start case study script in this project — [Company Name]`
>
> **Short equivalents:** `Start case study — [Company Name]` / `Let's start case study script: [Company Name]`.

---

## 1. Mission

Publish useful, fact-checked business case studies, not generic company praise. Help readers understand **what happened, why a company made major decisions, how the business worked, what evidence supports the interpretation, where it went wrong, and how an ordinary person could reverse-engineer a reachable first milestone**.

Start from raw evidence, develop a story only after checking it, and enter design/production only after the script is approved. Apply this process independently to every named company (initial list: Reliance Industries, Dixon Technologies, Zepto, then the remaining lineup).

**No stage advances automatically.** The creator retains approval authority at each gate.

## 2. Trigger and stage state machine

| User says | Required action | Stop point |
|---|---|---|
| `Let's start case study script in this project — [Company]` | Open a fresh company case; perform **Stage 1** | Research package delivered for QC 1 |
| `QC 1 approved`, `Research approved`, or equivalent | Mark Stage 1 approved; invite the next script command or proceed to Stage 2 if the same message clearly requests it | Approved research state |
| `Use the script` / `Write the slides` **after QC 1** | Perform **Stage 2** from approved evidence | 13-slide script delivered for QC 2 |
| `Revise slide 6`, `Check these numbers`, etc. | Revise within the current stage; update version, claims and change log | Remain at current QC gate |
| `QC 2 approved; produce` / `Approve and produce` **after QC 2** | Perform **Stage 3** using approved copy | Production assets delivered for QC 3 |
| `QC 3 approved` | Mark production approved; prepare final publication package if requested | No publishing without user request |

If user asks for a later stage while prerequisites have not been approved, show what remains unapproved and request the needed approval—**do not silently skip ahead**. If the user clearly approves an earlier stage and requests the next one in a single instruction, do both sequentially. Research and writing decisions remain distinct from visual production.

**State labels:** `RESEARCH_ACTIVE` → `QC1_PENDING` → `RESEARCH_APPROVED` → `SCRIPT_ACTIVE` → `QC2_PENDING` → `SCRIPT_APPROVED` → `PRODUCTION_ACTIVE` → `QC3_PENDING` → `APPROVED_FOR_PUBLISHING`.

---

## 3. Stage 1 — Research / evidence collection only

### Sources to collect

1. **Primary:** Annual reports; stock-exchange disclosures; audited statements; earnings presentations/calls; official corporate history; product/pricing and company websites.
2. **Independent reporting:** Credible, dated news investigations and industry journalism; independent market/financial datasets with clear methods.
3. **Market reality:** Customer reviews, contemporary campaigns, ad archives, documented launches, competitor offers, price and distribution evidence.
4. **Public social evidence:** Company and founder LinkedIn/Instagram/YouTube posts; official interviews. These are claims and artifacts to cross-check, not automatic proof.
5. **Academic evidence:** Peer-reviewed research for relevant business principles—vertical integration, network effects, pricing, consumer behavior, etc. Academic theory is context, **not** proof the company used a particular formula.
6. **Regulatory / legal records:** Government records, competition/market authorities, court orders or judgments where materially relevant; keep attribution and procedural status clear.

For public social/page collection, respect site terms, access rules, copyright, privacy, and reasonable scraping limits. Prefer official feeds and lawful exports where available. Never present a scraped rumor as a verified company fact.

### Research the following 13 editorial questions

- Company's current product/customer/scale and a meaningful hook.
- Founding: who, when, what market and why.
- First real sales, profits, or first verifiable financial milestones; mark missing historical figures as **unknown**.
- Business model and capital: where funds came from and how invested (profit ≠ cash flow ≠ capital raised ≠ debt).
- **Secret Sauce:** evidence of observation, market data, global shifts, news/industry signals, relationships/contact networks, and the opportunity being spotted. Don't assign a fictional internal process to founders.
- Vertical/horizontal moves, operational advantage, sourcing and strategic positioning.
- How buyers/customers were reached: marketing, price, distribution, direct sales, partnerships.
- Turning points and alternatives, underlying decision logic.
- Measured results AND challenges: revenue, margins, losses, customers, capacity, risks, missteps.
- Present position and announced future plans, clearly separating existing results from aspirations.
- Reverse-engineering a first *reachable* milestone, not copying a whole conglomerate.
- Actionable three-block application: **(1) Execute and earn money (2) Increase your market (3) Build a network sustaining cash flow**.
- Context-appropriate follow-page CTA (kept editorial until production).

### Evidence register (one record per claim)

| Field | Description |
|---|---|
| `claim_id` | Stable identifier, e.g. `REL-001` |
| `company`, `topic`, `slide_candidate` | Company, subject and possible slide number |
| `claim_text` | Exact claim in plain English |
| `evidence_kind` | Audit, filing, interview, ad, product, quote, benchmark, academic, etc. |
| `source_title`, `source_url`, `publisher` | Retrievable source information |
| `published_date`, `period_covered`, `access_date` | Date scope; financial-year basis when relevant |
| `evidence_excerpt_or_location` | Page, section, or short paraphrase for checking |
| `verification_status` | `verified`, `company_claim`, `reported`, `interpretation`, `unverified`, or `conflicting` |
| `caveat` | Interpretation/measurement/comparability limits |
| `reusable_asset` | Image, chart, filing, campaign, quote, or other supporting artifact |
| `story_angle` | Why this claim might matter to an audience |

Never fabricate sources, figures, quotes, dates, founders' motives or specific amounts. Separate historical currency from inflation-adjusted numbers; distinguish gross revenue from turnover, net sales, EBITDA, PAT, cash flow, and valuation. State if one period covers more or fewer months. Label forecasts and plans as such. Prefer corroboration on important disputed claims.

### Stage 1 output / QC 1 package

- `Research brief.md`: company snapshot, timeline, business model, financial analysis, strategy, sales/distribution, significant decisions, controversies/mistakes, future plans.
- `Evidence register.csv`: all claims and citations as rows with verification flags and dates.
- `Story ideas.md`: **2–4 rough narratives/headlines**, with evidence pointers, no final slide copy.
- `Open questions.md`: missing proof, disagreements, next sources to inspect, unsupported ideas to discard.
- `QC1 checklist`: enough strong evidence for a responsible case study? What needs verification?

**Stop here. No finished carousel script, slide images, visual design, or publishing assets.**

**QC 1 pass criteria:** Source traceability, date accuracy, important financial distinctions, independent validation where possible, credible material for the Secret Sauce, and known gaps explicitly labeled. If information is unavailable, note that rather than hide it.

---

## 4. Stage 2 — Write the 13-slide evidence-driven script

**Prerequisite:** QC 1 approval of the company research. Use the approved data; do not introduce unsupported facts for the sake of a bigger hook.

### Repeatable 13-slide structure

| Slide | Reusable headline prompt | What the slide does | Example of proof |
|---|---|---|---|
| **01** | **[COMPANY] — How Did It Get Here?** | Main headline; truthful curiosity gap and reason to continue | Striking dated scale or turning-point fact |
| **02** | **What Is [COMPANY] Really Selling?** | Company snapshot, core products, customers and relevance | Revenue, segments, stores, customers or products |
| **03** | **Where Did It All Begin?** | Founder, founding context, opportunity and first offering | Official chronology, early records, founder source |
| **04** | **How Did It Make Its First Money?** | First customers, early sale, revenue, profit or validation | Historical financials, contracts, archival report |
| **05** | **What Did It Do With the Money?** | Business model, financing, reinvestment, capital choices | Financing breakdown, audited statements, filings |
| **06** | **The Secret Sauce — What Did It See That Others Missed?** | Observe → Collect data → Understand the world → Follow news → Make contacts; how those signals revealed demand/pain points | Verified market shift, relationships, decisions and documented evidence |
| **07** | **How Did It Build Its Advantage?** | Vertical/horizontal expansion, control of value chain and defensibility | Capacity, supply chain, costs, technology, reach |
| **08** | **How Did It Convince People to Buy?** | Early/current marketing, positioning, acquisition, price and distribution | Ads, campaign history, price changes, buyers, sales |
| **09** | **What Changed Everything?** | Turning point, major decision and why it mattered | Dated event and measurable before/after change |
| **10** | **Did It Actually Work? What Went Wrong?** | Results, limitations, mistakes, competitive/regulatory pressure and trade-offs | Financial trend, churn/losses, margins, independent evidence |
| **11** | **Where Is It Today, and What's Next?** | Current state and future bets; separate ambition from completed execution | Latest dated filings, strategy presentation, verified news |
| **12** | **Can You Reverse-Engineer Its Success?** | Pick first reachable destination; work backward into stages and blocks | Real first company milestone and historical order |
| **13** | **What Can You Build Starting Today?** | Three blocks: earn money → grow market → build network; small next action + follow CTA | Company-backed logic + clearly labeled illustrative exercise |

### Slide-writing template (each slide)

- **Headline:** Company-specific, curiosity-driven, truthful; company name is visually dominant on Slide 1.
- **Key claim:** The one point viewers should remember.
- **Evidence:** One or more specific source-backed real-world proof points, *not necessarily numeric*.
- **Meaning:** What the evidence tells us and what it does **not** prove.
- **Copy:** Brief, easy American English, sharp but not hype for hype's sake.
- **Design suggestion:** Chart, timeline, process, photo, campaign artifact, number card, etc., only at a conceptual level in Stage 2.
- **Source label:** Legible short source and date; full URL maintained in register.
- **Swipe bridge:** A natural next question or insight without repetitive teaser spam.
- **Confidence:** Verified vs supported interpretation vs provisional.

**Every slide has evidence.** Final instructional/CTA slides can use a real company event or a transparent illustrative calculation; don't invent a numerical claim merely to satisfy the rule.

### Signature editorial differentiators

**Secret Sauce:** Name a **documented business insight** or a carefully labeled analysis—not a mythical founder trick. Use the five information-gathering steps where they truly fit. Any claimed causation or psychology must be anchored in sources or clearly marked as a hypothesis.

**Reverse Engineering:** Do *not* tell readers to 'think big' or 'become Reliance'. Choose a sensible first milestone (e.g., first paying buyer, positive unit economics, stable revenue, repeat distribution); work backward to today; split into short execution phases.

**Actionable learning:** One workable exercise that puts the three blocks into motion: **Execute to earn → expand market → build relationships/repeat cash flow**. Avoid generic 'be consistent' or 'have a long-term vision' platitudes.

### Stage 2 output / QC 2 package

- Full **13-slide writing draft** (headlines, short copy, evidence IDs, source lines, visual directions, swipe bridges).
- Notes on where to shorten/combine slides if a company lacks meaningful data.
- Highlighted claims needing editorial check or better sources.
- Version number and change log.

**Stop here. Do not generate slide art until QC 2 is explicitly approved.**

**QC 2 pass criteria:** Story coherent; honest causality; all claims sourced; no false equivalence between finance concepts; useful Secret Sauce; genuine reverse engineering; practical CTA; tone approved by creator.

---

## 5. Stage 3 — Produce carousel and publication package

**Prerequisite:** Explicit QC 2 approval plus clear production instruction.

- Confirm target platform, brand template and output ratio (Instagram 4:5 suggested, e.g., 1080×1350 px).
- Design a coherent visual system with consistent headline hierarchy, data visuals, source labels, margins and legibility.
- Generate or source appropriate and licensed imagery. Do not present AI imagery as documentary evidence or invent photographic moments.
- Render 13 slides, maintain one source-of-truth script, and verify visible text/numbers against approval.
- Prepare alt text, caption, sources/credits, publication checklist and optional platform versions when requested.
- Complete **QC 3**: factual visual check, typo/layout review, sequence, source footnotes, rights check, CTA and final export.
- **Do not publish** or post on external platforms without explicit instruction and a connected tool that supports the action.

---

## 6. Revision, provenance, and file naming

Create one folder or logical group per company:

```text
case-studies/
  001-reliance-industries/
    research-brief_v1.md
    evidence-register_v1.csv
    story-ideas_v1.md
    open-questions_v1.md
    script-13-slides_v1.md       # only after QC 1
    production-notes_v1.md      # only after QC 2
    changelog.md
  002-dixon-technologies/
  003-zepto/
```

For each revision, record date, version, changed slides/claims, reason, new sources, removed assumptions, and current QC state. Don't overwrite history silently; do not label unsupported sources as verified. If later sources contradict already approved copy, reopen the relevant QC stage.

## 7. Example command sequence

```text
USER: Let's start case study script in this project — Reliance Industries.
ASSISTANT: Stage 1 only — collect and verify evidence, provide research data and rough ideas for QC 1.

USER: QC 1 approved. Use the script.
ASSISTANT: Stage 2 — write full 13-slide source-backed draft; stop for QC 2.

USER: Slide 6 needs better real-world evidence. Revise it.
ASSISTANT: Revise Stage 2 Slide 6 and its sources; remain at QC 2.

USER: QC 2 approved. Produce the carousel.
ASSISTANT: Stage 3 — develop visuals and publication package; stop for QC 3.

USER: QC 3 approved.
ASSISTANT: Mark approved for publishing. Don't auto-publish.
```

## 8. Sourcebyjay content style guide

- **Style:** Clear American English, confident and approachable, occasional relatable humor.
- **Perspective:** Show the decision and context, not a hero-worship biography.
- **Truth:** Evidence first; no fabrication, no mystery 'secrets' with no evidence.
- **Value:** The company story is the vehicle; actionable business thinking is the takeaway.
- **Pacing:** One major idea per slide; visual proof over text walls; CTA only when earned.
- **Flexibility:** 13 is the master research/script template; in production, combine slides if brevity improves the story *with creator approval*.

---

## 9. Master change log

| Date | Version | Change |
|---|---|---|
| 2026-10-12 | 1.0 | Created reusable three-stage, three-QC workflow; preserved evidence-first 13-slide formula, Secret Sauce, reverse-engineering lesson and three-block application. |

**Current master state:** Working reference active. Every named company starts from Stage 1 unless its approved dataset is already supplied and the creator explicitly advances it.