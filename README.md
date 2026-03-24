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
│   │   ├── 090a28e46b58473210a74ec68a3c08b1535ff233.nq.gz
│   │   ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│   │   ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│   │   ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│   │   ├── 4d06dff4bc4a1cc16e0f600f71df8f41724efcec.nq.gz
│   │   ├── 5d949e3956e0f78a9497c6b1e8e62676106ff8d4.nq.gz
│   │   ├── 653a3753b71d2b73c392b4a4ecdb2871aa3013ad.nq.gz
│   │   ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│   │   ├── 7ed7d3a0c962b378837c56450f1b885ad7757269.nq.gz
│   │   ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│   │   ├── 8c1671a8b25e3ae0c35370f5918a57671867f38e.nq.gz
│   │   ├── 911cccd630965ff423316e25b4685ecf7df0ec0a.nq.gz
│   │   ├── 9540b5b9c2e630e89ab05de57a82d131adb00ca8.nq.gz
│   │   ├── 9977a2c8fd1067a6c5f9e8301aaba86e2a35c158.nq.gz
│   │   ├── 9f0e4462a89ecbf1e27acb733b9f203297f7c5b3.nq.gz
│   │   ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│   │   ├── a678c2f665a2f52c43b204dd70b2aa677331a423.nq.gz
│   │   ├── b351d730125e622a8439b4ea91927141fbdc5453.nq.gz
│   │   ├── b83b7dbb362dc189b07096a6a4ed494f57488251.nq.gz
│   │   ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   │   ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│   │   ├── cdb86e0cca633d846495447be290cb2511997d3b.nq.gz
│   │   ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│   │   ├── e6e5d3803ba2942c5e19e3c083d289009c27338c.nq.gz
│   │   ├── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
│   │   └── fea121028028ff40da3d7dd85c11e0902420ebc8.nq.gz
│   ├── lsp
│   │   ├── 090a28e46b58473210a74ec68a3c08b1535ff233.nq.gz
│   │   ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│   │   ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│   │   ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│   │   ├── 4d06dff4bc4a1cc16e0f600f71df8f41724efcec.nq.gz
│   │   ├── 5d949e3956e0f78a9497c6b1e8e62676106ff8d4.nq.gz
│   │   ├── 653a3753b71d2b73c392b4a4ecdb2871aa3013ad.nq.gz
│   │   ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│   │   ├── 7ed7d3a0c962b378837c56450f1b885ad7757269.nq.gz
│   │   ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│   │   ├── 8c1671a8b25e3ae0c35370f5918a57671867f38e.nq.gz
│   │   ├── 911cccd630965ff423316e25b4685ecf7df0ec0a.nq.gz
│   │   ├── 9540b5b9c2e630e89ab05de57a82d131adb00ca8.nq.gz
│   │   ├── 9977a2c8fd1067a6c5f9e8301aaba86e2a35c158.nq.gz
│   │   ├── 9f0e4462a89ecbf1e27acb733b9f203297f7c5b3.nq.gz
│   │   ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│   │   ├── a678c2f665a2f52c43b204dd70b2aa677331a423.nq.gz
│   │   ├── b351d730125e622a8439b4ea91927141fbdc5453.nq.gz
│   │   ├── b83b7dbb362dc189b07096a6a4ed494f57488251.nq.gz
│   │   ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│   │   ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│   │   ├── cdb86e0cca633d846495447be290cb2511997d3b.nq.gz
│   │   ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│   │   ├── e6e5d3803ba2942c5e19e3c083d289009c27338c.nq.gz
│   │   ├── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
│   │   └── fea121028028ff40da3d7dd85c11e0902420ebc8.nq.gz
│   └── repolex
│       ├── 090a28e46b58473210a74ec68a3c08b1535ff233.nq.gz
│       ├── 21f51a50a075f6bcc6cde9814ec7a5fa46ab655c.nq.gz
│       ├── 3f48f7eeded881ad0e316a5994f1995ed41326ff.nq.gz
│       ├── 4bf5eddf7b3eafc3882ffb61c8b478f6968b37fd.nq.gz
│       ├── 4d06dff4bc4a1cc16e0f600f71df8f41724efcec.nq.gz
│       ├── 5d949e3956e0f78a9497c6b1e8e62676106ff8d4.nq.gz
│       ├── 653a3753b71d2b73c392b4a4ecdb2871aa3013ad.nq.gz
│       ├── 6720e246357851009f7cf900beaf6299a855a2aa.nq.gz
│       ├── 7ed7d3a0c962b378837c56450f1b885ad7757269.nq.gz
│       ├── 89c0bd238bfb64a603d339fd03df8c66b31354cd.nq.gz
│       ├── 8c1671a8b25e3ae0c35370f5918a57671867f38e.nq.gz
│       ├── 911cccd630965ff423316e25b4685ecf7df0ec0a.nq.gz
│       ├── 9540b5b9c2e630e89ab05de57a82d131adb00ca8.nq.gz
│       ├── 9977a2c8fd1067a6c5f9e8301aaba86e2a35c158.nq.gz
│       ├── 9f0e4462a89ecbf1e27acb733b9f203297f7c5b3.nq.gz
│       ├── a63be71cb2b33bdb588592970e2c76288fd4e4f0.nq.gz
│       ├── a678c2f665a2f52c43b204dd70b2aa677331a423.nq.gz
│       ├── b351d730125e622a8439b4ea91927141fbdc5453.nq.gz
│       ├── b83b7dbb362dc189b07096a6a4ed494f57488251.nq.gz
│       ├── c1cc54f59833e38d58b30a30655404d8b92b84b0.nq.gz
│       ├── c323962bf9617b41e7119d40a9a3de930aa00624.nq.gz
│       ├── cdb86e0cca633d846495447be290cb2511997d3b.nq.gz
│       ├── e15bb79401517ca28013454662741ca9b0646fab.nq.gz
│       ├── e6e5d3803ba2942c5e19e3c083d289009c27338c.nq.gz
│       ├── e91fc38b312e473a414733c13f56855a38c5c226.nq.gz
│       └── fea121028028ff40da3d7dd85c11e0902420ebc8.nq.gz
└── blob
    ├── 00411dd95fa56eadeef3e6e8ad487206fd2803ac.nq.gz
    ├── 004135598c1e645e6d285adfd8590ba24a362ece.nq.gz
    ├── 011563fa500a47c6a85d9aa87ddd0c48fcf74dbf.nq.gz
    ├── 012a2fbdb9194fa1e1b747dcd8d66cdff50b2e6e.nq.gz
    ├── 01d4d1381cd57a2542bd98548032fd4d7007bf10.nq.gz
    ├── 0204d7d54fd4ab158f35064d0b747e2c9ee585f5.nq.gz
    ├── 021c147de45e29bd77e0432f7aedd5a473345960.nq.gz
    ├── 022b096ee44b899339a86ed3f3e49031b0ca4761.nq.gz
    ├── 024db2911c9f8d12209e5f3571e3f7f24ce31acd.nq.gz
    ├── 02ebf13a0c8ce48f5268396c5b480c417a29922c.nq.gz
    ├── 02f25d79dc9dc85af7b7a9aebe03d698ea43124a.nq.gz
    ├── 032943cee48b6c0caac21b80986a9a3e9f3f6b52.nq.gz
    ├── 03a30316859d60e206ee5acb7ccaf0c7a7dbce93.nq.gz
    ├── 03ceb5a248db9f2353ba78bbd784114dfd0e8185.nq.gz
    ├── 057ed462e0974e3599b33728562b767a0fadfce4.nq.gz
    ├── 05a1fd0bea1f3856eb073d98aca463255323353e.nq.gz
    ├── 0704ba7fb06a5c099e609158ee9251ec8f75703d.nq.gz
    ├── 070c583be6eb049b0338f2e3aabb8fba8a3550e4.nq.gz
    ├── 0764eb167ae20842deba7bf9f5f44dcca13bd0a8.nq.gz
    ├── 077edb9704e1c7be1996f47eb416d04e5781fd51.nq.gz
    ├── 07ed7bad059ae3fc2f05d93caf576658a91374d8.nq.gz
    ├── 08007cc79038dd75b7dc04c7f055f1be6a6e04f8.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 097aceb605437763e76c1731a64682b8619a50f1.nq.gz
    ├── 098e7df265245e8ebf8799ac872617643984666a.nq.gz
    ├── 09a4cc9bcd14dec71c96ece7cf739b498b49ecfd.nq.gz
    ├── 09e8b68b5fe531a74d8f49a9417a140ca7d115db.nq.gz
    ├── 0a68be9f16b817e93030af6a8201b4b1bb95b413.nq.gz
    ├── 0a96cc54d8009d70e648fbe56c45109613b2141c.nq.gz
    ├── 0af7025e71403caf497e4f6714d3d17dc147bc8a.nq.gz
    ├── 0b74664ebaa58e6c268ba1c7221b6369e2c11247.nq.gz
    ├── 0ba163ab895541395f035dc9eedc6ccc4bef2ee4.nq.gz
    ├── 0c35ce58ac9890e81cebade1897e4f0a41449c4c.nq.gz
    ├── 0c5f51fdb7e020b97708fc3a941921d4e562d180.nq.gz
    ├── 0d0c23c19351526880d517eefb5039d2b5014187.nq.gz
    ├── 0d4701d6abee75fe79cea59a54cd7463407886b0.nq.gz
    ├── 0d602b50c05a88e4401f362a6536ff89cf93cec6.nq.gz
    ├── 0da4fbe97ca8db70fca00bad9d4a6bc5a7e9274d.nq.gz
    ├── 0e2cdc8ebba6ffa3c19bba46ad49ebf530bdbd15.nq.gz
    ├── 0e36b88e1fca19120fb5e6d16b84023443433ed6.nq.gz
    ├── 0e4db243b1285f8d4d93a876845a3f72014e40a6.nq.gz
    ├── 0ebe4f13b367627b8d901b77f4ed01c55c41ef61.nq.gz
    ├── 0f5343787072e486c71a9364f2a8478dd187b392.nq.gz
    ├── 105f1423a70a94b006bc646c9b95f7b00ead4e23.nq.gz
    ├── 109f96b3d90573d0d786097d9c5aeac2af200fb0.nq.gz
    ├── 10f1f9fb439c96f05cac0141b71c7dafe4eebdd1.nq.gz
    ├── 10f7639762a0dfc0ef97b9af0f6484751275abaf.nq.gz
    ├── 11e5385d1b4eebe4cb0a3f9e1b79d04b2afbd17b.nq.gz
    ├── 1236d017d4405a778b7e102be6ddfc570ec9e41c.nq.gz
    ├── 124efaa3f5f8aeca3be5c327b0ebbc6c92177df4.nq.gz
    ├── 12796e9bca1093dec7451f398e17b50027c59670.nq.gz
    ├── 1295df6990c0914032d8897c4829c758eed4684d.nq.gz
    ├── 12968056d346e15d906a822783fbb01bfbf4e8f2.nq.gz
    ├── 12d1f8ceb4130c1cc14e8f25e514e72475c36299.nq.gz
    ├── 13493aab29766e02c2096c4e4b0dd58c98fc5f8c.nq.gz
    ├── 1357040d0f82caea7d2be482cae5a1e6608da7ee.nq.gz
    ├── 13570d3b6a9a9a473a23a56af8228564f6ba06d9.nq.gz
    ├── 136abb8059a574f06b80debc83fde83c45eea10b.nq.gz
    ├── 137333bbab0e4fcfe30ba1f659420c4182c84a26.nq.gz
    ├── 143e157d7088102c58e8bf212686089fd22b18d0.nq.gz
    ├── 151e28467ff577eec4719068ad11853f630ee07e.nq.gz
    ├── 153be5e2f6f996741b53558d8bc7825ec091699c.nq.gz
    ├── 15b43b1d0a8ead6e9763601c00b1bc6da097d568.nq.gz
    ├── 1624c28eb33babcedbefe61cfe19fdda0831322c.nq.gz
    ├── 166e7ff23debb91445ed24f24f1a5cfdc1fb7d6a.nq.gz
    ├── 166e8e54a30f7d71878e7f0b9a651daba48f5614.nq.gz
    ├── 16a3aab2215013e857eb1f8a8b3201069ad5bcc1.nq.gz
    ├── 173878300e5d24c586cf6bcab0722c8e11b9e18d.nq.gz
    ├── 177861624d6b531187e0325ac38b097ab34b6fa9.nq.gz
    ├── 17a1ba454a3a5c1c8d359020a8f949f9c1cb4211.nq.gz
    ├── 17a9361b3fd7c1f04cba6e72d98aa63bbc8c18d4.nq.gz
    ├── 17e957bf078ab409d364d6f5bf0452791aee9b31.nq.gz
    ├── 1884b6d864502bb1ebe12a68c72944dcf0e0a87f.nq.gz
    ├── 19155c818208099975b6a35c05a18527d1940dca.nq.gz
    ├── 1948c60c99f156e6ecf423dc6133f42f978598d0.nq.gz
    ├── 19c3210fd939e35c47d9a32faca0c8d3fd732b40.nq.gz
    ├── 19e68a37004d8c9e122b72833ff1d792cde907f9.nq.gz
    ├── 1a20ef6d674f68ff80e8352bec579fc08d75a03c.nq.gz
    ├── 1a7e541b784ad818760d100b3c3a449f79c78184.nq.gz
    ├── 1a96e0589390762d4891412c98c4976190820a5c.nq.gz
    ├── 1abb1eb29d39dae91ce2ed4ccf9e18498795470e.nq.gz
    ├── 1ac9eafcc45ae17e4bb1ff22ce51daac2e4e9d40.nq.gz
    ├── 1b270f00c1b70f6727c1858e51352a87691a571b.nq.gz
    ├── 1bf4d98c0fba94f713ca403c68ec2c6edf922aef.nq.gz
    ├── 1ccdd686e905fa760cfbd184f20c12ac62760ec7.nq.gz
    ├── 1d9ffd39f8f3d392310cf1130fe9eddedc1bd0ed.nq.gz
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
    ├── 242358ed8b59599f2d52f3530e550f04804b1711.nq.gz
    ├── 2485730432cb9d26a5024075c34ad95933e3679d.nq.gz
    ├── 24acaa1b1fc44a8802a5b1032f53a1c76cf8344c.nq.gz
    ├── 25272947bbfda7cb2f8acda6b21cf2cffc371385.nq.gz
    ├── 255239237aba179cde7b7cdead015fabd76248da.nq.gz
    ├── 257864fef9ff36359b772356325234199b9ea5f3.nq.gz
    ├── 25a87ac0ae7a8a990e46b4e3486079efa4744560.nq.gz
    ├── 25cb85db0098fc1ae9085e8b7a98a9f8ed8fbedc.nq.gz
    ├── 26296ff52fae8cfb76d6ae9230506e688b621771.nq.gz
    ├── 2650ed372390a7af13e28d4abf64d4daf4c6049a.nq.gz
    ├── 271b81ad4b1c88c1722a0125b874d8a7bb5a5257.nq.gz
    ├── 273efc55905e843f880118ecfeb1bc28a59cef9e.nq.gz
    ├── 2778f2abd6b65abf88cef27c99bb11c3ee3842cf.nq.gz
    ├── 27a58f97acce20426d860421ebee3470b2d1aef6.nq.gz
    ├── 27d69170179317085c62715cff9ce0c810148e96.nq.gz
    ├── 27d7e7d1ea44c02583e633bc847e86871a8fe948.nq.gz
    ├── 282db48799f6ed6a417f0cbc058ce660ab3e764b.nq.gz
    ├── 2888faa7b494ebebd837ad3da31bf11942bc8d21.nq.gz
    ├── 2aa36d5c7593ecf1551056aad60cec58e6010edf.nq.gz
    ├── 2b06bee8b4e51668c01255160cbf30e68e334073.nq.gz
    ├── 2b47f9e3355f509244085646439128fa2c332615.nq.gz
    ├── 2b7a44336e57729be70991aa9edabe5167d3b34a.nq.gz
    ├── 2ba9192a7334e0ee088d3347dfc9a1280b01a8cb.nq.gz
    └── 2bc61bf1d1a1cb66489d20b90b8052005a3e81f6.nq.gz

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
*Parsed on 2026-03-24 by [repolex](https://repolex.ai)*
