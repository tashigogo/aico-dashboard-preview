# AIco article dashboard trial preview

This is a trial UI for article editing and distribution workflow.

- Do not redistribute.
- No automatic posting.
- All publishing decisions require manual verifier approval.

## About

`index.html` is a standalone, self-contained dashboard — no backend, no build
step, no external API, no third-party assets. All data is stored only in the
visitor's own browser via `localStorage`. It walks one article through:

1. Topic candidates (skeleton / future hook)
2. Draft editing (v1 / v2 toggle, handwriting edits, voice memo)
3. 6-platform distribution drafting (note JP / Substack EN / Medium EN / LinkedIn EN / X / Instagram)
4. Pre-publish verification (8-point checklist)
5. Pre-publish status tracking (status / scheduled time / URL per platform)

It mirrors a dashboard kept privately in the AIco repository, and is published
here only so the workflow can be reviewed from a phone or another PC.

## Guardrails

- Brand name is **AIco**.
- No real names, titles, affiliations (e.g. broadcaster names), or
  confidential / client information.
- Content shown here may be unverified, in-progress draft material for testing.
- Posting to any external platform is done manually, only after verifier
  approval.

## Open

After GitHub Pages is enabled for this repository (branch `main`, folder `/`):

https://tashigogo.github.io/aico-dashboard-preview/
