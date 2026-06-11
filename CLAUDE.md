# CLAUDE.md

Guidance for Claude Code and agents working in this repository.

This is a **static site**: a single hand-edited `index.html` plus image assets. There is no build step, no `package.json`, and no framework. Edit `index.html` directly.

## FOB Standards (agents must follow)

- Static site: plain HTML/CSS/JS in `index.html`. No build step — do NOT add npm/Vite/Next.js tooling or a build pipeline. (The usual "npm run build must pass" rule does not apply here.)
- No em dashes anywhere in rendered content. En dashes for ranges fine.
- Unattended runs deliver via PR only; never merge.
- Never commit secrets or .env files.
