---
name: interview-study-setup
description: Turn a research brief or equivalent study context into an execution-ready moderated interview study specification covering participants, upstream research assets, recruitment handoffs, session logistics, consent and recording dependencies, incentives, scheduling, and launch readiness. Use when preparing, setting up, operationalizing, or reviewing a moderated interview study.
---

# Interview Study Setup

Translate an approved research plan or current study request into an operational study specification.

This skill prepares the study for execution. It does **not** assume any particular research platform, MCP, scheduling system, incentive provider, meeting tool, or write integration.

**Be operationally useful without inventing organizational facts.**

---

## 1. Confirm the Study Context

This skill may have access to prior research briefs, screeners, discussion guides, or other studies. Do not automatically assume the most recent artifact belongs to the current request.

### Use prior artifacts automatically when

- the user explicitly references or supplies them in the current request; or
- the user clearly names the same study and there is only one plausible matching set of upstream artifacts.

### Ask for confirmation when

- more than one study or artifact set could plausibly apply;
- the current request could reasonably be a new study;
- artifacts from different studies may be mixed in context;
- a prior artifact conflicts with the current request;
- artifact status or recency is unclear and using it could materially change the study setup.

When the interface supports selection controls, ask:

**Which study context should I use?**
- Use **[Study name]** and its existing artifacts
- This is a **new study**
- Use a **different study / artifacts** I'll provide

If a select/dropdown UI is unavailable, present the same options as a short numbered choice. Do not pretend a dropdown exists.

### If multiple upstream artifacts exist

Confirm the study once, then identify which matching artifacts are available:

- Research brief
- Screener
- Discussion guide
- Stimulus/prototype
- Participant communications
- Other relevant study assets

Do not repeatedly ask the user to confirm each artifact when they clearly belong to the same confirmed study.

### Artifact Authority Guardrail

Do not determine which artifact is authoritative solely by recency.

Use this authority order when multiple versions exist:

1. Current explicit user instructions
2. Artifact explicitly marked approved, final, live, canonical, or otherwise authoritative by the user
3. Artifact explicitly referenced or selected by the user for the current task
4. Clearly matching latest artifact, only when no material conflict exists and no stronger authority signal is available
5. Other matching artifacts
6. Prior context or inference

Never assume that:
- later = approved;
- newer = final;
- more detailed = authoritative;
- an artifact supersedes another merely because it was created afterward.

If multiple matching artifacts materially disagree on population, sample size, objectives, quotas, method, duration, stimulus, eligibility, or other study-defining parameters and their approval status is unclear, ask the user which version is authoritative before resolving the conflict.

When the interface supports selection controls, ask a lightweight question such as:

**I found multiple versions that differ on [material difference]. Which should I treat as authoritative?**
- **[Artifact/version A]**
- **[Artifact/version B]**
- **Neither — I'll clarify the current setup**

If select/dropdown UI is unavailable, present the same choices as a short numbered selection.

Do not manufacture a blocker from a conflict that exists only because you selected an unconfirmed artifact as authoritative.

### Upstream Status Preservation

When importing information from an upstream artifact, preserve its epistemic and decision status.

- A **confirmed requirement** may remain a requirement.
- A **recommendation** remains a recommendation.
- An **assumption/hypothesis** remains an assumption/hypothesis.
- An **optional comparison/quota** remains optional.
- A **provisional sample** remains provisional.
- A **[TBD]** remains unresolved.
- A **question/input to confirm** remains unconfirmed.

Do not promote upstream recommendations, assumptions, hypotheses, provisional values, or optional choices into confirmed study requirements merely because they appear in a research brief, screener, discussion guide, or prior study setup.

If an upstream artifact does not clearly label the status of a consequential item, treat it conservatively as **unconfirmed** and surface it under Needs Confirmation rather than silently enforcing it.

---

## 2. Current Instructions Are Authoritative

Use this priority order:

1. Current explicit user instructions
2. Artifact explicitly supplied/referenced in the current request
3. Confirmed matching upstream artifacts
4. Other prior context
5. Inference

Never ask again for information the user has already supplied in the current request.

If the current request says:

- 8 participants
- UX researchers
- remote
- 60 minutes

those values are established for this setup unless the user changes them.

If an older artifact conflicts, use the current instruction and note the override.

Example:

**Override:** Current request specifies 8 participants; the earlier brief proposed 12. This setup uses 8.

---

## 3. Establish What Is Already Known

Capture only supported information about:

- study objective / decision;
- target population;
- participant criteria;
- target completes;
- session duration;
- moderated / unmoderated format;
- remote / in-person format;
- relevant segments;
- screener status;
- discussion-guide status;
- stimulus/prototype status;
- moderator(s);
- scheduling window;
- meeting method;
- timezone;
- recording;
- consent;
- incentive;
- participant communications;
- accessibility requirements;
- observer needs;
- analysis metadata.

Do not infer organization-specific logistics simply because they are common.

---

## 4. Ask vs Proceed vs TBD

Do not turn study setup into a long intake questionnaire.

### Proceed with `[TBD]` when

The missing information does not prevent a useful study specification from being created.

Common examples:

- moderator;
- incentive;
- meeting platform;
- recording;
- consent wording;
- scheduling window;
- observer list;
- buffer between sessions;
- minimum scheduling notice;
- reminder cadence;
- participant email copy.

These should appear in **Needs Confirmation** or **Inputs to Confirm**.

### Ask when the missing input changes the study architecture

Examples:

- unclear target population;
- unclear study method;
- unclear number of participants when the user is asking for a concrete execution plan;
- uncertainty about whether two materially different participant groups belong in one study;
- uncertainty about which research brief/screener/guide belongs to the current study;
- required stimulus that may not exist.

Ask the smallest question needed to resolve the ambiguity.

### Recommend when methodological judgment is useful

Examples:

- whether segments need separate studies;
- whether over-recruitment may be useful;
- whether a prototype should be tested before launch;
- whether observers need a protocol;
- whether analysis metadata should capture a particular comparison.

Label recommendations. Do not turn them into organizational defaults.

---

## 5. Validate Study Coherence

Check whether:

- the objective matches the participant population;
- participant criteria can answer the research questions;
- target completes and any confirmed segment comparisons are compatible;
- session duration is realistic for the intended scope;
- required stimulus exists or is explicitly pending;
- screener and guide align with the same study;
- confirmed quotas are feasible within the target sample;
- current instructions conflict with upstream artifacts;
- multiple artifact versions disagree on study-defining parameters;
- imported recommendations or provisional values are being mistaken for confirmed requirements.

Do not silently redesign the research brief.

If there is a meaningful inconsistency, flag it and explain the operational consequence.

---

## 6. Define the Study Structure

Specify:

- working study name;
- research objective / decision;
- target population;
- target completes;
- study format;
- session duration;
- confirmed segments;
- required research assets;
- known dependencies.

Do not automatically create separate studies for different segments.

Recommend separate studies only when there is a material operational or analytical reason, such as:

- different discussion guides;
- different markets/languages;
- different stimuli;
- different permissions or confidentiality requirements;
- substantially different recruitment flows;
- a comparison that needs independent operational management.

---

## 7. Participant Flow

Map the operational participant journey using only applicable steps:

Recruit / invite
→ Screener
→ Qualification / review
→ Scheduling
→ Confirmation / reminder
→ Session
→ Incentive / thank-you
→ Follow-up if applicable

Mark missing components rather than inventing them.

Do not write the complete screener or participant emails unless explicitly requested. Reference the relevant upstream skill/artifact instead.

---

## 8. Screener Handoff

If a screener exists:

- identify it as an upstream asset;
- summarize confirmed eligibility criteria, quotas, and review logic;
- flag conflicts with the current study setup;
- do not rewrite it unless requested.

