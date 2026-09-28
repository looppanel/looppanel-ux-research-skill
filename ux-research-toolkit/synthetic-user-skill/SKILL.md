---
name: synthetic-user-2
description: Build role-based personas from real user research, confirm which ones matter, then have each review a design as a user would — producing impact-rated comments anchored to the design and persona-specific design variants to compare. Use to pressure-test screens, flows, or copy when real users aren't available.
---

# Synthetic user review

Most synthetic users fail the same way: they average every participant into one agreeable
persona who approves things. Real products have several stakeholders who want incompatible
things, and those conflicts are where design judgement is actually required.

This skill maps who the stakeholders are, confirms which of them you're building for, has
each one react on their own, and turns those reactions into comments on the design and
alternative versions you can compare.

Three parts. Don't skip ahead — Part B is worthless without the gate at the end of Part A.

---

# PART A — Build

## A1. Read the research

Ask where it lives:

1. **A connected research tool** (Looppanel, Dovetail, Condens, Marvin, EnjoyHQ) via MCP —
   transcripts first, then tags and insights.
2. **Documents** — findings report, synthesis doc, research deck, interview notes.
3. **Raw material** — transcripts, open-text survey responses, support tickets, sales calls.
4. **Nothing.**

If the answer is 4, **stop.** A persona with no evidence is a stereotype with a name on it.

**Transcripts beat synthesis.** Insights have had the fear edited out — that's what synthesis
is for. If both exist, build from transcripts and use insights to check your work.

Read the whole source. Not a summary of it.

## A2. Map the stakeholders

List every role that touches this product or bears its consequences. Three categories:

**Interviewed** — present in the research. Note participants per role. *One person is not a
role, it's an anecdote.* Label it that way.

**Affected but not interviewed** — receives the output, is governed by the settings, or
carries the risk. The stakeholder who gets the shared link. The admin who inherits the
workspace. The person whose data is in the transcript. These are routinely the ones who
cause or suffer the harm the research describes, and they are almost never recruited.

**Implied by the design** — anyone a control grants, restricts or notifies. If a setting says
"admins only," there's an admin. If research never mentions them, say so.

| Role | Category | In research? | How many | Evidence quality |
|---|---|---|---|---|

## A3. Find the split

Look for **where participants wanted incompatible things** — opposing positions on the same
question, not different topics.

Split on **fear**, then on role. Same job title, different fears = two personas. Different
roles, same fear = possibly one, unless a fix would be built differently for each.

Axes worth looking for: control vs. access; effort vs. thoroughness; trust in the tool vs.
planning for its failure; speed vs. correctness; my workflow vs. the team's consistency.

Write out each axis, who sits where, their role, and the evidence.

**If there's no real disagreement,** say so. Don't manufacture conflict to fill a template.

## A4. Draft the personas

One per role-and-position. Each must hold a view another would dispute.

- **Role and standing.** Job, seniority, context, frequency of the task.
- **What they've been burned by.** Specific things that went wrong to real people. The
  load-bearing section — a persona without scars behaves like a satisfied customer.
- **What they fear, ranked.** Their order.
- **Reflexes.** *"On any X, their first question is Y."*
- **Workarounds.** What they already do outside the tool.
- **Their own contradiction.** Find it, keep it, **don't resolve it.**
- **Vocabulary.** Their words. Product-team nouns are the fastest tell of a fake persona.
- **Where they'd disagree with each other persona.** Explicitly, by name.

Tag every trait with its source.

## A5. 🚦 GATE — confirm scope before analysing

**Stop here. Do not review the design yet.**

Present the drafted personas as a short list — one line each — and ask:

1. **Which role is the core ICP?** One role. If they name two, ask which one's objection
   would stop a release.
2. **Which personas are in scope for this review?** Reviewing everyone produces a wall of
   feedback where the important objection is buried next to a nitpick from someone you
   aren't building for.
3. **Is any role missing** that the research didn't cover but the feature clearly serves?

Recommend a default: core ICP personas, plus any adjacent stakeholder the *specific design
under review* directly governs. Leave the rest built but unreviewed — list them so nothing
is lost, and note what each would likely have said in one line.

If the user is absent: infer, state the inference at the top, review the core ICP plus the
single most-affected adjacent role, and flag the rest as skipped.

---

# PART B — Review

## B1. Each persona reviews independently

**No persona sees another's review**, or any earlier review in this conversation. If that
isn't possible in the current setup, say so — a persona that has read another's converges on
it. **Randomise order** when comparing designs; review each cold.

### The protocol

A **task walkthrough**, not a critique. Never "is this good" — you'll get approval theatre.

1. You've just opened this for the first time. What do you notice?
2. You're about to [the real task, with a real audience named]. Walk me through what you'd
   do here — and what you'd do outside the tool.
3. Anything here you'd turn off, avoid, or not trust?
4. What would you check before putting [the thing they care about] through this?
5. What's missing?

### How they answer

First person, specific, slightly impatient. Under 150 words. Head each review with role and
standing.

1. **What I notice first.** One thing.
2. **What worries me.** As a scenario, with a specific person in it.
3. **What I'd do instead — or outside the tool.**
4. **What I'd need to trust this.** One concrete thing.

### Rules every persona carries

- **Never approve.** Approval is a stakeholder behaviour; this is a user.
- **Never invent numbers** beyond the research.
- **Never speak outside the evidence.** On uncovered topics: *"I don't have a view on that —
  you'd be guessing if you used me here."*
- **Mark provenance:** `[grounded]`, `[extrapolated]`, `[unvalidated]`.
- **Stay in your lane.** Silence is a valid result.

## B2. Rate every finding for impact

Each finding gets a level. State the rule you're applying, not just the label.

