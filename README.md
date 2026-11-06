# Repolex Knowledge Graph of larksuite/oapi-sdk-python

RDF knowledge graph data for [larksuite/oapi-sdk-python](https://github.com/larksuite/oapi-sdk-python), parsed by [repolex](https://repolex.ai).

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
rlex download larksuite/oapi-sdk-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d9749a4728446a0ffa2e8374b37b5e1ce1cfd9c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0d9749a4728446a0ffa2e8374b37b5e1ce1cfd9c
│           └── chunk-001.nq.gz
└── blob
    ├── 001159fd6b56b09d932a39c2d315986cc8d352a0.nq.gz
    ├── 018570f256a0d6f74bddf65c5bcb6cd0e71802c6.nq.gz
    ├── 0194635dadb8e907065e4cea54eda7bdf7dde755.nq.gz
    ├── 01acdc9865be36da94e74957f83c9b6caf8068cb.nq.gz
    ├── 01bdbca92b0503f61840d47b229d1fc37f2a9e76.nq.gz
    ├── 01e7a7a78a7a079e20dc86b7b186d0bf4d4f2155.nq.gz
    ├── 02bea30ec23c3fa5c000b3e3be3b97e7c48c2571.nq.gz
    ├── 032a0bea4e16c8167ab3a1db0ea4a517f1fb06ea.nq.gz
    ├── 03f22e61ab090aca79167da281aec710f1ba8f29.nq.gz
    ├── 045ada383f34576ed275cb6844393d2c972bd7e4.nq.gz
    ├── 046b41cefd2fe28a4012b1fb249bbae1f9286a6e.nq.gz
    ├── 04ae4d3fff192d3ae44cac7abf6b60a88bd1c2c0.nq.gz
    ├── 05a36140a6ff8628098d7ae3a9cb8d621d77bcf9.nq.gz
    ├── 064509f04a8ce076896016e32bb236fbf3e47ec3.nq.gz
    ├── 0699933b276c3ac323b970048625402b73f54844.nq.gz
    ├── 06ae1849d89977ae42fb9254a76dbbcde7f54304.nq.gz
    ├── 0704e92f5b79fa15b31780d051c0a7295e60e6c6.nq.gz
    ├── 08145ea04dd5620333b0a4448e7ce8e885b5cb4c.nq.gz
    ├── 0864d70665fde5bd6c1e959bffd90f7249ef7f79.nq.gz
    ├── 08ce6de67a694d941ad85229428c3b247ae0dc72.nq.gz
    ├── 08f143d8b3772a7f6c9b1648cde4c71c887b26b6.nq.gz
    ├── 09066428ab538d835125209e2d38517d9357a189.nq.gz
    ├── 091b90846fd7cb03a27c3c52bf694297cac0bf63.nq.gz
    ├── 0971b2253536d5f0b74cb1d2b04df5dcdab87eb6.nq.gz
    ├── 09c8fe7e0c1b916f7853624b9a354ff21978630d.nq.gz
    ├── 0abfdf897c8617f05f2b6d56f3f2babe3bfc3222.nq.gz
    ├── 0afc2205fd8ecf375c9c22a129ff4eb404eaa0d0.nq.gz
    ├── 0b3717fbd9ed2fbd6766dcdd7664e858b703c7e9.nq.gz
    ├── 0b4eb783d498a7da9cfc49a10c2f387bc703a363.nq.gz
    ├── 0b7160366be9d2116c905b9a3f4dfaa2fa27d934.nq.gz
    ├── 0ba32b654f2cae31ee93ea4c1f7322c403ab7da7.nq.gz
    ├── 0bf1ecb726825a923b44f6ebd79560855870ed2a.nq.gz
    ├── 0c671dee4ab8fbddba3575b92b0a6f86f37aaad1.nq.gz
    ├── 0c8be7ed4cba4eee6e048d6ce1759bd96d36f1e6.nq.gz
    ├── 0c9a789b1e6d3efe7b9d3970839b344ef9f3c22f.nq.gz
    ├── 0c9e7910d134a95429733a010fa660071843ac93.nq.gz
    ├── 0cb2a691ebf3b372bad41f1c205b855524eb4271.nq.gz
    ├── 0cc38543f04c20aa3f0551d5d2e7a8ccb45ce8a8.nq.gz
    ├── 0dd8250652b360b18af7b1d607ae609446028676.nq.gz
    ├── 0de6de238abab8a377e8ecbea1c059d416466a2b.nq.gz
    ├── 0e0be0ee810a7589066f97c7404557d5251f4699.nq.gz
    ├── 0e16f15b9eb06cee0a86cd06673dd09adeb935c1.nq.gz
    ├── 0e31491dffdb90e26c64f178bd7a81d7f487f86c.nq.gz
    ├── 0e8d33127a3ed3a833ccc390d2c99ef732e2e631.nq.gz
    ├── 0eedcd1094ec6dbd39b07441f17a96c1667e5f5a.nq.gz
    ├── 0f3c501fcfd0791586fa0235939ca7102a059b2b.nq.gz
    ├── 1010c569f41992051a1e3a2e2f7ac4c6448d2582.nq.gz
    ├── 10390f828122009d92b1d85e9abc62539ed31896.nq.gz
    ├── 10749effbd1b89194dc627add54b23a8671939d4.nq.gz
    ├── 112edebd35f1547c95306f591a780f57f0fb42af.nq.gz
    ├── 11f69623156261853bf69fe55820419b33931c0d.nq.gz
    ├── 125165b40e10598b09ec237852ab9dc520d931b8.nq.gz
    ├── 126590070bcb1c727d296d13226338d2fac74fb2.nq.gz
    ├── 12e5301ccd949e8941f99a2e3951e0c207289023.nq.gz
    ├── 12f1e559f1045b831ef0f138dfcc9c3feda8356e.nq.gz
    ├── 1301e4d371786c304bab728608d92c85b8be54ed.nq.gz
    ├── 1325c16e5fa714a97b3faff74e316ada96191d39.nq.gz
    ├── 13e77dda2b0124e8062e0d95b6dce42e12f06d91.nq.gz
    ├── 1412184aa9c36c8d8979b6936a0d6e84e0780189.nq.gz
    ├── 15b731d4e7b7a265211cd63fcfd97fee1ab71859.nq.gz
    ├── 162531226e5f8d0c98ecf6950bae6b46ec38155b.nq.gz
    ├── 169d8887074288e811c010ed6bf08aa50054a8ea.nq.gz
    ├── 16ffc9f89365aba46f36adca8755da863d067bae.nq.gz
    ├── 170fdbc532cd6deab472af20135af6d495f94e1a.nq.gz
    ├── 175c91d380197fffb804994a47cd4829f2668b05.nq.gz
    ├── 17d566459ad639bc30b13b575a416ee78fe9ede9.nq.gz
    ├── 185a398a76c9ac5f540fca1555b05f3f99242583.nq.gz
    ├── 1887f0ec1d03c9389cfc89a688bf1b2393eb98b5.nq.gz
    ├── 1951ce01bf321fff1321e8585ebde84a170743aa.nq.gz
    ├── 198d25dac9c0ad077c2b30a4cab8b46d656bf311.nq.gz
    ├── 19a564eafb4594227cf9f6d4d5a8ef97d1572387.nq.gz
    ├── 19fdd9dec303d967a5445445ba5a98a94232b9e6.nq.gz
    ├── 1b5b321e88ae065ce30d4f39e7a4186f975b394a.nq.gz
    ├── 1c8b798dc3aa6a3bc167abb6a6bc1d176de47464.nq.gz
    ├── 1cbb6dc38955b56e90ccfe2a9ebdcffc2976b1f6.nq.gz
    ├── 1d948b5fb92cc993b85818fb2b1983b08f8bc21b.nq.gz
    ├── 1d9a5a49c98df541d669e0b9269c76a180500f4c.nq.gz
    ├── 1e7d0231e5f1af3e0eabcbb0b46cf46fbe05cc0b.nq.gz
    ├── 1e895d2176fd65d45d1fbe289068d0ac1ade59ea.nq.gz
    ├── 1f38627c9b72c11532bb3bba6ab1790f709dcbf3.nq.gz
    ├── 1f61f3636e25052dc822dc228195202c5ae5f1b3.nq.gz
    ├── 1fac11c0ca4f1ccbb2f27f7fea001eaa7d65d0d8.nq.gz
    ├── 205520386ad32b1d646dc483bd792cb09c29612e.nq.gz
    ├── 21cb450b19f8ddbe24546b7ba44f20537aac2088.nq.gz
    ├── 222f76e5ef63c2932739014ebb10f64132443525.nq.gz
    ├── 2258944567da6e28f6e4004ad5489b370954e511.nq.gz
    ├── 228a22f4443bfaeae2bd79ce2839e85ec33055b0.nq.gz
    ├── 233a8c4633bf79b0d19b3f384711c6043651bf07.nq.gz
    ├── 238e1c2829f3e489b41bdda764a9743d594a5427.nq.gz
    ├── 239e864e5ea58afd1e38407be31f0d06482da16e.nq.gz
    ├── 23c867996e1eb9047d97eebb42fab9c00bcc522f.nq.gz
    ├── 240670a391a1d68632bcb1cd3454dfa5b3ab9738.nq.gz
    ├── 2466fae8b96deba129a88c2d576c6e8871b66560.nq.gz
    ├── 253ad03970b152c6963debf4b2ea1eee26e31685.nq.gz
    ├── 25bc62033dff40ead00c6c09029ed363e40790cb.nq.gz
    ├── 2715c79db3baf09226a3e01b36fd4877d4ce91dc.nq.gz
    ├── 27fa604479cf63fa1b9a63fd4097a8c3d1ddc2cc.nq.gz
    ├── 280a35ef86390b380b2549e4a9f7b2dd2c17a470.nq.gz
    ├── 288d02cf5c882a291012cc35fb6e6e4cc50c5f7b.nq.gz
    ├── 28ceaa7ab44b85d8f6c5a19cb7b044059104cc65.nq.gz
    ├── 2923c247dd43cadf0f6fc77f624b70024c3e4aae.nq.gz
    ├── 29380088d64e4b20ea87bd741d25dcf0ea969ab8.nq.gz
    ├── 2946c0239973bf2aef0dd72e25defbbd71f3fcb2.nq.gz
    ├── 29e22dbc1f325947e013e52280aaffe39966abd4.nq.gz
    ├── 2a1a41e3c3f08ed7756420f7f784fed5909d5051.nq.gz
    ├── 2a7ab5a2a4a0ba7d33edd31fcbeea22ef577a9af.nq.gz
    ├── 2a8b7db83fb4fc4148adf71ef87e147a590adb54.nq.gz
    ├── 2ac90e2a7db3653872d19deff62f38c277f7ccc1.nq.gz
    ├── 2aee28fa17581d32987b2dff452f6011b9afddba.nq.gz
    ├── 2af02d6fc504eaecc3df0fba5dcbc112982c16cd.nq.gz
    ├── 2afba534c6b0eae1a958fc659662ef40494cec32.nq.gz
    ├── 2b13f9402353effa5025102781933e48d56e4f14.nq.gz
    ├── 2bdab236f4174c4822dae4c791dd63c7d79ab234.nq.gz
    ├── 2c2d968c120d633b03310019505781a577c711a7.nq.gz
    ├── 2c9128d502700064cafd0f50a5178deda93bdf92.nq.gz
    ├── 2ca6ca7cb0acd2122318f532a2dda8ec6e4db650.nq.gz
    ├── 2cea61ab092212d44c8c3602b740c509e166b953.nq.gz
    ├── 2da4b552ffcdb19bbdf2e1fb66f27bc3d8dfc8da.nq.gz
    ├── 2ed75f37056e09ab3d6cf223dfb013733fc7b731.nq.gz
    ├── 2eefe2ac75c2f0c31329e2bb49920b5c7fa040d9.nq.gz
    ├── 3026c41366481b9429f90f462c0ce2869fb06030.nq.gz
    ├── 30c7fc9b8c7822204744bb0aff7e34c72f7d123a.nq.gz
    ├── 3126c609824ca2e0a83e565853c72ed2f54d1727.nq.gz
    ├── 314ba3cb4a6c7e63623f3a4386abb5d430aa6a4d.nq.gz
    ├── 315e783425a2fff6581d81788b2da8bffe2d0ed9.nq.gz
    ├── 3197ab019b8d7d63a7600ae90e72cbd9df628dc3.nq.gz
    ├── 32003d91c7748098c632f1508715ed3466c93100.nq.gz
    ├── 326cdf49b6dfb06f8837ed257780a306229cc633.nq.gz
    ├── 32810c6efa220c928fe538c306bc20e9c4998147.nq.gz
    ├── 329e216e7eec07a294db0d874f0c45a95b9a85ab.nq.gz
    ├── 32c8ff86d2187caf401f61f5e96848b44893a634.nq.gz
    ├── 3327fea6c22ad91257342349dc4d9641e8c51a1a.nq.gz
    ├── 337e694050733d210fb9077e80168394e79ed6b2.nq.gz
    ├── 3472eed33ed6fa60d42224bc6d36bb70ec8737e2.nq.gz
    ├── 34c3e3201a4efce147dea5ecb97d807f16c0ee47.nq.gz
    ├── 34d4138168409e6acdab216303356fa00208dab2.nq.gz
    ├── 355a2fea972e1db7c23c10ea9a515bea75b2c6e7.nq.gz
    ├── 355e8c2e5dd01e15af70eb2c582873557d2bd0fb.nq.gz
    ├── 35669002d2e6dda13cd8840d779d6326f6c0384e.nq.gz
    ├── 36bf0285570cdec592522dba2109742a023803ee.nq.gz
    ├── 3762c9ae39458ac6e8d06d894a70997b4ae94506.nq.gz
    ├── 37b2125dbfca40f76dfd8fe68cacc7d831be7865.nq.gz
    ├── 38f6d851c6b889f949c09e53b7374f61b55f471e.nq.gz
    ├── 39542b161ff0077af3d94f72b52cf1f928ef1380.nq.gz
    ├── 39a790b66756d5d3a8bb3484fbd6b3d96059df4b.nq.gz
    ├── 3a4fe2000e0eda4df188726df2f56e41a3ebedeb.nq.gz
    ├── 3a7449c2411bbdb00b3b3cf896b12ece4432ef7f.nq.gz
    ├── 3a81ffa21cf621de38d13b1f50aae16d518e4caa.nq.gz
    ├── 3b048574cf7592aaf75132436dfc647273aac99d.nq.gz
    ├── 3bab8669d15a2f4265df1166913be445e659bef4.nq.gz
    ├── 3be11dcbbc0aa52825fd7a9a7cc52a695051168d.nq.gz
    ├── 3cfa7623dde23f223c7096c6c123016a2274d54f.nq.gz
    ├── 3d0d6c6ef98bc935e7fdf3ad212bcda6b2b83034.nq.gz
    ├── 3d3852e4c45545d40fc66ddfedf1a526276cf63f.nq.gz
    ├── 3de432c6110260df9c75ef9f4f78da2b4db13e01.nq.gz
    ├── 3e3b3c4d5d9bb891f6e7d623e3c55b64e2c1abd0.nq.gz
    ├── 3eb70ee7a29576da6cf50b06c46083336e623c5b.nq.gz
    ├── 3fc53725bb3f8bcf5321271620fdc902117e788d.nq.gz
    ├── 3fe112ca89ea1ddb18518df992febdc97efc2bae.nq.gz
    ├── 402cafbb678897d62a18b183351f221625671684.nq.gz
    ├── 403590ba3b2ee9e64f5ae6fd68ba6c45391d040e.nq.gz
    ├── 40aa4c30440dbe04d505bebd3cc4bad383cb3646.nq.gz
    ├── 41672499b6a445f0d0ca50eaaaf5deea10a7be0c.nq.gz
    ├── 41fbc9820751af674bb94042dc28b6d7d19d9fe0.nq.gz
    ├── 4275c38236eac30b42615331d7f4644e08c69be1.nq.gz
    ├── 428aa18edf8d7ac4d9ee54202f7a7d4cc81c58ab.nq.gz
    ├── 42d4e8e2af950755eda449bd66292a352af4fc10.nq.gz
    ├── 430ad290e4845572c20eec15481774da6a689fa6.nq.gz
    ├── 439bc0099a0b4eb6de5b7bec1cf0af923f39bc04.nq.gz
    ├── 43d08c0f713548abf0ed5609b622057616512f65.nq.gz
    ├── 4452cbaee317aa22b83f6ee471dd84610152bf90.nq.gz
    ├── 448bb8fad22f237f53cc65e25ba343cada679db7.nq.gz
    ├── 477bb0334f0a683e9451c23f58653803ac36ce11.nq.gz
    ├── 47ab117d86c6c32ce85a76608e512c5ccc6ca978.nq.gz
    ├── 48415f8358d32cb70fc48884397973ced0b924b8.nq.gz
    ├── 490e3089b868f298490af0f381d755db60413f63.nq.gz
    ├── 499a5e74786932f0e22b4e106df341c09121e42e.nq.gz
    ├── 49af88d1eb78f705e72d3a78754665c1bc55e0ba.nq.gz
    ├── 49b3766dea10f166378cd7491b91a7c77d231584.nq.gz
    ├── 4ac1c0ffec011a0b5fea1879b73ecb7ee2905407.nq.gz
    ├── 4b7fd80b75c82ae2b3e8586ab64ccf9450cb13e9.nq.gz
    ├── 4bafe36ca9897b5feab895b2870cb15c2c25aded.nq.gz
    ├── 4bb4e8e905c40e3e79f16df06fc4ca2fa347c6f1.nq.gz
    ├── 4c91dad14f0925bc1c0fd737db9b8a0f12dcb538.nq.gz
    ├── 4ca44d1ed2855d069ff59bba5c666470542e5b4c.nq.gz
    ├── 4dc4f4cf67c4ed8926266a728494d70dc5ab4808.nq.gz
    ├── 4e231d113b6b47bae166399625c35b0ba52ab835.nq.gz
    ├── 4ec49fe690208c0e213d73faf9a1790a42bfe076.nq.gz
    ├── 50d7dcb944bb367c3e912ebd25823d8197a73338.nq.gz
    ├── 511ebb78fc0b57adc70f55270b88260433ad3672.nq.gz
    ├── 5155689075f0936e9a8205bbb431f876b2619f51.nq.gz
    ├── 5165ec0a360744e9edeb84f86dcfc3bd90ef6036.nq.gz
    ├── 521357f1202e8aa57dc3498a06edc732b06e875e.nq.gz
    ├── 5242c50b3a0c07b62d98db0b32f075296dceb19a.nq.gz
    ├── 529b4d3f688cab9423898cbe0550bfda0c8fa707.nq.gz
    ├── 52aa9088aded6f190903430040306a7d3c9ce1dd.nq.gz
    ├── 55462e7f168d2371e8c44c26d8b6b4148f709470.nq.gz
    └── 55ddb8c6be2c541d83118ee6b8a6347141db2cfa.nq.gz

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

[larksuite/oapi-sdk-python](https://github.com/larksuite/oapi-sdk-python)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
