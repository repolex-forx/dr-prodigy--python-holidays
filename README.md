# Repolex Knowledge Graph of dr-prodigy/python-holidays

RDF knowledge graph data for [dr-prodigy/python-holidays](https://github.com/dr-prodigy/python-holidays), parsed by [repolex](https://repolex.ai).

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
rlex download dr-prodigy/python-holidays
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d3d32b9a9fbd1ebe1413c2b59eb158022fd01c2e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d3d32b9a9fbd1ebe1413c2b59eb158022fd01c2e
│           └── chunk-001.nq.gz
└── blob
    ├── 00692727be51bedb7de2586a3dac970a8c9af09c.nq.gz
    ├── 009bc044d355ceb58d03dd5985d620d47319c5c3.nq.gz
    ├── 01073e014b27ff5ef955893fcf504e366dce65d0.nq.gz
    ├── 016cb75057a3d86e85d01abbed237169ea334a34.nq.gz
    ├── 01bd320396ca4b5d8024e40643b5657fd08267b6.nq.gz
    ├── 0297a0f3d5b6d4a41c9d607b50ecb05dc2b4155c.nq.gz
    ├── 033616f0a20b5e09465fe3292c8d9e858e23dc13.nq.gz
    ├── 03652e8d306ac6554573c4d94896031833ccaace.nq.gz
    ├── 03b59121749ecdbf7069357d4e2669a293228787.nq.gz
    ├── 03f303c872b0f596f82cfca3d0d06900f2e63fcd.nq.gz
    ├── 04025edb9d2c46d60c2c4c68c2e0a70605404f3d.nq.gz
    ├── 040faae1c6e37b96cbcde6fe0af8b867c84b00c9.nq.gz
    ├── 041fee5415a4650bcc045e8881bb18ac792047a1.nq.gz
    ├── 046b3ead3c617979367bf309ccfaf7b5b04b42fd.nq.gz
    ├── 0548125e0cf2f755c962cef75e330f41793f84be.nq.gz
    ├── 0564598aa2d434fc6573900d0aa97f75c1d45951.nq.gz
    ├── 061f32f91b96f05f8fa2b52b2edcdcc19aa33d50.nq.gz
    ├── 070486e989833e5e4ba4f4ab112a3d8c52f143a8.nq.gz
    ├── 077d335ba2183b52140a15001afd4feb46afaddf.nq.gz
    ├── 07f5dc9c1b861c646acdecec075e4a16dbe7c1a5.nq.gz
    ├── 085d0a664086542555da6d10e9e75ed7b54efb54.nq.gz
    ├── 09254424342243832847cf9f6c8051445bf96197.nq.gz
    ├── 0948c8b1aab25f0d16f025021aa4fb04df7bc5b2.nq.gz
    ├── 0996f975e5ed8924e281e11cd7b61fbb9eaa05f4.nq.gz
    ├── 0a224091e6df93c1becaec2605e5d7b06e7e5c26.nq.gz
    ├── 0a50e11556e6f7cb732de56bbef129bda2250089.nq.gz
    ├── 0a96ac22af80546706eae3c36f3f7f176358b630.nq.gz
    ├── 0b15b446fa46fd0de375bfaf99b624234bcfb4da.nq.gz
    ├── 0be0ef5c6d39b7c17c89bc948e929c31eb1e22bc.nq.gz
    ├── 0c5b54ebc28d908e76d06cba9aa891db370729d5.nq.gz
    ├── 0da5f68a5496807cbcd16dce64acbb3ff6b98398.nq.gz
    ├── 0e02f932bbc37bba266a0d2258c7dbe7c624fcdf.nq.gz
    ├── 0e462c9b3035b054a3917f17bcea1ab68c138c4f.nq.gz
    ├── 0e84836642d8fe47083d3720620c850522bb21de.nq.gz
    ├── 0f42e28e93d855ddd0bf12be09acef4b7821878d.nq.gz
    ├── 0fe1d5ec6ff31402ed0bc0303c70fe857225dc2c.nq.gz
    ├── 10b368d9c7974a7b8f897e2ac27b595f609fc383.nq.gz
    ├── 10c208a3ccf86f7e000b50e9b4ae83e16f91d806.nq.gz
    ├── 114501044f87c4cfe66c30e3f5bafb5d3275c4de.nq.gz
    ├── 11a9c57569389e6495dd567c53ad93c290b0dc17.nq.gz
    ├── 11b9579f9151bb99632f9bf9433909de56c91a15.nq.gz
    ├── 11d3184a2cd6e86e24fccc58a7361b3249854205.nq.gz
    ├── 11e1119bc409dab899d100641123a6dcfd0a1cc9.nq.gz
    ├── 1267c13d5c380149279ea228a633ebe4d680b2a8.nq.gz
    ├── 12c82556059d16fd69def4acb590e605b38f60d4.nq.gz
    ├── 13030f39a4ec509d78311dd3259f569049c86fbc.nq.gz
    ├── 1364008e02e63a5dbf5b70d565e00cff1c928cb5.nq.gz
    ├── 13dc1966c19cf3de0dacbb6c10ee5b192e190dcf.nq.gz
    ├── 151242a8a82dfe4383bd29c383e8220dfd4d7ece.nq.gz
    ├── 154cd686b1207385f50f4e9adefb085ae309c9f0.nq.gz
    ├── 159b16f62358073e7a0344e8323f6dbc18fd3961.nq.gz
    ├── 15fe6d1fe4dbafc49abe9c31947778c0fef924b5.nq.gz
    ├── 165ed938f1690876cc7c62109da9e5cf5ac6fc98.nq.gz
    ├── 16b61d180a4a4b47c6976ef24111d9a2f3655f7e.nq.gz
    ├── 172f1c7f18df4376bb0115108d513bebff3450a9.nq.gz
    ├── 17b63d39c79ac811e00a58a106e51215b46fded8.nq.gz
    ├── 17c7070c3db907fda83c25e0ff662eb376874704.nq.gz
    ├── 17d64cda1bb8f0f0576f4e23f65c0b6db9178dac.nq.gz
    ├── 1806a8c6f4af96723060ff92942137989a9f9069.nq.gz
    ├── 1824f4ee872e90f761fba76226565d05836c51da.nq.gz
    ├── 185487ac73f39e46a1cf07a9cbe1a828370a0566.nq.gz
    ├── 18d08146c622f370958c27308c789e07034082e4.nq.gz
    ├── 1917c9161ed05f52d48820dc71dc716843f1c411.nq.gz
    ├── 1935c08197a6d5f4c9de8eb211d01a35d6374e52.nq.gz
    ├── 19370fa37612a73273211537eb675aded0a8fcc8.nq.gz
    ├── 19bc83b9aabaed961a6e20aa5f61ef3b4fde00d3.nq.gz
    ├── 1a04190043e8add18f68000616dc154e20bdee6a.nq.gz
    ├── 1b02d543973e66007cade0feef4e6ba41c0ee6fc.nq.gz
    ├── 1b293eb7d992fd14819f578992ce52e353cc6792.nq.gz
    ├── 1bf4ccbf93172e4d02ecf614e1e20785c6fc9d73.nq.gz
    ├── 1bf761ed91404c176740fb7e00c12fdf54de101d.nq.gz
    ├── 1c45392c797ac58569d9c3fa30c6fc02b63199ed.nq.gz
    ├── 1cc2ac2e52e7b5e48f18e2c8a63deea00b4e49f6.nq.gz
    ├── 1d3ca712f1e43232197246ac3d7a0675bf221a89.nq.gz
    ├── 1d762f2b07a83593ad3e8466d95eb590ee1785b6.nq.gz
    ├── 1d8232e2ab8d4c836fc9af2fd9d8153f93b3b00b.nq.gz
    ├── 1dc5b7734b716ac8ceabf7a928d1bf1d6da558fa.nq.gz
    ├── 1dd02a668735e27169f1081755221f834047caa4.nq.gz
    ├── 1e026603a728844d5605ddd45205ba7c17ad6287.nq.gz
    ├── 1e4b063e8c9148beba2359e182b6a806bc90ea6b.nq.gz
    ├── 1e9e035e799c2cecb047d455ce5f5870f84d6516.nq.gz
    ├── 1fc8c8771f803666095571b060547f94d67a72bb.nq.gz
    ├── 2030dd4e61ae6dec4444ac9bb1737fa33fa03e87.nq.gz
    ├── 204845091302137425f4ebdb7d7f27f8778f08e6.nq.gz
    ├── 20a0760623b741171e68adbb83b6f61da46d0f5d.nq.gz
    ├── 215d1f4be94ea041d29af8764028c41a7fa378ac.nq.gz
    ├── 21cb8e796471fee4ef9671e969023aa16b885c76.nq.gz
    ├── 22dd962521e70c48343dad72a88f6cf2bed47a6a.nq.gz
    ├── 23237f8a52b0d83b31f026e0e72350ffca541af6.nq.gz
    ├── 23bc94638469ab706e8c04f91709b3a754d6aeaf.nq.gz
    ├── 23e175fd84ced1010663699af6bdf81ad6a684a0.nq.gz
    ├── 23ff6390aa063c95c236791be1fe1d3187deef00.nq.gz
    ├── 2517a45dfaee2c661b7d4bc9b7665995dc00b943.nq.gz
    ├── 255a863f4be45de6fd8ab842d05e13c07bcffa74.nq.gz
    ├── 26486159ce41c4362d7bbe1e3a39062a49d1cbf4.nq.gz
    ├── 269c96dd5b0d178e9e5e27808fa4578833186f98.nq.gz
    ├── 26a6e747f722fb5ac7763cc71ba4c7591517e2be.nq.gz
    ├── 27493fae4d40fdc783728467697c08bd5ff6f242.nq.gz
    ├── 274b73027375cb6e7dbfbecc03b19c510d46ad58.nq.gz
    ├── 2771b61ed10d0407b5cb9bad934aa62eb1387de9.nq.gz
    ├── 277d9cffd4026391b3f721baabe9356114d7da31.nq.gz
    ├── 283723d4c76db8d778acd77044966731a9cc8a0a.nq.gz
    ├── 284e01f830671701ae5ffeb78f042b7a91de43da.nq.gz
    ├── 28645a68efc6e434cf8e9e0bcef73b606c39d4c8.nq.gz
    ├── 28b37099e1b0f7e166e5e019d6d51ac3bd397654.nq.gz
    ├── 291e4f97b9d6bdf6ad7aeb872b362b9435bb362d.nq.gz
    ├── 295778bb419e639f915f0fcfb5fe934f8473b09e.nq.gz
    ├── 2a36c3caa4cbae42b67f8db9a89166a2edf2534b.nq.gz
    ├── 2a680be7e2edf6657466d6403c1fa1030f71a875.nq.gz
    ├── 2b1d3d63122d27762b6386279b302caf86af6766.nq.gz
    ├── 2b67685b24642631c627e559496eddb77b2b2e24.nq.gz
    ├── 2b95a5969205f122134f74fa92328b04f4c5ac99.nq.gz
    ├── 2c0f1027d356f6aee5f605470379cbd512816eea.nq.gz
    ├── 2c34f04085a92b4e9041ff2a9080d502c2858692.nq.gz
    ├── 2d18ce6dfa1363022bd868671f6a481b87c0bb4c.nq.gz
    ├── 2d5690d40351d53b5734a8202c281567ec9e126f.nq.gz
    ├── 2d5f971689296139bae14ae62118e42e40b2498e.nq.gz
    ├── 2dc0a06d124d905d0d07275d8672ab6c2503c6a3.nq.gz
    ├── 2e250785d3a795a077492e90ed27b035b0af6822.nq.gz
    ├── 2e57543ad1f6e5cb645db1ef758f99efce9b10c1.nq.gz
    ├── 2e8eb9889a2f374e7a9ae8b71b3d37516a4239fa.nq.gz
    ├── 2ebe34aa70e096681de630046660786f1e53b70c.nq.gz
    ├── 2ed6f054c316f4de60d2bcb1068e834ddd12ccda.nq.gz
    ├── 2f2d212b5b5826fd8e75bc01383261e573f3ec48.nq.gz
    ├── 2f35ceeea341fd0f53342398f8f14392d4f03d42.nq.gz
    ├── 2f6a416518337e5e5a716ab2124f42bfb9d91158.nq.gz
    ├── 312a6301c3664aa03df366c6c433982327673104.nq.gz
    ├── 31824d708c10e554c2a303a21bbade56fdeb8da7.nq.gz
    ├── 319817fc15d63adde27b90e39cb1a286c82afa96.nq.gz
    ├── 31cc0ff2eb55eb1e73f3ad6f78c6776845a1ea20.nq.gz
    ├── 31d9b4105fc7068a518bc8779b2695f316292db0.nq.gz
    ├── 31f39adf14ea90bff7c5c2ba03e8ae7818c7d324.nq.gz
    ├── 325545bb5891a7e8ac1302677656e9146de14349.nq.gz
    ├── 34ddc4e46050fcb0ca27bdaefde11155c9d9670b.nq.gz
    ├── 356756b9aab2b53201bfbd434dc8e326a41b0ba1.nq.gz
    ├── 36888b7fcaab5e9adb7ac712f1e368e8936dfd19.nq.gz
    ├── 37a67f761429991a24252359f2eee40c953d8855.nq.gz
    ├── 37b5de68b4b6306f02c3b4c82ac6767f364a4f6f.nq.gz
    ├── 3933501bd646f9b4f0ef32c8845cde9435ceea22.nq.gz
    ├── 3a831f2ba455f27ac777ff4d937d39b51e26051c.nq.gz
    ├── 3b0370b36ae18df670316a8aaa5fd52841764370.nq.gz
    ├── 3b2dbe718a7ca3adcbd5eb1216860a3766a9ff05.nq.gz
    ├── 3d27e789dea88b44fec845c7395c6c3070d16acc.nq.gz
    ├── 3ea90055961c59fb78e403ff79a6b9192e387004.nq.gz
    ├── 3edfe32375c71e9d9d95e43378da8fc35b69cf22.nq.gz
    ├── 3eef6cd68a3cba1fa9b52d5617f236cd0f99ead7.nq.gz
    ├── 3fa44b98a550d4dec36fc4b81aed45449938d11d.nq.gz
    ├── 4013b0dec29e4346adf54323c4d9d9251c4717ac.nq.gz
    ├── 4023bc22cbf4d50b75cded74300521592ce6090e.nq.gz
    ├── 4091c5a7da7e8c835aaaac2458f51c80802c7cd6.nq.gz
    ├── 417e21e768a4bb59bc0c5fe48cd5d47d7c151284.nq.gz
    ├── 42408f34fa9ff51416085053bbd15d358863934b.nq.gz
    ├── 4242b35209481f042d04bfdf172a06ae8f66f9c9.nq.gz
    ├── 4282322ac52f6d37d59acf75512f92a56db11e83.nq.gz
    ├── 431d2476286161ab8d704df10c6890397429f213.nq.gz
    ├── 444925ef71577c38b802c407116a65aadad1cba7.nq.gz
    ├── 46bd42349ddf81927477a0185a40602e1c9af275.nq.gz
    ├── 46e3c83feeddc92fb6c87ce746cd26ae0ee0be42.nq.gz
    ├── 471e51a631fedd74c7f25beb7e28b66d3d2d1146.nq.gz
    ├── 4765d589663b7dc3927d9d076beb5246994bae16.nq.gz
    ├── 48548d02c8672895cbc84c8dfdcedbe2fcdc47cb.nq.gz
    ├── 48afa6b1c64cb04c6bd633d8c0eaec80016291f5.nq.gz
    ├── 48bb692f49b7acbc011abb15abc412fb3ae51086.nq.gz
    ├── 492a2db723aaa2b5f6544665acc028959b69820d.nq.gz
    ├── 498d5f77fbac3a8ca4b78a3f20ffb47624b24f08.nq.gz
    ├── 4ab7442046e9c99681a240c0dfcc05233bb03a25.nq.gz
    ├── 4b7fdb8b743cb23ea8d5aa7dedd5f5045b0f11b5.nq.gz
    ├── 4c3acd416904abf934eea360bbbd01ee3b6792d5.nq.gz
    ├── 4c63203251a400986e63c787374ac313b11329d5.nq.gz
    ├── 4e11569da994888d7fa3bc5766174c3fcfea87e4.nq.gz
    ├── 4e4e133faed17c044f031307d8de829e77917840.nq.gz
    ├── 4ef2aa2d95e578cb0066b6236540d93f164741aa.nq.gz
    ├── 4fe1fce8ace567311d51d476a743c087385f908c.nq.gz
    ├── 51b4262f38397ff4ef467ee867695f3a30a7eee6.nq.gz
    ├── 51b6fcd122a6f81e13944db98f0852bc2e5f2463.nq.gz
    ├── 51cc20d473bcf71aa67fe4ab64db05f8340639c4.nq.gz
    ├── 52d8df59e951caca944450465ff044f6cc69c57f.nq.gz
    ├── 535ac319a6b53691582b224ea9beb0399020206e.nq.gz
    ├── 539046685add7db7ba8a9364e7dc58a4424ae920.nq.gz
    ├── 541ffa78b399ff977aba1a619c44280f133f33fe.nq.gz
    ├── 55bfb19bf8de083515680d0078784bde414b3fd4.nq.gz
    ├── 560b7a1a46566a93d3716ddb2bf8d036a3489d7a.nq.gz
    ├── 561f53f20f068982efbad8f0ff6b58fb1dd74a2f.nq.gz
    ├── 56a514340840eb53c47a78251c839f02937e2a41.nq.gz
    ├── 57f5d88cc5fa8194b51c36935daae024e5ae22a3.nq.gz
    ├── 5833e091a5f4a9faf1d25a0d9a6aac8864ce61a7.nq.gz
    ├── 5893b8c797becf56b7009555fb365f38686ceb32.nq.gz
    ├── 5952e82337ba6ff9631d45c89a3a2ca606e8eeec.nq.gz
    ├── 59fa578317966f41c245388fef434997c16c2981.nq.gz
    ├── 5aec8b9e669ebfcdf46338e111d79ef89f4dd739.nq.gz
    ├── 5b03b5da347c439ae977b0ca4fbc00b69bd70aca.nq.gz
    ├── 5b968b1947e05b1a4ac470cf1a126c0629e5b19f.nq.gz
    ├── 5c0f6d6d9918c6a142dd22610cc1486200a8ed67.nq.gz
    ├── 5c18a45891ac44f26bbac4e9001fc88df81a3095.nq.gz
    ├── 5caaeec36fcd029ccddadfeefe27ace75ed2beef.nq.gz
    ├── 5d6cca63f1347227db91c7ed4ed37a58d4170b80.nq.gz
    ├── 5d95feebd9a74fd3ee97a8996ba27f4974e01495.nq.gz
    └── 5dfcbf4c5117bc2592cbe02079fb7a30d6d87e2e.nq.gz

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

[dr-prodigy/python-holidays](https://github.com/dr-prodigy/python-holidays)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
