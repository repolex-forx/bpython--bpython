# Repolex Knowledge Graph of bpython/bpython

RDF knowledge graph data for [bpython/bpython](https://github.com/bpython/bpython), parsed by [repolex](https://repolex.ai).

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
rlex download bpython/bpython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a21ac03d0474321ef6a760ecbf754352829bdb0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a21ac03d0474321ef6a760ecbf754352829bdb0
│           └── chunk-001.nq.gz
├── blob
│   ├── 017978277571c52091cabfa9efa043e31f012e69.nq.gz
│   ├── 03127f1b20c6acd4ffaf75958ffcc04c5583f35a.nq.gz
│   ├── 051e5b6913794c0705b28192a1182e4aa9d6da89.nq.gz
│   ├── 069f346535d41a36e9925db59a9a409f6a71f838.nq.gz
│   ├── 0745e3bfaa3c24c95ec4bc1fcfc0eb60822a0da4.nq.gz
│   ├── 0d8d16d6a2f1b86197d4e040cd331ecebc3d3d62.nq.gz
│   ├── 122f1ee9f856925e4d37f40ffbfc669a0ac64ce9.nq.gz
│   ├── 14169d6a8da7b7e296386ae0662e818c07288683.nq.gz
│   ├── 1521542ed54b3cd72a3c6d19e4681e215f45b451.nq.gz
│   ├── 17b178de6dccab869472d6f2c4ae24ffc956c4c1.nq.gz
│   ├── 1f559e15fe8c73f423b287d1edf58f31383bee35.nq.gz
│   ├── 230128c96dfc01cd6bfc0308ef47881edd118dd7.nq.gz
│   ├── 23e8798cc01b714a8d942166252b9681c29c01a2.nq.gz
│   ├── 243196d2f3491630823873467ec152c04caa6de2.nq.gz
│   ├── 276ef0be01a96780c06a5c0aab27c6f266127405.nq.gz
│   ├── 27852e837bf35e20ddfecdd001d13bd72e49042a.nq.gz
│   ├── 29e651cab9d7dea2ca48abe2f12e4179c3e6d665.nq.gz
│   ├── 2e99c90080ee6274ec51bf882185205ed2045774.nq.gz
│   ├── 2ef9004985cfee86eff4136248de49cf732a1544.nq.gz
│   ├── 30e911021faf1e55dfdc61a4377a3ba60c26e587.nq.gz
│   ├── 34dd4fb54810c13140b654930a39cb3c7064038e.nq.gz
│   ├── 36f233ebc1a0c8bd6fff1053e803b213298ae8a0.nq.gz
│   ├── 375f4f32e60d98a037484140b2c5431f20e9bfa8.nq.gz
│   ├── 38469541aaa8a28ad24d8f587a8bc344927deac4.nq.gz
│   ├── 38a233624f6ca90bdb5e394281739f1a04ce90cc.nq.gz
│   ├── 3968c20a62a125c26a3f807adb88e1ac77aa28db.nq.gz
│   ├── 39d4932724fd6d244be05bd46fb6ebddc3e58522.nq.gz
│   ├── 3b63ca4c9c724057840c0d2c4534db444ea21fd8.nq.gz
│   ├── 3b93089dfa91a55ad48127e5c224dbae1d253919.nq.gz
│   ├── 3d02c024aa01af5aedae01163ad5e937f076e7d1.nq.gz
│   ├── 3d1bd372f078a2c1468cf6b061cbd647dddba258.nq.gz
│   ├── 3d40d198c45c0b6f9b622fb2033e21301ea6cc4e.nq.gz
│   ├── 40efff3e6ac321e9665bdb216134386b008d4498.nq.gz
│   ├── 444ffbd3378950ebcdb6dd42b48d8b8a05017574.nq.gz
│   ├── 445e78b30e7750cfb9e2c94f2bbd0bad49ee67f0.nq.gz
│   ├── 448d9dc6ae84471fab930da3716a1aac7476ca29.nq.gz
│   ├── 4618eca4d360af9ff630ba4b99ec0d790c51153d.nq.gz
│   ├── 46488bc3ceef807ad54cd75f76eac1b1096a6ba3.nq.gz
│   ├── 46f642f27eac24051e3e15188ee0a6cd776ad60d.nq.gz
│   ├── 4830595be07f2bb7fd76b4f3be7541350d93d0d2.nq.gz
│   ├── 4f9c13e55112168b82076bea23afbb69d4258bee.nq.gz
│   ├── 4fd107b6126926e3c321fccc265643bc1c726e49.nq.gz
│   ├── 51f4c01177691ef59580f534b3c09273a60359ed.nq.gz
│   ├── 5374f70fbafe0d60d98e48f7e962d4eae0a5fd32.nq.gz
│   ├── 59102f9e1a6cf8cd7639137166c29f2a4b0f6be0.nq.gz
│   ├── 5cbd26503184ad5d53530635ed3ab93df94d0066.nq.gz
│   ├── 67b29f9439a1c23bd29f657c768ebf52ad48bc9c.nq.gz
│   ├── 6e911590edd1bae39907a6fde35511d3916ea4be.nq.gz
│   ├── 72572b0b1c8573582b08a15dbd1161d1248c6b70.nq.gz
│   ├── 77887ef4b6a4aa4df25cc14d83692fd9e0489735.nq.gz
│   ├── 778c827efa977d093f4e5b5e724cd2c644a8539e.nq.gz
│   ├── 78b35684d016f8b1e87f5b34a6b063fc0de993f4.nq.gz
│   ├── 7a81cbfe282b37854ef64841e253616fae97a876.nq.gz
│   ├── 7d789f166ae175603bdbd0caaf54123b46b25470.nq.gz
│   ├── 7d7bd28e0e6367edf6c7d1c905e69e544bb2f347.nq.gz
│   ├── 814d3c3121842b8e5d2f8facdbe4d397cd033468.nq.gz
│   ├── 83a75f09e1fa33126878e7551ee9d08bf2991500.nq.gz
│   ├── 8496f0dd65cf076b23c45c396d462ba0ec78df7c.nq.gz
│   ├── 86773609f2eced48bb74e48bfae9b4a22f3606f1.nq.gz
│   ├── 8a088ad737ee152af231cacb4d0a2e2c0c7710c2.nq.gz
│   ├── 8bdb192963d13edb76f205eeb665c00f9728c223.nq.gz
│   ├── 8c139c7bec29cd1fd808ae643e5b9181813f32b8.nq.gz
│   ├── 8e74ac2c2b743252eb342e18bd132d7113e7d2d0.nq.gz
│   ├── 8e8a36304fd8bca50b6b4ee26ef84774f5c83edb.nq.gz
│   ├── 911bbc4f6a9dcc9cd4ea8b084e06ace654cd98f8.nq.gz
│   ├── 9237869daa68147048fa8fec58386440bbf35964.nq.gz
│   ├── 928be253ec9ecbb0871ec4f9b684115b50a5da45.nq.gz
│   ├── 9382db6bc500b1ca27e1188b509fff42ba35e024.nq.gz
│   ├── 93ce5cbc297eb341913dc75472bcb6198fbf16a9.nq.gz
│   ├── 96626c16c2bf77511f91cb84365a953b0acd65ed.nq.gz
│   ├── 9693dadf7022f5541bcd4e2d37aa61706c11546b.nq.gz
│   ├── 9ce932d38f5e13a84194d6b226d6c0718442ef62.nq.gz
│   ├── 9f944ee66e976973a41214a05d3b18c63d4cd6fb.nq.gz
│   ├── a19293daa43e0e317d9394b9e8a62ffd09a6baad.nq.gz
│   ├── a32ef90e801630190022071c92913806b68f8327.nq.gz
│   ├── a74dc34547d183c308c48a461a4c25b384a8f164.nq.gz
│   ├── a91ef6317dcc3f3da0c2c4eebec0c99837a6f4bc.nq.gz
│   ├── ac78267a97e7610479e5c8c28b4f30bba35c1caf.nq.gz
│   ├── ae48a600724139cae29e43b9a9a1f7f2abb2e164.nq.gz
│   ├── af1e3cab79cf7963d5f716b738271f62c2291d45.nq.gz
│   ├── af9370d6c74add0e3c69c88800cab31be6c9b2cc.nq.gz
│   ├── b9778c97a37d27d36f872902216227d70d3c3bf3.nq.gz
│   ├── ba1205048b6f64d8187a6c9feca43b957b660f81.nq.gz
│   ├── bb5cec423ff376535425f8dba0b38d24fd7a2d47.nq.gz
│   ├── bbc871ada617ac31efc99d9d39f6a623c3dc9427.nq.gz
│   ├── bf09896eb734f57554ca7ed88cac59e1f532e687.nq.gz
│   ├── bfcfce46f7985c819ac8580906c19af02ca61f56.nq.gz
│   ├── c106c4155ef90a511f9cfecfbee12eca8b51422f.nq.gz
│   ├── c309403fdf3e2c1cf09b81b34395365eb7fd04a0.nq.gz
│   ├── c34f2dac623aa9d9d839ae031226ee5ca20a47c4.nq.gz
│   ├── c4596f2d9335acdf590b773e062ebb871faa6391.nq.gz
│   ├── c7c87aed6946f5f1f07fbaff231061d9f6386430.nq.gz
│   ├── c9535c4a8db5189c0ada91496518eb2a19028d6e.nq.gz
│   ├── cc8fbff842d69e32afbf1ad7c45081c43ac2e9b0.nq.gz
│   ├── d28912bccc33b94e99eb0dca3bbdde9fa6547310.nq.gz
│   ├── d348728161a7b54db48a67b24a6d8764809f093e.nq.gz
│   ├── d3e2d5e567243d47c138a6b3c602bf28a7d8d163.nq.gz
│   ├── d475229e05db6f98270cc3d50616827a6bf6f1f2.nq.gz
│   ├── d4899332d168a55a2f3013e91fb28d2107d53814.nq.gz
│   ├── d644c16dd24962ba66eb5f8d3c9d247c748dccd9.nq.gz
│   ├── d810cf6be3ea9b095f9e30fba99528494bd942cf.nq.gz
│   ├── d9caeab014a5e0708918ae98b8207589341894d5.nq.gz
│   ├── da32fbb8c7aa17c6860eba99da5ad6246142d8aa.nq.gz
│   ├── db7d63e03d7d36f28322976962e7a2b0721b2a29.nq.gz
│   ├── dd307d33b1c6d4b172562f40062625bfae36c1b8.nq.gz
│   ├── de10eaf44dfb3c8de78492fcfca4a1e1155fd3bb.nq.gz
│   ├── ded1fe942a4bb339ed721f70626f2efb6abb96ff.nq.gz
│   ├── e17199211812e7d155e4976849f90abd3d206dc0.nq.gz
│   ├── e22b61f62a8ecd0740c43489a8f872ec35002739.nq.gz
│   ├── e282f189061bf4edde38b5ccabcae414f5a49bae.nq.gz
│   ├── e43ce2f22f569a5f9bdfa31bf179822a8696d14c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb5d7f2fb0280216871381906dde0497260a2996.nq.gz
│   ├── eca01713983c585608b46422eadd8b484a218fb2.nq.gz
│   ├── ede87460da68512310de5e9719ef9457084a71a7.nq.gz
│   ├── f059fab88b150efeabb6ed7513a70eba1f412440.nq.gz
│   ├── f209d2971dc98365de6001cccd5931c1482e68d6.nq.gz
│   ├── f48a79bf7b0d32b3c9ac22de4c98230fa8b86023.nq.gz
│   ├── fdb9dcad4c76804b0527334b51938dc6e5c50184.nq.gz
│   ├── fde2b10370c78b2bdfcdbbd1a499d163329ef811.nq.gz
│   ├── fe37a25fed3c940f1a06602a01fc836abc40c5c2.nq.gz
│   └── feb534f7f39fef0dbe3af757147a8d97a920d0fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4a21ac03d0474321ef6a760ecbf754352829bdb0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 130 files
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

[bpython/bpython](https://github.com/bpython/bpython)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
