# Bart Waardenburg

I build Rust-native developer tooling for the JavaScript and TypeScript ecosystem. Mostly: trustworthy signal about codebases, for the people and the agents that work on them.

## fallow

[**fallow**](https://github.com/fallow-rs/fallow) is codebase intelligence for JS/TS. It turns a repository into a deterministic quality report. There is no AI inside the analyzer: every finding is deterministic, typed, and traceable back to the code that produced it, which is why CI, editors, and AI coding agents can build on it.

In one pass it reports:

- Health and quality score, plus changed-code risk against your base branch
- Complexity hotspots and code duplication (clone families)
- Circular dependencies and architecture boundary violations
- Dead code: unused files, exports, types, and dependencies
- Feature-flag patterns

122 framework plugins, zero config, sub-second static analysis on most projects (a persistent cache makes warm runs faster still). The static layer is free and open source. An optional paid layer, **Fallow Runtime**, merges production coverage into the same report, so you can review hot paths and remove dead code with confidence.

```sh
npx fallow audit       # changed-code audit vs your base branch
npx fallow dead-code   # unused files, exports, types, dependencies
npx fallow health      # codebase health and quality score
```

Available as a CLI, VS Code extension, LSP, MCP server, GitHub Action, and GitLab CI template. Docs at [docs.fallow.tools](https://docs.fallow.tools).

## The fallow ecosystem

Building blocks, under the [`fallow-rs`](https://github.com/fallow-rs) org:

- [**srcmap**](https://github.com/fallow-rs/srcmap): source map SDK for Rust tooling. Parse, generate, remap, and compose. ECMA-426 compliant.
- [**oxc-coverage-instrument**](https://github.com/fallow-rs/oxc-coverage-instrument): Oxc-based Istanbul coverage instrumenter.

## Other projects

- [**recraft-mcp-server**](https://github.com/BartWaardenburg/recraft-mcp-server): MCP server for AI image generation via the Recraft API.
- [**spaceship-mcp**](https://github.com/BartWaardenburg/spaceship-mcp): MCP server for the Spaceship registrar (domains, DNS, contacts).

---

[waardenburg.dev](https://waardenburg.dev) · [Twitter](https://twitter.com/bartwaardenburg) · [LinkedIn](https://linkedin.com/in/bartwaardenburg) · [Sponsor](https://github.com/sponsors/bartwaardenburg)
