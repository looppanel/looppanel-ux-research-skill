---
name: participant-screener-builder
description: Create participant recruitment screeners that translate a target research sample into neutral questions, qualification logic, useful variation, justified quotas, and review rules. Use for participant screeners, recruitment questionnaires, eligibility criteria, sample qualification, or improving an existing screener.
---

# Participant Screener Builder

Build concise, difficult-to-game participant screeners that recruit people with the relevant lived behavior and study context without inventing exclusions, quotas, thresholds, or logistics.

**Be opinionated about screener methodology. Be conservative about study facts.**

## 1. Confirm the Study Context Before Using Prior Artifacts

An upstream artifact such as a study brief may be available from prior context. Do not automatically assume it belongs to the current screener request.

### Use it automatically when
- the user explicitly references or supplies it in the current request; or
- the request clearly refers to the same named study and there is only one plausible upstream artifact.

### Ask for confirmation when
- more than one brief/study could plausibly apply;
- the current request could reasonably be a new study;
- the available brief conflicts with current instructions;
- the brief's status or recency is unclear and using it could materially change eligibility, quotas, population, or logistics.

Use one lightweight selection-style question when the interface supports it:

**Which study context should I use for this screener?**
- Use **[Study / brief name]** from earlier context
- This is for a **new study**
- Use a **different brief** I'll provide

If an actual dropdown/select UI is unavailable, present the same choices as a short numbered selection. Do not pretend a dropdown exists.

### Current instructions override upstream artifacts

Use this priority order:

1. Current explicit user instructions
2. Artifact explicitly supplied/referenced in the current request
3. Clearly matching upstream artifact
4. Other prior context
5. Inference

If current instructions change sample size, target population, timing, method, or other parameters, follow the current instructions and flag any meaningful conflict with the older brief.

## 2. Establish the Recruitment Target

Identify:
- target participant population;
- research objectives relevant to recruitment;
- behaviors/experience participants need;
- study method;
- requested sample size.

Use quotas, market, logistics, technology requirements, incentive, recording, language, accessibility, and known exclusions only when provided or confirmed.

If the target behavior and essential criteria are clear, proceed. Ask only when a missing criterion would materially change who qualifies.

## 3. Population Boundary Guardrail

Do not broaden the stated target population.

If the user asks for **UX researchers**, do not automatically allow PMs, designers, founders, or other research-adjacent roles to qualify merely because they perform similar tasks.

Adjacent populations may be suggested as an **optional comparison requiring confirmation**, but they must not affect:
- eligibility;
- participant-facing options;
- quotas;
- sample-size recommendations;
- routing logic

until confirmed by the user.

Behavior-based screening should determine whether people **within the approved target population** meet the study criteria; it should not silently redefine the population.

## 4. Separate Eligibility, Variation, and Quotas

These are different things.

### Hard eligibility
A criterion without which the participant cannot meaningfully answer the study's research questions.

### Useful variation
A dimension worth collecting because it may help interpretation or sample diversity, but it does not determine eligibility.

### Quota
A deliberately enforced sample-composition target because comparison or coverage on that dimension is important to the research decision.

### Review signal
An answer that deserves researcher judgment rather than automatic acceptance/rejection.

**Useful variation does not automatically become a quota.**

Do not create quotas for AI usage, seniority, team size, tooling, company size, role, geography, or any other dimension solely because variation might be interesting.

If a quota seems methodologically valuable but has not been established by the study, write:

**Optional quota to confirm:** [dimension + why it might matter]

and keep it out of qualification/routing until confirmed.

## 5. Translate Criteria Into Neutral Questions

Prefer evidence of actual behavior over identity claims or self-ratings.

Ask about:
- recent concrete experience;
- responsibility;
- actions personally performed;
- recency/frequency when relevant;
- study-specific context.

Avoid making the desired answer obvious.

Use distractor options only when ethical and genuinely useful. Never deceive participants about material study conditions.

Open text can be used for manual quality review when it provides meaningful corroboration, but do not add open-text burden merely as a trap.

## 6. Threshold Discipline

Do not invent hard numerical cutoffs merely because they make routing easier.

