# CLAUDE.md — R&D Market Reports Portal

## Project context

This is a public GitHub Pages website for R&D Market Reports.
It is a structured portal, not a collection of isolated HTML files.

## Architecture

- The homepage lists only countries that have at least one published report.
- Each country has its own dedicated country page.
- Each country page shows reports grouped by analysis date.
- Two report types exist:
  1. **Initial Market Analysis** — first deep research of a market.
  2. **Periodic Market Update** — recurring monthly, quarterly, or ad-hoc updates.
- Navigation hierarchy: Homepage → Country page → Report date → Report page.

## Safety rules

- This repository is public. Never commit private or sensitive material.
- Do not add: raw research files, screenshots, merchant-sensitive data, or internal notes.
- The `sources/` folder is ignored by `.gitignore` and must remain local only.
- Do not invent data, providers, PSPs, payment methods, merchants, banks, regulations, or facts.
- If information is missing or unverified, mark it explicitly as **not confirmed**.

## Design rules

- Keep the portal clean, structured, premium, and easy to navigate.
- Preserve existing design unless explicitly asked to redesign.
- Use simple static HTML/CSS compatible with GitHub Pages.
- Do not introduce frameworks or build tools unless explicitly requested.

## Workflow rules

- Inspect existing files before making any edits.
- Make focused, minimal changes only.
- Report which files were changed after each task.
- Do not overwrite pages unrelated to the current task.
- Keep all reports linked correctly to the homepage and their country page.
