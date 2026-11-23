# Open-source productization — license-first guides

A small static site: how to turn seven widely-used open-source projects into
products, starting from what each project's **license** actually permits.

- **Method — pin-and-wedge:** pin the upstream at a release, read its license as
  the load-bearing constraint, and ship a *wedge* alongside it. Never a fork or a
  rewrite; the upstream stays a pinned, replaceable dependency.
- **Guides (one page each):** Coolify, Immich, Stirling-PDF, Open WebUI,
  Vibe-Trading, God's Eye View, Paperclip.

Each page covers: what the project is → the license reality → how you'd
productize it (the wedge + the business model) → the groove → the one catch that
will trip you up.

## Honesty

Licenses and pinned versions were **verified against each repository on
2026-11-23** (read from each `LICENSE` file and the GitHub release list). These
are productization *guides* — nothing here is a running product, and none of the
named projects endorses this.

## Run locally

Open `index.html` in a browser. Plain HTML/CSS, no build step, no dependencies,
light + dark.

## Deploy

GitHub Pages, from `main` / root.
