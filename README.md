# Bart Waardenburg

Fast tools for slow problems. I build Rust-native developer tooling for the JavaScript ecosystem.

### fallow

Codebase analyzer for JS/TS. Finds unused code, circular dependencies, code duplication, complexity hotspots, and architecture boundary violations. 3-40x faster than knip, 16-33x faster than jscpd.

```sh
npx fallow            # all analyses — zero config, sub-second
npx fallow dead-code  # unused files, exports, deps
npx fallow dupes      # clone detection
npx fallow health     # complexity + maintainability
npx fallow boundaries # architecture boundary enforcement
```

90 framework plugins, VS Code extension, LSP, MCP server, GitHub Action, GitLab CI template. [Docs](https://docs.fallow.tools) | [Repository](https://github.com/fallow-rs/fallow)

### Other projects

**[srcmap](https://github.com/BartWaardenburg/srcmap)** — Source map SDK for Rust. ECMA-426 compliant. |
**[oxc-coverage-instrument](https://github.com/nicolo-ribaudo/oxc-coverage-instrument)** — Oxc-based Istanbul coverage instrumenter. |
**[recraft-mcp-server](https://github.com/BartWaardenburg/recraft-mcp-server)** — AI image generation via MCP. |
**[spaceship-mcp](https://github.com/BartWaardenburg/spaceship-mcp)** — Domain management via MCP.

---

[waardenburg.dev](https://waardenburg.dev) | [@bartwaardenburg](https://twitter.com/bartwaardenburg) | [LinkedIn](https://linkedin.com/in/bartwaardenburg) | [Sponsor](https://github.com/sponsors/bartwaardenburg)
