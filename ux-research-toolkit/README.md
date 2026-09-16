# UX Research Toolkit

10 Claude skills that take a research project from a business question to a stakeholder shareout.

Every skill is opinionated about research methodology and conservative about facts. None of them invent participants, quotas, timelines, or organizational context you didn't give them — missing inputs come back as `[TBD]` or a question, not a confident guess.

## What's Inside

### Plan and design the study

These turn a request, a decision, or a rough set of topics into a study you can actually run.

| Skill | What It Does |
|-------|-------------|
| **study-brief-builder** | Turns a business question or product decision into a research brief — objectives, method recommendation, participant strategy, scope, risks, and what success looks like |
| **discussion-guide-generator** | Builds semi-structured moderator guides for qualitative sessions, plus a Looppanel-ready question set optimized for AI-assisted note organization |
| **participant-screener-builder** | Writes recruitment screeners with neutral questions, qualification logic, useful variation, and justified quotas — designed to be hard to game |
| **survey-builder** | Designs research-quality surveys for feature validation, concept testing, NPS/CSAT, or post-interview follow-up, with rationale behind every question |
| **unmoderated-study-generator** | Designs platform-agnostic unmoderated studies — prototype tests, website tasks, concept evaluation, first-click, tree tests, card sorts, comprehension tests |
| **interview-study-setup** | Converts an approved brief into an execution-ready moderated study spec — participants, recruitment handoffs, session logistics, consent, incentives, scheduling, launch readiness |

### Analyze and communicate

These process the evidence you come back with.

| Skill | What It Does |
|-------|-------------|
| **evidence-coder** | Applies or develops a qualitative coding taxonomy across notes, quotes, and open-text responses, keeping raw evidence separate from interpretation |
| **affinity-map-builder** | Clusters evidence bottom-up into groups and higher-order themes while preserving source traceability, contradictions, and outliers |
| **findings-builder** | Synthesizes evidence into defensible findings with calibrated confidence, participant breadth, tensions, and unanswered questions |
| **stakeholder-shareout** | Reframes approved findings for leadership, PMs, designers, engineering, or GTM without letting compression inflate certainty |

No account, integration, or MCP connection is required. Every skill works on files and context you provide.

## How to Install

### Claude Desktop
1. Open **Settings → Capabilities → Skills**
2. Upload the `SKILL.md` file from any skill folder
3. Done — Claude will use the skill automatically when relevant

### Claude Code
1. Copy the skill folder into your project's `.claude/skills/` directory
2. Claude reads it automatically when handling related tasks

### Cowork
1. Drop the skill folder into your skills directory
2. Available immediately

## Recommended Workflow

These chain together across a full research project.

**Frame the work:** study-brief-builder → decide the method

**Build the instruments:** discussion-guide-generator (moderated) *or* unmoderated-study-generator *or* survey-builder → participant-screener-builder

**Set up fielding:** interview-study-setup

**Analyze:** evidence-coder → affinity-map-builder → findings-builder

**Communicate:** stakeholder-shareout

You don't need all 10 on every project. Start with the one that targets your biggest bottleneck — for most teams that's synthesis, so try findings-builder first.

## How They Handle Each Other's Output

The analysis skills are deliberately layered so certainty doesn't creep upward as work moves between them:

- **evidence-coder** tags evidence. It does not decide what the evidence means.
- **affinity-map-builder** organizes evidence into clusters. A cluster is not a finding.
- **findings-builder** is the analytical source of truth. It produces findings, implications, and confidence levels.
- **stakeholder-shareout** is a communication layer. It reframes approved findings and never re-synthesizes them.

Several skills also check which upstream artifact they're working from before they start, rather than assuming the most recent file in context belongs to the current request.

## Working With Looppanel

Two skills produce output shaped for Looppanel specifically:

- **discussion-guide-generator** emits a second, Looppanel-ready version of the guide where each question stands alone, so AI-organized notes stay readable without section context.
- **evidence-coder** aligns its taxonomy output to Looppanel's tag model, so a researcher can review, rename, merge, or remove tags without losing the evidence behind them.

The rest are platform-neutral by design and will not refuse to work because a research platform isn't connected.

## Customization

Every skill is a single markdown file. Open it, edit the instructions, save.

If your team has its own templates, taxonomies, confidence language, or methodology standards, adapt the skills to match — the output format blocks near the end of each `SKILL.md` are the fastest place to start.

## Built by Looppanel

Looppanel is a UX research platform for recording, transcribing, and analyzing user interviews. These skills extend that work into your broader AI workflow, including data from sources outside Looppanel.

Learn more at [looppanel.com](https://www.looppanel.com)
