# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](https://github.com/awesome-copilot/awesome-copilot/graphs/contributors)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a community-driven fork of [github/awesome-copilot](https://github.com/github/awesome-copilot), maintained to extend and improve the collection of resources for GitHub Copilot users.

> **Personal note:** I forked this for my own reference while learning how to use Copilot more effectively. My main interest is in prompt files and copilot instructions for Go and TypeScript projects. Most useful sections for me: [Copilot Instructions](#copilot-instructions) and [Prompt Files](#prompt-files).

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Prompt Files](#prompt-files)
- [Agent Workflows](#agent-workflows)
- [Extensions & Plugins](#extensions--plugins)
- [My Notes](#my-notes)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom `.github/copilot-instructions.md` files that tailor Copilot's behavior for specific languages, frameworks, or workflows.

- See [.github/copilot-instructions.md](.github/copilot-instructions.md) for the project's own instructions as an example.

## Prompt Files

Reusable `.prompt.md` files for common development tasks.

- Explore the community-submitted prompts in the [marketplace](.github/plugin/marketplace.json).

> **My picks:** The Go test generation prompt and the TypeScript refactor prompt have been the most useful to me personally.

## Agent Workflows

Agentic workflow definitions for multi-step Copilot tasks.

- [Agentic Workflows Guide](.github/agents/agentic-workflows.agent.md) — Best practices and examples for building agentic workflows with GitHub Copilot.

## Extensions & Plugins

A curated list of GitHub Copilot extensions available in the marketplace.

- Browse the full list in [marketplace.json](.github/plugin/marketplace.json).

---

## My Notes

Personal reminders and findings as I work through this repo:

- The Go test generation prompt works best when your functions have clear input/output signatures.
- For TypeScript, pairing the refactor prompt with strict mode enabled gives much cleaner suggestions.
- TODO: try the agentic workflow examples with a real side project.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

1. Fork this repository.
2. Add your resource to the appropriate section.
3. Submit a pull request with a clear description.

This project follows the [all-contributors](https://allcontributors.org/) specification. Contributions of any kind are welcome!

## License

[CC0 1.0 Universal](LICENSE) — Public Domain Dedication.
