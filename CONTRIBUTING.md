# Contributing to DLT TTRPG 2.0

Thanks for your interest in contributing! This document outlines how to propose changes and the conventions we follow.

## Ways to contribute
- Report bugs or data problems using the Bug Report issue template.
- Suggest features, rules, content, or improvements using the Feature Request template.
- Submit pull requests for fixes and enhancements.

## Branching and PRs
- Create a feature branch from `main`.
- Keep PRs focused and small when possible.
- Fill out the PR template, including testing/validation notes.
- CI must pass (JSON validation) and at least one review is required.

## JSON conventions
- Valid JSON only; no comments in JSON files.
- Use 2-space indentation.
- Keep objects and arrays consistently ordered where it helps readability.
- Prefer snake_case for keys (unless a schema dictates otherwise).

## File and directory layout
- Place core rules in `system/`, setting content in `world/`, examples in `characters/`, and adventures in `campaign/`.
- Large additions should include an index entry update if relevant (e.g., `master_index.json`).

## Commit messages
- Use present tense, imperative mood: "Add X", "Fix Y".
- Reference issues when applicable (e.g., "Closes #123").

## Local validation
- Validate JSON with `jq -e . < file.json>`.

## Questions
Open a Discussion (if enabled) or an issue if you're unsure how to proceed.
