---
routes:
  - README.md - what OKF is, how this toolchain ships (plugin, skills, GitHub Action, MCP server), and install instructions.
  - CHANGELOG.md - release history.
  - .okf/index.md - this repo's own OKF bundle: its architecture and decisions, self-documented in the format it implements.
---

This is a standalone clone of **okf**, the Claude Code-native toolchain for
the Open Knowledge Format — agents, skills, an MCP server and a GitHub
Action for authoring, validating, backfilling and visualizing OKF knowledge
bundles (portable markdown + YAML frontmatter).

It lives at `~/.local/src/open-knowledge-plugin`, with `origin` =
`skogai2/open-knowledge-plugin` and `upstream` = `scaccogatto/okf-skills`. It
was once a submodule of the skogai monorepo under the name `ofk-claude`;
that's now one line of history, not its current shape — this is a separate
repo with its own remotes, not a path or submodule inside `skogai`.

There's no AGENTS.md, CLAUDE.md, or CONTRIBUTING doc in this repo; the README
is the primary entry point for both humans and agents, and the project
documents its own architecture and decisions in `.okf/` rather than in prose
docs.

The skogai-specific reason this fork exists under a different name than
upstream is undocumented in the repo itself — nothing here records the
intent behind forking it.
