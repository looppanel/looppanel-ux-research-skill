---
name: research-informed-design
description: Turn user research into design decisions. Use before designing or reviewing any screen, flow, or feature when research exists — interview findings, a research repo, a findings report. Catches the structural mistakes designers make when research sits in a repository instead of in the design.
---

# Research-informed design

Most design failures aren't wrong values. They're wrong shapes — a control at the wrong
level, a warning on the wrong risk, a setting that can't express how people actually work.
Those come from not knowing what users fear, and they survive review because they look
reasonable.

This skill ingests real research and uses it to shape structure, not just defaults.

**Never skip to designing.** If you produce a screen before Step 1 completes, the research
has not entered the design and this skill has failed.

---

## Step 1 — Get the research

Ask the user where the research lives. Offer, in this order:

1. **A connected research tool** (Looppanel, Dovetail, Condens, EnjoyHQ, Marvin, etc.) — if
   an MCP connector is available, use it. Pull insights, tags, tagged evidence and
   transcripts. Transcripts matter most; synthesised insights have already had the fear
   edited out of them.
2. **A document** — findings report, research deck, synthesis doc, Notion page, Drive file.
3. **Raw material** — transcripts, notes, survey open-text, support tickets, sales call
   recordings.
4. **Nothing** — the user has no research for this.

If the answer is 4, say plainly: *"Then everything below is my judgement, not your users'.
I'll mark each decision so you can see which is which."* Continue, but tag every output.
Never pretend an assumption is a finding.

**Read the source before responding.** Don't work from the summary of a summary.

---

## Step 2 — Extract the brief

From whatever you got, write these six things. Show them to the user before designing — this
is the artifact that survives the project.

1. **Who this is for.** Role, seniority, org context. One paragraph.
2. **What they fear, ranked.** In their order, not yours. Fears drive structure; preferences
   drive values. Quote the evidence for each.
3. **The objects in their world.** The nouns they use and how they nest. *(A study lives in
   a repository lives in a workspace. An invoice lives in a client lives in an account.)*
   Get this from how they talk, not from the data model.
4. **Named failure modes.** Specific things that went wrong to real people. "A PM pulled one
   quote and called it research." These are more useful than any preference.
5. **How effort varies.** Do they treat all instances of this object the same, or do they
   right-size? If they right-size, a single global setting is already wrong.
6. **What the research is silent on.** Be explicit. This list is as valuable as the findings
   — it tells you where to flag rather than guess.

---

## Step 3 — Scope before you draw

Ask the user, before generating anything:

- **What object is this screen about?** If the answer is a container (workspace, account,
  org), then nothing that acts on a single item inside it belongs here.
- **Who else sees the output of this screen?** Not who uses it — who it affects. The
  affected party is usually absent from the brief and is usually the one who gets harmed.
- **Which controls here can expose, destroy, or irreversibly change something?** List them
  now, before layout. Ranking after layout never happens.
- **What's already true?** Existing settings, existing shares, existing data. Any default
  you change has a retroactive question attached to it.

Keep it to three or four questions. If the user is absent, answer them yourself and state
your answers at the top of the output.

---

## Step 4 — The nuance checks

Run every one of these. They're the mistakes that survive design review.

### 1. Scope integrity
An action that operates on one object never appears in the settings for a different object.
A container-level screen holds container-level actions only. If a destructive action has no
object in scope on this screen, it doesn't go on this screen.

*Test: name the object each control acts on. Do they all match the screen's object?*

### 2. Rank by consequence, not option count
Control type follows what happens if the setting is wrong — not how many options exist.
Controls that expose data to someone outside the team are the top tier and get weight,
explanation and friction to match. Convenience controls are the bottom tier.

*Test: could a stranger tell, from visual weight alone, which control on this screen is the
dangerous one?*

### 3. The warning goes on the largest harm
Find the most exposing or most destructive option on the screen. That's what carries the
caution, gate or confirmation.

*Test: does any lesser risk carry a warning that the largest risk doesn't? If so the
hierarchy is inverted.*

