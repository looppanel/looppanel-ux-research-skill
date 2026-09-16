---
name: findings-builder
description: Synthesize qualitative research evidence into defensible findings, tensions, implications, and unanswered questions. Use after interviews, tagged evidence, affinity mapping, or related qualitative analysis when a researcher needs to understand what the evidence collectively means. Supports single-study and cross-study synthesis while preserving provenance, participant breadth, contradictions, uncertainty, and the distinction between evidence, findings, implications, and recommendations.
---

# Findings Builder

Turn qualitative evidence into defensible research findings.

**Evidence → Pattern → Finding → Implication. Recommendation is a separate decision layer.**

## 1. Confirm Study and Evidence Context

Do not automatically use the newest prior brief, transcript set, tagged-evidence file, affinity map, or synthesis.

Use context automatically only when the user explicitly references it or one study has one clearly matching evidence chain. If multiple studies/evidence versions could apply, ask which to use.

**Authority order**
1. Current explicit user instructions
2. Explicitly approved/final/canonical artifact
3. Artifact explicitly selected for this task
4. Clearly matching latest artifact only when no material conflict exists
5. Other matching artifacts
6. Prior context/inference

Never assume newest = approved. If plausible upstream artifacts materially disagree on population, objectives, sample, segmentation, evidence inclusion, or analytical framing and authority is unclear, establish authority before final synthesis.

Preserve upstream status: evidence remains evidence; tags remain codes; affinity clusters remain organizational groupings; hypotheses remain hypotheses; recommendations remain recommendations; `[TBD]` remains unresolved. A brief hypothesis is not a finding.

## 2. Evidence Hierarchy

Prefer the most direct evidence available:
1. Raw/verbatim participant evidence
2. Atomic evidence units/highlights
3. Tagged evidence with source traceability
4. Affinity map with traceable evidence
5. Prior synthesis/findings

Use tags and affinity maps as analytical aids, not unquestionable truth. If an affinity claim conflicts with underlying evidence, evidence wins.

Do not treat research briefs, screeners, guides, stakeholder opinions, evaluator notes, expected-answer lists, or product hypotheses as participant evidence.

If only prior synthesis is available, state that this is synthesis-of-synthesis and calibrate confidence accordingly.

## 3. Align to Research Questions Without Forcing Answers

Use confirmed objectives to understand the decision the study intended to inform, but do not force every objective to produce a finding.

For each research question, evidence may support a clear answer, conditional answer, conflicting answer, insufficient evidence, or a reframing of the original question.

It is valid to conclude: **The study does not answer this yet.**

## 4. Build Findings, Not Just Themes

A finding is an evidence-backed interpretive claim explaining something meaningful about participant behavior, needs, decisions, constraints, or context.

A strong finding answers: **What appears to be happening, under what conditions, and why does it matter?**

Do not merely rename clusters.

Weak: **Theme: Trust in AI**

Better: **Finding: Researchers were more willing to delegate evidence retrieval than interpretive judgment, suggesting acceptance varied by analytical responsibility rather than a single global level of “trust.”**

## 5. Finding Construction

For each candidate finding include:

- **Claim** — one specific interpretive statement.
- **Evidence basis** — contributing sources, evidence units/quotes, relevant clusters/tags, and context.
- **Counterevidence** — disagreement, exceptions, weakening evidence, alternate interpretations.
- **Conditions/boundaries** — where the finding appears to hold and where it may not.
- **Confidence** — calibrated from evidence quality and breadth, not frequency alone.

## 6. Participant Breadth ≠ Evidence Volume

Always distinguish evidence-unit count from independent-source count.

Do not say “7 researchers” because a tag contains 7 evidence units. Compute counts from traceable source assignments. If source counts cannot be verified, do not invent them.

## 7. Confidence Calibration

Do not assign Strong/Moderate/Emerging solely from participant count. Consider:
- breadth;
- evidence quality (behavior/direct experience vs vague opinion/speculation);
- consistency;
- counterevidence;
- context coverage;
- analytical distance from what participants actually said/did.

Use:
- **High confidence** — multiple independent sources, direct relevant evidence, limited material counterevidence.
- **Moderate confidence** — meaningful support but important boundaries/contradictions/sample limits.
- **Emerging** — thin or narrow evidence that may still matter.
- **Unresolved tension** — materially different supported experiences/interpretations that should not be collapsed.

Confidence is not statistical significance.

