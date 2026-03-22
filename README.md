# Repolex Knowledge Graph of sdispater/tomlkit

RDF knowledge graph data for [sdispater/tomlkit](https://github.com/sdispater/tomlkit), parsed by [repolex](https://repolex.ai).

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
lexq download sdispater/tomlkit
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   ├── lsp
│   │   └── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   └── repolex
│       └── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
└── blob
    ├── 00411dd95fa56eadeef3e6e8ad487206fd2803ac.nq.gz
    ├── 004135598c1e645e6d285adfd8590ba24a362ece.nq.gz
    ├── 011563fa500a47c6a85d9aa87ddd0c48fcf74dbf.nq.gz
    ├── 012a2fbdb9194fa1e1b747dcd8d66cdff50b2e6e.nq.gz
    ├── 01d4d1381cd57a2542bd98548032fd4d7007bf10.nq.gz
    ├── 024db2911c9f8d12209e5f3571e3f7f24ce31acd.nq.gz
    ├── 02ebf13a0c8ce48f5268396c5b480c417a29922c.nq.gz
    ├── 02f25d79dc9dc85af7b7a9aebe03d698ea43124a.nq.gz
    ├── 032943cee48b6c0caac21b80986a9a3e9f3f6b52.nq.gz
    ├── 057ed462e0974e3599b33728562b767a0fadfce4.nq.gz
    ├── 05a1fd0bea1f3856eb073d98aca463255323353e.nq.gz
    ├── 0704ba7fb06a5c099e609158ee9251ec8f75703d.nq.gz
    ├── 0764eb167ae20842deba7bf9f5f44dcca13bd0a8.nq.gz
    ├── 08007cc79038dd75b7dc04c7f055f1be6a6e04f8.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 098e7df265245e8ebf8799ac872617643984666a.nq.gz
    ├── 09a4cc9bcd14dec71c96ece7cf739b498b49ecfd.nq.gz
    ├── 09e8b68b5fe531a74d8f49a9417a140ca7d115db.nq.gz
    ├── 0af7025e71403caf497e4f6714d3d17dc147bc8a.nq.gz
    ├── 0ba163ab895541395f035dc9eedc6ccc4bef2ee4.nq.gz
    ├── 0c5f51fdb7e020b97708fc3a941921d4e562d180.nq.gz
    ├── 0d602b50c05a88e4401f362a6536ff89cf93cec6.nq.gz
    ├── 0f5343787072e486c71a9364f2a8478dd187b392.nq.gz
    ├── 109f96b3d90573d0d786097d9c5aeac2af200fb0.nq.gz
    ├── 12796e9bca1093dec7451f398e17b50027c59670.nq.gz
    ├── 1295df6990c0914032d8897c4829c758eed4684d.nq.gz
    ├── 12968056d346e15d906a822783fbb01bfbf4e8f2.nq.gz
    ├── 13493aab29766e02c2096c4e4b0dd58c98fc5f8c.nq.gz
    ├── 13570d3b6a9a9a473a23a56af8228564f6ba06d9.nq.gz
    ├── 136abb8059a574f06b80debc83fde83c45eea10b.nq.gz
    ├── 143e157d7088102c58e8bf212686089fd22b18d0.nq.gz
    ├── 151e28467ff577eec4719068ad11853f630ee07e.nq.gz
    ├── 166e7ff23debb91445ed24f24f1a5cfdc1fb7d6a.nq.gz
    ├── 166e8e54a30f7d71878e7f0b9a651daba48f5614.nq.gz
    ├── 173878300e5d24c586cf6bcab0722c8e11b9e18d.nq.gz
    ├── 17a9361b3fd7c1f04cba6e72d98aa63bbc8c18d4.nq.gz
    ├── 19155c818208099975b6a35c05a18527d1940dca.nq.gz
    ├── 19c3210fd939e35c47d9a32faca0c8d3fd732b40.nq.gz
    ├── 1ac9eafcc45ae17e4bb1ff22ce51daac2e4e9d40.nq.gz
    ├── 1bf4d98c0fba94f713ca403c68ec2c6edf922aef.nq.gz
    ├── 1f06b0371894df6da11f8de9096342f3119009bd.nq.gz
    ├── 1f54422574eddf730a0aec437d03e815a1fb54a0.nq.gz
    ├── 201fff6acb7be9da5cf956f56c66b591c597d95e.nq.gz
    ├── 20a6a7b29d96d586a743d9d8ef90f4904f060f2e.nq.gz
    ├── 211cc25f8bed0c5dee8bd52156b881a891ae68ee.nq.gz
    ├── 21895a2acb4b3a0b390a750740dffc22285a0049.nq.gz
    ├── 2485730432cb9d26a5024075c34ad95933e3679d.nq.gz
    ├── 24acaa1b1fc44a8802a5b1032f53a1c76cf8344c.nq.gz
    ├── 25a87ac0ae7a8a990e46b4e3486079efa4744560.nq.gz
    ├── 27d7e7d1ea44c02583e633bc847e86871a8fe948.nq.gz
    ├── 2888faa7b494ebebd837ad3da31bf11942bc8d21.nq.gz
    ├── 2aa36d5c7593ecf1551056aad60cec58e6010edf.nq.gz
    ├── 2b06bee8b4e51668c01255160cbf30e68e334073.nq.gz
    ├── 2ba9192a7334e0ee088d3347dfc9a1280b01a8cb.nq.gz
    ├── 2bc61bf1d1a1cb66489d20b90b8052005a3e81f6.nq.gz
    ├── 2bc7646fe7ca48f93175c4da64a72477f4d4f587.nq.gz
    ├── 2d02791e81b1918aee00a28b7c5448584ebc015e.nq.gz
    ├── 2dfa897ba4282e82de5a59ba76aafa458c500bbf.nq.gz
    ├── 2e180cdcce9f016423554e2d1f44187bbeed7848.nq.gz
    ├── 30f3cc150a515cfad51ea73416d46f2705759ec1.nq.gz
    ├── 32b6bbe5f6fd1b8e9c9993cf692dec83fc6362ac.nq.gz
    ├── 32cbe7924b480dbf4e2b69117b97f01c899e265f.nq.gz
    ├── 337ad080befbde5ec35a5ff2b41f41cea3ed302e.nq.gz
    ├── 337fdc4d44fa2ba83d4c68c2533b280eb61d03d2.nq.gz
    ├── 338357437d160783fe47fee2d31a279e97c712f4.nq.gz
    ├── 3430e404a2124e4d809417b3927c5dde8c79e4f8.nq.gz
    ├── 3460d7568a90f4b5435dfb304c27cbab4e7f5b8a.nq.gz
    ├── 351f8c7df8bf9d0c19ec9b8d9f211a52a370c50d.nq.gz
    ├── 355657f9040295ca071bb2da0949cbb591f43400.nq.gz
    ├── 35c5cc5ea75c771c2699848c657d339144437721.nq.gz
    ├── 3628c5b67d113987e3cd5aee9cd900f2ed059338.nq.gz
    ├── 37615338822f4b8cb1e004df71b3d8557532f05c.nq.gz
    ├── 386629ca075bc685183950f57d8be5c2402b48a7.nq.gz
    ├── 388027d5a86fc3be8619b7bcb97146b02e784f71.nq.gz
    ├── 38856c8737a8e8066b1204d85b676883e2a292c2.nq.gz
    ├── 3a2120968c6a2780e0bd0fe15e3342e6f82f331f.nq.gz
    ├── 3a27db4fd38df702fea38aebb3b1d99f064ff504.nq.gz
    ├── 3a4c758bde8991d18496f18861a09ddd4c4c8ee0.nq.gz
    ├── 3a83cc161365ac8cb0f0896334c88905c466a29a.nq.gz
    ├── 3b416664dda4bc7e2d01ed0da80d6e5a8824c07d.nq.gz
    ├── 3be2b347ec13b3bfb97fe8548d8ea6b0af2ec3b2.nq.gz
    ├── 3c7b9ea76e668816ea43e3f61cfd7b3c02566b4d.nq.gz
    ├── 3c8f0aa5547d264c3ff0c67d3bea884c3502cbb7.nq.gz
    ├── 3c9046991c2dcb40ffc7912fa28a694fe7209593.nq.gz
    ├── 3d70a8b758b42ec2a64e70fd63f56ec277a218a2.nq.gz
    ├── 3ee906b72deffa06ecdbf5cd0f4c098fef99fdac.nq.gz
    ├── 3ff0f9f0d0096cb1a72b93d9b5b90c09dedc7e0b.nq.gz
    ├── 40055208235ee3aebbe8ac3d59a2d6199226741d.nq.gz
    ├── 407d6feed84b7f2092c5b9f78c8a1bb9127835dc.nq.gz
    ├── 42dcb27530dc268d4269f7f728baf0b63f03260c.nq.gz
    ├── 43dfb394b2fc5cdc3fb48c9ce9d6f46a364227f6.nq.gz
    ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
    ├── 4588c90964a9c19af478c66e3c196ed3047f8489.nq.gz
    ├── 45e161b1ba87aed3cb6bd3bcb4020d52d42e1418.nq.gz
    ├── 45e378f535eac704baa713a9ef11b036daf10332.nq.gz
    ├── 464435ac7c7663d3a87646afbb01bcce34483f60.nq.gz
    ├── 469c309f3a5ece008f0e5b7e1d0be8579ab16f2e.nq.gz
    ├── 47b30c3b0911d41ef9aa421bfaad0b1166afae54.nq.gz
    ├── 487657b522c6bc689794fcf7821f2b4a8857ffb2.nq.gz
    ├── 4aa0752d496337697530172a66780e498240ee1d.nq.gz
    ├── 4acc58992aab26d1da4d2a84895c51ee35b361c2.nq.gz
    ├── 4ad5062f51ff5876e1417bee5fdda597ad4acc03.nq.gz
    ├── 4b97a2a6f5abaf9af01b28c716dab510f3586ffc.nq.gz
    ├── 4dfbebfaadc40e1b971e849b51483efc7a0c49d4.nq.gz
    ├── 4f029d76e3bd3d6c05794d19de931838c54430ce.nq.gz
    ├── 4f2d733b731f052f95f008d23fd2c94375fbc513.nq.gz
    ├── 5017d8541e4a5f71c721f04e674cad98c51dec26.nq.gz
    ├── 51894ce10027d0903f8f50eccfd822042b98c5a3.nq.gz
    ├── 522fb4681547540a95ce29a1aee087685221d7cd.nq.gz
    ├── 5249fd615defbb7329f424a00690a2fa66b9bbc8.nq.gz
    ├── 53a8f0c5ef5609195a64c23a87efd4808d011fdd.nq.gz
    ├── 549c5fcd87d8b15d184755ae195282fc0080fcba.nq.gz
    ├── 54b023fd31ab710f8106f868d0bf88d0ec4addb5.nq.gz
    ├── 54f6470761d3135903b7758cb7dc308f880e8beb.nq.gz
    ├── 55809d62846b8de957d74547f70526bae67ce393.nq.gz
    ├── 562b95a737e9418ae0e0d3d4656d1723037f81c2.nq.gz
    ├── 564b833dfe5f6c6266c5e1b0a1a59828d583aec7.nq.gz
    ├── 56f085a5b094cbd264af10c1c3dc02eac42b7d39.nq.gz
    ├── 57ad1812c1ea1e4e629e7ce744f2f3e4e4c62803.nq.gz
    ├── 57ed4c6cd2aad4399d3b40010ccffc057eec06a6.nq.gz
    ├── 58752d9388346d710996390d7be3bc2844c6c50a.nq.gz
    ├── 59618e1a7b64a21e0cae6d1ba80a90754fc13018.nq.gz
    ├── 598612dc3a01f025700aab4b3e7cc7713f990a64.nq.gz
    ├── 5aea8eeaa10762041a055e3b6bfd8284d7797c00.nq.gz
    ├── 5bfa47f1b1f89a354d877f52ab11d4956ab18d57.nq.gz
    ├── 5c8113f0ea7e03cb3faf65e18665dc36b689eaa5.nq.gz
    ├── 5cc4bfea5d801f5553739301eb92f2452ee93e81.nq.gz
    ├── 5cfc8d08583c4e12d5b85170849f8369ea177639.nq.gz
    ├── 5d5399e58028323c2e26f74f032d54e866f444e5.nq.gz
    ├── 5d6cc0edccad834be19df0a9b2a5778e96e1fd51.nq.gz
    ├── 5ef48cc10880b3e27eaccbcaba986fd44567cc90.nq.gz
    ├── 5f5f16f5fde5ba73b4a4918a916009330ca1928a.nq.gz
    ├── 5f5f6168f555b1d7a729d356f479f996991da4dd.nq.gz
    ├── 5f9cc33b409adb539f9330e312d661096da73ccd.nq.gz
    ├── 6020bb7de783dfe87193a48a1d928483f62d6873.nq.gz
    ├── 6239539181bf8d4a9cbb3bc25f87b8a2d16ced0d.nq.gz
    ├── 656628a093aebc11b24f766af7100ba1305ec165.nq.gz
    ├── 6654844954596619bfd6f10d1c29b9290c78efef.nq.gz
    ├── 6670e5dd990ba5e20452fa0ff8315623d445ec50.nq.gz
    ├── 689d07a14cdc21f73ac0d6c13c2114e66398f1ba.nq.gz
    ├── 698d1ac4397041767e344619fde7b855f4a55540.nq.gz
    ├── 6aeca14d1b015697ab8b1340f366ae361acf4d48.nq.gz
    ├── 6b10d70a31fb478364d08ae50d83a19433af66f6.nq.gz
    ├── 6b719683f29858a65cc0a12f743e49bb5d80fcb5.nq.gz
    ├── 6c116378990a04a68f4635c28ee3e95a6b0315c3.nq.gz
    ├── 6d7d98d99ee1043ad3a736135770ef0860835e94.nq.gz
    ├── 6e03fdca957857a153848080ed1adad17126818c.nq.gz
    ├── 6e2ea44b4c1bcbcdd0f09c807c9cf71724195f4f.nq.gz
    ├── 6e3e62c1610f586902bcb5c859f0f9879421dfb8.nq.gz
    ├── 6e80668609ad3629679e83dd98e746e54bd6ad40.nq.gz
    ├── 6f2304c1767fbe7c7d828df06d7f2d2101fcedf9.nq.gz
    ├── 6f82d946c085df0fb39b1b67439ab00758493eb6.nq.gz
    ├── 6f9e5b2a60f2796ab64a2a5906e6e5e77c570c6d.nq.gz
    ├── 6f9fb055eb4065ad99d9d0886814064e4c3142fc.nq.gz
    ├── 705686c94f1b1ebfe86295f63df671e0ad1ae12e.nq.gz
    ├── 7210cc7c9bb341a4e2ba33e6b3704b7d343fbf22.nq.gz
    ├── 72b8d672184c04543d4b56cabd2c24f937daa901.nq.gz
    ├── 73333790081cf02dad8fd6d4fbdeac45ba3e8327.nq.gz
    ├── 73ed68b2c145b5069bdacd6d9499231399f210d1.nq.gz
    ├── 74376c34f60c441f75afae9db86236cff17edc95.nq.gz
    ├── 74b40322a1a03669997ed8df70a5362229a0f039.nq.gz
    ├── 7689e14fb78b1d1bbf20fd9c51ba73cafce3e6ff.nq.gz
    ├── 7744d469d39861de18f8811416aea1a390a30eeb.nq.gz
    ├── 7847bd401dcc2a32801f71f2d65b7ab2c46cffe0.nq.gz
    ├── 78bb2dc3a162cc4e3df30c94f447c4d1e783e0ab.nq.gz
    ├── 792cbd1c3f0f6ee883b861b5d49adc3dbc82256b.nq.gz
    ├── 7a653b43b52bdad1a3cee2ceb81174494789e56a.nq.gz
    ├── 7befe6bc8f7a93490659bdb19906711decd2a618.nq.gz
    ├── 7c3506965ea3909d1e9f178ec364f4e4ef342389.nq.gz
    ├── 7cc9ba63ce336a373e50e7c5c3f95cdb1cba2f93.nq.gz
    ├── 7d788a844c929b9d5b8f32b88f42d868f60684e5.nq.gz
    ├── 7dde452c6b4dc3bd224ab89799c6089f87fd5fc6.nq.gz
    ├── 7e6396367cad25f05123a8f13ccac3a49b0f51be.nq.gz
    ├── 7e65ade521fc66e02434849fd87caef5e8086b29.nq.gz
    ├── 7ea589ccf4387b814d17fee73cf072e097f7ec97.nq.gz
    ├── 7f3bbea9b3b0e13de24c09afb1f6f836e6b6c959.nq.gz
    ├── 80a025b401c5e87ff8a2b416127a09a867058118.nq.gz
    ├── 815d313fe7028ed032f88f5555312f23602abb38.nq.gz
    ├── 816cc97aab18c89f3159f5c4d3cebe1d7755e149.nq.gz
    ├── 845df2ee2a4349ce25de38c8095c6ae900440164.nq.gz
    ├── 84812f0e08a660bddf41d23fc78791336c4796a2.nq.gz
    ├── 8510285b3a97583867499d9ac8772adc0141802e.nq.gz
    ├── 861e1f6197002a1e0341175ccac38cd975d713c6.nq.gz
    ├── 86c4179da08beda773e34e5a002dc26aec1c3be8.nq.gz
    ├── 889b19e32a954db5c0aa2af67961c90ad0ecc47f.nq.gz
    ├── 88a1de3534276464af40b8287fa3d71351dc2a57.nq.gz
    ├── 898b957c8df4fc7b34722986bab4d06009446ef3.nq.gz
    ├── 8a6829cb4cc1f5de5a1bce66fde9440a45806656.nq.gz
    ├── 8aaf68eaf3a25a460c1ec764fe97ea60d27b06a1.nq.gz
    ├── 8ac49b5aa2ba9a55a8b1bf3d3a9a84836ec88861.nq.gz
    ├── 8b5289ed02fb53d8b9df6818f1f8fda42502b39b.nq.gz
    ├── 8c336c0bc7792367a1fb7e7d344998d064e8ed2f.nq.gz
    ├── 8d8d6608b4fbba10e97324a042ec55c8d32bf2b4.nq.gz
    ├── 8da5cefd439a82953b23333f793363e4fe43cce1.nq.gz
    ├── 8e1ffb18f313792b1a307bf122e95d3a4aed9485.nq.gz
    ├── 8e67edcc2540b49659a2bd4ff4e2a2fc86b948af.nq.gz
    └── 8f83571347ea61015bc0ff7780ebd20673f5600e.nq.gz

6 directories, 200 files
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

[sdispater/tomlkit](https://github.com/sdispater/tomlkit)

---
*Parsed on 2026-03-22 by [repolex](https://repolex.ai)*