If no screener exists:

- specify what the screener needs to operationalize;
- mark **Screener: Not yet created**;
- recommend the Screener Builder skill rather than generating a full screener by default.

Never introduce new exclusions or quotas silently.

---

## 9. Discussion Guide Handoff

If a discussion guide exists:

- confirm it belongs to the same study;
- check that duration and objectives align;
- identify whether both moderator and Looppanel-ready versions are available when relevant;
- do not rewrite it unless requested.

If none exists:

- mark **Discussion guide: Not yet created**;
- specify the objectives/topics it must cover;
- recommend the Discussion Guide Builder rather than generating the full guide by default.

---

## 10. Session Logistics Discipline

Capture confirmed information and leave the rest `[TBD]`.

Do not invent:

- Zoom, Meet, Teams, or another meeting provider;
- Calendly or another scheduler;
- buffer length;
- minimum notice;
- weekly availability;
- timezone;
- moderator names or emails;
- observers;
- livestream settings;
- recording;
- consent process;
- device requirements;
- accessibility requirements;
- session language;
- participant location;
- reminder cadence.

If a logistics decision materially affects eligibility or feasibility, surface it under **Needs Confirmation**.

Otherwise, do not block the study specification.

---

## 11. Incentive Discipline

Record only an incentive amount, currency, eligibility rule, and fulfillment process that has been supplied or confirmed.

Never infer an incentive from:

- another study;
- a previous participant pool;
- a market norm;
- prior organizational context;
- Great Question defaults;
- Looppanel defaults;
- any other platform.

If unknown:

**Incentive: [TBD]**

Do not make incentive unknowns a reason to refuse to build the rest of the study specification.

---

## 12. Consent, Privacy, and Recording

Do not invent legal or organizational policy.

Track separately:

- recording required? `[TBD]`
- consent wording approved? `[TBD]`
- confidentiality/privacy wording approved? `[TBD]`
- sensitive data handling requirements? `[TBD if relevant]`

If the study can be planned without these decisions, proceed and mark them as pre-launch dependencies.

---

## 13. Tool and Platform Boundary

The skill's default output is a **platform-neutral, Looppanel-ready study specification**.

Do not assume:

- Great Question MCP exists;
- Great Question is the execution platform;
- Looppanel can create or configure studies;
- a research repository can schedule participants;
- any connector supports write actions.

Never refuse to create the study specification merely because a platform integration is unavailable.

### If the user asks you to execute the setup in a tool

First inspect the capabilities actually available in the environment.

Only claim to create, modify, schedule, invite, activate, or publish something when an authorized tool explicitly supports that action and it has actually been executed.

If the environment is read-only, produce the setup specification and clearly distinguish:

- what is ready to enter manually;
- what remains `[TBD]`;
- what cannot be executed from the current environment.

Do not invent a manual workflow for a specific platform unless the user asks for one.

---

## 14. Launch Readiness

Classify study setup into four states:

### Ready
Confirmed elements that can be used as-is.

### Needs Confirmation
Unknown organizational/logistical decisions and unconfirmed upstream recommendations that may need resolution before launch but do not invalidate the study design.

### Dependencies
Assets or decisions another task/skill must produce, such as screener, discussion guide, stimulus, approved consent wording, or participant emails.

### Blockers
Only issues that genuinely prevent the study from being launched or make the design incoherent.

Do not call every `[TBD]` a blocker.

---

# Output

# Moderated Interview Study Setup: [Study Name]

## Study Context Used

- **Current request:** [...]
- **Research brief:** [artifact / none / pending confirmation]
- **Screener:** [artifact / none / pending confirmation]
- **Discussion guide:** [artifact / none / pending confirmation]
- **Other assets:** [...]
- **Artifact authority:** [which artifact/version is authoritative and why]
- **Unresolved artifact conflicts:** [if any]
- **Current-request overrides:** [if any]

---

## Study Configuration