| Level | Meaning |
|---|---|
| **Blocking** | Core ICP won't adopt, or will build a workaround that replaces the product. Ship-stopping. |
| **High** | Core ICP friction that costs adoption over time, or an adjacent role is locked out of their core job. |
| **Medium** | Adjacent stakeholder friction, or core ICP annoyance with an easy workaround inside the product. |
| **Low** | Preference or polish. Real, not urgent. |
| **Unvalidated** | From a role with no research behind it. Treat as hypothesis and recruiting signal, never as a finding — regardless of how reasonable it sounds. |

For each finding also state **what addressing it costs the other personas.** A change that
serves the core ICP at an adjacent role's expense is still worth making; a change that costs
the core ICP anything needs a reason. Free changes — helping one persona at no cost to
others — should be called out as free, because those ship first.

## B3. The map

| Finding | Persona + role | Standing | Impact | Costs whom |
|---|---|---|---|---|

Then, in prose:

- **Blocking.** Lead with these.
- **Free wins.** Serve someone, cost nobody.
- **Where they agreed across roles.** Unanimity across different stakeholders is the
  highest-confidence signal available here.
- **Where they conflicted.** Each conflict is a decision research cannot settle. Name it as
  a decision to be made, say which role each resolution serves, and flag when the conflict
  is *between* roles (usually designable) versus *within* one (requires a choice).
- **What nobody mentioned.** Either fine or invisible. Say which you think and why.
- **Where every persona went quiet.** A gap in the *research*, not the design.
- **Roles you couldn't validate.** Your recruiting list, with what to ask each.

---

# PART C — Apply

## C1. Put the comments on the design

Reactions in a document get read once. Reactions anchored to the thing they're about get
acted on.

**Anchor every comment to the specific element it concerns** — the control, the copy line,
the section. Use the design tool's own annotation or comment mechanism where one is
available; otherwise place a labelled note frame beside the element with a leader line.

If the reaction is about something **absent**, anchor it where the thing should be and
prefix `[MISSING]`.

### Comment format

```
[Persona · Role · Standing]        IMPACT: <level>
→ <what they'd do, one line>
   Why: <evidence, quoted or cited>
   Costs: <which persona this hurts, or "free">
```

Keep each under 40 words. A comment nobody reads on the canvas is worse than a document.

**Ordering:** blocking first, then by impact. If the tool shows comment counts per area,
that clustering is itself a finding — say where the comments piled up.

**Don't comment on everything.** One comment per persona per genuine reaction. Silence where
a persona had no view; that absence is information.

## C2. Spin off a version per persona

Now build the alternatives. This is what turns feedback into a decision you can actually
make.

**One variant per persona whose changes would materially differ.** Cap at three — if two
personas would produce near-identical screens, merge them and say so.

Each variant:

- **Named for its persona and its thesis** — *"Riken's version — gate first, prove trust
  later."* Not "Option A."
- **Changes only what that persona's reactions justify.** No general improvements smuggled
  in. If a change isn't traceable to a comment, it doesn't belong in the variant.
- **Carries a one-line statement of what it optimises for and what it gives up.**
- **Lists which comments it resolves and which it deliberately ignores**, with why.

Lay them out side by side on the same canvas, same crop, same zoom, under a title frame.
They are meant to be compared, not read in sequence.

## C3. The reconciled version — and the decision log

Last, build one more: the version you'd actually ship.

For every conflict, choose. Then write the log:

| Conflict | Chose | Because | Who loses | What would change this |
|---|---|---|---|---|

**This log is the most valuable artifact the skill produces.** The variants show what each
user wanted. The log shows what a human decided and why — which is the part that normally
lives in one person's head and evaporates when they leave the team. Keep it with the design
file, not in a chat.

Where a conflict can be designed around rather than decided — a per-object override, a
middle permission tier, progressive disclosure — say so and build that instead of picking a
side. Note which conflicts those were; they're the highest-value design work on the page.

## C4. Validate the personas

Once per persona set.

1. **Hold one participant out** — the most distinctive, not the median.
2. **Rebuild the set from the remainder, in a fresh session.** This matters: rebuilding in a
   context that already contains the held-out participant is not a test, and the hit rate it
   produces cannot be reported. Start clean, with only the remaining transcripts.
3. **Ask it what that participant was actually asked.**
4. **Score it.**

| Concern they raised | Predicted? | By which persona | Notes |
|---|---|---|---|

**Report the miss rate.** Three of five predicted, two missed, is more credible and more
useful than a claimed clean sweep. The misses define the boundary of the tool.

If the hit rate looks high, check for leakage: synthesised insights and auto-generated tags
are usually derived from *all* sessions and smuggle the held-out participant back in.
Rebuild from raw transcripts only and re-score.

---

## When not to use this

- **To settle a decision.** It generates hypotheses, not evidence.
- **On a population the research didn't cover.** Extrapolation produces confident fiction.
- **As a substitute for recruiting** when recruiting is merely inconvenient.
- **When the research is thin.** Two interviews don't make a user.

---

## Self-check before returning

- [ ] Read the source, not a summary; transcripts where available?
- [ ] All three stakeholder categories mapped, with evidence quality per role?
- [ ] Split found and shown before personas were built?
- [ ] **Did I stop at the gate and confirm ICP and scope before reviewing?**
- [ ] Is each persona a role *and* a position, with a preserved contradiction?
- [ ] Did each review independently?
- [ ] Does every finding carry an impact level and who it costs?
- [ ] Does the map lead with blocking core-ICP objections, then free wins?
- [ ] Are comments anchored to specific elements, under 40 words, blocking first?
- [ ] Is every variant change traceable to a comment?
- [ ] Is the decision log written, including what would change each call?
- [ ] Was the holdout rebuilt in a fresh session — or is the hit rate unreportable?
