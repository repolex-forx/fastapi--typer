# Repolex Knowledge Graph of fastapi/typer

RDF knowledge graph data for [fastapi/typer](https://github.com/fastapi/typer), parsed by [repolex](https://repolex.ai).

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
rlex download fastapi/typer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── b15210b71a5b9b35be82a1ffdb172ef7b3a89d85
│   │   │   └── chunk-001.nq.gz
│   │   └── eaec8fae8a8ab39a64a20f39190f13400b639a22
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── eaec8fae8a8ab39a64a20f39190f13400b639a22.nq.gz
│   └── repolex
│       ├── b15210b71a5b9b35be82a1ffdb172ef7b3a89d85
│       │   └── chunk-001.nq.gz
│       └── eaec8fae8a8ab39a64a20f39190f13400b639a22
│           └── chunk-001.nq.gz
└── blob
    ├── 00384d1f559152bce67a596db2a319a027cb7ee6.nq.gz
    ├── 010f899034c6b19eebe5e33a4735db930c63d8c3.nq.gz
    ├── 015262728d8581fa10ce918d7f8d5dda41e1177c.nq.gz
    ├── 01533e71cf287181ed542b3aead84703bf49fdc7.nq.gz
    ├── 02269c7108d0cbc6d14c08a4798aca09e9549cf3.nq.gz
    ├── 0232605f97f3ab526b36eeea7e97350e07b51b1c.nq.gz
    ├── 024b125466802552bec8ee6349cc982f19535316.nq.gz
    ├── 0283347a6fde7d8752427eff2cc2df8d5e061018.nq.gz
    ├── 0337e933e6f6f7a0a7071ae611f47be1891892c7.nq.gz
    ├── 03f91279f390d06082d3871cce8665867dd41ecb.nq.gz
    ├── 03ffd9c990b1002b2d89bbb70b82196ecc63702c.nq.gz
    ├── 041bc0831a413a44b1fd1373e3b3d295ebb7133a.nq.gz
    ├── 042620f9a0e2dd873e8b302a349841db66609294.nq.gz
    ├── 049ec4f6af4a0d04ebb2fb88d486e64caa2e8508.nq.gz
    ├── 0503b410af83b5d6cec7dee11467776a4d832d24.nq.gz
    ├── 05752c5c0790458dcef7867d3929adf9f699f15a.nq.gz
    ├── 058bf1e469365c4b192d84ce4d5399f9ade0fd3e.nq.gz
    ├── 05cf245b26941dc721eff257dfd1fb520becc36e.nq.gz
    ├── 05fcd61cf4bf02338f844f3e6cdfa45f23d71b8e.nq.gz
    ├── 06588837335d6e7444556ad414a76dc13435bcb5.nq.gz
    ├── 067bdffe515bb31920eb9627be556a8b2a821e2d.nq.gz
    ├── 06a020ad8ea95b4b84b8210fc9f3688f9208c472.nq.gz
    ├── 06d848c9b6f8cc9811fca89d6d2e3a7de9c1188b.nq.gz
    ├── 0791fab3339206350130514ccfa70aaa5dde3311.nq.gz
    ├── 08cf334341cc6f1b3ef195f088b3b4c916c454f8.nq.gz
    ├── 08d43ff87eb9e91105f0c26ef87f12a1ae3ba2db.nq.gz
    ├── 0947a5e77e43e7952316eeae292c0f8edf82e764.nq.gz
    ├── 09711e66fd82bb7214f6d6a43ba5bd0ae8602865.nq.gz
    ├── 0a73c7ebc3121672d0d4ac2481792e09adf1c673.nq.gz
    ├── 0a7f9d042997782af5002da62655a808fb2a00ae.nq.gz
    ├── 0ae2c594c3aa98254dd06c60a7d889af3f5bbe62.nq.gz
    ├── 0b22469133e38d47bbf2f3e5b4ddd03375526dc7.nq.gz
    ├── 0b3bd2bac19ab2313ec7447769f0c332d3856f97.nq.gz
    ├── 0b577c1c4749f5b6b08345553666cd58ef0765d5.nq.gz
    ├── 0b67d3c5606bffe9f6654eb3181f0a39116adff4.nq.gz
    ├── 0b6da988a6a5d96ed317c75b43b43773870ba000.nq.gz
    ├── 0ba1d8882ad53326be81eaf333c4083b93c55da1.nq.gz
    ├── 0baef9e301edb3ad199db1ea874b6ccd22270251.nq.gz
    ├── 0c1bac04e47276c56ce18dca87e3600e321bd48f.nq.gz
    ├── 0c5d120e5fdad0d87d93fd10cc3884e3bc582cf6.nq.gz
    ├── 0c670a84e662832c051a1fad8425b45aae6c241e.nq.gz
    ├── 0c75055eb9b670f6e9f7378f77b12bb38515feff.nq.gz
    ├── 0cd4acbe2b1f4aedf358fccd59c9e52fdd1c55ee.nq.gz
    ├── 0ced4090b37634ca424704540528513db2a02f75.nq.gz
    ├── 0d0874d2ba8dfb74e3acbc284e63aa4f5e48c960.nq.gz
    ├── 0d621e411d7bab9a6d4ab14102670adbcabaf962.nq.gz
    ├── 0dc0c35f868778aebbb21c3f78c4bdea4b85bd2d.nq.gz
    ├── 0e3daf04c463061acddc036334a9c98b3b810fa8.nq.gz
    ├── 0f2f8140156a9449791c707f15238e7e31a9cf40.nq.gz
    ├── 0f6c8e458d09b26ee0e240dcb7bbfc231901dc68.nq.gz
    ├── 0fd8ed8f33eb0b731556ccd246d4a300103b0fa1.nq.gz
    ├── 0ffc101a3f23548392499fe5104f3f8cf4d4e91b.nq.gz
    ├── 102ce8d70e0d98eb95ac08d76591a99f52d0c67f.nq.gz
    ├── 104d8b200e742e297cf165835ce252b7f654b7e1.nq.gz
    ├── 10ac532ad285a886c331bc5abea6742391797ac9.nq.gz
    ├── 11098b1085a2fb6a65bc265ee5fa48468038bed0.nq.gz
    ├── 1236f33e57bcf80c636f7fbce3a7dbf02fa5f757.nq.gz
    ├── 12c32214eaad871b47645084d60ce57e13e31051.nq.gz
    ├── 12ec33812300e38fbb231fb6a7c662724e26e582.nq.gz
    ├── 13b25ba7a38166de2ae82a13568decb8dcd64d31.nq.gz
    ├── 141aa375aa4086c87679d163ee5486b2576b02d2.nq.gz
    ├── 1442aa24422c7877bf1e0d9eb1e73839927b9370.nq.gz
    ├── 1638b5e720f60fb4d02d3622313c7fdb16ed49d7.nq.gz
    ├── 164bc739163e4cc2526898afd0c49968be7fe7b4.nq.gz
    ├── 1655fec7885cff70831fe392e88dbcc19ca9d344.nq.gz
    ├── 1688bf193da8493af1869b6061762f53f63a62c5.nq.gz
    ├── 170522c3dec1e49f03fe34a2ca4096c4dd845d3a.nq.gz
    ├── 175841b304eda6d1134b9839d584c75720dbdd27.nq.gz
    ├── 177871ed83ebc99c954fa58c60d3f811a9f6f825.nq.gz
    ├── 1784b13f0641d6c1236eddf5d40952bb2dbcbf73.nq.gz
    ├── 17850f600793548f9f499d13912fe31b47be7a1a.nq.gz
    ├── 179f6936fc360db5aa5b1a2c6a688c1c5888f9a2.nq.gz
    ├── 17bb7ead3710a5071071f9e72476815dba0e3728.nq.gz
    ├── 183cf318daef8f26450170300eafc34309372974.nq.gz
    ├── 1868d01a7601f114749aa6ce7a87166fa0219e44.nq.gz
    ├── 1870e9c6c3cdc1e7cac4f49a3fb6d703d0005145.nq.gz
    ├── 18740beec366363e000aeaaa61d24b9e1e830d59.nq.gz
    ├── 1887b2f289d788fc78a4d60370c660ab623eb838.nq.gz
    ├── 18c3374ff360bd0a37ed227ec7326411f1abd47c.nq.gz
    ├── 18f172e691a0b9f2ac0b0aaeef55f53b3976ea89.nq.gz
    ├── 18f4b00efe4d8d928d2441382ef253625dffddf4.nq.gz
    ├── 18f7660c167025371233e63e7642cf6f53b10470.nq.gz
    ├── 196d94db6fb0be030457b3872012b84b2097a1b7.nq.gz
    ├── 19dc48acdaec53bbb7f89d5de86643693a765d7b.nq.gz
    ├── 1a50e246817513a7bb22027f0428a06b9faacc50.nq.gz
    ├── 1aa65971e73ae805763f631b584dc4369500ec59.nq.gz
    ├── 1b4c0f117857d66f206059e40185aca6e429d6e4.nq.gz
    ├── 1ba882ac8a3acee8bb7d49593a74657415eebc29.nq.gz
    ├── 1c4f2a7cf0b15496f0a1845eedc4aab11739e3df.nq.gz
    ├── 1cfc18cc20d46c1b4e83671ddb9d1ac634b2cba0.nq.gz
    ├── 1da8bb73ef8040f9862a5571e39586a0bc46da48.nq.gz
    ├── 1e078173294f7b774e9239bc1334066a37029b0d.nq.gz
    ├── 1eaddaba87873cf9b8eae681724b6652b44bdb43.nq.gz
    ├── 1ed8610db8933842fb8c1b40c8c8b723f9172f5d.nq.gz
    ├── 1f1b7904de9cabb81d509b54680f16f1cea91189.nq.gz
    ├── 1f3a98f776b18102c3832b80da37c659c5513373.nq.gz
    ├── 1f78ea069c9b0343a5eeb9c3d6c02842932fa248.nq.gz
    ├── 1fa6caad27c37701190a2ae41262e7f5d7c524d4.nq.gz
    ├── 1fd6edfea6bec5dea394793539bda6244d596ded.nq.gz
    ├── 1fdc3e36b0b48326274b41acc477347f9ffa9e1f.nq.gz
    ├── 1ffbb833033e228ada22eaee2bfe4ee7aebf479a.nq.gz
    ├── 20695b93399a9740921c396839cb0c8589f03323.nq.gz
    ├── 20bd6b76eaf581890387258cba82971f58a0c5ca.nq.gz
    ├── 20d091d268b5d8b6b69dc747457991a6704e9e79.nq.gz
    ├── 210e9da0d3900927b44391c0ee1a9d6192639d57.nq.gz
    ├── 210ff5bb08c6b87761160a8b1b70e7a0536496e0.nq.gz
    ├── 2158474cd274237678dfd53fc230b0eccdee4055.nq.gz
    ├── 21801861bc420df6b5c00d39fbdf5ea1ee0d539d.nq.gz
    ├── 218f674c2220589738656294fdd8ec243965376f.nq.gz
    ├── 22bccc9a8db44e275b088e62eca5b2887e78961f.nq.gz
    ├── 22f902197bf68332969fbd5c6bccd453a0ae1eff.nq.gz
    ├── 230c8c0c1f051398ddaaa0baef99e37d319d6e6f.nq.gz
    ├── 232b2ceb3e9679b2cb6cdf867caeb53539c1bb26.nq.gz
    ├── 23679b04b5d781f077674a8f4463b43e37677dc0.nq.gz
    ├── 2377d549ed78062fccb834f528c7090bfc665da1.nq.gz
    ├── 25666e29070d0a9db705486a36ec1a83a809b62d.nq.gz
    ├── 25bc963a90eca3aee302af66eb68ea46c6b83b34.nq.gz
    ├── 25cd6df27b74492cacabcfe36d7d80802ceec0e3.nq.gz
    ├── 26086fb2701b083a15ae0fa4f529ecc7ace2b497.nq.gz
    ├── 26d0007236d6e0a6d59f3c9c05d76ec06393e120.nq.gz
    ├── 26dc5676fc935754b0e64c2a693bb48388247f9f.nq.gz
    ├── 26f2d26334a60b6cc9fb0252c3847ebd0d136166.nq.gz
    ├── 274616e04c8c458c9f94d0116186a6ccf5925c05.nq.gz
    ├── 278908fc723b7a6f8e491f6de8c21eecc96d9d20.nq.gz
    ├── 279cd6736c27229ed9f910cd5ca54b1638cd5f59.nq.gz
    ├── 27a13823ef43c119b7789bef12b5d5bd93744f13.nq.gz
    ├── 27fd0861519328253bb949717e80b3c573660d05.nq.gz
    ├── 2811c4376f192e7e8b9637b01745326831cd7bbe.nq.gz
    ├── 288b371e427a7544faac948d46517194e7c2ae06.nq.gz
    ├── 28bbf78c3932f847d7cb47b03a1f0e5913d2d357.nq.gz
    ├── 29539b5ae4d92478bbe9d3cf91f47b34a1dfa753.nq.gz
    ├── 29b03634cf828865940fd392ca10303d13fdde6a.nq.gz
    ├── 29c118f6bd1031d73220196caffbb2110db8587d.nq.gz
    ├── 2ab21e75f8c18f27be4873e899963a2052fd2b9c.nq.gz
    ├── 2b25a1075c1713e9062ef8e8087cd8d98ca138af.nq.gz
    ├── 2ca391beac601c13d23411d858014c43a533c8c1.nq.gz
    ├── 2cb064ed098e78222761eeeae9e8df3c2ad646ce.nq.gz
    ├── 2f21f0dadafbc40d4e0f6ee421e67fc5152952a3.nq.gz
    ├── 2f7f9b695d502633060018556f8da7d10b04ab9f.nq.gz
    ├── 2f98d7390580885ffb9adaf796eaff8bd3d1a15b.nq.gz
    ├── 304911b934b327debb9ad6ca310f528e651f2b0f.nq.gz
    ├── 30b43526fdafcc051928e00edd4ca414946b7d32.nq.gz
    ├── 3175a87f44b946ef4ea857c503b989f32693dc4b.nq.gz
    ├── 31a371cde62a8d69a8923a582728875f89a1e0a1.nq.gz
    ├── 31adabcdc67e093c78e8e004ae899a6e0833426b.nq.gz
    ├── 31c5c952e0476a321d7f97f25c5e66c9cb3c6581.nq.gz
    ├── 325196fae4319a3fd9842ea8a78176b551d6c22a.nq.gz
    ├── 325c850028d43e446d89bc215520398922a1dfc1.nq.gz
    ├── 3285a96a2433176a22c11c2402116e5f7562218e.nq.gz
    ├── 32917f666d3e4baefefcc765b0147f5ee7864f30.nq.gz
    ├── 32963f17a897d3ac47cd024b4c008b83d39f7c22.nq.gz
    ├── 32a9aeafd1e6b654f4d108ff5dce7814f3b7d398.nq.gz
    ├── 32c07214c002df0b88cf901d040fdfd027a7ca0d.nq.gz
    ├── 34871796d3011276f2a67dfe0d36a7bb32de5d5b.nq.gz
    ├── 34badfdabf856c61ee65991c00be22bb1bc749a3.nq.gz
    ├── 34c584626617955341d37e2d5d381dd0d1b6f15c.nq.gz
    ├── 351f3df4f3a82239efaf42f0731200ea3be99d5b.nq.gz
    ├── 35565a363e47c4dda6a629a735dd721f500bc58c.nq.gz
    ├── 35d089860c07306cb8c912c67f60c5679b5d3094.nq.gz
    ├── 372dc40749b1fe97aeb7c6c5d58c1684b0540280.nq.gz
    ├── 376b8e2b869bb29c5ff7bd5225c63c3917dac6e2.nq.gz
    ├── 377b045fa1ebd5f2f29cc8a1925297922b90ec9b.nq.gz
    ├── 3785df1a0c34eaea6f0d454de1f5795f2464488d.nq.gz
    ├── 37a2441d8592862c7a5592df5ac50fc340162c72.nq.gz
    ├── 37e1c057ce3bfc04302a3a721110c163c9c02dd5.nq.gz
    ├── 37eedd779d25d4617665707a4299da5c38c8fe5e.nq.gz
    ├── 3866fab11a19a1a3915ddcf4541e60cc0c491232.nq.gz
    ├── 38ce63d9d4c516578793afc053aaa6463c9243d9.nq.gz
    ├── 395229d1f080ec36ac5766a5cf3f6124b68cce64.nq.gz
    ├── 3a2a7b3e048806b89efa69a8125becbde5030c12.nq.gz
    ├── 3a49db9034dbe91ea073245c6a840d0b5b0df5a8.nq.gz
    ├── 3b5afedcf580f72b4153e26cf50ad3731f68f344.nq.gz
    ├── 3b95f60868f97db6f31ce3d34f7a9d2d799cf4c6.nq.gz
    ├── 3bd53af1ac1511b7e14a90e1e525db74eb04f223.nq.gz
    ├── 3bd9c5c84de50a3cad195726b6fb26af398fecb1.nq.gz
    ├── 3be0cf35dbf392a2d6a02c47ba91311522e5db3b.nq.gz
    ├── 3bf07d67ace1fa649b8eb124622f1860706283b8.nq.gz
    ├── 3c05ab929d445f1da087f98c2cd7d41631788765.nq.gz
    ├── 3c6c45061e9f101408c1f75af001da3be8183229.nq.gz
    ├── 3c89d218c99f9377aa41188214290e2bcad7c499.nq.gz
    ├── 3cbeaaba4949ebba3162bc8d6d35b05bc828afa8.nq.gz
    ├── 3ce2f215826cfa1d331bc836277c3550743e864b.nq.gz
    ├── 3cf3b5c1f79abd818bc0dafbb6e0db91f5ed72dd.nq.gz
    ├── 3d06a1c869b2e5fbb0acc020c2537fd525bf78c5.nq.gz
    ├── 3d0d1e80b3d187454afe7a49aece9df9487407c9.nq.gz
    ├── 3d5acac84c06e5f49872be35c998378b7d743cde.nq.gz
    ├── 3de7044aaec279a926ea2064483fedd6da73b930.nq.gz
    ├── 3e3fdba3844b0ed5f5e847e575299e9cd74433a6.nq.gz
    ├── 3e5429d529212ec326c5e072c5f3c506aab5b65b.nq.gz
    ├── 3e72d839893185826dfdc9e9d6d8006a279db48d.nq.gz
    ├── 3eb5acd632a71b5167e92ba6d06c3ce05f08c182.nq.gz
    ├── 3ecd98dd6b2c56ae87d1fc873cdcf2d4ac52227a.nq.gz
    ├── 3f029018fbf2123fc5b12ce3222eb384f2bfecf5.nq.gz
    ├── 40772510887584051c8dc332aef673dedb9015f3.nq.gz
    └── 408e5310092cd011e6e25aaccaadf6b813971e67.nq.gz

10 directories, 200 files
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

[fastapi/typer](https://github.com/fastapi/typer)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