## 8. Contradictions Are Analytical Material

Contradictions must shape findings, not sit in a token appendix.

Ask whether disagreement is supported by differences in context, workflow, responsibility, verification behavior, study type, policy constraint, or desired outcome. Do not invent the explanation. If evidence does not explain the difference, say so.

A contradiction may become a finding only when the condition separating outcomes is supported.

## 9. Avoid False Segmentation

Do not infer that participant attributes explain differences merely because they co-occur.

Do not conclude seniority, company size, role, AI-use level, or another attribute drives behavior unless evidence supports the relationship. Unsupported segment explanations are hypotheses for future research, not findings.

Do not manufacture personas, adopter/sceptic camps, or maturity stages.

## 10. Weak Signals and Outliers

Preserve meaningful evidence from one or two sources when it exposes a failure mode, reframes the problem, identifies emerging behavior, reveals a constraint, or challenges the dominant interpretation.

Do not inflate it into a broad finding and do not discard it for low prevalence.

## 11. Separate Finding, Implication, and Recommendation

This is a hard boundary.

- **Finding:** what evidence supports about participants/context.
- **Implication:** what the finding may mean for product/service/research/decision.
- **Recommendation:** proposed action that also depends on strategy, feasibility, constraints, priorities, and risk.

The synthesizer may generate evidence-backed implications.

Do not automatically turn every finding into a product recommendation.

If recommendations are explicitly requested, separate them, identify supporting findings, label assumptions beyond research evidence, and never present them as participant demands.

Bad: **Researchers want provenance, therefore build a provenance dashboard.**

Better: **Implication: Any AI synthesis experience may need a fast path back to source evidence. The research does not determine the best interface for providing that traceability.**

## 12. Researcher Requests Are Not Evidence

Stakeholder/user instructions define the analysis task; they are not participant evidence.

Do not use evaluator notes, expected-answer lists, brief hypotheses, discussion-guide wording, or stakeholder beliefs as support for findings.

## 13. Quotes and Provenance

Use quotes selectively. Preserve participant/source ID, wording, and enough context to avoid changing meaning. Never fabricate quotes.

When possible, link findings to evidence IDs rather than relying only on illustrative quotes.

## 14. Ordering

Do not rank findings purely by prevalence. Order by decision relevance, evidence strength, explanatory power, risk/constraint, breadth, and unresolved tension.

If prevalence ordering is requested, provide it without implying frequency equals importance.

## 15. Cross-Study Synthesis

Preserve study provenance. Distinguish replicated patterns, study-specific findings, contradictions between studies, change over time, and methodological differences.

Do not merge participant counts across studies as though all studies used one sample unless designs support it.

## 16. Large Evidence Sets

Do not use arbitrary transcript-count limits as methodological rules.

If the evidence exceeds reliable working capacity, preserve a source index, process in evidence-grounded batches, use consistent scaffolding, synthesize across batches, and return to raw evidence for important final claims where possible.

Do not batch by “participant similarity” merely for convenience; it can manufacture segment differences. State batching limitations.

# Presentation Layer: Findings Workspace

The analytical methodology above remains the source of truth. The default consumption experience should **not** be a long linear Markdown report when the environment supports richer presentation.

Produce two layers:

1. **Findings Workspace** — the primary researcher-facing experience: visual, scannable, progressively disclosed, and interactive where supported.
2. **Analysis Record** — the complete audit layer: research-question coverage, evidence, quotes, counterevidence, boundaries, methodology notes, and traceability.

Do not reduce analytical rigor to make the workspace prettier. The workspace is a view over the analysis, not a replacement for it.

## 17. Progressive Disclosure

Default to showing the researcher the smallest amount of information needed to understand the synthesis, with detail available on demand.

### Level 1 — Synthesis Overview

Show:
- study name;
- participant/source count;
- number of findings;
- number of unresolved tensions;
- number of emerging signals;
- major evidence limitations;
- 3–6 executive synthesis statements.

Then show a **Findings Overview** with one row/card per finding:

| Finding | Confidence | Breadth | One-line meaning |
|---|---|---:|---|
| [Finding headline] | High / Moderate / Emerging / Tension | X/Y sources | [Plain-language interpretation] |

This overview is for navigation, not prevalence ranking.

### Level 2 — Finding Cards

Each finding should be represented as a compact card.

**[Finding headline]**

`[CONFIDENCE]` · `[X/Y SOURCES]`

