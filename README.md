# Repolex Knowledge Graph of karpetrosyan/httpx-aiohttp

RDF knowledge graph data for [karpetrosyan/httpx-aiohttp](https://github.com/karpetrosyan/httpx-aiohttp), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download karpetrosyan/httpx-aiohttp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22a58c53767371e9626ca16faf25d593388a624e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22a58c53767371e9626ca16faf25d593388a624e
│           └── chunk-001.nq.gz
├── blob
│   ├── 09c05e76cdfb8a37cd82fedeb3874633e8c28a0c.nq.gz
│   ├── 0a197900e25d259ab4af2e31e78501787d7a6daa.nq.gz
│   ├── 0d8cd400879d1b608e0ec567b797b2767313503f.nq.gz
│   ├── 1187fcb1da141babe55a69b14b3824321c03df22.nq.gz
│   ├── 1b3859cc5b1e1429015bb2ba540f557aad6cbdc4.nq.gz
│   ├── 1b7e7e19e5e48cf676c973cbe7518739bf61c733.nq.gz
│   ├── 263bfe106d99205a308d3a0ccbf4b2a55caeff5d.nq.gz
│   ├── 2a9654495cc9ec467f9d498f1bc8c522fd1aafdb.nq.gz
│   ├── 2cc9800e6869596464a5df16dcd2fd3ec5ba8a98.nq.gz
│   ├── 2ed218e4b7ccce1ced26c744ea659e0fe65628d4.nq.gz
│   ├── 3029b3b72c75500dc9a10902b2f1c03eb7333cb1.nq.gz
│   ├── 43262f96ea81ff892fb68b88ade71a849b51d0ae.nq.gz
│   ├── 44fd02822b69b741efae779cb10bbb3bd915cd4b.nq.gz
│   ├── 47db6a88bd8463d2f2468d03d2735915b5c4949f.nq.gz
│   ├── 5257fdd32ea3e1bcc43b44829c32785d80107346.nq.gz
│   ├── 55b091e1cfcc1e7d0352517e406861776c5a7f94.nq.gz
│   ├── 56a7803e661b86d74fdffd5e2b3fa593ce3e4046.nq.gz
│   ├── 57f5e3218837b2c26c7ee38b5bc51037471905e9.nq.gz
│   ├── 58938a9fecd578a65e9ccae7e368292b1b326c47.nq.gz
│   ├── 5af8cf6db78359d3c285de8e0e972918bccce3ad.nq.gz
│   ├── 5bec43f6f99b8b648c360445a3b1984d0afa291f.nq.gz
│   ├── 6587551098ec57deddbc9cf5ead7b387ff22b7ce.nq.gz
│   ├── 69d989b0539f821070da91aaa0c048380f633475.nq.gz
│   ├── 95c95043479480d63cbaf8f01be63cc700bed7df.nq.gz
│   ├── 96bcd938b5776c1fe21d647667e8966f6e965288.nq.gz
│   ├── 9de0aff8a2701570702a7bfe27ffbf9ffd5359f9.nq.gz
│   ├── a96139ea97c2718d6f8d5c819b570a98dab2ebf7.nq.gz
│   ├── acf052ae3808f65d4695b1c1324bf6e39e58b72e.nq.gz
│   ├── b08d4bf1929a76f65ab02e34c8d3b45874e72825.nq.gz
│   ├── b12a874e17c98309a41955e5f9d9745effa4aa0c.nq.gz
│   ├── bd28b9c5c27e0dfa60da94179ec9b23f2be8be0c.nq.gz
│   ├── d1531a45c1b752470c93cd8a7e2feda76783f87b.nq.gz
│   ├── d32919142a896ca86a59f793e508007aeca39034.nq.gz
│   ├── d5e61f85f3c55549fa93352d2a471f4217805d6f.nq.gz
│   ├── d6b9331c63254bac93712885186736b8fec75e11.nq.gz
│   ├── d76520492b2258e2df5e2367e3cca24129ec0fcc.nq.gz
│   ├── da7925d7c391f549a0fa77651ffd8a1416dea130.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e894b380c3d62770b5a936fe4c342f067c0494e7.nq.gz
│   ├── ee2c60388111bafb5765951b9a3ed61746a26921.nq.gz
│   ├── f12539fab7e0387b60459b9c44a839b0fbf99850.nq.gz
│   ├── f9c285fdcdfbd3037da2f3c1533125853fc307ae.nq.gz
│   └── fa3828fbc2c96747996a37b4b1942d24f97b7699.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22a58c53767371e9626ca16faf25d593388a624e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[karpetrosyan/httpx-aiohttp](https://github.com/karpetrosyan/httpx-aiohttp)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
