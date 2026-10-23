# PKM Demo

[![GitHub](https://img.shields.io/badge/GitHub-iwe--org%2Fpkm--demo-blue)](https://github.com/iwe-org/pkm-demo)
[![Browse](https://img.shields.io/badge/Browse-iwe.pub-green)](https://iwe.pub/pkm-demo/)

Personal Knowledge Management demonstration using IWE.

This graph showcases IWE's capabilities for managing interconnected notes, tasks, and knowledge using markdown files with block references.

## Structure

- `graph/` - Markdown documents managed by IWE
- `.iwe/` - IWE configuration

## Usage

Requires the [IWE](https://github.com/iwe-org/iwe) CLI. All `iwe` commands must be run from this directory:

```bash
iwe find                    # List all documents
iwe retrieve -k index       # View index document
iwe tree                    # Show document hierarchy
```

## Related Projects

- [IWE](https://github.com/iwe-org/iwe) — CLI for markdown document graphs
- [iwe.md](https://iwe.md) — Documentation and website
