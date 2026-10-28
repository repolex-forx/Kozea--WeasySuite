# Repolex Knowledge Graph of Kozea/WeasySuite

RDF knowledge graph data for [Kozea/WeasySuite](https://github.com/Kozea/WeasySuite), parsed by [repolex](https://repolex.ai).

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
rlex download Kozea/WeasySuite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 246a9ca0ca9cd55db8fc2162c609f4f9c0664e85
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 246a9ca0ca9cd55db8fc2162c609f4f9c0664e85
│           └── chunk-001.nq.gz
├── blob
│   ├── 01906ad0ce04e9e89f0bb083ccc3195864260810.nq.gz
│   ├── 09ac0862935ed13ccf8e84330cbb3548583f4fac.nq.gz
│   ├── 0b87e53467e4200bf6cb43c0c0f28c24a276bb7b.nq.gz
│   ├── 0c516d14b9638547e4067321e8f9d266d2eb087b.nq.gz
│   ├── 0de92cd2b310e3bdb53c8b9de0b4169fa00ea523.nq.gz
│   ├── 0e087e349273ffedf9223de85f2410b4805e8839.nq.gz
│   ├── 0f771f56f7f1cc514afdedccd404865ce560dd84.nq.gz
│   ├── 0fe31dafe13d7621c0a06e77dd09374887d16222.nq.gz
│   ├── 1097e627a27937926629cf914d17fab032464600.nq.gz
│   ├── 11902d3e1a71bcd1811c0df64d89e200a7175419.nq.gz
│   ├── 18c36755ac6f5b57ce0fa7115a3d9a65769bde02.nq.gz
│   ├── 1df68bc602df69463fe20476909070be48343a34.nq.gz
│   ├── 2138ad55c557c0f48996b174b6a4fadad49a2291.nq.gz
│   ├── 23162691044acb1baed4dd35d0f127b4d7fd32a7.nq.gz
│   ├── 24e9580ea7a4d09a9dc00665d747988245780e96.nq.gz
│   ├── 291a7e27f11cfe3172e4e894c2a4fa98d9857819.nq.gz
│   ├── 2b466c30c071b581239875985aa263e60795ccaf.nq.gz
│   ├── 2c4e1e7e74aa70f632c644854cd5968bf5a9729d.nq.gz
│   ├── 2e7e0c350b1be14e7bff4770cdd0e282394462d2.nq.gz
│   ├── 323dcfdfc9ff56ef1964ea373713283566c34095.nq.gz
│   ├── 330cbdd38e0c7c0cecc4ee0436b4ab525216fd61.nq.gz
│   ├── 33e5c307ff1a14572cc14034785cf10a001a4d52.nq.gz
│   ├── 34226133769f0d80d7e11dcf38629858098a5e26.nq.gz
│   ├── 38cec23e99737ef708355c8b8eeb713fc73b2fda.nq.gz
│   ├── 3c73b0053f6424ee1174710611b2fbc4a8e38296.nq.gz
│   ├── 3c844c55c2937c6df39084bbd1878e2863cd84a5.nq.gz
│   ├── 4003421e55585fe5cbb04cbf14b737e112072ffa.nq.gz
│   ├── 4315ea45144a5641f19e237dae5216504c6ce613.nq.gz
│   ├── 44bdd1b590b862254607bae2aecdcfcce1f99c4d.nq.gz
│   ├── 46cebb88151ab59d38b11f9bf78563bfb152db97.nq.gz
│   ├── 49800a057192829f33742952df1671e5d8b7201e.nq.gz
│   ├── 49e6e5049a258de7f08dfb3a01dc59503572f5c7.nq.gz
│   ├── 4ad3a4d4508c9c078eceac6e750aae61f1a5eadf.nq.gz
│   ├── 4c357c6c89a4fd059d2c382dd59bd15cc7522b96.nq.gz
│   ├── 4ca66f8ee2730d23371cf3d71982c3384f121f80.nq.gz
│   ├── 4cd1849c69ee51a1dc9fb4343bac296a2d0db75e.nq.gz
│   ├── 4d9be4306a5379291f682b16091f4a8bee2a70a3.nq.gz
│   ├── 51ba0b58812f019bd504d3be7236f80255ec2484.nq.gz
│   ├── 549187250e57386feb976a45898c2ffab639935f.nq.gz
│   ├── 5502fdaa66eeffc227a690ea5edc9a55884dd775.nq.gz
│   ├── 5569fa0151019d9abcb6605b0246b349554d14ac.nq.gz
│   ├── 5761bc94d17a47854f04433b5efaed0cf17a0cfd.nq.gz
│   ├── 57cda2c0914f3d1d662382ccf91a9b4f4057a467.nq.gz
│   ├── 5c1ee00902de23ba0cb093f60e8acb9a736c9baf.nq.gz
│   ├── 5ca3c6e36b36a1110c0133b76b3d43580476d542.nq.gz
│   ├── 5cd5fa0770ed29498dc036d451876532014e7e47.nq.gz
│   ├── 5d92dc91ebf38e871fb616b4d8ff0863918de1ad.nq.gz
│   ├── 5e7edee378cbc3992feb1e5d843e32544a38e41d.nq.gz
│   ├── 5ed695523900d05e8cffdedac6cf9568f272eab5.nq.gz
│   ├── 5f969e7676785f1fe6f3c15744ac2e3b74413fab.nq.gz
│   ├── 60647e485a0855051697b4251a5d35e3333489fe.nq.gz
│   ├── 62b43d68dcf7f6083c180ed874657b2e15bdcf8f.nq.gz
│   ├── 6329815863f3796bb21bbe9c3cd14853c4be0f94.nq.gz
│   ├── 67b4405efef7e923db0678c5ca6f22d1f9102f94.nq.gz
│   ├── 68f6e4cb63be9bc6a5d96219de81c438976a6228.nq.gz
│   ├── 69859c7942bb0ecd8424fcb7aaed0fc2a2e8e441.nq.gz
│   ├── 6a07c6019253c38ee117ffb71bb5d6f5337c8a8f.nq.gz
│   ├── 6a0b02ac4d4165a94baad0a30a6b99b05b58f490.nq.gz
│   ├── 6a1cb0fedf20317e90ac9f3434323a59a1a85868.nq.gz
│   ├── 6b1a6e15dcd6ccdd66bfbb0a6802d95216a50451.nq.gz
│   ├── 6b53c5608b47adf0fc940cfbf4a855fb58311049.nq.gz
│   ├── 6f278cef03a0abf82b2ac2b12ead757f9a593f47.nq.gz
│   ├── 724ff033ba1d2cfda1bf822e8cdc4cf16c974b03.nq.gz
│   ├── 74fe71f9a62f66587fa5224b3402aa805c680d05.nq.gz
│   ├── 77a1856c8338bfd944b278b888f10f208e7e9eee.nq.gz
│   ├── 7944e1a59784f7a370eb915925be626dda963f68.nq.gz
│   ├── 7b68567b9aa969c73d7e64335f9856487e456c24.nq.gz
│   ├── 81193d0bd15c23a1d279c11a2671476d0cd520d2.nq.gz
│   ├── 84444aeb2cc3b28388aca2e81f52e29d23e1e90d.nq.gz
│   ├── 84d5724886a256f3b015ba5d44e2022a343a37b3.nq.gz
│   ├── 84f67f1e242de04230344c1df91c262ff926a852.nq.gz
│   ├── 86ffb03228ccdf18bcae7ec0e2c2465c32705514.nq.gz
│   ├── 8a84cd4878ff02577e47b456f30813bf2a647b97.nq.gz
│   ├── 927515806e389dfd077693275c19bf011fe217db.nq.gz
│   ├── 97cbc11ed40b2d58af242a422bcf8d3ed4fec53a.nq.gz
│   ├── 9813ff3cb94c45812659800a70c3a66e665b6ae5.nq.gz
│   ├── 98a64cf7f16873e22c9224eb3df11a0e2fb1b254.nq.gz
│   ├── 9b2467fa29132dfe759ddbd977c89db0504b4483.nq.gz
│   ├── 9bf4f4cd509bfc59387faa304cbecbab37a9d920.nq.gz
│   ├── a049825cf8764812440e1567c751800b43a1971f.nq.gz
│   ├── a0911aa370c1d1e00cf3906ba42f9d7f4072999f.nq.gz
│   ├── a0a865e223d16d2ee23d29a09e7ee6ab5308bdf5.nq.gz
│   ├── a1af64c221ed7561822ff2ea2885b31b29da5d17.nq.gz
│   ├── a3f41b9d9a1b3647e2cd44b3d6b9df2d90c0b61d.nq.gz
│   ├── a821a6c05bfb09a8b428943be413aabf0293c9cc.nq.gz
│   ├── a86e0af54840ff21c436e4c7ac8a4f18bc40b62c.nq.gz
│   ├── a8a2f600d78c1d9326f3278bc32d2adad4a990a7.nq.gz
│   ├── b266cbf4943921825f8c1015ea02ff2e7df13c43.nq.gz
│   ├── b3a4e20d600a050e9b64aa99e2f053d46e59f2bd.nq.gz
│   ├── b56fbd251bd7ab0aca976e939207a5928870640a.nq.gz
│   ├── b670c424426f0da5c2838c4962e4c907e0bab9ae.nq.gz
│   ├── b7939e9ec542873bb0b622d59a212cb4e4c81197.nq.gz
│   ├── bab4b98259c7bfe1966d2ea854f7ea09f97c72cc.nq.gz
│   ├── bac5b0bcabb104ca1d60fd01aa394f850122a5a8.nq.gz
│   ├── c2dfa628e73bd2af47c7fbd18e17a65ab5af2e4b.nq.gz
│   ├── c468842134d758eb337f115af72e52cfe19bf4d8.nq.gz
│   ├── c4f7121c989d1f3ddaa72845f92accba3d3e6e42.nq.gz
│   ├── c5c7b4ff1a97d513e73c33e54ae617aef259e1c0.nq.gz
│   ├── c7235e46466df06e9946748e62cc8a9e2e73e41b.nq.gz
│   ├── cb97aae1745156b3ee6748d22f163bcf42e75153.nq.gz
│   ├── cd680b5f30fac3396fd3cd29593afbda36d19c2e.nq.gz
│   ├── d14577169195cfee21c7d1206a755d94c9c146c7.nq.gz
│   ├── d4c57e4be475dd1fcc1ae285a45df0ba257d8765.nq.gz
│   ├── d82c2446c39f9105f24c03e90b82f7c5c0a35021.nq.gz
│   ├── dd0679331c19b3fb80d0df20b24232ac36a5e81b.nq.gz
│   ├── ddfa71ed1762aa805dcc64efa92c4b5185d458ed.nq.gz
│   ├── de65c6a1a327d7a2413e4453ebcaccb300b935fd.nq.gz
│   ├── dea01eace9a53cc007c78ceb2e7e15dfafc6f0e5.nq.gz
│   ├── e17b554b2e6db144192f3deddb5f2e4a3a8bb171.nq.gz
│   ├── e5fc7dab55168a22dd7c22576a1fb69a7cd872e1.nq.gz
│   ├── e7f909fce7d38b1e190e30571fb46608a84a465a.nq.gz
│   ├── e953d42eb4184fb9c3191fed7337467583a14d54.nq.gz
│   ├── eae265f1d06dc871b09d655c54126155e0c0a0f0.nq.gz
│   ├── eb7081cd3502fa516c31d3ec036fa85da4020a09.nq.gz
│   ├── ee081db7bb3ecc78bb7f577d5d7dc97b1816866e.nq.gz
│   ├── f22d02b5543137c27554e95970746998a992452c.nq.gz
│   ├── f41799cd41788ae7c58e98a0fec5a917555392e1.nq.gz
│   ├── f457b54443116153af0c2a3e379112dfbed10551.nq.gz
│   ├── f7b1abf33faf454d331ffe2d0794198753d6b5ca.nq.gz
│   ├── fa045da56f5f6b676d3409a8218db3e85fd51c1d.nq.gz
│   ├── fda0a65da330fce9c86125ac6a733e3b33aa1a91.nq.gz
│   └── ffc7f0a04e0630bf0bfce5e92ba1d6e14c2171d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 246a9ca0ca9cd55db8fc2162c609f4f9c0664e85.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 128 files
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

[Kozea/WeasySuite](https://github.com/Kozea/WeasySuite)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