**Finding**  
[1–2 sentence evidence-backed claim]

**Why it matters**  
[Short interpretation/implication]

**Evidence shape**  
[Useful compact counts or participant overlap only when verified]

**Counterevidence / boundary**  
[One short line when material]

Then provide expandable/drill-down areas when supported:
- Evidence
- Counterevidence
- Conditions / boundaries
- Interpretation
- Implication
- Traceability

Do not make the user read all evidence before understanding the finding.

### Level 3 — Evidence Detail

On expansion, show:
- evidence IDs;
- participant/source IDs;
- representative verbatim quotes;
- relevant tags/clusters;
- counterevidence;
- analytical notes.

This is the audit layer behind the card.

---

## 18. Tensions Should Be Visually Distinct

Do not format unresolved contradictions as ordinary findings.

When supported, use a two-sided tension view:

**[Tension name]**

`Position / experience A` ←──── **UNRESOLVED** ────→ `Position / experience B`

**A:** [participants/sources]  
**B:** [participants/sources]

**What the evidence explains:** [...]  
**What it does not explain:** [...]

If the tension is partially explained, label it **PARTIALLY EXPLAINED** rather than unresolved.

Do not force a midpoint or resolution.

---

## 19. Emerging Signals Should Look Emerging

Create a separate **Signals to Watch** area.

Each signal should show:
- observation;
- source breadth;
- why it may matter;
- what would clarify it.

Do not visually style an emerging signal with the same prominence as a high-confidence finding.

Do not hide it merely because it is thin.

---

## 20. Research Question Coverage Should Be Scannable

Instead of making the researcher read long prose to discover whether objectives were answered, provide a compact coverage view:

| Research question | Status | Short answer |
|---|---|---|
| RQ1 | Partial | [...] |
| RQ2 | Clear | [...] |
| RQ3 | Insufficient | [...] |

Allowed statuses:
- Clear
- Partial
- Conditional
- Unresolved
- Insufficient evidence

Selecting/expanding an RQ may reveal its evidence basis and boundaries.

---

## 21. “What We Do Not Know” Is a First-Class View

Create a prominent section for:
- objectives not answered;
- unsupported segment claims;
- prevalence not established;
- causal claims not established;
- design questions not answered;
- hypotheses that remain hypotheses.

Do not bury these only in methodology notes.

This view should make it easy for the researcher to distinguish:
**Finding / Hypothesis / Unknown / Unresolved tension.**

---

## 22. Interactivity

When the host environment supports interaction, the Findings Workspace should support useful research-review actions such as:

- expand/collapse finding evidence;
- filter by participant/source;
- filter by confidence/status;
- show only contradictions/tensions;
- show only emerging signals;
- inspect evidence IDs and quotes;
- jump from a finding to its source evidence;
- compare two findings;
- inspect participant overlap across findings.

Where safe and supported, the workspace may also allow researcher review states such as:
- **Approve**
- **Needs review**
- **Hold / do not share**

These are researcher workflow states, not changes to evidence confidence.

### Approval guardrail

Never mark a finding approved on the researcher's behalf.

If approval states are supported, default generated findings to **Needs review** unless the user has explicitly approved them.

An approved finding can become an authoritative input to downstream Stakeholder Shareout.

---

## 23. Visual Encoding Guardrails

Visual design must not make qualitative evidence look statistically representative.

### Good uses of visual encoding
- confidence category;
- participant/source breadth;
- finding/tension/signal status;
- participant overlap;
- evidence provenance;
- research-question coverage.

### Avoid
- pie charts implying population prevalence;
- percentage charts from small qualitative samples;
- bar charts where note count looks like respondent count;
- heatmaps whose intensity implies statistical magnitude;
- decorative “scores” not derived from the methodology.

If counts are shown, label whether they are:
- **sources/participants**, or
- **evidence units**.

Never use one as a proxy for the other.

---

## 24. Capability Boundary

When the environment supports visual or interactive artifacts, prefer the Findings Workspace as the primary output.

When it does not:
- simulate the same information hierarchy with compact tables, cards, disclosure-style headings, and clear status labels;
- still provide the Analysis Record;
- do not claim that filters, expandable cards, approval controls, or source jumping are interactive when they are not.

Markdown is the **portable fallback/export**, not necessarily the primary experience.

---

# Default Output

## A. Findings Workspace

# Findings: [Study Name]

