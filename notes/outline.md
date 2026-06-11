# Codex Meetup JKT Jun 2026 - Speaker Outline

Deck: `Using Codex in Daily Work`

Speaker: Naufaldi Rafif S, Codex Ambassador Indonesia

Format: live browser-based HTML presentation, professional tech meetup style.

Workflow rhythm:

- Before Codex context slide
- Before Codex proof/image slide
- After Codex context slide
- After Codex proof/image slide

This creates more room for wording and makes screenshots/videos readable during the showcase.

## Talk Flow

1. Opening
   - Introduce Codex as a daily work agent.
   - Set expectation: this is not only about code generation.

2. Mental model
   - Before Codex: manual context switching.
   - After Codex: context, tools, automation, verification.

3. Coding / Software Engineer
   - Planning before Codex: PRD, KPI, backlog, and codebase reality are discussed manually.
   - Planning after Codex: automation prepares codebase and business improvement ideas before planning.
   - PRD/RFC before Codex: manual reading and writing.
   - PRD/RFC after Codex: Codex drafts RFC from PRD, templates, and codebase context.
   - Task breakdown before Codex: manual issue creation and inconsistent DoD.
   - Task breakdown after Codex: Codex creates structured tasks with labels and acceptance criteria.
   - Daily work before Codex: standup depends on memory.
   - Daily work after Codex: Codex summarizes yesterday and suggests useful next work.
   - Guardrails before Codex: vague prompt creates risky work.
   - Guardrails after Codex: prompt includes RFC, task, route, test, and browser verification.
   - Implementation before Codex: manual file hunting.
   - Implementation after Codex: Codex traces codebase and edits in scope.
   - Debugging before Codex: patch-by-error.
   - Debugging after Codex: root-cause tracing across frontend, backend, data flow, and runtime.
   - Testing before Codex: late or broad testing.
   - Testing after Codex: focused verification with evidence.
   - MR/review/deploy before Codex: manual context writing.
   - MR/review/deploy after Codex: Codex prepares review-ready summary, CI check, and risk notes.
   - Sprint review/retro before Codex: depends on memory.
   - Sprint review/retro after Codex: Codex turns work history into demos, themes, and learning.

4. Non-coding workflows
   - Codex outside coding: projects, skills, plugins, screenshots, and automation.
   - Content creation before Codex: manual idea search.
   - Content creation after Codex: 24h idea automation.
   - Draft refinement before Codex: raw ideas are hard to judge.
   - Draft refinement after Codex: screenshot or rough idea becomes clearer draft.
   - Social engagement before Codex: fast replies can blunder.
   - Social engagement after Codex: dedicated project with tone and risk guardrails.
   - Marketing before Codex: inspiration is scattered.
   - Marketing after Codex: Codex turns references into campaign angles.
   - Asset creation before Codex: blank canvas or stock hunting.
   - Asset creation after Codex: image generation plus Canva editing.
   - Slide creation before Codex: blank deck.
   - Slide creation after Codex: rough notes become deck outline and speaker notes.
   - Meeting/report before Codex: manual context collection.
   - Meeting/report after Codex: meeting brief, weekly report, blockers, metrics, and follow-up.
   - Research/learning before Codex: many tabs and scattered notes.
   - Research/learning after Codex: learning note, comparison, and next action.
   - Computer Use before Codex: manual clicking.
   - Computer Use after Codex: Codex operates and verifies workflows.

5. Closing
   - Codex is strongest when the workflow has context, tools, guardrails, and proof.
   - Final line: Codex helps turn repeated work into a system.

## Asset Checklist

Add final screenshots or videos into these folders:

- `assets/coding/`
- `assets/non-coding/`
- `assets/videos/`

Suggested filenames are already shown as placeholders inside each slide, for example:

- `planning-automation-ideas.png`
- `guardrail-complete-prompt.png`
- `content-idea-automation.png`
- `social-project-guardrails.png`
- `asset-imagegen-canva.png`
- `computer-use-codex.png`

The plugin screenshot is already copied to:

- `assets/non-coding/codex-plugins.png`

## Prompt Style For Demo Screenshots

Use prompts that show guardrails clearly:

```text
Use the RFC and GitLab task as the source of truth.
Inspect the current implementation before editing.
Keep the change scoped to this feature.
Verify with focused tests and browser behavior.
Return what changed, why it is safe, and exact evidence.
```
