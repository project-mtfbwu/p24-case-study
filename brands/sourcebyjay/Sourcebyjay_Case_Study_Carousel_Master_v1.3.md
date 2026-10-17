# Sourcebyjay — Case Study Carousel Master V1.3

> **Reusable project workflow / operating skill** for the **fan pages** Project and the **Sourcebyjay — Reverse Engineering Case Study Script**.
>
> **Version:** 1.3 · **Updated:** October 12, 2026 · **State:** Active upgraded master for future case studies; retains all three creator QC gates.
>
> **Primary activation phrase:** `Let's start case study script in this project — [Company Name]`
>
> **Short equivalents:** `Start case study — [Company Name]` / `Let's start case study script: [Company Name]`.

---

## 1. Mission

Publish useful, fact-checked **decision-driven** business cases, not generic company praise. Help readers understand **what the company faced, which choice it made, which credible alternatives existed, why that choice might have been rational, what changed before vs. after, who its competitors were, what worked and failed, **who founded the business, what relevant experience they brought, and who financed or owns it**, how strong the evidence is, and how a reader can reverse-engineer a realistic first milestone**.

Start from raw evidence, develop a story only after checking it, and enter design/production only after the script is approved. Apply this process independently to every named company (initial list: Reliance Industries, Dixon Technologies, Zepto, then the remaining lineup).

**No stage advances automatically.** The creator retains approval authority at each gate. This update changes **how we research and tell the story**, not the QC protocol.

### Four methodological layers (our synthesis, not a claim of Harvard/McKinsey endorsement)

1. **Harvard-inspired teaching case:** identify one decision dilemma and alternatives **using only information plausibly available at the decision date**; let the reader think before outcome reveal.
2. **Consulting-inspired diagnosis:** define the problem, break it into drivers (customers, margins, supply, competition, finance), rank which levers matter, compare strategic options, and check results.
3. **Research-grade evidence:** cross-check material assertions; distinguish observed facts from hypotheses and causal claims; look for contrary evidence and rival explanations; document uncertainty.
4. **Sourcebyjay signature:** sharp story, easy language, first-money/sales reality, grounded Secret Sauce, and a *reachable* reverse-engineering action, not a fantasy billion-dollar blueprint.

**Editorial rule:** A Harvard teaching case, a consultancy client-success story, and a peer-reviewed academic case study serve different purposes. Borrow useful methods, but never label our independently researched public-source carousel as a Harvard case, McKinsey engagement, or peer-reviewed publication.

### Case-type selector — select ONE primary type before researching

| Case type | Central teaching question | Best emphasis |
|---|---|---|
| **Strategic decision** | Which option should management choose? | Dilemma, alternatives, pros/cons, outcome |
| **Growth / expansion** | How did the company unlock its next market? | Demand, distribution, capital, competitors |
| **Turnaround** | What changed and what actually improved? | Before/after, implementation, other drivers |
| **Failure / postmortem** | Why did the approach fail or break down? | Warning signs, incentives, trade-offs, counterevidence |
| **Business model / unit economics** | Where does the money really come from? | Acquisition, margin, cash flow, funding, durability |
| **Competitive advantage** | What is different—and hard to copy? | Peer benchmarks, positioning, defensibility, threats |

The same **14-slide master spine** works for all six; the founder-background slide may be combined with Origin only when evidence is thin and the creator approves a shorter version. Change *emphasis*, not the QC gates; don't force every company into a success story. Choose **one central decision question and one learning objective** for each case.


## 2. Trigger and stage state machine

| User says | Required action | Stop point |
|---|---|---|
| `Let's start case study script in this project — [Company]` | Open a fresh company case; perform **Stage 1** | Research package delivered for QC 1 |
| `QC 1 approved`, `Research approved`, or equivalent | Mark Stage 1 approved; invite the next script command or proceed to Stage 2 if the same message clearly requests it | Approved research state |
| `Use the script` / `Write the slides` **after QC 1** | Perform **Stage 2** from approved evidence | 14-slide master script delivered for QC 2 |
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
7. **Peer/competitor evidence:** Like-for-like comparable companies, alternate products and independent sector benchmarks; match geography, year, metric definition and business model.
8. **Counterevidence:** Serious criticism, failed initiatives, market-wide tailwinds, losses, changes in competitors, source disagreements; deliberately seek evidence that could weaken our favorite thesis.
9. **Investor and ownership records:** For public companies use dated stock-exchange shareholding patterns, annual reports, ownership disclosures and relevant IPO/offer documents; for startups use original funding announcements, regulatory filings and credible financing reporting. Prefer a disclosure over an unsupported funding database estimate.