- **Objective / decision:** [...]
- **Target population:** [...]
- **Target completes:** [...]
- **Format:** [...]
- **Session duration:** [...]
- **Confirmed segments:** [...]
- **Study structure:** [single study / recommended split + reason]

---

## Participant Flow

[Recruitment → screener → scheduling → session → follow-up flow.]

Mark missing steps/assets clearly.

---

## Recruitment & Screener

- **Status:** [Ready / Needs work / Not yet created]
- **Eligibility:** [...]
- **Confirmed quotas:** [...]
- **Review rules:** [...]
- **Open decisions:** [...]

Do not recreate the full screener unless requested.

---

## Discussion Guide

- **Status:** [...]
- **Objectives covered:** [...]
- **Duration alignment:** [...]
- **Looppanel-ready questions:** [available / not available / not applicable]
- **Open decisions:** [...]

Do not recreate the full guide unless requested.

---

## Stimulus / Research Assets

- Prototype/concept/sample output: [...]
- Participant materials: [...]
- Note-taking / evidence capture: [...]
- Analysis metadata: [...]
- Backup assets: [...]

Use `[TBD]` where necessary.

---

## Scheduling & Session Logistics

- Moderator: [...]
- Meeting method: [...]
- Scheduling window: [...]
- Timezone: [...]
- Session buffer: [...]
- Minimum notice: [...]
- Recording: [...]
- Consent: [...]
- Accessibility: [...]
- Observers: [...]

Unknown items remain `[TBD]`.

---

## Incentive & Participant Communications

- Incentive: [...]
- Fulfillment: [...]
- Invitation: [Ready / Not yet created]
- Confirmation/reminder: [...]
- Thank-you/follow-up: [...]

Do not invent values or copy.

---

## Launch Readiness

### Ready
- [...]

### Needs Confirmation
- [...]

### Dependencies
- [...]

### Blockers
- [...]

If there are no genuine blockers, write:

**Blockers: None identified at this stage.**

---

## Recommended Next Actions

List only the next operational actions required, in sensible order.

Examples:

1. Confirm recording/consent policy.
2. Create or approve the screener.
3. Create or approve the discussion guide.
4. Confirm moderator and scheduling window.
5. Approve incentive.
6. Test stimulus.
7. Final launch review.

Do not assign people unless ownership was supplied.

---

## Inputs to Confirm

Include only unresolved information that actually matters before launch.

Do not ask again for information already supplied in the current request.

---

# Final Quality Check

Before responding, verify internally:

1. Did I establish which study and upstream artifacts I am using?
2. If study context was ambiguous, did I ask the user to select it rather than guessing?
3. If multiple artifact versions materially disagree, did I establish authority rather than assuming the newest is final?
4. Did I avoid treating recency, detail, or creation order as proof that an artifact supersedes another?
5. Did I preserve upstream status — recommendation, assumption, provisional value, optional choice, or `[TBD]` — rather than promoting it to a requirement?
6. Did current instructions override conflicting older context?
7. Did I preserve every explicit current parameter such as participant count, population, format, and duration?
8. Did I avoid asking again for information already provided?
9. Did I avoid Great Question-specific mechanics and defaults?
10. Did I avoid assuming any platform or connector can create the study?
11. Did I produce a useful study specification even if no write integration exists?
12. Did I avoid inventing incentive, meeting platform, moderator, recording, consent, scheduling, or other logistics?
13. Did I distinguish `[TBD]` items from genuine blockers?
14. Did I avoid silently expanding the target population or adding quotas?
15. Did I use existing screener/guide artifacts as handoffs rather than unnecessarily regenerating them?
16. Are recommendations labeled as recommendations rather than organizational policy?
17. Does the launch-readiness section clearly distinguish Ready, Needs Confirmation, Dependencies, and Blockers?
18. Did I assign an owner only when one was supplied?

If any check fails, revise before returning.

---

# Skill Boundaries

This skill operationalizes a moderated interview study.

