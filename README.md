# Repolex Knowledge Graph of marshmallow-code/flask-smorest

RDF knowledge graph data for [marshmallow-code/flask-smorest](https://github.com/marshmallow-code/flask-smorest), parsed by [repolex](https://repolex.ai).

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
rlex download marshmallow-code/flask-smorest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3440f0d851f9e7f7b94d5559df3ab59746f5f6ca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3440f0d851f9e7f7b94d5559df3ab59746f5f6ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 0709e413a5ce61ed58af30c817d1e2b67e0e067c.nq.gz
│   ├── 0b0bc4c3c8a420a6078b8ac5442568eb6e2824a5.nq.gz
│   ├── 0c9c9c120d4bac34a49f957ea9f122177843e5cb.nq.gz
│   ├── 13134ad47467841ffecc6557d108dc79968eb31b.nq.gz
│   ├── 14dfe4fa0ae650fdfcb6295dbc607928f300cea3.nq.gz
│   ├── 1f0666d555cee8b9c7608358f16a4a19421bd2d4.nq.gz
│   ├── 20541486f45c2fdf2cbb8cb37af6be7dff68e63a.nq.gz
│   ├── 2308d85b0b867517a833a60e804cd7ccd5cc84ec.nq.gz
│   ├── 23adab388e8d9066e1b41316c8dc814141da732d.nq.gz
│   ├── 27a475b88b27a58093c84b3c8e509601e4be1a4a.nq.gz
│   ├── 365f80940ae2634ca3797bd845a1a7aa25336c27.nq.gz
│   ├── 391d5640411d7e61c44f7470a41e87be767dacc0.nq.gz
│   ├── 46574a31224896739b5c2020a0dbdf6f24fc07c9.nq.gz
│   ├── 4b29779faf621ec15592767d5c7889a045fddaa9.nq.gz
│   ├── 50f4f9d2c47a3e2df0bcc4896120e51ab147a424.nq.gz
│   ├── 5156479c46c663fccbec2f5786eab962de684449.nq.gz
│   ├── 584fba18b764b02cd791f8db3ff67cbba645a3cc.nq.gz
│   ├── 5d55a5af9b2c3fcc9a970df669c8726532e2a86e.nq.gz
│   ├── 5eb07ea1396e0a681285a87a446c11d3bb5c493a.nq.gz
│   ├── 5edcb66bbeadf1a8b56ba0b2b40f90288995da8d.nq.gz
│   ├── 60621c3459f3a32ed40d6a098a2c7be16118cec9.nq.gz
│   ├── 65ce1869a3d293cdadb010ae48ead525a5e69f3f.nq.gz
│   ├── 676f4dab1d1521911df3df7d4f0fb0ff2d184f62.nq.gz
│   ├── 68bc17f9ff2104a9d7b6777058bb4c343ca72609.nq.gz
│   ├── 6b6db9b339cd4a16a650ae34202d50c4b402e09d.nq.gz
│   ├── 6bdbf7b4a413adfd6c49374bbf4ada3575cdf6aa.nq.gz
│   ├── 6f752cc373a45d30df8c58ade9b789137a836c17.nq.gz
│   ├── 76888fe1bf10912f9575845efabb510921743065.nq.gz
│   ├── 78baf480d30438bec2a316922d05c4cb1af8c235.nq.gz
│   ├── 7bcbdd6a9d8bea4c578bbfb162e8fd836ecac8ad.nq.gz
│   ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
│   ├── 8924563c288677986b480fbcc3a407945c4c636f.nq.gz
│   ├── 8b4f28ea00253ea8e96bf480a63e8ad3e87fde31.nq.gz
│   ├── 8e3881d3fd7ae6fccf6e9a43da524f4a784d91c2.nq.gz
│   ├── 98ed489910e0e5aa20d609970106f1c03d3ced9e.nq.gz
│   ├── a01bf034543fc58d4c369b5d96e4c6b3477646fc.nq.gz
│   ├── a767c4feed608b8191254b434b87e92bc6f38a51.nq.gz
│   ├── a810ba2dac41d61041b6754e11106dc27b0ae4df.nq.gz
│   ├── af73122255b2a3317eac2893535f1e208aa783ef.nq.gz
│   ├── af9eae0ca9d82ec10c77df6caf859b02fc6ee0ce.nq.gz
│   ├── b06cc620d2f3224bdb0d4492992f14cf7fc3ab4d.nq.gz
│   ├── b637cd1cbdb813b8bb77b72dde86bc0096837447.nq.gz
│   ├── bbe4bdb5bdade68102e94a72a95e72d636ea74a8.nq.gz
│   ├── bea7f52ee02ab20069a15e73447ddcdd09703e51.nq.gz
│   ├── c4a807390655eead35dab62d5ae88391bd2282ff.nq.gz
│   ├── d6af8f8211464b05ecc7531c9cff1df80ca020c5.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e29d0a0ecaf0a7740a2dcebc0415fa02d5a8c49e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e816f154b5dbcf20fca26dfe046685a016e2786f.nq.gz
│   ├── e974badcf1a7c9e62bd995f0e1a1349901279a25.nq.gz
│   ├── ee48fabfde9cbfdb1cfc5fa79495c994e2142b8c.nq.gz
│   ├── f40ce91be5fa3ae6afbf5457462f0d87000e4f1b.nq.gz
│   ├── f7284455e876c71ada87da98f5517160bf85f056.nq.gz
│   └── fabe81fa986325d1925eae727f0e642b7b215890.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3440f0d851f9e7f7b94d5559df3ab59746f5f6ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[marshmallow-code/flask-smorest](https://github.com/marshmallow-code/flask-smorest)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
