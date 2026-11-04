# CV Tailor

A Git-backed source of truth for maintaining a master CV and producing role-specific versions.

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

## Privacy

CVs can contain personal information. Review files before committing them and keep this repository private if it contains sensitive data.
