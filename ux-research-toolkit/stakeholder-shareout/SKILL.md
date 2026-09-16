---
name: stakeholder-shareout
description: Turn approved qualitative research findings into a stakeholder-ready shareout without re-synthesizing the research or increasing the certainty of the evidence. Use when a researcher has findings or a synthesis and needs to communicate them to product, design, leadership, engineering, GTM, or cross-functional audiences. Tailors narrative, depth, evidence, implications, open questions, and decision framing to the audience while preserving provenance, confidence, contradictions, and the boundary between findings, implications, and recommendations. When supported, can additionally render the shareout as a visual presentation or interactive artifact.
---

# Stakeholder Shareout

Transform research findings into a clear, decision-useful stakeholder narrative.

This skill is a **communication layer**, not a second synthesis pass.

**Approved findings → audience framing → shareout narrative**

Never improve the story by changing what the research actually established.

---

## 1. Confirm the Study, Findings, and Audience

Before building the shareout, establish the correct upstream artifact.

### Use context automatically when
- the user explicitly references or supplies the findings/synthesis;
- one clearly matching study and one authoritative findings artifact exist;
- the intended audience is explicit or unambiguous from the request.

### Ask for confirmation when
- multiple studies could plausibly apply;
- multiple findings/synthesis versions materially differ;
- it is unclear which findings artifact is approved/authoritative;
- the intended audience materially changes the shareout and cannot be inferred safely.

When supported, use lightweight choices.

**Which findings should I use?**
- Use **[study / findings version]**
- Use a **different existing version**
- I'll provide **new findings**

**Who is this for?**
- Leadership
- Product
- Design
- Engineering
- GTM / customer-facing teams
- Cross-functional team
- Other

Do not ask questions whose answers are already clear from the user's request or authoritative context.

### Artifact Authority

Priority:
1. Current explicit user instructions
2. Explicitly approved/final/canonical findings
3. Artifact explicitly selected for this task
4. Clearly matching latest findings only when no material conflict exists
5. Other matching artifacts
6. Prior context/inference

Never assume newest = approved.

---

## 2. Findings Builder Is the Analytical Source of Truth

The primary upstream input should normally be the output of **Findings Builder**.

Preserve upstream status exactly:

- finding → finding
- implication → implication
- recommendation → recommendation
- hypothesis → hypothesis
- weak/emerging signal → weak/emerging signal
- unresolved tension → unresolved tension
- `[TBD]` → unresolved

Do not silently promote:
- a cluster into a finding;
- an implication into a finding;
- an emerging signal into a headline conclusion;
- a hypothesis into something “validated”;
- an open question into a recommendation.

If only raw evidence, tags, or an affinity map are available and no findings have been established, do not pretend a stakeholder shareout can substitute for synthesis. Explain that findings should be established first, or proceed only if the user explicitly asks this skill to work from that lower-level material and clearly label the analytical limitation.

---

## 3. Do Not Re-Synthesize During Shareout

The shareout may:
- select;
- order;
- shorten;
- explain;
- contextualize;
- tailor emphasis;
- connect approved findings to the stakeholder decision.

It should not discover materially new findings.

If something in the underlying evidence appears to support a new interpretation not present in the approved findings:
1. do not quietly add it;
2. flag it as a possible synthesis follow-up;
3. keep it out of the main shareout unless the user approves a synthesis update.

This prevents the communication layer from becoming an unreviewed analysis layer.

---

## 4. Compression Must Not Increase Certainty

This is a hard guardrail.

Shortening a finding for a slide title, executive summary, Slack message, or headline must preserve:
- confidence;
- conditions;
- population/sample boundary;
- material counterevidence;
- uncertainty.

Example:

Upstream finding:
> Researchers in this sample were more willing to delegate evidence retrieval than interpretive judgment.

Allowed headline:
> Delegation varied by the type of research work.

Not allowed:
> Researchers don't trust AI synthesis.

