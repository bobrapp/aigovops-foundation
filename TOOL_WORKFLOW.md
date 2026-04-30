# TOOL_WORKFLOW

**Philosophy:** Evidence over intent. Every artifact in this repo is traceable to the Google AI tool that produced it.

## Pipeline

| Stage | Google Tool | Output | Location |
|---|---|---|---|
| Research & IA | NotebookLM | Messaging brief, IA, FAQ, Briefing Doc, Mind Map ("Architecture of AI Governance"), Infographic ("Lifecycle of Modern AI"), Audio Overview Episode 0 | `/docs/notebooklm/` |
| Brand & Campaign | Pomelli | Business DNA extraction (logo, Inter font, palette, founder photos), "Governance that ships with code" campaign + 4 creatives | `/assets/pomelli/` |
| Site Generation | Stitch | Vanilla HTML/CSS/JS site: hero, Evidence Loop, 4 Pillars, Readiness Assessment, Standards Registry, Policy Bundle, newsletter | `index.html`, `/css/`, `/js/`, `DESIGN.md` |
| Hero Video | Flow (Veo 3.1) | 2x 1080p 16:9 hero MP4s: command center → governance pipeline | `/assets/flow/` |

## Source Inputs
- aigovopsfoundation.org (original site)
- Peter Yang YouTube walkthrough: https://www.youtube.com/watch?v=BQ_mgojj0Mo

## Accounts
- Google AI tools: bobrapp@gmail.com
- GitHub: bobrapp@hotmail.com (this repo)

## Build
No build step. Vanilla HTML/CSS/JS deployed directly via GitHub Pages from `main` branch root.

## License
MIT — see `LICENSE`.
