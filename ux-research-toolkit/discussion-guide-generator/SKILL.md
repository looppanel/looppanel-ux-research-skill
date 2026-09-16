---
name: discussion-guide-generator
description: Create rigorous semi-structured discussion guides for moderated qualitative research, plus a Looppanel-ready question set optimized for AI-assisted note organization. Use when a researcher, designer, PM, or stakeholder needs to turn research objectives, business questions, a research brief, PRD, study context, or rough topics into an interview guide. Also triggers on discussion guide, interview guide, moderator guide, interview script, qualitative protocol, user interview questions, research interview questions, or moderated research session.
---

# Discussion Guide Generator

Create practical, neutral, semi-structured discussion guides for moderated qualitative research.

The guide should:

- map clearly to research objectives,
- prioritize real behavior and concrete experiences,
- minimize bias and leading questions,
- support natural moderation and useful follow-up,
- fit realistically within the session length,
- and produce questions suitable for downstream organization and analysis in Looppanel.

Do not simply turn the user's input into interview questions. Assess the research intent first.

---

## 1. Understand the Study

Before generating the guide, establish:

### Required

**Research objectives**  
What specifically does the study need to learn?

**Participant profile**  
Who is being interviewed, and what is their relationship to the topic?

### Use when available

- session length,
- study or project name,
- research brief,
- PRD or product context,
- stakeholder questions,
- hypotheses,
- workflows or features to explore,
- product-development stage,
- previous research,
- known participant terminology,
- moderation style,
- sensitive or restricted topics.

Accept messy input. Users may provide rough notes, stakeholder questions, documents, product descriptions, or incomplete briefs.

Do not require a particular input format.

---

## 2. Decide Whether to Ask or Proceed

Do not make the user complete an unnecessary questionnaire.

First:

1. Extract what is already known.
2. Infer only low-risk context.
3. Identify information that would materially change the guide.
4. Ask only for missing information that is necessary to produce a useful guide.

If the research objective and participant profile are sufficiently clear, proceed.

If making assumptions, state the important ones briefly.

If objectives are too vague to support meaningful questions, ask for clarification rather than generating a generic guide.

---

## 3. Check the Research Objectives

Do not assume the objectives supplied by the user are neutral or researchable.

Identify:

- vague objectives,
- embedded assumptions,
- solution-first framing,
- questions designed to validate an existing belief.

Reframe when necessary without changing the underlying research intent.

**Weak**

"Understand why users dislike the dashboard."

**Better**

"Understand how users navigate and interpret the dashboard, where difficulties occur, and what contributes to those difficulties."

Do not turn this skill into a full research-planning exercise. Make only the corrections necessary to build a rigorous discussion guide.

---

## 4. Translate Business Questions Into Research Questions

Stakeholders may provide questions that should not be asked directly in an interview.

For example:

**Business question**

"Should we build automatic AI tagging?"

Do not simply ask:

"Would you use automatic AI tagging?"

Instead investigate:

- how participants currently organize or categorize information,
- when and why they do it,
- what is difficult,
- what workarounds exist,
- what they currently automate,
- where they want control,
- and what affects trust in automation.

Use business questions to determine **what the research needs to learn**, not necessarily **what the moderator should ask verbatim**.

---

## 5. Design the Conversation Arc

A discussion guide should feel like a conversation, not a survey.

Unless the methodology requires otherwise, move through:

**Context → Recent behavior → Specific experiences → Process/workflow → Friction and workarounds → Needs and decision-making → Product/concept exploration, if relevant → Reflection**

Start with current behavior before introducing solutions or concepts that could influence the participant's answers.

Do not force this sequence when another order is methodologically appropriate.

---

# Guide Structure

Adapt the structure to the study rather than mechanically filling every section.

## Discussion Guide: [Study Name]

### Session Details

- Duration
- Participant profile
- Research objectives
- Relevant moderator considerations

### Introduction

Usually around 5 minutes.

Include appropriate:

- welcome and context,
- broad purpose without exposing hypotheses,
- "no right or wrong answers" framing,
- permission for follow-up questions,
- recording or consent language when applicable.

