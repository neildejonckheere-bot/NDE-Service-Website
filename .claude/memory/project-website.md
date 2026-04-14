---
name: NDE Service website project
description: Hosting setup, DNS, file structure, and current state of the website
type: project
originSessionId: 63a87357-8966-47db-a025-05124981630f
---
Static HTML website hosted on GitHub Pages. Migrated away from Wix.

**GitHub:** github.com/neildejonckheere-bot/NDE-Service-Website (public repo)
**Domain:** www.ndeservice.be (registered with Wix, DNS points to GitHub Pages)
**DNS:** 4 A records pointing to GitHub IPs, CNAME www → neildejonckheere-bot.github.io

**File structure:**
- index.html — homepage
- over-mij.html — about page
- style.css — shared CSS for both pages
- CNAME — contains www.ndeservice.be
- images/ — Favicon.png, logo.svg, landing image.jpg, Stap1-4.jpg, Neil.jpg, eindwerk.jpg, logo.svg

**Logo:** SVG file (logo.svg) with paths converted in Inkscape. //NDE SERVICE format, slashes in orange (#fa4e42), text in dark. Raw Inkscape masters stored in Dropbox. White version still to be added.

**Design:** DM Sans font, orange (#fa4e42) accent, dark (#1a1a1a) and light (#f5f5f5) backgrounds. Dark header (#111) matching footer. Sticky header.

**Current state (as of 2026-04-14):** Homepage has hero image, alternating 4-step process section, contact section (light), "Ik werk voor" section (dark). Over mij page has Neil photo + intro side by side, story text, eindwerk section, CTA. White logo for header still pending.
