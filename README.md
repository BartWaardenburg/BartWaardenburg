# Bart Waardenburg

I build open-source developer tools in Rust for the TypeScript and JavaScript ecosystem.

## fallow

[**fallow**](https://github.com/fallow-rs/fallow) is codebase intelligence for TypeScript and JavaScript. It reads a repository as one graph and reports:

- a health score, complexity hotspots, and refactoring targets
- duplication across code, styles, and components
- architecture boundary violations and circular dependencies
- design-system drift in CSS and CSS-in-JS
- unused files, exports, types, and dependencies
- the risk that a pull request adds, as a CI gate

The analyzer is deterministic, so CI, editors, and coding agents can build on its output. It is free and MIT licensed. Fallow Cloud, an optional paid add-on, merges production runtime coverage into the same reports.

```sh
npx fallow          # health, duplication, and unused code in one run
npx fallow audit    # the findings that your pull request introduces
npx fallow health   # health score, hotspots, and refactoring targets
```

It ships as a CLI, a GitHub Action, a GitLab template, a VS Code extension, and LSP and MCP servers. Docs: [docs.fallow.tools](https://docs.fallow.tools).

## Also in the fallow-rs organization

- [**srcmap**](https://github.com/fallow-rs/srcmap): a source map SDK for Rust tooling. It parses, generates, remaps, and composes source maps (ECMA-426).
- [**oxc-coverage-instrument**](https://github.com/fallow-rs/oxc-coverage-instrument): Istanbul-compatible coverage instrumentation on the Oxc AST.

## Other projects

- [**spaceship-mcp**](https://github.com/BartWaardenburg/spaceship-mcp): an MCP server for the Spaceship registrar (domains, DNS, contacts).
- [**recraft-mcp-server**](https://github.com/BartWaardenburg/recraft-mcp-server): an MCP server for image generation with the Recraft API.

---

[waardenburg.dev](https://waardenburg.dev) · [X](https://x.com/bartwaardenburg) · [LinkedIn](https://linkedin.com/in/bartwaardenburg) · [Sponsor](https://github.com/sponsors/BartWaardenburg)
