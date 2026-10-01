# sgranadaag

This is the user's own GitHub profile repository — `README.md` is the content that renders on their GitHub profile page. It's a living document the user updates over time, so treat it as the current, evolving source of truth rather than a fixed snapshot — but any future edit should preserve the structure and intent below, not just the wording.

## README structure & philosophy

- **Purpose comes first, person second.** The opening copy (no heading, right under the `<h1>`) frames this GitHub account as a hub of open-source examples/implementations covering software development practices, design, patterns, and technologies — each meant to be freely replicated, with a thorough write-up of what it does and why. This section comes *before* "About me".
- **Usage terms are explicit**: anyone is free to use, fork, or build on the examples here. Credit as co-author on the resulting implementation is appreciated, not required. Keep this stated plainly whenever that copy changes — don't drop it or soften it into something vaguer.
- **"About me" stays deliberately minimal** — a one-line bio, no career narrative — and links out to [LinkedIn](https://www.linkedin.com/in/sgranadaag/) for detailed experience. Don't re-expand this section with role history, achievements, or dates; that level of detail belongs on LinkedIn or in the CV (`docs/`), not in this README.
- **Section order**: profile purpose → About me → Tech Stack → Featured Projects → Certifications.
- **Tech Stack** is a full-width HTML `<table width="100%">` with three equal columns: every `<td>` has `width="33%"` and `valign="top"`, and holds a bold category label over one skillicons row (`height="30"`). Categories fill the rows in order so they line up: Frontend | Backend | Databases, then CI/CD | Infra & Cloud | AI. Keep it compact — the projects are the focus. Claude uses the custom tile `assets/claude.svg`, since skillicons has none.
- **Certifications** is a single row of Credly badge images, each linked to its public verification page and sized like the others (`width="110"`). Add new badges to that row by hand; don't swap it for an auto-sync action or third-party card service.
- **Heading style**: section headings after the `<h1>` are plain text with no emoji (e.g. `### About me`, `### Tech Stack`) — the user wants a professional look. Match that when adding or renaming a section.

## docs/

Holds the user's current CV. Check there for specific roles, dates, or achievements beyond what the README or LinkedIn summary covers.

## Workspace

This repo lives alongside the user's other personal projects as sibling folders under one parent directory — each an independent repo with its own history. When working in one of those other projects, this repo (and its README/CV) is the place to look for the user's overall background, skill set, and featured-project list.
