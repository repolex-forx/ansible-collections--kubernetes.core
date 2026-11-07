# Repolex Knowledge Graph of ansible-collections/kubernetes.core

RDF knowledge graph data for [ansible-collections/kubernetes.core](https://github.com/ansible-collections/kubernetes.core), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/kubernetes.core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 782672d2fdb0004d593440a3ddd4b9db014d9e4b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 782672d2fdb0004d593440a3ddd4b9db014d9e4b
│           └── chunk-001.nq.gz
└── blob
    ├── 002c00238c64d8d1e32cf35f2eefb69e276687d7.nq.gz
    ├── 0064e8ac33ace2e18d527e6013ff91bdb455696d.nq.gz
    ├── 00696503c995d3278b1e914d12f0b06c460a0bd6.nq.gz
    ├── 0070d891031b7948be6d259193f511d0e588221d.nq.gz
    ├── 0073319bd460abdf03acfafa8dab6ee1111f675d.nq.gz
    ├── 02363aaf7b009f7753a649db52581ef0709f10a2.nq.gz
    ├── 029b5854e742ff05a715eedbdc0308fdac2e8f4e.nq.gz
    ├── 02eb1d618867f902fd15e3a5ef7bc8213b8cca1d.nq.gz
    ├── 02ef146038ae1451839fff4973ce64f150091888.nq.gz
    ├── 03fc72695bf8d6a72cfbe60fe3308e9c5e264d7e.nq.gz
    ├── 04d84eb56e9f72965f3c712fe406876ec0cce574.nq.gz
    ├── 0562d59ce4b26a6896f23ac08d54ae33b67de57d.nq.gz
    ├── 05895d249ef7f72a950ca09cd2656a5013f1735e.nq.gz
    ├── 05c096f98ba61aa380c30ef8ed3781f6387c569e.nq.gz
    ├── 05c3655b96255361019f2b89e9a5e12b33c05f75.nq.gz
    ├── 0676e9f640c010a71cc4012bc209d62e158bc0cb.nq.gz
    ├── 069f055393e33f2fb716236cd88e5f4e50bf411b.nq.gz
    ├── 077b53b4131d2c0fc0bd5fbc4035d55cc7c6f638.nq.gz
    ├── 078108247ff167b6245e15881d5f4efc2a716a9a.nq.gz
    ├── 07e77915683fe10f1aa94771fe9aa764434f8c65.nq.gz
    ├── 07f47a635f035a0fe5c2e3fa9baf91d66b891cab.nq.gz
    ├── 07f7c2935f40a0412a543040ec896b15e065d903.nq.gz
    ├── 08178602aa06fba4c68f48d9bd3fbf1baeed15f5.nq.gz
    ├── 08362c7808e554116ce825f6587fa2277e62170c.nq.gz
    ├── 087fc2d71e2be251b8888d308bdde0958569e067.nq.gz
    ├── 090a0293149620b03dc68f80631f533fb16d2efd.nq.gz
    ├── 09bcf301fd8d4e8c0876f15a1d27c65747028512.nq.gz
    ├── 09c0d3554a8a6b8b153702c478973bef847bc6a5.nq.gz
    ├── 0aa275af9cd0126a6b714af8b2b50384dfe16f92.nq.gz
    ├── 0b1524cf3d9bcd65ae86699c9ee7f553ffcec5b0.nq.gz
    ├── 0b5a723fba82819f7b16643aaab0ad4d65cf40b0.nq.gz
    ├── 0b7156d5b68921244399a2a9e22d32ab9c8152a9.nq.gz
    ├── 0b76d4d0c3c196d7d1b3bfa06a6a7358720e0508.nq.gz
    ├── 0cb0a524bf38b87dac286ddefaaf98d5ea66c01c.nq.gz
    ├── 0d62f5859cb7f03248e8ddbe89e8e101ca712277.nq.gz
    ├── 0d8c3ba4c8845b848a01b7d180cf21f4383ea591.nq.gz
    ├── 0dc4600a68e31066dae7e6cacce485ce0635943a.nq.gz
    ├── 0f792f5408a1e78110a8bf033a906ea82d55467a.nq.gz
    ├── 0fca150032eadd6f769612e65ec4deb86668f521.nq.gz
    ├── 104b16661127a0ac460330d67a6cd5fd925186d4.nq.gz
    ├── 106e8b440995373700f4b09fbca5e04d54148924.nq.gz
    ├── 113fc5294c530ec429bef14781ffb5d182302969.nq.gz
    ├── 118fffd525aeccf6f5b3f6704ea33d65e3c9c3af.nq.gz
    ├── 11b5830baff148860639e80d1fdaa1101d7c8b28.nq.gz
    ├── 11d34cfbfa0328a345151ee644328c5b4cd90c49.nq.gz
    ├── 12af64a9c6a3c787187a566bbd84ed45ff0040bb.nq.gz
    ├── 151289105a7c94179ab61cfe43ef00502eea3fa5.nq.gz
    ├── 15b099c62e7f30eadd6ee32a6596df62e15b9e9d.nq.gz
    ├── 15debdbdd3ba97e7c1e3a19677efbab903324366.nq.gz
    ├── 1792a2d81831e5bb35d001e62a2908d3f08709b2.nq.gz
    ├── 17b302531e12a0718ccc4792e360226297815273.nq.gz
    ├── 1855427a4f7594c5de9adcde0d170f87280e0d07.nq.gz
    ├── 1858b94ea0e691ce1589b5e57970462b653bb54f.nq.gz
    ├── 18c46bf928135e396b20775ded7b39222e9c3235.nq.gz
    ├── 19e1226b0da126d7730be6edd743c384cc19771b.nq.gz
    ├── 19e18bf7a5066f3d5644672a4fa25c85d520d570.nq.gz
    ├── 1a4e6112268b6702c9cb9893ca1bca00392a197e.nq.gz
    ├── 1a5ed844a6f5eae3ed6e3a389cd7ca52edcf20b8.nq.gz
    ├── 1b015d1e9185fe8f640b38f2965bc93c3327c60f.nq.gz
    ├── 1b9e873d4e5c2e585b9e204be77c18ff6b1826c3.nq.gz
    ├── 1c5bbb1bfb0ee1b845ae652eb89bdb36bec62baf.nq.gz
    ├── 1cbecc09c3a8a82adb6cf014c3b053c7b7dde4c8.nq.gz
    ├── 1da505e92ca9a9c335c96f0197c99c808d118e53.nq.gz
    ├── 1ddeb31f04df36a98ce84747e7aebc63635b305b.nq.gz
    ├── 1e0d45ec3ebceb7427942da4468bb13b1184039d.nq.gz
    ├── 1e27bd950901b2d4343fb55e7ffc5946034af842.nq.gz
    ├── 1e4303607751efe8f00e45b061e66c845ab944bc.nq.gz
    ├── 1e8b394f1a7872c194c070f7789043ca19c8a7a0.nq.gz
    ├── 1ec791988be20ff26d27a3944c4622ef77c2cf60.nq.gz
    ├── 1ef60c4aa801874bbe982f305a529bd0f85d301a.nq.gz
    ├── 1fb6e2349fe0fbe41fd9daee9a9d22605071a513.nq.gz
    ├── 2105bf7ac639c8f36c8e5c1231d21a78e465f95e.nq.gz
    ├── 21ade8a6d0f5f0269f7133a57997d437f6e102c2.nq.gz
    ├── 21df7fdd5c51abf6b7c36ad26eee2c039fea1b17.nq.gz
    ├── 227d5ba25f351109806c4bd3008e0b5f6dac60ce.nq.gz
    ├── 230caa771e6289eb0ed40f5d7997d543b0a2d08c.nq.gz
    ├── 235c469369aebba412a80874a31f082daf7d7beb.nq.gz
    ├── 23d0663c30db56080f92d5706d628b2a8080d385.nq.gz
    ├── 24133ba533cb972916b3b59d1d45b75500699f0c.nq.gz
    ├── 250354e210f89c9561ffce502cbb85d8b77895ee.nq.gz
    ├── 26219fe862cfc31901dab4ad0e05dbef70e603b1.nq.gz
    ├── 276f82f2b374052de3ea8442504992cd01d2694e.nq.gz
    ├── 28109689545016d51648d7827b350b5e90ea1f48.nq.gz
    ├── 295a154c2645bbe563383a8c66961b79a1116212.nq.gz
    ├── 2986b01ef32b5fcfe24cad40c31e34a4ba874929.nq.gz
    ├── 29fda1c9af5cd84ed9f7513372ba01c7e6b2ad35.nq.gz
    ├── 2a25b8c3b28fff083b999be3cadf3c6d8bd88fbe.nq.gz
    ├── 2a415adf32b8e94e04e0ed1655a08a85e59bc1ee.nq.gz
    ├── 2a81b7c3274b9af45620dbd3e426d184e0c253f5.nq.gz
    ├── 2ab2eed651504f70a7e28418a4630ccbdb7c85f1.nq.gz
    ├── 2ac78be47e628fdee5b48c6e50506f288ffc11b3.nq.gz
    ├── 2ad3cd0158277eba1aa185757cc51add40ffbad4.nq.gz
    ├── 2b77fbfd78c17a3f697850514bb9422b18306b9d.nq.gz
    ├── 2c48db5ab91314ee13daec2b2252375b3967d949.nq.gz
    ├── 2c83021b7cf96fefb8c8e4c2e3bf0a1aa3cf1f0e.nq.gz
    ├── 2da4a4a8776e25d6cf75c22bbf05ad53ef560f69.nq.gz
    ├── 2e3ba2fa377f3406298187a86fae43e7733990d5.nq.gz
    ├── 2fd8c70c5ca9e2a4b795663dee80e2402e88551f.nq.gz
    ├── 303acd53983a9c9c05a196ce74ebae8d34ff8c9e.nq.gz
    ├── 305e933d12a1261004fa6a8c1503c36fff38657a.nq.gz
    ├── 308f99e5833576f900620e3341506f06c71c9414.nq.gz
    ├── 320e4eb7fd7ae7ffddf431de818d9880d7d61152.nq.gz
    ├── 3330ef714595616cc996cc7c3acf3150ae568652.nq.gz
    ├── 334dc479878bc3915197f618fe631d2f2da8e71c.nq.gz
    ├── 349b62951faf24c898e2fad3b12a7d66cbbe0e6c.nq.gz
    ├── 34aed289f229961e0966f66903370c4223ead26a.nq.gz
    ├── 34dbc210297602ee7ad30eb2c128c85c05632182.nq.gz
    ├── 35016f458f496574e65929d84e7bd3366208fd69.nq.gz
    ├── 35a2f093bf34320f05fdab2f962251b7c2e3a2c2.nq.gz
    ├── 35acd7fb5ff4bee4a15091b93cb73545679cb26a.nq.gz
    ├── 35bda6ca7b33e1490e7768d7d15f0100a6f41fdf.nq.gz
    ├── 3607281149561f2e6ebc2955a2b47fbfefb0319f.nq.gz
    ├── 36c01bec4b29c29dbba4d650b9ec7505018a4ac8.nq.gz
    ├── 36cc49c0f286b2ba11c2a196ebdb91108e3ee391.nq.gz
    ├── 38be79f87c2a9090d78a8afa3d8168b7e4f22b43.nq.gz
    ├── 38c57aace517b240a69e3be7469bdd6d0dd3a1b1.nq.gz
    ├── 391764bd9005ab69c9239f53d74793931cde8d50.nq.gz
    ├── 39f51cef6318b36826f9bb3879e0f24c98e779b0.nq.gz
    ├── 3a20824104209590d419cd205c1cbe76df65df28.nq.gz
    ├── 3a32d89638cd76cc6bb236387af81ab464ae0afc.nq.gz
    ├── 3a6411e8ac0fb60b50ecc2457e0224496bda6fe8.nq.gz
    ├── 3b58e89ff3a1385dae0591754be6ba0ec965c951.nq.gz
    ├── 3b5d200498f7e87a0ad0bb8995e37580179c19ad.nq.gz
    ├── 3c0d402aea0c4eb2a7d11122309cea6289cb37b6.nq.gz
    ├── 3c4bb27987569b42d6a9813af6cf3ef8aaf9d0a5.nq.gz
    ├── 3c544c769afdc2d0916174592dbff15e4a4d5886.nq.gz
    ├── 3d0d3394a5469dc5d73e6423e9dfd4d0d1569f24.nq.gz
    ├── 3d7729caf3a3a0dd39b3cf2b9c8a1be19d19d69a.nq.gz
    ├── 3dd116108270c31b0f1b72411e7ee14b9c01e03e.nq.gz
    ├── 3ec1f599c476f22acc899de5bcfd7bae9bc2b6b2.nq.gz
    ├── 3f26f1dd10e62cf5aa4a15dbc9cdb972ef173cee.nq.gz
    ├── 3f85228bcabe78c019221e3caf7ecaf4a6832c5e.nq.gz
    ├── 3fda961713d359c6ea571a237947dff32e889129.nq.gz
    ├── 405ef0dc74c44a406aab38f47780e99344bfe7d7.nq.gz
    ├── 42770dfd06bbc5ee4ca928adaabcc6f859744a01.nq.gz
    ├── 4325987608b2b0c180238a97f09fb42dd3a89eef.nq.gz
    ├── 4346f09b20ba41d46f23410fbee45ac848b3de22.nq.gz
    ├── 43db9196c599c4f797583d48d7159fceea0d985d.nq.gz
    ├── 43e835fd2419b27230058900b0d308b62c589ac5.nq.gz
    ├── 43e9187c86ffbfd8116f7252ce17e21a705aa05c.nq.gz
    ├── 43fb11db1161c4a57972bdfb2c3e3f361e4586fa.nq.gz
    ├── 44cdb1f699e05b192f3e2a67d356a51d3a3b6700.nq.gz
    ├── 4551802948525877f200756fca1b766f7ef7f45a.nq.gz
    ├── 4609910f021ca8c5503c1389781aa7ee9f63f976.nq.gz
    ├── 466ac0961634133e9900766aaf3224414ac3a9bc.nq.gz
    ├── 47283a2f9c3e5e1ec1a0ed624d64c8420f6a3d47.nq.gz
    ├── 477b2031a7c99108b15f107e2d0fb95fcfa37bd0.nq.gz
    ├── 477d4fe050266830e4df94ec5a090c513622d1ac.nq.gz
    ├── 47a0c7ff6f1290c5e2ebd9407ab6514517e24529.nq.gz
    ├── 47eb1f695dcb5d1b2ccc198ef36728f88325578d.nq.gz
    ├── 490f0ef82e7da9f545aff79651ca8e7248d113ff.nq.gz
    ├── 49fdb76be2bb412ecd35236bb914bbab540018cf.nq.gz
    ├── 4a0a9fa9f8cd4d6095113c640852e894892f2287.nq.gz
    ├── 4b4aa1cc6b5242af5220f3459d01b650f9e3381d.nq.gz
    ├── 4b5ad66f9024fa4e13c353cdc48b4facb0fb8d5d.nq.gz
    ├── 4b5df41389ddbeb4f23f0bd08265bf7711954c2b.nq.gz
    ├── 4b952614cf30f69723237cf6968afe112772ec78.nq.gz
    ├── 4bbad8d690ac73528f2f0fd258769dca30cce92f.nq.gz
    ├── 4c3b7f0fb57b5c4d3524ba0bb2c4853ceac7fa2f.nq.gz
    ├── 4c84898680465d80545e01413fabe65728a13a30.nq.gz
    ├── 4cb437513d3e9d59e7d0584bf4f2ef9b2110df22.nq.gz
    ├── 4e5171ee33db65ac4f1ff566252aa1789c0742bb.nq.gz
    ├── 4fd494f52fee6882d2b93c4592200c79f689f6ac.nq.gz
    ├── 4ff405e9c86a2849845fae3b3d994c622390cf7d.nq.gz
    ├── 50f6f97f5f9a0436c1aa4f56e735375db8cace5b.nq.gz
    ├── 510c8e6cdeac946a034796afcadc849bbecf88e2.nq.gz
    ├── 51d177c07ef0fcdad68695cfafa4da92effc97d2.nq.gz
    ├── 52a8c44a021aaf561a9e5f9f7ab5c528284213f6.nq.gz
    ├── 530035fcbe7ee9e68bc90f9f422e6d73ef3d2dda.nq.gz
    ├── 53b0a58d4d7f7c53215250b497da65c88ac5dec3.nq.gz
    ├── 54561c975c0df6eaaec0815394b86c26ea7af8a5.nq.gz
    ├── 5541bddba83d5be036e1505c68fc36992e064038.nq.gz
    ├── 56f65f52d2765c010b25d1a438eae4d0e5129881.nq.gz
    ├── 5732fb1f4cd0a09394527032154fbfc6486f3a68.nq.gz
    ├── 57791c390044b87bb5c0c34d98f71aa4b6870f04.nq.gz
    ├── 580de1cab058d09b524861618893f4df429a0727.nq.gz
    ├── 58d8ae175c563db9da91d4b4a96bfb46b3620fae.nq.gz
    ├── 59aa07ff95f933478ba65b05bfcaf9c1b3fbb5d7.nq.gz
    ├── 5a7637b306b862f81eb6de2523aea8747f864282.nq.gz
    ├── 5ac9bcf0bb6d06a89baca9cb3010dfb1b9f360dc.nq.gz
    ├── 5aec041fc55c5b32414848fdac44b9da1cacb7f9.nq.gz
    ├── 5bdb6e0acd69cadd959210ce754e9d329405afaa.nq.gz
    ├── 5c0b6a16102ac2e486fd9a81581530fbe2f5fcd1.nq.gz
    ├── 5d09a08c3176be26642841454042bbd71eb1c70f.nq.gz
    ├── 5d3758b31c2ec7aef24935a817b0e223e265aa93.nq.gz
    ├── 5d4102a3bd42fa94c6081cc8a824623d2d050ba8.nq.gz
    ├── 5d9e2caa76d358345afb3b188fa760f1d9329896.nq.gz
    ├── 5e0e70559b4ac9773c31a060a576839a602ed914.nq.gz
    ├── 5e2db246b1d86b47f81b98b741841ad13ecc1b47.nq.gz
    ├── 5f429d0687e9a23c598c9d1f72db9e716fa036b0.nq.gz
    ├── 5f55b56d6f4fac4c9e133db9abc4a63b48adefe9.nq.gz
    ├── 5f8bf92b402c72f82793232e406dfaed56def2b0.nq.gz
    ├── 5fe14da95c8e69a6b1e8571ef7c6d88412f386d7.nq.gz
    ├── 60af294e5f1023217dfdec9c87a3035d8c257635.nq.gz
    ├── 618b0cb08bd1b75ea57ae2a7d6287366973ba3e7.nq.gz
    ├── 6193ad8385ee179af1ba7ec65999c9b7ff98449a.nq.gz
    ├── 6245ff71a08ecb451cdf61d009031f34d930db2c.nq.gz
    └── 62dec76d64e06849abdb14137d0263f4bcc415f1.nq.gz

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

[ansible-collections/kubernetes.core](https://github.com/ansible-collections/kubernetes.core)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
