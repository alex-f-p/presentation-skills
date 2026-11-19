# Presentation skills

Four independently usable presentation skills and an optional, explicitly invoked grilling companion.

| Skill | Use it to |
| --- | --- |
| [Grill a presentation](grill-presentation/SKILL.md) | Challenge consequential choices through an interview and produce a brief; call on related skills when a bounded task would help. |
| [Brief a presentation](brief-presentation/SKILL.md) | Define the audience, intended outcome, conditions of use and scope. |
| [Develop a presentation](develop-presentation/SKILL.md) | Build or revise the argument, evidence, sequence and storyboard, including the roles of slides, speech and supporting material. |
| [Design presentation slides](design-presentation-slides/SKILL.md) | Choose visual representations and create or repair slides in the requested format. |
| [Review and rehearse a presentation](review-and-rehearse-presentation/SKILL.md) | Review content, rendered slides or delivery evidence; report findings and make requested repairs. |

Choose the entry point that matches the work. There is no compulsory sequence: an existing deck can go directly to review or design, and a request for a brief does not require producing slides. Each skill can use the context and artifacts already available.

## Installation and use

Follow your host application's instructions for installing skills. Install the **whole selected skill folder**, including its references, metadata and any attribution or license files; copying only `SKILL.md` omits supporting material. You can install any combination. No skill requires another to be installed.

Ask for the relevant presentation task or explicitly select the skill using your host's supported invocation method. Supply the intended audience, outcome, delivery format and available source material when known. Existing decks, notes and templates can be used as starting points.

Invoke `grill-presentation` explicitly: `$grill-presentation` in Codex or `/grill-presentation` in Claude Code. Its Codex policy and Claude Code frontmatter disable implicit invocation. Other hosts must support an equivalent invocation setting; strict standard-only uploaders may reject the Claude Code extension. The skill's interview instructions also require an explicit request. Ordinary presentation work uses the other four skills without a compulsory interview.

The grilling method is adapted from Matt Pocock’s skills, with [attribution](grill-presentation/ATTRIBUTION.md) and his [MIT notice](grill-presentation/LICENSE) included in that package.

## Working files and handoffs

For saved presentation projects, reuse the chosen working document or use `presentation.md` beside the presentation files. A small project can use this layout:

```text
presentation-project/
  presentation.md
  [editable deck and requested exports]
  sources/                    # only when local supporting files need it
```

A hosted deck can stay in its service; link to it from the working document. Add only the sections the requested work needs:

| Section | Contents | Example |
| --- | --- | --- |
| Brief | Audience, outcome, success criterion, use/time, scope, constraints and consequential assumptions. | [Brief](brief-presentation/references/output-example.md) |
| Content | Outline or storyboard, with purpose, evidence, qualifications and visible/spoken/supporting contributions at the requested depth. | [Content](develop-presentation/references/output-example.md) |
| Outputs | Links to the actual deck, notes and exports; the version checked, checks performed and remaining limits. | [Outputs](design-presentation-slides/references/output-example.md) |
| Review | Located findings, proposed or completed fixes and recheck results; rehearsal observations when available. | [Review](review-and-rehearse-presentation/references/output-example.md) |

Each skill reads relevant earlier sections and updates the existing record. Keep sources and qualifications beside claims; use a separate evidence table only when helpful. Leave a short continuation note explaining what remains within the request and what a consequential change affects. A check applies to the identified artifact revision or snapshot, not automatically to later edits.

Adapt the headings to existing material. Chat-only requests stay in chat, and small advice or repair requests need not create a record. Split a long section into a linked file only when useful, replacing the original section with its link so there is one maintained copy. The examples illustrate output structure; their fictional files and checks are not actual deliverables.

## Capabilities and conventions

The skills provide communication and review guidance. They use authoring, rendering and inspection tools available in the host environment; they do not bundle a slide-production application. Native editing, export, recording inspection and accessibility checks depend on those tools. Unsupported capabilities should be reported. Slide artifacts that require rendered verification remain unverified drafts until rendered and inspected; text-only briefs and advice do not require rendering.

Each skill bundles the same editorial rules for wording and visual choices. Agents follow them unless the user explicitly asks otherwise or requires a template that differs. Evidence integrity, accessibility and honest reporting of completed checks are never traded away.

Some reference files are intentionally copied into several skill folders so each package remains self-contained when installed independently. Keep corresponding copies consistent when changing a shared convention.

Maintainers can use the [evaluation protocol](EVALUATION.md) to compare skill revisions. It is separate from normal presentation work.

## Licence

Each skill folder includes the applicable notices for the [MIT License](LICENSE).

---

Shared by [Signal Eight](https://www.signaleight.ai/).
