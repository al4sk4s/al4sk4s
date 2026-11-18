# CLAUDE.md

This is a GitHub **profile repository** (`al4sk4s/al4sk4s`). Its `README.md` is shown on the user's GitHub profile. There is no build, test or app code.

## Files
- `README.md` — the profile page (HTML + Markdown, centered header, typing SVG, social badges).
- `.github/workflows/update-age.yml` — runs every Jan 12 (and on manual dispatch) and rewrites the age.
- `alaskagub.png` — image asset.

## Rules
- The age lives between `<!--AGE-->` and `<!--/AGE-->` in `README.md`. Never edit the number by hand or remove the markers; the workflow computes it as `current year - 2007` (birthday: Jan 12).
- Keep the README renderable on GitHub: only HTML that GitHub allows, no scripts.
- The user's name is spelled **Auriélio R. S. Júnior**; handle is `al4sk4s`.
- Commit messages: short, lowercase, English (see `git log`).
- No Claude attribution (no `Co-Authored-By` or "Generated with" lines) in commits or PRs.