Not allowed:
> Researchers want AI for retrieval, not synthesis.

The latter claims are broader and more categorical than the evidence.

### Avoid certainty inflation words

Do not introduce words such as:
- always;
- universally;
- clearly;
- definitively;
- proven;
- validated;
- all users;
- researchers want;
- users need;

unless the upstream evidence genuinely supports that wording.

---

## 5. Preserve Evidence Breadth Correctly

Do not turn qualitative evidence counts into false prevalence.

Keep distinct:
- number of evidence units/quotes;
- number of independent participants/sources.

Do not write:
> “Seven researchers said…”

when the upstream artifact contains seven notes from two participants.

When upstream source counts are available, retain them accurately.

When they are not available, use qualitative language rather than inventing counts.

Avoid population-level claims from qualitative samples.

Prefer:
> “Several participants in this study…”

over:
> “Most researchers…”

unless the latter is explicitly supported and appropriate.

---

## 6. Audience Tailoring Changes Emphasis, Not Truth

Tailor what the audience sees first, how much context they receive, and which implications are most relevant.

Do not change the underlying claim.

### Leadership / Executives

Prioritize:
- decision being informed;
- 3–5 most consequential findings;
- strategic implications supported by the research;
- material risks/uncertainties;
- decisions needed;
- what remains unknown.

Do **not** invent:
- revenue impact;
- retention impact;
- conversion uplift;
- ROI;
- investment required;
- market-share effect;
- competitive impact

unless supported by supplied evidence or other explicitly authorized business data.

### Product Managers

Prioritize:
- product decision context;
- user behavior/workflow;
- constraints and unmet needs;
- implications for product direction;
- trade-offs;
- unresolved questions;
- what needs validation next.

Do not turn implications into roadmap commitments.

### Designers

Prioritize:
- behaviors;
- mental models when evidence supports them;
- workflow/journey context;
- friction;
- workarounds;
- representative evidence;
- design implications;
- tensions and edge cases.

Do not invent emotional states or “mental models” from behavior alone.

### Engineering

Prioritize:
- workflow constraints;
- failure modes;
- trust/verification requirements when supported;
- dependencies;
- edge cases;
- evidence-backed technical implications;
- uncertainties that affect implementation.

Do not infer technical architecture from research findings.

### GTM / Customer-Facing Teams

Prioritize:
- customer language;
- problems/use cases;
- expectations;
- objections/constraints;
- segment-specific evidence when genuinely supported;
- implications for messaging or enablement.

Do not convert research observations into market-size or win-rate claims.

### Cross-Functional Teams

Prioritize:
- why the study happened;
- who participated;
- coherent participant/problem story;
- key findings;
- tensions;
- implications by function where supported;
- shared decisions/open questions;
- next steps.

Avoid inventing a separate recommendation for every function simply to fill the format.

---

## 7. Audience Relevance Must Be Evidence-Safe

A finding may be framed differently for different audiences, but its factual core cannot change.

For each reframed headline, ask:

**Would the Findings Builder still recognize this as the same claim?**

If not, the framing has gone too far.

Do not manufacture business relevance where none is established.

If a stakeholder audience needs information not contained in the research—such as revenue exposure, engineering effort, market size, or roadmap dependency—label it as an additional input needed rather than filling the gap.

---

## 8. Narrative Structure

Build a coherent story rather than a dump of findings.

A useful default arc is:

**Why we researched this → What we learned → What complicates the picture → What it may mean → What decision/question comes next**

The story should follow the research, not a predetermined dramatic arc.

Do not suppress inconvenient findings because they weaken the narrative.

Do not force all studies into “problem → solution → recommendation.”

---

## 9. Findings Selection

Not every finding must appear in the main shareout.

Select based on:
- relevance to the audience's decision;
- confidence/evidence strength;
- explanatory value;
- risk;
- material contradiction;
- importance to understanding the overall study.

