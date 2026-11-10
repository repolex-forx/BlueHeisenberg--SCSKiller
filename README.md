# Repolex Knowledge Graph of BlueHeisenberg/SCSKiller

RDF knowledge graph data for [BlueHeisenberg/SCSKiller](https://github.com/BlueHeisenberg/SCSKiller), parsed by [repolex](https://repolex.ai).

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
rlex download BlueHeisenberg/SCSKiller
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a996cfe737bff9ece0e8117c463339c3b9fbdac4
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── a996cfe737bff9ece0e8117c463339c3b9fbdac4
│           └── chunk-001.nq.gz
└── blob
    ├── 00130c0b2e897784515e8804fb9bfccf98ef3dbb.nq.gz
    ├── 023dd995934f3a4a197e2725f6485e6ebb859f4b.nq.gz
    ├── 0252e7230cf5a39dff22c9997010d3c65e1b8c2d.nq.gz
    ├── 0322a2c697873410d7a3691778252e26787eda1c.nq.gz
    ├── 033b5ff635a2c0f6e280ca4021b44fe3de97280e.nq.gz
    ├── 035fbd2755766b2cfeb684e4c7221f119b6d650f.nq.gz
    ├── 045ae3869bd42cc89adb8bdddb662e7ca62f3768.nq.gz
    ├── 0481ac957e4724305818fee8d832635512cafb4e.nq.gz
    ├── 04f62a14ac548efcebf0292100ab276cdf80517e.nq.gz
    ├── 0580dabeca5b01cf791697a01cffdf74b986648b.nq.gz
    ├── 05bfd9ecb82bf0134fe434d04eb94b596f2a87b4.nq.gz
    ├── 06e2c82ac5813cbdd35999557966a1ef44edea3c.nq.gz
    ├── 07438860de3eeb88aed14a4a64d72479c6727f32.nq.gz
    ├── 07b4fef18763d3a9faec3eff09e0798ad1f4d92c.nq.gz
    ├── 089a0facde5e4ca2ec5df3363463885cd407eecb.nq.gz
    ├── 08aaa4b3a8ab0e81a19eb05c94210b0c40ed757d.nq.gz
    ├── 092b7684f277c643f3628a95fa81c04559df7740.nq.gz
    ├── 098a30ee68c5a724d47922c3f9ca045f61578fbd.nq.gz
    ├── 099ef9fed541391b0de91c77baece7239298f2f1.nq.gz
    ├── 0a1585b5ff9ee9f4ab55ffde821b51b374830e6f.nq.gz
    ├── 0afc5ff1c79d0b1a784e0d3000193d757310d6ad.nq.gz
    ├── 0be5cf615842c5cd2ecdb58739cea307ee075c5d.nq.gz
    ├── 0bf3cfdefe00e5243a010377b8d8d8ad2e7bd52e.nq.gz
    ├── 0c0a17fe2ff95becc78f01cfbde4ff9d48a4dfed.nq.gz
    ├── 0c134f57d75d17ac050d8eea1525a2395d39a91f.nq.gz
    ├── 0c334c31e32c24dd2c4b954e151b201f6690b326.nq.gz
    ├── 0c8eecd03bdf26334a68b050a3154e34745a5725.nq.gz
    ├── 0c9ead304df56018cd7097cb186453b1b93bc94b.nq.gz
    ├── 0cd61ba42e35c53f5c36d76740cffec90cafa999.nq.gz
    ├── 0d539d22680a2b7311252af75e6868ab8d7dd0b9.nq.gz
    ├── 0dc76737af8ec9518385ced46b78c3045c8e8b5f.nq.gz
    ├── 0df75937a2da52ca7a01ee38a11cc1c23851f556.nq.gz
    ├── 0e07624ba7414824149c844972c9590cfe858bc4.nq.gz
    ├── 0e9fe7bb1098d0988f00b3792dadf2d878ab4834.nq.gz
    ├── 0ebcddfb8cc1cb3d06cbc9f635f40f10fe0001bb.nq.gz
    ├── 0ee2a16b074f123d50e30503d4a7ce9ae208bd5f.nq.gz
    ├── 0ffad698cb6ea10bc89bdd8e597f19f40e5b4395.nq.gz
    ├── 110aef53784919f8beaef394b70359e55fd7f22b.nq.gz
    ├── 11fc775ee986b6eb412a589cf4c832013e8b54c8.nq.gz
    ├── 120f2f419624e243698a929f5a3ecce413cad834.nq.gz
    ├── 133e183eea38abd433864f5033e98fdce6024c07.nq.gz
    ├── 1374f946e689389b2be06fa68afe0602f5f2c0f7.nq.gz
    ├── 148dfacd44345d5d04a091d7fb7b7585b0394470.nq.gz
    ├── 14e64756ecbbf5d3a84ccea0fed7f1317c06a1b2.nq.gz
    ├── 14ed514341377610464c16df674ec601692849e1.nq.gz
    ├── 154a182c765e2e0565c666b34150e3b62bee2d0f.nq.gz
    ├── 15a47965447ff7c4a34ce80afb03a5d63c03fadf.nq.gz
    ├── 1611deb616d51fe2b8c13e7edda253e5e215c51a.nq.gz
    ├── 16a73f68c4554aad38538723ab89dec74f14aac2.nq.gz
    ├── 1799832d6ba011bca7cb6047bbb265457736efb1.nq.gz
    ├── 17a978dcf6361672ec05a6a3aec48dd969f9f35d.nq.gz
    ├── 17ac5db63314fd066acf6000a823650e55f4cbbd.nq.gz
    ├── 17af7cb2aa2890445ac1f53daf4ca38b4603c1f9.nq.gz
    ├── 18be5a9377a04c6d7ec0fe93228451dae7221060.nq.gz
    ├── 18c82b52536105e1db4e086b6984a1f101b5e981.nq.gz
    ├── 18dfaae0ac56f60b1bc810265077c80355a0bda8.nq.gz
    ├── 197132df3539e7045adce4d5dbd6ea3751a08610.nq.gz
    ├── 197dd2c4d0bb310bb0cdec3cb3f3f3ebf146b401.nq.gz
    ├── 19b0ae0a932d4236131667d41a92dacf4c107cbd.nq.gz
    ├── 1af2a8de5cc7eaae513ef24d665ec6f7197d52e5.nq.gz
    ├── 1b282fa03bfff0315053ebb88c2a80632fa71b31.nq.gz
    ├── 1b5046b8e974a9610d10416d49c44d4ed01bf0f4.nq.gz
    ├── 1bf90ff2676fc6d721de078deb4077fa0a845be8.nq.gz
    ├── 1c7f5257d2b4d6a6b1fd985a29b43afb4141884b.nq.gz
    ├── 1ce47467c7acc3f9b4638d8bb1196eb22d7edebc.nq.gz
    ├── 1d5632c744c0637de7345ff02771e80851e16be4.nq.gz
    ├── 1dab2d5e80bd4db63be008f5f2d682352419c50f.nq.gz
    ├── 1dfa00cdd1dc752d347fbe26971fe83bd91cfc79.nq.gz
    ├── 1e23a079ef4743f4f644cad288471fb24f0e9fe7.nq.gz
    ├── 1ec9ddfe3bd4a2c5ddcf2f0e39576bb07bcc51e1.nq.gz
    ├── 20b01163e38c2913b42a0e7c0a84f0198f070165.nq.gz
    ├── 21297c68fe64da72028b8a6e289ce4859223d5be.nq.gz
    ├── 2134a7650e46fa46c4d1197076f86c7e786ea239.nq.gz
    ├── 21558654a824454be7d6910f11473d38d777c6fc.nq.gz
    ├── 21d47b91326d4e36951864137055e2afa307b725.nq.gz
    ├── 21ffeb25fcc818536f1928642cb3989a12750f05.nq.gz
    ├── 235e47840401a00c51f1ff04bdde6f344bfcdd3f.nq.gz
    ├── 23a742b097ff3b36f42c8d23d9e1b35bf209eb90.nq.gz
    ├── 24c699132ca846519af4e1b5b4549c07bd6236b8.nq.gz
    ├── 24f47e4e340c722fa4d018f8753f6f2fb18d5cc9.nq.gz
    ├── 24fd377f201582e71538ff9974e1d3a6c9405733.nq.gz
    ├── 25200d8f2b1956d0247105412a8bcfaed0926f55.nq.gz
    ├── 25b64a3c0e02f8c05ee4700263f0d58739d076dd.nq.gz
    ├── 26224e9c2496f1e987b1bbe2ce21551ad03a588d.nq.gz
    ├── 26461d6b5b1617132ef722890de5cf88b38273fb.nq.gz
    ├── 267008576fe27ffd23cffe2d16ba07efa41f427a.nq.gz
    ├── 2711a4bbb005d54dc14e634ff8265ad8dffbcde2.nq.gz
    ├── 27563e67a5dc64e5070345c99c6eccbd4cc7f3be.nq.gz
    ├── 287561cc94151faeef570bcd8c5c08ee7c724738.nq.gz
    ├── 2896b6da96181124c14de987649f232938033809.nq.gz
    ├── 28cbfb98ad90e63292fd84ed2fac052c06e4db90.nq.gz
    ├── 28ea7407861f352a76b60f825a9853bfe16700b9.nq.gz
    ├── 2901eea67e71509512dd7d4588030db2cd0f40e1.nq.gz
    ├── 2940ae95b1bf5d96d5aa70fb836806c0c07cb846.nq.gz
    ├── 2b93f0517666bad6bac5f6f7c06fd19a6a11fb19.nq.gz
    ├── 2bbbe514639f8788ee0e5580158f184ddad20499.nq.gz
    ├── 2c0ad158e07fac24cf1c38a22a9b75ecc722d872.nq.gz
    ├── 2c2924086e3e5cf94deff48339f8b477d94bd3f3.nq.gz
    ├── 2c4986cb50a2b57943d47de9d5fea34404ba3d7e.nq.gz
    ├── 2cc4aa045a4bce56f190e8bad5373bc97b639397.nq.gz
    ├── 2d9a00d4e445b85686beb4d788a6aff7b7c252c1.nq.gz
    ├── 2dba6deb64beae4af379df4ca394ca5971ed6dad.nq.gz
    ├── 2e981c588ffc8393ffe6b7090acf65a8599c4e05.nq.gz
    ├── 2ec186f58784f80d802274f470e2077b87cba794.nq.gz
    ├── 2f6493625dbe077000c157e1e4d0a2e07584d379.nq.gz
    ├── 2f967cdea5d6edbafeb870db0044e70c5f8fde59.nq.gz
    ├── 2ff41ad9a399ff71a5b703555923f6e9d58a8f5b.nq.gz
    ├── 303827f7ef15b79333707aa648b9848b4c41b673.nq.gz
    ├── 306c3cc1e29648e82ad0d9bdf981a49b1b723051.nq.gz
    ├── 30fafa716b3c2611704e5bc9facce7c6c8e9a5d6.nq.gz
    ├── 31583b0a54b34142ec69e69663b5750fccb5fab2.nq.gz
    ├── 31d51c3ff6cd4ccf1af36de4a5b73f0a9f5bb6d5.nq.gz
    ├── 3211c8c0c60c1ab0a596d7d7e2b34582bf78607a.nq.gz
    ├── 3242133ff038f3e1d29397248c4277eb3155fde3.nq.gz
    ├── 32b5e215b3131e3e684f45e0b8b5e3389a2b43d7.nq.gz
    ├── 33480a45785fe0751fa8ebb147278b17a2442aed.nq.gz
    ├── 339043207469dbe5d75d93fdad0ea9498ba334e8.nq.gz
    ├── 33e750d98d651d5dd720a3f1a7cb0bfcff325dff.nq.gz
    ├── 34116cda4561b9efd676407d76dc8804c58e671c.nq.gz
    ├── 343baaa4e784b500cd1a32cab5d4219d19f755dd.nq.gz
    ├── 35ce364d57250283de8a12b62c8333b0d06b8e28.nq.gz
    ├── 36cd5d77639ff149189b50fbc6cc6adc6d88379d.nq.gz
    ├── 3728b3ee5f9f828f0449a38b0c5a3352e44a9b15.nq.gz
    ├── 3765f3f773e3eaf7645c989734bedd2acddceb7d.nq.gz
    ├── 377352601dfe93e43aceedea2cf6bc5477a0cf98.nq.gz
    ├── 39e60923c078d55f15715dd9f1c0173d706a258e.nq.gz
    ├── 3a35d293b5de6d747a29c11459290b046f86c0f5.nq.gz
    ├── 3ce6fd7140a1f88a6981085d15236e84e2726d24.nq.gz
    ├── 3d388252ae974ac2655d159fc13032567f0ce68b.nq.gz
    ├── 3d798a719397449139785d028d32757e07a0daf7.nq.gz
    ├── 3dd8b1465f032c6d2dc3660b92e69a084f47f9dd.nq.gz
    ├── 3eb390e18758e3eafa12dff69ef4669449a6695a.nq.gz
    ├── 3f1cb93758992f2bac4de505bf90cc3a54c55a51.nq.gz
    ├── 3f33dbedd64b845170ed3694c11ce9e3faf02701.nq.gz
    ├── 40c335d5147c7d8ec44cf03f1db46616142f0524.nq.gz
    ├── 4334ad2dee3f5a6b485ac734c729c7d16eff4dc4.nq.gz
    ├── 435522fe660b8cbf1602aed6342855f0fe3c21fe.nq.gz
    ├── 43a0eb977cb517a56af9f59c24f9e78d36fd1abd.nq.gz
    ├── 43d7dc91c444cc7bca1375266d332961868f8f30.nq.gz
    ├── 440d0e0310588c160cf986dd8204b2a0829a0664.nq.gz
    ├── 448ff022c29549af46f1477fbad51afc1d389234.nq.gz
    ├── 44c6f0faf0b98cd8c90ac18f3b620e6ed5ced37b.nq.gz
    ├── 44d0f7c5419d7f6315d46e820a7c85c086696165.nq.gz
    ├── 44dc5c445a739cd706f1122952f7736125e4e865.nq.gz
    ├── 454e1a7f571810fd59e6c3b904c6d14292322b74.nq.gz
    ├── 463b8e56276d4836345e33c76668740d2db490fb.nq.gz
    ├── 46acde062ca4a369ef90581d4e64aa664533f7d0.nq.gz
    ├── 473b81a7f42cf3094541cc81b1ca54173a9efb4c.nq.gz
    ├── 48239a5fc87b50ae168869aa499724106628ed08.nq.gz
    ├── 484d5f7793ac5f21c55684c350e2615ce55c7723.nq.gz
    ├── 487c7494aa41cde96a54e7d9ba439fde9e0d5247.nq.gz
    ├── 49ebbf455963ef722ec35b0981d78358158a1eff.nq.gz
    ├── 4aae57fd2b343d2c0297c06e4bfb79adc234a9f2.nq.gz
    ├── 4ad9d7112d3a51a6276042917ef670a8b600cae6.nq.gz
    ├── 4b19e4fca0cffe7366a7868559cfef6f58e03bff.nq.gz
    ├── 4c258ac23191e59f64a979ce16b93a62b8371a13.nq.gz
    ├── 4c56f1c9066b07753935f39d73d67f1ff5516d1b.nq.gz
    ├── 4c7bad31f621f23235f843bd65b39bda57dd814c.nq.gz
    ├── 4c9a820988005db402ea339b30e16c2fee1568d6.nq.gz
    ├── 4cd21bd153cdb0dffaf9e3f7cdd124f3cb9faa29.nq.gz
    ├── 4ce51e4e2f2ce7fe479c9384894cba669302d498.nq.gz
    ├── 4dc2928461646979c7e4fbe9537dab0a77129f02.nq.gz
    ├── 4e8e1b26e4c21f2c8ed3d22a29a2b12c37703afc.nq.gz
    ├── 4eecd73e515017abf261f079137d2fb91b4d44a1.nq.gz
    ├── 4f0ebd3aaa5ac9067b5b79c5a4cdc35d8019580d.nq.gz
    ├── 4f14337021b4d2b5ac8a3bf22c96096af676291c.nq.gz
    ├── 4f755d1633654e14243b8158797fdd09df5de8a4.nq.gz
    ├── 51303eb8311b2f3206c937a1bc6d43c31ef57e3c.nq.gz
    ├── 515059eefd7f6f512aa03fccd8149868063b4e3d.nq.gz
    ├── 51645b294e3d814b6d1e4b486a0df18cef2ce4eb.nq.gz
    ├── 52268e4194e616535249787f4a42fcce77bd3e9d.nq.gz
    ├── 53ab37e910d600ad140b55d2319678d0b66025a9.nq.gz
    ├── 543580aea74e2f208d0bf8a4937249fe8309a263.nq.gz
    ├── 54f45a1123111f390441d3ba81f3bdbf92140900.nq.gz
    ├── 5574d79913eb219ec0d0c646a53eadcd9589fab3.nq.gz
    ├── 557ddd0b92bec9686a83921c71aceeaf5915871c.nq.gz
    ├── 5639a587e9076385962642734e63e4d199ea4228.nq.gz
    ├── 563ced021aa69ab5a392544727c4b0f3c94fffcf.nq.gz
    ├── 56f6c2b53aa0877ba9a22793084de9993f205404.nq.gz
    ├── 58244da3ee12fb852b9742dbc4275d4c9376f6ce.nq.gz
    ├── 5904e4d3df4a982b305b78db1edfbc8626fb9461.nq.gz
    ├── 591044be94c65ae50df81a14d97e129a5f2c136d.nq.gz
    ├── 5a2938264b497adc76976db66a006e237de55420.nq.gz
    ├── 5a8751630e8f15a14622d643979c4e9687a6c5ab.nq.gz
    ├── 5aaca9175adac8bf5b80c77ddf7181e2cb96d0ba.nq.gz
    ├── 5c70771946b602087e57ccad5feb4b4824217b9b.nq.gz
    ├── 5ce7369be302ca7927c056d9f66bf2aa45fa65e6.nq.gz
    ├── 5d0075609ad04dd6d04b47eaa9b25e6d120577cd.nq.gz
    ├── 5d4d6c39c2488955c688f2a16f0458014d001500.nq.gz
    ├── 5e499c793c261defdcefb53bb3073809f93ec758.nq.gz
    ├── 5ec501d8e3e30086e0d7069db5eab2751fef23ed.nq.gz
    ├── 5ef18146b55b57c4ff33ddb53b699e953f292827.nq.gz
    ├── 5ef19fadd3b9360be3366d3635ce25662fc937bf.nq.gz
    ├── 5f8f80468d71b734780845a9bec91faca4aa3e7d.nq.gz
    ├── 60176047ed473406889a6234cc692bf897ae8ce9.nq.gz
    ├── 616b3acf59178c5a894a8687d25c31acb1090e17.nq.gz
    └── 61bca82c1d87d2891ff2e01b29f854d4a778e2dc.nq.gz

7 directories, 200 files
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

[BlueHeisenberg/SCSKiller](https://github.com/BlueHeisenberg/SCSKiller)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
