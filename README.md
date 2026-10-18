# Kevin Taehyun Kim — Personal Archive

Jekyll website for GitHub Pages. The existing Taehyun logo and navy/ivory style are preserved.

## Publish a new entry (no homepage editing)
1. On GitHub, open `_entries` → **Add file** → **Create new file**.
2. Name it `2026-10-18-my-first-project.md` (use your actual date and slug).
3. Copy the content of `_templates/new-entry.md` into it.
4. Change `title`, `date`, `category` and the body, then **Commit changes**.
5. Category must be exactly one of: `Engineering`, `Investment`, `Strategy`, `Research`, `Essays`, `Presentations`.
6. Your entry appears automatically on its category page after Pages deploys.

## Upload reports
Upload a PDF to `assets/reports/`, then link it from your entry with:
`[Read PDF]({{ '/assets/reports/report.pdf' | relative_url }})`

## Setup
Upload the **contents** of this package to the root of `kevintaehyunkim.github.io` (not the enclosing folder). Replace the old `index.html`. Keep Settings → Pages → Deploy from a branch → main → /(root). Do not copy `index.html` by itself: Jekyll needs `_config.yml`, `_layouts`, and other folders.

## Notes
- `_templates` is excluded from publishing; example content is not displayed as a real achievement.
- GitHub Pages builds Jekyll automatically when publishing from a branch.
- All files in this public repository are publicly readable. Do not upload private research, personal notes, or credentials.
- The logo is stored in `assets/img/taehyun-logo.png`.
