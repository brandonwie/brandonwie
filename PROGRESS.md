# brandonwie - Progress

## Milestones

- [x] Project initialized with 3B integration
- [x] GitHub profile README elegance overhaul

## Session Log

### 2026-04-25

- Replaced the 3D contribution chart workflow with `Platane/snk@v3.5.0`
- Swapped README contribution media from `output-3d-contrib` day/night SVGs to
  `output-snake` light/dark snake SVGs
- Removed the unused `conf/github-profile-3d-contrib.json` config
- Rebasing was required before push because GitHub stats automation had advanced
  `origin/main`

### 2026-03-15 (session 2)

- Pinned `github-profile-3d-contrib` action to v0.9.2 (was `@latest` — supply chain risk)
- Enabled `workflow_dispatch` for manual 3D chart triggers
- Added `paths-ignore` to skip 3D rebuild on markdown-only pushes
- Replaced external Hi.gif CDN image with Unicode 👋 emoji
- Unified LinkedIn badge to shields.io `for-the-badge` style
- Added completion dates to 3 Coursera certifications (sourced from 3B credentials index)

### 2026-03-15

- Added OSS contributions section (2 merged PRs, 6 issue reports)
- Reviewed entire profile for elegance improvements (section-by-section)
- Restructured README: 147 → 91 lines, 10 → 7 sections
- Removed: Learning Platforms, trophy card, WakaTime, recent activity feed, footer
- Merged: "Things I work with daily" + "Previously worked with" → "Tech Stack"
- Flattened: Goals section (removed H3 sub-headers and checkboxes)
- Moved LinkedIn/Blog links from footer to Who Am I section
- Deleted `waka-readme.yml` and `update-readme.yml` workflows
- Evaluated 6 popular GitHub profile plugins (Streak Stats, Typing SVG, etc.) — skipped all

### 2026-02-24

- Initialized project with /init-3b
- Self-deployed github-readme-stats via GitHub Actions workflow
  (`github-stats.yml`) to avoid public Vercel instance rate limits
- Updated README to reference local `./profile/stats.svg` instead of external
  API
- Switched trophy card from single-row (`column=-1`) to default 6-column layout
- Verified WakaTime workflow is already self-contained (no changes needed)
