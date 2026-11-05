# CV Tailor

A Git-backed source of truth for maintaining a master CV and producing role-specific versions.

## ChatGPT architecture

Use three separate layers:

1. **Facts:** `master/` contains verified candidate facts. It is the only factual authority.
2. **Method:** the private **Resume ATS Tailor** ChatGPT plugin controls analysis, clarification, rewriting, and formatting.
3. **Delivery:** `outputs/` contains job-specific drafts. Output files never become evidence for future CVs unless a verified fact is deliberately promoted into `master/`.

The ChatGPT GitHub app should be used to read this repository. Repository changes should be made through a reviewed branch or pull request, not by silently overwriting the master CV.

## Repository structure

- `master/` — canonical career history, skills, achievements, and supporting facts.
- `templates/` — reusable CV layouts, prompts, and tailoring templates.
- `outputs/` — generated, job-specific CVs and related deliverables.

## Suggested workflow

1. Keep verified career information current in `master/`.
2. Add reusable formats and instructions to `templates/`.
3. For each application, provide the job description and answer any clarification questions.
4. Save the tailored result in a clearly named subfolder under `outputs/`.
5. Review every generated CV for accuracy before using it.

See `templates/chatgpt-agent-instructions.md` for the operating rules and `templates/application-workflow.md` for the per-vacancy workflow.

## Privacy

CVs can contain personal information. Review files before committing them and keep this repository private if it contains sensitive data.

This repository currently contains a CV with personal contact information. Make the repository private before adding a plain-text or Markdown copy of the master CV, because text files are easier to search and index than a Word document.
