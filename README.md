# Repolex Knowledge Graph of twisted/epsilon

RDF knowledge graph data for [twisted/epsilon](https://github.com/twisted/epsilon), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/epsilon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68b7e4328671d169ba59a7f6571aca4f37062a82
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68b7e4328671d169ba59a7f6571aca4f37062a82
│           └── chunk-001.nq.gz
├── blob
│   ├── 038768a6eaf5a0af8c095ee184b230b801dfde6f.nq.gz
│   ├── 075e2a4813a4b9408612a890f0aa9b1a7f473886.nq.gz
│   ├── 0b68379add0476acbb3d3f9bdfa74b375e980b1f.nq.gz
│   ├── 0dd90560e51ad62e72140168efe05ffbf77c9ebd.nq.gz
│   ├── 0e899dccc4c32a757de66afbdf0d01897e456517.nq.gz
│   ├── 1165a31847e536a6a3e8e1cd68643288eaee78d0.nq.gz
│   ├── 147eea01f10760ccdadde5637a11ba838feafc63.nq.gz
│   ├── 148c6700dd507647ac40b1d9d774270c7d009389.nq.gz
│   ├── 1b28212374f65bd2d434ab9c472bb097b95fa33d.nq.gz
│   ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
│   ├── 1ce0d38798a7059d22abb328d4e2c778fec2af75.nq.gz
│   ├── 1d4a0e4f5017f64a5fb60311927214aba1f89fbc.nq.gz
│   ├── 24d64a66e1bd904d0911b0bccb74ae046f609f8b.nq.gz
│   ├── 277faa07728bb7a78af868e4d6e82da00872e4be.nq.gz
│   ├── 293e584d633770e7fd3b32d9ace7fb62a4228da1.nq.gz
│   ├── 2a3429cd581ef98a20cbc84cccc833f87da87e59.nq.gz
│   ├── 2a5f480cccf6bc26c004e6f71f66c722ef2a4791.nq.gz
│   ├── 2b3ecbaff71b7ba7b78f6d994087fb61012a5af6.nq.gz
│   ├── 304d22d8db7da98b402add2912d871bf14f1fe71.nq.gz
│   ├── 30678a25d5586cb707e715caa4373def64efdfd6.nq.gz
│   ├── 30ca9a02d0683ac4f8fc194bb502463983c2190d.nq.gz
│   ├── 30ddc033b36bd280ca1d2ef23d2f36ecb7241782.nq.gz
│   ├── 33ae7aee4be52a8a31ad3157ee3050a631e7c2a3.nq.gz
│   ├── 33b71038a17437a308028e761fbacffc2cd1af59.nq.gz
│   ├── 33c36af34a462bc61dc8711d40188a23c1a06bdb.nq.gz
│   ├── 3412850a5424a98a7f7a11766721fe828c98094c.nq.gz
│   ├── 352ef35902628cad35a1fc548220999f8da30125.nq.gz
│   ├── 36516db219e3db2aed01dec2854a05b00c196f68.nq.gz
│   ├── 385f2550594912a380b06617cd521b94744afb90.nq.gz
│   ├── 3a4c2c7ca9cbb5d7a7ce157d5b5413859ddb1664.nq.gz
│   ├── 40a028fdcc2ec98229d7f70a1692b8c36c45fab3.nq.gz
│   ├── 47507f59e77ae0a517e8e775baa2628f6c7f6b68.nq.gz
│   ├── 479e503b518924b5b080566b528985c8d09922bc.nq.gz
│   ├── 4ed2a4492cb536270fb22b320b661b512f5254c0.nq.gz
│   ├── 502b54f9e2694a6799143d4616f223a4c013a480.nq.gz
│   ├── 5222c64489071026e3b93d8154529b849a8edccb.nq.gz
│   ├── 528b1be4147916b376f4c4d53412eedff35201fa.nq.gz
│   ├── 52b55cf5c50de71db1e86b6e551775069e579afc.nq.gz
│   ├── 5bedc7eed666aed64cfab136d86d9bf853207640.nq.gz
│   ├── 60279678c9716e5fb5fe64ec399afc3019b3bc9c.nq.gz
│   ├── 61e60e98aba804a11aac4631c92aafb11d374281.nq.gz
│   ├── 63ce4c85d2faf7827e3117ba22c67055482c5a44.nq.gz
│   ├── 66dc9cc50a99c76213526d03be6970454d5e9ff5.nq.gz
│   ├── 69d2bfd93a681693bbe24b590b0bb5568caeab5f.nq.gz
│   ├── 6a588636dc362efae84b790a87924f429a4e4039.nq.gz
│   ├── 6aa5ec4d340e5c42104de5acb3d0e0980a6bda87.nq.gz
│   ├── 6b6dd16a010f0a777daa4419d0bab7ef6b2c2d3f.nq.gz
│   ├── 6be49ec97caa220ef1c4ea46b6bc4944bb803cfe.nq.gz
│   ├── 6f833a4768281878211d0111acb5e55ada243a2c.nq.gz
│   ├── 72e09cf5b013a6b027fbbaecd3626214d0df1f74.nq.gz
│   ├── 73cdba3e8886177efa46d30f2787df015a721150.nq.gz
│   ├── 78b9e881286e4ec0f0a406da19de622218c2a205.nq.gz
│   ├── 79a46d4f02ac7154ceaab567fb1bc37be61c41e8.nq.gz
│   ├── 978bbbc53cdb58e229a2d61748fb08332ab2b52e.nq.gz
│   ├── 986c3ff2b6379cd63c60265517a6878b69ccb0a7.nq.gz
│   ├── 98b92c1e6a3ec7689ac015a2b17b3fd304f9836b.nq.gz
│   ├── 998976e6a368663f2269029374183884b23bf86c.nq.gz
│   ├── 9e7d2610ecfdd160fd717f4173961a2d604dde86.nq.gz
│   ├── a28352a000b9db093afc236cee4cd51b97243958.nq.gz
│   ├── a6b6113a3d7175e81db061139818197a8ded66f0.nq.gz
│   ├── a9cbbf8199ed32008fb58a86f82d15d785d574fc.nq.gz
│   ├── ab2150c8955ecc81420de3838f0a881bfcd50b7a.nq.gz
│   ├── ac8dda84ae4dc005adfa9ff2ba2cb5120097f493.nq.gz
│   ├── ad0a3bbd4d33048b12599c2de709bd25ba66021c.nq.gz
│   ├── aff9ede5540823e46aeb03b944715216a4b0c849.nq.gz
│   ├── b24f26fbb3cdb82e803d04abdc0833220917c7d1.nq.gz
│   ├── bd4e30230a6f5f659f947c9d75fdd80dcec797ee.nq.gz
│   ├── bfc4cb283f16197bc357585bd3fdccd65b288606.nq.gz
│   ├── c8cdd4459c79e9e37692238192112fae846b8fff.nq.gz
│   ├── cbbd9717988044babc6da0a7c09120795b125303.nq.gz
│   ├── d5c79a512a74543c873cb5f0c039043dfbdd2f4e.nq.gz
│   ├── d6c421f23743b927cc4678e289bd4195c9c1a588.nq.gz
│   ├── d7d5feecdcc6f68f6bbe26209a9f58fccc1be1db.nq.gz
│   ├── d8ad39d411584e1662aa37664836c77b2e350727.nq.gz
│   ├── dbb9f18316a953a00eba5f0b48b43b6b4b8b8058.nq.gz
│   ├── e5c135e56521a07ed0e46f4df249f7f35cf1e6f7.nq.gz
│   ├── e60502112988aee497069ea28f6818153f4c4ef1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bfed30e0390d370c1e0e2e03f4855dd78439c4.nq.gz
│   ├── ea2df3f1eb47da6afbbd04214eff906b8f707479.nq.gz
│   ├── eb2e7edb65485c8693c7393605cd6fabae079970.nq.gz
│   ├── eed30111a4eb7423aeedbc2d82853a7a24090a32.nq.gz
│   ├── f04e56a7dcbd7dd21364ddb44147e078c6ff545f.nq.gz
│   ├── f11d032728e95bd7c56f000dbc4ae394cfcc1734.nq.gz
│   └── f18f2bf5742b0706b66c32cb2836f5694c3e487f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 68b7e4328671d169ba59a7f6571aca4f37062a82.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[twisted/epsilon](https://github.com/twisted/epsilon)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