**[X] participants/sources** · **[Y] findings** · **[Z] tensions** · **[N] emerging signals**

### Study Health
- **Objective:** [...]
- **Evidence:** [...]
- **Important limitations:** [...]
- **Artifact authority:** [...]

### Executive Synthesis
3–6 concise, evidence-safe statements.

### Findings Overview

| Finding | Confidence | Breadth | What it means |
|---|---|---:|---|
| [Finding 1] | High | X/Y | [...] |
| [Finding 2] | Moderate | X/Y | [...] |

### Finding Cards

#### [Finding 1]
**HIGH CONFIDENCE · X/Y SOURCES**

**Finding:** [...]

**Why it matters:** [...]

**Evidence shape:** [...]

**Counterevidence / boundary:** [...]

**Evidence ▸** [expanded where supported]  
**Interpretation ▸**  
**Traceability ▸**

[Repeat.]

### Tensions

Use visual two-sided tension treatment where possible.

### Signals to Watch

Compact cards for emerging/weak signals.

### Research Question Coverage

| Research question | Status | Short answer |
|---|---|---|

### What We Do Not Know

Prominent list of non-findings and analytical limits.

### Implications

Evidence-backed implications, separate from recommendations.

### Recommendations

Include only when explicitly requested.

---

## B. Analysis Record

Preserve the complete analytical detail behind the workspace.

### Research Question Answers
For each RQ:
- answer status;
- evidence basis;
- important boundary/tension.

### Detailed Findings
For each finding:
- Claim
- Confidence
- Evidence breadth
- Evidence basis with evidence IDs and quotes
- Supporting patterns
- Counterevidence / exceptions
- Conditions / boundaries
- Interpretation
- Implication

### Cross-Cutting Tensions
Full evidence on both sides and whether the difference is explained.

### Weak / Emerging Signals
Observation, breadth, why it matters, and what would clarify it.

### What the Study Does NOT Establish
Explicit non-findings and limits.

### Methodology / Synthesis Notes
Evidence sources, excluded material, missing evidence, batching if any, artifact conflicts, and analytical limitations.

### Traceability Index

| Finding | Participants/Sources | Evidence IDs | Upstream clusters/tags |
|---|---|---|---|

The Analysis Record may be exported as Markdown or another portable format.

---

# Presentation Quality Check

Before returning, verify:

1. Can a researcher understand the 3–6 main findings without reading the full Analysis Record?
2. Is each finding visible as a distinct, compact unit?
3. Are confidence and source breadth easy to distinguish?
4. Are tensions visually different from findings?
5. Are emerging signals visually less authoritative than established findings?
6. Can unanswered research questions be spotted quickly?
7. Is “what we do not know” prominent rather than buried?
8. Does any visual encoding imply prevalence, magnitude, or statistical confidence that the study does not support?
9. Are source count and evidence-unit count unmistakably different?
10. Is detailed evidence available without dominating the default view?
11. If interactivity is supported, can the researcher drill from finding → evidence/source?
12. If approval controls exist, did I avoid approving findings on the user's behalf?
13. If the environment is text-only, did I preserve the same hierarchy without pretending it is interactive?
14. Does the Analysis Record still contain everything required to audit the synthesis?

If any check fails, revise the presentation layer without weakening the analytical layer.

---

# Final Quality Check

Before returning, verify:
1. Correct study/evidence set?
2. Ambiguous context/authority resolved rather than guessed?
3. Participant evidence used rather than brief hypotheses, guide questions, or evaluator notes?
4. Direct evidence preferred over upstream interpretation?
5. Tags, clusters, findings, implications, recommendations kept distinct?
6. Each finding interpretive rather than a renamed cluster?
7. Every material finding traceable?
8. Participant/source breadth computed rather than inferred from evidence-unit count?
9. Frequency not used as sole importance/confidence measure?
10. Contradictions materially shape synthesis?
11. No invented explanations for contradictions?
12. No unsupported segmentation?
13. Weak signals preserved without generalizing?
14. Confidence calibrated using breadth, quality, consistency, counterevidence, context, analytical distance?
15. No unsupported statistical-sounding claims?
16. Implications separated from recommendations?
17. No feature backlog unless recommendations explicitly requested?
18. What the study does not establish stated?
19. Provenance preserved in quotes/evidence references?
20. Cross-study provenance/method differences preserved?
21. No arbitrary batching/count rules?
22. Executive claims fully supported?

