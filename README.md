# Repolex Knowledge Graph of pallets/markupsafe

RDF knowledge graph data for [pallets/markupsafe](https://github.com/pallets/markupsafe), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets/markupsafe
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   │   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   │   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   │   └── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│   ├── lsp
│   │   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   │   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   │   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   │   └── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│   └── repolex
│       ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│       ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│       ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│       └── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
├── blob
│   ├── 07698ec2dcda21d8c1963c9e7ef32f3722647dd6.nq.gz
│   ├── 088b3bca9839ee489eefa546a0773a465b8cd0ca.nq.gz
│   ├── 1028180710b4a75393732e85828ddd56c22f180e.nq.gz
│   ├── 1172d150bb27216308ffdb4350a879a3133d40c0.nq.gz
│   ├── 137a26fb4f5ab2a994783f7453715b7099b234b0.nq.gz
│   ├── 1fe38f17fd80188cc3ddad1293f5cbb7e6a46057.nq.gz
│   ├── 21a7e0621b79658222ee673ac2d9c6f9336469d2.nq.gz
│   ├── 2a09b42ea6b0f8fd8414566dedb3f50c6907e2b2.nq.gz
│   ├── 2c57ad3e535b0c86d94be5078eb720896cb123a0.nq.gz
│   ├── 2ebdc53c58d467e82df973a0f45a844080cd9142.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 320fb0a93bf7be1fab621b0af0c2a7621ac6c61a.nq.gz
│   ├── 38d56b8ca5bc5560d4d3d79d8038f60aa6902af2.nq.gz
│   ├── 3a41e7a648dd5d7def6330807dd1c50eebea3ff3.nq.gz
│   ├── 3acf91b56dd66374dac163741109a7e7f2501efd.nq.gz
│   ├── 3e535dc3da05af1fe0968fa79595d7b4b597ddca.nq.gz
│   ├── 43fe56371ea4d8ddd824e52a311e7f39d175aa20.nq.gz
│   ├── 4b8c70128be422f42f7b4c6ca81b8dc96d5a1816.nq.gz
│   ├── 4c395d7ba6005500b71f8d9bea5fb4c3abe371d2.nq.gz
│   ├── 4c654da7a361a02c30ea0726cf3462c833ff1683.nq.gz
│   ├── 4cece02ab4d995c1fabac764e684ac72c6c487e0.nq.gz
│   ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
│   ├── 5691977abc0027551386f2fa2491689aa357a5b7.nq.gz
│   ├── 56b2e26e8ce4d2252a916b66a19e423f53f9a415.nq.gz
│   ├── 582c74913678c05ceb00c7e7aa9ef72aa52fb0e9.nq.gz
│   ├── 59617aa88a85f9f0034110afecf9091dbc21c8a7.nq.gz
│   ├── 5d2693890dddc34129973f5613afd88767213b24.nq.gz
│   ├── 65fa1717b78258e9cf205d23e5a2191e9fc3f588.nq.gz
│   ├── 6affff18a365878504394923a19c77052fdcdccb.nq.gz
│   ├── 758aa2374264a23e80d7ac5a6212e035b433d16b.nq.gz
│   ├── 77a0efb708f7949083e116cc5f3beab019acdc89.nq.gz
│   ├── 7893348a1b7dbb588983a48e6991282eae7e1b55.nq.gz
│   ├── 797506ace86f7a467eed183e83c355f2805bbf2d.nq.gz
│   ├── 79cd99729a490e6a0d9d4e8eb14d121d42a269f9.nq.gz
│   ├── 7bde595c10a8f83dde52176c0c64401ba38e5d50.nq.gz
│   ├── 83b6236963f439e6d4e87ff54a9d7b0af1388f93.nq.gz
│   ├── 846bad802a491a63ccd2e147c64274642d6e9fff.nq.gz
│   ├── 85d9ea16be79fd706d45b64477e66c5578e6cb39.nq.gz
│   ├── 8a315f23c52851b23525d205e392ee69e0a27f39.nq.gz
│   ├── 8b7096acb1debd2c584880502e3739f7a4ad3d35.nq.gz
│   ├── 8c8885852a26eba90d3ca1783beca535d4d43bb0.nq.gz
│   ├── 919bf03c5092e557b164e7e2322b12ed74d349fb.nq.gz
│   ├── 91cccc49916f3db7adc8df753adb8d94cafaca70.nq.gz
│   ├── 93a10f89067f012f5a3ecd33b93caadef87d0779.nq.gz
│   ├── 955deaf27bc821a6367e818f36c016892fed3d33.nq.gz
│   ├── 9c41add09df3d46c430de808e6793cffacc5858f.nq.gz
│   ├── 9d227a0cc43c3268d15722b763bd94ad298645a1.nq.gz
│   ├── 9e7000aa2959a721679aa784987a0139eb94c9ba.nq.gz
│   ├── a2d0e73f995ecdf0137b17478403045a973b3558.nq.gz
│   ├── a53c2619e58565852a775772c32509ba8724ae0c.nq.gz
│   ├── acbd83f90b38e208b211fc7e62366556e9565dd8.nq.gz
│   ├── b57ae2474fdb032ee128c9ae55e7e9796f15ad95.nq.gz
│   ├── b57d2bec8eb939a96bfe621a3c47ea8d368bf8b1.nq.gz
│   ├── b5ff67d9a03c78a59b1307148d7ee6d41d381b48.nq.gz
│   ├── b7dbad4808ae52c62b60b76e45b4bf1e863bcec7.nq.gz
│   ├── bca464e088727dc8e41317feadd9195d5bade7f3.nq.gz
│   ├── c14f9170e9814f5ee6328b683f1ceeab169d29d6.nq.gz
│   ├── c4b245d256d38f221cf0813d208f77ad0521d0ed.nq.gz
│   ├── c9de47513e2b7490492c88c60a8266178577ca2c.nq.gz
│   ├── d50e4e0dc798d6edd3c135a63e5b7513da8b644a.nq.gz
│   ├── d941970b8e98fb1689042f851f91bd59b4226f25.nq.gz
│   ├── dec87af0737ef20204204694f79c663594a918cb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb124d251a733352fc4e867844072e876d1a8508.nq.gz
│   ├── ec330905ed44d72d0f959987376d1fefc43d1ef5.nq.gz
│   ├── ef0f7a1aa45d8a005382eeee20aebf483ee7d754.nq.gz
│   ├── f3055c545954920906d6e5e3d3db1cec7048bc73.nq.gz
│   ├── f349febf22d59ec7dfe440b65faf5838c1234b90.nq.gz
│   ├── f7e2942eccd11ed7d5f3d567639e1607d29299d2.nq.gz
│   └── fc6e392227205872f83426bf303550f070993c8a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   └── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
├── filetree
│   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   ├── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│   └── 98caea1496846935dd60a0e170c401e91ce9029a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

## Source repository

[pallets/markupsafe](https://github.com/pallets/markupsafe)

---
*Parsed on 2026-04-03 by [repolex](https://repolex.ai)*
