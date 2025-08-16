# AGENTS Guidelines

This repository hosts a single-page Werewolf host panel implemented with vanilla **HTML**, **CSS**, and **JavaScript**. All functionality resides in `index.html`.

## Coding conventions
- Keep the project dependency-free; do not introduce external libraries or build steps.
- Write modern ES6 JavaScript and inline CSS/JS within `index.html`.
- Use descriptive camelCase names for variables and functions.
- Favor clarity over brevity; comment complex logic (comments may be in Chinese).

## Testing
- If a `package.json` with test scripts is present, run `npm test` and ensure it passes before committing.
- Currently no automated tests exist; running `npm test` should error if `package.json` is missing—log this result.

## Documentation
- Update `README.md` when adding or changing features so that the usage guide remains accurate.

## Commit guidance
- Use conventional commit messages (e.g., `feat:`, `fix:`, `docs:`).
- Keep commit history linear; avoid creating new branches.
