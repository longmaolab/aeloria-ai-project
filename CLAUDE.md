# Aeloria AI Project — Claude Memory

## Project Overview
Fantasy world creative project built with AI tools during Week 1 learning challenge.
Live site: https://longmaolab.github.io/aeloria-ai-project

## Entry Point
`index.html` — project hub, links to all pages

## World Lore (Quick Reference)
- **World**: Aeloria (艾洛瑞亚) — fantasy continent, nature magic vs industrial tech
- **Main character**: Toron — Silver Armor Totoro, forest guardian, awakened after 1000-year sleep
- **5 regions**: Lingsen Domain (west/forest), Iron Plateau (north/industrial), Blue Tide Isles (east/ocean), Red Sand Empire (south/desert), Frost Wastes (arctic)
- **5 characters**: Toron, Ah Qing (apprentice), Runkar (antagonist), Silvi (healer), Aeka (silver eagle)

## File Map
| File | Description |
|------|-------------|
| `index.html` | Project hub homepage |
| `adventure_game.html` | Branching story, dice combat, 4 endings |
| `pokemon_snake.html` | Pixel snake + Pokémon quiz on failure |
| `aeloria_legend.html` | 6-chapter creation chronicle |
| `aeloria_map.html` | World atlas with ASCII map |
| `characters.html` | 5-character gallery with AI image prompts |
| `manga_script.html` | 6-panel manga script |
| `storyboard_toron.html` | 30-second animation storyboard, 10 shots |
| `totoro_warrior.html` | Toron character sheet |
| `image_prompts.html` | AI image generation prompts |
| `video-prompts/kling_omni_v2.html` | Kling Omni 3-part prompts (30 sec) |
| `video-prompts/kling_omni_oneshot.html` | Kling Omni single highlight prompt |
| `video-prompts/jimeng_prompts.html` | Jimeng AI (Ghibli style) prompts |

## Asset Folders
- `characters/` — 5 AI-generated character PNGs
- `manga-panels/` — 6 AI-generated manga panel PNGs
- `videos/` — Kling AI generated MP4s

## Naming Rules (Always follow)
- HTML files: `snake_case.html`
- Images: `descriptive-english.png`
- No Chinese characters, no spaces, no special symbols

## GitHub
- Repo: https://github.com/longmaolab/aeloria-ai-project
- Remote: `git@github.com:longmaolab/aeloria-ai-project.git` (SSH)
- Push: `git push -u origin main`

## Tools Used
- Claude — writing, HTML/JS, world-building
- ChatGPT / DALL-E — character & manga panel images
- Kling AI (Omni engine) — AI video generation
- Jimeng AI — Ghibli-style video generation
- CapCut / 剪映 — video editing

## Known Tech Notes
- Copy buttons: use `textarea.select()` + `execCommand('copy')` — clipboard API fails on local files
- Snake game state machine: `phase = 'start' | 'play' | 'quiz' | 'over'`
- All HTML files are self-contained (no external dependencies)