For public social/page collection, respect site terms, access rules, copyright, privacy, and reasonable scraping limits. Prefer official feeds and lawful exports where available. Never present a scraped rumor as a verified company fact.

### Research the following 14 editorial questions (preserve original + decision checks)

- Company's current product/customer/scale and a meaningful hook.
- Founding: who started the company, when, what market gap existed and why the company began.
- **Founder(s) before the company:** each material founder's relevant education/training (if it matters), earlier jobs, ventures, practical skills, industry contacts, financial/resource constraints, complementary cofounder strengths, and documented prior failures/lessons. **Explain how experience connected to a later decision**, without treating credentials as proof of success. If unverifiable, mark unknown; do not speculate about private lives.
- First real sales, profits, or first verifiable financial milestones; mark missing historical figures as **unknown**.
- Business model and capital: where funds came from and how invested (profit ≠ cash flow ≠ capital raised ≠ debt). **Identify key investors, major shareholders and promoters when relevant.**
- **Secret Sauce:** evidence of observation, market data, global shifts, news/industry signals, relationships/contact networks, and the opportunity being spotted. Don't assign a fictional internal process to founders.
- Vertical/horizontal moves, operational advantage, sourcing and strategic positioning.
- How buyers/customers were reached: marketing, price, distribution, direct sales, partnerships.
- Turning points and alternatives, underlying decision logic.
- Measured results AND challenges: revenue, margins, losses, customers, capacity, risks, missteps.
- Present position and announced future plans, clearly separating existing results from aspirations.
- Reverse-engineering a first *reachable* milestone, not copying a whole conglomerate.
- Actionable three-block application: **(1) Execute and earn money (2) Increase your market (3) Build a network sustaining cash flow**.
- Context-appropriate follow-page CTA (kept editorial until production).

### Added V1.3 founder-background research — complete BEFORE slide writing

- Identify the founder(s) and their specific roles at founding; distinguish founding team, later executives, and public-facing figureheads. Handle companies with multiple founders and legacy-family ownership accurately.
- Map the **relevant pre-founding timeline**: domain knowledge, practical work, previous ventures, failures, access to capital or supplier networks, educational background *only if decision-relevant*, and cofounder skill complementarity.
- Ask **"What did the founder know or have access to that changed the starting strategy?"** For every proposed connection, attach a reliable contemporaneous source or label it an **interpretation**, not an established motivation.
- **Never imply success happened because someone attended a prestigious school**, or romanticize dropping out, humble origins, wealth or elite networks.
- Skip personal-life trivia, unsupported childhood narratives, and unverifiable net-worth claims. Note founder-background `sufficient` / `thin` / `disputed` and whether Slide 04 deserves a dedicated page.
- For publicly traded conglomerates or multi-generation businesses, distinguish **original founder**, **successor leader**, and **the decision-maker relevant to this case**. Do not attribute a successor's initiative to the original founder.

### Added V1.1 research questions — complete BEFORE slide writing

- **What is the case type, learning objective and one-sentence problem?** What exactly was management optimizing or trying to avoid?
- **Who made the decision and when?** State the decision date and which facts were knowable then. Do not import hindsight into the dilemma.
- **What were the realistic alternatives?** At least two if supported; for each, identify expected upside, downside, resource needs, and risks. Label reconstructed options as analyst interpretations rather than proven boardroom deliberations.
- **What evidence shows the company actually chose this route?** Verify strategic action; avoid invented founder motivations.
- **What changed BEFORE vs AFTER?** Use comparable periods and units (e.g., FY24 vs FY25 margin; customer base; capacity). Mark not comparable or unavailable instead of manufacturing a number.
- **What were competitors / other firms doing?** Identify 1–3 valid peers or a grounded alternative. Do not compare unlike metrics.
- **What is the strongest rival explanation?** Market growth, price inflation, acquisitions, regulations, subsidies, demand cycles, capital availability, competitor exits, or general industry tailwinds may explain part of the result.
- **Where did the plan lose?** Build a balanced assessment of pros, cons, mistakes, externalities, and unresolved risk.
- **What would falsify our explanation?** Write an observation that would make our Secret Sauce claim weaker or incorrect.
- **Which related academic findings help interpret the decision?** Distinguish peer-reviewed evidence for general mechanisms from evidence that *this company* followed them.

### Added V1.2 investor / ownership research questions — required assessment for every company