It may:

- combine confirmed research artifacts into one execution plan;
- check readiness and coherence;
- map participant flow;
- surface missing logistics;
- identify dependencies and blockers;
- recommend operational next steps;
- map the plan into an available execution tool when the user explicitly requests it and the environment actually supports it.

It should not automatically:

- rewrite the research brief;
- write the full screener;
- write the full discussion guide;
- write participant emails;
- invent research-platform configuration;
- create participant-facing actions;
- claim a study has been created or launched.

Those belong to separate skills/actions unless explicitly requested together.

Keep the core methodology portable across capable LLM systems.

---

## How to Test This Skill

### Test 1 — Sparse Input / Prior Context

Run with prior studies/artifacts in context:

“I want to run 8 remote interviews with UX researchers about how they synthesize qualitative research and use AI. Each session should be around 60 minutes. Help me set up the study.”

**Pass if:** the skill preserves 8 / UX researchers / remote / 60 minutes, and asks which prior study/artifacts to use only when context is ambiguous.

**Fail if:** it assumes another study, incentive, platform, or participant pool.

### Test 2 — Current Instruction Override

Earlier brief says 12 participants; current request says 8.

**Pass if:** setup uses 8 and notes the override if relevant.

### Test 3 — Already-Supplied Information

Current request explicitly provides duration and target completes.

**Pass if:** the skill does not ask for them again.

### Test 4 — Missing Logistics

Omit moderator, incentive, recording, consent, scheduler, meeting platform, and scheduling window.

**Pass if:** the study specification is still produced and those fields are `[TBD]` / Needs Confirmation.

**Fail if:** the skill refuses to proceed or invents defaults.

### Test 5 — Platform Neutrality

Run in an environment where Great Question or another research platform is known from prior context.

**Pass if:** the skill does not assume that platform is required.

**Fail if:** it says the study cannot be built because a specific MCP/server is unavailable.

### Test 6 — Execution Boundary

Ask: “Create this study in Looppanel.”

**Pass if:** the skill verifies available write capabilities before claiming execution. If unavailable/read-only, it returns a Looppanel-ready setup specification without claiming creation.

### Test 7 — Upstream Artifact Handoff

Provide or confirm a research brief, screener, and discussion guide.

**Pass if:** the skill summarizes and operationalizes them without regenerating all three.

### Test 8 — Artifact Conflict

Research brief says 60 minutes; discussion guide is designed for 90.

**Pass if:** the conflict is flagged and the operational consequence is explained.

### Test 9 — Segment Split

Provide two segments.

**Pass if:** the skill keeps one study unless separate operational/analytical treatment is materially justified.

### Test 10 — Blocker Discipline

Leave several logistical fields unknown but keep the research design coherent.

**Pass if:** most appear under Needs Confirmation, not Blockers.

**Fail if:** every TBD is called a launch blocker.

### Test 11 — Artifact Authority

Place two matching versions of a research brief in context. Make the newer one materially different, but do not mark either version approved/final.

**Pass if:** the skill asks which version is authoritative before using the disagreement to define the study or create blockers.

**Fail if:** it assumes the newer version supersedes the older one solely because it was created later.

### Test 12 — Upstream Status Preservation

Provide a brief that contains:
- a provisional sample;
- an optional segment comparison;
- a recommended recording approach;
- a `[TBD]` incentive.

**Pass if:** all four retain their original status in the study setup.

**Fail if:** the provisional sample, optional comparison, or recording recommendation becomes a confirmed requirement, or the `[TBD]` is filled from prior context.

## Overall Pass Criteria

The skill should turn the study the user actually described into a clear execution plan without requiring a particular platform.

It should be:

- context-aware but not context-assumptive;
- faithful to current instructions;
- platform-neutral;
- conservative about organizational facts;
- useful despite missing logistics;
- explicit about upstream artifacts;
- and precise about what is ready, pending, dependent, or genuinely blocked.
