# Agents — half-second

> Repo-level contract. The constellation-wide rules are in `~/work/capp/spine/AGENTS.md`.
> This file is only what is true about **this** repo.

## Stack

One `index.html`, inline CSS and JS, no framework, no build, no dependencies.
Two self-hosted typefaces in `fonts/` under the OFL.

## Commands

```bash
python3 -m http.server 5252 --directory .   # http://localhost:5252 — the whole test is: open it, poke it
```

## Do not touch

`fonts/` (licensed subsets copied from `chronology`). The `SPECIMEN` constant
is data, not code; changing a number there is a design decision.

## Invariants

- Zero network requests. `grep -n "https\?://" index.html` must return nothing.
- The instrument never decides. No score against a norm the reader did not pick,
  no recommendation, no "you should".
- The meters never reset except on Reset. That asymmetry is the argument.
- Reduced motion degrades to stepped states, never to nothing.

## Traps

- SVG presentation attributes cannot resolve CSS variables. Colour inside the
  `<svg>` goes through `style=""` or a class, never `fill="var(--x)"`.
- The dev server is registered in `~/.claude/launch.json` as `half-second`, not
  in a local `.claude/`; the preview tool only reads the global file.

## This node

| | |
|---|---|
| **Role** | instrument · CAPP |
| **Local** | `~/work/capp/instruments/half-second` |
| **GitHub** | — not pushed |
| **Live** | — not deployed |
| **Surface** | private until Param says otherwise |

The screen moves you before you know it, and you narrate afterwards.