- **Who backed the company?** Name material VC/PE funds, strategic investors, family offices, founders/promoters, sovereign funds, or institutional holders *when verified and relevant*. Do not invent an investor where the company was bootstrapped or ownership is private.
- **When and how did they participate?** Year/round, verified funding amount and currency, primary share issue vs secondary stake sale, debt vs equity, strategic partnership vs actual ownership.
- **How much do they own—and as of when?** Include stake percentage or named holder ranking **only when a dated disclosure supports it**; say `not publicly disclosed` otherwise. A historic investor is not automatically a current shareholder.
- **Why is this investor important to the business case?** Documented capital, distribution access, technology/operations, governance influence, strategic alignment or dilution/control trade-off. Do not assign secret motivations to investors.
- **What changed after a notable investment?** Record true before/after metrics when available, while not confusing sequence with causation.
- **Does ownership create a risk or constraint today?** Concentration, founder control, dilution, investor exit, debt obligations, governance tension, or runway concerns—but only with evidence.
- **Public-company caution:** A mutual fund or institution buying existing listed shares is **not** necessarily funding the company. Keep **major shareholders** and **capital raised by the company** as distinct ideas.

### Required analytical mini-files inside the research brief

1. `decision-brief`: protagonist/decision owner (if known), decision date, specific dilemma, what was known then, and alternative A/B(/C) with trade-offs.
2. `competitor-benchmark`: comparable peers, geography, metric name/definition, matched time period, explicit limitations.
3. `before-after-register`: metric, pre-period, post-period, unit, direct source, any normalization, and caveat; no effect-size claims without credible attribution.
4. `rival-explanations`: primary interpretation, alternative explanations, evidence for/against each, current confidence.
5. `peer-review-notes`: reviewer, check date, strongest counterargument, corrections, resolved/unresolved items. **Editorial peer review ≠ academic peer-reviewed publication.**
6. `investor-ownership-map`: major named backers/holders, entity type, funding or purchase date, disclosed amount/stake (or `not disclosed`), primary vs secondary, current vs historical status, what they actually contributed and any evidenced ownership risk.

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
| `decision_date`, `known_at_decision` | Which historical decision and whether evidence was available then |
| `alternative_option`, `pros`, `cons` | Real or clearly labeled reconstructed alternative and trade-offs |
| `peer_company`, `peer_metric_comparability` | Competitor / sector comparison and its limitations |
| `before_period`, `after_period`, `metric_definition` | Comparable evidence for observed change, if available |
| `rival_explanation`, `counterevidence` | Plausible other causes and evidence contradicting preferred story |
| `causal_claim_status` | `observed_change`, `supported_mechanism`, `causal_inference`, `not_established` |
| `editorial_reviewer`, `review_status`, `review_note` | Independent second-pass review and remaining questions |
| `investor_name`, `investor_type`, `role` | Backer / promoter / major shareholder / lender / strategic partner; distinguish roles |
| `round_or_transaction_date`, `transaction_type`, `amount` | Dated primary issue, secondary sale, debt or disclosed strategic investment; currency and units |
| `stake_pct`, `stake_as_of`, `historic_or_current` | Verified ownership percentage/date and whether a holder remains invested |
| `investor_contribution`, `control_or_risk`, `investor_source` | Backer significance, documented governance/operating impact, source/caveats |

Additional founder-background evidence-register fields:

| Field | Description |
|---|---|
| `founder_name`, `founder_role`, `founder_period` | Who founded the company and what role/time period the claim concerns |
| `pre_founding_experience`, `source_and_date` | Verified earlier jobs, ventures, domain expertise, education (only if relevant), or material constraints |
| `cofounder_complementarity` | Documented division of founding-team skills/responsibilities |
| `advantage_claim`, `connection_confidence` | What experience *might* have enabled; mark documented, supported interpretation, or not established |
| `founder_privacy_and_relevance` | Evidence it belongs in this business case rather than personal trivia |

Never fabricate sources, figures, quotes, dates, founders' motives or specific amounts. Separate historical currency from inflation-adjusted numbers; distinguish gross revenue from turnover, net sales, EBITDA, PAT, cash flow, and valuation. State if one period covers more or fewer months. Label forecasts and plans as such. Prefer corroboration on important disputed claims.

### Stage 1 output / QC 1 package

- `Research brief.md`: company snapshot, timeline, business model, financial analysis, strategy, sales/distribution, significant decisions, controversies/mistakes, future plans.
- `Evidence register.csv`: all claims and citations as rows with verification flags and dates.
- `Story ideas.md`: **2–4 rough narratives/headlines**, with evidence pointers, no final slide copy.
- `Open questions.md`: missing proof, disagreements, next sources to inspect, unsupported ideas to discard.
- `QC1 checklist`: enough strong evidence for a responsible case study? What needs verification?
- `Decision and trade-off brief.md`: time-bound choice, alternatives, pros/cons, documented vs inferred options.
- `Benchmark and before-after.md`: matched comparisons; source/metric labels and caveats.
- `Rival explanations and peer-review.md`: strongest counterargument, source disagreement, reviewer sign-off or open objections.
- `Investor and ownership map.md`: key investors/promoters/major holders, funding and stake dates, capital type, significance, uncertainties; mark no meaningful outside investors or private information as appropriate.
- `Founder advantage brief.md`: founding-team identities and roles, verified pre-founding background, evidence for any business advantage, cofounder complementarity, and a recommendation to use or merge Slide 04.

