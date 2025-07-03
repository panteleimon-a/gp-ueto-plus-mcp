# GP-UETO+ Research Monorepo

This repository is a research monorepo for the GP-UETO+ project, following a Meta-style structure for collaborative, reproducible, and automated research workflows. It integrates with GitHub and Linear via MCP servers for advanced automation and daily progress tracking.

## Structure

- `docs/` — Project documentation, protocols, and reference material
- `papers/` — Manuscripts, drafts, and publication-ready documents
- `data/` — Datasets (excluded from version control by default)
- `src/` — Source code for analysis, modeling, and utilities
- `notebooks/` — Jupyter notebooks and exploratory analyses
- `progress/` — Daily research logs and progress summaries

## Automation & Integration

- **GitHub MCP**: All repository operations (push, branch, PR, etc.) are automated via the GitHub MCP server.
- **Linear MCP**: Research tasks, milestones, and progress are tracked in Linear, with daily logs linked to milestones.
- **.vscode/mcp.json**: Configuration for MCP servers (GitHub and Linear) is stored here (excluded from version control).

## Daily Research Tracking

- Add a new Markdown file in `progress/` for each day’s research summary.
- Push updates to GitHub via MCP server.
- Log key milestones and progress in Linear (see "Pretesting the model" milestone).

## Getting Started

1. Clone the repo: `git clone https://github.com/panteleimon-a/gp-ueto-plus-mcp.git`
2. Install dependencies as needed for your research stack.
3. Use the provided structure for all research artifacts.

## License

This project is licensed for academic and research use only. See individual files for additional licensing where applicable.
