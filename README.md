# Repolex Knowledge Graph of allenai/ir_datasets

RDF knowledge graph data for [allenai/ir_datasets](https://github.com/allenai/ir_datasets), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/ir_datasets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76d107e3c1f9acf05875d263fcb206f94f7a356b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76d107e3c1f9acf05875d263fcb206f94f7a356b
│           └── chunk-001.nq.gz
└── blob
    ├── 015737157978317956175f54fedd2570b7e47833.nq.gz
    ├── 021442912e187fe77b10327c333f15c704808f53.nq.gz
    ├── 040a0c7f644ec1ebc2c7d7a79c28f1709ff78163.nq.gz
    ├── 0445022514c06d939db9367914c3a50fd1af0f2d.nq.gz
    ├── 0503bee0a5c742cf92effe05c3b951a4e51f8c5c.nq.gz
    ├── 06124f092be0ce1b32e299c1bb4879e1c43922d6.nq.gz
    ├── 0a27640e83aee28329ca29f86ee886d3cb6acdde.nq.gz
    ├── 0a7d5e0f9f706c12d24b8b18f04b3c9672ed2043.nq.gz
    ├── 0b149f93495fae464d76adef09f5bd65ccd283af.nq.gz
    ├── 106c758d0859d8d526cedd8c895800f80a0ba0bb.nq.gz
    ├── 1098ad0a769b04c17624b0570af1d58fb44f72cd.nq.gz
    ├── 11fc491ef1dae316f2b06bbb40eaba9c757fdfd1.nq.gz
    ├── 1298a93512091e6d27c003692122828cd960feff.nq.gz
    ├── 129da0190bf382dea32cc3a268f5b19e83fdf5b2.nq.gz
    ├── 1318cc5b69e61b46650af9c5884486a84fb7d6ad.nq.gz
    ├── 13536de6cced0df3f5e0ae8ff195e13861d30a20.nq.gz
    ├── 137f33cac0edaa462a6be3a7467128b2d55770a8.nq.gz
    ├── 145bf7dca233473e0793465b357e79fa81a90175.nq.gz
    ├── 15f0a5fefe845e54a64b156d98e1adc3a2263269.nq.gz
    ├── 19425ff7dfbda648fcb61b0a14e8201c00ccd95c.nq.gz
    ├── 196fed5acb97436f9fcf12e16500c1501e3e85fb.nq.gz
    ├── 19d6e32118296de0ab9236850f2df86dd857778b.nq.gz
    ├── 1a67ef1ba1edcec5725a82a0c49d5d5fa7e122d9.nq.gz
    ├── 1b99cc1def5d17934a47cd675e67f2ed4d2944e8.nq.gz
    ├── 1bf09f001660daea9adb70c87ed32c6521d1ae61.nq.gz
    ├── 1d59a06dd22e75da527cc773d76ad36407b4e775.nq.gz
    ├── 1f16b9c0c56ae2a3187bd1ea7a5e89d222dff8a4.nq.gz
    ├── 21b3ea497d007377b67281c4cb48102c9fe18b5e.nq.gz
    ├── 22e93341cb9529dbc40dde133ecc963cb15ca7bd.nq.gz
    ├── 232135c64b18a82759ffc2cf9cb85dc7edfc91d9.nq.gz
    ├── 23fa271cb2975991e5336021301c2ddb5fd2694a.nq.gz
    ├── 24c24adcb2f9d03657b7398645fe8f5a8c6aee48.nq.gz
    ├── 25bb6053d6074d3ee9b874825306b593c15c56bf.nq.gz
    ├── 261a26a8e3f05d19cdda021fd8f260b12bcd3114.nq.gz
    ├── 266a7ac0ffbab0cb6b2f0cfed9858cb15b1a88eb.nq.gz
    ├── 26f47c969869a8add01f4f78ff2207186f9c2a58.nq.gz
    ├── 272bfa01db3cc3b0fd78f0a44db18a06b36ebe26.nq.gz
    ├── 276a43eb3f06f0adc5a26f927bfd2d5336644c4b.nq.gz
    ├── 2979d3f572b061f4c7f2acb40953471ea82a95c7.nq.gz
    ├── 2a5adcf337fed9e67fea7876943a5060b6dfe35f.nq.gz
    ├── 2c0a18b0c9c3b6d433b4e4a6c55e748147aa483e.nq.gz
    ├── 2c4d2932e91e904e62fa278d9785dac871e56598.nq.gz
    ├── 2ecb857e6ee3c361c5f988f99d5d83efd5a569c5.nq.gz
    ├── 2f10dc4cb3e8eb53ea26e129e8205a69f63b98a6.nq.gz
    ├── 309db45ed5e9cac62bf4738a6e50ff6eb0518bb6.nq.gz
    ├── 34a0a94033aeeddfafebd372eb2ea1345fe9caf8.nq.gz
    ├── 36e90dfac7ac73f2538dc4ad85cebd4c6ffe7ee6.nq.gz
    ├── 36f272b7c08036e58b13e0d34d785aa0d74304ea.nq.gz
    ├── 38467fcf97062d2a2588a32d2fe44ed9d914a07e.nq.gz
    ├── 392368e2b70f6432c1e2516e40736c493773c53a.nq.gz
    ├── 3949c22fcbd276a6c7fe8cda89ef152cb6f8067e.nq.gz
    ├── 3a8b7a18ae73eca56c55c6027a49da3fcf30c2bc.nq.gz
    ├── 3b6f8a25e54457ec39943443b58751543b7a7fc6.nq.gz
    ├── 3c5a8cb4a0cc8a41788ece4d5161e87a052d48b2.nq.gz
    ├── 3c65eefe6b9bdb6b45415ecd13c7d0ebaa984acf.nq.gz
    ├── 3dcb0b0f5afd95ffcd5646f2f5bc351a47331b43.nq.gz
    ├── 3de8a1bca6f8092377feee3d6fea70a7a0b12cad.nq.gz
    ├── 3fa77c20ba76e005ed70544db12f8e5f4463695d.nq.gz
    ├── 3fd7b84df60b0aa2eb9bf3ac9d5ed5efbc662923.nq.gz
    ├── 408625a3c4da9007fdc7f60df59e6ca9ab833897.nq.gz
    ├── 424d303aa732fc235b3a16fdf32e7baa38cc854f.nq.gz
    ├── 42debe05268edd6c8c819f036584d7d7cfd37599.nq.gz
    ├── 435a3f3a5f3ca137fa987afda611dde94babedba.nq.gz
    ├── 449137293a88e9bb440b515569379bbbba43cd84.nq.gz
    ├── 455de7e4585da1eca9246bfaf0d0dfc5290a85fa.nq.gz
    ├── 456c063babc5018f57929d759df3319470ca34bb.nq.gz
    ├── 468ed13392dd2d84fd45530db3ac5f42ece0a4f5.nq.gz
    ├── 4870e9c2e654ada3540a41e64a1b7ab435261f64.nq.gz
    ├── 49fe2e4181e7a2c906b366a2b1230c21aff0aaf2.nq.gz
    ├── 4b976b916bf123e5e099fd038e39e87f74211b27.nq.gz
    ├── 4ba793e2c60bcdac531a938087df8690fb334549.nq.gz
    ├── 4d06afe5a63329d20e85441c3dc6689fd4a48c6f.nq.gz
    ├── 4d5f713dc1a0e8ed31c43aef4e5d4cf6d98045e8.nq.gz
    ├── 4fbc11e55dc4f36ee97e28210717551edd5f56ef.nq.gz
    ├── 501babb3c95ae24b07c8a960ab3c78b858a05dcc.nq.gz
    ├── 5212ef0555d75cbb94394e46a3b8395991c09447.nq.gz
    ├── 52c2c3da8a7a250f3891b54af50f99717ae4691e.nq.gz
    ├── 56abf9a5bd30e26c8a947572b2e0c1a6b9cae10f.nq.gz
    ├── 591759147c85864a86dfe9e2a9514a11023b20c5.nq.gz
    ├── 59242f8d3696d66c83dd67d372d0498fb94e3f99.nq.gz
    ├── 5929c3cdec82749345287d1ea3e1c84cc3cbf323.nq.gz
    ├── 5a4a43c26d9a07112949e2a1af7319ce53e22359.nq.gz
    ├── 5ad4265a61c848837b5e1cb3f344805463e6e1b2.nq.gz
    ├── 5cbadebfedacd725d5a9364bbe64696f25af4100.nq.gz
    ├── 5cbe39527b5dfd1c9dd76f0b0efa3c92af6a01d2.nq.gz
    ├── 5d44315527deb4755b43f56c999de799c582a333.nq.gz
    ├── 5e6f787af553605d884b912ea3bf8d33d8654a35.nq.gz
    ├── 62561ee71d6a39b91ffd9a348ee4c9668fabe3aa.nq.gz
    ├── 62b12727fbc7d093286240337191a5668a3ea1e6.nq.gz
    ├── 62eaf52098f87c77a0f2842142707dcd619abea2.nq.gz
    ├── 643570635f90e128153cf3918fb7802c91da9686.nq.gz
    ├── 65ac0ce53816a1726cc70f06120c3173438a7949.nq.gz
    ├── 66a6506e13f5dc2f3825b8415ba190a2a800a7c5.nq.gz
    ├── 674cab408da85c5131304ad5fce716dd706a1d17.nq.gz
    ├── 676c2d47ba86bf7b0a14fdde76559fee49e32a9e.nq.gz
    ├── 68d5786584a84cf1372d9151f80ed9f6d94ae7c3.nq.gz
    ├── 699b9127859c07f471312e8f1762dbcc0dc2f917.nq.gz
    ├── 69ee6a5e63ac310af5aaea98e048a0813ecf27da.nq.gz
    ├── 6a80021e1155fe45c80f1008411c13316af7243e.nq.gz
    ├── 6aae858d14262adcfbc3f5969d8bbe2d430ad317.nq.gz
    ├── 6b4ff9e1a0e682c277f9d81b2b80325a71ca0f68.nq.gz
    ├── 6bed76e4c367cefb00cff9a016d9e189b51dd57a.nq.gz
    ├── 6c0a3ef5a88603bcfc6d476c1115c86cb2e7ae5d.nq.gz
    ├── 6d5f09ba8dbf8606710d857764c6f5456b5f8c89.nq.gz
    ├── 6eca549d8aeedbe9aeb5bba5f3aa323366e4d787.nq.gz
    ├── 6fa57618878bea8c398fd58c6f68de4d11d70fb6.nq.gz
    ├── 70bf9dd7536b7e0ef40db6253b6937aa611e11f9.nq.gz
    ├── 7187b0299ab6c3312e83ea6fff0a18698a7d3d2f.nq.gz
    ├── 727d998572f04a2a6dcb681cce7f7fa154c41103.nq.gz
    ├── 72f756feb6ae6995bd71585eb14995ba2575bfad.nq.gz
    ├── 7301df303254f2b6e8f509348cf4e72860c89752.nq.gz
    ├── 7414e86068057f6a2fb9815713cf8982398091e0.nq.gz
    ├── 75186e06dbaddf0911aacc02fcd893e2a7785416.nq.gz
    ├── 769eb48575be19de70dac249e28b026e4ef1d052.nq.gz
    ├── 776410d8a315cc0488bef8fc7a1bb1ed1d202acf.nq.gz
    ├── 78896c9d2f6ad4ed2520e4bbed1198d3f63cc96b.nq.gz
    ├── 78bddfe50e2c1676c5ffd1ff31ae42027bd48ee0.nq.gz
    ├── 7976e3a96e8e642d702c9eb5e2a82b0a61524ce5.nq.gz
    ├── 7a22246590799ed4cd33c17c94c02be6da79953d.nq.gz
    ├── 7b7693b33841c47a5fc232286a25fc1687416fe0.nq.gz
    ├── 7bf60ec5172c29f77b349f997d877a886b2ede4b.nq.gz
    ├── 7c42c7dabb53175ba5a140792fc2db3d68192e5b.nq.gz
    ├── 7fd97cb363e234e4ebf35487f14a9108732f6445.nq.gz
    ├── 811f32db75b262481a5d2b69c2e44f7d643cc258.nq.gz
    ├── 8225270b959bde2e76fe127de0b336ad8ac0df25.nq.gz
    ├── 825113353d3e92113e7f56a2330bc6c2b3274b5e.nq.gz
    ├── 827b59896e4f177bd76255615d2988ab7b1318be.nq.gz
    ├── 827f9165d0011ba2ae608d810218a5adc147c98d.nq.gz
    ├── 833d7791313ffa9da8ddcd1a5f628adb9bbbc8b5.nq.gz
    ├── 855d46dfc864181e154de35e79941202714f9111.nq.gz
    ├── 8638e14ca39b8af10f5cab0189a974a9368add34.nq.gz
    ├── 876d8bee3b6b6e2fbd2c72eac23d5dc8663a60ea.nq.gz
    ├── 88b8101e72da44f8766d574f58e3e39542ea4a10.nq.gz
    ├── 89d58fd464098a4a309381ab0a821009401056f1.nq.gz
    ├── 89e4f9378ab283c399d27bfd61c32975ea3b6ec1.nq.gz
    ├── 8a748b6b45485f05a26877761d595b6a72dcdf94.nq.gz
    ├── 8a7f93fdf1dda3c790ed494dcb5615804f9b1df1.nq.gz
    ├── 8b1872a19e9d4168098441b7aded571f43232f6e.nq.gz
    ├── 8cea7b2b8426230efea1e2bf1e3644ebeef033d4.nq.gz
    ├── 8d4796e7ca04c7ef31777c5c5599c33de3b63895.nq.gz
    ├── 8d4f03c4096fc8a56f94426117974cd0b1a48d39.nq.gz
    ├── 8dfb54581c3b627b5556d0ec8a0120f02f879ded.nq.gz
    ├── 8e7d650a1a603d1d91a8f93c00b466d54bb66edf.nq.gz
    ├── 8f1a1100bfccfcaf0d017f7d99c77ac3a5586454.nq.gz
    ├── 90c8a0189bf109e89771899659cd3c63aa901ab9.nq.gz
    ├── 914af6d502e3eb73986c8fbd96ba0afd5c14b6cf.nq.gz
    ├── 91affb8fc4ddcf6b40d1ef4dff7c6713da1b6089.nq.gz
    ├── 92fe3760de5027a093f55e372e1ed669c2812224.nq.gz
    ├── 938659d31d8744b6ccb05afcd93a22c50998f312.nq.gz
    ├── 94bca98fa103cf8c1ee3b49eff9f8f1f7a1e0c24.nq.gz
    ├── 951cc024aededfabd3911352400d32bda2788123.nq.gz
    ├── 95be63a8b9146338e7eba15d01a39809808c2e1d.nq.gz
    ├── 981d24b033ee5472a20e5521c80ff9941ad10dc8.nq.gz
    ├── 984184411a080feed2309c0fcf8433cb46e11de8.nq.gz
    ├── 99afb2d1caed1a53e836c9677de556bb09ca1641.nq.gz
    ├── 9ba5740f69a6aa450c7d59e6061acacc4186731d.nq.gz
    ├── 9d22ced5c6cee46589c8c09d5d0100333934ad4f.nq.gz
    ├── 9d7a89a64aa43ef56d711f93ec7c670d37600ef1.nq.gz
    ├── 9e668e9712ba84c8cbe85221480370683a97bd31.nq.gz
    ├── 9ec4f447e27fa3abe65ef2215dd7343dac6c9855.nq.gz
    ├── 9f2364d91f70a3bec78121be206ffcbe28b54874.nq.gz
    ├── 9f68aa862dd366471434a40025c57cffa035262a.nq.gz
    ├── 9f6c226e70e038ffaf4a872a42d37652fbcf75ce.nq.gz
    ├── 9ffd197db27d0e91ce1cbd498e694a3fff8b371c.nq.gz
    ├── a2342b64ad891d1c0462862e5ddd28fad9f53bfa.nq.gz
    ├── a31cccfccef63fdcfbe1561667cfefa32e3077e6.nq.gz
    ├── a53c47e7ac3c3e2c579bae1f063dd4e673c9b205.nq.gz
    ├── a59cab4cf651665ec9637cbc96ad99eced06d2e5.nq.gz
    ├── a74bb1e90565ad8de2668c13adb72aa09d51af16.nq.gz
    ├── a7c93a53401b5a53388949301c422bf5f809d970.nq.gz
    ├── a7f2940ff0ff8ea287ba2f53b3158ae9b9393baf.nq.gz
    ├── a876a354b0729b4edd57d49c01e78ad0697a06b0.nq.gz
    ├── a87a51bd3a2ab083c12f65bdd5d52977be827708.nq.gz
    ├── a978edcf28b6b37c8d59bc2b126ef1b34cd02820.nq.gz
    ├── aae7a37a30d3a3c84fbafd605b4a65112a6d30df.nq.gz
    ├── ab09f31c82cf22786ed3392c8d906743ff8cbecd.nq.gz
    ├── ab4b540df1169af9658c882e519c63d92a5b7f0b.nq.gz
    ├── ac0e7282efacd0a14777b4b6362f3f7ebc4422b3.nq.gz
    ├── ae4af42b291151291329f76fdb7e2a8127b2c3c2.nq.gz
    ├── ae99469d5b4d62b82392aac2c2380b1c2ad79cc6.nq.gz
    ├── b007984fd705afb5265646c6f85f8dc3a8cfa568.nq.gz
    ├── b2ce779efb8dbd435eb3f8f8315d1d91ec804a5b.nq.gz
    ├── b2ed0e608514843333ffdb47a6b8f57e4c4ac52f.nq.gz
    ├── b441e68323d64d623018d98dd38420ae7deffc7b.nq.gz
    ├── b5e518e8629efb69d92611c08ecc55cbf881c705.nq.gz
    ├── b85fc53aa96b173d4080bf8da5c8f39bbc169478.nq.gz
    ├── b95655e9bebd8348b16cec3fd3b0f26cbce99867.nq.gz
    ├── b9cf6577d92859124b2a898362db0be9ef77ba6e.nq.gz
    ├── bab16cb694f18150bf822c8239fa71f23439c74a.nq.gz
    ├── bbf3348ea72e84b3cc39c8b9d0af541757aa6a30.nq.gz
    ├── bd170d3d47bcbf3abbe7443b4f5cfd8415bab42b.nq.gz
    ├── be0152439b3f750a54e164ca3850584b089f64ce.nq.gz
    ├── bf31687a42c6af3c4893c8bc75d8b40d8b542bd2.nq.gz
    ├── bfa81f5ae892ef5c7ccdb2f63fa319bff46941d4.nq.gz
    ├── bff4f567ec3f15d65391b40c99dbc42e4c5ac313.nq.gz
    ├── c185353e88390cd4f1d263c21e8b9092da6a1787.nq.gz
    ├── c1f1a20f36b742bfad6021f06b15b66bd7555978.nq.gz
    └── c26bfe2e2a3ebab3280ab58911f1fc127069c748.nq.gz

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

[allenai/ir_datasets](https://github.com/allenai/ir_datasets)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