**Stop here. No finished carousel script, slide images, visual design, or publishing assets.**

**QC 1 pass criteria:** Source traceability, date accuracy, important financial distinctions, independent validation where possible, credible material for the Secret Sauce, and known gaps explicitly labeled. **V1.1 requires** a bounded decision dilemma, a comparison/alternatives plan, an explicit evidence-strength label, a rival explanation, and a documented critical second pass. **V1.2 additionally requires an investor/ownership check** (including `bootstrapped`, `not material`, or `not publicly disclosed` where applicable), source/date validation for named backers, and a clean distinction between corporate capital raised and shareholders trading stock. If data are unavailable, the gap must remain visible—not fictionalized. If information is unavailable, note that rather than hide it. **V1.3 additionally requires a founder relevance check:** verifiable background facts, correct attribution for all cofounders or successor leaders, and an evidence-based link (or clearly labeled uncertainty) between experience and business choices.

---

## 4. Stage 2 — Write the 14-slide evidence-driven script

**Prerequisite:** QC 1 approval of the company research. Use the approved data; do not introduce unsupported facts for the sake of a bigger hook.

### Repeatable 14-slide structure — V1.3 (new Slide 04: founder background)

**Reader journey:** hook → understand the business → origin → founder background / relevant starting advantage → first money → model/investors → insight → edge vs peers → customer acquisition → decision dilemma → outcome/before–after → mixed verdict and ownership → reverse-engineer → act.

| Slide | Reusable curiosity headline | Must answer / show | Analysis / proof test |
|---|---|---|---|
| **01 — Hook** | **[COMPANY] — Would You Have Made This Bet?** | Company name dominates; one surprising *verifiable* fact + central business tension | Dated, sourced fact; no invented tension |
| **02 — Business today** | **What Does [COMPANY] Really Sell?** | Products, buyers, revenue engine, relevance and scale | Dated segments / customer or revenue evidence; avoid vanity metrics |
| **03 — Origin** | **Where Did the Opportunity Start?** | Founding event/date, the unmet market need, and what the founders set out to make or solve | Historical records; do not fabricate internal motivations |
| **04 — Founder background / edge** | **Who Were the People Behind the Bet?** | Founders' **relevant pre-founding experience, previous work/ventures, learned skills, complementary roles or resource constraints** and how that background may have informed the opportunity | Verify identities, roles, dates, and career/venture facts independently when possible; explain a documented link or label an interpretation; no resume dump, school prestige worship or life-story guesswork |
| **05 — First money** | **Who Paid First—and Why?** | First buyers, sales/contract, first repeatability or documented early milestone | What is known vs unknown; distinguish sales, earnings and cash |
| **06 — Money engine + key backers** | **Who Funded It—and Where Did the Money Go?** | Business model, major financing, **named key investors/promoters**, how the investment helped; label funding rounds and ownership carefully | Funding disclosures/shareholding filings; sales vs profit vs debt vs equity vs secondary shares |
| **07 — Secret Sauce** | **What Did It Notice Before Others?** | Grounded market signals and insights; preserve **Observe → Collect data → Understand the world → Follow news → Make contacts** only where evidence supports | Label inferred insight vs company's stated explanation |
| **08 — Competitive edge** | **What Did It Do Differently From Rivals?** | Operating advantage, vertical/horizontal expansion, fair peer comparison | Like-for-like peer benchmarks or explained qualitative alternative; advantage **and** weakness |
| **09 — Sales machine** | **How Did It Get Customers to Say Yes?** | Marketing, direct sales, price, trust, channels and customer acquisition | Historical campaigns, distribution, customer metrics when available |
| **10 — Decision dilemma** | **Then Came the Hard Choice. What Would You Do?** | Dated inflection point; 2–3 realistic options with a pro, con and constraint each; let readers decide before reveal | Clearly distinguish documented options from analyst-reconstructed alternatives; no hindsight |
| **11 — Reveal + before/after** | **What Did [COMPANY] Choose—and Did It Work?** | Verified action, matched-period before/after outcome, unexpected consequences, rival explanations | Same metrics and time periods; correlation does not equal causation |
| **12 — Reality check + ownership (when material)** | **What Won, What Failed, and Who Holds the Power Now?** | Current footprint, wins, failures, risks, next bets; optional *current* key owners/holders and governance implications | Dated latest records; distinguish historical from current investors, evidence from speculation |
| **13 — Reverse engineer** | **How Would You Rebuild Only the First Milestone?** | Work backward from a reachable first goal through skills, costs, customers, constraints, sequences and proof of demand | Don't pretend a beginner has the founder's original industry network or capital access |
| **14 — Action + CTA** | **What Can You Try This Week?** | **Execute and earn → Expand market → Build network/repeat cash flow**; one specific exercise and follow CTA | Lesson supported by documented decision; hypothetical exercise labeled |

