# Master CV source

This folder contains the canonical, verified information used to tailor future CVs.

## Recommended contents

- `cv.md` — complete master CV.
- `achievements.md` — measurable outcomes and supporting context.
- `skills.md` — skills, tools, and proficiency notes.
- `education.md` — education and certifications.
- `preferences.md` — target roles, locations, work authorization, and formatting preferences.

Keep facts detailed and accurate. Tailored CVs should select and rephrase this material, not invent new experience.

## Source precedence

When sources disagree, use this order:

1. A fact explicitly confirmed by the candidate and recorded in `master/`
2. The current master CV
3. Supporting notes in `templates/`
4. Job-specific files in `outputs/` (presentation only; never factual evidence)

Label uncertain items as unresolved rather than choosing the most convenient version. Do not infer dates, metrics, seniority, tools, employment relationships, work authorization, location, or proficiency.

## Safe Markdown migration

The recommended long-term source is `master/cv.md`, because it is easier for ChatGPT and GitHub search to retrieve reliably than a binary Word file. Create it only after the repository is private. Preserve the Word file as the visual-format reference, and compare every migrated claim before making `cv.md` authoritative.
