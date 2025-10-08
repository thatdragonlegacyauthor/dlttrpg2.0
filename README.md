# DLT TTRPG 2.0

A ruleset and world content for a tabletop role-playing game (TTRPG), stored as structured JSON for portability and tooling.

## Project structure
- `system/` — Core rules, mechanics, traits, actions, equipment, etc.
- `world/` — Setting data: locations, factions, items, lore.
- `characters/` — Example characters, NPCs, and archetypes.
- `campaign/` — Adventures, quests, encounters.
- Root JSON files — Indexes and helper data (e.g., `master_index.json`, `gm_ai_instructions.json`).

## Getting started
1. Clone the repo and create a feature branch.
2. Make changes to JSON or docs.
3. Run JSON validation locally:
   - If you have `jq`, you can validate a file: `jq -e . < file.json>`
4. Open a pull request. Our CI validates all JSON files automatically.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines, branching, PR flow, and conventions.

## Code of Conduct
Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security
If you discover a security issue, please follow the steps in [SECURITY.md](SECURITY.md).

## Roadmap
We track improvements using issues and a project board. See open issues and plans in the repository.

## Licensing
No license has been selected yet. Until a license is chosen, all rights are reserved. We will add a license via a future decision tracked in issues.
