# Repolex Knowledge Graph of zen-xu/pyarrow-stubs

RDF knowledge graph data for [zen-xu/pyarrow-stubs](https://github.com/zen-xu/pyarrow-stubs), parsed by [repolex](https://repolex.ai).

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
rlex download zen-xu/pyarrow-stubs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d92217fe71ff56e86c0125175b488b0d486a3a3e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d92217fe71ff56e86c0125175b488b0d486a3a3e
│           └── chunk-001.nq.gz
├── blob
│   ├── 021f2b8ce7fd6ec99ca73a390348b2042da07349.nq.gz
│   ├── 048973301dc9e7333c40da9e4093ed759002654f.nq.gz
│   ├── 0cb4f6171d3e3eab8cc3b225e2f91ca4afc9b996.nq.gz
│   ├── 0e80fae4ebffb1cf402fe3b1276819b8941dd847.nq.gz
│   ├── 166e10c9734a4e1ed9fa998d4b3c035f11e9293d.nq.gz
│   ├── 1698b55520b35a77543e09c545a3810128db84f0.nq.gz
│   ├── 200f669379b1884658cbf3dd728072fbe74f2212.nq.gz
│   ├── 20db1ae8fee3d7feaba0daf6ba2f9028de48edf9.nq.gz
│   ├── 2ae945c5974ae350a0b99e0a59c7d34b82ffd717.nq.gz
│   ├── 2eba8d40a11483a190ab5765ef5969fb75214d91.nq.gz
│   ├── 2f49f8c9a6c77a037721d53cc29bcf7a37e800f6.nq.gz
│   ├── 317943ce20f452f34f279199678c2c179b4b75b5.nq.gz
│   ├── 367408cb176715d2add05412d9a28e76d6551cfe.nq.gz
│   ├── 3d61ae42787fa8951634ab10dff6223c855d170d.nq.gz
│   ├── 43d2ae83cd80805401d5c3a2a38c00db04b6cf21.nq.gz
│   ├── 4450c42df49a09e4f3df58e1bf2e23fc09b7be75.nq.gz
│   ├── 46673961a755f2f584a2e15f9fa4fc081ebf447d.nq.gz
│   ├── 4a0e9ca47085971b155b37d0b26b2df03fafe112.nq.gz
│   ├── 4ef887058092df748edb4412e0f6186f9c8bf9fa.nq.gz
│   ├── 4fc7ea68e48e11638ed96ea2328809cbcb608cdb.nq.gz
│   ├── 510229d7e728f3b2c1bb3933d92bed78351889ea.nq.gz
│   ├── 526a58926a99494705b88505797a20b16afc425b.nq.gz
│   ├── 57a3bb4f1b399ea7303d06f0c1fa57d0a88d9be5.nq.gz
│   ├── 5a77dae7ef7c902a3bc5ca7be7ca399e17a62968.nq.gz
│   ├── 66981bf0f51880eca37f74385585c09e52b28c19.nq.gz
│   ├── 683869e52f9e0ec6d456825095ddbf1effd7a73c.nq.gz
│   ├── 69418d9d7defe521f4c2ec3ba01571b9d7b4124c.nq.gz
│   ├── 6af8fd695988661326bb321109c3aa1cb6f2814f.nq.gz
│   ├── 6bf75616c13a2ad175e134bf8b92eee06f5d815f.nq.gz
│   ├── 6d8ab44c433a0de4d6bae37ed2f9ede7d7315ed7.nq.gz
│   ├── 6d8e2aff5b74b5658ae37a0ec02c86fd3aa6cb7d.nq.gz
│   ├── 71bf0dde9babe59b6da0cd558579c6cc6e4d1077.nq.gz
│   ├── 72e0c690e476a042792a4a2d508480c2f2e50eb9.nq.gz
│   ├── 73f9f2916f3b55c0f6aecac81a04afa36a63ed95.nq.gz
│   ├── 7623275b8658f6995b6e52ecb1822f5c4905b9f3.nq.gz
│   ├── 7670ef5230d9b902e2a086ebec72991d9c8338ae.nq.gz
│   ├── 7f437d4532c0ffdd17cfd24dbd120ac613835fd2.nq.gz
│   ├── 81ab501206798db63db2664f8ce2c16832937044.nq.gz
│   ├── 8a0d1e870c5e32dca40a118c39f99c829b01f034.nq.gz
│   ├── 8a520bdc24ab7fede442c2a7389f47a5e7838e13.nq.gz
│   ├── 8bb914ba45dfde4a79c76de4c9c1c10aaac13d13.nq.gz
│   ├── 9451ee15763e11e689db100a20cbf537b957a5b0.nq.gz
│   ├── 981ed51e680cbf04d8790c343bf76da86514d0f9.nq.gz
│   ├── 98f1a38aa85e4bec7920c5d65246cfb2c416b977.nq.gz
│   ├── 9b806ccf30562230269b195e7f594c9062836b1c.nq.gz
│   ├── 9c4ac04198f58205c33319b39c10564735ca3836.nq.gz
│   ├── a22d1101f07039646d03f5a15151263f0016530e.nq.gz
│   ├── a344f885b29b6084ddf9157df94fac52122d07a2.nq.gz
│   ├── a56a8a5b40fb19044362779ebab1eb446a1be22e.nq.gz
│   ├── a9187df0428fc6887d170e32d8e87607317e0488.nq.gz
│   ├── ad52b2f380f7a83a025aa4056a6e95baa713724a.nq.gz
│   ├── ae667be453e879922dc813265bb76f8348613dc4.nq.gz
│   ├── b04b6268975b533e31411b305d74b7e6622f1e4f.nq.gz
│   ├── b3ce8b804282f71e2f8fc273c34dd111a4ef94aa.nq.gz
│   ├── c259513f1ea5fc0a4b06c1edd29abecd6c69d183.nq.gz
│   ├── c2ecf7d6b61be9559aa0c83276a5dd8c20528d98.nq.gz
│   ├── c707edb844a4986d078a070120ab580ca7815f01.nq.gz
│   ├── cbcc17235f15a3ae043b29b7635969f4a9fd7325.nq.gz
│   ├── d1b9f39eeddb5e2fe690a88ce9893e680b81ea8d.nq.gz
│   ├── d849abd0f1f40c269646102e5dc3a6521b606951.nq.gz
│   ├── d882fd79d573a389dd4cad760c322e71f92ed510.nq.gz
│   ├── db1d35e0b8b4802468cbd0c8683ce9fceeca7a1c.nq.gz
│   ├── e11baf7d4e72268da861b0a44e4c390e72d5580e.nq.gz
│   ├── e2e238e5073d09a361e2e85a1eb476aec2664e8a.nq.gz
│   ├── e3f1b4ea3b2bea3feca0517a88aab88f5ab17191.nq.gz
│   ├── e6662867b6b28fd0db9ad65124d2d800e976d3db.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78fdc9b020e3f4b3080fc6a8c5f9362c0b69351.nq.gz
│   ├── ec40186f30d555f2d791d766fd7dd5c2143595a2.nq.gz
│   ├── efbd05ac2fe9a2860aab09d53f9306e886568354.nq.gz
│   ├── fc13c498bd96e4be86d5e460dbdbb50b61981f68.nq.gz
│   ├── fd680cbde2520405912a6575222a55c071ca3f62.nq.gz
│   └── ff226e9521baed15cbf2aef3da7214f1a4452c6e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d92217fe71ff56e86c0125175b488b0d486a3a3e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[zen-xu/pyarrow-stubs](https://github.com/zen-xu/pyarrow-stubs)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
