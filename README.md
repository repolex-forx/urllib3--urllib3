# Repolex Knowledge Graph of urllib3/urllib3

RDF knowledge graph data for [urllib3/urllib3](https://github.com/urllib3/urllib3), parsed by [repolex](https://repolex.ai).

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
lexq download urllib3/urllib3
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
│   └── repolex
│       └── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0079d14e98119a2c0ee1ee8a77ac937a509dc4f7.nq.gz
│   ├── 0084df476a6f661c46e005ff80c844660264c0ff.nq.gz
│   ├── 0097179fb49c5e3a920d2f3b161799ae50002eab.nq.gz
│   ├── 00c0a1b8b82c4b242a586bd8f3c9bb71c0f6ad05.nq.gz
│   ├── 016484d2971840524515b85cb2bc04494c471797.nq.gz
│   ├── 0378aab1b1aba0b61cb2741156dea652591ca2bf.nq.gz
│   ├── 03cda714f66f7aba4278c0ae43158c508909a1ce.nq.gz
│   ├── 06167207c25060aec713b2dcbbbccf90a79f9045.nq.gz
│   ├── 069aa198709cccbed3e3bce49016a6dc20d0fc8c.nq.gz
│   ├── 081877b1374dee09a91aa56c7498f5a2915f290f.nq.gz
│   ├── 0a026da0a8357e324ded47b82b24042713b9bf06.nq.gz
│   ├── 0ab1b3a2453a06370d01cd6411c446d3efb1409f.nq.gz
│   ├── 0b3d7a1fe47d66d96bd6fc783e809f594d34c55d.nq.gz
│   ├── 0ec62457d2436a72fb0830fafde6e06f60697b6f.nq.gz
│   ├── 0f4578696fa2e17a900c6890ec26d65e860b0b72.nq.gz
│   ├── 11785fa5852a87f74b1cb264285bb23b61566388.nq.gz
│   ├── 133e1d8f237f6fddd557ae1c0e0cf738f7cc2748.nq.gz
│   ├── 140ca9fb6738be217c8a24b02e658888c00d2753.nq.gz
│   ├── 1492c952c4da14b16599eb8f0c860efcda960a85.nq.gz
│   ├── 14f70b05b4778f91137e4a9e7059d7514aa44d28.nq.gz
│   ├── 176fed4ae4d2c3b8728b7b24d4e30070b6fe180e.nq.gz
│   ├── 184edbbe9b8f7b49b1e31159649994f90ecef95e.nq.gz
│   ├── 1d9d0bbdb6270260743dde03934141cb50d271d8.nq.gz
│   ├── 200f140ce39ca9fac6b4850fa448f59abca892c0.nq.gz
│   ├── 23413f5a85c4e2c3249cb05c7a99adb08a90b3d8.nq.gz
│   ├── 24026c367a25843098ec8ef2316b4975f83fcf5c.nq.gz
│   ├── 25d91000419ea4a860f511ebe669fe171b79254c.nq.gz
│   ├── 26a877a07e4b101385a79d6adbd4ddede9193a55.nq.gz
│   ├── 28ec82f0168543a8aee7cdb79a4b46f10bb2cc91.nq.gz
│   ├── 297c271bf401c1cb48c6225f8822e78f58c3ca56.nq.gz
│   ├── 2ceeb0a5483bef1927a57d03c3dd2cab0d8c9f8f.nq.gz
│   ├── 30fc163aed5909b9954558215acc3c775379ffdb.nq.gz
│   ├── 322ca26fb96c8b0a4c03b89629784f1219e77cc9.nq.gz
│   ├── 33f567e4d5136dbedf0137f7b1bdbf296d63781d.nq.gz
│   ├── 35c77e4025842f548565334a3c04cba90f9283d6.nq.gz
│   ├── 35fb1991647ff8d3d1bc4583f8dca78f634a44c9.nq.gz
│   ├── 36d7ed5dd63b7219e5606f37cc0c5bb5208d84c1.nq.gz
│   ├── 36f599d7b410b2ec2a3df36eddea9c7eb2a12e8e.nq.gz
│   ├── 3721274571739c849bdc488fa5e23c788b4ff1dc.nq.gz
│   ├── 3a0685b4cdd0562e508b9dd032765b5c759ea61e.nq.gz
│   ├── 3ab4fcf3a52b336342c58ad9f2175b02a6e6a483.nq.gz
│   ├── 3d16e7cd18f37ff40546659a7fb6d27657e7fe37.nq.gz
│   ├── 3ee127a02bbc3aa7734ec1d97714b4becfd24a16.nq.gz
│   ├── 3fe782c8a45bbabcf240f3cac4303ac12b0ec274.nq.gz
│   ├── 41aa35b9d8a1bab25dd93949a8981d1619bed3cf.nq.gz
│   ├── 445bc7e9ec77aec863370cf4bb196ec3a619a2b3.nq.gz
│   ├── 45538a6ead65a57778776fa8f913ebb376eb32a2.nq.gz
│   ├── 45dee02b8e9d4f189b1e7fe4a0a9249fddf70076.nq.gz
│   ├── 46707571e62fc3484f670908e579fda493ec2d65.nq.gz
│   ├── 4725e28b57bdc6bc1c151aacfafb9f7791f71036.nq.gz
│   ├── 4a932c0de46c9c53bbcb79ce35e1f659326ccee1.nq.gz
│   ├── 4bb1be11d9cb06900dd82ecebd06aa6a7c5de916.nq.gz
│   ├── 4d81060e5d533bab2af2be9e7b321c0d77d550ed.nq.gz
│   ├── 4ff003bde1f50a2d90fd4ac640c841bc09e4118e.nq.gz
│   ├── 508136d1a572663fea70c040884e51faa53bd565.nq.gz
│   ├── 534126033c083203649022fa9b753a433f005556.nq.gz
│   ├── 53b41c0a42594e78ad040ba1f6f03f8c5a822690.nq.gz
│   ├── 56fe9093adaa86b30085aef2435e49f84841df12.nq.gz
│   ├── 582b8f719fb71122f217516e635cafefa6e26402.nq.gz
│   ├── 58723faeb0ca7e5d8e3ba319f8d5acc79c91409c.nq.gz
│   ├── 58e1c201670c3f6bd903e5da2ae6ffe263b36318.nq.gz
│   ├── 592ee6bea21389ee3714892bd489cedc9b3d9861.nq.gz
│   ├── 5b82e9329d88b6e993841b75c466fbcac2ccc913.nq.gz
│   ├── 5e16c955323298437a0e6144ab0bce09cae555a3.nq.gz
│   ├── 5e5e7dd4b0858a4258affbdc1942034608e907bd.nq.gz
│   ├── 5f3ea3d919363f08ab03edbc85b6099bc4df5647.nq.gz
│   ├── 612cfddc4c28d2f0edf47522278fa6d9b7906623.nq.gz
│   ├── 620e2b1827845dbcfb4574ffefc835d0ac683361.nq.gz
│   ├── 6321696dbbcb1a0ad9355a227eed53f94b2667a4.nq.gz
│   ├── 6370ab1795c380b4b8642383f4b1778f83da49d3.nq.gz
│   ├── 63f79dd3be803db09671c909f79316c3f65d6916.nq.gz
│   ├── 66e3ee5e9086c04d00fa905492afb3e2e423f82f.nq.gz
│   ├── 6c2372ba7e777826a4eb124ddfb54f0240b65d67.nq.gz
│   ├── 6cbf5a88f1f6095c6123e3150fc64a55255868f2.nq.gz
│   ├── 6d59bc3bce2489c3a0aa5bcb83b737dcf33c033b.nq.gz
│   ├── 7000aa0817c869829c7b7cc717a9bd554f75d22e.nq.gz
│   ├── 7011caabe68efd07d28443b76cd7f53f7b100574.nq.gz
│   ├── 710b8fbd98a5bff1dca272b3231b031d386c0257.nq.gz
│   ├── 733a0d323393e73cfc52dec1726dcd237151e8be.nq.gz
│   ├── 750c17246170a785657dc636be26ab127dded340.nq.gz
│   ├── 77a3bb2a37f8d3c2718531bf22641d2ac26da8f6.nq.gz
│   ├── 7c2377a4c33fb4bf46bf981aab80b016e697a838.nq.gz
│   ├── 84603a7f6e7da3938c261a198fb8994744cf361a.nq.gz
│   ├── 86e6661e729e506d651a606cf2742164a1a4e782.nq.gz
│   ├── 8a07a8effb7313f864b660e6f6e0853bf4636619.nq.gz
│   ├── 8a4c410e33b39d37336ec787825ecf6ff202a819.nq.gz
│   ├── 8b9ae652ccfa787ab96969f82930cd8d0205ae34.nq.gz
│   ├── 8bd7b258bdfb94098bdde53a35bf55d200bae117.nq.gz
│   ├── 8d36b1471b78ed8e617f57ae7e10a87a772a4cf3.nq.gz
│   ├── 8d6107aea03915a62344b2e82228a8eb3535e811.nq.gz
│   ├── 8e05d3d785d53021a97a713cbdbb1f43708c9150.nq.gz
│   ├── 8ea10d80ec4f95ad1602273b0b64c18914740db9.nq.gz
│   ├── 8f0c88065eb8c1a0e7181ffe40f6ca122c658d1c.nq.gz
│   ├── 908fc6621d0afbed16bde2c1957a5cf28d3a84d8.nq.gz
│   ├── 90a531fefb2b880f8a4593ebbbd6fb3095bafd89.nq.gz
│   ├── 9550de8fce975500c4b35b2e14204cf2e3420ee9.nq.gz
│   ├── 95dea64fc444613fb6b67452107e56cfc7981431.nq.gz
│   ├── 960259ee78423c12a882bf62129af8cfab1afee0.nq.gz
│   ├── 966c4c7bc5b3a8421b56f609d0ba7880398a7c21.nq.gz
│   ├── 96dfa2f91fc20cfd1a8c5bca4b8d642399426769.nq.gz
│   ├── 9723dfdf3cb7ad76c2c1ebf53332d26c2924ad9e.nq.gz
│   ├── 97c4730cff0df570e1ab47f77e6aa879ec3c36e7.nq.gz
│   ├── 9ea900764f0885eafaac9454523417d86e33df2d.nq.gz
│   ├── 9edeb6b860b8c939f08fa418b83feb5ce9d6df26.nq.gz
│   ├── a11012fb16b281023284782b5a23feb3bdfe7288.nq.gz
│   ├── a2cda88659146eac7178b55109ac93bd30db7580.nq.gz
│   ├── ab05d227a77573afc6b1d9a83038558cb21a0dbf.nq.gz
│   ├── aeca0c7ad5b232eeb1ad9c43d315bd1d74eaed9a.nq.gz
│   ├── b1be2badbd604c64951adda08523c57053367908.nq.gz
│   ├── b1e0406c867ef72a8007d67e506aa9f68f1f1069.nq.gz
│   ├── b21b4b64ebbd4748eb6fa4301f947b0d4965da8b.nq.gz
│   ├── b481a19d59429896a79f833ddc74cdf68c477aa6.nq.gz
│   ├── b6da4b94473d517f3a0f3c61c9afe5806a50c40a.nq.gz
│   ├── b9c547c00f7b7bc5f6673cb665573cbcbefcf8c4.nq.gz
│   ├── bb8bc08bc6840289813b71f71dd91a0468c6bff3.nq.gz
│   ├── c00d51b62bc62a4f9be7354cc36786136b904f91.nq.gz
│   ├── c2da2ae8afe316ef0a4c52b2abfd411736b72b7f.nq.gz
│   ├── c46bcc0bb077dfa71f75c6393bc194d5ae9ca7f5.nq.gz
│   ├── c8c423a94e8107f33592aaa399c7099c644d4c3c.nq.gz
│   ├── cb1088a1826d089e1b603c51e85560b8583a3e3d.nq.gz
│   ├── d00b8af65c8bc56a1aa2a85a3cad0b237ab2c086.nq.gz
│   ├── d14181f26a012b37ba868c67a97b82cae78633b5.nq.gz
│   ├── d182727866daa7dda2b994ba46579d4556fdd3ca.nq.gz
│   ├── d267a737be6144635530da5c3f59f05fbb8f5645.nq.gz
│   ├── d837b85fd4f74e011ee020eb5e910f58866fd449.nq.gz
│   ├── db057f17be610174f30928748b5004dcbf6c501c.nq.gz
│   ├── dc0f318c0b380926eed0f4209d395c79963eaf9e.nq.gz
│   ├── e1be27a5e9828c2c7298ef5abd4dae7e4d2d4feb.nq.gz
│   ├── e3239b569d93c6139f9c6a86118a5884daf1dabd.nq.gz
│   ├── e5765d51089c932f753ebbf87098ef142886faf8.nq.gz
│   ├── e5b62b25e932566f7ae7599c1cedec2b8f30d95b.nq.gz
│   ├── e6183d0276b26c5b87aecccf8d0d5bcd7b1148d4.nq.gz
│   ├── e692e692bd0d38f6a0677992a6993fc68050dff3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e793f79189394d3421123922502a911e14e500bf.nq.gz
│   ├── e8a00ec2ffd1400d383c1639132b77b96db82366.nq.gz
│   ├── e8c94843ba7d2813b048fc6bafe4e9b3c264f833.nq.gz
│   ├── ea39de894ec317e8ab0302af46373bb8ae2c0e63.nq.gz
│   ├── eaeb29af297b59617ba3093829bbc6467d590081.nq.gz
│   ├── ec7d83e0fd78d65aa1eebae6f7659565eb5f3dee.nq.gz
│   ├── ef09151ad3041e8053c8686807b711ae8ed1c28e.nq.gz
│   ├── f3d658532b7ce186666d0b050c35488d2cc8e55c.nq.gz
│   ├── f55809f79071f23a3f0dffe362dde1402cc56ad7.nq.gz
│   ├── f5587907285cd37280d3ae0d245ac4de0c3d6ab1.nq.gz
│   ├── f92519ee9124e91e5da7d60ccc3f274312ed3514.nq.gz
│   ├── f935021a8f8a7bd22f9d6703cafa5134bb6a57f8.nq.gz
│   ├── faf141e1fa4113a0c14480d1681ddecb9678ced4.nq.gz
│   ├── fb3014417c4e8c5da04aedd9cf4728947773be33.nq.gz
│   ├── fc34cc9c04e8ad798bcd0416f51c688cdcec2a22.nq.gz
│   ├── fc8e559360b76c2f311f5f04b4fe7e47c0c070a8.nq.gz
│   └── ff6d1f4911c2e304a2d7822059d9574536f81aea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
├── filetree
│   └── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 161 files
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

[urllib3/urllib3](https://github.com/urllib3/urllib3)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
