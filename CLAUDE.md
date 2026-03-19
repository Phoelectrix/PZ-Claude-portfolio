# CLAUDE.md — pavloszafiropoulos.com Portfolio Site

## Project overview

This is a personal portfolio website for Pavlos Zafiropoulos, a science journalist,
science communicator, and senior editor currently seeking work. The site will be hosted
at pavloszafiropoulos.com, deployed as a static site via Netlify, with the domain
registered through Cloudflare Registrar.

The goal is a complete redesign replacing an existing WordPress.com portfolio at
pavloszafiropoulos.wordpress.com. All content should be drawn from that site and
the biographical information below.

---

## About the owner

Pavlos Zafiropoulos is a science journalist and communications strategist with an
academic background in Biology (University of Cambridge) and Science Communication
(Imperial College London). He has over 15 years of experience across broadcast
journalism, print, digital media, and EU research communications.

Journalism clients and outlets include: the New York Times, the BBC, the Washington
Post, the Wall Street Journal, Deutsche Welle, This American Life, Kathimerini,
SKAI TV (award-winning EcoNews programme), Air Traffic Technology International,
Alma Economics, and Citylab.

Most recently he has led communication and dissemination for three Horizon Europe
research consortia (HiDALGO2, ImAFUSA, RefMap), translating cutting-edge scientific
research into public-facing content that surpassed all project KPIs.

He is also a seasoned copy editor, proofreader, and translator (Greek–English), and
has extensive experience as a Digital Editor, most notably for Greece-Is.com
(Kathimerini newspaper).

Contact: pjzafiropoulos@gmail.com
LinkedIn: https://www.linkedin.com/in/pavlos-zafiropoulos-77458093/

---

## Target roles

The site must credibly position Pavlos for the following types of roles:

- Science communication (specialist and leadership)
- Journalism (print, digital, broadcast)
- Senior editor positions
- Communications and dissemination leadership (research/NGO/corporate)

The site is a professional portfolio, not a blog. Hiring managers and commissioners
are the primary audience. First impressions and scannability matter enormously.

---

## Content inventory

The site should include the following sections and content items. Each portfolio
item listed below has its own **individual detail page** (in `/portfolio/`) with
full descriptions sourced from the WordPress export, project metadata sidebar,
skills tags, external links/PDF downloads, and prev/next navigation:

### Hero / above the fold
- Name, positioning statement, primary credential indicators
- Call to action (view work / get in touch)

### About
- Biographical summary in first person, editorial voice
- Professional headshot: `Hero Portrait.jpg` (in project root)

### Journalism — articles
- "The Long-Ignored Athens Waterfront Is Being Revived" — New York Times, Oct 2019
- "Creating a Golf Destination in the Hills of Greece" — New York Times
- "Drone Economics" — Air Traffic Technology International
- "Brisk Business for Smugglers in Greece" — Deutsche Welle
- "EU shirks refugee relocation responsibility" — Deutsche Welle
- "Behind the scenes: The making of a new tax relief for UK filmmaking" — Alma Economics
- "A Billion Lonely People" — Alma Economics
- Additional BBC, Washington Post, Wall Street Journal, and This American Life work
  referenced in bio (clips/links TBC — include as bio references if no links available)

### Science communication — Horizon Europe projects
- HiDALGO2 (Horizon Europe) — Communication & Dissemination Lead
  €6M project, HPC & AI for environmental challenges, 8 partners, 7 countries,
  Nov 2024–Jan 2026, all KPI targets surpassed. Link: www.hidalgo2.eu
- ImAFUSA (Horizon Europe) — Communication & Dissemination Lead
- RefMap (Horizon Europe) — Communication & Dissemination Lead

### Video
- "Lights, Camera, Economics: Independent Film in the UK" — Alma Economics
- "Argolicorama Short Film" — Argolic Environment Foundation
- "Alma Economics in Under 60 Seconds" — Alma Economics

### Digital & editorial
- Website Content & Social Media Management — Alma Economics
- Website Content & Social Media Management — Greece-Is.com / Kathimerini
- Website Content & Social Media Management — Argolic Environment Foundation

### Other projects
- The Atlas of Greek-Turkish Relations — Kathimerini
- AEF Scoping Report — Argolic Environment Foundation
- Argolicorama 2022 — Argolic Environment Foundation
- Symbols & Iconic Ruins Catalogue — Citylab
- Greece Is Publishing — Kathimerini

### CV
- Concise version of the full CV (source: `CV/PZ Master CV.md`)
- Timeline format with key roles and 1–2 key achievements per role
- Roles to include: Future Needs / Horizon Europe (2024–2026), Alma Economics (2022–2024),
  Argosaronic Environment Foundation (2021–2022), Kathimerini / Greece-Is.com (2017–2021),
  Freelance Journalism (2015–2021), SKAI TV (2007–2012)
- Education: MSc Imperial College London, BA Cambridge
- Optional: downloadable PDF link (owner to supply PDF)

### Contact
- Email address (pjzafiropoulos@gmail.com)
- LinkedIn link
- Statement of availability and services offered
- No contact form — email link and LinkedIn are sufficient

