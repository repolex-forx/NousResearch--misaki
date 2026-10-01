# Repolex Knowledge Graph of NousResearch/misaki

RDF knowledge graph data for [NousResearch/misaki](https://github.com/NousResearch/misaki), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/misaki
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f03fd2be7346952a83d3d4845c217fc7667f322d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f03fd2be7346952a83d3d4845c217fc7667f322d.nq.gz
│   └── repolex
│       └── f03fd2be7346952a83d3d4845c217fc7667f322d
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ef913ef16c36d390c24bd6df05b3625ab3b868.nq.gz
│   ├── 0737a248313217ee45d0b448f6c8a5713e299fc4.nq.gz
│   ├── 0bf13a97e1a6a429743b60a08df11ea44801763e.nq.gz
│   ├── 10148a3cf137ebaf7b63c18a7806dadad227ecb1.nq.gz
│   ├── 121ba0c4a4ed40d284a58f9fd1fcaa2003613df0.nq.gz
│   ├── 1250e96ca4d1b163edca87da844fab0b173d1d02.nq.gz
│   ├── 15201acc113da01edf6fa2fb2708b2e9076b6bc5.nq.gz
│   ├── 1b6d220c5d45d1603fee47f1842c07624217807d.nq.gz
│   ├── 1e3dc4ade72124541f6a33dec4b7fc24e9941a82.nq.gz
│   ├── 1f3d0496f5680737efd42986b8643eba54e7ad2a.nq.gz
│   ├── 211a322d65c83bacbb167402b7f21d59af9027bb.nq.gz
│   ├── 21e3987ddecff2e48cdf2b0334e6113658aa49ea.nq.gz
│   ├── 222c170d5dd1037c2085985000be945984164f25.nq.gz
│   ├── 226dfd7cb5734dfd87698db0139267d8c47d12b6.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27f22e97880baeb76e02752b22d29c0bc46a6c6c.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 4033697d9ac102288af0550730dfa1da3f388cf4.nq.gz
│   ├── 438d95b16ce2fe3fb26a4e257b9bfdc27c7c62b7.nq.gz
│   ├── 43e2270bc13822a795dea03083c5df32b1334a16.nq.gz
│   ├── 4ade11ae3b36e96269d511c5ec03f147e9ea9adf.nq.gz
│   ├── 4ef629467cacab81f8741985a74066a0710e72eb.nq.gz
│   ├── 50566c83464a36fa03027f98706a90dfc8cbe1b3.nq.gz
│   ├── 50b4f3abcef04559fffd84a5c3ea74f849d17c1d.nq.gz
│   ├── 51835112603c1a8c31052285276f138b8c5a74d6.nq.gz
│   ├── 53a0156dfaf20ff0df6a0efae9934cef3dac0af0.nq.gz
│   ├── 55b570b28b9e7c6ccc84b30becc1fbf9aba6d3b1.nq.gz
│   ├── 5f67f700ab6a890ae8f403afd6048e9dce4ac65b.nq.gz
│   ├── 6423ad74a5c9a92df35aebf04bebdf4050a292de.nq.gz
│   ├── 66b27ab8a2ee54f5f4ebff690ba50fef96398e5d.nq.gz
│   ├── 6790d7eabb25aceca3aa5b6b0e7cdb367ebba536.nq.gz
│   ├── 6c695893492a8ee44813f1c59a8855b6f33a593e.nq.gz
│   ├── 725d6a141c5cf8ef24b6637887b42c98dd70557b.nq.gz
│   ├── 74a4ef3aff834e52e7e268483b0bd2a7fba5fc07.nq.gz
│   ├── 7576524a9b0df137b6eb7e30a4a79baf945866c4.nq.gz
│   ├── 79ec316c035f5d442be65c4e3eb8bb929e7a3071.nq.gz
│   ├── 87fdeeaa99d3be7c793ead0529f2d8b5513be7a9.nq.gz
│   ├── 886bba3be105e53ab2eb548b32c87875e451703b.nq.gz
│   ├── 8a8ef9ee5f56ef49eaef63a6b763291bfb49fab6.nq.gz
│   ├── 8c7de92c8bf311dcd145fdde163a9d43ffa7d08a.nq.gz
│   ├── 8e90b14ade63fbcc3c7b0eeb00ec5e5cd7f3e078.nq.gz
│   ├── 8edf700e5cb2fc999696b127e68908107595acd4.nq.gz
│   ├── 8ef4bdc43cf8e29a8d259e674f3c3d60e1b0376b.nq.gz
│   ├── 91082721987023e9df78362a1a782d30d94ed1c2.nq.gz
│   ├── 99ff29bc2d7ed0360296b68c85784be5b3aa4aa7.nq.gz
│   ├── 9c9d24390be5cda8a6c102d845ab012fe3d2ae4b.nq.gz
│   ├── a1b0f76420045801a0d764eadec7302d5cb8a6a4.nq.gz
│   ├── a97496bc9ca953d800e3fb445104a24fe4154745.nq.gz
│   ├── ae00682439d56b4a968beec5e8b4ae2377a733ad.nq.gz
│   ├── ae13ece6c1ac520581b2f6c84c4df795959f7519.nq.gz
│   ├── ae75e5aa8b89827209eeabda142c2dc62f618f4c.nq.gz
│   ├── bcb66f61011e558f42bdeee7b6fe06a764f88e95.nq.gz
│   ├── c29cfcf1c4ae0d5a5281fec69f80e90aa2fca4c7.nq.gz
│   ├── c56563e563886c870884d1f8638c6fbbe6d8e60a.nq.gz
│   ├── cf085002387f337c9bc1a37c354b17f0a3ecb10b.nq.gz
│   ├── d1d2e8f8ab11c99d708b6a67fe4fed5b01d69cd5.nq.gz
│   ├── d211ec9f185dcc5dd73c56cc30f0bda770617f02.nq.gz
│   ├── dcf95d72861348b36e4f21c31350f47e56934fc1.nq.gz
│   ├── e2a43c047d8cd34ecf8839148d4403687d011d19.nq.gz
│   ├── e5d880c617752cfac03031d20f8f7bd6b3c5a91a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4558e2a7abba4ff454656b82e67b3f5c483bf2.nq.gz
│   ├── eb6fdb785ffb6d80e3e641210dc5c8fb2470a2ff.nq.gz
│   ├── f3a56d5658eaed35777bdfbf98a694aacfeb64dc.nq.gz
│   ├── f8afd42d5da24b44df14f84677bfb5b89cd1fb97.nq.gz
│   └── fb3b5b1f87e8dcf113857f96ffe845869a616908.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f03fd2be7346952a83d3d4845c217fc7667f322d.nq.gz
├── filetree
│   └── f03fd2be7346952a83d3d4845c217fc7667f322d.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[NousResearch/misaki](https://github.com/NousResearch/misaki)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
