# DBA Phase 1 Proposal — Redesign

Critical redesign of https://dba.smb-ops.com/clients/dba/phase1-proposal (a colleague's SMB Ops client proposal).

**Live:** https://dba-proposal.pages.dev (Cloudflare Pages project `dba-proposal`)

- `site/index.html` — v2, the shipped version: "blueprint / drawing set" design (Archivo + IBM Plex, ultramarine, drafting title block, sheet-numbered sections), copy rewritten.
- `site/v1/` — v1: structural/UX fixes only, keeping the original's cream/serif design language (sticky CTA, price+ROI in hero, proposal metadata, no hidden accordions, real approve action).
- `site/v2/` — same as root.

Deploy: `npx wrangler pages deploy site --project-name dba-proposal --branch main`