**New founder-background rule:** Slide **04** is a dedicated slide in the **14-slide master** when the founding-team background explains the opportunity, key decision or advantage. Lead with what a founder *knew, built, learned or could access*, not their school or celebrity status. If credible founder-specific information is too thin or adds nothing, **combine 03 and 04 with creator approval** for a 13-slide publish version; never invent material to fill a page. Multiple founders should be handled fairly, or explicitly narrow attention to the decision-maker for the case.

**Investor placement: maximum two slides, no investor-only filler slide.** Slide **06** covers material historical funders, promoters, investment timing and what financing enabled. Slide **12** optionally shows *current* owners or governance implications if that affects the case. Keep investor sources and as-of dates clear.

**Template snippets (fill only with verified company-specific facts):**

- Slide 06: `Investor/backer — year or round — verified amount/stake if disclosed — strategic/business significance`.
- Slide 12, when relevant: `Major holders/promoters as of [reporting date] — ownership/control reality — opportunity or risk`.
- If bootstrapped: `Founder-funded / operating cash flow; no verified outside equity round` (only if truly supported).
- If private and undisclosed: `Key investors named, stake not publicly disclosed` or omit names if even those cannot be verified.

**Why Slides 10–12 change:** Slide 10 forces a decision *before* the reveal (Harvard-inspired); Slide 11 tests the narrative with outcome, before/after, and rival explanation (consulting + research); Slide 12 gives an honest mixed verdict and forward view. Slides 01–09 and 13–14 preserve the established Sourcebyjay identity.

**Investor minimum:** document investor/ownership status in Stage 1; visibly name key backers on Slide 06 only when verifiable and consequential. Avoid logos/names without dated evidence, founder-stake guesses and implying a financial holder personally endorsed the company. Where meaningful, add current control/risk to Slide 12; do not crowd the slide with the entire cap table.

**Minimum on-slide comparison rule:** every substantial case includes a competitor/alternative contrast (normally 08), a realistic pros/cons choice (10), and an outcome with baseline if available (11). If any element is unavailable, say so; do not force fabricated comparisons. **Keep one leading idea per slide**; detailed tables live in the supporting research package / caption if too dense for Instagram.

### Slide-writing template (each slide)

- **Headline:** Company-specific, curiosity-driven, truthful; company name is visually dominant on Slide 1.
- **Key claim:** The one point viewers should remember.
- **Evidence:** One or more specific source-backed real-world proof points, *not necessarily numeric*.
- **Meaning:** What the evidence tells us and what it does **not** prove.
- **Copy:** Brief, easy American English, sharp but not hype for hype's sake.
- **Design suggestion:** Chart, timeline, process, photo, campaign artifact, number card, etc., only at a conceptual level in Stage 2.
- **Source label:** Legible short source and date; full URL maintained in register.
- **Swipe bridge:** A natural next question or insight without repetitive teaser spam.
- **Confidence:** Verified / company-reported / independently reported / inference / unresolved; don't present a model as a source fact.
- **Case mechanics:** Where relevant, add `decision-date`, `option-and-trade-off`, `before/after definition`, `peer-compared`, `rival-explanation`, and `reason-to-believe` fields. For Slides 06/12 add `investor-type`, `amount-vs-stake`, `transaction-type`, `shareholding-as-of`, and `documented-impact`.
- **One takeaway:** What a reader should learn *about making a decision*, not just about this brand.

**Every slide has evidence.** Final instructional/CTA slides can use a real company event or a transparent illustrative calculation; don't invent a numerical claim merely to satisfy the rule.

### Business-school + consulting + peer-review techniques that must be visible

