# Repolex Knowledge Graph of block/echoapp

RDF knowledge graph data for [block/echoapp](https://github.com/block/echoapp), parsed by [repolex](https://repolex.ai).

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
rlex download block/echoapp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f74abb5bd83771644f7ba9781b89b133b6b89639
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f74abb5bd83771644f7ba9781b89b133b6b89639.nq.gz
│   └── repolex
│       └── f74abb5bd83771644f7ba9781b89b133b6b89639
│           └── chunk-001.nq.gz
└── blob
    ├── 0059c204b0faeb5eae1cc9480e1d44de44fd1ff9.nq.gz
    ├── 0225ab0a44bdc0496a8727c94bbe23290825fbf2.nq.gz
    ├── 04a120523992e5b5b1f38587c1d09c17f1b1f35a.nq.gz
    ├── 06169439cb790d3956565e0421f518a4563d19e1.nq.gz
    ├── 06b88e8edc82efa1f14dcb606f7009072f38fc1e.nq.gz
    ├── 0702663b9744371d0f4d026900a80316ab8275f8.nq.gz
    ├── 07450223733c1589c1b0283ccfd68f8fc425f6f7.nq.gz
    ├── 07630854f486280e8e2c368a3115e963ca3918fe.nq.gz
    ├── 077085839b3c17fdcf2ece390ec8b439dc5e656b.nq.gz
    ├── 079ff209d86771bba4103360e7180416e352f6fa.nq.gz
    ├── 07a20a3a414be9cf9e62046697a574116c192fa6.nq.gz
    ├── 081ebee69c55d079fa03dea80ce8bc6b5328b7bc.nq.gz
    ├── 085ae78438ca4b4607127ebf6bfdaeb6ae83bf70.nq.gz
    ├── 08b92f3226c3ee33b095dfba206280564a751f85.nq.gz
    ├── 08c132a9fce5eb4d38cbd4b125c3bb23a542a263.nq.gz
    ├── 08f1174fe53c240bfde30b549dde5cf1a80f5cb9.nq.gz
    ├── 0916065b0bca1a879fe57273be64da6601be80c4.nq.gz
    ├── 091d3b9b1850eac5ca036d3ae23b2ef4585a70e4.nq.gz
    ├── 09837df62f4459f17b06a7247c89e00e65b88f44.nq.gz
    ├── 0b3539c33115ddad46d77f51843497fe8a73a3d4.nq.gz
    ├── 0b834c53e3d6d5e48efad0df192818c5f2fa08b9.nq.gz
    ├── 0c1645bd08994207eea6be213ff08f37d612f926.nq.gz
    ├── 0c608352198587a9622c952f62ab744a2db1bc0d.nq.gz
    ├── 0c90ad7578edde381be5e285d18930741e3c2c98.nq.gz
    ├── 0ca0032fbcb9fdb3ecedb4f16b4a259985f05cb9.nq.gz
    ├── 0cebb89bb5cc881a8cfa39216916f8fde09fc348.nq.gz
    ├── 0e827a85f2f9db3d77b70495bd80caac290f0698.nq.gz
    ├── 0fcc25d358eb268082f640907bea23ab17625a62.nq.gz
    ├── 0fe02c6d3cfe2409e76a8ec61d4f85251d0bc080.nq.gz
    ├── 0ff8c28fcd61e4a234b186d3e176aa686ce16873.nq.gz
    ├── 100829200b1f584b1c0ed489dc7dc16df12df4f7.nq.gz
    ├── 10b102ad740af068687b32dd01001b4a2d5850f3.nq.gz
    ├── 1189d5e78054eb4abe209b41918ad61622f17046.nq.gz
    ├── 1335e9ed7b0f3188724175c1ac967b0f60ec668e.nq.gz
    ├── 13bec027080a06ebda14305712299327244f5157.nq.gz
    ├── 1496bed3e1fd9843bcdd435fa9e7b8d89b555cb5.nq.gz
    ├── 14b73ced57d823ffbfcb9cdfe3fd575de640e17e.nq.gz
    ├── 14bde3b7f42b97ca87066169632105a36846b026.nq.gz
    ├── 156041cc2114b1ff4178a8ee203c55015a3bc962.nq.gz
    ├── 168c2fa44b61b7eabb38ee593244596512638bdd.nq.gz
    ├── 180b09806c8cffc4ae22acd2fc67af16c4e03551.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 1a0c6182318d879c412f7b280d9a50d864a73537.nq.gz
    ├── 1a0debe61ebf9889d6cb4921456e45378e1e62b8.nq.gz
    ├── 1a1d8bd47ed57fe10b2e4b4374749b8b2c89139a.nq.gz
    ├── 1aa94a4269074199e6ed2c37e8db3e0826030965.nq.gz
    ├── 1ab70140228f8788b2aeb123baf15e2a40ca847e.nq.gz
    ├── 1ad454324720027cc4f88bc60f62363cb40ce69f.nq.gz
    ├── 1b9a6956b3acdc11f40ce2bb3f6efbd845cc243f.nq.gz
    ├── 1bbf12b0be7f74bd57bfb8cd32071d4a0c9103a1.nq.gz
    ├── 1c1e2c231ba89ee85abfa4a3953d6cd936c069bb.nq.gz
    ├── 1c5194596595f34fd0e1b1f4988fd1a487e86fde.nq.gz
    ├── 1c68cb919b8bbc935ced97e04eedf05fb5ae78f1.nq.gz
    ├── 1c9f3763436d234fff552396657dce4e58e08e28.nq.gz
    ├── 1d14bf378782ff59efe41c3028d5285f066fe6f0.nq.gz
    ├── 1dc7c637954ef280ba28f5ad459f95458dc3fb12.nq.gz
    ├── 1ddd9cc4403e84f96af91d43ae8dfdb4b100e395.nq.gz
    ├── 1e43346911a3171dc673ffb4503296afbf9f6ad7.nq.gz
    ├── 1f7d97153f81506b35ae8a78819a5751413feda9.nq.gz
    ├── 200c80e24cf67958ddb1e691875fea3c2737b879.nq.gz
    ├── 2067b352c8893d66a04041e23281dd2b1a59cc70.nq.gz
    ├── 20c7814dfdb326ad66f6d091f81c6fdc59f4c4bd.nq.gz
    ├── 214c3d6626039d211bf052c4fa376b758e05dc4e.nq.gz
    ├── 21814ca0722f11bad38983f967e19c7a6366346f.nq.gz
    ├── 21a11a7403493a2f6b8f0cc17646d6c4c2e08eda.nq.gz
    ├── 21d2bb92d02777c0fbacdb294ecdccb6ee223807.nq.gz
    ├── 224f0eea089f918371cbdf0e4309263fdb842537.nq.gz
    ├── 22e42b2ce546621b473d698c7aa85e103fce3066.nq.gz
    ├── 236a0d8b8c2e1e4d5491ee67272b1bc4f8707cfd.nq.gz
    ├── 23d3f08e98fa077692b6020fc622d5c072596dc8.nq.gz
    ├── 23d5d1ce2ecfa4605a5f1e5262a60ea387778d0d.nq.gz
    ├── 2528846475d1192e5dcb7dc5ac2379957bdd6425.nq.gz
    ├── 27d413c010ff769eff3f962cabf1a748fddb6fa8.nq.gz
    ├── 28288723ce9ecc58914f008a6c6f5421d381edae.nq.gz
    ├── 28327fe51e6b8672d31d245e8e223c4d543ff57b.nq.gz
    ├── 285379a6f27a0b0656c50b68d178c0fd1d943a2e.nq.gz
    ├── 2864fa3d2fc4779fea4bb9ba7a5c136412160ced.nq.gz
    ├── 28d2077fa1d0f803cc354a06924e56ec3fb4b7ed.nq.gz
    ├── 28d4b77f9f036a47549d47db79c16788749dca10.nq.gz
    ├── 2a9341ce01ada82576dbb467598b0ac2209f73fa.nq.gz
    ├── 2af87a8b1112a633a4f914c6725d46240223ab95.nq.gz
    ├── 2bf3db4d2fd61785c321631835d34d02c897e6aa.nq.gz
    ├── 2e21eed2f5348ad7ebaaa1af870dc190fd745730.nq.gz
    ├── 2e65f37707c1b64ea6e763d07ab0cbac4b54cf2c.nq.gz
    ├── 2e9aea1dda2ede6af45af0f81cee0e70e4a96763.nq.gz
    ├── 2ef0db68bdca02a75189675be2820c19984e1bc1.nq.gz
    ├── 2ef43d7b14a1d04d20baff1fb4bb5ce7a3a69280.nq.gz
    ├── 2f0dadd284ad2973d6ef3a21880aee9b3e1438c8.nq.gz
    ├── 312703fe959abbce89d53541ce3b44bfbd0dcb5d.nq.gz
    ├── 3345da1734edaa5f402b3cf25c2bfb4ce099c0d5.nq.gz
    ├── 34403c214ed0489c206c0cb31d48f645f899ae78.nq.gz
    ├── 350877c3bf643b5678238bdf02a5aa1a1e82fe75.nq.gz
    ├── 351ca4df905fa40d6befba4ab2e31bd75557b371.nq.gz
    ├── 3540f307cfe491b113cd5f1bb4fe6728d63d2e0e.nq.gz
    ├── 354a6efbd7eb1f82761f76ec437f80e4c8bb6717.nq.gz
    ├── 354b5b0a4343dfa0fe147b3d7c2a1fe3739241cc.nq.gz
    ├── 35ddaed2f22ace6bf7ce9bca2c5dbb7e7cd3b564.nq.gz
    ├── 36227a19bcb6ce146b9c21180e4735f30911f2d4.nq.gz
    ├── 362999eec91b3dbc9543919143db6dacf555515f.nq.gz
    ├── 364c27e18db24df70902d32f5b4e03b11414030f.nq.gz
    ├── 369a50136b1fc2f25f019c4e5e21090dfffe99b8.nq.gz
    ├── 37387f313f8f296e20580d00fe4fa9512a55b2da.nq.gz
    ├── 37617b19b6d1689d1ebeef3870085eb30f1a9770.nq.gz
    ├── 3763e94d566c0a8b479072ac66d622452570defa.nq.gz
    ├── 37b1ab4ea7515907c86d90428bdc4ec406315646.nq.gz
    ├── 37f78a6af8379e9ac907b8527c9c68807bf42d20.nq.gz
    ├── 38b1f659f492624d35f55ab233de400964f7d6c1.nq.gz
    ├── 39a261d5e0c8a218b9d275999048abcbfbb9e6f7.nq.gz
    ├── 3abac8bb260ee337a756b7d0d2cc0bc738c0fb50.nq.gz
    ├── 3b896f95f67018d741c933cd5f9a7422fa09f126.nq.gz
    ├── 3ba4b091aeb69a2a8af24b420dfb4d03640e2975.nq.gz
    ├── 3c8be65a57255483de7c3889e48eb3e10f8e4033.nq.gz
    ├── 3caee131edbf63d18ac2b287b6638d75fe146553.nq.gz
    ├── 3e026f3bab859b78ef2f8cbce17f00047ff82cac.nq.gz
    ├── 3e4ac71935862781867e835842af8a00989ae70d.nq.gz
    ├── 3eb1386fcc084ec86ac8d453d7e77fccc10d1fb0.nq.gz
    ├── 3ec4fd45526b999b2465ee8d55a3cf6f36a24156.nq.gz
    ├── 3f3e0fd8cc1ba38215fbc929151517f07b235f0c.nq.gz
    ├── 3f89296ab3dda45135d5fc8002d11cb95a1740da.nq.gz
    ├── 3f9d6d37eb270d4f8f0b75ed0e9f987e5ee4151b.nq.gz
    ├── 403ba83af9e0f92ed0bf41232123313af062f32b.nq.gz
    ├── 40aeca5c6b4e651b8d717630ddce8e0ef96b0727.nq.gz
    ├── 40df957e83dff2817e562521396b20eb203944c0.nq.gz
    ├── 413627f2493bc9d0cb50eb211d46bd8349992cdc.nq.gz
    ├── 4164b5fdeb6b62a0820961b24a4ee7c49628defb.nq.gz
    ├── 43695549b9f7542a79b07ff9fb81daf60d8b51c0.nq.gz
    ├── 440663b71531d072f8576b0dbe25d5b6cbf082d8.nq.gz
    ├── 440a152a0b28db423cc07dc31d0ae58c65adba49.nq.gz
    ├── 44e81b7d48392d0655b83ea37477f9eb68196089.nq.gz
    ├── 454fa03e7b2a702a40f9e883b8cae716ac1c92cb.nq.gz
    ├── 45b0509f4c13cc7c9bd5558f459e632ba3df4b93.nq.gz
    ├── 45d89c07347dbae6671e84bd36dba576b7c81bb9.nq.gz
    ├── 46c312a76894a273d3be57b1d8a1247bc945bab0.nq.gz
    ├── 481bb434814107eb79d7a30b676d344b0df2f8ce.nq.gz
    ├── 4866ff9870a90477d5ec0a947a9c61068c6dcda3.nq.gz
    ├── 4a79bef182bc05ddbc7961f24cbe46d1b5680bfc.nq.gz
    ├── 4aa5154a3003e0b67245d97b512d616fbccda383.nq.gz
    ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
    ├── 4afccdb4950ccbbf924af003cf6a1de072d812ce.nq.gz
    ├── 4b084dc198af45fd8d88645c42cfc9042bec690e.nq.gz
    ├── 4b1a03a9825522b81868c8ce9859856a653b4765.nq.gz
    ├── 4b65abb69ba7954f086d58b6d77ac9f261987069.nq.gz
    ├── 4c9c90dec042c364f6bcb97a2e919aac74d3afdd.nq.gz
    ├── 4cd573167a0a5e88076ce2a3034149dd3a028324.nq.gz
    ├── 4d8847d5eab8d95d4817322d8b009da2b5885ba9.nq.gz
    ├── 4eb0f0fd3f0d36bbd23863bc9da47f5d8d5419c1.nq.gz
    ├── 4ed83a7a7e0fcc4f77e801d04da846fd5994ae23.nq.gz
    ├── 4eebdf2dca8b7c577c6a3ce941d192edcc90b386.nq.gz
    ├── 4f0f1d64e58ba64d180ce43ee13bf9a17835fbca.nq.gz
    ├── 4f2ad23094d9aab47e0e0c28eed07635e43ef762.nq.gz
    ├── 4f2e42a202e82e09845fd6cc158c020f694f8109.nq.gz
    ├── 4f43d4e17b33cf6a516813dece3b7e77c786ade7.nq.gz
    ├── 4fa511a2d823cb4219d75d3c38dc9f1266a4697f.nq.gz
    ├── 4fcf1c88b70e8a968a21c4e868b1d65066934571.nq.gz
    ├── 509c86254a7921990f90c837b7ef4f810cd69330.nq.gz
    ├── 510e1fb520b0ede1d3ef8334e2578548bcf2e9f3.nq.gz
    ├── 52c3b43f7539d0bdc14aca2b0fcc57ebc0cbd5c0.nq.gz
    ├── 5310ff5b7dc374f8ea507ca498170aa9126309ab.nq.gz
    ├── 5339b608350dd800c87ddfaba7c6fb8b2d2a61d4.nq.gz
    ├── 535d3638d0618bee5763358ed3259c319edeb4de.nq.gz
    ├── 541666077c3c1362c221e7dcfc1b4e32106cd1e1.nq.gz
    ├── 54ca372c50113fc021d3df6ccfb3ccb15ca992f0.nq.gz
    ├── 54cb59115e7144f5a2ce67a115d8fd59df6e0ff6.nq.gz
    ├── 5589c053345888f27b6067303b3a43ecef77a704.nq.gz
    ├── 55c170cba120bb84ed616457be5d97a548efedb7.nq.gz
    ├── 562cc66fc64e628f1308988b497eb3c6d8f90633.nq.gz
    ├── 575b3243eb298ec8e1eed649021a70a3d2ebfb2a.nq.gz
    ├── 5887c011462be3abbff005eeee6bd26d8465d376.nq.gz
    ├── 5951220ff1ee8cb1d55419eb13f1bfe7de0e4ca5.nq.gz
    ├── 59bad23c41feada9fb396428d16d0b2b7e95e2bb.nq.gz
    ├── 5ad9ce1576fc52f28229404edcbef39381bc57bc.nq.gz
    ├── 5b2c2147698e2c511bafd05c0631bc1d9b58c327.nq.gz
    ├── 5b8cf37a3d47a4908b95a1187420b7e42ff7dfd3.nq.gz
    ├── 5c2ce895987728367462fbae6565e3807e7c0e90.nq.gz
    ├── 5c743c0fec28762a05d322520d741bff3161d00c.nq.gz
    ├── 5caeac9749c1307f24fd12fc5ce8df4400cb65c3.nq.gz
    ├── 5d77fcf25a4e5a21f61b0618760b0501adb60fa6.nq.gz
    ├── 5d9c74b1c0a4843dedeef19034e0b231a8583d4c.nq.gz
    ├── 5e05a5716fc182dc0431a3cf1a8aea11125f82b6.nq.gz
    ├── 5e1f003d13e54bce88c52a968a21725b770ea65c.nq.gz
    ├── 5ee5d1cdc71fc404f2784ab042197851d23ead9c.nq.gz
    ├── 5ee794a69dd53ead888ae120ae143ab81edc0fb8.nq.gz
    ├── 5f0a1be80b7d44ff862c50cd1aa41281f0a4337f.nq.gz
    ├── 5f7b34aa7e6e400cace5205bf38453d73a4c3451.nq.gz
    ├── 5ff3f4633a378c09429cdd9e3069da4d9c571f70.nq.gz
    ├── 600600bbf10da6788b3bc762544148ba04c6dbb3.nq.gz
    ├── 610dc2c6d044427fe4e93fafce0b8a8c306822b7.nq.gz
    ├── 6189654904985228c0438eecb3bc2000fbeeb63e.nq.gz
    ├── 61944dd9fda78d701d1e277266c7e536e46e72f1.nq.gz
    ├── 62a2ce5afd6051e30ecd8161fe6493a52acdf467.nq.gz
    ├── 62b611da081676d42f6c3f78a2c91e7bcedddedb.nq.gz
    ├── 63218fa4acfea152cba2a2df426e8514d0719335.nq.gz
    ├── 633f492e22e8d4d28c6c76b77ab066f47b01271c.nq.gz
    ├── 63705776c502ca0a844cecd63c291c30a1046a1c.nq.gz
    ├── 63d40b0b3c9d03df478ff9b6e4e5b960e6b5ae15.nq.gz
    ├── 63e86dfd270c0750191c40bfa718e7df80c586d4.nq.gz
    └── 64ef0cddb2709a79a88c179bb541135df519e332.nq.gz

8 directories, 200 files
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

[block/echoapp](https://github.com/block/echoapp)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
