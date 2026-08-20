# Regan's Sweep Stake

A static site for a 20-player Premier League sweepstake, built for GitHub Pages.

- `index.html` — the sweepstake draw table (club/player/paid per entry)
- `rules.html` — full rules
- `overview.html` — the €2,000 prize structure, organising committee, entry details, and payment links

## Enabling GitHub Pages

1. Merge this branch into `main`.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. The included workflow (`.github/workflows/pages.yml`) deploys the site automatically on every push to `main`.

## Editing placeholders

Search each HTML file for `TBC` / `class="placeholder"` to find the fields that still need real values (entry fee, deadline, organiser contact, draw results).
