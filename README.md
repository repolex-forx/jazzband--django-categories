# Repolex Knowledge Graph of jazzband/django-categories

RDF knowledge graph data for [jazzband/django-categories](https://github.com/jazzband/django-categories), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-categories
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3964ba4b78ad1cf3ad542ccfc509c33bc969c986
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3964ba4b78ad1cf3ad542ccfc509c33bc969c986
│           └── chunk-001.nq.gz
├── blob
│   ├── 02b08522c9c77d2e72fbe4b9f4a564c6d8d95178.nq.gz
│   ├── 043d49b4e6e7638b2d583f35cf4842f01001a45b.nq.gz
│   ├── 07421f1251f4d6f036d6a5c1262854d0f7b83ebc.nq.gz
│   ├── 0d71e2295e11e42e1cdf31981a9d1fd08d5b23f5.nq.gz
│   ├── 1320bd284375893c55cb01403b6bfb0f7e25aa88.nq.gz
│   ├── 13d84e25d1415c8938787436ccb3b76352249e09.nq.gz
│   ├── 195f6b9c2ee719bb7e81fbc5b82e7aa5400c20aa.nq.gz
│   ├── 19c9ddec1a0b765d4f7728ed1a6c6c6edb908f1b.nq.gz
│   ├── 1be7e62eb2d0ec6f027477868fece86f6fb07a91.nq.gz
│   ├── 1c57cd7c68c26e22440d7c2b395487b721138069.nq.gz
│   ├── 1cb253a10cd55c01b7a5f7bd9d9978b8516aefa4.nq.gz
│   ├── 1cf4e4ff5fd562c19665d8b2dad402d481a23c43.nq.gz
│   ├── 1cff18a6e9140b003487964d568c7ca3a7995906.nq.gz
│   ├── 211955da05477ff0fbb006555c6f976daf530490.nq.gz
│   ├── 22be8a7ae0eb0b3dd7b501a0c444ad5a8dd56606.nq.gz
│   ├── 22fd550d236e8b66f84c300490d8dd1a5b8c9435.nq.gz
│   ├── 25f77d231bb51e7524c6f865e811758c849f2199.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26665e4590496ac38ba3d1007a208f39bf4ea579.nq.gz
│   ├── 26828b6b37dd8e97ec1ae716795deae01ccd762d.nq.gz
│   ├── 27b52344dcdfe9b55cde5f3a95883c2d905636aa.nq.gz
│   ├── 27babd995c8fc8e63ba0c7f5a76409ce5a941509.nq.gz
│   ├── 2948063637e4228ceec62e81adb569055611252b.nq.gz
│   ├── 2abf52bf59abbe9a73971519ff9039b8606bee58.nq.gz
│   ├── 2ec544435be37459f55d1510636818190adad01a.nq.gz
│   ├── 32f3f2d478d9c54ffdb59205b35baee9435af9e8.nq.gz
│   ├── 387aa728cf00c1b57fc1aa923097c4e82af07c43.nq.gz
│   ├── 3a8d8bd6ff81ef510d854d05e91eab1024b59c58.nq.gz
│   ├── 3b3cdcf7118da7b62b89788beb669122e458b0d1.nq.gz
│   ├── 3c2a5b5fefeddb5ffb0c22114baf6113100513af.nq.gz
│   ├── 3f23d06452b37c9fd29231d42390252b49a19407.nq.gz
│   ├── 412bdaf4f1820179872f60e7711ac7abb044cfea.nq.gz
│   ├── 43d0f3dfeb7df5c5f61ed451f8dc7b87901f8cb0.nq.gz
│   ├── 481867230f0a30bda06741a02e96f28a2901c4f8.nq.gz
│   ├── 484a7072d9b27b83df98841d9e76cc85a7a59677.nq.gz
│   ├── 4885628365ac865fc413e44a540d35741e4392f7.nq.gz
│   ├── 4ca0fe0e4fb52343e157c0659ff5c2c73d441983.nq.gz
│   ├── 4f858b5a727be3b3aa850007fd75889cc1897ad1.nq.gz
│   ├── 53a9c3a2c6d7867a1bc2c303b4420c2284ada526.nq.gz
│   ├── 55940b0db194f85a721a84b4cfc1e625525b71b7.nq.gz
│   ├── 585e2abce090bed5b190007575955a0d3f862b74.nq.gz
│   ├── 59a7390a4d96de169e4bc03a56e9e38ebdccb798.nq.gz
│   ├── 5ab36e3afaed237e7ae19d57c53ebd137050d803.nq.gz
│   ├── 5c830b42a5376a48886ec20bc58aa24521924a6b.nq.gz
│   ├── 5eaadb8e90aeabf2ad66a087d33b710ae58b5686.nq.gz
│   ├── 65fb511111595d279e6f82211736df127219d8b2.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 67fd19bfeba5585055dccdd60818481ef52c9c92.nq.gz
│   ├── 68a437e10ce18bf85e44b9c7b986eff7a759e235.nq.gz
│   ├── 6c353a783d747e96888d158f59a6f31b6436ea23.nq.gz
│   ├── 6c9275ff53e4979da0ae2baa499cb58206916ad9.nq.gz
│   ├── 6ec70411c81a6ff08b51e09992f571fba34748b1.nq.gz
│   ├── 720074ca799ac669080a3fb4140d357864644317.nq.gz
│   ├── 74c3fdecd228f43fa41eff13e5642f83827d0caf.nq.gz
│   ├── 76577a57a23105b4c821b851902cda145e348d9c.nq.gz
│   ├── 767c6b1782cc517f1bb3bd19b7e53c904805bafb.nq.gz
│   ├── 797d52cfb8f914c2da8ba2a9059538d39baeb87b.nq.gz
│   ├── 7c75b9abd7c2efccb6f561e4d7267a721623390e.nq.gz
│   ├── 7da03f5d13f489d2f3cad3283058dab874142c1e.nq.gz
│   ├── 7f95b37c27d2502352bc984492b09a8137281cc6.nq.gz
│   ├── 8081eb8d27dab15b12b378f5ca3d50f7e1a68d37.nq.gz
│   ├── 825c65e614960aa6b78706c62545586b4ea0302e.nq.gz
│   ├── 83e9779c15f7a5fcee3380b2ebc00d7173ff9bc5.nq.gz
│   ├── 85852b5c234ce41d68115267ac1ec55e7c6af573.nq.gz
│   ├── 877d86ea42d5b3f588e9a6b80200112674304121.nq.gz
│   ├── 8a89169c2115cdb0750abb393f635c857d201673.nq.gz
│   ├── 8c35c95725c89cf9bb711db1684a0a1b48eaa1cf.nq.gz
│   ├── 8ca03c62746294f197af4504b00a9815db35fdb7.nq.gz
│   ├── 8ded421c3206c2bfbe9e24adcf6730429c9b2206.nq.gz
│   ├── 90e3521db025a778d779cefa8fc27b1daad2e5e6.nq.gz
│   ├── 9125774c565f30f0af7a84f75475047352c2a6df.nq.gz
│   ├── 91341adde493a21ddb0ee4926e03f62b3427ad69.nq.gz
│   ├── 9161fb4ac59b0b0bf763c9596e24a636f72b7dbe.nq.gz
│   ├── 918d8c9a680d1429257c35e2b48083f547ff1b77.nq.gz
│   ├── 9356e05b6083b2ebe7cdf34af693bc943274c729.nq.gz
│   ├── 97be142b454707c2df51ceabf8db3fa30e9d5c78.nq.gz
│   ├── 9bca020c4b8a5cabec2d4c1aa157a9f1a760fa1f.nq.gz
│   ├── 9cf93798ef68d476762cce69dc65e47afd073c60.nq.gz
│   ├── 9e4b8768e9e9c5d3dd289d672cf4f16dfe668cc9.nq.gz
│   ├── 9e63168c5c7bf4f92d6fb8225e1420cf8f1ae1d4.nq.gz
│   ├── 9f846fd4384c6ef9b3674c58d8c0375e37bc5346.nq.gz
│   ├── a11230060418b5014d2382c6d2d6a0856eca3d99.nq.gz
│   ├── a1afeed10911d90a71843934ac57a92f1a3fc40e.nq.gz
│   ├── a2524f9cf4ebee4181b4f489ac9004500c91815a.nq.gz
│   ├── a9f271858c3bc762b83ff626f7304706867b5cf0.nq.gz
│   ├── abc606cfce723e250c70b17f51cce35001b155e5.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── aed1611cdcba68ae79a4ebb9a309eff0606e74d8.nq.gz
│   ├── aee7b352d14cd78d142567fa9eb9e1178e75c238.nq.gz
│   ├── b2bb0b3e9d6c7e9a96b7516a00f7f5ec4ddd10a1.nq.gz
│   ├── b40709b6726e4a37433ffa32baec5bd574c8253d.nq.gz
│   ├── b5312781dcb1a2da1c40869d6313d4a3c0410ef0.nq.gz
│   ├── b8e3b0744699df89fe6819d964fed88376ab7bd8.nq.gz
│   ├── b94c8423615d373f13ecbfe3cb72a60be9452ede.nq.gz
│   ├── bd605bd25628894df5a79ab7496974524f442373.nq.gz
│   ├── bdd7c4e295585de87ba63cf760653f285984398d.nq.gz
│   ├── c1b6e64d8c72ce9b3b39c19d08cc52647fe85604.nq.gz
│   ├── c9c07d81c95479cd00a0efa8ccd4ae888de551f1.nq.gz
│   ├── cfb42a451247095be68232ab38f75842893ce407.nq.gz
│   ├── d0afb827420749c49c52c0154493e46df4efb7f2.nq.gz
│   ├── d2248e3eb2e0a4f4b8080df29ef7575dd0175ece.nq.gz
│   ├── d443fff92730f947fa3b1eda2e1217200cb4e7fd.nq.gz
│   ├── d54092aa1071c28a9c40e685b79ef4783f9a0616.nq.gz
│   ├── d664d28b08cd938bd8f29e033b97b3d0d35b13b0.nq.gz
│   ├── d7e512c034951fb86bb8f7b47550ab948ea7bd7c.nq.gz
│   ├── d881cde0837540f259b103f9a0df3874271ff41b.nq.gz
│   ├── dc4545ed53e7498850223b2f4145c538c7129148.nq.gz
│   ├── dd3d786739d8dc83b0dd7c399990722784776e8e.nq.gz
│   ├── e2cab653e1cc079e79ad829c8ce8700f3e6fc822.nq.gz
│   ├── e2f48d4066f2c482c3a123e3f0068360b93be7ca.nq.gz
│   ├── e422573035ba48253260bac7147e4022d4d3bb54.nq.gz
│   ├── e44f6522c0c265d3498ce525ebd19f21072035da.nq.gz
│   ├── e4f3ef60f5601a60eba9de5f3cb4f1bcc50fed82.nq.gz
│   ├── e6535cf7ee31f80778ec259b2eca3857ae7fa5ff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a4d64f35bde87b258be2b9da84bbe0860c4ce8.nq.gz
│   ├── e985bda2473f1bf47d7885ae68733bd7a70774eb.nq.gz
│   ├── ea2a88b7b6bfd9da72755ca26784d58a1a492bad.nq.gz
│   ├── eb10fd5353f8b4f8715f3e81f1c6d71dace17cef.nq.gz
│   ├── ecfb5a059ccfeb9d6d275abde008110aee76e987.nq.gz
│   ├── ed1612fd9b7f76f56dede10ce96cacbbfc0699d8.nq.gz
│   ├── f00d4ccef8ea3bb1792abec88b5bc1aae80168a9.nq.gz
│   ├── f024960d7cc7017236f2aa7d268f7c4c30d60ad4.nq.gz
│   ├── f4ce71e3bb404c90ed2091f1c6eec8d71f1767ba.nq.gz
│   ├── f51d798ffde4c28d8c8d5b87a83878b0cfe37b41.nq.gz
│   ├── f537742ce687d983ba348d02b9d23a75b855c2eb.nq.gz
│   ├── f985356eeb0f7fa7eb6d19a67388cd8a38b09629.nq.gz
│   ├── fb2a37e3431951b68042688a6a5ff3b89b6ec124.nq.gz
│   ├── fb4062b987ff91512264879b54e080a509e6342a.nq.gz
│   └── fb5557bfd7952e94c872eb3e0c230941f7591a8a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3964ba4b78ad1cf3ad542ccfc509c33bc969c986.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 138 files
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

[jazzband/django-categories](https://github.com/jazzband/django-categories)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
