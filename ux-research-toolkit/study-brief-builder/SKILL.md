---
name: study-brief-builder
description: Turn a business question, product decision, or research request into a decision-oriented research brief with objectives, method recommendation, participant strategy, scope, timeline assumptions, risks, and evidence of success. Use for research briefs, research plans, study proposals, methodology selection, or study design.
---

# Study Brief Builder

Create a study brief that helps a team make a better decision by making the decision, knowledge gaps, evidence needs, research approach, constraints, and unresolved inputs explicit.

**Be opinionated about research methodology. Be conservative about facts.**

Do not simply expand the user's request into a polished document. Assess the research intent first.

## 1. Start With the Decision

Identify, when possible:
- the decision or action the research should inform;
- what is currently unknown;
- what the team appears to believe or assume;
- what evidence would reduce the important uncertainty.

Keep these categories distinct:
- **Provided information** — explicitly supplied for this study.
- **Known context** — relevant context available in the current environment or supplied materials.
- **Researcher inference** — a reasonable interpretation that is not established fact.
- **Recommendation** — methodological or strategic research guidance.
- **Unknown / TBD** — information that is not known and should not be invented.

Never turn an inference, recommendation, or prior-context detail into a study fact.

## 2. Decide Whether to Ask, Infer, or Use TBD

Do not make the user complete a long intake form.

**Missing but non-critical → proceed with `[TBD]`.**
Examples: research owner, stakeholder names, incentive, exact recruitment channel, exact dates, moderator, tooling.

**Missing and design-critical → ask a focused question or make the affected recommendation conditional.**
Examples:
- Is build/no-build genuinely open, or has the decision to build already been made?
- Is a prototype or concept stimulus available when the recommended method depends on one?
- Is the goal exploratory learning or quantitative measurement?
- Are there participant populations that must be compared?

When possible, produce the parts of the brief that can already be determined and mark the affected section pending confirmation rather than blocking all progress.

**Reasonable methodological judgment → recommend and label it.**
Do not ask permission for every research judgment, but do not present recommendations as facts or mandatory requirements without support.

## 3. Use Prior Context Carefully

Relevant organizational or project context available in the current environment may improve the brief, but:
- do not assume previously known information is still current;
- do not silently introduce people, internal datasets, customer lists, tools, budgets, deadlines, product status, or organizational decisions;
- do not assign owners or responsibilities based only on prior context;
- do not treat previous customer feedback or anecdotal knowledge as established evidence for this study unless its provenance is clear.

If prior context materially changes objectives, sample, methodology, timeline, or decision criteria, surface it as an **assumption to confirm**.

Example:

**Assumption to confirm:** Existing project context suggests this capability may already be in active scoping. If the build decision has been made, the primary objective should shift from build/no-build toward defining scope, trust requirements, and interaction design.

Prior context should make the skill more useful, not less auditable.

## 4. Do Not Invent Organizational Context

Never invent or silently assume:
- stakeholder or team-member names;
- research owners;
- internal datasets or analytics availability;
- previous research findings or customer feedback;
- recruitment lists or channels;
- competitor-customer access;
- budget or incentive amount;
- deadlines;
- product-development status;
- organizational priorities;
- legal/privacy requirements;
- tools or platforms available to the team.

If useful but unknown, use `[TBD]`, list it under **Inputs to Confirm**, or ask only when it materially changes the study design.

## 5. Reframe the Research Request

Separate:
- business decision;
- assumptions/hypotheses;
- existing evidence;
- unknowns;
- research objectives.

Do not treat a plausible hypothesis as settled knowledge merely because it makes the research plan cleaner.

Example:

**Initial request:** “Find out whether researchers trust AI synthesis.”

Possible embedded assumptions:
- AI synthesis is useful enough to consider;
- trust is the primary adoption barrier;
- researchers conceptualize “AI synthesis” consistently.

A more neutral objective might be:

“Understand how researchers currently approach synthesis, where they use or avoid AI assistance, and what conditions influence whether AI-supported analysis is considered useful, trustworthy, or inappropriate.”

Preserve the business intent while making the research question neutral and answerable.

## 6. Distinguish Knowledge From Hypotheses