Examples:
- exactly 4+ interviews;
- 3+ analysis activities;
- 2+ years of experience;
- 3 studies in the last 6 months.

A threshold may be used when:
- the user or confirmed research brief specifies it;
- it follows directly from the study requirement; or
- there is a defensible methodological reason and the threshold is clearly labeled as a recommendation requiring confirmation.

Otherwise, screen for the underlying behavior and use review logic for borderline cases.

Example:

Prefer:
**Must-have:** personally synthesized findings across multiple qualitative interviews recently.

over:
**Must-have:** analyzed at least 4 interviews in the last 3 months

unless the 4-interview threshold has been explicitly justified.

Do not present arbitrary thresholds as methodological facts.

## 7. Qualification Logic

Use pass/fail only for genuine requirements.

Use scoring only when ranking candidates is actually useful; do not create point systems by default.

When quotas matter, keep quota logic separate from individual eligibility.

Do not automatically reject someone solely because they have participated in research before. If repeat participation creates a study-specific bias risk, define and justify the criterion.

Use manual review when the evidence is ambiguous rather than manufacturing false precision.

## 8. Study Logistics Discipline

Do not invent:
- recording requirements;
- consent requirements;
- session language;
- geography;
- device requirements;
- camera/microphone requirements;
- confidentiality rules;
- incentive;
- scheduling window;
- meeting platform;
- preparation requirements.

If a logistical condition is unknown:
- use `[TBD]` if it does not affect eligibility;
- place it under **Inputs to Confirm** if needed before launch;
- ask only if it materially changes who can participate.

Do not make an unknown logistical condition a disqualifier.

## 9. Prior Context and Assumption Discipline

Prior context may help, but do not silently convert it into current-study requirements.

Do not invent or assume:
- recruitment sources;
- Looppanel-user quotas;
- competitor-user quotas;
- internal customer lists;
- fraud concerns;
- company-specific policies;
- market/language requirements;
- team-size comparisons;
- seniority comparisons.

If prior context suggests something useful, label it:

**Assumption to confirm:** [...]
or
**Optional sample consideration:** [...]

Never state a plausible hypothesis as a fact solely to justify a screener rule.

## 10. Participant-Facing Messaging

Do not reveal exact qualifying answers.

Qualified, waitlist, or disqualification wording should be neutral and respectful.

Never invent:
- legal consent language;
- privacy promises;
- incentive terms;
- data-retention terms;
- scheduling details.

Use placeholders where necessary.

# Output

# Participant Screener: [Study]

## Study Context Used
- **Current request:** [...]
- **Upstream artifact:** [name / none / pending confirmation]
- **Conflicts or overrides:** [if any]

## Recruitment Target
[Who the study needs and why.]

## Qualification Rules

### Must-have
[Only genuine eligibility criteria.]

### Useful Variation
[Dimensions worth collecting but not enforcing.]

### Confirmed Quotas
[Only quotas explicitly supplied or clearly confirmed. If none: `None confirmed.`]

### Optional Quotas to Confirm
[Only when there is a clear methodological reason. Otherwise omit.]

### Exclusions
[Only justified exclusions.]

### Logistics
[Confirmed logistics + `[TBD]` items.]

## Participant-Facing Screener

### Q1. [Neutral question]
- [option]
- [option]

**Internal logic:** [qualify / disqualify / quota / review / context only]
**Why it is needed:** [brief methodological reason]

[Repeat.]

## Routing / Logic Map
[Branching, termination, waitlist, and review rules.]

Keep eligibility, quota management, and manual review visibly separate.

## Sample Composition
Summarize:
- confirmed quotas;
- useful variation to monitor;
- optional comparisons awaiting confirmation.

Do not turn useful variation into numeric targets without justification.

## Researcher Review Flags
[Ambiguous answers requiring judgment rather than automatic rejection.]

## Participant Messaging
[Neutral qualified / not-qualified / waitlist wording where useful.]

## Inputs to Confirm
List unresolved items that matter before launch, such as:
- recording requirement: [TBD]
- language/market: [TBD]
- incentive: [TBD]
- scheduling constraints: [TBD]
- optional comparison/quota: [TBD]

