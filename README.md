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
│   │   ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 04df048cf4b1c3790c56e26c659db764aad62d6f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1af920653cfed1920a576e80cc7a856fe4df2ac9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│   │   │   └── chunk-001.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│   │   │   └── chunk-001.nq.gz
│   │   ├── 612cead3f9704716f4ab2a1334a16e0f05fce942
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6446fef0cf432ca035169602a1447a0d8ef53e80
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387
│   │   │   └── chunk-001.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│   │   │   └── chunk-001.nq.gz
│   │   ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d
│   │   │   └── chunk-001.nq.gz
│   │   ├── b85e93d619a323b92c2954da852857e0119d71b8
│   │   │   └── chunk-001.nq.gz
│   │   ├── bfe8e198a13800e3ee8ef8124a8928acb170c843
│   │   │   └── chunk-001.nq.gz
│   │   ├── c479b73ba6114c0ec1010db86f6eb193fe874c84
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9016bf464751a02b7e46f8b86504f47d4238784
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│   │   │   └── chunk-001.nq.gz
│   │   ├── d94029b7e2193ff47b627906a70e06377a09aae8
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9d85c88aa644af56d5e129634e750ce76e1a765
│   │   │   └── chunk-001.nq.gz
│   │   └── d9f85a749488188c286cd50606d159874db94d5f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
│   │   ├── 04df048cf4b1c3790c56e26c659db764aad62d6f.nq.gz
│   │   ├── 1af920653cfed1920a576e80cc7a856fe4df2ac9.nq.gz
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a.nq.gz
│   │   ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700.nq.gz
│   │   ├── 612cead3f9704716f4ab2a1334a16e0f05fce942.nq.gz
│   │   ├── 6446fef0cf432ca035169602a1447a0d8ef53e80.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462.nq.gz
│   │   ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469.nq.gz
│   │   ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7.nq.gz
│   │   ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d.nq.gz
│   │   ├── b85e93d619a323b92c2954da852857e0119d71b8.nq.gz
│   │   ├── bfe8e198a13800e3ee8ef8124a8928acb170c843.nq.gz
│   │   ├── c479b73ba6114c0ec1010db86f6eb193fe874c84.nq.gz
│   │   ├── c9016bf464751a02b7e46f8b86504f47d4238784.nq.gz
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0.nq.gz
│   │   ├── d94029b7e2193ff47b627906a70e06377a09aae8.nq.gz
│   │   ├── d9d85c88aa644af56d5e129634e750ce76e1a765.nq.gz
│   │   └── d9f85a749488188c286cd50606d159874db94d5f.nq.gz
│   └── repolex
│       ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│       │   └── chunk-001.nq.gz
│       ├── 04df048cf4b1c3790c56e26c659db764aad62d6f
│       │   └── chunk-001.nq.gz
│       ├── 1af920653cfed1920a576e80cc7a856fe4df2ac9
│       │   └── chunk-001.nq.gz
│       ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│       │   └── chunk-001.nq.gz
│       ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│       │   └── chunk-001.nq.gz
│       ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│       │   └── chunk-001.nq.gz
│       ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a
│       │   └── chunk-001.nq.gz
│       ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│       │   └── chunk-001.nq.gz
│       ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│       │   └── chunk-001.nq.gz
│       ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│       │   └── chunk-001.nq.gz
│       ├── 612cead3f9704716f4ab2a1334a16e0f05fce942
│       │   └── chunk-001.nq.gz
│       ├── 6446fef0cf432ca035169602a1447a0d8ef53e80
│       │   └── chunk-001.nq.gz
│       ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│       │   └── chunk-001.nq.gz
│       ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387
│       │   └── chunk-001.nq.gz
│       ├── 720f484b605f18887a48eef448d0084e2b76902d
│       │   └── chunk-001.nq.gz
│       ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│       │   └── chunk-001.nq.gz
│       ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
│       │   └── chunk-001.nq.gz
│       ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b
│       │   └── chunk-001.nq.gz
│       ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│       │   └── chunk-001.nq.gz
│       ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│       │   └── chunk-001.nq.gz
│       ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d
│       │   └── chunk-001.nq.gz
│       ├── b85e93d619a323b92c2954da852857e0119d71b8
│       │   └── chunk-001.nq.gz
│       ├── bfe8e198a13800e3ee8ef8124a8928acb170c843
│       │   └── chunk-001.nq.gz
│       ├── c479b73ba6114c0ec1010db86f6eb193fe874c84
│       │   └── chunk-001.nq.gz
│       ├── c9016bf464751a02b7e46f8b86504f47d4238784
│       │   └── chunk-001.nq.gz
│       ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│       │   └── chunk-001.nq.gz
│       ├── d94029b7e2193ff47b627906a70e06377a09aae8
│       │   └── chunk-001.nq.gz
│       ├── d9d85c88aa644af56d5e129634e750ce76e1a765
│       │   └── chunk-001.nq.gz
│       └── d9f85a749488188c286cd50606d159874db94d5f
│           └── chunk-001.nq.gz
└── blob
    ├── 005467cec04f2ebe46d350c07976ae4d8a047a64.nq.gz
    ├── 006edd23c4302e1a3d6d5dd8712c93f26a3ed3af.nq.gz
    ├── 0079d14e98119a2c0ee1ee8a77ac937a509dc4f7.nq.gz
    ├── 0084df476a6f661c46e005ff80c844660264c0ff.nq.gz
    ├── 0089cd27e05062cd94398a9d7ae8e9a479f8f919.nq.gz
    ├── 0097179fb49c5e3a920d2f3b161799ae50002eab.nq.gz
    ├── 00c0a1b8b82c4b242a586bd8f3c9bb71c0f6ad05.nq.gz
    ├── 011bb77bf1a0524f2ddfdb65004173f4b9aa4150.nq.gz
    ├── 0129dda7c2bb3ddbf89d2a09960252a4fc8f5354.nq.gz
    ├── 016484d2971840524515b85cb2bc04494c471797.nq.gz
    ├── 02724a378a6da8a240eaa4b79f028556d6a12aab.nq.gz
    ├── 02a38115c5a14945429fc22256da58f7ee844220.nq.gz
    ├── 02b2f622a1b1cfca660f602ba13913530e21992e.nq.gz
    ├── 02e3de5ec625c506276342363f5699234233e949.nq.gz
    ├── 0318601bbd3df95e0a068b0a2453f4a1847290b7.nq.gz
    ├── 03186e51296fc1a6ccdde018f31b716b1723afd3.nq.gz
    ├── 0378aab1b1aba0b61cb2741156dea652591ca2bf.nq.gz
    ├── 0394578287c19042344f338c896c1178ba81fbd6.nq.gz
    ├── 03a1992df71dad49a558356502d3dd99a0a84064.nq.gz
    ├── 03cda714f66f7aba4278c0ae43158c508909a1ce.nq.gz
    ├── 0456cceba47b16ae6784458cc17eaa528a517ffa.nq.gz
    ├── 04a94c2bca8e1d69ce27fc38cf4d4988b8a51e58.nq.gz
    ├── 04e65f8cd4a1e1ce402a61cb4b316b45059135ab.nq.gz
    ├── 06167207c25060aec713b2dcbbbccf90a79f9045.nq.gz
    ├── 069aa198709cccbed3e3bce49016a6dc20d0fc8c.nq.gz
    ├── 069cd2742cf51f2c619386d7efacecbfc6459b65.nq.gz
    ├── 069f726cb85a5e3722f974adf8d5a617f9fef4a9.nq.gz
    ├── 06db4a0e186920bc84a8fce3a52d369ba73528c5.nq.gz
    ├── 081877b1374dee09a91aa56c7498f5a2915f290f.nq.gz
    ├── 08277e97e0c93ede67e6730e3fe50846e610f9f2.nq.gz
    ├── 083854d1b04810e174b31fe2cd087401d3065597.nq.gz
    ├── 085d1dbafdb3d8141523b2b0e93fdd26845e3aa0.nq.gz
    ├── 0872ed770117096a8decf02e099a5c4148e018f3.nq.gz
    ├── 095cf3c16b9debf6bd3f77e75e26b0ab9c2a7612.nq.gz
    ├── 09b08eeb0591d9229114dda04eae217b7a8eb19c.nq.gz
    ├── 0a026da0a8357e324ded47b82b24042713b9bf06.nq.gz
    ├── 0a4573e7d9848499cd86450bed8721936333c058.nq.gz
    ├── 0a5eb6616406ac491e09b377a0c40c326ccdde01.nq.gz
    ├── 0ab1b3a2453a06370d01cd6411c446d3efb1409f.nq.gz
    ├── 0af923e34c1a9d0e3f0db4f267f18a945626a1c4.nq.gz
    ├── 0b3d7a1fe47d66d96bd6fc783e809f594d34c55d.nq.gz
    ├── 0b9d1f1fb02ea3a314031525fc73088ed08a95c5.nq.gz
    ├── 0bd13d40b8ac751e4e57f2e4a2f7b447283dca9d.nq.gz
    ├── 0c1e79347adc04c250d14863fb862f2d1b002f55.nq.gz
    ├── 0c42b2a2492ab80a16fc7e419fde4f68a91a6302.nq.gz
    ├── 0c46aa1dd3a9ab4186bd576caed3daf02c129597.nq.gz
    ├── 0cd8dedd264f4350d19b1fa5a7960113bd754211.nq.gz
    ├── 0d013932688bfbe8522a305436fb0e340de79916.nq.gz
    ├── 0d270272aff2694813508ddee1a4f046d111293e.nq.gz
    ├── 0d41bf1fa681c485a846d41c9efb5c5e9f9303cc.nq.gz
    ├── 0dbfef92a207b8d65bb7c7ebe7eca544f80f02be.nq.gz
    ├── 0e26aa3b4822ac5f1eaef8305968cb7a60899531.nq.gz
    ├── 0e286aa32ef235f4d248d6903bc93d52156433ad.nq.gz
    ├── 0e854a54241483c78d109e23263c5830abbce290.nq.gz
    ├── 0ec62457d2436a72fb0830fafde6e06f60697b6f.nq.gz
    ├── 0eeb93f7396ebc3aca4979ec8a6721b483ca5a7e.nq.gz
    ├── 0f1586336432ff13b67fa05c7c14cbab4343ef0d.nq.gz
    ├── 0f4578696fa2e17a900c6890ec26d65e860b0b72.nq.gz
    ├── 0f4e5cc581c63cbacb0d2b8cc5342df0b3f6abd0.nq.gz
    ├── 0f58105ca1dcee53bdbff63720bc9046ae3b813f.nq.gz
    ├── 0f7e24c26422d97993b99d2b48deb0a62bc3960a.nq.gz
    ├── 0fee338948ceb23f7457ad188c235abd9a355066.nq.gz
    ├── 0ff7ddb2a1412a7e3b6b8d2bd4f00c62d9e8c099.nq.gz
    ├── 10109fa917e9f0c265cde007f615102b82fbde2f.nq.gz
    ├── 105837dbfaaece95c44fe9f843d4cb17f784e917.nq.gz
    ├── 107c5e0af7989bcdf062c9854e875a76c290443d.nq.gz
    ├── 10b2f2baf841fe7e355ead4979ccca605a16921d.nq.gz
    ├── 10dad117669d33f4ddd09880e52846a9d284682e.nq.gz
    ├── 11785fa5852a87f74b1cb264285bb23b61566388.nq.gz
    ├── 11beb3dfefb7e92c2e37440bd2a29809657d5f47.nq.gz
    ├── 12097ea9c20698dff1b56d8d100f8a3267a33655.nq.gz
    ├── 12a6ddcf2b8280c677798586ca05e85faa9567e9.nq.gz
    ├── 12b1c7fbb18a731c59e70ef68b92094f910cab61.nq.gz
    ├── 12c0055493a2a40c69ede93d799ac832d90830bd.nq.gz
    ├── 12e07839eeb409286e1af9435d4dcb87d32b93f1.nq.gz
    ├── 133579fc1144f81598224ae162c66c18d0dd063b.nq.gz
    ├── 133e1d8f237f6fddd557ae1c0e0cf738f7cc2748.nq.gz
    ├── 138f99abbec0569cbf596adaccb4f1c74ba56db3.nq.gz
    ├── 13ad811d06b24a3382ad59deba7aa52777436413.nq.gz
    ├── 13dd6fd2f95bcbdfade647afea950a8081b3f16e.nq.gz
    ├── 1407431a5c56ba093554072f6137a8da08100dd5.nq.gz
    ├── 140ca9fb6738be217c8a24b02e658888c00d2753.nq.gz
    ├── 14324fecb26bbfdfbfe31344463ba34e8aa443cf.nq.gz
    ├── 1442827def8e5732518d616349fe53dc8a61c6d3.nq.gz
    ├── 1492c952c4da14b16599eb8f0c860efcda960a85.nq.gz
    ├── 14a40906c558e29c3fb66e7f4f678709a773202f.nq.gz
    ├── 14b10daf3a96229be87eed34c643e962a0d30450.nq.gz
    ├── 14e69fe16d85bc1bdc9246c70ade7b7d74a5dd3a.nq.gz
    ├── 14f70b05b4778f91137e4a9e7059d7514aa44d28.nq.gz
    ├── 15f09268a1d0ca1def1722cf971bf0a1e9a2927c.nq.gz
    ├── 15fa9d9157e7a1c075fec33e5bea49b44e1f7e0d.nq.gz
    ├── 162d089514b230b7531f069ad6157960a8ebd179.nq.gz
    ├── 1668b38304896c0c0a2bd51b31ea2bf48a79d952.nq.gz
    ├── 166d3b248c0bb92681fb4fd7e153b81a4e11e186.nq.gz
    ├── 1707eaddc9b0e542b39ce8a91328c5e88d43f104.nq.gz
    ├── 171cb23b675a71f0d8fb07617da7605933683d0a.nq.gz
    ├── 17264d8c507a38b74d915eca41efdfd3275dadcd.nq.gz
    ├── 1748fbdaaef1f80974c43b7815cb806389b8cb98.nq.gz
    ├── 176fed4ae4d2c3b8728b7b24d4e30070b6fe180e.nq.gz
    ├── 1798fa9e746477391d800545bd37975e55d423f4.nq.gz
    ├── 184b53bdf01501f772c5c1f169a069b691b038fc.nq.gz
    ├── 184edbbe9b8f7b49b1e31159649994f90ecef95e.nq.gz
    ├── 18891ce8c18b5896eaa12c76b345d98c2bd6f39a.nq.gz
    ├── 18f718f1cf8e87caf6f50418ae0a2bbdee753358.nq.gz
    ├── 1963f853f53d74ed1c24ea5badf86c1f7968b700.nq.gz
    ├── 1966513c181c5d34366fec1d0cf4e94e1a77b5c5.nq.gz
    ├── 199ca80179cec7d444099f84df39c6fb1df89a65.nq.gz
    ├── 1a296b6844a246ddb51db276bd5578667eb29623.nq.gz
    ├── 1b162792096e1c360314158f4b197545e4f30579.nq.gz
    ├── 1b6c1364213b990c716c39d7cc6427cb319cb948.nq.gz
    ├── 1b8c68222922db56fa1bea39703a8b623b1d9711.nq.gz
    ├── 1c90a211fbc4337b08734db0d2fd3de0f4eb0e21.nq.gz
    └── 1cb2703fc0f3b31532562b422ee4415bbfd0b76f.nq.gz

64 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
