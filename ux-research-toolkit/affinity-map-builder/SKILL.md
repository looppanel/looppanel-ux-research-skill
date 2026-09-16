---
name: affinity-map-builder
description: Create evidence-grounded affinity maps from qualitative research notes, quotes, highlights, or tagged evidence. Group evidence units into clusters and higher-order groups while preserving source traceability, contradictions, outliers, and uncertainty. Produce a portable structured map and, when the environment supports it, an additional visual or interactive affinity-board representation with inspectable evidence cards. Use for affinity mapping, affinity diagrams, clustering research notes, grouping observations, thematic clustering before synthesis, or organizing qualitative evidence.
---

# Affinity Map Builder

Create an affinity map that helps a researcher reorganize qualitative evidence without prematurely turning clusters into findings.

The core unit is **evidence**, not a tag and not a pre-existing theme.

**Affinity mapping organizes evidence. It does not finish the synthesis.**

---

## 1. Confirm the Study and Evidence Context

Prior transcripts, tagged evidence, research briefs, screeners, guides, or affinity maps may exist in context. Do not automatically assume the most recent artifact belongs to the current request.

### Use context automatically when
- the user explicitly references or supplies the evidence/artifact;
- the request clearly names the same study and only one plausible evidence set exists.

### Ask for confirmation when
- more than one study/evidence set could plausibly apply;
- multiple affinity-map versions materially differ and authority is unclear;
- a tagged-evidence file and raw evidence appear to belong to different studies;
- the current request could reasonably refer to a new study.

When supported, use a lightweight selection control:

**Which evidence should I map?**
- Use **[study / evidence set]**
- Use a **different existing study**
- I'll provide **new evidence**

If selection UI is unavailable, use the same choices as a short numbered question.

### Current instructions are authoritative

Priority:
1. Current explicit user instructions
2. Explicitly approved/final or explicitly selected artifact
3. Clearly matching upstream evidence artifact
4. Other prior context
5. Inference

Do not use recency alone as proof of authority.

### Upstream status preservation

A tag is a tag, not a finding.
A hypothesis is a hypothesis.
A recommendation is a recommendation.
A `[TBD]` remains unresolved.

Do not promote upstream interpretation simply because it exists.

---

## 2. Establish the Evidence Units

Accept:
- verbatim quotes;
- research notes;
- highlights;
- tagged evidence;
- observations;
- open-ended survey responses;
- support/customer-feedback excerpts.

Each evidence unit should retain, where available:
- evidence/unit ID;
- participant/source ID;
- verbatim quote or original note;
- upstream tags;
- relevant metadata such as segment or study context.

### Atomicity

If one note contains genuinely separate observations, it may be split into atomic evidence units.

When splitting:
- preserve the original source;
- preserve the original wording;
- do not create meaning that was not present;
- make the split traceable to the original unit.

Do not rewrite verbatim quotes into cleaner statements and then treat the rewrite as evidence.

---

## 3. Cluster Evidence Units, Not Tag Labels

If tagged evidence exists, tags are metadata that may help retrieval and orientation. They are **not** the objects to affinity-map by default.

Cluster the underlying evidence units.

Why:
- grouping tags inserts an extra interpretive layer;
- different evidence carrying the same tag may belong in different affinity contexts;
- one evidence unit may legitimately contribute to more than one conceptual relationship.

Do not simply:
- sort by existing tag;
- turn each tag into a cluster;
- rank tags by frequency and call them themes.

If only aggregate tags are available and the underlying evidence cannot be accessed, state that limitation before producing a tag-level approximation.

---

## 4. Bottom-Up Grouping

Build clusters from conceptual relationship in the evidence.

Start specific.

Prefer a cluster such as:

**“Being able to get back to the original conversation”**

over:

**“Trust”**

when the former better describes what the evidence actually says.

Cluster names should describe the contents without claiming the research conclusion.

### Do not force a target cluster count

Do not impose arbitrary rules such as:
- 8–15 clusters for 50–100 notes;
- no more than 20 clusters;
- every cluster must contain 3+ participants.

Granularity should follow the evidence and the intended usefulness of the map.

If the map becomes overly fragmented, propose possible merges. Do not merge merely to hit a number.

---

## 5. Cluster ≠ Finding

This is a hard boundary.

An affinity cluster is a grouping of related evidence.

It is **not automatically**:
- an insight;
- a finding;
- a user need;
- a product requirement;
- a recommendation;
- a prevalence claim.

Do not attach an “insight statement” to every cluster by default.

Instead include a short **cluster rationale** explaining what makes the evidence belong together.

Interpretive findings belong downstream in synthesis.

---

## 6. Higher-Order Groups

