# NSF CAREER Workshop Studio (AI Era)

Interactive, GitHub-hostable workshop site for University of Mississippi NSF CAREER-seeking applicants.

## What this site includes

- Current funding trend briefing (NSF-first, plus NIH/NEH comparisons)
- Deep-dive grant process activities from positioning through final red-team
- AI draft-review lab with heuristic "AI tell" checks and revision prompts
- Microsoft Copilot prompt library with copy-ready exemplars
- Prompt builder and prompt quality triage tool (for custom CAREER prompt lists)
- Broader impacts canvas focused on AI-era societal and educational challenges
- Reflection journal with browser persistence
- Source deck with policy links for workshop facilitation

## Tech stack

- Vite
- React 18
- Plain CSS

## Local run

1. Install dependencies:
   - `npm install`
2. Start dev server:
   - `npm run dev`
3. Build production output:
   - `npm run build`

## GitHub hosting

This project is static and can be hosted with GitHub Pages.

1. Build:
   - `npm run build`
2. Publish the `dist/` folder through your preferred GitHub Pages workflow.

Notes:
- `vite.config.js` uses `base: "./"` so built assets resolve from relative paths.
- Before each live workshop, re-check agency policy links for updates.

## Content refresh workflow

- Update policy language and date stamp in `src/App.jsx` (`LAST_UPDATED`).
- Add/remove workshop prompts in the `promptLibrary` array.
- Add local institutional guidance in the trends panel or source deck.
