# Repolex Knowledge Graph of canonical/sdcore-ausf-operator

RDF knowledge graph data for [canonical/sdcore-ausf-operator](https://github.com/canonical/sdcore-ausf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-ausf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36c38567845e37a335b8f4c052343ebc7d350ecb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36c38567845e37a335b8f4c052343ebc7d350ecb
│           └── chunk-001.nq.gz
├── blob
│   ├── 034a6b82a816b76e76abdf77268a2dfb68ddc7ff.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 116b3c32bb54cfa0ced155d6d451b4f33b7be5d8.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 2507270f64121c0a95974660b9b5e83462badf73.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 423b4455a4f665535a3eb4f8f00b35b30901292b.nq.gz
│   ├── 47c52a90e58f78ffee8251131d7abcc984e9205a.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 56123af4bfeb5aa1d328825ccb9f5a3bf64daaaf.nq.gz
│   ├── 58a33abc7fbedbb15f39330e8eb54633f4a6e66b.nq.gz
│   ├── 592917c1faf09d824880438d553cabdf97ef219c.nq.gz
│   ├── 6042940a45bd36de5be5d0aecd85af65432defb2.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 62ef211efc29e2c63a9c2ef8138c29263c7283b3.nq.gz
│   ├── 64b81985e27474229caa09993597098e87e74e05.nq.gz
│   ├── 6e7930eadaf58b4c73b4fcffacc2f4579df851ed.nq.gz
│   ├── 71d7eb3c9940b1c6c7a2a36ffe4b5ff530c765c5.nq.gz
│   ├── 7335dd8d66dff3530556fa72af18b180a956ffb8.nq.gz
│   ├── 76489163110a35f173013b9b422c941c78dc1f67.nq.gz
│   ├── 76947568aaa30ae4b8da778946a9a4a4d0a28fe5.nq.gz
│   ├── 77eb8073d89654f25406c67f3ff767022107df0b.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 9298f4b32c427f65d03c2065f24e230453a96a4d.nq.gz
│   ├── 93034e0acae5ff1f7b755a4d29dfcb159a197c52.nq.gz
│   ├── 9aba7a42f1ff5d93a690f0f4782c10d4dcd5e48b.nq.gz
│   ├── 9ca1547ad0094dcdc444f3992dff80ab1bdc315d.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a44e5711f1e9189cf1d07f983fcfa3e574a57441.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── c5e3d3f94c6bc3651276f9b133de26696ef11602.nq.gz
│   ├── cf846d2a53917efe218cc1947a8cdd2b2f095140.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d618a8be2fc5a354288e523cdba2cfdc6a003c46.nq.gz
│   ├── ddbe4129e418999b80b46eaca90c3834c9628d98.nq.gz
│   ├── e7979fe5c4f275f4646c650fae9119194209668b.nq.gz
│   ├── eb5fc80ea619aa1cc08bc11bbbb6915c78421967.nq.gz
│   └── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36c38567845e37a335b8f4c052343ebc7d350ecb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[canonical/sdcore-ausf-operator](https://github.com/canonical/sdcore-ausf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