After first-pass clustering, organize related clusters into higher-order groups when this improves navigation.

Higher-order group labels should remain descriptive rather than pretending to be final themes.

Example:

**What has to come attached to an answer**
- Return to source conversation
- Provenance structure
- Explanation beyond quotes
- Editable output

Do not create higher-order groups merely because a visually symmetrical map looks cleaner.

---

## 7. Preserve Cross-Cutting Evidence

An evidence unit may appear in more than one cluster when it genuinely supports multiple relationships.

When this happens:
- retain the same evidence ID;
- record every cluster placement;
- distinguish cross-cutting placement from accidental duplication.

Never duplicate a quote in a way that makes it look like two independent pieces of evidence.

Include a coverage/cross-placement audit in the structured output.

---

## 8. Contradictions and Tensions

Do not average disagreement away.

Actively look for:
- same activity, opposite outcome;
- same premise, opposite conclusion;
- same mechanism, wanted by one participant and unwanted by another;
- apparently conflicting preferences held by the same participant;
- evidence that complicates an otherwise coherent cluster.

A contradiction may be represented:
- inside a cluster;
- between clusters;
- as a held-in-tension evidence card;
- in a dedicated tension layer.

Do not force contradictory evidence into separate “personas” or camps unless the evidence supports that segmentation.

Do not resolve a product or research decision merely because the affinity map exposes it.

---

## 9. Outliers and Weak Clusters

Do not force every item into a large cluster.

An outlier may remain:
- ungrouped;
- in a single-source cluster;
- in an emerging cluster;
- held against another cluster as a tension.

Single-source evidence is not invalid. Label its evidentiary breadth accurately.

For each weak/thin cluster, distinguish:
- number of evidence units;
- number of independent sources/participants.

Do not imply that five notes from one participant equal five participants.

---

## 10. Frequency and Prevalence Discipline

Always distinguish:

**Evidence-unit count** — how many notes/quotes are assigned.

**Source count** — how many independent participants/sources contributed.

Do not use note count as a proxy for prevalence.

Do not rank clusters by frequency unless the user asks for a frequency view.

Even when requested, state that qualitative frequency does not by itself establish importance.

---

## 11. Relationship Mapping

Map relationships only when supported by evidence.

Possible relationship types:
- tension / contradiction;
- overlap;
- sequence;
- dependency;
- condition/context;
- part-of;
- enables/constrains.

### Causality guardrail

Do not label A → B as causal merely because the concepts co-occur or appear sequentially.

Use **causes/leads to** only when participant evidence or study design supports a causal claim.

Otherwise use a weaker relationship such as:
- associated with;
- occurs before;
- conditions;
- appears alongside;
- held in tension with.

---

## 12. Coverage Audit

Before returning, account for the input evidence.

Report:
- total evidence units received;
- total units placed;
- units intentionally ungrouped;
- cross-cutting units appearing in multiple clusters;
- missing/unusable units;
- number of independent sources.

Do not drop evidence because it does not fit the emerging structure.

If evidence is excluded because it is unusable, duplicated, outside scope, or lacks enough context, state why.

---

# 13. Output Representation: Structured + Visual/Interactive

The affinity map has two layers.

## Layer A — Portable Structured Map (always required)

Always produce a structured textual representation first.

This is the canonical analytical record because it preserves:
- evidence IDs;
- source IDs;
- verbatim evidence;
- cluster membership;
- cross-placement;
- tensions;
- outliers;
- coverage.

The structured map must remain usable even if no visual renderer exists.

## Layer B — Visual / Interactive Affinity Board (when supported)

When the environment supports visual or interactive artifacts, additionally render the affinity map as a board.

Preferred hierarchy:

**Higher-order group → Cluster → Evidence cards**

Each evidence card should expose, where available:
- evidence ID;
- participant/source ID;
- short evidence preview;
- full original evidence on expand/open;
- upstream tags as secondary metadata;
- tension/outlier/cross-cutting status.

### Preferred interactions, when the environment can actually support them

Allow the researcher to:
- expand/collapse groups and clusters;
- inspect the full evidence behind a card;
- filter by participant/source;
- filter by upstream tag or metadata;
- search evidence;
- move/reassign a card between clusters;
- multi-select cards;
- merge clusters;
- split clusters;
- rename clusters/groups;
- mark a card as outlier or tension;
- show/hide cross-cutting placements;
- inspect source count separately from evidence count;
- undo/review structural changes where supported.

### Interaction boundary

A Markdown skill cannot guarantee that the host LLM/client can render or persist an interactive board.

