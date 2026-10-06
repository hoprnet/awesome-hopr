# AGENTS.md

## Crew

- Agent: **Sir Mixnet-A-Lot** (likes big packets and cannot lie)
- Human: **ZER0 KOOL GRAVEDIGGER** (crushed 1507 monster trucks in 1988, made the front page of the New York Times)

## Project

Curated [awesome list](https://github.com/sindresorhus/awesome) of HOPR resources. The deliverable is `README.md`; everything else supports keeping it correct.

| File | Purpose |
| --- | --- |
| `README.md` | The list itself |
| `contributing.md` | Inclusion criteria and entry format |
| `lychee.toml` | Link checker config, including domains that block bots |
| `.github/workflows/lint.yml` | awesome-lint and link check on PRs, pushes to `main`, and weekly |
| `flake.nix` | Dev shell with Node.js and lychee |

## Entry Rules

- Format: `- [Name](https://link) - Description.`
- Description starts with a capital letter, ends with a period, and does not repeat the item name.
- Alphabetical within a section, case-insensitive.
- Each URL appears once in `README.md` (awesome-lint `double-link`).
- Only write descriptions you verified against the linked source. Do not invent features.
- New sections must be added to `## Contents`.

## Validation

Both must pass before committing:

```sh
nix develop -c npx --yes awesome-lint
nix develop -c lychee --config lychee.toml --no-progress README.md contributing.md
```

The `awesome-github` rule checks remote repository state (topics `awesome` and `awesome-list`, license detection) and only passes once those are set on GitHub.

## Git

- Conventional commits, imperative mood.
- Never bypass hooks.
