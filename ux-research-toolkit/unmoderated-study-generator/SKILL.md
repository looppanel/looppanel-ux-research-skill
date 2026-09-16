---
name: unmoderated-study-generator
description: Design a complete platform-agnostic unmoderated research study from a research brief, objective, concept, prototype, live experience, or other testable stimulus. Use for prototype tests, website/task tests, concept evaluation, first-click/navigation tasks, card sorts, tree tests, content/comprehension tests, or other research participants can complete independently. Produces the study design even when no research-platform integration is connected, and distinguishes study-design readiness from fielding readiness.
---

# Unmoderated Study Generator

Turn a research objective into a study participants can complete independently.

This skill's primary job is **research design**, not platform orchestration.

A missing Great Question, UserTesting, Maze, Lyssna, or other platform integration must never prevent the skill from designing the study.

**Research objective → method fit → stimulus/task design → participant flow → measures/questions → analysis plan → launch readiness**

---

## 1. Confirm Study Context

Prior briefs, surveys, screeners, prototypes, interview studies, and other study artifacts may exist. Do not automatically inherit them.

Use existing context automatically only when:
- the user explicitly names or supplies the study/artifact; or
- one clearly matching study exists and there is no material conflict.

Ask for confirmation when:
- multiple studies could plausibly apply;
- multiple briefs or artifact versions materially differ;
- the current request could refer to an earlier survey/interview study or a new unmoderated study;
- population, objective, stimulus, or authoritative artifact is unclear.

When supported, use a lightweight choice:

**Which study context should I use?**
- Use **[existing study / brief]**
- Use a **different existing study**
- Start a **new study**

### Artifact Authority

Priority:
1. Current explicit user instructions
2. Explicitly approved/final/canonical artifact
3. Artifact explicitly selected for this task
4. Clearly matching latest artifact only when no material conflict exists
5. Other matching artifacts
6. Prior context/inference

Never assume newest = approved.

Preserve `[TBD]` and unresolved decisions rather than filling them from unrelated prior studies.

---

## 2. Check Method–Objective Fit

Do not force an unmoderated method merely because this skill was invoked.

Ask:

**Can the research objective be meaningfully investigated through activity a participant can complete independently, without a live moderator needing to probe or adapt?**

### Strong fits
- usability/task completion;
- prototype navigation;
- website workflows;
- first-click/navigation;
- tree testing;
- card sorting;
- concept/output evaluation;
- comprehension;
- information findability;
- preference with concrete stimuli;
- review/verification behavior;
- structured reaction to generated output;
- repeated or standardized tasks.

### Weak fits
- exploratory discovery requiring deep adaptive probing;
- sensitive topics where rapport and moderator judgment are important;
- objectives primarily asking “why” without observable activity or useful follow-up mechanism;
- ambiguous concepts with no stimulus or task;
- studies where participant interpretation must be clarified live.

If fit is weak:
1. explain the mismatch briefly;
2. recommend a more appropriate method;
3. still provide an unmoderated design if useful/explicitly requested, clearly stating its limitations.

Do not silently turn an unmoderated study into a survey.

---

## 3. Determine the Evidence-Producing Activity

Before writing questions, identify what the participant will actually **do**.

Every study should have a clear activity such as:
- complete a task;
- navigate to a destination;
- review a prototype;
- inspect generated output;
- find supporting evidence;
- identify an error;
- choose between alternatives;
- organize cards;
- navigate a tree;
- interpret content;
- make a decision using a stimulus.

Then ask:

**What observable behavior or decision would produce evidence for the research objective?**

Questions should support the activity, not replace it.

Bad:
> “Would you trust an AI-generated synthesis?”

Better:
> Show a synthesis output, ask the participant to review it, decide what they would verify, inspect available evidence, identify what they would keep/change, then explain the decision.

---

## 4. Stimulus Is Broader Than a Prototype

Valid unmoderated stimuli may include:
- live product;
- live website/URL;
- Figma or other clickable prototype;
- static screens;
- screenshots;
- concept cards;
- generated output;
- workflow mock-up;
- video/demo;
- copy/content;
- navigation tree;
- card set;
- document/report;
- side-by-side concepts;
- structured scenario.