| Technique | Reader-visible home | Required internal evidence |
|---|---|---|
| Founding opportunity vs founder's prior edge | 03 and **04** | Founding date, roles and grounded pre-founding experience; distinguish fact from inferred advantage |
| Decision dilemma without hindsight | 01 (tease), 10 (full) | Decision date, then-known facts and realistic alternatives |
| Option-by-option pros and cons | 10; summarize 12 if useful | A/B(/C) matrix, resources, feasibility and downside |
| Competitive / peer contrast | 08; optionally 09/11 | Comparable definitions, markets and periods; disclose limitations |
| Before/after business result | 11 | Pre/post periods, same metrics/units, transparent source |
| Rival explanations / uncertainty | 11–12 | Strongest competing interpretation; avoid unjustified causal claims |
| Credible criticism and failure | 11–12 | Independent criticism, material downside, open questions |
| Concrete learning / practical action | 13–14 | Transferable mechanism, realistic first milestone and constraints |
| Key investors and meaningful financing | 06; optionally 12 | Dated backing, capital type vs shareholding, impact and present control |

### Signature editorial differentiators

**Secret Sauce:** Name a **documented business insight** or a carefully labeled analysis—not a mythical founder trick. Use the five information-gathering steps where they truly fit. Any claimed causation or psychology must be anchored in sources or clearly marked as a hypothesis.

**Reverse Engineering:** Do *not* tell readers to 'think big' or 'become Reliance'. Choose a sensible first milestone (e.g., first paying buyer, positive unit economics, stable revenue, repeat distribution); work backward to today; split into short execution phases.

**Actionable learning:** One workable exercise that puts the three blocks into motion: **Execute to earn → expand market → build relationships/repeat cash flow**. Avoid generic 'be consistent' or 'have a long-term vision' platitudes.

### Behind-the-scenes critical peer review — mandatory before QC 2

Independent **editorial** challenger reviews all 14 slides (may be a second human or an explicitly separate second-pass role; no claim of independent review if same author merely reread it). Challenge:

1. Does every important figure lead to a source and period? Is a firm's statement mislabeled as proof?
2. Did we confuse simultaneous events with a cause-and-effect relationship?
3. Did we use only information known at the decision point for Slide 10?
4. Would a credible competitor or skeptical operator agree that the comparison is fair?
5. Did we search for at least one serious counterargument / rival explanation?
6. Are the pros, cons, benefits, risks, mistakes, and trade-offs genuinely balanced?
7. Does the before/after chart use the same definitions, comparable periods, and right denominators?
8. Is the Secret Sauce tied to evidence, not made-up mind reading?
9. Is the reverse-engineered lesson practical under small-company constraints?
10. Can a beginner understand it without losing important qualifiers?
11. Did we verify **who the key investors/holders actually are**, with dated disclosures, and separate historical from current ownership?
12. Did we correctly distinguish **funding raised by the company** from an investor buying shares in the market? Are stakes/amounts/governance impacts sourced rather than guessed?
13. Is Slide 04 **actually relevant** to how the business began or gained an advantage? Have we verified founder/cofounder backgrounds and avoided irrelevant trivia, invented motives, credentials-as-causation and successor misattribution?

Record **PASS / REVISE / UNSUPPORTED** by claim/slide; keep author/editor name or role and review date. If no separate reviewer was involved, label the review `self-check only` and never `peer reviewed`. Relevant peer-reviewed research may inform a principle but does *not* certify our company's conclusion.

### Stage 2 output / QC 2 package

- Full **14-slide writing draft** (headlines, short copy, evidence IDs, source lines, visual directions, swipe bridges).
- Notes on where to shorten/combine slides if a company lacks meaningful data.
- Highlighted claims needing editorial check or better sources.
- Decision-options matrix; Slide 08 peer-comparison basis; Slide 11 pre/post metrics and limitations; alternative-cause note.
- Founder-background evidence map showing why Slide 04 matters, or an explicit recommendation to combine it with Slide 03.
- Investor/ownership map showing Slide 06 evidence and optional Slide 12 current ownership/risk, including investor role, as-of dates and unknowns.
- Second-pass **editorial reviewer report** with challenged claims and resolutions.
- Version number and change log.

**Stop here. Do not generate slide art until QC 2 is explicitly approved.**

**QC 2 pass criteria:** Story coherent; honest causality; all claims sourced; no false equivalence between finance concepts; useful Secret Sauce; genuine reverse engineering; practical CTA; tone approved by creator. **V1.1 gate additionally checks** a clear dilemma, alternatives/pros/cons, fair peer context, before/after comparability, counterevidence, reviewer notes, and visible uncertainty. **V1.2 adds key-backer accuracy and public/private ownership caveats**. **V1.3 additionally checks founder-background sources and whether its slide earns its space, with a creator-approved merge if not.** If information is not available, acknowledge gaps rather than blocking a strong narrative or inventing facts.

