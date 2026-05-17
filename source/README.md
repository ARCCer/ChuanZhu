# Source Facts

This folder is the canonical source for CV, bio, website, and job-market materials.

Use these YAML files to store verified facts only. If a detail is unknown or not ready, leave a placeholder such as `[TODO: add university]` rather than guessing.

## Files

- `profile.yml`: basic identity, contact, links, and public positioning.
- `education.yml`: degrees, dissertation, advisors, and training history.
- `research_interests.yml`: research identity, fields, substantive interests, methods, and keywords.
- `working_papers.yml`: papers that are complete enough to circulate or submit.
- `work_in_progress.yml`: earlier-stage projects and research pipeline items.
- `publications.yml`: published or accepted papers, if any.
- `conference_presentations.yml`: conference talks, posters, workshops, and doctoral consortia.
- `invited_talks.yml`: invited seminars, guest talks, and job-market talks.
- `teaching.yml`: instructor, teaching assistant, advising, and teaching interests.
- `industry_experience.yml`: industry collaboration and research-facing professional experience.
- `awards.yml`: awards, fellowships, grants, and honors.
- `service.yml`: reviewing, conference service, departmental service, and memberships.
- `skills.yml`: programming, empirical methods, tools, and languages.
- `references.yml`: advisor and reference contact information for private/job-market versions.
- `missing_information.md`: checklist of all fields to complete.

Suggested workflow:

1. Update the relevant YAML file first.
2. Mirror the verified detail into `cv/`, `bio/`, `website/`, or `job_market/`.
3. Run the checklists in `checks/` before sharing any public version.
