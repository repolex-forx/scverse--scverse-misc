# Repolex Knowledge Graph of scverse/scverse-misc

RDF knowledge graph data for [scverse/scverse-misc](https://github.com/scverse/scverse-misc), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scverse-misc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── abeb0bdc8493a4e62f606a09e89761d077088857
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── abeb0bdc8493a4e62f606a09e89761d077088857
│           └── chunk-001.nq.gz
├── blob
│   ├── 003c2d8278a5a0e1da6084ac5de67ad68799dfd8.nq.gz
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 0d7940ea3e4eecaedc7b68c219487a5b0bff4045.nq.gz
│   ├── 1912582edd7be49466200d73b3eae5fe3e8d5ab3.nq.gz
│   ├── 230e7670e0f1a2c2ea6c53dba163a17ad67db23a.nq.gz
│   ├── 2380a4d49cffdcebe19dfe0dbfe018bbb39e4678.nq.gz
│   ├── 23b97c9859a8bbe9a6abc48a019c8bac7115801e.nq.gz
│   ├── 2933d41c5c11f31b4dadafc390ed144e699b6b7e.nq.gz
│   ├── 2a82dd73c890b574a229fcfb2528d28d1be0abd9.nq.gz
│   ├── 2e8e35908fe0e1cbfc37bf306fbf1b28d180be2b.nq.gz
│   ├── 3d023c72f30dec0453b67475014132aca0edcb90.nq.gz
│   ├── 3dc87cd072de198e48ff27e10e6bdd96a9ed11b7.nq.gz
│   ├── 4414d78d2143e68ac3fb88cf82bfd14f105841d0.nq.gz
│   ├── 488bb122efa535b44a361a91a80c3c30427a3ea2.nq.gz
│   ├── 4c04fffa6b2fd120bd26306ad5d0ded67c06c46d.nq.gz
│   ├── 5816e635076db149a79025f2a6ed640ee7d48141.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 6104b9e6f4ae97e25a2fd85f24bc2370b23bab6a.nq.gz
│   ├── 645fd717d9e878fb689d008363d7aa8a3a38cade.nq.gz
│   ├── 65f359fb327aa9aa158e75a9aacfc99a9a634636.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 67ecba67afacb80dfedcd577022b003492c1185c.nq.gz
│   ├── 682e7cfa819f6f85a3e7fe3fc03231ae59368377.nq.gz
│   ├── 70fa27178640e72388e2a661acab98f328dad0ed.nq.gz
│   ├── 720f98fc462f03d65ff6756415a31f70bff48f7c.nq.gz
│   ├── 758b620231b284dfc704b0786d4a975d9d2f602a.nq.gz
│   ├── 805e9a4f1ec5ee979d7b886c9d9c09f48a46267c.nq.gz
│   ├── 8209e8e5f1ec6c4cc35619604bd725949f504316.nq.gz
│   ├── 85792bb5a318f9f6e32bd8cfe90d3b16df361f66.nq.gz
│   ├── 8587165b974a5756c2267b394f33fd03751cbb1f.nq.gz
│   ├── 8929d392c73648fdf168fd4d8c20e35c89be4776.nq.gz
│   ├── 8ed3c4123a1f901a64c349962ff7db5f690d55dc.nq.gz
│   ├── 914ad69d5046bebb8743ad4f7a9f003284d56925.nq.gz
│   ├── 9e351642f9597c4cd45e10957a4c292e5a067a96.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a0d691c36e45861741cd393220977ab1ebfa5016.nq.gz
│   ├── a4f673f9ef927eb4514af42bf4c3a3b6889d8c04.nq.gz
│   ├── a734532e694a186808d426dcdff01e4c2326aa96.nq.gz
│   ├── a77c882ea72942dffeca4091b1cf4d38c8a9badb.nq.gz
│   ├── aa561e36f580e8578607d61c6b9992ec3ccfb8e4.nq.gz
│   ├── ab6347e64813f70aabe764a11e4ff046c5286fee.nq.gz
│   ├── ac78402a792f73c8969ee5cfbf1e75cffbc2518d.nq.gz
│   ├── b7299568431d6eab5ee88aec6c5b949f7eb8cc52.nq.gz
│   ├── ba538e26a83edcd0c26669c448416a17fc7c71a2.nq.gz
│   ├── bfd113f90a2537d182d58b6593642055fa0a1f2a.nq.gz
│   ├── c3103476775ec3ceb15a2048b75e302e6b500365.nq.gz
│   ├── c45be287f299e5ced4ee094849d6b5b8ff860c58.nq.gz
│   ├── cdf29260eb98387e13f618e6964507be6800e903.nq.gz
│   ├── ce2301ffc70e0c26c1000e1a92f48ebe5a85f769.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d206e116600b21c33266109e06a2667e42c01af7.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d5fbf259936bf4612218feeafea50a4a7ef5b313.nq.gz
│   ├── d6af5e92530dcf5f4528312c719f51f50e9ac0ec.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── dd5307f3d21322fdc93a776bc7ec9e2cdb7527c4.nq.gz
│   ├── e2acb2b85fa12d7a2b2336a60c9bb6ec6e355182.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e20135f50d0fd7241608b087a14007b41575d5.nq.gz
│   ├── eefac698bb4a3c5b2acaf0ad08b1472088df5462.nq.gz
│   ├── ef521457338205bc1a6c901764185de0ddf475ee.nq.gz
│   ├── f22cfb7149eb441c66f9824501a83c772a445c9d.nq.gz
│   ├── f71ce5a7c3c70061aac0dac326abff842a33f401.nq.gz
│   └── fdfac0b96780a29365e4455409d8be6f106211df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── abeb0bdc8493a4e62f606a09e89761d077088857.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
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

[scverse/scverse-misc](https://github.com/scverse/scverse-misc)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