Do not require a Figma URL unless the study genuinely needs one.

### Stimulus readiness

Distinguish:

**Can I design the study?**  
from  
**Can participants field it today?**

If a stimulus is required but not ready, design the study around a clearly specified placeholder:

`[TBD — AI-generated synthesis output required before fielding]`

Then describe what the stimulus must contain to make the study valid.

Do not say “there is nothing to test” when the study can still be designed.

---

## 5. Essential Inputs

To design a useful study, establish:

### Required
1. **Research objective / decision** — what should the study help answer?
2. **Participant population** — who should complete it?
3. **Evidence-producing activity** — what will participants do?

The third may be proposed by the skill from the objective and confirmed when needed.

### Often needed before fielding
- stimulus/artifact;
- target sample;
- screener;
- language;
- incentive;
- consent/privacy wording;
- platform;
- recruitment source.

These are not automatically blockers for **design**.

Use `[TBD]` when unknown unless the missing information prevents methodological design.

---

## 6. Choose the Study Type

Select the method based on the objective and activity, not based on whichever block type a platform offers.

Possible structures include:

### Prototype / usability test
Participant completes realistic tasks using a prototype.

### Live website/product task
Participant performs tasks in a live environment.

### Concept evaluation
Participant reviews a concrete concept/output and responds through structured activity plus follow-up.

### Output review / verification test
Participant evaluates generated or system-produced output, inspects evidence, identifies errors/omissions, and decides what to accept/change.

### First-click / navigation test
Participant indicates where they would begin a task.

### Tree test
Participant navigates an information hierarchy to locate something.

### Card sort
Participant organizes items into categories; open, closed, or hybrid.

### Content / comprehension test
Participant interprets copy, instructions, reports, or other content.

### Comparative test
Participant completes equivalent evaluation across alternatives. Control order/randomization where appropriate.

### Custom unmoderated flow
Use when the research objective requires a combination.

Do not force one study per segment. Split studies only when differences in stimulus, task flow, eligibility, language, or analytical design justify separate fielding.

---

## 7. Build Tasks Before Follow-Up Questions

For each task specify:

### Scenario
Give enough context for realistic action without telling the participant what to do.

### Task
State the goal in participant language.

Avoid:
- leading instructions;
- UI labels that reveal the answer;
- internal product terminology;
- telling participants what success looks like.

### Evidence to capture
Examples:
- completion;
- path taken;
- first action;
- time-on-task where meaningful;
- errors;
- backtracking;
- selections;
- items inspected;
- evidence opened;
- changes made;
- confidence;
- explanation.

### Follow-up
Use the minimum questions necessary to understand the behavior.

Prefer:
- “What made you choose that?”
- “What, if anything, was difficult?”
- “What would you check before using this?”
- “What would you change?”

over speculative:
- “Would you use this?”
- “Do you like this?”
- “Would this save you time?”

---

## 8. Do Not Over-Instrument

Unmoderated studies are vulnerable to fatigue.

Every task/question must map to:
- a research objective;
- an interpretation need;
- a qualification need; or
- a required operational/legal need.

Remove questions that are merely “nice to know.”

Do not make every block required by default.

Mark required only when missing the response would make the participation unusable or create a compliance problem.

---

## 9. Avoid Leading and Priming

Do not reveal hypotheses before behavior is observed.

Bad:
> “Our AI helps researchers synthesize faster. Review this output.”

Better:
> “This is a synthesis generated from a set of interviews. Review it as you normally would if you received it during your work.”

Collect behavioral reaction before evaluative explanation where possible.

Do not ask satisfaction/trust questions before the participant has interacted with the stimulus.

---

## 10. Behavioral Measures vs Self-Report

Keep distinct:

### Behavioral / task evidence
What participant did.

### Self-report
What participant says about the experience.

### Researcher-derived interpretation
What the study may conclude from the two.

Do not treat:
> “I would probably use this”

as equivalent to observed successful use.

Where useful, pair a rating with an open follow-up, but do not over-index on scales.

---

## 11. Success Criteria

Define success based on the research question.

Examples:
- participant reaches correct destination;
- participant identifies relevant evidence;
- participant catches a deliberately plausible error;
- participant can explain why they accepted/rejected output;
- participant correctly interprets content;
- participant groups/navigation behavior reveals a pattern.

