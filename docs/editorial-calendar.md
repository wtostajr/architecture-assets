# Architecture Assets — Editorial Calendar

**Version:** 1.0
**Planning horizon:** November 10 – December 18, 2026
**Publishing cadence:** Tuesday and Friday
**Audience:** Software architects, solution architects, enterprise architects, and senior engineers

## Editorial purpose

Architecture Assets explores consequential software architecture decisions through practical questions, explicit trade-offs, and reusable decision models.

The objective is not to prescribe universal patterns, but to help architects understand when, why, and under what conditions a particular architectural choice makes sense.

## Editorial principles

1. One meaningful architectural question per publication.
2. Favor decision frameworks over generic pattern descriptions.
3. Explain trade-offs, constraints, and failure modes.
4. Use industry-neutral principles and diverse practical examples.
5. Include one original, minimalist SVG diagram.
6. Avoid duplicating previously published topics.
7. Preserve technical depth over publication frequency.


## Publication schedule

| Week | Date | Title | Theme | Issue |
|---|---|---|---|---|
| 1 | 2026-11-10 | What Happens When a Cross-Domain Process Fails? | Resilience & Reliability | [#5](https://github.com/wtostajr/architecture-assets/issues/5) |
| 1 | 2026-11-13 | When Is a Retry Actually Safe? | Resilience & Reliability | [#6](https://github.com/wtostajr/architecture-assets/issues/6) |
| 2 | 2026-11-17 | When Is Eventual Consistency Acceptable? | Consistency & Data | [#7](https://github.com/wtostajr/architecture-assets/issues/7) |
| 2 | 2026-11-20 | Who Owns the Truth When Data Is Replicated? | Consistency & Data | [#8](https://github.com/wtostajr/architecture-assets/issues/8) |
| 3 | 2026-11-24 | How Do You Know an Architecture Is Working? | Architecture Quality | [#9](https://github.com/wtostajr/architecture-assets/issues/9) |
| 3 | 2026-11-27 | When Does an Abstraction Become a Liability? | Architecture Quality | [#10](https://github.com/wtostajr/architecture-assets/issues/10) |
| 4 | 2026-12-01 | Where Should Authorization Decisions Live? | Security & Trust | [#11](https://github.com/wtostajr/architecture-assets/issues/11) |
| 4 | 2026-12-04 | What Does Zero Trust Mean Inside an Application? | Security & Trust | [#12](https://github.com/wtostajr/architecture-assets/issues/12) |
| 5 | 2026-12-08 | Can You Observe a Business Outcome Across Services? | Operational Architecture | [#13](https://github.com/wtostajr/architecture-assets/issues/13) |
| 5 | 2026-12-11 | What Happens When a Dependency Becomes Unavailable? | Operational Architecture | [#14](https://github.com/wtostajr/architecture-assets/issues/14) |
| 6 | 2026-12-15 | When Should You Split a System? | Architecture Evolution | [#15](https://github.com/wtostajr/architecture-assets/issues/15) |
| 6 | 2026-12-18 | How Do You Modernize Without a Big-Bang Rewrite? | Architecture Evolution | [#16](https://github.com/wtostajr/architecture-assets/issues/16) |

## Publication workflow

Planned → Drafting → Visual Design → Review → Ready → Published

### Planned
The architectural question, thesis, scope, and target publication date are defined.

### Drafting
The Markdown gist is being written, with examples and a reusable decision framework.

### Visual Design
The companion SVG is created and reviewed for architectural clarity and visual consistency.

### Review
Technical accuracy, editorial quality, diagrams, links, and overlap with existing publications are validated.

### Ready
The content and visual assets are approved for publication.

### Published
The public gist is available, its SVG renders correctly, the repository README is updated, and the tracking issue is closed.

## Definition of Done

- [ ] Architectural question clearly defined
- [ ] Decision framework and trade-offs explained
- [ ] Practical example included
- [ ] Original SVG created and committed
- [ ] Markdown references the correct SVG URL
- [ ] Technical and editorial review completed
- [ ] Gist published
- [ ] Repository README updated
- [ ] GitHub Issue closed

## Editorial management

- Maintain one GitHub Issue per planned publication.
- Use a GitHub Project board for workflow status.
- Keep a rolling six-week planning horizon.
- Aim to maintain two completed publications in reserve.
- Review the schedule every two weeks.
- Reprioritize when necessary without sacrificing quality.

## Existing publications

Before drafting, consult the repository README to avoid repeating published architectural questions.

## Notes

The cross-domain failure and recovery publication already has an approved draft. Its final integration and publication status must be verified before closing the corresponding issue.

Publication dates are editorial targets and may change when additional technical review is necessary.
