# Audit summary — MCP-youtube ML tooling playlist

Playlist audited: https://www.youtube.com/playlist?list=PLyzTA8cetPdHtlGw1X8Kt7Ea4bd27ApR7

This branch carries the summary of the audit whose three machine-readable reports live at the
root of `master`:

- `playlist_inventory.md` — all 40 retrievable playlist entries, one row per video, with an
  `include`/`skip` decision and a reason on every row (9 include, 31 skip), plus the 12
  unavailable entries YouTube does not expose.
- `ml_tech.md` — the 7 distinct technologies mined from the `include` videos, with category,
  canonical GitHub repository, main functions and supporting video IDs.
- `repo_conflicts.md` — the 5 genuine disagreements between the repository a video points at
  and what GitHub search returns near the top.

videos=40; techs=7; conflicts=5
