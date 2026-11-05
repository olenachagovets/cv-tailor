# ChatGPT CV-tailoring operating rules

Use these rules with the private **Resume ATS Tailor** plugin and the connected GitHub repository `olenachagovets/cv-tailor`.

## Authority and evidence

- Treat `master/` as the only factual source of truth
- Treat `templates/` as method, formatting, and supporting context
- Treat `outputs/` as unverified job-specific drafts, never as evidence
- Never invent or strengthen dates, titles, seniority, tools, metrics, scope, causality, employment relationships, work authorization, location, or language proficiency
- If sources conflict, surface the conflict and ask one concise substantive question; do not guess
- Rephrasing is allowed only when the meaning and level of responsibility remain unchanged

## Intake

For each application, obtain the job description as pasted text, an attachment, or a verifiable link. Read the current master source from GitHub. Do not ask the candidate to resend facts already established in `master/` or in the current conversation.

If the GitHub source is unavailable, say exactly what could not be accessed and request only the missing source file or text.

## Required workflow

1. Extract required and preferred vacancy criteria
2. Map each important criterion to explicit evidence in `master/`
3. Label each item as supported, underemphasized, unverified, or candidate-confirmed gap
4. Stop before rewriting and ask only high-impact questions about genuinely unresolved experience
5. Accept “no experience” and “familiarity only” as complete answers
6. After answers, draft the tailored CV using only verified evidence
7. Produce a factual-change audit listing any claim whose wording materially changed
8. Require human review before the CV is submitted or saved as final

## Questions

Ask only questions that could materially change the CV for this vacancy. Group related issues and prioritize the highest-impact uncertainty. A good question names the vacancy requirement and asks for the candidate’s role, hands-on versus oversight involvement, project context, duration or recency, and any verified outcome or scope.

Do not ask generic discovery questions, repeat answered questions, or treat silence in the master CV as proof that experience is absent.

## Output and repository safety

- Draft into `outputs/<company>-<role>/`
- Keep `job-description.md`, `cv.md`, and `notes.md` separate
- In `notes.md`, record unresolved claims, omitted requirements, and the source files used
- Never overwrite files in `master/` during a tailoring run
- Never promote a claim from `outputs/` into `master/` without explicit candidate confirmation
- Do not commit or publish an output until the candidate has reviewed factual accuracy and personal information
- Use a branch and pull request for repository changes when available

## Final checks

Verify names, contact details, dates, titles, companies, locations, metrics, tools, education, certifications, languages, links, spelling, text extraction, and rendered layout. Do not claim an ATS score, guaranteed passage, or guaranteed interview.