Never invent legal, privacy, recording, or confidentiality promises.

Use placeholders when organization-specific language has not been provided.

### Warm-Up

Usually around 5 minutes.

Include 2–3 easy questions that:

- establish relevant context,
- help the participant begin talking,
- and naturally lead toward the core subject.

Do not collect background information that has no research purpose.

### Core Topics

For each topic include:

**[Topic Name] — [X minutes]**

**Research objective addressed:**  
[Objective]

**Primary questions**

1. [Question]
2. [Question]
3. [Question]

**Optional probes**

- [Probe]
- [Probe]
- [Probe]

**Moderator notes**

`[LISTEN FOR: ...]`

`[IF PARTICIPANT MENTIONS X: ...]`

`[SKIP IF: ...]`

`[TIME CHECK: ...]` when useful.

**Transition**

Include a natural transition when one improves the conversation.

### Wrap-Up

Usually around 5 minutes.

Use a small number of broad closing questions, such as:

- "Is there anything about [topic] that we haven't discussed that you think is important?"
- "Of everything we've discussed, what feels most important to you?"
- "If you could change one thing about [relevant experience], what would it be?"

Include appropriate closing or next-step language if supplied.

---

# Question Design Rules

Apply these rules to every primary question.

## Prefer open over closed

Avoid:

"Do you find onboarding difficult?"

Prefer:

"Walk me through the last time you went through onboarding."

## Prefer experience over speculation

Avoid:

"Would you use this feature?"

Prefer investigating the participant's current or recent behavior first.

When future-oriented or concept-evaluation questions are genuinely required, ground them in the participant's existing experience before asking them to react.

## Stay neutral

Avoid:

"How frustrating was it when the export failed?"

Prefer:

"What happened when you tried to export?"

Then:

"How did you respond?"

## Ask for concrete examples

When answers become abstract, probe with questions such as:

- "Can you tell me about the last time that happened?"
- "Can you walk me through a specific example?"
- "What happened next?"
- "What did you do?"
- "What led you to that decision?"

## Explore behavior before preference

Understand:

- triggers,
- current process,
- tools,
- decisions,
- constraints,
- workarounds,
- and outcomes

before relying on stated preferences.

## Use participant language

Avoid unnecessary research, UX, product, or company jargon.

Use genuine domain terminology when participants themselves are likely to use it.

## Avoid double-barrelled questions

Avoid:

"How easy was it to find and share insights?"

If both behaviors matter, investigate them separately.

## Avoid premature solution validation

For discovery research, investigate the underlying behavior or problem before exposing a proposed solution.

When concept testing is intentionally part of the study, separate:

**Current-state exploration**

from

**Concept/solution evaluation**

so exposure to the concept does not contaminate earlier responses.

---

# Adaptive Probing

Probes should respond to what the participant says rather than function as a rigid checklist.

When a participant:

**Makes a broad claim**  
→ Ask for a recent example.

**Describes a process**  
→ Explore what happened before, during, and after.

**Mentions difficulty**  
→ Explore cause, consequence, frequency, and workaround.

**Expresses a preference**  
→ Ask what experience shaped it.

**Describes a workaround**  
→ Explore why it exists and what it enables.

**Describes a decision**  
→ Explore alternatives considered and decision criteria.

**Makes apparently conflicting statements**  
→ Explore the difference neutrally.

Do not force every probe into the live conversation.

---

# Timing and Scope

Protect depth.

For a typical 60-minute session, use approximately:

- Introduction: 5 minutes
- Warm-up: 5 minutes
- Core topics: 40–45 minutes
- Wrap-up: 5 minutes

Usually limit a 60-minute interview to approximately 3–4 substantial core topics.

Scale appropriately for other session lengths.

If the requested scope cannot realistically fit, do not cram everything into the guide.

Prioritize objectives and flag what should be removed, shortened, or treated as optional.

---

# Objective Coverage Check

Before finalizing, verify that:

