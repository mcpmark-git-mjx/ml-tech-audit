# Audit summary — MCP-youtube ML tooling playlist

Playlist audited: https://www.youtube.com/playlist?list=PLyzTA8cetPdHtlGw1X8Kt7Ea4bd27ApR7

This branch carries the summary of the audit whose three machine-readable reports live at the
root of `master`:

- `playlist_inventory.md` — all 50 retrievable playlist entries, one row per video, with an
  `include`/`skip` decision and a reason on every row (8 include, 42 skip), plus the 2
  unavailable entries YouTube does not expose IDs for.
- `ml_tech.md` — the 8 distinct technologies mined from the `include` videos, with category,
  canonical GitHub repository, main functions and supporting video IDs.
- `repo_conflicts.md` — the 6 genuine disagreements between the repository a video points at
  and what GitHub search returns near the top.

videos=50; techs=8; conflicts=6