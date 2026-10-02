# Change 1: Complete the About Page

## Goal

Replace the placeholder text in `about.md` with Tatsuro Okui’s actual professional and academic background, using only information he provides.

## Status

Proposal only. The About page has not been modified for this change. The detailed background information needed to complete it has not yet been supplied.

## Planned content

- **Professional introduction:** a concise overview based on supplied résumé or LinkedIn About text.
- **MBA background:** institution, program or degree name, study or graduation dates, and current status, as provided.
- **Professional background:** relevant roles, employers, responsibilities, and experience, as provided.
- **Areas of focus:** international business, digital strategy, and entrepreneurship, supported by any relevant details supplied.

## Information needed

Paste your résumé content or LinkedIn About text, or provide:

1. Your preferred professional introduction.
2. Your MBA institution, program, dates, and study or graduation status.
3. Your relevant professional experience and academic background.
4. Any details you want to include about international business, digital strategy, or entrepreneurship.
5. Any information you want omitted.

No personal information will be fetched from a URL.

## Implementation scope

After the background is supplied and the change is approved:

- Update the About page’s Markdown content.
- Replace placeholders only where verified information is available.
- Keep any remaining missing details clearly labeled as placeholders.
- Preserve its YAML front matter, URL, navigation, shared layouts, and existing design.
- Do not modify other pages or add features.
- Do not add a public email address or `mailto` link.

## Acceptance criteria

- The About page accurately reflects the supplied professional and academic background.
- No achievements, employers, projects, metrics, dates, or qualifications are invented.
- Supplied content replaces the corresponding placeholders.
- The page remains readable, accessible, and consistent with the light, minimal portfolio design.
- The Jekyll build passes, and the About navigation link still works.

## Current deliverable

Create only `Change1.md`. Do not modify `about.md` yet.