Therefore:
- use native interactive/visual capabilities only when they actually exist;
- do not claim a board is draggable, editable, saved, or interactive unless the environment supports those actions;
- if interaction is unavailable, return the structured affinity map plus the best supported visual representation;
- if only text is supported, explicitly say that the output is the **underlying affinity structure** and can be rendered as a board in a compatible environment.

Do not refuse to affinity-map because visual rendering is unavailable.

---

## 14. Visual Design Rules

The visual layer is an analytical interface, not decoration.

### Board layout

Prefer:
- columns or swimlanes for higher-order groups;
- cluster containers within groups;
- evidence cards inside clusters;
- a clearly separated tension/outlier area when useful.

Avoid:
- radial diagrams that imply centrality without evidence;
- bubble sizes that imply importance merely from note count;
- arrows implying causality without support;
- heatmaps that convert qualitative evidence into false quantitative certainty;
- decorative visual hierarchy that makes one cluster look more important without analytical justification.

### Evidence cards

Keep evidence visible enough that the researcher can judge the grouping.

Do not render only cluster titles with participant counts and call that an affinity map.

For large maps, cards may show a short preview, but full evidence must remain accessible in an interactive environment or available in the structured companion output.

### Visual encoding

If visual distinctions are used for:
- participant;
- segment;
- evidence type;
- tension;
- outlier;
- cross-cutting placement;

include a legend and do not rely on color alone.

Do not assign meaning to color arbitrarily.

---

## 15. Researcher Control

Treat the map as a proposal that the researcher can reshape.

The system may suggest:
- possible cluster merges;
- possible splits;
- alternate labels;
- overlooked relationships;
- evidence that may be misplaced.

Do not silently apply consequential restructuring after the initial map if the user is actively reviewing it.

Where interaction is supported, researcher edits should preserve evidence provenance.

Never lose the original evidence/source relationship when a card moves.

---

# Output Format

# Affinity Map: [Study / Evidence Set]

## Context Used
- **Study:** [...]
- **Evidence source:** [...]
- **Upstream tagged evidence:** [artifact / none]
- **Artifact authority:** [...]
- **Current-request overrides:** [...]

## Coverage
- **Evidence units received:** X
- **Evidence units placed:** X
- **Independent sources:** X
- **Cross-cutting units:** X
- **Intentionally ungrouped/outliers:** X
- **Excluded/unusable:** X + reason

## Board View

### Group A — [Descriptive group label]

#### Cluster A1 — [Descriptive cluster name]
**Cluster rationale:** [Why these units belong together]
**Evidence units:** X
**Sources:** X — [IDs]

**Evidence cards**
- `[P01-E3]` **P01** — “verbatim or original evidence”
- `[P04-E7]` **P04** — “verbatim or original evidence”

**Held in tension**
- `[P07-E2]` **P07** — “verbatim evidence” — [brief reason]

[Repeat.]

## Outliers / Emerging Clusters
[...]

## Tensions the Map Holds
For each:
- tension description;
- evidence on each side;
- participant/source IDs;
- whether it is within-person or across participants;
- why it remains unresolved.

## Relationships Between Clusters
| From | To | Relationship | Evidence basis |
|---|---|---|---|

Only include supported relationships.

## Cross-Cutting Evidence Audit
List evidence IDs placed in more than one cluster and all placements.

## Weak / Thin Clusters
Call out clusters whose note count could be mistaken for broad support.

## Groupings Considered but Not Made
Include only when useful. Explain tempting but misleading groupings the evidence does not support.

## What This Map Does Not Establish
State important analytical boundaries:
- clusters are not automatically findings;
- note count is not participant prevalence;
- tensions remain unresolved;
- downstream synthesis is still required.

## Visual / Interactive Representation
- **Mode used:** [native interactive board / visual board / text-only structured map]
- **Available interactions:** [only capabilities actually available]
- **Traceability:** [how evidence/source can be inspected]
- **Limitations:** [if any]

---

# Final Quality Check

Before returning, verify internally:

1. Am I using the correct study/evidence set?
2. If context or artifact authority was ambiguous, did I ask rather than guess?
3. Did I cluster underlying evidence rather than simply group tag labels?
4. Did I preserve verbatim/original evidence and source IDs?
5. Did I avoid turning every cluster into an insight/finding?
6. Did I avoid arbitrary cluster-count targets?
7. Did I preserve contradictions rather than smoothing them away?
8. Did I distinguish evidence-unit count from independent-source count?
9. Did I avoid treating frequency as importance?
10. Did I preserve single-source/outlier evidence without overstating it?
11. Did I account for every input evidence unit?
12. If units appear in multiple clusters, did I identify them as cross-cutting rather than independent duplicates?
13. Did I avoid unsupported causal arrows?
14. Are higher-order groups descriptive rather than premature themes?
15. Did I avoid imposing an adopter/sceptic or other segmentation unless the evidence supports it?
16. Did the structured map remain complete and auditable?
17. If visual/interactive capabilities exist, did I provide the additional board representation?
18. Did I avoid claiming interactions that the host environment cannot actually perform?
19. Does the visual layout avoid implying unsupported importance, prevalence, or causality?
20. Can a researcher reshape the map without losing provenance?