Do not invent numeric pass thresholds unless:
- supplied by the researcher;
- established by prior benchmarks; or
- explicitly proposed as a provisional decision rule.

Label provisional thresholds as proposals.

---

## 12. Screener Boundary

If a dedicated screener already exists, reuse only after confirming it belongs to this study and is authoritative.

If no screener exists, either:
- draft the minimum eligibility logic needed; or
- mark `Screener: [TBD / build with Screener Builder]`.

Do not recreate an elaborate screener when a dedicated Screener Builder is the intended workflow.

Population rules from the research brief must not be silently narrowed.

A role question must not accidentally eliminate a planned comparison segment.

---

## 13. Survey Boundary

An unmoderated study may contain survey-style questions, but it is not automatically a survey.

If the design contains no meaningful participant activity/stimulus and consists almost entirely of attitudinal questions, flag:

> **Method check:** This currently behaves more like a survey than an unmoderated behavioral study.

Recommend Survey Designer where appropriate.

Do not copy a prior survey into the study simply because it exists in context.

---

## 14. Study Flow

A useful default is:

1. Welcome / expectations
2. Consent/privacy if supplied/required
3. Minimal context/warm-up
4. Pre-task baseline only if analytically necessary
5. Core task 1
6. Immediate follow-up
7. Core task 2...
8. Overall reflection
9. Closing

Do not add a warm-up just because moderated interviews have one.

Do not front-load demographic questions that may prime the participant unless needed for qualification.

---

## 15. Instructions for Unmoderated Participants

Instructions must compensate for the absence of a moderator.

They should be:
- concise;
- self-contained;
- neutral;
- explicit about what the participant should do;
- clear about when to stop/move on;
- free of internal jargon.

When thinking aloud is useful, request it clearly but do not assume participants will reliably do it.

Do not depend on a moderator rescuing confusing instructions.

---

## 16. Order Effects and Randomization

Consider order effects when:
- comparing concepts;
- reviewing multiple outputs;
- sorting cards;
- asking evaluative questions after behavior;
- showing deliberately flawed vs accurate stimuli.

Randomize/counterbalance only when methodologically useful and supported by the platform.

Do not randomize by default merely because a platform can.

Document any order constraint needed for interpretation.

---

## 17. Data Quality and Anti-Gaming

Where relevant, include quality signals grounded in the task:
- coherent open-text explanation;
- completion behavior;
- consistency between action and explanation;
- task-specific comprehension;
- reasonable engagement.

Do not default to trick attention checks when natural task behavior provides better evidence.

Do not infer fraud solely from disagreement with the expected answer.

---

## 18. Analysis Plan

Before fielding, specify how each objective will be evaluated.

Use a table:

| Objective / question | Evidence captured | How it will be interpreted |
|---|---|---|

For task studies, separate:
- behavioral outcome;
- participant explanation;
- researcher interpretation.

For concept/output evaluation, define what would count as:
- acceptance;
- verification;
- correction;
- rejection;
- uncertainty;
- unexpected use.

Do not create conclusions in advance.

---

## 19. Readiness States

Every output must end with one of four statuses:

### READY TO DESIGN
Enough context exists to start design, but essential design decisions still require confirmation.

### NEEDS INPUT
A missing input prevents a valid methodological design.

State only the true blockers.

### DESIGNED — NOT FIELD-READY
The study design is complete, but operational or stimulus dependencies remain.

Examples:
- stimulus not final;
- prototype URL missing;
- screener TBD;
- incentive TBD;
- consent TBD;
- platform not selected.

### FIELD-READY
The study design and all required fielding dependencies are confirmed.

Do not call something field-ready when `[TBD]` remains on a launch-critical item.

---

## 20. Platform and Integration Boundary

The skill must work without any research-platform integration.

### No compatible integration
Produce the complete platform-agnostic study specification.

Do not fail.

### Compatible integration available
After the study design is established, the skill may optionally map it into supported platform constructs or create/configure the study when the user asks and the environment permits it.

Platform mechanics are downstream of methodology.

Do not alter the research design merely to fit a platform's default blocks without flagging the compromise.

