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
│   │   ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│   │   ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│   │   ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│   │   ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│   │   ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│   │   ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│   │   ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   │   ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│   │   ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│   │   └── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
│   ├── lsp
│   │   ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│   │   ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│   │   ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│   │   ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│   │   ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│   │   ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│   │   ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   │   ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│   │   ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│   │   └── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
│   └── repolex
│       ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│       ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│       ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│       ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│       ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│       ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│       ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│       ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│       ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│       └── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
└── blob
    ├── 00411dd95fa56eadeef3e6e8ad487206fd2803ac.nq.gz
    ├── 004135598c1e645e6d285adfd8590ba24a362ece.nq.gz
    ├── 011563fa500a47c6a85d9aa87ddd0c48fcf74dbf.nq.gz
    ├── 012a2fbdb9194fa1e1b747dcd8d66cdff50b2e6e.nq.gz
    ├── 01d4d1381cd57a2542bd98548032fd4d7007bf10.nq.gz
    ├── 0204d7d54fd4ab158f35064d0b747e2c9ee585f5.nq.gz
    ├── 022b096ee44b899339a86ed3f3e49031b0ca4761.nq.gz
    ├── 024db2911c9f8d12209e5f3571e3f7f24ce31acd.nq.gz
    ├── 02ebf13a0c8ce48f5268396c5b480c417a29922c.nq.gz
    ├── 02f25d79dc9dc85af7b7a9aebe03d698ea43124a.nq.gz
    ├── 032943cee48b6c0caac21b80986a9a3e9f3f6b52.nq.gz
    ├── 03ceb5a248db9f2353ba78bbd784114dfd0e8185.nq.gz
    ├── 057ed462e0974e3599b33728562b767a0fadfce4.nq.gz
    ├── 05a1fd0bea1f3856eb073d98aca463255323353e.nq.gz
    ├── 0704ba7fb06a5c099e609158ee9251ec8f75703d.nq.gz
    ├── 070c583be6eb049b0338f2e3aabb8fba8a3550e4.nq.gz
    ├── 0764eb167ae20842deba7bf9f5f44dcca13bd0a8.nq.gz
    ├── 07ed7bad059ae3fc2f05d93caf576658a91374d8.nq.gz
    ├── 08007cc79038dd75b7dc04c7f055f1be6a6e04f8.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 097aceb605437763e76c1731a64682b8619a50f1.nq.gz
    ├── 098e7df265245e8ebf8799ac872617643984666a.nq.gz
    ├── 09a4cc9bcd14dec71c96ece7cf739b498b49ecfd.nq.gz
    ├── 09e8b68b5fe531a74d8f49a9417a140ca7d115db.nq.gz
    ├── 0a96cc54d8009d70e648fbe56c45109613b2141c.nq.gz
    ├── 0af7025e71403caf497e4f6714d3d17dc147bc8a.nq.gz
    ├── 0b74664ebaa58e6c268ba1c7221b6369e2c11247.nq.gz
    ├── 0ba163ab895541395f035dc9eedc6ccc4bef2ee4.nq.gz
    ├── 0c5f51fdb7e020b97708fc3a941921d4e562d180.nq.gz
    ├── 0d4701d6abee75fe79cea59a54cd7463407886b0.nq.gz
    ├── 0d602b50c05a88e4401f362a6536ff89cf93cec6.nq.gz
    ├── 0da4fbe97ca8db70fca00bad9d4a6bc5a7e9274d.nq.gz
    ├── 0e36b88e1fca19120fb5e6d16b84023443433ed6.nq.gz
    ├── 0e4db243b1285f8d4d93a876845a3f72014e40a6.nq.gz
    ├── 0f5343787072e486c71a9364f2a8478dd187b392.nq.gz
    ├── 105f1423a70a94b006bc646c9b95f7b00ead4e23.nq.gz
    ├── 109f96b3d90573d0d786097d9c5aeac2af200fb0.nq.gz
    ├── 10f1f9fb439c96f05cac0141b71c7dafe4eebdd1.nq.gz
    ├── 11e5385d1b4eebe4cb0a3f9e1b79d04b2afbd17b.nq.gz
    ├── 1236d017d4405a778b7e102be6ddfc570ec9e41c.nq.gz
    ├── 12796e9bca1093dec7451f398e17b50027c59670.nq.gz
    ├── 1295df6990c0914032d8897c4829c758eed4684d.nq.gz
    ├── 12968056d346e15d906a822783fbb01bfbf4e8f2.nq.gz
    ├── 13493aab29766e02c2096c4e4b0dd58c98fc5f8c.nq.gz
    ├── 13570d3b6a9a9a473a23a56af8228564f6ba06d9.nq.gz
    ├── 136abb8059a574f06b80debc83fde83c45eea10b.nq.gz
    ├── 137333bbab0e4fcfe30ba1f659420c4182c84a26.nq.gz
    ├── 143e157d7088102c58e8bf212686089fd22b18d0.nq.gz
    ├── 151e28467ff577eec4719068ad11853f630ee07e.nq.gz
    ├── 153be5e2f6f996741b53558d8bc7825ec091699c.nq.gz
    ├── 15b43b1d0a8ead6e9763601c00b1bc6da097d568.nq.gz
    ├── 166e7ff23debb91445ed24f24f1a5cfdc1fb7d6a.nq.gz
    ├── 166e8e54a30f7d71878e7f0b9a651daba48f5614.nq.gz
    ├── 173878300e5d24c586cf6bcab0722c8e11b9e18d.nq.gz
    ├── 177861624d6b531187e0325ac38b097ab34b6fa9.nq.gz
    ├── 17a9361b3fd7c1f04cba6e72d98aa63bbc8c18d4.nq.gz
    ├── 17e957bf078ab409d364d6f5bf0452791aee9b31.nq.gz
    ├── 1884b6d864502bb1ebe12a68c72944dcf0e0a87f.nq.gz
    ├── 19155c818208099975b6a35c05a18527d1940dca.nq.gz
    ├── 19c3210fd939e35c47d9a32faca0c8d3fd732b40.nq.gz
    ├── 1a20ef6d674f68ff80e8352bec579fc08d75a03c.nq.gz
    ├── 1a7e541b784ad818760d100b3c3a449f79c78184.nq.gz
    ├── 1abb1eb29d39dae91ce2ed4ccf9e18498795470e.nq.gz
    ├── 1ac9eafcc45ae17e4bb1ff22ce51daac2e4e9d40.nq.gz
    ├── 1bf4d98c0fba94f713ca403c68ec2c6edf922aef.nq.gz
    ├── 1ccdd686e905fa760cfbd184f20c12ac62760ec7.nq.gz
    ├── 1f06b0371894df6da11f8de9096342f3119009bd.nq.gz
    ├── 1f2bd0269672694aacdd613fca73bf3d97831144.nq.gz
    ├── 1f527c8a23d0e63169e87ecf88410c10ef34cbc2.nq.gz
    ├── 1f54422574eddf730a0aec437d03e815a1fb54a0.nq.gz
    ├── 201fff6acb7be9da5cf956f56c66b591c597d95e.nq.gz
    ├── 20a6a7b29d96d586a743d9d8ef90f4904f060f2e.nq.gz
    ├── 211cc25f8bed0c5dee8bd52156b881a891ae68ee.nq.gz
    ├── 21711ca4d5076e165dc74b810986d7a7e3461af8.nq.gz
    ├── 21895a2acb4b3a0b390a750740dffc22285a0049.nq.gz
    ├── 21ab5f81c91022af243522c0f4075a1d012f9bff.nq.gz
    ├── 22bd50340bcb4df108388fb604d036532b5ad4c0.nq.gz
    ├── 23c83af8710a671a87b16daa8235c61d31abeb9d.nq.gz
    ├── 2485730432cb9d26a5024075c34ad95933e3679d.nq.gz
    ├── 24acaa1b1fc44a8802a5b1032f53a1c76cf8344c.nq.gz
    ├── 25272947bbfda7cb2f8acda6b21cf2cffc371385.nq.gz
    ├── 255239237aba179cde7b7cdead015fabd76248da.nq.gz
    ├── 257864fef9ff36359b772356325234199b9ea5f3.nq.gz
    ├── 25a87ac0ae7a8a990e46b4e3486079efa4744560.nq.gz
    ├── 273efc55905e843f880118ecfeb1bc28a59cef9e.nq.gz
    ├── 27d69170179317085c62715cff9ce0c810148e96.nq.gz
    ├── 27d7e7d1ea44c02583e633bc847e86871a8fe948.nq.gz
    ├── 2888faa7b494ebebd837ad3da31bf11942bc8d21.nq.gz
    ├── 2aa36d5c7593ecf1551056aad60cec58e6010edf.nq.gz
    ├── 2b06bee8b4e51668c01255160cbf30e68e334073.nq.gz
    ├── 2b7a44336e57729be70991aa9edabe5167d3b34a.nq.gz
    ├── 2ba9192a7334e0ee088d3347dfc9a1280b01a8cb.nq.gz
    ├── 2bc61bf1d1a1cb66489d20b90b8052005a3e81f6.nq.gz
    ├── 2bc7646fe7ca48f93175c4da64a72477f4d4f587.nq.gz
    ├── 2ce869b4dea3b700dc342fc885c8e2cd3d087115.nq.gz
    ├── 2d02791e81b1918aee00a28b7c5448584ebc015e.nq.gz
    ├── 2db19e3cbd615d41e0b328b2fcd1f146f4a63921.nq.gz
    ├── 2dfa897ba4282e82de5a59ba76aafa458c500bbf.nq.gz
    ├── 2e180cdcce9f016423554e2d1f44187bbeed7848.nq.gz
    ├── 2efd659b8d8e9ccd57ce64b33c271c23221de4b2.nq.gz
    ├── 2f94daa965340290ca93cfe22873a141988766a3.nq.gz
    ├── 30d0d85cee7a0d21213b19b102dfed967893d579.nq.gz
    ├── 30f3cc150a515cfad51ea73416d46f2705759ec1.nq.gz
    ├── 3147ca2a22db6ccb33860ab66576ab5982808745.nq.gz
    ├── 316c98b849bcc7935955f72a4ff7fb2a2875b72c.nq.gz
    ├── 32b6bbe5f6fd1b8e9c9993cf692dec83fc6362ac.nq.gz
    ├── 32cbe7924b480dbf4e2b69117b97f01c899e265f.nq.gz
    ├── 334f4bd23fecd9f183b3cac87f05ef251b92d1b0.nq.gz
    ├── 337ad080befbde5ec35a5ff2b41f41cea3ed302e.nq.gz
    ├── 337fdc4d44fa2ba83d4c68c2533b280eb61d03d2.nq.gz
    ├── 338357437d160783fe47fee2d31a279e97c712f4.nq.gz
    ├── 3430e404a2124e4d809417b3927c5dde8c79e4f8.nq.gz
    ├── 345e404a24add6fbd41f463b0c75c4cea81428b7.nq.gz
    ├── 3460d7568a90f4b5435dfb304c27cbab4e7f5b8a.nq.gz
    ├── 351f8c7df8bf9d0c19ec9b8d9f211a52a370c50d.nq.gz
    ├── 355657f9040295ca071bb2da0949cbb591f43400.nq.gz
    ├── 35c5cc5ea75c771c2699848c657d339144437721.nq.gz
    ├── 3628c5b67d113987e3cd5aee9cd900f2ed059338.nq.gz
    ├── 37615338822f4b8cb1e004df71b3d8557532f05c.nq.gz
    ├── 3764821d832885f5dc43487fd31be0192982aa32.nq.gz
    ├── 37a4d7508604db1758f86c6063571ff41f8314ad.nq.gz
    ├── 381dd858c1573c4f2d95b58789ca6ea0836f5c91.nq.gz
    ├── 386629ca075bc685183950f57d8be5c2402b48a7.nq.gz
    ├── 388027d5a86fc3be8619b7bcb97146b02e784f71.nq.gz
    ├── 38856c8737a8e8066b1204d85b676883e2a292c2.nq.gz
    ├── 3a2120968c6a2780e0bd0fe15e3342e6f82f331f.nq.gz
    ├── 3a27db4fd38df702fea38aebb3b1d99f064ff504.nq.gz
    ├── 3a4c758bde8991d18496f18861a09ddd4c4c8ee0.nq.gz
    ├── 3a83cc161365ac8cb0f0896334c88905c466a29a.nq.gz
    ├── 3a850f712c3cde1916fe5a8889cf1951b4483f46.nq.gz
    ├── 3b34b3268d12079510422aefc5d31622a9b2bf4c.nq.gz
    ├── 3b416664dda4bc7e2d01ed0da80d6e5a8824c07d.nq.gz
    ├── 3ba51fbbd9e25a0b49314cd390b04ffee5bcc321.nq.gz
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
    ├── 42e39cde83a34bffae5f45d7f10e9fb051698316.nq.gz
    ├── 4374b9d67508cbd1cd70cd7d0a75168b052559e8.nq.gz
    ├── 43dfb394b2fc5cdc3fb48c9ce9d6f46a364227f6.nq.gz
    ├── 440ea2284c3e2843f14f130492ee048679347f5e.nq.gz
    ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
    ├── 4553198225a2277a62ba54d5f1985cbdfe37a97f.nq.gz
    ├── 45822afd7e2c528a85f0db734930afab1a0c4289.nq.gz
    ├── 4588c90964a9c19af478c66e3c196ed3047f8489.nq.gz
    ├── 45aea258140a21f53a23ebd3cda12544cbe51752.nq.gz
    ├── 45e161b1ba87aed3cb6bd3bcb4020d52d42e1418.nq.gz
    ├── 45e378f535eac704baa713a9ef11b036daf10332.nq.gz
    ├── 464435ac7c7663d3a87646afbb01bcce34483f60.nq.gz
    ├── 469c309f3a5ece008f0e5b7e1d0be8579ab16f2e.nq.gz
    ├── 47b30c3b0911d41ef9aa421bfaad0b1166afae54.nq.gz
    ├── 47c9f2c23845710c5e3b7989c09916f7355d8c5f.nq.gz
    ├── 487657b522c6bc689794fcf7821f2b4a8857ffb2.nq.gz
    ├── 49573b5ee1d025b41f0cfc144829b750cc77d6fc.nq.gz
    ├── 4972d0a03fef10f8d8820d883588627e4d5cb879.nq.gz
    ├── 4aa0752d496337697530172a66780e498240ee1d.nq.gz
    ├── 4aa57e6e46d88f30fac3952df45152ed7238a5a3.nq.gz
    ├── 4acc58992aab26d1da4d2a84895c51ee35b361c2.nq.gz
    ├── 4ad5062f51ff5876e1417bee5fdda597ad4acc03.nq.gz
    ├── 4b40a13b7330d4c1bf30db37989a6aeff2604a67.nq.gz
    ├── 4b97a2a6f5abaf9af01b28c716dab510f3586ffc.nq.gz
    ├── 4dfbebfaadc40e1b971e849b51483efc7a0c49d4.nq.gz
    ├── 4f029d76e3bd3d6c05794d19de931838c54430ce.nq.gz
    └── 4f2d733b731f052f95f008d23fd2c94375fbc513.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
