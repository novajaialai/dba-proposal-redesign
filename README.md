# DBA Phase 1 Proposal — Redesign

A take on the [Phase 1 implementation proposal](https://dba.smb-ops.com/clients/dba/phase1-proposal), rebuilt as two standalone versions.

**Live demo:** https://dba-proposal.pages.dev

| Version | URL | What it is |
|---|---|---|
| **v2** (recommended) | [dba-proposal.pages.dev](https://dba-proposal.pages.dev) | Full redesign — "blueprint / drawing set" concept (the proposal *is* the construction drawing set for the Revenue Operations Blueprint), copy rewritten, real approve CTA |
| **v1** | [dba-proposal.pages.dev/v1](https://dba-proposal.pages.dev/v1/) | Same design language as the original, structural fixes only |

## What changed vs. the original

1. **A way to say yes** — sticky "Approve Phase 1" button + mailto approve/question actions in the closing section (swap in your real email or a scheduling link).
2. **Price and ROI up front** — $18,500, 5 weeks, $36k/yr value, and the ≈1.9× year-one return are in the hero instead of 80% down the page.
3. **Nothing hidden** — out-of-scope items, future roadmap, and week details are fully visible instead of collapsed accordions (scope boundaries are contractual; don't make the client hunt for them).
4. **Proposal trust metadata** — prepared for/by, issue date, validity date, revision.
5. **v2 only:** acceptance criteria (AC-1…5), deliverables as a bill of materials, week-by-week schematic, and the drafting title block.

## Using it

Each version is a single self-contained HTML file — no build step, no dependencies beyond Google Fonts.

- Grab `site/index.html` (v2) or `site/v1/index.html` and host anywhere.
- Deploy to Cloudflare Pages: `npx wrangler pages deploy site --project-name <your-project>`
- Before sending to a client: replace `hello@smb-ops.com` in the approve buttons with your address or a booking link.