---

## 5. Stage 3 — Produce carousel and publication package

**Prerequisite:** Explicit QC 2 approval plus clear production instruction.

- Confirm target platform, brand template and output ratio (Instagram 4:5 suggested, e.g., 1080×1350 px).
- Design a coherent visual system with consistent headline hierarchy, data visuals, source labels, margins and legibility.
- Slide 04 visual recommendation: small verified founding-team portraits with roles, 2–3 **relevant** earlier experiences, a simple `experience → observed problem → founding advantage` arrow, and dated sources; show multiple founders when materially responsible.
- Recommended repeatable visual motifs: 06 compact `backer → capital → business effect` map with source/date, 08 comparison (compact peer card), 10 A/B decision fork with pros/cons, 11 before/after with clearly matched units/dates, 12 balanced wins/risks with a small ownership/control inset **only when material**. These are conditional layouts—not mandatory inflated charts.
- Generate or source appropriate and licensed imagery. Do not present AI imagery as documentary evidence or invent photographic moments.
- Render 14 slides, maintain one source-of-truth script, and verify visible text/numbers against approval.
- Prepare alt text, caption, sources/credits, publication checklist and optional platform versions when requested.
- Complete **QC 3**: factual visual check, typo/layout review, sequence, source footnotes, rights check, CTA and final export.
- V1.1 **visual truth check:** charts retain exact source denominators; no nonzero truncated axes without disclosure; dates/currencies explained; visual size does not imply an unsupported ratio; reader can distinguish verified vs illustrative graphics.
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
    decision-brief_v1.md
    competitor-before-after_v1.md
    investor-ownership-map_v1.md
    rival-explanations_v1.md
    reviewer-notes_v1.md
    open-questions_v1.md
    script-14-slides_v1.md       # only after QC 1
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
ASSISTANT: Stage 2 — write full 14-slide source-backed draft; stop for QC 2.

USER: Slide 6 needs better real-world evidence. Revise it.
ASSISTANT: Revise Stage 2 Slide 6 and its sources; remain at QC 2.

USER: QC 2 approved. Produce the carousel.
ASSISTANT: Stage 3 — develop visuals and publication package; stop for QC 3.

