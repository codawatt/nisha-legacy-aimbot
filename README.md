# Nisha Legacy Aimbot

A small Borderlands 2 Python SDK add-on for **LJBreeze's Nisha playable-character mod**.

The goal is to bring the legacy auto-aim feel of Nisha's original **Showdown** action skill from *Borderlands: The Pre-Sequel* to the BL2 Nisha mod.

> This is an add-on / experiment, not the original Nisha mod.

## Credits

- **LJBreeze** — creator of the original Nisha playable-character mod for Borderlands 2. This project exists on top of / alongside that work.
- **Dragoș / codawatt** — legacy aimbot adaptation / experiment.
- **LLM assistance** — used during development and iteration of the adaptation. Final integration and testing remain the responsibility of the project author.

## Installation

1. Make sure the Borderlands 2 Python SDK / Willow2 Mod Manager setup required by the Nisha mod is installed.
2. Open your `sdk_mods` directory.
3. Create a folder for this add-on, for example:

   ```text
   sdk_mods/
   └── nisha_aimbot/
       └── __init__.py
   ```

4. Put this project's `__init__.py` inside that folder.
5. Start Borderlands 2 and enable the mod from the Mods menu if required by your SDK setup.

## Repository layout

```text
nisha-legacy-aimbot/
├── README.md
├── AGENTS.md
├── .gitignore
└── sdk_mods/
    └── nisha_aimbot/
        └── __init__.py
```

## AI-assisted workflow

This project was developed with LLM assistance for code exploration, implementation ideas, debugging, and iteration.

AI assistance is treated as a development tool rather than an authorship substitute: generated or suggested changes should be reviewed and tested against the game/mod environment before release.

## Status

Experimental / work in progress.

## Original mod

Nisha - Full Playable Character for Borderlands 2, by **LJBreeze**.

This repository does not claim authorship of the original Nisha mod or its assets.
