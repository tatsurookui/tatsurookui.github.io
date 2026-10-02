---
published: false
---

# Change 2: Clarify Work Experience for Recruiters

## Goal

Make `work-experience.md` clearer, more concise, and easier for recruiters to scan, using only professional background supplied by Tatsuro Okui.

## Status

Proposal only. The Work Experience page has not been modified for this change.

This document is marked `published: false` so Jekyll does not publish it as part of the website.

## Current page

The page currently says that professional experience details have not been provided and contains a placeholder for roles, employers, dates, responsibilities, and achievements. A professional summary has since been supplied, but detailed role history is still unavailable.

## Verified background available

- 13 years of experience in the life insurance industry.
- Experience in retail sales.
- Participation in an overseas trainee program in Singapore.
- New business development in collaboration with startups.
- Most recent focus: enhancing digital strategies in the asset formation sector, with the goal of creating new experiential value for customers.

These are supplied experience areas, not confirmed job titles or a dated employment timeline. The customer-experience statement is a goal, not evidence of a completed result.

## Proposed content structure

### 1. Brief career overview

Lead with a short summary that immediately communicates industry experience and recent focus.

Suggested draft for later approval:

> I have 13 years of experience in the life insurance industry, spanning retail sales, an overseas trainee program in Singapore, and new business development with startups. Most recently, my work has focused on digital strategies in the asset formation sector, aiming to create new experiential value for customers.

### 2. Concise experience highlights

Use short, descriptive headings and bullets rather than repeating the overview in long paragraphs:

- **Digital strategy:** Enhancing digital strategies in the asset formation sector, with a focus on new experiential value for customers.
- **New business development:** Developing new businesses in collaboration with startups.
- **International experience:** Participating in an overseas trainee program in Singapore.
- **Retail sales:** Experience in retail sales within the life insurance industry.

Present these as experience areas, not separate jobs. Lead with the most recent focus; do not imply dates or chronology for the other areas.

### 3. Role history, when supplied

If verified employment details are provided, replace the experience-area format with a concise, reverse-chronological role history:

- Job title, employer, dates, and location, where supplied.
- Two or three bullets per role describing responsibilities and relevant contributions.
- Outcomes or metrics only when provided and approved for publication.

Until then, keep any missing role-history details clearly labeled as placeholders. Do not turn experience areas into invented roles.

## Writing guidelines

- Use plain, professional English and consistent first-person wording.
- Lead with the most relevant experience and make each bullet easy to scan.
- Use concrete descriptions; avoid generic claims such as “proven leader” or “results-driven.”
- Distinguish responsibilities and goals from verified achievements.
- Avoid repeating the About page's general biography or academic background.
- Do not invent employers, titles, dates, projects, technologies, achievements, metrics, or qualifications.

## Information needed for a fuller recruiting profile

Before adding a detailed role history, request:

1. Employer names, official job titles, and employment dates.
2. The responsibilities and contributions to highlight for each role.
3. Any verified outcomes or metrics that may be published.
4. Target roles or recruiting priorities, if the page should be tailored.
5. Confidential details or other information to omit.

Use only text supplied directly by the user. Do not fetch personal information from LinkedIn or another URL.

## Future implementation scope

Only after approval to implement:

- Update the Markdown body of `work-experience.md`.
- Replace the outdated introduction and supported placeholders with verified content.
- Preserve its YAML front matter, `/work-experience/` URL, navigation, shared layouts, and existing simple, professional design.
- Leave About, Home, Contact, styles, and website configuration unchanged.
- Keep the root-level static Jekyll structure; do not add frameworks, services, or features.
- Do not add a public email address or `mailto` link.
- Do not commit or push unless separately instructed.

## Acceptance criteria for later implementation

- Recruiters can quickly identify the 13-year industry background, recent digital-strategy focus, and other supplied experience areas.
- The page uses a brief overview and concise, clearly labeled highlights or verified role entries.
- Every factual claim is supported by user-provided information.
- Missing details remain clearly marked; experience areas are not misrepresented as jobs or achievements.
- The page remains readable, accessible, and visually consistent with the existing site.
- The Jekyll build passes and the Work Experience navigation link still works.
- Only the approved page content changes; no commit or push is performed without separate instruction.

## Current deliverable

Create only `Change2.md`. Do not modify the website, implement this proposal, commit, or push any changes.