Move secondary findings to an appendix or “additional findings” section where useful.

### Selection must not distort

Do not omit a finding or tension if doing so would materially change the audience's interpretation of a headline finding.

Do not select only findings that support the stakeholder's prior position.

---

## 10. Evidence in the Shareout

Use enough evidence to make important claims inspectable without reproducing the entire synthesis.

Evidence may include:
- short participant quotes;
- source counts;
- behaviors/observations;
- traceable evidence IDs;
- links/references to the approved findings artifact when available.

Choose representative evidence, not merely dramatic quotes.

Preserve participant/source IDs where appropriate.

Do not fabricate or “polish” quotes.

Do not strip context in a way that changes meaning.

---

## 11. Contradictions, Caveats, and Boundaries Survive Compression

Material contradictions cannot disappear simply because the shareout is short.

For each headline finding, determine whether a boundary/tension is necessary to prevent misinterpretation.

Ways to preserve nuance without overwhelming the audience:
- a “but” line;
- confidence label;
- boundary note;
- tension card;
- “what we don't know” callout;
- appendix evidence.

Do not hide uncertainty in methodology notes when it changes the meaning of the finding.

---

## 12. Finding → Implication → Recommendation

Keep these visibly distinct.

### Finding
What research established.

### Implication
What the finding may mean for the stakeholder's decision.

### Recommendation
A proposed action that depends on research plus business/technical/strategic judgment.

Do not make recommendations mandatory.

If the approved upstream artifact contains recommendations, preserve them as recommendations.

If the user explicitly asks this skill to propose recommendations:
- ground each in specific findings;
- state assumptions beyond research;
- distinguish research confidence from decision confidence;
- do not attribute the recommendation to participants.

---

## 13. Decisions and Next Steps

A strong shareout should clarify what happens after people consume it.

But do not invent:
- owners;
- deadlines;
- roadmap commitments;
- launch dates;
- priority levels;
- investment amounts.

When these are not supplied, use:
- **Decision needed:** [...]
- **Owner:** [TBD]
- **Timing:** [TBD]

or ask only when the missing information is essential.

Research next steps may be proposed when clearly labeled as proposals.

---

## 14. Business Metrics Guardrail

Never estimate business impact from qualitative findings unless the user supplies a defensible quantitative basis or explicitly asks for a separate modeled estimate.

Forbidden inference pattern:

> 8/12 interview participants struggled → fixing this should improve activation by 15–20%.

Qualitative participant incidence is not a conversion model.

If a finding plausibly affects a metric, say:

> This may be relevant to activation; this study does not estimate the size of that effect.

Do not claim ROI, revenue impact, churn reduction, retention lift, or conversion impact from qualitative evidence alone.

---

## 15. Visual / Presentation Output

A stakeholder shareout is inherently communicative, so prefer a visual artifact when the environment supports one and the user's requested format benefits from it.

### Always maintain a portable content layer

Before or alongside rendering, maintain a structured content representation containing:
- section/slide purpose;
- headline;
- supporting finding(s);
- evidence;
- implication;
- caveat/tension;
- source reference.

This is the analytical source for the presentation.

### When presentation/visual capabilities exist

The shareout may additionally be rendered as:
- presentation/deck;
- interactive document;
- visual report;
- shareable artifact.

Use the host environment's native capability only when it actually exists.

Do not claim that a deck, interactive artifact, animation, link, or editable board was created unless it was.

### Visual hierarchy

Visual emphasis may represent:
- narrative importance for the audience;
- section hierarchy;
- evidence type;
- finding confidence when clearly labeled.

It must not imply unsupported:
- prevalence;
- statistical magnitude;
- causality;
- business impact.

Avoid charts for qualitative counts when the chart would make small-sample incidence look quantitative/generalizable.

---

## 16. Suggested Shareout Formats

Choose based on the request and environment.

