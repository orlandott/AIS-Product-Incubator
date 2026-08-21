# AIS Product Incubator website

Landing site for the **AIS Product Incubator**, an AI safety product incubator in Lisbon run in collaboration with the [Lisbon AI Safety Hub (LAISH)](https://lisbonaisafetyhub.org/).

## The program

1. **Apply**: open call for tech workers in Lisbon who are curious about AI safety.
2. **Selection**: the strongest applicants form a small cohort.
3. **Context**: 8 weeks of AI safety grounding, run by LAISH.
4. **Build**: 4 weeks building AI safety products in teams.
5. **Pitch**: teams pitch their products to potential donors and investors.

Example product directions on the site are adapted from Forethought's [Design sketches for a more sensible world](https://www.forethought.org/research/design-sketches-for-a-more-sensible-world) and the [Checks & Balances in an Automated Society](https://checks-and-balances.ai/) RFP.

## Tech

A single self-contained static page. `index.html` holds all markup, styles, and scripts. No build step, no dependencies (only Google Fonts loaded at runtime, with system-font fallback).

## Deploying (GitHub Pages)

1. Repo → **Settings → Pages**.
2. Source: **Deploy from a branch**, pick the branch and `/ (root)`.
3. Save, and the site goes live at `https://<user>.github.io/AIS-Product-Incubator/`.

Any static host (Netlify, Vercel, Cloudflare Pages) works too; just serve the repo root.

## Before launch

- **Application form**: search `index.html` for `TODO` and point the "Apply for Cohort 01" button at your real application form URL (currently it just scrolls to the apply section).
- **Dates**: the site says "Applications opening soon"; update the copy once cohort dates are fixed with LAISH.