Never claim a study was created in a platform unless it actually was.

---

## 21. Unknown Organizational Policy

Never invent:
- incentive amount;
- currency;
- consent form;
- naming convention;
- participation cap;
- recruitment source;
- language;
- legal/privacy language;
- default platform;
- always-on screener questions.

Use `[TBD]` or supplied organizational defaults.

Reasonable methodological defaults may be proposed, but label them as recommendations rather than company policy.

---

# Default Output

# Unmoderated Study: [Study Name]

## Study Status
**[READY TO DESIGN / NEEDS INPUT / DESIGNED — NOT FIELD-READY / FIELD-READY]**

**Why:** [...]

## Study Context
- **Decision / objective:** [...]
- **Participant population:** [...]
- **Authoritative source:** [...]
- **Study type:** [...]
- **Why unmoderated fits:** [...]
- **Key limitation:** [...]

## Stimulus

**Type:** [prototype / live product / generated output / static concept / tree / cards / etc.]

**Status:** [Ready / Draft / TBD]

**Required characteristics:**
- [...]
- [...]

**Fielding blocker:** [Yes/No]

## Research Questions
1. [...]
2. [...]

## Participant Flow

### Welcome
[Participant-facing copy]

### Task 1 — [Task name]

**Scenario**  
[...]

**Participant instruction**  
[...]

**Evidence captured**
- [...]

**Follow-up**
1. [...]
2. [...]

**Maps to:** RQ[...]

[Repeat.]

## Overall Reflection
Only questions needed after the tasks.

## Measures / Signals

| Signal | Type | Why it matters |
|---|---|---|
| [...] | Behavioral / self-report | [...] |

## Screener / Eligibility
- **Population:** [...]
- **Existing screener:** [artifact / none]
- **Status:** [confirmed / needs confirmation / TBD]
- **Minimum eligibility logic:** [...]

## Analysis Plan

| Research question | Evidence | Interpretation approach |
|---|---|---|
| [...] | [...] | [...] |

## Operational Setup

| Item | Status |
|---|---|
| Target sample | [value/TBD] |
| Stimulus | [Ready/TBD] |
| Screener | [Ready/TBD] |
| Incentive | [value/TBD] |
| Consent/privacy | [Ready/TBD] |
| Language | [value/TBD] |
| Recruitment | [value/TBD] |
| Platform | [value/TBD] |

## Launch Blockers
Only true blockers:
- [...]

## Pre-Field Quality Check
- [ ] Stimulus works without moderator assistance
- [ ] Instructions are understandable independently
- [ ] Tasks do not reveal the answer
- [ ] Behavioral evidence precedes evaluative questions where appropriate
- [ ] Every question maps to an objective
- [ ] Order/randomization is intentional
- [ ] Success/interpretation criteria are defined
- [ ] Screener matches intended population
- [ ] Consent/privacy requirements are confirmed
- [ ] No launch-critical TBDs remain

---

# Final Quality Check

Before returning, verify:

1. Correct study context?
2. Artifact authority resolved?
3. Is unmoderated research a defensible fit?
4. Did I identify an evidence-producing participant activity?
5. Is this genuinely more than a survey?
6. Did I avoid requiring a particular research platform?
7. Did I distinguish design readiness from field readiness?
8. If stimulus is missing, did I design around a clear placeholder where possible rather than refusing?
9. Did I state what the stimulus must enable?
10. Are tasks neutral and behavior-oriented?
11. Did I avoid leading/priming before activity?
12. Did I distinguish behavioral evidence from self-report?
13. Does every task/question map to an objective?
14. Did I avoid over-instrumenting?
15. Did I avoid making all questions required by default?
16. Did I preserve population boundaries?
17. Did I avoid inheriting an unrelated survey/screener/study?
18. Are success criteria evidence-safe rather than invented benchmarks?
19. Did I consider order effects deliberately?
20. Does the analysis plan exist before fielding?
21. Did I avoid inventing org policy?
22. Are launch blockers only actual blockers?
23. Is the readiness status accurate?
24. If a platform integration is unavailable, did I still produce the study design?
25. If a platform action was taken, did I accurately report what was actually created?

If any check fails, revise.

---

# Skill Boundaries

This skill designs unmoderated research studies.

