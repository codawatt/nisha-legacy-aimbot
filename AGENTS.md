# AGENTS.md

## Scope

This repository is a small Borderlands 2 Python SDK add-on for LJBreeze's Nisha character mod.

## Development rules

- Preserve compatibility with the expected Borderlands 2 Python SDK / Willow2 Mod Manager environment.
- Keep changes narrowly scoped to the legacy Showdown-style auto-aim behavior.
- Do not refactor unrelated upstream behavior without a clear reason.
- Read the existing implementation before changing hooks, Unreal object paths, or SDK calls.
- Prefer small, testable changes over broad rewrites.
- Clearly call out assumptions that cannot be verified outside the game runtime.
- Do not remove or weaken attribution to LJBreeze.

## AI-assisted development

AI tools may be used for code exploration, implementation suggestions, debugging, and documentation. Suggested code must be reviewed and tested by the maintainer before release.
