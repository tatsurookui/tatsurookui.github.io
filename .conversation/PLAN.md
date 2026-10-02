# Personal Portfolio Site Plan

## Status

Planning only. The site will not be built until this plan is reviewed and approved.

## Goal

Create a professional personal portfolio for Tatsuro Okui, published as a GitHub user site at:

`https://tatsurookui.github.io`

The site will present a clear, credible overview of:

- MBA background
- Professional experience
- International business
- Digital strategy
- Entrepreneurship

The site will use only information supplied by Tatsuro. No employers, achievements, clients, projects, metrics, dates, responsibilities, or other biographical details will be invented.

## Site structure

The root of the project will be the complete, publish-ready Jekyll site. Planned pages:

- **Home** — concise professional introduction, focus areas, and calls to explore the portfolio
- **About** — MBA background, professional positioning, and supplied biography
- **Work Experience** — supplied roles, responsibilities, and accomplishments, presented in a readable chronological structure
- **Contact** — a simple contact-oriented page without a publicly displayed email address or `mailto` link

Every page will share:

- Primary navigation
- A consistent page header
- A semantic footer
- Responsive layout behavior
- Accessible focus states and color contrast

## Visual direction

- Light theme only
- Clean, professional, minimal visual language
- Generous white space
- Single-column layout
- Clean, modern typography
- Restrained color palette with strong text contrast
- No decorative animation system, unnecessary visual effects, or distracting interaction

Reference websites have not been supplied yet. If references are provided before implementation, they will guide layout and tone without being copied directly. If none are provided, the site will follow the direction above.

## Content plan

Content will remain separate from the design system:

- Markdown files will contain page content and YAML front matter.
- Reusable layouts and includes will contain shared page structure.
- CSS will contain the visual system and responsive rules.
- Any missing information will be labeled with a clear placeholder, such as `[Placeholder: add MBA details]`.

The following information is still required before the content can be finalized:

- LinkedIn About text or résumé content
- MBA institution, degree, dates, and relevant details
- Work experience, including employers, roles, dates, responsibilities, and achievements
- International business, digital strategy, and entrepreneurship details
- Projects or case studies, if they should be included
- Preferred professional summary or headline
- Public links to include, such as LinkedIn or other professional profiles
- Favicon identity or preferred mark, if different from a simple text-based placeholder

## Technical implementation

The site will be implemented as a static Jekyll site using:

- `index.md`
- Markdown page files
- YAML front matter
- `_config.yml`
- Reusable files in `_layouts/`
- Reusable partials in `_includes/`
- Plain HTML and CSS
- Minimal JavaScript only if a specific accessible interaction requires it

GitHub Pages configuration:

- `url: "https://tatsurookui.github.io"`
- `baseurl: ""`
- URL filters such as `relative_url` and `absolute_url` for generated links
- GitHub Pages-compatible Jekyll settings
- Publication from the `main` branch and repository root

Planned supporting files and features:

- SEO metadata and page titles
- Canonical URL support
- `sitemap.xml`
- Favicon
- `README.md` with editing, local preview, GitHub Pages, and Lighthouse instructions
- No backend, database, CMS, contact-form service, tracker, framework app, package manifest, or separate preview application

## Verification before delivery

Before the site is considered complete, verify that:

1. `index.md`, `_config.yml`, `_layouts/`, `_includes/`, assets, and all other website files are directly in the project root.
2. There is no nested website directory such as `jekyll-site/`, `website/`, `app/`, `artifacts/`, or `dist/`.
3. The project contains only the static Jekyll site and its documentation.
4. Navigation links resolve correctly using the empty `baseurl`.
5. The layout works at approximately 375px and 1280px viewport widths.
6. The site builds using GitHub Pages without a manual build step.
7. Lighthouse targets are at least 90 for Performance, Accessibility, Best Practices, and SEO, or any shortfall is documented with its cause.

## Assumptions

- The GitHub username is `tatsurookui`.
- The site is a GitHub user site, so `baseurl` must remain empty.
- The site should be written in English unless supplied content indicates otherwise.
- Light theme only is the current preference.
- No public email address or `mailto` link will be included.
- Placeholder content is acceptable until the missing biography and experience material is supplied.
- No reference sites are currently available.