If any check fails, revise.

# Skill Boundaries

This skill interprets qualitative research evidence.

It may answer research questions, construct findings, explain conditions/tensions, calibrate confidence, identify weak signals, derive evidence-backed implications, and synthesize across studies with provenance.

It should not automatically rewrite the brief, create screeners/guides, affinity-map raw evidence when mapping is the requested task, turn every finding into a recommendation, generate the stakeholder readout, invent statistical generalizability, or use stakeholder hypotheses as participant evidence.

**Typical inputs from:** transcripts, Evidence Tagger / Insight Tagger, Affinity Mapper / Evidence Clusterer.
**Typical output to:** Research Readout / Stakeholder Readout Generator.

# How to Test This Skill

## Test 1 — Minimal prompt
“Use the research-synthesizer skill. Synthesize the findings from the AI synthesis study.”

**Pass if:** contradictions, provenance, counts, confidence, and recommendation boundaries are handled without prompting.

## Test 2 — Evaluator contamination
Provide transcripts plus evaluator notes describing expected themes.
**Pass if:** evaluator notes are excluded as evidence.

## Test 3 — Tags vs findings
Provide tagged evidence with many tags.
**Pass if:** frequent tags are not simply converted into findings.

## Test 4 — Affinity map vs findings
Provide descriptive clusters.
**Pass if:** synthesis creates higher-order interpretive claims rather than renaming clusters.

## Test 5 — Note-count trap
7 evidence units from 2 participants vs 4 units from 4 participants.
**Pass if:** breadth is 2 vs 4 sources, not 7 vs 4 people.

## Test 6 — Contradiction
Same verification activity is time-saving for one participant and time-consuming for another.
**Pass if:** tension shapes the finding or remains unresolved.

## Test 7 — False segmentation
Positive AI users happen to be more junior without causal evidence.
**Pass if:** no claim that seniority drives acceptance.

## Test 8 — Compliance vs trust
One participant is policy-blocked but personally open to AI.
**Pass if:** compliance is not synthesized as personal mistrust.

## Test 9 — Finding → recommendation jump
Strong evidence for source traceability.
**Pass if:** implication is expressed without declaring a specific UI must be built.

## Test 10 — Weak signal
Interesting challenger use case from 1–2 participants.
**Pass if:** preserved as emerging rather than discarded/generalized.

## Test 11 — Unanswered RQ
Little evidence for one research objective.
**Pass if:** explicitly marked unanswered/insufficient.

## Test 12 — Context / artifact authority
Multiple briefs/evidence versions conflict and approval is unclear.
**Pass if:** authority is established before final synthesis.

## Test 13 — Upstream status
Brief hypothesis says “trust is the primary barrier.”
**Pass if:** remains hypothesis unless evidence supports it and may be rejected/reframed.

## Test 14 — Cross-study
Two related studies use different populations/methods.
**Pass if:** shared, unique, contradictory, and methodological differences remain visible.

## Test 15 — Default Consumption Layer

Run the skill in an environment capable of richer artifact rendering.

**Pass if:** the first thing the researcher sees is a scannable Findings Workspace rather than a 300-line report.

## Test 16 — Progressive Disclosure

Use a finding with 10+ evidence units, counterevidence, and several boundaries.

**Pass if:** the default card remains concise and detailed evidence is available on drill-down rather than dumped into the first view.

## Test 17 — Tension Visualization

Provide a genuine unresolved contradiction.

**Pass if:** it is visually represented as two supported sides with an unresolved/partially-explained status, not converted into an averaged finding.

## Test 18 — Qualitative Chart Trap

Use 8 participants and uneven source counts.

**Pass if:** the skill avoids percentage/pie/bar visuals that imply population prevalence and clearly labels source counts.

## Test 19 — Researcher Review State

Run where interactive approval states are supported.

**Pass if:** findings default to Needs review and the skill never self-approves them.

## Test 20 — Text-Only Fallback

Run where no interactive/visual artifact capability exists.

**Pass if:** the output still uses compact overview tables/cards and a separate Analysis Record without claiming fake interactivity.

## Overall Pass Criteria

The skill should tell the researcher what the evidence collectively supports without becoming either a frequency report or a product-strategy generator.

It should be evidence-grounded, interpretive but auditable, contradiction-aware, conservative about causality/segmentation, calibrated about confidence, explicit about unknowns, and cleanly separated from downstream recommendation/readout packaging.
