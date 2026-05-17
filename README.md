# Academic CV Materials

This repository now includes a maintainable material system for academic CV, bio, website, and job-market documents.

## Structure

- `source/`: canonical YAML facts. Update these first.
- `cv/`: modular LaTeX CV built from section files.
- `bio/`: short, website, and long bios.
- `website/`: draft Quarto pages for research, publications, teaching, and service.
- `job_market/`: application-specific CV and statement templates.
- `checks/`: consistency, missing-information, and release checklists.

## Workflow

1. Add verified facts to `source/`.
2. Update the relevant public-facing material in `cv/`, `bio/`, `website/`, or `job_market/`.
3. Search for `[TODO` before sharing anything.
4. Run the checklists in `checks/`.
5. Compile the CV from the `cv/` folder when ready.

Example CV build command:

```sh
cd cv
latexmk -pdf main.tex
```

Example job-market CV build command:

```sh
cd job_market
latexmk -pdf cv_job_market.tex
```

## Fact Policy

Do not invent personal facts. If a detail is missing, keep a placeholder such as `[TODO: add advisor name]` until it can be verified.

The YAML files are the source of truth. The LaTeX, bio, website, and job-market files are presentation layers that should be kept synchronized with those source facts.