---

## Technical approach

- Static site — no CMS, no server-side logic
- Pure HTML, CSS, and minimal vanilla JavaScript only
- No frameworks, no npm, no build tools
- **Multi-page site** with separate pages for major sections (Portfolio, CV, etc.),
  a home page featuring selected/featured portfolio items, and **individual detail
  pages for each portfolio item** (in `/portfolio/` directory) containing full
  descriptions, project metadata, skills demonstrated, sidebar with links/PDFs,
  and prev/next navigation between items
- Shared navigation and footer across all pages
- All content hardcoded in HTML — owner is comfortable editing text in files directly
- Images referenced locally (owner will supply headshot and project images)
- Fully responsive — must work well on mobile and desktop
- Fast loading — no unnecessary dependencies
- Deployable to Netlify by dragging and dropping a folder
- Custom domain: pavloszafiropoulos.com (DNS managed via Cloudflare)

---

## Design direction

The owner's stated feel: **light background, clean, with science and nature fusion accents**.

**Theme:** Light theme only for initial build. Dark mode toggle may be added later.

**Primary design reference:** miromannino.com — take structural and layout inspiration
from this site, specifically:
- Card-based portfolio display with large image + text + metadata tags
- Strong hero section with headshot, name, and concise positioning statement
- Generous whitespace and clear section separation
- Scroll-triggered fade-in animations (vanilla JS, no libraries)
- Fixed navigation with clean typography
- Selected/featured portfolio items on the home page, with a "See all" link
  to the full portfolio page

Adapt the reference's structure to a **light colour scheme** and a more editorial,
journalistic register (not developer-oriented).

Target aesthetic references: editorial quality of publications like The Atlantic or
Nature, combined with the clean personal portfolio conventions of senior journalists
and academics. The site should feel contemporary and confident — not corporate, not
bloggy, not over-designed.

The design should reflect the dual identity of the owner: rigorous scientific
background combined with strong journalistic and editorial voice. The medium should
reinforce the message — a beautifully crafted site is itself a demonstration of
communications competence.

Beyond this direction, all specific design decisions — typography, colour palette,
layout, spacing, component style, and visual hierarchy — are left entirely to
Claude's discretion. Develop a coherent, considered design system appropriate for
the brief without being constrained by any particular reference or convention.

---

## Key design principles (non-prescriptive)

- Credibility signals should be prominent without being boastful
- The most impressive work (NYT bylines, Horizon Europe leadership, broadcast credits)
  should be immediately visible — do not bury the lede
- The owner's editorial voice should be present from the first paragraph
- Content organisation should reflect value and impact, not format categories
- The site must work hard in the first 10 seconds of a hiring manager's visit
- Contact information must be accessible without scrolling on desktop

---

## Screenshot workflow

- Puppeteer is installed globally at `~/.npm-global/lib/node_modules/puppeteer/`.
- **Serve the site locally first:** `python3 -m http.server 8080` (run from the project folder)
- **Then screenshot:** `node screenshot.mjs http://localhost:8080`
- Screenshots are saved automatically to `./temporary screenshots/screenshot-N.png` (auto-incremented, never overwritten).
- Optional label suffix: `node screenshot.mjs http://localhost:8080 label` → saves as `screenshot-N-label.png`
- `screenshot.mjs` lives in the project root. Use it as-is.
- After screenshotting, read the PNG from `temporary screenshots/` with the Read tool — Claude can see and analyze the image directly.
- When comparing, be specific: "heading is 32px but reference shows ~24px", "card gap is 16px but should be 24px"
- Check: spacing/padding, font size/weight/line-height, colors (exact hex), alignment, border-radius, shadows, image sizing

---

## Required skill

When building, designing, or modifying any frontend code for this site, **always use
the `frontend-design` skill** (invoke via the Skill tool). This ensures all HTML, CSS,
and visual work meets a high design-quality standard and avoids generic AI aesthetics.

---

## Available assets

- **Headshot:** `Hero Portrait.jpg` (project root)
- **Full CV:** `CV/PZ Master CV.md`
- **WordPress export:** `Old_Wordpress_Content/pavloszafiropoulos.WordPress.2026-03-19.xml`
  Contains all 17 published portfolio items with full descriptions, external links, and tags.
- **Media files:** `Old_Wordpress_Content/media-export-237385525-from-0-to-337/`
  Contains project screenshots, article PDFs, and images organised by date (2024/09, 2024/10, 2026/02).
- **Portfolio images:** `images/portfolio/` — Correctly matched images for each portfolio
  item, sourced from the WordPress media export. Each item has its own distinct image
  matching what was used on pavloszafiropoulos.wordpress.com.
- **Article PDFs:** `documents/` — PDF copies of published articles for download links.
- **Reference screenshots:** `Reference_Screenshots/` — Hero, Portfolio items,
  Selected Articles, and Footer from miromannino.com for design reference.

---

## Out of scope

- Blog or news feed functionality
- CMS or admin interface
- Contact form with backend (email link and LinkedIn are sufficient)
- Dark mode / theme toggle (may be added in a later phase)
- Any WordPress dependency
