# CHECKMATE//ANIMA — Chess Animaze

A two-part concept and playable prototype for an anime-inspired tactical chess experience.

## Projects

### 3D playable prototype (`chess3d/`)
React + TypeScript + Vite + Three.js. Includes a 6x6 tactical grid, class-based pieces, procedural character rigs, animated combat, skills/ultimates, enemy AI, HUD, audio, and model-loader support.

```bash
cd chess3d
npm ci
npm run dev
npm run build
```

### Concept / presentation site (`chess/`)
React + TypeScript + Vite site containing the design overview, roster, animation lab, board demo, UI/HUD and pipeline sections.

```bash
cd chess
npm ci
npm run dev
npm run build
```

See `chess3d/README.md` and `chess3d/docs/ART_DIRECTION.md` for implementation notes and art direction.

> Import note: this branch currently contains metadata scaffolding only. The complete source/assets import has not yet landed; see PR #1 discussion for review notes.