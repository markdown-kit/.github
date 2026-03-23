<div align="center">

# markdown-kit

**Composable tooling for Markdown, MDX, MDC, and MDD workflows**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D22-339933.svg?logo=node.js&logoColor=white)](https://nodejs.org/)
[![pnpm](https://img.shields.io/badge/pnpm-workspace-F69220.svg?logo=pnpm&logoColor=white)](https://pnpm.io/)
[![npm](https://img.shields.io/npm/v/@markdownkit/markdownkit.svg?logo=npm&label=%40markdownkit%2Fmarkdownkit)](https://www.npmjs.com/package/@markdownkit/markdownkit)
[![GitHub stars](https://img.shields.io/github/stars/markdown-kit/markdownkit.svg?logo=github)](https://github.com/markdown-kit/markdownkit/stargazers)

</div>

---

## Overview

**markdown-kit** is an ecosystem for writing, linting, validating, and transforming markdown-first content across docs and professional documents.

**Why markdown-kit?**

- Unified workflows for `.md`, `.mdx`, `.mdc`, and `.mdd`
- Opinionated quality pipeline (`oxfmt` + `oxlint` + remark tooling)
- Editor-native ergonomics via LSP and VS Code extension
- Seamless output pipeline from markdown content to DOCX

## Key Features

<table>
<tr>
<td width="50%">

### Authoring & Quality

- Opinionated markdown formatting and linting
- MD/MDX diagnostics with source remapping
- MDD semantic validation for structured documents
- Shared quality scripts across repositories

### Ecosystem Interop

- CLI + library-first package design
- Reusable remark plugins and schema-driven validation
- Language server support for real-time feedback
- VS Code integration for daily editing workflows

</td>
<td width="50%">

### Document Workflows

- Markdown/MDX/MDC support for docs content
- MDD support for business/semantic document structure
- Markdown ↔ DOCX conversion utilities
- Preview and validation tooling for document pipelines

### Developer Experience

- Node.js 22+ baseline across packages
- pnpm-centric scripts and package management
- Consistent repo conventions (`format:check`, `lint:ci`, `check`)
- Public npm packages with focused responsibilities

</td>
</tr>
</table>

## Tech Stack

<div align="center">

| Technology | Role |
|------------|------|
| ![Node.js](https://img.shields.io/badge/Node.js-22%2B-339933?style=for-the-badge&logo=node.js&logoColor=white) | Runtime baseline |
| ![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white) | Type-safe package development |
| ![pnpm](https://img.shields.io/badge/pnpm-workspace-F69220?style=for-the-badge&logo=pnpm&logoColor=white) | Package management |
| ![remark](https://img.shields.io/badge/remark-unified-111111?style=for-the-badge) | Markdown/MDX processing pipeline |
| ![VS Code](https://img.shields.io/badge/VS%20Code-Extension-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white) | Editor integration |

</div>

## Repositories & Packages

### Core Packages

| Repository | Package | Purpose |
| --- | --- | --- |
| [`markdownkit`](https://github.com/markdown-kit/markdownkit) | `@markdownkit/markdownkit` | Opinionated markdown formatter/linter CLI |
| [`oxlint-mdx`](https://github.com/markdown-kit/oxlint-mdx) | `@markdownkit/oxlint-mdx` | Oxlint-first MD/MDX linting with source-remapped diagnostics/fixes |
| [`remark-mdd`](https://github.com/markdown-kit/remark-mdd) | `@markdownkit/remark-mdd` | Remark plugins + validation primitives for MDD |
| [`mdd`](https://github.com/markdown-kit/mdd) | `@markdownkit/mdd` | MDD preview/validation CLI for professional document workflows |
| [`md-docx`](https://github.com/markdown-kit/md-docx) | `@markdownkit/md-docx` | Markdown ↔ DOCX conversion library + CLI |

### Editor Tooling

| Repository | Package | Purpose |
| --- | --- | --- |
| [`mdk-lsp`](https://github.com/markdown-kit/mdk-lsp) | `@markdownkit/lsp` | Language Server for markdown + MDD diagnostics/formatting |
| [`mdk-vscode`](https://github.com/markdown-kit/mdk-vscode) | `mdk-vscode` | VS Code extension powered by Markdownkit + LSP |

## Quick Start

<table>
<tr>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:package.svg?color=%236366f1" width="48"><br>
<strong>1. Install</strong><br>
<code>npm i -D @markdownkit/markdownkit</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:sparkles.svg?color=%236366f1" width="48"><br>
<strong>2. Format</strong><br>
Run <code>markdownkit format</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:check-check.svg?color=%236366f1" width="48"><br>
<strong>3. Lint</strong><br>
Run <code>markdownkit lint</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:rocket.svg?color=%236366f1" width="48"><br>
<strong>4. Integrate</strong><br>
Add LSP / VS Code extension
</td>
</tr>
</table>

### Example

```bash
npm i -D @markdownkit/markdownkit
npx markdownkit format
npx markdownkit lint
```

## Documentation

<div align="center">

| Resource | Link |
|----------|------|
| Markdownkit CLI | [github.com/markdown-kit/markdownkit](https://github.com/markdown-kit/markdownkit) |
| oxlint-mdx | [github.com/markdown-kit/oxlint-mdx](https://github.com/markdown-kit/oxlint-mdx) |
| MDD CLI | [github.com/markdown-kit/mdd](https://github.com/markdown-kit/mdd) |
| remark-mdd | [github.com/markdown-kit/remark-mdd](https://github.com/markdown-kit/remark-mdd) |
| md-docx | [github.com/markdown-kit/md-docx](https://github.com/markdown-kit/md-docx) |
| VS Code Extension | [github.com/markdown-kit/mdk-vscode](https://github.com/markdown-kit/mdk-vscode) |

</div>

## Contributing

<div align="center">

[![Issues](https://img.shields.io/github/issues/markdown-kit/markdownkit.svg?logo=github)](https://github.com/markdown-kit/markdownkit/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/markdown-kit/markdownkit.svg?logo=github)](https://github.com/markdown-kit/markdownkit/pulls)

</div>

Contributions are welcome across all markdown-kit repositories.

| Type | Action |
|------|--------|
| Bug report | [Open an issue](https://github.com/markdown-kit/markdownkit/issues/new) |
| Feature request | [Start a discussion](https://github.com/markdown-kit/markdownkit/discussions) |
| Package contributions | [Browse organization repos](https://github.com/markdown-kit) |

## License

All markdown-kit repositories are released under the **MIT License** unless noted otherwise in a specific project.

---

<div align="center">

[![GitHub Organization](https://img.shields.io/badge/GitHub-markdown--kit-111111?style=for-the-badge&logo=github)](https://github.com/markdown-kit)
[![npm Scope](https://img.shields.io/badge/npm-%40markdownkit-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/search?q=%40markdownkit)

<br>
<sub>Built with care by the markdown-kit maintainers</sub>

</div>