If any check fails, revise before returning.

---

# Skill Boundaries

This skill organizes evidence before synthesis.

It may:
- normalize/split compound notes carefully;
- cluster evidence;
- create higher-order groups;
- preserve tensions/outliers;
- map supported relationships;
- produce a visual/interactive board where supported;
- suggest structural revisions.

It should not automatically:
- declare final research findings;
- rank product opportunities;
- recommend what to build;
- calculate statistical significance;
- turn qualitative frequency into prevalence;
- invent causal relationships;
- overwrite the source evidence;
- claim a visual/interactive capability the environment does not have.

For interpretation and findings, hand off to the Research Synthesizer / Evidence Synthesizer.

---

## Chaining

**Typical inputs from:**
- Evidence Tagger / Insight Tagger
- raw interview highlights
- qualitative notes
- survey open ends
- support/customer evidence

**Typical output to:**
- Research Synthesizer / Evidence Synthesizer
- Research Readout, after synthesis rather than directly when possible

The affinity map should remain a distinct analytical artifact, not a disguised synthesis report.

---

# How to Test This Skill

## Test 1 — Minimal Real-User Prompt

Prompt:

“Use the affinity-mapper skill. Create an affinity map from the AI synthesis study interviews.”

Do not add instructions about traceability, contradictions, outliers, or visual output. Those are the skill's job.

**Pass if:** it independently preserves evidence provenance, contradictions/outliers, and produces the best visual/interactive representation actually supported.

## Test 2 — Tagged Evidence Is Not the Map

Provide evidence with an existing tag taxonomy.

**Pass if:** it clusters the evidence units rather than merely turning each tag into a cluster.

## Test 3 — Premature Synthesis

Use evidence containing several related but meaningfully different concerns around “trust.”

**Pass if:** it creates specific descriptive clusters rather than one generic Trust theme or attaching a final insight to every cluster.

## Test 4 — Frequency Trap

Provide five notes from one participant and three notes from three different participants.

**Pass if:** it reports note count and source count separately and does not imply the five-note cluster is more prevalent.

## Test 5 — Contradiction

Provide participants describing the same mechanism with opposite reactions.

**Pass if:** the shared mechanism and disagreement remain visible rather than being averaged into a neutral statement.

## Test 6 — Cross-Cutting Evidence

Provide one evidence unit relevant to two relationships.

**Pass if:** it can appear in both places with the same evidence ID and is reported in the cross-cutting audit.

## Test 7 — Outlier

Include a unique but relevant observation from one participant.

**Pass if:** it remains visible and is labeled thin/outlier/emerging rather than discarded or inflated into a broad theme.

## Test 8 — Causality

Provide sequential but non-causal evidence.

**Pass if:** the relationship is described as sequence/association rather than “causes.”

## Test 9 — Visual Capability Available

Run in an environment that supports a board, canvas, artifact, or comparable interactive surface.

**Pass if:** it produces the structured map plus a visual board with evidence cards grouped under clusters/groups and preserves source traceability.

## Test 10 — No Visual Capability

Run in a text-only environment.

**Pass if:** it still completes the affinity map, explicitly labels it as the underlying affinity structure, and does not pretend the cards are draggable/interactive.

## Test 11 — Interaction Integrity

Where interactive editing exists, move an evidence card between clusters or rename/split a cluster.

**Pass if:** evidence ID, original evidence, source ID, and cross-placement history/provenance remain intact.

## Test 12 — Visual Misrepresentation

Inspect the board for visual encodings.

**Pass if:** card/group size, position, color, and arrows do not imply unsupported importance, prevalence, or causality.

## Test 13 — Coverage

Provide a known number of evidence units.

**Pass if:** placed + intentionally ungrouped + excluded/unusable accounts for the input, with cross-cutting placements not double-counted as new evidence.

## Overall Pass Criteria

The skill should produce a researcher-editable affinity structure grounded in original evidence.

It should be:
- bottom-up;
- traceable;
- contradiction-preserving;
- conservative about interpretation;
- honest about evidence breadth;
- complete enough to audit;
- visually useful when supported;
- interactive when the host environment genuinely permits it;
- and clearly upstream of final synthesis.
