# KiCad Workspace

This repository contains various KiCad hardware projects with an automated webviewer deployment.

## Projects

All KiCad projects are located in the `boards/` directory:
- `pedal_split_supply` - Pedal Split Supply

## Webviewer

An interactive webviewer is automatically built and deployed to GitHub Pages on every push to `main`.

**View the projects:** [https://hmcty.github.io/kicad-ws/](https://hmcty.github.io/kicad-ws/)

The webviewer allows you to:
- Browse all projects in the repository
- View schematics and PCB layouts interactively
- Download project files as ZIP archives
- Share links to specific locations in designs

## Deployment

The webviewer is built using [KiShare](https://github.com/hmcty/kishare) with [KiCanvas](https://github.com/theacodes/kicanvas) for rendering.

The deployment workflow (`.github/workflows/deploy.yml`) automatically:
1. Scans the repository for KiCad projects
2. Generates an interactive webviewer
3. Deploys to GitHub Pages

To trigger a manual rebuild, go to **Actions** → **Build and Deploy KiCad Webviewer** → **Run workflow**.

## Adding New Projects

Simply add new KiCad projects to the `boards/` directory and push to `main`. The webviewer will automatically rebuild and include the new projects.
