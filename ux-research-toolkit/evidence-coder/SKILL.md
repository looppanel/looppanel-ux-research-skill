---
name: evidence-coder
description: Apply or develop a consistent qualitative coding taxonomy for research notes, quotes, highlights, and open-text responses. Use for thematic coding, tagging research evidence, taxonomy cleanup, categorizing highlights, or preparing evidence for analysis in Looppanel.
---

# Evidence Coder

Code qualitative research evidence consistently while preserving the distinction between raw evidence, descriptive tags, sentiment, and interpretation.

## Inputs

Accept notes, quotes, highlights, open-ended responses, or an existing taxonomy plus evidence. Preserve source identifiers and exact quote text.

If inputs contain multiple ideas, split them into atomic evidence units when doing so does not distort context.

## Choose the Coding Mode

Use **existing-taxonomy mode** when the user provides tags. Treat those tags as primary and propose additions only when evidence genuinely does not fit.

Use **emergent mode** when no taxonomy exists. Develop candidate tags bottom-up from the evidence.

Use **audit mode** when the user wants an existing tag set cleaned, merged, renamed, or checked for consistency.

## Tagging Rules

- Prefer specific, reusable labels over vague buckets.
- Tag the meaning of the evidence, not every noun mentioned.
- Use the fewest tags needed to represent an item accurately.
- Do not assign sentiment unless the evidence expresses or clearly implies valence.
- Preserve "uncertain" rather than forcing an ambiguous code.
- Keep participant characteristics separate from thematic tags unless the taxonomy explicitly combines them.
- Do not turn a single note into an "insight"; tagging is coding, not synthesis.

When a new tag is proposed, provide a short definition and inclusion/exclusion guidance so future coding stays consistent.

## Looppanel Alignment

Looppanel tags can organize notes by themes, features, needs, or a team's own taxonomy, and AI-suggested tags remain editable by researchers. Design outputs so a researcher can review, rename, merge, remove, or apply tags without losing the evidence behind them.

When summarizing tag frequency, distinguish **note count** from **unique participant/source count**. Never treat note count as participant prevalence.

## Output

# Tagged Research Evidence: [Study/Project]

## Taxonomy

| Tag | Definition | Include when | Exclude when | Evidence count | Unique sources |
|---|---|---|---|---:|---:|
| ... |

## Coded Evidence

### [Evidence ID]
- **Evidence:** [verbatim quote or clearly labeled observation]
- **Source:** [participant/file if available]
- **Tags:** [...]
- **Sentiment:** Positive / Negative / Mixed / Neutral / Not applicable
- **Coding note:** [only if assignment is ambiguous or important]

## Proposed Taxonomy Changes
[New tags, merges, splits, renamed tags, or none.]

## Contradictory / Multi-coded Evidence
[Items that challenge or complicate the taxonomy.]

## Quality Check

Check for:
- synonymous duplicate tags;
- tags so broad they obscure meaningful differences;
- tags so narrow they cannot be reused;
- inconsistent application;
- unsupported sentiment;
- missing source traceability;
- misleading frequency claims.

Do not automatically delete a rare tag or split a frequent tag solely because of its count. Use conceptual usefulness and evidence fit.

## Skill Boundaries

This skill codes evidence. It does not perform full affinity mapping, research synthesis, or create unsupported insights from tag frequency.

Keep the methodology portable across capable LLM systems.
