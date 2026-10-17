# Repolex Knowledge Graph of skypilot-org/skypilot

RDF knowledge graph data for [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot), parsed by [repolex](https://repolex.ai).

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
rlex download skypilot-org/skypilot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d91efff99c0d81e4aff6b9f1ad423ce1e19a306
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8d91efff99c0d81e4aff6b9f1ad423ce1e19a306
│           └── chunk-001.nq.gz
└── blob
    ├── 004ebe8c46a833dff706454106811e15cca96acf.nq.gz
    ├── 00965cbcf3146a1599c914664ab6823c3d6809a3.nq.gz
    ├── 01918bcf34d33af7fcc5c3a943271e085afaf191.nq.gz
    ├── 027a7b734b219e57b3fedd79d32138793580dc08.nq.gz
    ├── 03b8d196ba4bc6c46ddbcfb0bce3bca05a27651c.nq.gz
    ├── 045e35c6d0f068f5263b8bf1bdd7898bbd348552.nq.gz
    ├── 046e72cc00f806686a70c2003abf009011804584.nq.gz
    ├── 047334703c1c0289b5ead952e6a790ebdb3635f1.nq.gz
    ├── 04aae1284a6e42389ff86ac0e0d864a5fffe47eb.nq.gz
    ├── 0530c52f7ecfd45fa3da3b5f4f5cab9905cb2d50.nq.gz
    ├── 0627d435a60f80efec51dcc0b78a517888f5181a.nq.gz
    ├── 078e4ea7e8ffcbfa733face5d0702e5844184143.nq.gz
    ├── 081d531db6b85df52c8b5a2b7971ea51e4d2869e.nq.gz
    ├── 08427349f1d46bfbbe3d65f0ec1cbf2c4d4c90a6.nq.gz
    ├── 0946388f7ecc27d288c6917046fae592bb226d2b.nq.gz
    ├── 0a0f0ded1accab659ede028390ade8ca4093894d.nq.gz
    ├── 0a513dd8a403b08814fcacd67dc79e4b31f314cd.nq.gz
    ├── 0abc7e635f80344f4d4fb245ddb46057bab9900c.nq.gz
    ├── 0abefe84f930c84fad4ee3a10a33bcfd0e5789c3.nq.gz
    ├── 0acd659d6636c8fe48a43b3bf0f1e3c501bbb44e.nq.gz
    ├── 0afb9a9c4919ed1381a3d724308b8117da97aa9c.nq.gz
    ├── 0b10f7f769895f4d4b0e64c36e65821a1178e070.nq.gz
    ├── 0b3733e27f04f592ee9e35f1a2ac75caf6691215.nq.gz
    ├── 0c4fd6c07fce16c2f394cbc50e16bd0e65112f98.nq.gz
    ├── 0c73bf7b3ea95adc03387e286574e7e4c10df563.nq.gz
    ├── 0cc69d14b96a7136dcba4c42b6a7154f3a7b3f38.nq.gz
    ├── 0da3de5b12c231e03c177575ae77aa82af5bdb5c.nq.gz
    ├── 0e0ab2589604a1be1393587558ca3ad6cea038c7.nq.gz
    ├── 0e1a023cea4c184161f621bcc7535d6bf0065af1.nq.gz
    ├── 0e4ac65d458aa9ce0498838f9fe3b8e86da6dd65.nq.gz
    ├── 0fbae8bdfff6a1fc18de310ff229fdd0a7910cd0.nq.gz
    ├── 10ed3129916052b1a16aae64882cc2bd203ddbe4.nq.gz
    ├── 111cf1893bd6018be6bf991997a116d2a6f5f974.nq.gz
    ├── 11787b8fbb0f73418fafc557be8081cf4a88c3fd.nq.gz
    ├── 120e3e223276306b39da0554cfa8699353d425bb.nq.gz
    ├── 1279e0ba30d05eeef50b1c9a8f50100a7ec38280.nq.gz
    ├── 12d058228eae8f26624f7774e6d7d5f55252aed7.nq.gz
    ├── 14202b88d87cb6b2af41d768948a720467b549dd.nq.gz
    ├── 14901e635ef49810ed9823ccaa460f655a9b012a.nq.gz
    ├── 1530eed94de85b9ba2d0b819fbcecee033afcdc1.nq.gz
    ├── 15345bf98b78fbaa7f61a8111b78aab0334de5fa.nq.gz
    ├── 15d852a6494a7010993f73e4bd5a9ed3598622c8.nq.gz
    ├── 161a48bad17ae204c48b23294925b3d3a94d52da.nq.gz
    ├── 17f36d5acf0e4e2e48c79039f9570414e7b7bd4a.nq.gz
    ├── 186f5a4a7a2130a003fe1ec99b25363aa4112dc2.nq.gz
    ├── 18b8ddc8632e1cf1a4c2bb35af0f94f312176c28.nq.gz
    ├── 191640b0cf32c162d2b6918dd1663c46e94d8f9f.nq.gz
    ├── 1a2f4939a48db9814081851b2f994ad7e56ee6dc.nq.gz
    ├── 1a377e55e7abc15318ec9a05732bc1f99b475380.nq.gz
    ├── 1a515c7c47426f470066e064c4be81c69ef36cf9.nq.gz
    ├── 1bdfbf3974ea3d269b42854c16967e334460ceb8.nq.gz
    ├── 1bfc58cb22af43c5d24c578cfd8f60f8ffe5ad0c.nq.gz
    ├── 1d2586f1b2b9990cb87a63b5870d8be3565ff1f2.nq.gz
    ├── 1e80c1445af197fe077c1b5a6b714e99b2a1d0c6.nq.gz
    ├── 1f039d8c2289a4d0684d17284b6ac942d7d7d326.nq.gz
    ├── 1f5fd2058b4aaf5f67d6eaf728e3a6937c268625.nq.gz
    ├── 1fbc627fad7926dba97b4ad7939d990bb21df16b.nq.gz
    ├── 20f026d8f4ef553d766b45ad29f6cf6467a73f5c.nq.gz
    ├── 21fbf28ecdb5837e64f1b055fe7a147c3aa95acc.nq.gz
    ├── 2219309d0e85c112b0230b9559181b840ac3c4f7.nq.gz
    ├── 226801cd5fe1fee936ec4d7bcaf6c4a39e0c448e.nq.gz
    ├── 22f78cd88d05a8f738789a376332b5ec904c7ea2.nq.gz
    ├── 23fbe9e95d6abce6e39e5df275aa407316c2375f.nq.gz
    ├── 244517f6aecfddb9641abf1cfc274386fd6c6770.nq.gz
    ├── 247f4427ebbe6897b5f43243f4e37b65ec8e0520.nq.gz
    ├── 24a007ad259cbfaa0c38a9a404a9ea4df19a2b65.nq.gz
    ├── 25bac8391386d66889744231fc9c5b909acd3213.nq.gz
    ├── 25e2eb907ac821062e3cd63c562c3892c3183d23.nq.gz
    ├── 26bec19db66391dc8a88642f7f41851f974a4593.nq.gz
    ├── 271e963a33daa3ad273da1ccf97527b58658af53.nq.gz
    ├── 27ed558b4fcec3353c38fc36f3a93f594a33547f.nq.gz
    ├── 2879eda5f03364ecbe63d0178cb2ef1164735d19.nq.gz
    ├── 2897c97beb0011f2205690c6755fc6ab0824e34d.nq.gz
    ├── 28e74b45bb5c6d070a71c1187d2e5bf8f55662c5.nq.gz
    ├── 291eb0d0458f73ff1d1bf61ee769ebef61a8b220.nq.gz
    ├── 29483b87d0f2fd11db28dc1dc761414e05d767bb.nq.gz
    ├── 29ed1b779ed748e3aa8f138f8085243f2e7563c8.nq.gz
    ├── 2a0e02cfca7e81e30e954a6ff1022b154ae8041e.nq.gz
    ├── 2a45b279bfe1e772084e6f95e9de288250c6aeb8.nq.gz
    ├── 2af138c4f9759237850d88639a9c2cda99a50307.nq.gz
    ├── 2af5a718927891f2da798351a9f354911fafdcf5.nq.gz
    ├── 2b4b6855ee8ff53ee157d0dfdf9eb87c668ae945.nq.gz
    ├── 2b8d8f1ab7d6a9dbd526b88d606ba96cb3c29a7f.nq.gz
    ├── 2b9bf4b6f20336126645f37be09b84317f32eec4.nq.gz
    ├── 2c93d8f9faf0ef01278425ffcaac845e5e4cedda.nq.gz
    ├── 2d05eeb7419e34c05d1dfc6977087ce9c1b645ee.nq.gz
    ├── 2e1b528f02cd8548b01b1760014aafaf9cbd8dbf.nq.gz
    ├── 2edae11b950814275ea347e0fc0c9dae2d5a2794.nq.gz
    ├── 2ede3f4e57ce108f5edede6e9b691a6d614a0f3a.nq.gz
    ├── 2f80b6dd0c8e9e8372d4b32405f30003ccb5c50a.nq.gz
    ├── 304756a355e4aea2a77e66495e0141c5f4318540.nq.gz
    ├── 3066e7747fd91a3f92601366d3fc1f6714101a93.nq.gz
    ├── 30b4ed774368af89d654c9f01850d769e6cf9f52.nq.gz
    ├── 311e6321cd4ebd37d31c8234d9fbba164753e5ea.nq.gz
    ├── 31f38b22bdb2abf7b26d962a857f3f6bb4f9ddb3.nq.gz
    ├── 33245dbf1d74c0de66c3621cc4cf4628cafec32f.nq.gz
    ├── 335028fd8fb9b99775f0abbec86302b8abc04287.nq.gz
    ├── 3361bc23b55404e368b15d6db09318cbc207006a.nq.gz
    ├── 341ee61eeff0b2aa8e3831192d23e68f2885dc76.nq.gz
    ├── 344c86f3474848bf0cb5e96e9aa314ed8451f066.nq.gz
    ├── 3503993e545a59e8a6f838652e3cd8561e30daf6.nq.gz
    ├── 37708ded0949a82ff821a80b681d5475e832793d.nq.gz
    ├── 37a16c4764a4b06c3916e3b7ca2f8d8ee92effe9.nq.gz
    ├── 383845c3fd5c29b6e2b16dc47d6de5be0402d0a7.nq.gz
    ├── 38a67dc4cf34ae9cb9ad4ea9b7ec716b6b54acfa.nq.gz
    ├── 399f36637d09a567261971842f1fadaf95b845d8.nq.gz
    ├── 39b2c55b1ce3f8b45b903f2c964d3f67a1815f94.nq.gz
    ├── 39c07f403873575de3e2b7b2d49b67e9fd4c1f7a.nq.gz
    ├── 3a01552b2413d593d09d596167f70820cedf1611.nq.gz
    ├── 3a566e031c68ca4f6a165932a53b27d06b8cf543.nq.gz
    ├── 3a7d0db180593f8982dedf32f9151be3a365eb36.nq.gz
    ├── 3b1c8ba243ef69f00e625947f2ac7d354eed8fa9.nq.gz
    ├── 3b71e8757439ae446b9e25f046125ec39829c742.nq.gz
    ├── 3c3685c2322bf69f3bb64211bd088e55b6b43889.nq.gz
    ├── 3cae399b3fca6a5bb13c7cabcce5962e7eaffc66.nq.gz
    ├── 3d177bb09f05803b8de8133051cd4e8764fd4774.nq.gz
    ├── 3dd8abe2602d0244716b1b37315afbcabe9c8dcf.nq.gz
    ├── 3fb17994cbdbcf04f669848626f54893659ab0ef.nq.gz
    ├── 3fe65593c7e9d079517f05c43c4198ccf205354c.nq.gz
    ├── 4011049f02353c5639457f48789521b5a4f5d0fc.nq.gz
    ├── 408c8e91a48b8b395e4f20bae27438725c59aa23.nq.gz
    ├── 409c6f15a9b6ceea122660858cba39fe8f9e70fa.nq.gz
    ├── 4150803b3e95cc793046341ce8b520a9c29a2ae5.nq.gz
    ├── 41df3427ae6c3f7760ff28275eae94ffc3772a89.nq.gz
    ├── 43028dfb13a04a82feb8de7b1b921671cf19a93a.nq.gz
    ├── 431ec5309a04df4bcf0c2e69e86a9908b946ac00.nq.gz
    ├── 449c7994da788d83c3b73a3f6ba8ffc465b28d65.nq.gz
    ├── 449e2fdfd75defc5d3a9d28b05ffe010e70d17bf.nq.gz
    ├── 44a7224051f59100025e5e6bfa2198c314e937a8.nq.gz
    ├── 44b1f50a35d84e96278924f898443cc63a6f2f83.nq.gz
    ├── 458e8bed3b22930754a7ce5ec7d26d723bb8a6ba.nq.gz
    ├── 4624c9938ecd5fbc029b7a9502326e99503f4fee.nq.gz
    ├── 46312a7fbbb190ba0f97fdf97af2505e4eca02b2.nq.gz
    ├── 4699dd682de3e87c5bb3f7ce26a27c1d224d8979.nq.gz
    ├── 46d888c2910fdc0434d6ff1c115200c8a4d817af.nq.gz
    ├── 47302b90d2a831d19036c707f0d6d0af8cf2c293.nq.gz
    ├── 4758cd6a474c8cbc79598d40d5ce84c5c1137690.nq.gz
    ├── 478671538a14b2f562a2bdb4c489d80eb5446d9e.nq.gz
    ├── 4894a7bdd1f32fe4ab058b839f1f1068ed2e05c1.nq.gz
    ├── 497cf46d3ba45886c8e7b876cf1013e55b8764a1.nq.gz
    ├── 4a16698c0a3b7b40eee1ac3fa08ebdc85cc18614.nq.gz
    ├── 4aad8a19e6b66e391e96e9ba6a402ff14f0f5e04.nq.gz
    ├── 4ac054c157b4578dedfe7f1fda0458705a805389.nq.gz
    ├── 4c90fbd667caf49c15559be305e2722f2d35093c.nq.gz
    ├── 4cf3720a869c70b59ff0ce36bcd581a56e9acdee.nq.gz
    ├── 4d9d0e8c8a1c1d9b6d2f8151a387dc85f4236b5e.nq.gz
    ├── 4e488ad82f0bf97206a5dd637697751de807119b.nq.gz
    ├── 4f29b084ed9e2f6fdb43af8a3001d042782bc320.nq.gz
    ├── 4fb742476248c41b86c8c8fd7745ab5dcaee4755.nq.gz
    ├── 5002db5be7568622dd5a785af6134e778419af81.nq.gz
    ├── 511281c11fe4c5d65a2a4f9938ea7973fa23e25a.nq.gz
    ├── 51f23703182ef56fcdfd55c3abf45f9d7c10c5c9.nq.gz
    ├── 5211325b636497020775a16ebe6f42b29e049aa3.nq.gz
    ├── 52a9ff67258fd5f104c2745234158686dba92944.nq.gz
    ├── 53371c969a68ebfa5286dbfaede2f634f7f8b611.nq.gz
    ├── 533df04e9cf499a85d5c66e10d43d1feebb6740d.nq.gz
    ├── 5378fe97a9bdc453d1a1b5420f72d983a61955c7.nq.gz
    ├── 53cdadd0a600d85694fcb98f42675f2c2cf81bb7.nq.gz
    ├── 55e0e2dc234cb9065e4663e0a170cf392fed3401.nq.gz
    ├── 56857777002a8627672efd001f590e0ebbc14876.nq.gz
    ├── 5693178b00d34156c283a092c1d8ddb11d933f18.nq.gz
    ├── 56ae5e9e6c7a6194baa7ee5ff03f80d5ddb94a1d.nq.gz
    ├── 56c04c7d1dd84dd35174bd238843ec23ea846004.nq.gz
    ├── 5809e183c8c6253bf1955aca6f5ef8f6e044d3f1.nq.gz
    ├── 5815a807cb08f44f2142363bd3b3f138eb43ee45.nq.gz
    ├── 584e165723689c44e4c59aca8183b9f30f1bc83c.nq.gz
    ├── 58e9ceb2a8a48c0e38e9e99db18a47d22071fa5a.nq.gz
    ├── 590d98ce7156dcc7acea5bf913e1c66df8d037ce.nq.gz
    ├── 5960d29028c44d8d3355db57554ab6d531d46197.nq.gz
    ├── 59aab0548c128892c9a2fd1bfa0545d1cd7713ab.nq.gz
    ├── 5a308e8cdab0d60d6a3b2b366180aff4f85b3dcf.nq.gz
    ├── 5b20071790fe63c7f1b7085f8dde486d4dfca18b.nq.gz
    ├── 5b7bb2cf79271b14d948f5ccc7c8cd87cf930666.nq.gz
    ├── 5c22ded6e64fa73aba6360582c52d4266ba4cc83.nq.gz
    ├── 5ca020efd296bcda9c361234c1f703e3b3d3148d.nq.gz
    ├── 5d3cb1ba142cf5062f633b3f7d4926f20108583b.nq.gz
    ├── 5dcb8de1d87c91187d18166be59b981c34094a7f.nq.gz
    ├── 5ddbfd96be7d569ddc89ae28b2f0e0a83df0b21b.nq.gz
    ├── 5e54991bb3228d7fe064a06896cf5ca01bdca04d.nq.gz
    ├── 600a548534c4c1a1b89fb342246cc9317f12201d.nq.gz
    ├── 60c01fd998ecbfa8db023a5163433ff187865aee.nq.gz
    ├── 61bdda6a60dc35c78ca762d14f61fde21aec48a7.nq.gz
    ├── 61fc150dfe34d99048da3983cfb1970c437243fe.nq.gz
    ├── 62fe2c909a2df73ccaf6b626f4de6f35fcc138eb.nq.gz
    ├── 63510cfce74a73296f39a58f97b2faeb6636a062.nq.gz
    ├── 635353892040ef1eeb0bfbd687cd1502888ba65a.nq.gz
    ├── 63b4f7ca4eaa467b2ecba7ebc0328a572b78ef8f.nq.gz
    ├── 6400eceff598c5b55761204d815875aab068d18c.nq.gz
    ├── 640c7836bc10fdf45497a4eedbde1978724f4b05.nq.gz
    ├── 647e5df5caf13a77c1cb88586521748b7825d36a.nq.gz
    ├── 64a9033ead24603cde20982e6a41f6b3dbc6c7a8.nq.gz
    ├── 64fbd96a74d9b54c374c9fee46b69aecdb3d2117.nq.gz
    ├── 65dac649f742e2b25defd337933be5429069a8ed.nq.gz
    ├── 660f531ce2cca12ccbbf5166de18d3eec66eb40e.nq.gz
    ├── 66b14c18b6cb2529f0cc354b406a36e3e8bae572.nq.gz
    ├── 66cb145ca4d7588cb84b7a6257dd4cf1cb8228c4.nq.gz
    ├── 6730a032f6434cfef1162ee6c82f498bbadaed39.nq.gz
    └── 673cc86c515b362a9189e15caaa6a585c1e2d842.nq.gz

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

[skypilot-org/skypilot](https://github.com/skypilot-org/skypilot)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
