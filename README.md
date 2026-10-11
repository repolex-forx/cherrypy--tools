# Repolex Knowledge Graph of cherrypy/tools

RDF knowledge graph data for [cherrypy/tools](https://github.com/cherrypy/tools), parsed by [repolex](https://repolex.ai).

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
rlex download cherrypy/tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1b4e9438e9558d8001f6fbe3dc2fadbb4fe74f15
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1b4e9438e9558d8001f6fbe3dc2fadbb4fe74f15
│           └── chunk-001.nq.gz
├── blob
│   ├── 024a72f83fe41214b541ba8ad49e697bfe7eeea4.nq.gz
│   ├── 02683007c07c7f16ad237ea4246f6d83409d1207.nq.gz
│   ├── 057513c741bc476152bb7f5922ada97bfb2442ef.nq.gz
│   ├── 061dcc3323560edb7ebaa7ef64e1382f5aa35631.nq.gz
│   ├── 07bb65a7e7222541c1a101fd82c63e64bf7b3854.nq.gz
│   ├── 07ca634b64d9d163c8522213b33e4906d253df94.nq.gz
│   ├── 084f231b2ab01988cb3e25966a5f361ef696f85a.nq.gz
│   ├── 0ae312968405338d16b6d2a290ef992f4859ecf0.nq.gz
│   ├── 0c5661da5edb35a094f1dcb81e46fb2215dd7fcf.nq.gz
│   ├── 0e51111903294626b54e1202a9c1d6b21c45e60e.nq.gz
│   ├── 142b49bbb2a2363173154092984b9b9f17450b64.nq.gz
│   ├── 17219e35dc8fa542ca387845fc365f4ce8f9a800.nq.gz
│   ├── 18d73c4558d2176cb97595beea60863ae3fd7845.nq.gz
│   ├── 19741d262ed5a6378f14b12bfba9ec253a565b3d.nq.gz
│   ├── 1cdfe132b32a2680801540bc05efffd6e6758359.nq.gz
│   ├── 225da2195b837da22f31bce8376da9b8cdb4eb06.nq.gz
│   ├── 276b528e10731730b86d9692dcc05871e1da7b4e.nq.gz
│   ├── 2903e99a9024d59ffe5a8bf50d6d68f02a5e3ce0.nq.gz
│   ├── 2c445dc1be72e05ac86db616e950e31958d43cf4.nq.gz
│   ├── 2e2a7a4f4ae44a420d4f385381c940d092205904.nq.gz
│   ├── 2f3b548d5a517b74c35210069ca98d96d7476ffd.nq.gz
│   ├── 329d257e7370bc475c786d328c9687b6dbe1016d.nq.gz
│   ├── 3382a4db5a3eeb2d018ea702c24a0924edfd87da.nq.gz
│   ├── 351c9623d196da2a0f6b181430fe55fbfc40df88.nq.gz
│   ├── 363248b30d2c62385e4dce07d47eda4498f91a1f.nq.gz
│   ├── 3ac9a0f1a56fc533832a4a43c90baff7c20fb15b.nq.gz
│   ├── 3b37e1599cb4383c82216a2a1c4740742b784526.nq.gz
│   ├── 3f2b6fd734c12fce53fd97664b38eb53c0b5c158.nq.gz
│   ├── 3f4dad3503c621131988a5e8967bad4cc64b1ac5.nq.gz
│   ├── 4344992186b1b0d463dc02e6c98d56e641715f0a.nq.gz
│   ├── 43dd3a256f943c463161edc44623119398e197c5.nq.gz
│   ├── 46bf270c74b369d2aacd0e288fe1254e0bceb0ee.nq.gz
│   ├── 4c87edbe2092d7e071aa42a0b0a9a9fc9a910602.nq.gz
│   ├── 4fdf97b67e8423708f13851e3e1f76fab89cce3e.nq.gz
│   ├── 5400badeba3336e5e9fb650fad1c218997e45936.nq.gz
│   ├── 56df9831c3cfa94e4feaf173548940377d0b6c7f.nq.gz
│   ├── 63da312949ee2941f0587f69e1715eab741dadbb.nq.gz
│   ├── 6c37010b2e5237d8a09c7dc10af9e6473da7dc58.nq.gz
│   ├── 6ecb8fdab35425fe42262aa5721c37f0b9521329.nq.gz
│   ├── 7a5517d0a5146860c9a8612007b19cba8d00f4bf.nq.gz
│   ├── 80e263bdabe019a8aa030cb492d7aaae1cd2b220.nq.gz
│   ├── 82424c677d912ec20debed03530484071cffe959.nq.gz
│   ├── 832e4972d27ff2c6bc333b5fd7cdd3d1569fc288.nq.gz
│   ├── 835d0149b1ba05ecf70782254907f0d5133a1085.nq.gz
│   ├── 838f17b90bb6e48d83f7ab0755414b6fc3f0f529.nq.gz
│   ├── 8498a3c02a3cbeaaf1f89c6f3d93f64b596baa2f.nq.gz
│   ├── 865af858330f080c3855481de2aa311d3571385a.nq.gz
│   ├── 8664aeb336a11e67d18c0f4f823bd9c904d30458.nq.gz
│   ├── 87c1db9b26779936ce56342c6ca624f7164524e7.nq.gz
│   ├── 89c701505f4be940f574a0a11b19c697a3c7f9d9.nq.gz
│   ├── 8acf990b1c861650726d32be9101bd588a8e4d6b.nq.gz
│   ├── 8bd8bab2365345f414e86d8220a25da2c45bacec.nq.gz
│   ├── 8d6b29a963ea430e8a21e5f485cfb025f00f191f.nq.gz
│   ├── 9119093a8f137a5c8055966895b2fe1e632859fe.nq.gz
│   ├── 92defebd3deae70f25ec1e717c166aa91371c172.nq.gz
│   ├── 966795758c7f0fa848dd51d8761588f1d42cd5db.nq.gz
│   ├── 96dd1b3ced03a7af4e09e77ef0f5c782f4e6e055.nq.gz
│   ├── 99c6453482785691ca1c4a90f02656295ae7ce8a.nq.gz
│   ├── 9bb8060ae13a026864beea62e234872dbd4440e6.nq.gz
│   ├── 9ff0c81241fdac2c9a416ff4be001d4a8bb5c268.nq.gz
│   ├── a2c67fecb023cdb33dcbdf7f3b526a6e8c65f76d.nq.gz
│   ├── a482bdfd0438875560f26b5218bbc78680d5ecfe.nq.gz
│   ├── a7088b9901eed7e39e912d3cc484a05a10c566f0.nq.gz
│   ├── abc805efdbfeaea0ed03977748a974c92843182c.nq.gz
│   ├── b14864cff3dea1f38cba477efeb278d0a7981f2e.nq.gz
│   ├── b623df963976d9a2a442a7ded4f7b663fb09b411.nq.gz
│   ├── b6493865d157667c9ab8d5d0abc83dab9d8ad564.nq.gz
│   ├── b7190a7f0f02de379900424921b22b8fdd23e2bc.nq.gz
│   ├── b97b74557b01eade744cf24026b22d153d5cbfb6.nq.gz
│   ├── bb59359ab99348d350dd5db0e2118f2ada3427f9.nq.gz
│   ├── bc7a11e00eddc4c3cec5b6e938e69218c432a6c9.nq.gz
│   ├── bf37e7c10f5c1e9a5935af509f0773a312d10ab5.nq.gz
│   ├── bfffdf240f381f5585453952f6645c86354daa71.nq.gz
│   ├── c2e3956d50a26437035cbd429ae68e698b1c9716.nq.gz
│   ├── c4192631f25b34d77a7f159aa0da0e3ae99c4ef4.nq.gz
│   ├── c4839c0507d9a44975a389d3608d1a196b75d38f.nq.gz
│   ├── c52d86ef6a4a43d32ef28d80994600e14c254613.nq.gz
│   ├── c68986ddf33474c70ee7d366d841f3d0caa3cc2b.nq.gz
│   ├── c7b43f1ce3972c446e8371f1136545d764bc0366.nq.gz
│   ├── c896a4b9a613f0232ef1237b0e033fac811d848b.nq.gz
│   ├── ca2e9bcb865c7f97327f904cea5f12c23cbf1276.nq.gz
│   ├── d1a9e2faef3ba5bc0b7ff9076d3ab3cee1c1ce88.nq.gz
│   ├── d1bc764b969fd710959932894ffd166e283fa753.nq.gz
│   ├── d6379ccc43561666fb693ab12b9a2f1abe996fb4.nq.gz
│   ├── d653498e9648afc0ccd31306d1e6986f5d4017da.nq.gz
│   ├── d8189f2de6094f1944f1fae65aee9cfe1636e92f.nq.gz
│   ├── d93baa93922c4af59292ab27406b44faaf5c0932.nq.gz
│   ├── d95b989e50aeebb84bf55692be2d72a8b6d478e7.nq.gz
│   ├── e0e8a86b77602cb1ff0c8fe908aae3b57137cf5c.nq.gz
│   ├── e0fdc452e05bc8280e7a9bd18bf9cbbc8109b5d9.nq.gz
│   ├── e1a667b2e04a568efdb9d663f8f79ca930100ebb.nq.gz
│   ├── e31ff0f3e9a17e31e4e1fe34c8f3a0428bc107a1.nq.gz
│   ├── e3a230ee9ea82545dd48f370e1d6a1807d2b1c93.nq.gz
│   ├── e418a6f42a9ef4e6863dc6b9f2782d9ea236eaeb.nq.gz
│   ├── e57ae1870c79e626364c850f359d637a3312d7ca.nq.gz
│   ├── e5bdaddcf6e6390979e649d5e9d231a4b30c9801.nq.gz
│   ├── e9a72f6eb9e222c3a93c390e9ed4d1d505f7b6c1.nq.gz
│   ├── ef679f7441bf148ec439356b063c32b74abc4d13.nq.gz
│   ├── efabb94f9bffa34df534aa3a018c55f1c56fba5d.nq.gz
│   ├── f2c5bfdd837069bcd050f11e3fe9448188c6b77b.nq.gz
│   ├── f3adfc5cd8f71f6c880c929f434bc328ad861b56.nq.gz
│   ├── f48757b940bd0b7f03c175382753595f43161845.nq.gz
│   ├── fc7e5b2dccbe2ef36a2fea6daffd641b758001b0.nq.gz
│   ├── fcbd8bcad6f87ab4ffe51c5c68fe2339689d37bb.nq.gz
│   └── ff06a35d099bb35cc539aa23495925b1f47ec8d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1b4e9438e9558d8001f6fbe3dc2fadbb4fe74f15.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 111 files
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

[cherrypy/tools](https://github.com/cherrypy/tools)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
