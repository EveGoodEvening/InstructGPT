# AGENTS.md

## Lessons

- Commit messages must not contain Claude/AI attribution lines (e.g. `Co-Authored-By: Claude ...`); a PreToolUse hook blocks such commits.
- Commit messages follow Conventional Commits (`feat: ...`, `fix: ...`, `docs: ...`).
- The Artifact publish wraps pages in a doctype/head/body skeleton; local copies of artifact HTML (e.g. `index.html`) need that skeleton and `body{margin:0}` added by hand.
