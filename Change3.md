---
published: false
---

# Change 3: Complete MBA Details and Remove Unneeded Sections

## Goal

Complete the About page's MBA background, remove the Contact page and its navigation entry, and remove the unfinished Role history section from Work Experience.

## Status

Plan only. None of these website changes have been implemented.

This document is marked `published: false` so Jekyll does not publish it as part of the website.

## Planned changes

### 1. Replace the MBA placeholder on About

In `about.md`, retain the **MBA background** heading and replace its placeholder with this exact sentence:

> MBA Candidate at UC Berkeley Haas School of Business, Class of 2027.

Do not change the professional profile, areas of focus, front matter, or page URL. Do not describe the MBA as completed or add other academic details.

### 2. Remove Contact from the site

- Delete `contact.md` so the entire Contact page is removed, rather than merely hidden from navigation.
- Remove the **Contact** navigation entry. The current `_includes/header.html` generates navigation from pages with `nav_order`; deleting `contact.md` should remove the entry automatically, without changing the shared header.
- Keep the remaining navigation in its existing order: **Home**, **About**, **Work Experience**.
- Verify that `/contact/` is absent from the generated sitemap. The current `sitemap.xml` uses the same page metadata and should update automatically.
- Check for remaining internal links to `/contact/` and remove any that would become broken.
- Verify that the generated site contains no leftover Contact page and that `/contact/` returns the site's normal 404 response after rebuilding. Do not add a redirect, replacement contact page, email address, or `mailto` link.

Removing this page intentionally makes its previous URL unavailable. No contact method will be added in its place.

### 3. Remove Role history from Work Experience

In `work-experience.md`, remove the entire **Role history** section:

- Delete the `## Role history` heading.
- Delete the placeholder block beneath it.
- Remove any resulting unnecessary blank space.

Keep the career overview, all four experience highlights, front matter, and page URL unchanged. Do not add replacement role entries or another placeholder.

## Implementation scope

Only after the user explicitly requests implementation:

- Modify the relevant content in `about.md` and `work-experience.md`.
- Delete `contact.md`.
- Make additional navigation or internal-link edits only if necessary to remove Contact completely; do not refactor shared templates unnecessarily.
- Preserve the existing simple, professional design, styles, layouts, remaining pages, and root-level static Jekyll structure.
- Do not introduce new features, frameworks, services, tracking, or personal information.
- Do not commit or push anything. The user handles Git manually.

## Verification and acceptance criteria

After implementation:

1. The About page displays exactly: **MBA Candidate at UC Berkeley Haas School of Business, Class of 2027.**
2. The MBA placeholder is gone; the rest of About remains unchanged.
3. The Contact source page and generated page are absent.
4. Contact appears in neither desktop nor mobile navigation, and no internal navigation points to `/contact/`.
5. The sitemap no longer includes `/contact/`, and that URL returns a normal 404.
6. Work Experience contains neither the Role history heading nor its placeholder; its overview and four highlights remain unchanged.
7. A clean Jekyll build passes, remaining navigation links work, and the affected pages retain their existing layout.
8. No commit or push commands are run.

## Current deliverable

Create only `Change3.md`. Do not implement any planned changes, modify website files, delete the Contact page, commit, or push anything.