Statements such as “we think…”, “customers seem to…”, “synthesis is probably…”, or “researchers care about…” are hypotheses or preliminary signals unless supporting evidence is supplied.

Do not promote them to established statements such as “Researchers consistently…” unless the evidence supports that conclusion.

Put useful unproven beliefs under **Assumptions / Hypotheses to Explore**.

## 7. Select Method by Evidence Need

Choose based on what must be learned:

- **Generative interviews/contextual inquiry:** motivations, behaviors, needs, mental models, workflows, decision processes, poorly understood problem spaces.
- **Moderated usability testing:** observable interaction with a design where probing matters.
- **Unmoderated testing:** well-defined independent tasks with stable stimulus where live probing is not essential.
- **Survey:** structured measurement across a broader sample when constructs are understood and sampling supports the intended inference.
- **Diary/longitudinal study:** behavior or context that unfolds over time or is poorly recalled retrospectively.
- **Concept evaluation:** comprehension, relevance, perceived value, concerns, tradeoffs, expectations around a defined concept.
- **Mixed methods:** only when different evidence types are genuinely required.

Do not default to interviews merely because the request concerns users.

## 8. Make Stimulus-Dependent Research Conditional

If a prototype, concept, mock-up, sample output, or other stimulus would strengthen the study, recommend it.

Do not assume it exists. Do not make the entire study dependent on a stimulus unless the objective genuinely cannot be answered without it.

Prefer:

**Recommendation:** If a credible concept stimulus can be prepared, add concept evaluation after current-state exploration so participants react to concrete output rather than only hypothetical descriptions.

If the study fundamentally depends on stimulus, mark its availability as a design-critical input to confirm.

## 9. Participant Strategy

Define participants primarily by relevant behavior, responsibility, experience, or context.

Separate:
- **Must-have criteria**
- **Useful variation**
- **Comparative segments** — only when deliberate comparison is warranted
- **Exclusions** — only when methodologically justified

Avoid demographic criteria unless relevant to the question or required for representation.

Do not create precise quotas merely because they make the plan look rigorous. Prefer a recommendation for meaningful variation unless exact segment comparisons are justified.

## 10. Sample Size

Do not use fixed sample-size rules as universal truths.

When useful, recommend a range and explain what drives it:
- participant heterogeneity;
- number of important segments;
- complexity of behavior;
- method;
- desired depth;
- decision risk;
- recruitment feasibility.

For qualitative research, do not promise that a particular number guarantees saturation.

For quantitative inference, note that sample requirements depend on population, sampling approach, expected effect/precision, and analysis plan.

If information is insufficient for a defensible number, give a provisional recommendation and state what could change it.

# Output

Unless the user requests another format, produce:

# Research Brief: [Study Name]

## Decision to Inform
[What decision/action should the research inform? If uncertain, say so.]

## Background
[Only supported study context. Distinguish preliminary signals from evidence.]

## What We Know
[Evidence/context actually supplied or reliably available. If little is known, say so.]

## Assumptions / Hypotheses to Explore
[Beliefs worth investigating but not established.]

## Knowledge Gaps
[Important uncertainties the study should reduce.]

## Research Objectives

### Primary
[Most decision-relevant objectives.]

### Secondary
[Useful lower-priority objectives.]

Objectives must be neutral, researchable, and realistic.

## Out of Scope
[Questions this study should not attempt to answer.]

## Recommended Approach
- **Method:** [...]
- **Why it fits:** [...]
- **What this method can tell us:** [...]
- **What it cannot establish:** [...]
- **Optional enhancement:** [...]
- **Alternative considered:** [...]

Label methodological judgment as recommendation rather than fact.

## Participant Strategy
- **Must-have criteria:** [...]
- **Useful variation:** [...]
- **Comparative segments:** [only when justified]
- **Exclusions:** [only when justified]
- **Provisional sample:** [...]
- **Rationale:** [...]

Avoid false precision.

## Study Shape
- Moderated/unmoderated
- Remote/in-person if relevant
- Approximate duration
- Stimulus/prototype requirements
- Evidence to collect

Use `[TBD]` for unknown organization-specific logistics.

## Analysis Plan
Explain how evidence will be compared, which objectives require cross-participant synthesis, which segment comparisons matter, how contradictions/minority patterns will be handled, and what constitutes a useful answer.

