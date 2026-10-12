# Repolex Knowledge Graph of executablebooks/jupyter-cache

RDF knowledge graph data for [executablebooks/jupyter-cache](https://github.com/executablebooks/jupyter-cache), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/jupyter-cache
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9394eada9b8b16baf88451369b63ec09c70733c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9394eada9b8b16baf88451369b63ec09c70733c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00448c2f800e81ad99d909378be279e1ffcb5a96.nq.gz
│   ├── 01c876534cc9f90091717df4e93a297f8f29a10b.nq.gz
│   ├── 065f2c072f73a471dc73169eed3e4476553d1a4d.nq.gz
│   ├── 0bdf14e23034e6a7d367cdec1b93a82f09c243cd.nq.gz
│   ├── 0fc225207075f8e602c9f4277d2c24d08930753f.nq.gz
│   ├── 16df1283ccbc24cab469b34ea66ad0ad0091ab05.nq.gz
│   ├── 1f4eba3688597f69fd739a37878452dbc9804ed7.nq.gz
│   ├── 21756c231ce1cf27bfaaea0e1d1ff7889a3d3e0d.nq.gz
│   ├── 22f62c85ade8ca20e75567e9de256eaf15f669c9.nq.gz
│   ├── 2e98dbbc36fe318c84e07956d2b8160b187385b9.nq.gz
│   ├── 2f272daaf62b4e1d83ea863e57f57a54f7dcf8dc.nq.gz
│   ├── 31057a3a9dac491fbf2217f4be62a7f8d1f5b00c.nq.gz
│   ├── 31fa7704bf36f14957c837030b2ce2362a70cdfc.nq.gz
│   ├── 32a483e241a388711288859aeef590c622c16aa2.nq.gz
│   ├── 394678ce19385c2be39e7055cacf84a7fc38d419.nq.gz
│   ├── 41c846ea28ba347f24f098c9acc835d7d197df96.nq.gz
│   ├── 425552b032651aede2b6b5a0e499a52d4af631d5.nq.gz
│   ├── 42ecbd45fb042c6c1d41aaf465ef32bfc26fde12.nq.gz
│   ├── 431328503905d112df8d6d85ce745274e1b6f670.nq.gz
│   ├── 44fd69e16c99d8d97982bb63b4703932eb9135ac.nq.gz
│   ├── 4860968e673f592eb0d049eefe5adcda2238cb1e.nq.gz
│   ├── 4c19f614e424a5623c7265e53e3c8313a59d9e1b.nq.gz
│   ├── 50b7c58c843af9eb443c0fabfffe6ea6fafbbc2f.nq.gz
│   ├── 51ca6ed9315a11ec20d23734864198db936d3ffb.nq.gz
│   ├── 59020e2a489da9d1727466ebee6077cd1ac82f90.nq.gz
│   ├── 5f41fb21a1f105ca636c3f42dadef5c94dec731d.nq.gz
│   ├── 6e1b477c414a2dcdf0990ea6c77604bcb40eb850.nq.gz
│   ├── 74ee552810ef26cb8077666ab269a590be45526a.nq.gz
│   ├── 7579e1500e620b37c84831592adc616c444b3b18.nq.gz
│   ├── 783cc0ae7ce9094203cd5255e4827fee654d5210.nq.gz
│   ├── 786f83cd9e9f81b513c7dbf09e6de831e36b2b37.nq.gz
│   ├── 7968c349b5d05dfa91abe2eabe4555b66f82d9d4.nq.gz
│   ├── 79d229ba894259e0e178ef140ce6795cf872e510.nq.gz
│   ├── 7aae7db387229839fec8b99517deb1a36d71bfaa.nq.gz
│   ├── 7bbaf03edae9a63883e426fe98d3dd6b956119c3.nq.gz
│   ├── 7f2e9d5a63347ff9058a9186453d722bccad401e.nq.gz
│   ├── 84e8b119082209790a21542e279ab5317effbcdc.nq.gz
│   ├── 87bd10ef2ae9a9e72fb44ddb0a99ad532fd12638.nq.gz
│   ├── 914a4f5a233dede578264860912339428c96a3e1.nq.gz
│   ├── 937e1572bf9c424fed26583511d438618f37170d.nq.gz
│   ├── 9a106102ab1cb61c948841f5a76c69aad59d81da.nq.gz
│   ├── a5a0101ba336c457df16026177005b9e5ac662cf.nq.gz
│   ├── ae8a2148b774e36b3d85fe8e249f5ccd2bdd661b.nq.gz
│   ├── b546e0a640e4bff2a81218e2012eb747bdef73b2.nq.gz
│   ├── b54b4fa67de30f9a8b9a64e07f1f3047f90def0b.nq.gz
│   ├── d31b43604063bace071bb8bb48c45c5e7857a3cb.nq.gz
│   ├── dcb3e997d607bb672da596d05465d86649e9019e.nq.gz
│   ├── e467782994dcb33b68fa29d42f9ac4a306dd6131.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ed0e250b4466de21aec689111d6f409d4aeff0.nq.gz
│   ├── ee1717056ad9673416ca4b3405802422ca3d3576.nq.gz
│   ├── efa84d9b7d3287a4a1712569ab8c3fcfaf2e65d9.nq.gz
│   ├── f0f3f9af22504810740e206cac3ff92fb111dd5f.nq.gz
│   ├── f2e9e62b716610bbac1986d5fe1dbe0d5aa1d25d.nq.gz
│   ├── f4aad67fdcd0066a0a9738dbc5653f169e760dad.nq.gz
│   ├── f741d5296c20fddd80a467f0512dfd8222b124a1.nq.gz
│   ├── fa67cd8e9476a78b18aa8586d14b3496c4dde745.nq.gz
│   └── ff439bfe8b5182dd120ebd69af1ec2f76b699b4e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9394eada9b8b16baf88451369b63ec09c70733c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[executablebooks/jupyter-cache](https://github.com/executablebooks/jupyter-cache)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
