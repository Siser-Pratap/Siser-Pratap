# GitHub profile README: research and phased plan

Researched: 25 October 2026. Account: [Siser-Pratap](https://github.com/Siser-Pratap).

Execution update: the user authorized the remaining phases with automatic approval. The evidence inventory, resume integration, content draft, visual design, and pre-publication checks are complete. This version publishes the reviewed README and banner together. Account-setting suggestions are recorded separately in docs/MAINTENANCE.md.

See [evidence](docs/EVIDENCE.md), [verification](docs/VERIFICATION.md), and [maintenance](docs/MAINTENANCE.md) for the completed work. The plan below preserves the original research and intended sequence.

## Purpose and audience

Build a complete, evidence-based introduction to Siser's skills, projects, experience, contributions, and ways to connect. The confirmed audiences are recruiters and engineering hiring managers, and open-source maintainers and developer peers.

Use a concise main page with expandable supporting details. Give visitors a quick understanding of what Siser builds, then direct them to code, demonstrations, and contributions that support those claims. This is a proposed editorial approach, not a GitHub requirement.

## Phase 1 — research and setup: complete

- Cloned [Siser-Pratap/Siser-Pratap](https://github.com/Siser-Pratap/Siser-Pratap) into this local workspace.
- Baseline at cloning: `main`, commit `dde476c` (`Update README.md`).
- Read the existing profile README and sampled public project READMEs.
- Checked GitHub's official documentation for profile requirements, formatting, pins, and contribution visibility.
- Verified one merged contribution to another maintainer's project.
- Recorded this plan locally. The public profile README has not been rewritten or published as part of this phase.

## GitHub requirements and platform constraints

The profile repository must match the username, be public, and have a nonempty `README.md` at its root. The existing repository meets these conditions. Managed user accounts cannot use profile READMEs. [Official requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)

Use GitHub Flavored Markdown and supported HTML. Tables, collapsible `<details>` sections, and images with light/dark variants are available. Include meaningful image descriptions. [GitHub formatting guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

GitHub sanitizes rendered HTML, including removing scripts, inline styles, and class attributes. A README layout must work within that rendering pipeline. [GitHub's markup pipeline](https://github.com/github/markup)

GitHub truncates README content beyond 500 KiB. Prefer relative paths for assets maintained in this repository. [README documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

Profile pins are configured separately from the README, with a maximum of six repositories and gists combined. [Pinning documentation](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)

The native profile already includes a contribution graph and activity timeline. Private contribution counts can be shown with identifying details anonymized; this does not expose private source code. [Contribution visibility](https://docs.github.com/en/account-and-profile/concepts/contributions-on-your-profile)

GitHub does not require skills badges, statistics cards, trophies, visitor counters, automation, a license, or a custom banner to display a profile README.

## Existing profile audit

Source of truth: the cloned [root README](https://github.com/Siser-Pratap/Siser-Pratap/blob/main/README.md). Search-indexed profile content differed slightly from the current repository, so use the repository when editing.

| Area | Current state | Proposed improvement |
| --- | --- | --- |
| Introduction | Name and a generic full-stack developer headline | Explain focus, capabilities, and the kind of engineering work Siser wants to do |
| Skills | C, C++, CSS, Django, HTML, JavaScript, MongoDB, Node.js, Python, React, and Tailwind icons | Group skills by purpose and connect them to evidence; confirm proficiency instead of inferring it from icons |
| Work | No project narratives in the current README | Feature 3–5 projects with purpose, personal contribution, stack, and code/demo links |
| Open source | No contribution narrative | Link meaningful merged PRs and explain the problem solved |
| Experience | No work or education narrative | Add confirmed experience, education, and relevant achievements |
| Contact | LinkedIn, Instagram, LeetCode, and X links | Confirm destinations, add descriptive text, and choose professional channels |
| Accessibility | Several social icon descriptions contain another person's identifiers | Replace copied descriptions with accurate, meaningful labels |
| Presentation | Several remotely hosted animations and statistics images | Review their value and availability; keep essential information readable without images |
| Maintenance | No maintenance instructions | Document how to update projects, links, and any optional generated content |

The current links are candidates to confirm, not proof of current ownership or availability:

- [LinkedIn](https://linkedin.com/in/siser)
- [LeetCode](https://www.leetcode.com/siser_ins17)
- [X](https://x.com/PratapSiser)
- [Instagram](https://instagram.com/siser_ins17)

External image endpoints have not received a complete availability or rendering check in Phase 1. Do not label them broken without checking them.

## Initial project and contribution leads

These are investigation candidates, not a final ranking. Existing READMEs describe intent and may contain templates or unverified claims. Inspect code and confirm personal ownership and outcomes before writing profile claims.

| Candidate | Possible evidence to investigate | Source |
| --- | --- | --- |
| IntelAi frontend and backend | AI product UI, API integration, authentication, frontend/backend responsibilities | [Frontend](https://github.com/Siser-Pratap/intelai), [backend](https://github.com/Siser-Pratap/IntelAi-Backend) |
| VisionWeave | Image generation project; verify implementation and documentation | [Repository](https://github.com/Siser-Pratap/VisionWeave) |
| Authence | Authentication tooling and documentation UI; separate demo behavior from working backend features | [Frontend](https://github.com/Siser-Pratap/authence-frontend), [Authence](https://github.com/Siser-Pratap/Authence) |
| Portfolio and 3D portfolio | Next.js/React work, animation, 3D interaction, and presentation | [Portfolio](https://github.com/Siser-Pratap/portfolio), [3D portfolio](https://github.com/Siser-Pratap/portfolio-3d) |
| Mac on-screen chat | Potential desktop and local AI work; repository discovered but implementation not audited | [Repository](https://github.com/Siser-Pratap/mac-on-screen-chat) |
| AI email automation | Potential automation work; repository discovered but implementation not audited | [Repository](https://github.com/Siser-Pratap/AI-Email-Automation) |

Verified external contribution: [coffeeShop PR #234](https://github.com/Mujtabaa07/coffeeShop/pull/234), authored by `Siser-Pratap`, merged on 7 January 2025. The PR describes adjusting the scroll indicator, coffee graphic placement, and navbar spacing. Review its code changes before claiming a broader impact. This is one verified example, not a complete contribution inventory.

Documentation follow-ups: the exact `VisionWeave/README.md` lookup returned 404; check filename casing or alternate documentation. Several sampled project READMEs contain template installation URLs or broad feature lists. Treat documentation cleanup as a separate follow-up when choosing showcase projects.

## Proposed README content

1. **Introduction:** name, specific engineering focus, and a short statement of what Siser builds.
2. **Current work:** active project, current technical interests, and desired collaboration.
3. **Skills:** languages; frontend; backend and APIs; data; AI and automation; tools and deployment. Include categories only when supported by experience.
4. **Selected projects:** 3–5 focused summaries. For each: problem, personal role, key implementation decisions, outcome, stack, repository, and working demo or screenshot where available.
5. **Open-source contributions:** selected merged PRs, issues resolved, documentation, reviews, or maintenance work with direct evidence.
6. **Experience and education:** confirmed roles, dates, responsibilities, and relevant learning.
7. **Achievements:** certifications, awards, talks, publications, packages, or community work when applicable and verifiable.
8. **Connect and collaborate:** confirmed LinkedIn, portfolio, optional public professional email, resume, and useful developer profiles.
9. **Expanded history:** collapsible additional projects, older work, and optional interests.
10. **Optional activity visuals:** only when useful and maintainable. Treat language percentages and commit counts as activity indicators, not proficiency scores.

GitHub's own career guide recommends an introduction, skills, professional experience, selected projects, and achievements, backed by clear project documentation. [GitHub career guide](https://docs.github.com/en/account-and-profile/tutorials/using-your-github-profile-to-enhance-your-resume)

## Remaining phases and completion criteria

| Phase | Work | Reviewable result |
| --- | --- | --- |
| 2 — evidence inventory | Inspect public repositories and contribution history; collect personal details that code cannot establish | A source-linked skills/project inventory, contribution shortlist, and a small list of facts needing confirmation |
| 3 — content draft | Choose the strongest work and write the narrative for the confirmed audiences | A complete text-first README draft with accurate links and no invented outcomes |
| 4 — visual presentation | Apply a consistent style, choose useful badges/assets, and use expandable sections for depth | A readable GitHub-compatible layout in light/dark themes and narrow widths |
| 5 — verification | Check claims, links, images, accessibility, markup, and public rendering | A reviewed diff and rendered preview; identify any remaining gaps explicitly |
| 6 — publication and profile alignment | Publish the reviewed README and align bio, portfolio links, pins, and contribution visibility as separately applicable | The live profile reflects the finished README and selected work |

The user subsequently authorized completion of the remaining phases with automatic approval. Changing other project repositories, account settings, or pins remains separate work from editing this profile repository.

## Information to collect during Phase 2

Infer and verify what public code can establish before requesting details. The remaining personal inputs will likely be:

- Preferred role/title, employment or internship history, and dates.
- Education and relevant certifications or achievements.
- The projects Siser considers strongest and the parts personally implemented, especially team work.
- Measured outcomes that can be substantiated, if any.
- Current interests, availability, and collaboration goals.
- Current portfolio, resume, and preferred public contact channels.

Do not transfer private repository details into the public README without an explicit decision to disclose them. Do not invent employers, expertise levels, business metrics, awards, project adoption, or contribution totals.

## Verification checklist for the later draft

- [ ] Intro explains focus and value quickly to both confirmed audiences.
- [ ] Every listed skill is confirmed or connected to credible work.
- [ ] Each featured project explains Siser's own contribution and links to evidence.
- [ ] Contribution links accurately distinguish merged work from open proposals.
- [ ] Contact destinations and resume/portfolio links are current.
- [ ] No placeholders, copied identities, unsupported metrics, or unintended personal details remain.
- [ ] Important content is available as text, including when remote images fail.
- [ ] Images have meaningful alt text and remain readable across themes.
- [ ] GitHub's actual rendering is checked, including tables and collapsible content.
- [ ] Optional external cards are checked before inclusion and can be removed without losing essential content.
- [ ] Any automation has a clear purpose and documented maintenance needs.
- [ ] The final diff contains only the intended profile changes.