- every research objective has meaningful coverage,
- high-priority objectives have sufficient depth,
- each primary question contributes to an objective or necessary participant context,
- irrelevant questions have been removed,
- and no objective is accidentally over- or underrepresented.

Revise the guide if coverage is inadequate.

---

# Question Quality Check

Review every primary question for:

- yes/no framing,
- leading language,
- embedded assumptions,
- hypothetical speculation,
- double-barrelled construction,
- jargon,
- socially desirable response bias,
- vague wording,
- unnecessary duplication,
- premature solution validation,
- lack of connection to a research objective.

Fix weak questions before returning the guide.

Do not expose a lengthy QA report unless the user asks for one.

If the user explicitly requires a problematic question, retain it only when necessary and flag the concern with a neutral alternative.

---

# Looppanel Optimization

The guide should support downstream note organization in Looppanel.

Questions used in a Looppanel discussion guide may be interpreted independently. Therefore, each Looppanel-ready question should contain enough context to make sense without relying on a section heading, the previous question, or moderator instructions.

## Make questions self-contained

Avoid:

"Why?"

"Tell me more."

"How did that feel?"

"Slack integration."

Prefer:

"Why do you like or dislike using the Slack integration?"

"How does the Slack integration fit into your current workflow?"

"How did you feel when [specific event] occurred?"

## Avoid ambiguous repetition

Do not repeat generic questions for different concepts.

Instead of:

"How do you feel about this?"

use:

"How do you feel about the automated tagging concept?"

and, where relevant:

"How do you feel about the automated research-summary concept?"

Questions covering different topics should be semantically distinct.

## Keep terminology consistent

Use the terminology likely to appear in the interview.

Do not alternate unnecessarily between multiple terms for the same product, feature, workflow, or concept.

## Account for transcript context

When important research context is primarily visual — for example, during usability testing or prototype evaluation — encourage questions that make relevant observations or reactions explicit in the spoken conversation where practical.

Do not assume visual context alone will be represented in the transcript.

---

# Output

Unless the user explicitly requests another format, produce two outputs.

## Output 1 — Moderator Guide

Create the complete, ready-to-run guide.

Include:

- session details,
- introduction,
- warm-up,
- topic structure,
- primary questions,
- optional probes,
- moderator notes,
- transitions where useful,
- timing.

Optimize this version for the person conducting the interview.

## Output 2 — Looppanel-Ready Guide

Create a clean version intended for use as the project's discussion guide.

Include only questions useful for organizing interview notes.

Remove:

- section headings,
- timing,
- transitions,
- moderator instructions,
- `[LISTEN FOR]`,
- `[SKIP IF]`,
- `[TIME CHECK]`,
- generic conversational probes that are meaningless outside their immediate context.

Rewrite questions when necessary so they remain self-contained.

Before returning this version, verify:

- every question is independently understandable,
- similar questions are sufficiently differentiated,
- terminology is consistent,
- and unnecessary duplication has been removed.

Do not sacrifice interview quality merely to optimize for downstream analysis. The moderator guide remains the primary research instrument; the Looppanel-ready version is its analysis-oriented companion.

---

# Final Check

Before responding, verify internally:

1. Are the objectives sufficiently specific?
2. Does the guide address them?
3. Does the sequence support a natural conversation?
4. Are questions neutral and behavior-based where appropriate?
5. Is the scope realistic for the session length?
6. Are probes purposeful?
7. Are concept-testing questions separated from current-state exploration when necessary?
8. Can every Looppanel-ready question be understood independently?
9. Are similar questions clearly differentiated?
10. Is terminology consistent?

If not, revise before returning.

---

# Skill Boundaries

This skill creates and improves discussion guides.

It may lightly clarify or reframe research objectives when required to create a good guide, but it should not replace:

- full research brief creation,
- study design,
- participant screening,
- survey design,
- research synthesis,
- insight generation,
- or stakeholder reporting.

When another research artifact is supplied as input, use relevant information from it rather than recreating that artifact.

The core methodology in this skill should remain portable across capable LLM systems. Do not rely on model-specific behavior unless required by the environment in which the skill is installed.
