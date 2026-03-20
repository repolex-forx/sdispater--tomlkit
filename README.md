# Repolex Knowledge Graph of sdispater/tomlkit

RDF knowledge graph data for [sdispater/tomlkit](https://github.com/sdispater/tomlkit), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download sdispater/tomlkit
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 0c5f51fdb7e020b97708fc3a941921d4e562d180.nq.gz
│   ├── 166e8e54a30f7d71878e7f0b9a651daba48f5614.nq.gz
│   ├── 355657f9040295ca071bb2da0949cbb591f43400.nq.gz
│   ├── 38856c8737a8e8066b1204d85b676883e2a292c2.nq.gz
│   ├── 3b416664dda4bc7e2d01ed0da80d6e5a8824c07d.nq.gz
│   ├── 3c7b9ea76e668816ea43e3f61cfd7b3c02566b4d.nq.gz
│   ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
│   ├── 469c309f3a5ece008f0e5b7e1d0be8579ab16f2e.nq.gz
│   ├── 47b30c3b0911d41ef9aa421bfaad0b1166afae54.nq.gz
│   ├── 5017d8541e4a5f71c721f04e674cad98c51dec26.nq.gz
│   ├── 522fb4681547540a95ce29a1aee087685221d7cd.nq.gz
│   ├── 598612dc3a01f025700aab4b3e7cc7713f990a64.nq.gz
│   ├── 5cfc8d08583c4e12d5b85170849f8369ea177639.nq.gz
│   ├── 5f9cc33b409adb539f9330e312d661096da73ccd.nq.gz
│   ├── 698d1ac4397041767e344619fde7b855f4a55540.nq.gz
│   ├── 6b719683f29858a65cc0a12f743e49bb5d80fcb5.nq.gz
│   ├── 6e03fdca957857a153848080ed1adad17126818c.nq.gz
│   ├── 6f9fb055eb4065ad99d9d0886814064e4c3142fc.nq.gz
│   ├── 7210cc7c9bb341a4e2ba33e6b3704b7d343fbf22.nq.gz
│   ├── 7cc9ba63ce336a373e50e7c5c3f95cdb1cba2f93.nq.gz
│   ├── 816cc97aab18c89f3159f5c4d3cebe1d7755e149.nq.gz
│   ├── 8aaf68eaf3a25a460c1ec764fe97ea60d27b06a1.nq.gz
│   ├── 8d8d6608b4fbba10e97324a042ec55c8d32bf2b4.nq.gz
│   ├── 995e71673d7fb1d7356dca3c8f44d4f0929f1afc.nq.gz
│   ├── 998c46d56475a4ca4da84b00052576d42b7a4232.nq.gz
│   ├── a6671e5075d00ca3a0ee1bf9adff45e01e5d03a4.nq.gz
│   ├── b2f3c492116bb4c9e5071d488ce640c1e3d59497.nq.gz
│   ├── b308f1203e4f7e9c29486110dd51c203993de0d3.nq.gz
│   ├── b485e3029e21b2d93ca779797cb5ab54f002126d.nq.gz
│   ├── c2a68470604e1935cf9b84927cad15fdc40ac28f.nq.gz
│   ├── e4b45c718ed8120af9d724dc7dfc707455c7fb01.nq.gz
│   ├── e610f9d98cbc04ce7b75e647ec50fb830ecdda98.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef7e9ac1708624da87aef533cac83a19f3c52212.nq.gz
│   ├── f5999195fc40b12165d29435bf65178032934b24.nq.gz
│   ├── f84063b3e562e1f70b37708a374feef801f4a983.nq.gz
│   └── fb33779d3a3af651e9d370d5135ce336548b1d27.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 43 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[sdispater/tomlkit](https://github.com/sdispater/tomlkit)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
