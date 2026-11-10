# Repolex Knowledge Graph of Yalantis/Context-Menu.Android

RDF knowledge graph data for [Yalantis/Context-Menu.Android](https://github.com/Yalantis/Context-Menu.Android), parsed by [repolex](https://repolex.ai).

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
rlex download Yalantis/Context-Menu.Android
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 595c679e571745d7e119f81966e6f5b20c823574
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 595c679e571745d7e119f81966e6f5b20c823574
│           └── chunk-001.nq.gz
├── blob
│   ├── 035bb58adb9b4b8bde27fd00afd93a146f3097c2.nq.gz
│   ├── 04f72f8fe3720c29a3582b774a365a4a28536b88.nq.gz
│   ├── 05ad3c6c644a62c5c14d8ee778bd3866f03a5c43.nq.gz
│   ├── 07df11b10a554180f7efe96b6e787ab80426a038.nq.gz
│   ├── 0a8c8865d4965fb96e38714d0de64f72928c21e1.nq.gz
│   ├── 0a9ba9dc85fe80848d9742efdb50671aa7053f48.nq.gz
│   ├── 0d1889b9d4367a9ab6fe4c297836bc335371a46c.nq.gz
│   ├── 0e1e8000e57b4aef96377ce4b67a116aad4e89c0.nq.gz
│   ├── 0e39e6b05abc563a967a853b0159099eb3d1368a.nq.gz
│   ├── 1024cfc20aab91d45153bbefab80312e93a82e85.nq.gz
│   ├── 10bfaffa8f52b90683aede92754f8bbade069a8d.nq.gz
│   ├── 15f6cdfdca04593b8b9a63883873be5ed5e3d0b4.nq.gz
│   ├── 1e4d827927eada373e99c5e9d3447e358f927d37.nq.gz
│   ├── 25164f78b93ab1a92ac62d061336e55bdb417eac.nq.gz
│   ├── 28f8c529e3225bf30cbfc4be5cce3b245b3202b7.nq.gz
│   ├── 2dc02d8df13351df7369332de5c811620c5357b4.nq.gz
│   ├── 2e64dc254c35da0e0d35e497d7bb737e4be9ff82.nq.gz
│   ├── 2fc904c621b6e24987f0578aa53635e778d2aefd.nq.gz
│   ├── 34893a8bc24c7d9474987be0ace4cecac0ed651e.nq.gz
│   ├── 3866ac36e19b40525d9d337fc6fd22f65a5e3844.nq.gz
│   ├── 3867b84b3fbbdf7e3575f03223f8192dfe129abc.nq.gz
│   ├── 388899ea3775b5527c5583f31bef55a2f19bae61.nq.gz
│   ├── 39a49a88b962f62ce90779cdb5c0283b7d11849c.nq.gz
│   ├── 3b52deb0b085af45dc928e5795cf9cec9a418123.nq.gz
│   ├── 3c8d2bffa196749f9f281dbca2b2609b2acb5adc.nq.gz
│   ├── 43051731a92b13570f689809bda8c2dc75e51744.nq.gz
│   ├── 4b445722eae589bfaf05f25e962cedec36998240.nq.gz
│   ├── 4c764a7b6cb084b248fed0b47272d5b5544e4fa7.nq.gz
│   ├── 4f575b0e76e6fdba044297f37af7a079d3f41bb8.nq.gz
│   ├── 507aee38b7b2874d3371e0d8e0686e80046935fe.nq.gz
│   ├── 574ed7ad8fdb4629eb4234b1edcda07b9af48c94.nq.gz
│   ├── 5968d05185a02e8b609415da4017f96f5b38c6f2.nq.gz
│   ├── 60489a9307a6520493ee89d38ae2ce5628d5e2cb.nq.gz
│   ├── 6792c3a8681ec73ba715421992f61f82bdfefb7e.nq.gz
│   ├── 691b59bdc9d597926a00102063fd719e8e48d126.nq.gz
│   ├── 6bb59a543eb1ce78235c0f0846411f3ef2fb26d8.nq.gz
│   ├── 709085fc1e0273533dbed66190ea1b18b4d5e5c8.nq.gz
│   ├── 72e7d5746751d0d8703b29752d68d6311a05ad13.nq.gz
│   ├── 7358a1fcd79fbc08dc515a0628d5300f37a162bb.nq.gz
│   ├── 769089a3461dd22e7acb497fda7fd5074a1e7745.nq.gz
│   ├── 7709bb1f58f270a68098e61d485101612406e43b.nq.gz
│   ├── 77f76760380fe9a472eb30405f9ef700c5bb1efa.nq.gz
│   ├── 794d6de0c725aca5512773df39fb11f33a8d3ec4.nq.gz
│   ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
│   ├── 7d007fe92a1c57b4e5ce0041ad4439ac12b39cd1.nq.gz
│   ├── 7d85288d12533c71acb8c6722fe898f89d724228.nq.gz
│   ├── 7ee47305687b923ed8d8a25312ddab68d7f7b2e8.nq.gz
│   ├── 87213aad932c3cf2674d7699422d2d16e917d3ab.nq.gz
│   ├── 88299b81b43a2dab662b6453fef67975d60aa736.nq.gz
│   ├── 88a14dcd9dde1beefdba2f0818cbee96fa1707d5.nq.gz
│   ├── 8a0b282aa6885fb573c106b3551f7275c5f17e8e.nq.gz
│   ├── 8c0fb64a8698b08ecc4158d828ca593c4928e9dd.nq.gz
│   ├── 8c5d9d32d3dbc879149ffe7db9f45f06291295f5.nq.gz
│   ├── 91a7e269e19dfc62e27137a0b57ef3e430cee4fd.nq.gz
│   ├── 925d24c88e105b82d6a0b688a54b4b3c02335d29.nq.gz
│   ├── 96b49f14174e48967272f50e960ec7bc60904010.nq.gz
│   ├── 9722e787781a3dfaf41c01e0089b9d08dfe6753f.nq.gz
│   ├── 9873549917cf58bde4d9780d6b69c4c1fdddb960.nq.gz
│   ├── 9c388123b132b8a8bcdd259746af328c954423c8.nq.gz
│   ├── a17ef93031c8547a3abdafbb1868e0aba2a2715f.nq.gz
│   ├── a39e9fb27e73a38cc21bbd82234854dfffb369ae.nq.gz
│   ├── a7aac53fd04424c87b44102d0ff0678ec165358e.nq.gz
│   ├── ac4552abd316603cbf4cadf20fec110e65a4f90f.nq.gz
│   ├── b2fbbf24bf0b23c09115e54bc124ce65d84196c4.nq.gz
│   ├── b40d492754f306f340d932cf7446e73c394ec70c.nq.gz
│   ├── b7505cf2bb1d68d9903f66fb76fcff8b15c52af0.nq.gz
│   ├── ba4f6f1f114cdacb5914ffe3af148ae60c1c02cd.nq.gz
│   ├── bdec8385277e66243fea42068c3e651af70f48f3.nq.gz
│   ├── bec3def4e60edfc0b4449a2bea11c764d8f4a3dc.nq.gz
│   ├── c532611a166d9d7de36bfc40f0e98e95fb67c829.nq.gz
│   ├── c72989173bd1d6f4fbeb007853d2c3055fc4762d.nq.gz
│   ├── c7f8a8714dc660925aec2705288a26bfdae3639c.nq.gz
│   ├── c975869468d11a231edf55fd51cb3123512aaaf4.nq.gz
│   ├── c9be0870be15f49732fbdd79d129c52e21f741f9.nq.gz
│   ├── cb26578bf5e1f1dacf01a38d4a2e68e1c5a5db4b.nq.gz
│   ├── ceb187eef34b5d7614039dadf29af2504fcc9fdd.nq.gz
│   ├── d2bb1cd43637c246d99cf04439c108eed4614c5c.nq.gz
│   ├── d7958b48c32aaf6126c2dcb6e89d7cbb849cc71f.nq.gz
│   ├── d7964f6126e941c465cac685baa2738d424c9cef.nq.gz
│   ├── d7a5722b12855f7cd870201540dc6a2e765291a0.nq.gz
│   ├── e06d2081865a766a8668acc12878f98b27fc9ea0.nq.gz
│   ├── e1abae702258ff52295c13de74bbabf51dffee4b.nq.gz
│   ├── e48233515189599b599bfbd81e3b5cf9ea008300.nq.gz
│   ├── e620c84a31e3d79a7c43f48359f6044ab4b09824.nq.gz
│   ├── e65b4bfd5ce360d7109bafe6f59066e88d472d6a.nq.gz
│   ├── e7376979113092f30690261a27f61e8529045561.nq.gz
│   ├── ea7bc0ec4e19e63222565e4b80e6c6936ffa6025.nq.gz
│   ├── ee4e28f8006b6465df075a83b417a99cc35cbe5d.nq.gz
│   ├── f04974cb739262784020a9cd9e0fc2c98e540d3c.nq.gz
│   ├── f2ae3ec9526dc23e78201a3c3b51511ddb366dc9.nq.gz
│   ├── f62da34927a33fcd4f52f21942cc263d0c037bc7.nq.gz
│   └── f717860874113a5841e486ea72143b12034dda79.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 595c679e571745d7e119f81966e6f5b20c823574.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[Yalantis/Context-Menu.Android](https://github.com/Yalantis/Context-Menu.Android)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
