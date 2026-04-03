# Directus

[![Forma](https://img.shields.io/badge/forma-stable-brightgreen.svg)](https://github.com/forma-tools/forma) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> Directus CMS - schema, migrations, users, extensions.

**Origin:** Vendor (1st-party) - [https://github.com/directus/directus](https://github.com/directus/directus)

## Install

```bash
npm install directus
```

## Quick Start

```bash
npx create-directus-project my-project
cd my-project
npx directus start
```

## Forma Protocol

This tool follows the [Forma Protocol](https://github.com/forma-tools/forma/blob/main/docs/protocol/00-index.md) v0.7.0.

- **Type:** Vendor CLI
- **Auth:** `directus auth login`
- **Output:** `--json` flag for structured output
- **Exit codes:** Semantic (0 success, 1 general error)
