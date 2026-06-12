# Repository Guidelines

## Project Structure & Module Organization

This repository is a Hugo static site for ViveCodigo.org. Site-wide settings live in `config.yml`, including theme, menus, taxonomy, metadata, and permalink rules. Blog posts are in `content/blog/` as Markdown files with YAML front matter. Use `archetypes/default.md` when creating new content with Hugo. Theme overrides are in `layouts/`; keep them minimal so Stack can provide the look and feel. Files in `static/` are copied directly to the generated site. The active theme is `hugo-theme-stack` under `themes/`.

## Build, Test, and Development Commands

- `hugo server -D`: runs a local development server and includes draft content.
- `hugo server`: previews only publishable content.
- `hugo`: builds the static site into `public/` for validation or deployment.
- `npx --yes sass@1.69.7 --load-path=themes/hugo-theme-stack/assets/scss themes/hugo-theme-stack/assets/scss/style.scss static/stack.css --style=compressed --no-source-map`: regenerates the checked-in Stack CSS for non-extended Hugo builds.
- `hugo new blog/YYYY-MM-DD-short-title.md`: creates a new blog post from the default archetype.

The repo does not include Make or Go module tooling. Install Hugo locally and run commands from the repository root.

## Coding Style & Naming Conventions

Use two-space indentation for YAML front matter and `config.yml`. Keep Markdown prose readable with short paragraphs and descriptive headings. Name blog files with the existing date-prefixed, lowercase, hyphenated pattern, for example `content/blog/2015-08-15-podcast-10-de-la-temporada-0.md`. Prefer Stack configuration in `config.yml` over layout overrides. If Stack SCSS changes, regenerate `static/stack.css`.

## Testing Guidelines

There is no dedicated automated test suite. Before submitting changes, run `hugo` and fix build errors, broken shortcodes, or front matter issues. For content or visual changes, run `hugo server -D` and review the affected page locally. Check that images resolve, permalinks match `blog/:year/:month/:day/:title/`, and Spanish copy renders correctly.

## Commit & Pull Request Guidelines

Recent history uses short, imperative commit subjects with optional prefixes such as `add:`, `update:`, or `Test:`. Prefer concise messages that describe the user-visible change, for example `add: podcast episode notes` or `update: secure external links`. Pull requests should include a brief summary, affected paths or pages, validation performed (`hugo`, local preview), linked issues when applicable, and screenshots for layout or styling changes.

## Agent-Specific Instructions

Keep edits scoped to the static site source. Do not commit generated `public/` output unless the deployment workflow explicitly requires it. Preserve existing content metadata and avoid broad formatting churn in archived posts.