USER: QC 3 approved.
ASSISTANT: Mark approved for publishing. Don't auto-publish.
```

## 8. Sourcebyjay content style guide

- **Style:** Clear American English, confident and approachable, occasional relatable humor.
- **Perspective:** Show the decision, what was *known then*, the alternatives and context, not a hero-worship biography.
- **Truth:** Evidence first; no fabrication, no mystery 'secrets' with no evidence.
- **Value:** The company story is the vehicle; analytical business thinking, an honest mixed verdict, and one actionable experiment are the takeaway.
- **Pacing:** One major idea per slide; visual proof over text walls; CTA only when earned.
- **Flexibility:** 14 is the master research/script template; in production, combine slides if brevity improves the story *with creator approval*.

---

## 9. Reference methodology and source notes

These sources inform **our adapted editorial method**, not the details of any company case. For every individual company, separately source the facts in its own evidence register.

- **Harvard Business School — Case Method Teaching:** The teaching case builds to a decision moment using historical information available at the time; outcome is not initially revealed. https://www.hbs.edu/case-method-project/about/Pages/case-method-teaching.aspx
- **Harvard Business School — The Case Method:** Analysis, discussion, classroom debate and reflection around incomplete information. https://www.hbs.edu/mba/academic-experience/the-case-method
- **Harvard Business Publishing — What is a Teaching Note?** Instructional goals, case summaries, discussion questions and suggested analysis; restricted instructor resources are NOT to be reproduced. https://help.hbsp.harvard.edu/hc/en-us/articles/49668722375315-What-is-a-Teaching-Note-How-Do-I-access-and-use-it
- **McKinsey — How to master the seven-step problem-solving process (2019):** Problem definition, logic trees, priorities, analysis and clear actionable synthesis; describes a method, not proof any published client case used this exact sequence. https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/how-to-master-the-seven-step-problem-solving-process
- **Eisenhardt, K. M. (1989), Academy of Management Review, DOI: 10.5465/amr.1989.4308385:** Grounding case-based theory in evidence and method. https://journals.aom.org/doi/10.5465/amr.1989.4308385
- **Eisenhardt & Graebner (2007), Academy of Management Journal, DOI: 10.5465/amj.2007.24160888:** Multiple case logic and explicit research design. https://journals.aom.org/doi/10.5465/amj.2007.24160888
- **Peer-reviewed case research guidance (Runeson & Höst, 2009):** Source/observer/method/theory triangulation. https://link.springer.com/article/10.1007/s10664-008-9102-8

### Pros / cons of the V1.1 editorial upgrade

| Pros | Cons / guardrail |
|---|---|
| More original and useful than biography-only carousels | More research time; only add comparisons where good evidence exists |
| Readers must evaluate actual trade-offs | Too many choices can clutter a carousel; max 2–3 options in 09 |
| Before/after makes claims testable | Outcome does not establish cause; check rival explanations |
| Peer comparisons reduce hero worship | Cherry-picked or incomparable peers can mislead; disclose limitations |
| Second-pass editorial review catches overclaims | Editorial review is not blind academic peer review; be precise |
| Fixed structure makes scale across 25+ companies possible | Don't make every story sound identical; match case type and central tension |

### V1.2 → V1.3 — founder background and founder advantage

- **Master format:** 14 slides; added a standalone **Slide 04 — Founder background / edge**, immediately after origin.
- **What qualifies:** relevant previous jobs, practical expertise, prior ventures (including relevant mistakes), complementary cofounders, meaningful networks or constraints, and a grounded link to how this specific company began or made an early decision.
- **What does not qualify:** generic LinkedIn biography, prestige education as alleged explanation for success, invented hardship, unsupported family stories, net worth speculation, or attributing a later CEO's moves to the original founder.
- **Conditional shortening:** If nothing valuable can be independently verified, merge founder background into Slide 03 with creator approval. The master remains 14, but a particular published carousel may use 13 slides.
- **Shifted earlier topics forward by one:** first money 05, key investors 06, Secret Sauce 07, competitive edge 08, customer acquisition 09, dilemma 10, reveal 11, reality check 12, reverse engineering 13, CTA 14.
- **Quality gate:** a new `founder-advantage-brief` and editor challenge for relevance, cofounder fairness and verified attribution. Three QC gates stay unchanged.

### V1.1 → V1.2 — investor clarity without a bigger carousel

- **Kept:** Original 13-slide arc; rigorous Stage 1 → QC 1 → Stage 2 → QC 2 → Stage 3 → QC 3; balanced reality check.
- **Slide 05 (default):** *Who are the key investors / promoters?* Names, investment timing, disclosed amount/stake, funding instrument and impact on the business.
- **Slide 11 (conditional):** *Who are the major holders now, and how does ownership affect risk or decision-making?* Only when significant; otherwise keep pure pros/cons/next bets.
- **Research/QC addition:** Investor-ownership map, dated sources and strict checks against confusing fundraising with secondary-market share purchases, historical investors with current holders, or share valuation with investment proceeds.
- **No change to slide count:** the investment story occupies **one or at most two existing slides**.

### V1.0 → V1.1 changes at a glance

- **Kept:** 13-slide carousel, company-first hooks, origin, first money, funding/reinvestment, Secret Sauce, competitive advantage, customer acquisition, current state, reverse engineering, three-block CTA, and three-stage / three-QC workflow.
- **Strengthened:** Slide 01 with a decision question; Slide 07 fair peer comparison; Slide 09 Harvard-inspired choose-before-reveal dilemma + pros/cons; Slide 10 documented choice + comparable before/after + rival explanation; Slide 11 mixed verdict; Slide 12 realistic constraints.
- **New behind the scenes:** Case type + learning objective, historical information cutoff, comparable baseline, negative/counterevidence search, independent/editorial review log, academic sources for general mechanisms only.

---

## 10. Master change log

| Date | Version | Change |
|---|---|---|
| 2026-10-12 | 1.0 | Created reusable three-stage, three-QC workflow; preserved evidence-first 13-slide formula, Secret Sauce, reverse-engineering lesson and three-block application. |
| 2026-10-12 | 1.1 | Upgraded carousel with Harvard-style dilemma, consulting problem breakdown, competitor benchmarks, before/after metrics, pros/cons, rival explanations and an editorial peer review protocol; 13 slides and QC gates preserved. |
| 2026-10-12 | 1.2 | Added **key investors, significant financing, and ownership/control context** to Slide 05 and optional Slide 11, plus investor evidence/verification rules; kept 13 slides and three QC gates. |
| 2026-10-12 | 1.3 | Added **founder background / starting advantage** as new Slide 04, expanding master from 13 to 14 slides while preserving investor, Secret Sauce, decision, before/after, peer comparisons, reality check, reverse engineering and three separate QC approvals; added founder verification/conditional merge rules. |

**Current master state:** V1.3 active for new and revised cases. Every named company still starts at Stage 1 unless its approved dataset is already supplied and the creator explicitly advances it. New requirements never override existing per-company creator approvals; reopen a stage when new material changes factual claims.