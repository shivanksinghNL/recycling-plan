# Repository Guidelines

## Project Structure & Content

This repository is a document collection centered on `Gujarat_Battery_Recycling_Master_Compendium.pdf`. Keep the root uncluttered: place any future supporting material in a clearly named directory such as `sources/`, `drafts/`, or `assets/`. Do not rename or replace the published PDF unless the change is explicitly requested.

Use descriptive, stable filenames. Prefer lowercase, hyphen-separated names for new files (for example, `sources/battery-recycling-data-2026.xlsx`); retain official document titles when they are supplied externally.

## Development, Build, and Review

There are currently no source files, package manifests, build scripts, or automated test commands. Before adding tooling, document its purpose and usage here or in a README. For document changes, review the rendered PDF locally in a standard PDF reader and confirm that page order, text legibility, tables, links, and citations remain intact.

If a PDF is generated from editable inputs, commit the editable source alongside it and record the generation command, for example:

```sh
make pdf
```

## Content and Formatting Standards

Preserve terminology, units, dates, and proper names exactly as supported by source material. Cite sources close to the relevant claim and include retrieval dates for web-based data. Use consistent heading levels, typography, and table formatting throughout a document. Keep images and charts readable at normal page scale; avoid embedding confidential or personally identifiable information.

## Validation Guidelines

Proofread every changed page and verify numerical values against the cited source. When practical, use a PDF validator and ensure the file opens without warnings. For substantive revisions, have a second reviewer check factual claims, references, and visual layout.

## Change Submission Guidelines

This directory is not currently a Git repository, so no local commit history defines a convention. If version control is initialized, use concise imperative commit subjects, such as `docs: update recycling capacity table`. In change requests, summarize the affected document and pages, explain the source of each material update, link related issues or source records, and attach before/after screenshots for layout-sensitive changes.

## Security and File Handling

Treat external documents as untrusted. Scan downloads before adding them, avoid macros or executable attachments, and remove metadata or sensitive data before publication. Keep licensed source material and access credentials out of the repository.