## Timeline and Dependencies
Describe phases and dependencies. Do not invent exact dates, owners, or internal responsibilities.

## Risks and Mitigations
Include supported methodological/operational risks such as recruitment bias, leading concept exposure, insufficient variation, prototype readiness, scope overload, hypothetical-response bias, or uneven evidence.

## Success Criteria
Define success as reducing important uncertainty, understanding meaningful behavior/decision criteria, distinguishing plausible directions, or enabling a concrete decision—not validating a preferred hypothesis.

## Inputs to Confirm
End with a concise list of unresolved information, for example:
- Decision status: [TBD]
- Study owner: [TBD]
- Key decision-maker(s): [TBD]
- Existing stimulus/prototype: [TBD]
- Recruitment channels: [TBD]
- Incentive/budget: [TBD]
- Important segment comparisons: [TBD]

Only include genuinely unresolved and useful items. For design-critical inputs, briefly explain how the answer could change the plan.

# Final Quality Check

Before responding, verify internally:

1. Is the business decision explicit?
2. Are provided facts separated from assumptions?
3. Have plausible hypotheses remained hypotheses?
4. Did I introduce any stakeholder, owner, dataset, tool, customer list, budget, deadline, or product-status fact that was not supplied or clearly available?
5. If I used prior context, did I surface materially important details as assumptions to confirm?
6. Are objectives neutral rather than validation-oriented?
7. Does the method match the evidence need?
8. Are stimulus-dependent recommendations conditional unless genuinely essential?
9. Is participant strategy behavior-based rather than arbitrarily segmented?
10. Is sample guidance justified without false precision?
11. Are success criteria about reducing uncertainty rather than proving a hypothesis?
12. Are unresolved organization-specific inputs `[TBD]` or under Inputs to Confirm?
13. Did I ask only questions that materially affect research design?

Revise before returning if any check fails.

# Skill Boundaries

This skill defines the study at brief level.

It may reframe a business question, identify assumptions, recommend methodology and participant strategy, identify dependencies/risks, and flag missing inputs.

It should not automatically create the full screener, discussion guide, survey, participant emails, research synthesis, or stakeholder readout unless explicitly requested together.

Keep the methodology portable across capable LLM systems.

## How to Test This Skill

### Test 1 — Sparse Input / Hallucination
Prompt:
“We’re considering an AI feature that automatically synthesizes user interviews into themes and insights. We need to figure out whether UX researchers actually need this and what they would trust AI to do. Help me create a research brief.”

**Pass:** useful brief; assumptions remain assumptions; no invented stakeholders, owners, datasets, recruitment lists, budgets, tools, or product status; `[TBD]` used appropriately; only design-critical questions are asked.

**Fail:** unsupported organizational details appear as fact.

### Test 2 — Validation Framing
Prompt:
“We’ve built a new dashboard and want research to validate that users find it easier and faster.”

**Pass:** ease and speed become hypotheses/questions rather than assumed outcomes.

### Test 3 — Method Selection
Run separate prompts requiring exploratory workflow understanding, prototype usability, broader quantitative measurement, and longitudinal behavior.

**Pass:** method changes appropriately and limitations are stated.

### Test 4 — Prior Context
Run in an environment that already knows related people, projects, customers, or product plans.

**Pass:** potentially stale or design-changing context is surfaced as an assumption to confirm.

**Fail:** previous context silently becomes current study fact or people are assigned work.

### Test 5 — Stimulus
Ask about a concept where a prototype/sample output could improve research but do not say whether one exists.

**Pass:** stimulus is recommended conditionally or listed as an input to confirm.

**Fail:** the skill assumes it exists or unnecessarily makes the entire study impossible without it.

### Test 6 — Sample Precision
Provide a heterogeneous target population but little information about which comparisons matter.

**Pass:** useful variation + provisional sample with rationale.

**Fail:** arbitrary precise quotas or universal saturation claims.

## Overall Pass Criteria

The skill should behave like a strong research partner: **opinionated about methodology, conservative about facts, useful with sparse input, transparent about assumptions, selective about clarification, and disciplined about what the research can establish.**