It may:
- assess method fit;
- propose the evidence-producing activity;
- select an unmoderated study type;
- design stimulus requirements;
- write participant tasks/instructions;
- write targeted follow-ups;
- define measures/signals;
- create an analysis plan;
- identify launch dependencies;
- map a finished design to a compatible platform when available and requested.

It should not automatically:
- write a full research brief when one exists;
- turn the study into a survey because stimulus is missing;
- recreate a full screener when Screener Builder is the intended tool;
- invent incentives/consent/org policy;
- require Great Question or any other specific platform;
- declare field readiness with unresolved blockers;
- activate/recruit/launch unless explicitly requested and supported.

**Typical input from:** Research Brief Writer, Screener Builder, product/design artifacts.

**Typical output to:** fielding platform, research operations, or later Evidence Tagger / Findings Builder.

---

# How to Test This Skill

## Test 1 — Minimal prompt
“Use the `unmoderated-study-builder` skill. Create an unmoderated study for the AI synthesis concept.”

**Pass if:** it does not fail because Great Question is absent and does not automatically reuse the prior survey.

## Test 2 — Missing stimulus
Provide the AI synthesis objective but no finished concept output.

**Pass if:** it designs the study, specifies the required stimulus, marks it as a fielding blocker, and returns **DESIGNED — NOT FIELD-READY** when appropriate.

## Test 3 — Survey collapse
Give an objective about trust in AI.

**Pass if:** it proposes concrete output-review/verification behavior rather than only “Would you trust this?” questions.

## Test 4 — Method mismatch
Ask for unmoderated exploratory research on a sensitive, deeply contextual topic.

**Pass if:** it flags the fit issue and recommends a better method without pretending unmoderated is ideal.

## Test 5 — Platform absence
No research-platform connector exists.

**Pass if:** complete study spec is still produced.

## Test 6 — Platform availability
A compatible platform is connected.

**Pass if:** methodology is designed first and platform mapping is downstream; it does not let platform defaults dictate the research.

## Test 7 — Placeholder contamination
Original template contains incentive/currency/consent/title placeholders.

**Pass if:** no placeholder or invented company policy appears as a confirmed value.

## Test 8 — Prior survey in context
A survey for the same broad topic exists.

**Pass if:** the skill confirms context/authority and does not simply paste survey questions into the unmoderated study.

## Test 9 — Population conflict
Brief includes researchers + PM/design practitioners while an old screener excludes non-researchers.

**Pass if:** the conflict is surfaced rather than silently narrowing the sample.

## Test 10 — Behavioral ordering
Concept stimulus plus post-task trust questions.

**Pass if:** interaction/review occurs before trust/evaluation questions.

## Test 11 — Prototype test
Provide a prototype and task objective.

**Pass if:** scenarios avoid UI-label leakage and success evidence is defined.

## Test 12 — Card sort
Provide cards but no categories.

**Pass if:** it recognizes an open sort rather than inventing categories.

## Test 13 — Tree test
Provide a navigation hierarchy and target task.

**Pass if:** task language does not reveal the target label.

## Test 14 — Comparative concepts
Provide two concepts.

**Pass if:** it considers order/counterbalancing and does not assume fixed ordering.

## Test 15 — Over-instrumentation
Give five research questions and many “nice to know” topics.

**Pass if:** it prioritizes and removes unnecessary participant burden.

## Test 16 — Readiness accuracy
Leave incentive, consent, and stimulus unresolved.

**Pass if:** it does not label the study FIELD-READY.

## Test 17 — No arbitrary segment splitting
Provide two participant segments using the same stimulus and flow.

**Pass if:** it does not automatically create two studies unless separate fielding is methodologically/operationally justified.

## Test 18 — Analysis plan
Provide a complex output-verification task.

**Pass if:** the study states how behavior and explanations will answer each research question before fielding.

## Overall Pass Criteria

The skill should create a methodologically useful unmoderated study regardless of platform availability.

It should be:
- platform-agnostic;
- behavior-first;
- stimulus-aware;
- context-safe;
- conservative about assumptions;
- clear about method fit;
- explicit about design vs fielding readiness;
- efficient for participants;
- and ready to map into whatever supported research platform the team uses.
