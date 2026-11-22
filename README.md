# Repolex Knowledge Graph of rwf2/multer

RDF knowledge graph data for [rwf2/multer](https://github.com/rwf2/multer), parsed by [repolex](https://repolex.ai).

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
rlex download rwf2/multer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 09cc7300c9bb7b3bbb30776e87ce14d2bd85588f
│   │   │   └── chunk-001.nq.gz
│   │   └── 541df3952995e9ac147c20c9d66c11a73bb3ce7e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 09cc7300c9bb7b3bbb30776e87ce14d2bd85588f.nq.gz
│   │   └── 541df3952995e9ac147c20c9d66c11a73bb3ce7e.nq.gz
│   └── repolex
│       └── 541df3952995e9ac147c20c9d66c11a73bb3ce7e
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a3c6e0da06ffe76825d1159d37e113bbb0a0b6.nq.gz
│   ├── 06f6907734201214e35d7f4486e5c0c6d7aeeb8b.nq.gz
│   ├── 09b78cab1e52416d917dea8da81d7d1f0815d843.nq.gz
│   ├── 0a9989dbd93e0148777d28fcf866ce71ee8df90e.nq.gz
│   ├── 14f768136b4f2217b6b4aab4f7c4d2d1b1b15ed0.nq.gz
│   ├── 170959f672e0c93d318a94e5ba14be368a0d4be6.nq.gz
│   ├── 2035c0107e8f9837f36dfbc8dff77200283069b6.nq.gz
│   ├── 23f863d7bfecb3aad20e8a606fefa8d6167c8d20.nq.gz
│   ├── 314dedf3009b5083bc4152b3dd4d7698503259b6.nq.gz
│   ├── 319f09f21437cf15e27dc1a74ad878868d5bb41b.nq.gz
│   ├── 3a1e04ea9cb8e01c6c0572a16305b7e420961d3e.nq.gz
│   ├── 3e08bb68ae724c88ad7664cb70d899154c9f2d88.nq.gz
│   ├── 4443e51a1ab1eb669f9eb859b2a3f4a728e7e020.nq.gz
│   ├── 4abcd9782fd08619807b117c4a54a44efb9429de.nq.gz
│   ├── 4e816e5a4c040f31c66576d995d02fb94be22411.nq.gz
│   ├── 4f3b47b076594093e86701aefbe8d0240c14ea70.nq.gz
│   ├── 57849409f42b954dfe1c3d41768749dbcaa6ea22.nq.gz
│   ├── 773c710e3f367f486f427f5d3f46aecd97438b85.nq.gz
│   ├── 887f2597c655e48519c6d5fdaf1bce60222d70ef.nq.gz
│   ├── 89b3bbb4fb657f5b4a7fccf20a457dcdd02eb915.nq.gz
│   ├── 8c4c192e7ad333e47a2c366fc4fe0a9967f655df.nq.gz
│   ├── 8dbdbe1e7de77b855f8d5719e3ccc38ed4bd9dab.nq.gz
│   ├── 95801a9499449d74bbaed3629c3897e308ec4e88.nq.gz
│   ├── 99369685a450396623678803dbfcd09cd3a1963d.nq.gz
│   ├── 99c02530a74108c5602d1739068c20d7417543df.nq.gz
│   ├── 9dd9c7af6a4973c5c6727410d3d66136e45b4275.nq.gz
│   ├── b5c683644455f09b8cef469adfce5a9d98622151.nq.gz
│   ├── cd61357c203ff5e2d198692122cf3aecbb985c19.nq.gz
│   ├── cff23f1e20ed3fb443cbf3776a36576b6f37fc59.nq.gz
│   ├── d01018ddbca47c6e75b0cac1b693b1c0032a9e6f.nq.gz
│   ├── d901f792aaf6dba262d7e1f221a01ba00af7e898.nq.gz
│   ├── dc726ae7b76290db424933f2e1a0bde3696a8b44.nq.gz
│   ├── ddfb380fc80a887e48f033d75ab47ec49553e1ca.nq.gz
│   ├── e186f378751f2ef0074fe69c4ed1eb50e56e0de5.nq.gz
│   ├── ec5d671e370d9fa9d2a1930a7123be1319ee9254.nq.gz
│   ├── ee27952b9c781fc94b1b83ecfaaae62353312dd6.nq.gz
│   ├── f2ba58b38cc543c65ea7db53bcffe4009b1269ee.nq.gz
│   ├── f3994ff8e37ef7163f9ef17b31fbbe7df4c657c6.nq.gz
│   ├── f7121311c312ca6ede8e9779b149a43251cc4f4b.nq.gz
│   └── fb428352196d6c54b263d4552c92618f36f3e08f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 09cc7300c9bb7b3bbb30776e87ce14d2bd85588f.nq.gz
│   └── 541df3952995e9ac147c20c9d66c11a73bb3ce7e.nq.gz
├── filetree
│   ├── 09cc7300c9bb7b3bbb30776e87ce14d2bd85588f.nq.gz
│   └── 541df3952995e9ac147c20c9d66c11a73bb3ce7e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 54 files
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

[rwf2/multer](https://github.com/rwf2/multer)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
