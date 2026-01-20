# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **GitHub Profile Repository** - a personal portfolio/showcase displayed at https://github.com/wh131462. It is not a traditional software development project but a curated collection of static content for profile presentation.

## Repository Structure

- `README.md` - Main profile content with personal bio, tech stack, featured projects, and contact info
- `assets/` - Static media files (avatar.png, logo.svg)
- `.github/workflows/snk.yml` - GitHub Actions workflow for generating contribution snake animations

## Automation

The repository uses GitHub Actions to automatically generate animated contribution grid visualizations:

- **Workflow**: `.github/workflows/snk.yml`
- **Schedule**: Runs every 24 hours, on push to master, or manual trigger
- **Outputs**: Generates SVG/GIF snake animations deployed to the `output` branch
  - `github-snake.svg` (light theme)
  - `github-snake-dark.svg` (dark theme)
  - `ocean.gif` (animated ocean theme)

## Common Tasks

**Update profile content**: Edit `README.md` directly

**Update avatar or logo**: Replace files in `assets/` directory

**Manually trigger snake animation**: Go to Actions tab → "Generate Snake" → "Run workflow"

## Git Conventions

- Commit message prefixes: `docs:`, `chore:`, `fix:`, `feat:`
- Both English and Chinese commit messages are acceptable

## License

Dual-licensed under Apache License 2.0 and CC0-1.0 (public domain)