Do not include irrelevant TBDs simply to fill the section.

# Final Quality Check

Before returning, verify internally:

1. Am I using the correct study/research brief?
2. If prior context was ambiguous, did I ask the user to select the study context?
3. Did current instructions override conflicting older context?
4. Did I keep the target population within the user's stated scope?
5. Did I separate hard eligibility from useful variation and quotas?
6. Did I create any quota that was not supplied or clearly justified and confirmed?
7. Did I invent any numerical threshold?
8. Does every hard exclusion have a research reason?
9. Are questions behavioral and neutral rather than easy to game?
10. Are response options understandable and sufficiently complete?
11. Did I avoid arbitrary scoring?
12. Did I use manual review where ambiguity is more appropriate than a cutoff?
13. Did I invent recording, language, incentive, geography, device, consent, scheduling, or other logistics?
14. Did I convert any hypothesis or prior-context detail into a fact?
15. Does participant-facing wording avoid revealing qualification rules?

If any check fails, revise before returning.

# Skill Boundaries

This skill selects participants for a defined study.

It may:
- operationalize participant criteria;
- identify useful variation;
- propose optional quotas for confirmation;
- build routing logic;
- identify review cases;
- flag weaknesses or ambiguity in recruitment criteria.

It should not:
- redefine the target population without confirmation;
- redesign the research brief silently;
- invent study logistics;
- create the discussion guide;
- decide organizational policy.

If the upstream research brief appears internally inconsistent, flag the issue rather than silently correcting it.

Keep the methodology portable across capable LLM systems.

## How to Test This Skill

### Test 1 — Sparse Input

Prompt:

“We’re recruiting UX researchers for interviews about how they synthesize qualitative research and use AI. We need people who regularly conduct qualitative interviews and have personally synthesized a multi-interview study recently. We want 8 participants.”

**Pass if:** it produces a useful behavior-based screener without inventing organizational facts, quotas, or logistics.

### Test 2 — Study Context Confirmation

Run the skill when a previous research brief exists but the new request does not explicitly say whether to use it.

**Pass if:** when the match is ambiguous, the skill asks the user to choose between the prior brief, a new study, or another brief. When the request clearly names the same study, it uses the brief without unnecessary confirmation.

**Fail if:** it silently uses an ambiguous prior artifact.

### Test 3 — Current Instruction Override

Prior brief says 12 participants. Current request says 8.

**Pass if:** the screener uses 8 and flags the changed parameter if relevant.

**Fail if:** it reverts to 12 because the brief is older/more detailed.

### Test 4 — Population Boundary

Prompt specifies UX researchers only.

**Pass if:** PMs, designers, founders, and adjacent roles do not automatically qualify. They may appear only as an optional comparison requiring confirmation.

### Test 5 — Eligibility vs Variation vs Quota

Mention that variation in AI usage, seniority, and team size could be interesting, but do not request quotas.

**Pass if:** these are collected as useful variation unless a comparison is explicitly required.

**Fail if:** numeric quotas are invented.

### Test 6 — Threshold Discipline

Ask for participants who have recently synthesized multiple interviews without specifying a minimum count.

**Pass if:** the skill screens for genuine cross-interview synthesis and does not invent a 4+ threshold.

### Test 7 — Missing Logistics

Do not specify recording, incentive, language, platform, or scheduling.

**Pass if:** unknown logistics remain `[TBD]` or under Inputs to Confirm and are not used to disqualify.

### Test 8 — Gaming / Neutrality

Inspect whether a respondent can easily infer the desired answer from the question wording or options.

**Pass if:** questions establish behavior without transparently revealing the qualification path.

### Test 9 — Ambiguous Candidate

Include a candidate with plausible but borderline experience.

**Pass if:** manual review is used where appropriate rather than an arbitrary point score or cutoff.

## Overall Pass Criteria

The skill should recruit for the study the user actually defined—not a more elaborate study the model invented.

It should be:
- behavior-based;
- difficult to game;
- conservative about exclusions;
- disciplined about quotas and thresholds;
- transparent about unresolved logistics;
- respectful of population boundaries;
- and careful about which upstream research context it uses.
