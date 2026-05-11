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
│   │   ├── 026f317933afbf49e7babd2a1fe7d19e86b1b5cf.nq.gz
│   │   ├── 0aa98c6abd7e8e1c4f585fa01a51a7607f501ada.nq.gz
│   │   ├── 297fc8e356e6836a62087949245d09a28e9f1b13
│   │   │   └── chunk-001.nq.gz
│   │   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   │   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   │   ├── 497d9b67793ad9ca09d597c27d1196a94f57ddc4.nq.gz
│   │   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   │   ├── 58cde05bdcb0a53d87213b4a5bb605937f178171.nq.gz
│   │   ├── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│   │   ├── 7afa6391254dc176a2352475226eabf35f0d178d.nq.gz
│   │   ├── 98caea1496846935dd60a0e170c401e91ce9029a.nq.gz
│   │   ├── cbac3a73c628aed66800e993e3931fcb43f76dd0.nq.gz
│   │   ├── d762f0dbdaf8fbd4c3622d6efafea99c0036a443
│   │   │   └── chunk-001.nq.gz
│   │   ├── ef0b95e2544ea0d09230a57dc01ac91e3bab9689
│   │   │   └── chunk-001.nq.gz
│   │   └── fbba4acd0312826cec9cfe18371c7df07962cb65
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 026f317933afbf49e7babd2a1fe7d19e86b1b5cf.nq.gz
│   │   ├── 0aa98c6abd7e8e1c4f585fa01a51a7607f501ada.nq.gz
│   │   ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│   │   ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│   │   ├── 497d9b67793ad9ca09d597c27d1196a94f57ddc4.nq.gz
│   │   ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│   │   ├── 58cde05bdcb0a53d87213b4a5bb605937f178171.nq.gz
│   │   ├── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│   │   ├── 7afa6391254dc176a2352475226eabf35f0d178d.nq.gz
│   │   ├── 98caea1496846935dd60a0e170c401e91ce9029a.nq.gz
│   │   ├── cbac3a73c628aed66800e993e3931fcb43f76dd0.nq.gz
│   │   ├── d762f0dbdaf8fbd4c3622d6efafea99c0036a443.nq.gz
│   │   ├── ef0b95e2544ea0d09230a57dc01ac91e3bab9689.nq.gz
│   │   └── fbba4acd0312826cec9cfe18371c7df07962cb65.nq.gz
│   └── repolex
│       ├── 026f317933afbf49e7babd2a1fe7d19e86b1b5cf.nq.gz
│       ├── 0aa98c6abd7e8e1c4f585fa01a51a7607f501ada.nq.gz
│       ├── 297fc8e356e6836a62087949245d09a28e9f1b13
│       │   └── chunk-001.nq.gz
│       ├── 297fc8e356e6836a62087949245d09a28e9f1b13.nq.gz
│       ├── 3284e098e54c816c561ccb800d978b570f08c36e.nq.gz
│       ├── 497d9b67793ad9ca09d597c27d1196a94f57ddc4.nq.gz
│       ├── 515ec279a31168272c9f32d24f11735b69eb3217.nq.gz
│       ├── 58cde05bdcb0a53d87213b4a5bb605937f178171.nq.gz
│       ├── 71693a29735082f78fe84d7311f5e33aed69ef8b.nq.gz
│       ├── 7afa6391254dc176a2352475226eabf35f0d178d.nq.gz
│       ├── 98caea1496846935dd60a0e170c401e91ce9029a.nq.gz
│       ├── cbac3a73c628aed66800e993e3931fcb43f76dd0.nq.gz
│       ├── d762f0dbdaf8fbd4c3622d6efafea99c0036a443
│       │   └── chunk-001.nq.gz
│       ├── ef0b95e2544ea0d09230a57dc01ac91e3bab9689
│       │   └── chunk-001.nq.gz
│       └── fbba4acd0312826cec9cfe18371c7df07962cb65
│           └── chunk-001.nq.gz
└── blob
    ├── 03e0b64892f24b376719c1b4769b478ea150f97a.nq.gz
    ├── 0664a6f9b00bda23b25d7bc631902196b6444962.nq.gz
    ├── 07698ec2dcda21d8c1963c9e7ef32f3722647dd6.nq.gz
    ├── 0886ac6e3bcfd2444219a190b98bea0467f0a3b3.nq.gz
    ├── 088b3bca9839ee489eefa546a0773a465b8cd0ca.nq.gz
    ├── 09dd57caa8c364f431b4fe6cbf37d4cc3172687e.nq.gz
    ├── 0a839517dfa084e8a21670750335e526ebfc1f66.nq.gz
    ├── 0afddc0c39f1320c64328df5d1b02253b03c5b80.nq.gz
    ├── 0e94d9e0a19c69685fe33118750a013c7fd1ce50.nq.gz
    ├── 1028180710b4a75393732e85828ddd56c22f180e.nq.gz
    ├── 10627a6622d2f328453aff9003d7bfad0aa46b07.nq.gz
    ├── 1172d150bb27216308ffdb4350a879a3133d40c0.nq.gz
    ├── 12cd69b8fe587ee068141bd6c6ff68fb872ee23f.nq.gz
    ├── 137a26fb4f5ab2a994783f7453715b7099b234b0.nq.gz
    ├── 145fafb156fd433c9aaef4211f4697ae73172dfa.nq.gz
    ├── 16431d3a6abce01b83767c8ef8d046eb425907c6.nq.gz
    ├── 1a0ec17f153b1c02d8b7b05d499e973ae095a8a8.nq.gz
    ├── 1b13b0552857c03846f82380614ef5e6875192a9.nq.gz
    ├── 1cddf087e93e5cc093920ea73bd2e12edccc3775.nq.gz
    ├── 1efde82b173ffe47e0b7410a7d28addacff74a11.nq.gz
    ├── 1f47f125e5c06e827ba4df75cffd838547a4163a.nq.gz
    ├── 1fe38f17fd80188cc3ddad1293f5cbb7e6a46057.nq.gz
    ├── 21a7e0621b79658222ee673ac2d9c6f9336469d2.nq.gz
    ├── 220a5917d9d404a761952ac1e37dee69093ce4af.nq.gz
    ├── 22228a1cd2fd561782e0fc49bbbe17d61007f4d8.nq.gz
    ├── 258a50e52003f9d42f617fe449a4ed19d6a2a922.nq.gz
    ├── 25f00d3a4f2795dec69d65c68ff7cb00e659afbb.nq.gz
    ├── 275540154ea5b5a7e3031939c952d774e42c29ed.nq.gz
    ├── 29e4a3dac13f28e9c1a72792ccae83a03ed193d6.nq.gz
    ├── 29fd35f8557158826f728f846f4c631a18469400.nq.gz
    ├── 2a09b42ea6b0f8fd8414566dedb3f50c6907e2b2.nq.gz
    ├── 2ad0a4c01b2e8c146c7ee4f8bb9aaf4caf1d1f72.nq.gz
    ├── 2c4a109ad92457335399c037212761eff2dd46c2.nq.gz
    ├── 2c57ad3e535b0c86d94be5078eb720896cb123a0.nq.gz
    ├── 2eaacbc67e989c802175a0e7569231be6c534fdc.nq.gz
    ├── 2ebdc53c58d467e82df973a0f45a844080cd9142.nq.gz
    ├── 2ed44981ce37a2343ab0669b6416acd2bd45b000.nq.gz
    ├── 2f350677e4b1f3124cf2d8cb6fbdef5dea74aa33.nq.gz
    ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
    ├── 320fb0a93bf7be1fab621b0af0c2a7621ac6c61a.nq.gz
    ├── 346900b20057ec00e57daea6fe05344254f1c168.nq.gz
    ├── 347f233644a8731e85af90f2af1fc8cd91ba3410.nq.gz
    ├── 35f38daaa4f03fd67f547f3568e59dd24cfe644f.nq.gz
    ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
    ├── 38d56b8ca5bc5560d4d3d79d8038f60aa6902af2.nq.gz
    ├── 3a41e7a648dd5d7def6330807dd1c50eebea3ff3.nq.gz
    ├── 3acf91b56dd66374dac163741109a7e7f2501efd.nq.gz
    ├── 3c463fb82d53e9a9616acfbbece0eb3be6d0d5e7.nq.gz
    ├── 3e535dc3da05af1fe0968fa79595d7b4b597ddca.nq.gz
    ├── 3f2e0c99e8f4b3668738c6b473e72211b9c03d56.nq.gz
    ├── 43fe56371ea4d8ddd824e52a311e7f39d175aa20.nq.gz
    ├── 49dbd10446a4c8944ab9784995c2c5df93a596cf.nq.gz
    ├── 4b8c70128be422f42f7b4c6ca81b8dc96d5a1816.nq.gz
    ├── 4c395d7ba6005500b71f8d9bea5fb4c3abe371d2.nq.gz
    ├── 4c654da7a361a02c30ea0726cf3462c833ff1683.nq.gz
    ├── 4cece02ab4d995c1fabac764e684ac72c6c487e0.nq.gz
    ├── 50f1ac1dd62260bba694ec5ec3d05593f88b89e7.nq.gz
    ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
    ├── 55b10b98a42a49d7a912d0a29882e60fecf62c2b.nq.gz
    ├── 5691977abc0027551386f2fa2491689aa357a5b7.nq.gz
    ├── 56b2e26e8ce4d2252a916b66a19e423f53f9a415.nq.gz
    ├── 582c74913678c05ceb00c7e7aa9ef72aa52fb0e9.nq.gz
    ├── 59617aa88a85f9f0034110afecf9091dbc21c8a7.nq.gz
    ├── 5c45e646c52a84a9f64f6b5dbeb48bed45f70181.nq.gz
    ├── 5c5af40f551fa54f8d869ccf9daf0b7dab9226ac.nq.gz
    ├── 5c999c6cf8f6f36cf679effb965fb76d07d98c7e.nq.gz
    ├── 5d2693890dddc34129973f5613afd88767213b24.nq.gz
    ├── 5e83f10a117c4717975327337ef43d0a14a91e96.nq.gz
    ├── 5ec86ad1c6a95d8b3d0e71e601e959eb7818741a.nq.gz
    ├── 62e5632ad8fd531fbc17dc99ac062d413e93a002.nq.gz
    ├── 633f63f599ab7e489a0aa517526168ad3d53e314.nq.gz
    ├── 65fa1717b78258e9cf205d23e5a2191e9fc3f588.nq.gz
    ├── 66ed6e888db15bcb9bb504b9f1e881173240680f.nq.gz
    ├── 675b2f9f355093469545e97a45fff3cbeac39444.nq.gz
    ├── 68f9605361a799b32123ed7dd3245c5ba2d95012.nq.gz
    ├── 6a8dc5e6779e697bb2ac0b13e432c10215e5a404.nq.gz
    ├── 6affff18a365878504394923a19c77052fdcdccb.nq.gz
    ├── 6c5be3fc648890514a9fba2f29596e4c05fd82df.nq.gz
    ├── 73c2955827ad692041b0c7785b3593c76f377daa.nq.gz
    ├── 7481c52a8643f58be128ec249b4cf76dcb81a053.nq.gz
    ├── 758aa2374264a23e80d7ac5a6212e035b433d16b.nq.gz
    ├── 77a0efb708f7949083e116cc5f3beab019acdc89.nq.gz
    ├── 7893348a1b7dbb588983a48e6991282eae7e1b55.nq.gz
    ├── 797506ace86f7a467eed183e83c355f2805bbf2d.nq.gz
    ├── 79cd99729a490e6a0d9d4e8eb14d121d42a269f9.nq.gz
    ├── 7bde595c10a8f83dde52176c0c64401ba38e5d50.nq.gz
    ├── 7d51c9fa96f872481664322a8729020e2b3d7c7d.nq.gz
    ├── 7dfa3f60c7c7f4c91184d3e9b6e3bc2bda49bac9.nq.gz
    ├── 80a099610d335c3b6ec4177ff3600e9087ab7c75.nq.gz
    ├── 8117b2716d110074d9a81365c59343e81396b7f5.nq.gz
    ├── 83b6236963f439e6d4e87ff54a9d7b0af1388f93.nq.gz
    ├── 846bad802a491a63ccd2e147c64274642d6e9fff.nq.gz
    ├── 84e02176ac7e8d88785420de940e0aa8274710c3.nq.gz
    ├── 858a9485f2445e6a4d3782b3e2095cddf85d3b4f.nq.gz
    ├── 85d9ea16be79fd706d45b64477e66c5578e6cb39.nq.gz
    ├── 865c68597994a02456d113489a5d931464d2b9c5.nq.gz
    ├── 88fd7721d483dca4bc611eebe819082264754002.nq.gz
    ├── 8a315f23c52851b23525d205e392ee69e0a27f39.nq.gz
    ├── 8b7096acb1debd2c584880502e3739f7a4ad3d35.nq.gz
    ├── 8be59c5dc36bac6517788b5003db1822a89a6c2f.nq.gz
    ├── 8c8885852a26eba90d3ca1783beca535d4d43bb0.nq.gz
    ├── 9129982e4171c5dd5d9579b6360b40e196a3e71e.nq.gz
    ├── 919bf03c5092e557b164e7e2322b12ed74d349fb.nq.gz
    ├── 91a61c5b5fe0ef8066c058d252c2cd733ac7e86b.nq.gz
    ├── 91cccc49916f3db7adc8df753adb8d94cafaca70.nq.gz
    ├── 934667208193ebd28a493d1ad140fbe778689384.nq.gz
    ├── 93a10f89067f012f5a3ecd33b93caadef87d0779.nq.gz
    ├── 94bea3879541ab873dec0b369cb67817ac6efc0d.nq.gz
    ├── 94ea08e53af7602fd0559da3b293be8545fa0910.nq.gz
    ├── 955deaf27bc821a6367e818f36c016892fed3d33.nq.gz
    ├── 98a1b908ac531a93e9c7ffd5ec608a4fc339b3f9.nq.gz
    ├── 9c41add09df3d46c430de808e6793cffacc5858f.nq.gz
    ├── 9ced67f316b79547e1f4a14a95d1c63002885d19.nq.gz
    ├── 9d227a0cc43c3268d15722b763bd94ad298645a1.nq.gz
    ├── 9e7000aa2959a721679aa784987a0139eb94c9ba.nq.gz
    ├── 9ea34cc523f28d27902a8cef7696f4827476f101.nq.gz
    ├── 9fabbd27ef67de09202c2ffd728920d163b9e6fb.nq.gz
    ├── a1e262f497fcc0eb564be79ff9ad7c219ee66525.nq.gz
    ├── a2d0e73f995ecdf0137b17478403045a973b3558.nq.gz
    ├── a4c35717cefa0ac8bf3a3811233fdb9c4e19f36a.nq.gz
    ├── a53a98cf3d4b093c6696becd3df4e1c6c0660fc9.nq.gz
    ├── a53c2619e58565852a775772c32509ba8724ae0c.nq.gz
    ├── a5ca3effa199ab1708ed9dccddf8cbcaa4a1b81c.nq.gz
    ├── acbd83f90b38e208b211fc7e62366556e9565dd8.nq.gz
    ├── ad2480c80d071a86a442b037bb0843f01bee1126.nq.gz
    ├── b34cc6ee02097abe3f69e7c34a75e7312d4eeac0.nq.gz
    ├── b40f24c66dea9a3b6c140b8aeeef96078d40a2ca.nq.gz
    ├── b48a303da5c5ad551389b0db8096a0e22fe58006.nq.gz
    ├── b57ae2474fdb032ee128c9ae55e7e9796f15ad95.nq.gz
    ├── b57d2bec8eb939a96bfe621a3c47ea8d368bf8b1.nq.gz
    ├── b5ff67d9a03c78a59b1307148d7ee6d41d381b48.nq.gz
    ├── b67eda4b18fb996657665868cb4d36050b735799.nq.gz
    ├── b786e0725de81e3dd9f00f5ef399335cf8581eec.nq.gz
    ├── b7dbad4808ae52c62b60b76e45b4bf1e863bcec7.nq.gz
    ├── ba3fd777497d8a8369916141293596d11055363f.nq.gz
    ├── bbe6e992aaa73095e57892813e67be9560275150.nq.gz
    ├── bc8ae07b6f962603e3a56b59fa8a23af3f7ae0fa.nq.gz
    ├── bca464e088727dc8e41317feadd9195d5bade7f3.nq.gz
    ├── bf53facedda195d83bffe9defc4c7ca9765f9e39.nq.gz
    ├── c14f9170e9814f5ee6328b683f1ceeab169d29d6.nq.gz
    ├── c1719207f950066aacc84beafcf311a9e60c787d.nq.gz
    ├── c4b245d256d38f221cf0813d208f77ad0521d0ed.nq.gz
    ├── c790fae5cb82c522b0c9142e5c41e0971634ab46.nq.gz
    ├── c9de47513e2b7490492c88c60a8266178577ca2c.nq.gz
    ├── cc6adb7286b3336061a7a219e9d70a6f0fae5472.nq.gz
    ├── cc79e281a8363ad2ad5ab017eb7d7aa75f9479a1.nq.gz
    ├── d01eb7407268fca4af5359332c33bea65f028c4a.nq.gz
    ├── d040ea8b1c685582d5c8c17ce85e4554a76dca1f.nq.gz
    ├── d19a4faad8b4e1c216879daf1e4ed7bd88e2d79e.nq.gz
    ├── d399b1fc53a159b8d412f05fb57b1a4e42e673e9.nq.gz
    ├── d50e4e0dc798d6edd3c135a63e5b7513da8b644a.nq.gz
    ├── d66d8afd6b386fb72dd89ff0963f9cafea1d0b9e.nq.gz
    ├── d941970b8e98fb1689042f851f91bd59b4226f25.nq.gz
    ├── dec87af0737ef20204204694f79c663594a918cb.nq.gz
    ├── df8fbaf908a146679dfdbc5340997b9e8fe8f19b.nq.gz
    └── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz

14 directories, 200 files
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
*Parsed on 2026-05-11 by [repolex](https://repolex.ai)*
