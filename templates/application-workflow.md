# Per-application workflow

## 1. Create the application folder

Use a stable lowercase name:

```text
outputs/<company>-<role>/
```

Create:

```text
job-description.md
cv.md
notes.md
```

## 2. Capture the vacancy

Save the full vacancy text in `job-description.md` with:

- source URL, if available
- date accessed
- company and role
- location or remote arrangement as stated
- required and preferred criteria

Do not rely on a link alone; postings can change or disappear.

## 3. Analyze before rewriting

Ask the Resume ATS Tailor plugin to compare the vacancy with the current master source in GitHub. It must first return:

- a compact requirement table
- a supported / underemphasized / unverified gap analysis
- only the unresolved, job-relevant experience questions

Do not request a rewritten CV until those questions are answered or the candidate explicitly chooses a strict master-only version.

## 4. Draft and audit

After clarification, generate `cv.md`. In `notes.md`, record:

- master files and commit/ref used
- confirmed answers supplied in the chat
- vacancy requirements intentionally omitted
- unresolved claims excluded from the CV
- any wording that could be mistaken for a stronger factual claim

## 5. Human review

Before use, verify every factual claim against `master/` and confirmed answers. Check contact information and links, then inspect the final DOCX or PDF visually and verify its extracted text.

## 6. Save safely

Keep the result as a draft until reviewed. If committing it, use a branch or pull request. Never merge a new fact into `master/` merely because it appeared in a generated CV.

## Suggested ChatGPT prompt

> Use the Resume ATS Tailor plugin and the connected GitHub repository `olenachagovets/cv-tailor`. Treat `master/` as factual authority, `templates/` as method only, and `outputs/` as non-authoritative drafts. Analyze this vacancy, complete the keyword and evidence-gap steps, then ask only unresolved substantive experience questions. Do not rewrite the CV until I answer or explicitly request a strict master-only version. Never invent facts or metrics.