This one fails constantly, because instinct ranks risk by what *sounds* dangerous rather
than by what the research says actually goes wrong.

### 4. Show, don't describe
Any control that changes what someone outside the team will see needs a preview of what
they'll see. Prose descriptions of a viewer's experience aren't sufficient — "what will they
see and what will they do with it" is a visual question.

*Test: are there three options each explained in a sentence of grey text? Replace with a
preview.*

### 5. Level matching
Does the setting live at the level the behaviour lives at? If people right-size per instance
and the setting is global, the control is at the wrong altitude. The fix is presets or
per-object settings — an architecture change, not a value change.

*Test: can this control express the difference between their most sensitive instance and
their most throwaway one?*

### 6. Destructive actions sit next to recovery
Anything irreversible has its export, backup or undo affordance adjacent, at comparable
weight. Referring to a safety net in helper text without providing it is worse than silence.

*Test: does any copy mention a capability that has no control on this screen?*

### 7. State retroactive scope
When a default changes, say what it applies to. "New items only," or "Applies to 14 existing
items, 3 with live share links." Silent retroactivity on an access setting is undetectable
and unforgivable.

### 8. Copy contradiction sweep
Read every block's header against its body. A header asserting one thing above a line
asserting the opposite isn't nuance — it's two people writing at different times.

### 9. Affordance consistency and semantics
Decisions of the same class use the same control pattern. Radio groups are real radio groups
— `role="radiogroup"`, `aria-checked`, arrow-key navigation — not styled buttons. If one
control on the page implements accessibility correctly, all of them meet that standard.

---

## Step 5 — The absence check

The prompt describes what someone thought to ask for. The research describes what people
need. The gap is where the value is.

Before returning anything, ask:

- **What did the research demand that the prompt never mentioned?** If users fear losing
  data, and there's no export anywhere in the brief, that's a missing control — say so.
- **What does this screen imply exists but doesn't?** Referenced capabilities, mentioned
  concepts, empty nav items.
- **What happens after?** Most briefs describe a screen, not a consequence. Who gets
  notified, what changes for other people, what's now visible that wasn't.
- **What's the second use of this screen?** The first time someone sets it up and the
  fortieth time they come back are different jobs.

Put these in the output as **suggestions, clearly separated** from what was asked for. Don't
silently build things nobody requested — propose them and say which finding drives each.

---

## Step 6 — Output format

Return, in this order:

1. **The design** — screen, flow, component, whatever was asked for.
2. **Grounded decisions** — what you chose *because* of research, with the evidence. Brief.
3. **Judgement calls** — decisions the research didn't cover that you made anyway. This list
   is the point of the whole skill: it's the tacit layer, written down, so the next person
   inherits it instead of re-guessing.
4. **Not asked for, but recommended** — from Step 5, each tied to a finding.
5. **Couldn't know** — where research was silent and the decision matters. Flag, don't fill.

---

## Escalate, don't guess

Stop and ask a human when a decision would:

- expose one person's data to another party
- be irreversible or retroactive
- turn on region, language, legal or regulatory context
- contradict something the research says directly

An acknowledged gap is usable. A confident guess is not.

---

## Self-check before returning

Run this against your own output. Fix anything that fails; don't report it as a caveat.

- [ ] Did I read the actual research, not a summary of it?
- [ ] Is the brief (Step 2) written down and shown?
- [ ] Does every control act on this screen's object?
- [ ] Is the most dangerous control the one that looks most dangerous?
- [ ] Does the largest harm carry the warning?
- [ ] Is anything describing a viewer's experience in prose that should be a preview?
- [ ] Is any setting global that the research says varies per instance?
- [ ] Does every irreversible action have recovery next to it?
- [ ] Does any copy reference a control that doesn't exist?
- [ ] Do headers and bodies agree?
- [ ] Are same-class controls using the same pattern and correct semantics?
- [ ] Have I listed judgement calls separately from grounded decisions?
- [ ] Have I said what I couldn't know?