### Concise stakeholder update
Best for Slack/email/async:
1. Why we ran the study
2. 3–5 key findings
3. Important tension
4. Implications
5. Decision/open question
6. Link/reference to full research

### Standard research shareout
Best for meeting/document:
1. Study context
2. Executive synthesis
3. Findings
4. Evidence
5. Tensions/edge cases
6. Implications
7. What remains unknown
8. Decisions/next steps
9. Appendix

### Presentation/deck
Default conceptual structure:
1. Title + decision context
2. Why this research / what we needed to learn
3. Who/what we studied
4. Executive synthesis
5. Finding 1
6. Finding 2
7. Finding 3
8. Tensions / where experiences diverged
9. Implications
10. What the study does not establish
11. Decisions / open questions / next steps
12. Appendix / evidence trail

Adapt slide count to content. Do not pad to reach a target.

---

# Presentation Layer: Visual Stakeholder Shareout

The analytical and evidence-safety rules above remain authoritative. The default stakeholder experience should be **visual, scannable, and decision-oriented**, not a long research report.

Produce two layers:

1. **Shareout View** — the primary stakeholder-facing experience.
2. **Research Appendix** — the complete supporting context, evidence, caveats, and traceability.

The Shareout View should answer, quickly:

**What did we learn? → Why does it matter? → Where does the evidence disagree? → What does the team need to decide? → What can research not answer?**

Do not sacrifice nuance for visual polish.

## 17. Start With the Decision, Not Methodology

The first view should orient stakeholders to the decision/context the research informs.

Preferred opening:

# [Study / Shareout Name]

**Decision we're informing**  
[One concise sentence]

**Study at a glance**  
`[X participants]` · `[method]` · `[scope]`

Then surface 3–5 evidence-safe takeaway cards.

Do not lead with a large methodology block unless methodology is itself the stakeholder's concern.

---

## 18. Executive Takeaways as Visual Cards

Do not default to one dense executive-summary paragraph.

Represent each major takeaway as a compact card:

### [Short evidence-safe headline]

**What we learned**  
[1–2 sentences]

**Evidence breadth**  
[X/Y participants/sources, when verified]

**Why it matters**  
[One concise implication]

**Boundary**  
[Material caveat/counterevidence, when needed]

A stakeholder should be able to scan the cards and understand the study without opening the appendix.

Keep headlines short, but obey the **Compression Must Not Increase Certainty** rule.

---

## 19. Quotes Are First-Class Visual Evidence

Participant quotes must **stand apart from explanatory prose**.

Never bury an important quote inside a long paragraph.

When a quote materially supports a finding, render it as a quote card/callout:

> “Exact participant wording.”
>
> **— P03 · [brief context if needed]**

Then put analysis outside the quote card.

### Quote rules

- Use only verbatim source wording.
- Preserve participant/source ID.
- Add context only outside the quote or clearly as metadata.
- Do not bold fragments inside a quote merely to steer interpretation unless the source itself had emphasis.
- Do not stitch separate excerpts into one quote.
- Prefer 1–2 strong representative quotes per main finding in the primary shareout.
- Put additional quotes in the Research Appendix.
- A dramatic quote cannot substitute for evidence breadth.
- Do not use quotation marks around paraphrases.

### Quote layout

Where supported, visually separate quote cards using spacing, container treatment, typography, or native callout components.

Quotes should be recognizable **before they are read**.

---

## 20. Use the Right Visual Primitive for the Finding

Do not render every finding as the same text card.

Choose a visual form that matches the analytical structure.

### Boundary / spectrum

Use when evidence shows a line between types of work, responsibility, or acceptance.

Example structure:

**Delegable work**  
[participants / evidence]

↔ **BOUNDARY** ↔

**Reserved judgment**  
[participants / evidence]

Show overlap when the same participants occupy both sides.

### Layered requirement

Use when participants mean different things by one broad request.

Example:

**“Show me the evidence”**

**1 · Source access**  
Where did this come from?

↓  
**2 · Evidence package**  
What contributed / what contradicts it?

↓  
**3 · Grouping rationale**  
Why do these experiences belong together?

Do not imply these are sequential maturity stages unless evidence supports that.

### Tension

Use for contradictory experiences of the same mechanism:

**“This anchors me.”**  
P02 · P06

← **SAME PRODUCT BEHAVIOUR** →

**“Give me a starting structure.”**  
P03 · P07

**UNRESOLVED**  
[What evidence does/doesn't explain]

### Branch / conditional finding

Use when behavior changes by context:

**If tactical study** → [observed preference]  
**If strategic study** → [observed preference]

Label thin evidence prominently.

### Evidence constellation / overlap

Use when participant overlap is analytically important.

Example:

`6 delegate retrieval`  
`5 reserve interpretation`  
`4 appear in both`

Do not use a Venn diagram unless the rendering environment can make it accurately and the overlap is verified.

---

## 21. Research Says / Team Decides / Unknown

This is a core shareout primitive.

For consequential product questions, separate three layers:

### RESEARCH SAYS
[Evidence-backed finding or implication]

### TEAM DECIDES
[Decision requiring product/business/technical judgment]

### RESEARCH DOESN'T ANSWER
[Missing evidence, business input, technical input, or unresolved research question]

This prevents research from pretending to make roadmap decisions while still making the shareout actionable.

Use this pattern especially for:
- scope choices;
- defaults;
- prioritization;
- feature form;
- positioning;
- segment strategy.

---

## 22. Tensions Get Their Own Visual Section

Material contradictions should not be hidden inside finding prose.

Create a **Where the evidence splits** / **Tensions** section.

Each tension should show:
- side A;
- side B;
- participants/sources on each side;
- shared mechanism or premise;
- status: **UNRESOLVED** / **PARTIALLY EXPLAINED**;
- what evidence does and does not explain.

Do not visually imply that both sides have equal prevalence unless they do.

Do not resolve the tension for the stakeholder.

---

## 23. Implications Should Be Visually Downstream of Findings

Make it obvious that implications are derived from findings.

Preferred pattern:

**FINDING**  
[what evidence says]

↓  

**IMPLICATION**  
[what it may mean]

Do not visually merge them into one claim.

Recommendations, if explicitly requested or already approved, should be another distinct layer:

**FINDING → IMPLICATION → RECOMMENDATION**

Use labels consistently.

---

## 24. Open Questions and Unknowns Must Be Easy to See

Create a distinct **What we still don't know** section.

Group unknowns where useful:

- **Research gap** — study did not answer it.
- **Product decision** — research frames but cannot choose.
- **Business input needed** — e.g. market size, revenue, strategy.
- **Technical input needed** — e.g. feasibility, model performance, engineering effort.
- **Validation needed** — emerging finding/hypothesis needs further evidence.

Do not let unknowns disappear into footnotes.

---

## 25. Methodology Becomes Supporting Context

Keep the main shareout light.

The primary view may show:

**8 participants · Moderated interviews · Recent multi-interview study experience**

Put detailed methodology, recruitment, sample limitations, evidence-count caveats, unanswered objectives, and artifact notes in the Research Appendix — **except** when a limitation materially changes a headline finding. Then surface it directly on the finding card as a boundary.

---

## 26. Visual Hierarchy and Aesthetic Quality

The shareout should feel designed, not merely formatted.

Use:
- generous spacing;
- short headlines;
- clear section hierarchy;
- consistent card structure;
- pull quotes;
- small evidence-breadth/status labels;
- restrained use of icons only when they improve comprehension;
- visual separation between Finding / Implication / Decision / Unknown.

Avoid:
- walls of text;
- 5+ sentence cards;
- giant tables as the main experience;
- decorative charts;
- excessive badges;
- rainbow color coding;
- visuals that imply statistical significance.

### Color / status encoding

When the host supports visual styling, colors may distinguish semantic states such as:
- finding;
- implication;
- tension;
- unknown;
- emerging signal.

Always pair color with text labels. Never rely on color alone.

Do not use color intensity to imply evidence magnitude unless that encoding is explicitly supported.

---

## 27. Presentation / Interactive Mode

When the environment supports presentations, interactive documents, or rich artifacts, prefer that format for a stakeholder shareout.

Useful interactions may include:
- expand evidence behind a finding;
- reveal additional quotes;
- jump to source evidence;
- filter findings by topic;
- open methodology/limitations;
- move between executive and research-detail views.

Do not claim interactivity that does not exist.

### Presentation mode

If rendering a deck, design each slide around **one communication job**.

A strong default sequence:

1. **Title + decision**
2. **What we learned — at a glance**
3. **Finding / visual 1**
4. **Finding / visual 2**
5. **Finding / visual 3**
6. **Where the evidence splits**
7. **What this means**
8. **Research says / Team decides / Unknown**
9. **What we still don't know**
10. **Next steps / decisions**
11+. **Research appendix**

Do not force this slide count. Use fewer or more when the story requires it.

Avoid copying the Markdown report one section per slide.

---

## 28. Text-Only Fallback

If rich visual rendering is unavailable, recreate the same hierarchy using concise Markdown.

For example:

### FINDING — Delegation depends on analytical responsibility
**HIGH CONFIDENCE · 7/8 SOURCES**

[Concise finding]

> “Participant quote.”
>
> **— P02**

**Why it matters →** [...]

**Boundary →** [...]

Use whitespace and labels so findings, quotes, implications, and caveats remain visually distinct.

Do not return dense paragraphs simply because the output is Markdown.

---

# Default Shareout View

# [Study Name]

## Decision We're Informing
[One sentence]

**Study at a glance:** `[X participants]` · `[method]` · `[relevant scope]`

---

## What We Learned

### 01 · [Takeaway headline]
**[CONFIDENCE] · [X/Y SOURCES]**

[1–2 sentence finding]

> “[Representative verbatim quote]”
>
> **— PXX**

**Why it matters →** [...]

**Boundary →** [...]

[Repeat for 3–5 primary findings.]

---

## [Purpose-Built Visual]

Use the most appropriate structure for the most decision-relevant relationship:
- boundary;
- layered requirement;
- tension;
- conditional branch;
- overlap.

Do not create a visual merely to decorate the shareout.

---

## Where the Evidence Splits

### [Tension]
**Side A** ← **UNRESOLVED / PARTIALLY EXPLAINED** → **Side B**

[Participants + concise evidence on each side]

**What we know:** [...]  
**What we don't know:** [...]

---

## What This Means

### FINDING
[...]

### IMPLICATION
[...]

[Repeat only for material implications.]

---

## Research Says / Team Decides / Unknown

| Research says | Team decides | Research doesn't answer |
|---|---|---|
| [...] | [...] | [...] |

Use multiple rows when needed.

---

## What We Still Don't Know

- **Research gap:** [...]
- **Validation needed:** [...]
- **Business input:** [...]
- **Technical input:** [...]

Only include categories that actually apply.

---

## Next Steps

Use only supplied/approved actions or clearly labeled proposals.

**Decision needed:** [...]  
**Owner:** [TBD unless supplied]  
**Timing:** [TBD unless supplied]

---

# Research Appendix

## Study Context and Method
[...]

## Full Findings Detail
[...]

## Additional Quotes
Quotes remain visually separated from analysis.

## Limitations / Non-Findings
[...]

## Evidence Traceability

| Shareout claim | Upstream finding | Participants/sources | Evidence IDs | Status |
|---|---|---|---|---|

---

# Presentation Quality Check

Before returning, verify:

1. Can a product stakeholder understand the decision and top findings in under two minutes?
2. Is the first screen/page/slide about the decision and learning rather than methodology?
3. Are important quotes visually separated from analysis?
4. Is every displayed quote verbatim and attributed?
5. Did I avoid embedding quotes inside dense prose?
6. Does each major finding use the visual structure best suited to its analytical shape?
7. Are tensions visually distinct from findings?
8. Are Finding, Implication, Team Decision, and Unknown visually and semantically distinct?
9. Did I avoid turning qualitative counts into charts that imply prevalence?
10. Did I avoid using evidence-unit counts as participant counts?
11. Did compression preserve confidence and boundaries?
12. Are important limitations attached to the relevant finding rather than buried?
13. Are methodology details available without dominating the primary view?
14. Does the Research Appendix preserve full traceability?
15. If a presentation was rendered, does each slide have one clear communication job?
16. Did I avoid simply converting report headings into slides?
17. If the environment is text-only, is the Markdown still highly scannable with whitespace, quote blocks, and compact sections?
18. Does the artifact look like a stakeholder communication product rather than an analysis dump?

If any check fails, revise the presentation layer without changing the approved research findings.

---

# Final Quality Check

Before returning, verify internally:

1. Correct study?
2. Correct approved findings artifact?
3. Audience established?
4. Did I avoid re-synthesizing the research?
5. Did every headline preserve the meaning and confidence of its upstream finding?
6. Did compression increase certainty anywhere?
7. Did I preserve participant/sample boundaries?
8. Did I distinguish source count from evidence-unit count?
9. Did I avoid population-level prevalence claims unsupported by the study?
10. Did material contradictions/caveats survive?
11. Did I avoid inventing revenue, retention, conversion, ROI, market, or competitive impact?
12. Did I avoid inventing owners, dates, priorities, or roadmap commitments?
13. Are findings, implications, and recommendations clearly distinct?
14. Did I avoid making recommendations unless upstream or explicitly requested?
15. If I proposed recommendations, did I label assumptions beyond research?
16. Did audience tailoring change emphasis rather than truth?
17. Did I avoid inventing mental models, emotions, technical architecture, or segment explanations?
18. Are quotes accurate and contextualized?
19. Can important shareout claims be traced back to approved findings/evidence?
20. Did I state what the research does not establish?
21. If I omitted findings from the main narrative, would their omission materially distort the story?
22. If I created a visual/presentation artifact, did visual hierarchy avoid implying unsupported magnitude or certainty?
23. Did I avoid claiming an artifact/interaction that the environment cannot actually create?

If any check fails, revise before returning.

---

# Skill Boundaries

This skill communicates established research findings.

It may:
- tailor findings to an audience;
- build a narrative;
- compress research responsibly;
- select representative evidence;
- surface implications;
- preserve tensions and limitations;
- structure decision questions;
- create a visual/presentation artifact where supported.

It should not automatically:
- conduct primary synthesis;
- turn affinity clusters into findings;
- generate new participant evidence;
- invent business impact;
- create a roadmap;
- assign owners;
- estimate ROI;
- increase certainty for executive readability;
- turn every finding into a recommendation.

**Typical input from:** Findings Builder.

**Typical outputs:** stakeholder meeting, research shareout, async update, document, presentation, or downstream decision discussion.

---

# How to Test This Skill

## Test 1 — Minimal Real-User Prompt

“Use the stakeholder-shareout skill. Create a shareout of the AI synthesis study for the product team.”

Do not add instructions about nuance, traceability, contradictions, or business claims.

**Pass if:** the skill handles those independently.

## Test 2 — Executive Certainty Trap

Provide a moderate-confidence finding with meaningful counterevidence and ask for an executive shareout.

**Pass if:** the headline becomes shorter but not more certain.

## Test 3 — Invented ROI Trap

Provide qualitative evidence about onboarding friction but no product analytics.

**Pass if:** the skill does not estimate conversion improvement, revenue impact, or ROI.

## Test 4 — Re-Synthesis Trap

Include raw evidence containing an interesting pattern absent from the approved Findings Builder output.

**Pass if:** it flags the pattern for synthesis review rather than silently adding it as a new finding.

## Test 5 — Emerging Signal

Provide an upstream emerging finding supported by 1–2 participants.

**Pass if:** it remains emerging and does not become a top-level universal claim.

## Test 6 — Contradiction Compression

Provide a strong finding with an important opposing experience.

**Pass if:** the tension remains visible in a concise shareout.

## Test 7 — Note Count Trap

Provide seven evidence units from two participants.

**Pass if:** it does not write “seven researchers.”

## Test 8 — Audience Switch

Create product and leadership shareouts from the same findings.

**Pass if:** emphasis and depth change but the factual claims do not.

## Test 9 — Finding vs Recommendation

Provide findings and implications but no approved recommendations.

**Pass if:** the skill does not invent a roadmap or “what to build” list unless asked.

## Test 10 — Missing Business Context

Ask for a leadership shareout where findings may relate to retention but no retention data exists.

**Pass if:** it states the possible relevance while explicitly saying the study does not quantify the effect.

## Test 11 — Artifact Authority

Place two materially different findings versions in context without clear approval.

**Pass if:** it establishes which one to use rather than taking the newest.

## Test 12 — Population Boundary

Provide findings from eight researchers.

**Pass if:** it uses language such as “participants in this study” rather than “researchers generally” where generalization is unsupported.

## Test 13 — Visual Output

Run where presentation/artifact capabilities are supported.

**Pass if:** it can create a stakeholder-ready visual representation while retaining a traceable content layer and without introducing unsupported quantitative visual encoding.

## Test 14 — Text-Only Environment

Run without presentation capability.

**Pass if:** it still produces a complete structured shareout and does not pretend a deck was created.

## Test 15 — Decision Gap

Ask the shareout to support a decision that requires engineering effort or market-size data not present in research.

**Pass if:** it separates what research contributes from what additional input the decision still needs.

## Test 16 — Quote Separation

Provide findings with several strong participant quotes.

**Pass if:** key quotes appear as visually distinct quote cards/callouts rather than being embedded inside explanatory paragraphs.

## Test 17 — Two-Minute Scan

Create a product-team shareout from a detailed synthesis.

**Pass if:** decision context, 3–5 primary findings, and main implication can be understood without reading the appendix.

## Test 18 — Visual Primitive Selection

Provide one boundary finding, one layered-requirement finding, and one contradiction.

**Pass if:** the skill does not render all three as identical cards and instead uses boundary/layer/tension structures appropriately.

## Test 19 — Research / Decision / Unknown Separation

Provide a finding that frames a product choice but does not rank the options.

**Pass if:** the artifact clearly shows what research says, what the team must decide, and what the study cannot answer.

## Test 20 — Methodology Demotion

Provide a long methods/limitations section.

**Pass if:** essential study-at-a-glance context remains in the primary view while detailed methodology moves to the appendix; limitations that change a finding remain attached to that finding.

## Test 21 — Deck Quality

Run in an environment with presentation capability.

**Pass if:** the deck is visually structured around communication jobs and does not simply paste one Markdown section onto each slide.

## Test 22 — Text-Only Visual Hierarchy

Run in Markdown-only mode.

**Pass if:** whitespace, labels, quote blocks, compact cards, and purpose-built text diagrams make the shareout scannable rather than report-like.

## Overall Pass Criteria

The skill should make research easier to consume **without making the research stronger, broader, cleaner, or more decisive than it actually is**.

It should be:
- audience-aware;
- evidence-safe;
- concise without certainty inflation;
- traceable;
- contradiction-preserving;
- decision-useful;
- visually communicative where supported;
- and clearly downstream of Findings Builder.
