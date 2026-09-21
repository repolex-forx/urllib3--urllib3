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
│   │   ├── 21758b0694ea53b499e832a993e8d1ada01135b2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│   │   │   └── chunk-001.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2a57bc5758075a9248cc0d87f66a2ff678338478
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 342aff50ff300d96a58e9be22f27fcee771ce98d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 361f1e2a61afdef86cb2feb0fa3f302e06c5fe2c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3c3fb0299f5e56613003bc293a9a9082e264c982
│   │   │   └── chunk-001.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│   │   │   └── chunk-001.nq.gz
│   │   ├── 612cead3f9704716f4ab2a1334a16e0f05fce942
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6446fef0cf432ca035169602a1447a0d8ef53e80
│   │   │   └── chunk-001.nq.gz
│   │   ├── 64b7f792c8ab62e301147d4115c4bca98529593a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6de3330eb54f73a57c7860f75123bde8b043dbd2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387
│   │   │   └── chunk-001.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
│   │   │   └── chunk-001.nq.gz
│   │   ├── 95ca35211d23d8baf7646e1f60aa31e3650178a8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 969fd3957a652ebe90bfe60483a478ad8b88f44a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9b95f29c575d73260ec4f5a8c0ea368cf242019e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5b29ac1025f9bb30f2c9b756f3b171389c2c039
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── a8913042b676c510e94fc2b097f6b514ae11a537
│   │   │   └── chunk-001.nq.gz
│   │   ├── aa3def7d242525e6e854991247c4b68583d15135
│   │   │   └── chunk-001.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│   │   │   └── chunk-001.nq.gz
│   │   ├── ac61b73da703df53707c31030b4ea51aab22d43c
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1f60e44d43b13e5272d5b6003f125af9c25c8ad
│   │   │   └── chunk-001.nq.gz
│   │   ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d
│   │   │   └── chunk-001.nq.gz
│   │   ├── b85e93d619a323b92c2954da852857e0119d71b8
│   │   │   └── chunk-001.nq.gz
│   │   ├── ba95e9eac73452d3bccfb5413b00d9a4fe3e4c31
│   │   │   └── chunk-001.nq.gz
│   │   ├── bfe8e198a13800e3ee8ef8124a8928acb170c843
│   │   │   └── chunk-001.nq.gz
│   │   ├── c479b73ba6114c0ec1010db86f6eb193fe874c84
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9016bf464751a02b7e46f8b86504f47d4238784
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│   │   │   └── chunk-001.nq.gz
│   │   ├── d1616473df94b94f0f5ad19d2a6608cfe93b7cdf
│   │   │   └── chunk-001.nq.gz
│   │   ├── d94029b7e2193ff47b627906a70e06377a09aae8
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9d85c88aa644af56d5e129634e750ce76e1a765
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9f85a749488188c286cd50606d159874db94d5f
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd00949dbded99869981880270d3ec900989e82b
│   │   │   └── chunk-001.nq.gz
│   │   ├── ddb8c96bd93f3a00fe9eba142e6739533c2b7164
│   │   │   └── chunk-001.nq.gz
│   │   └── f96a1cfc568beddf1e17ce7609609eca40780be5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
│   │   ├── 04df048cf4b1c3790c56e26c659db764aad62d6f.nq.gz
│   │   ├── 1af920653cfed1920a576e80cc7a856fe4df2ac9.nq.gz
│   │   ├── 21758b0694ea53b499e832a993e8d1ada01135b2.nq.gz
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a.nq.gz
│   │   ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a.nq.gz
│   │   ├── 2a57bc5758075a9248cc0d87f66a2ff678338478.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4.nq.gz
│   │   ├── 342aff50ff300d96a58e9be22f27fcee771ce98d.nq.gz
│   │   ├── 361f1e2a61afdef86cb2feb0fa3f302e06c5fe2c.nq.gz
│   │   ├── 3c3fb0299f5e56613003bc293a9a9082e264c982.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700.nq.gz
│   │   ├── 612cead3f9704716f4ab2a1334a16e0f05fce942.nq.gz
│   │   ├── 6446fef0cf432ca035169602a1447a0d8ef53e80.nq.gz
│   │   ├── 64b7f792c8ab62e301147d4115c4bca98529593a.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462.nq.gz
│   │   ├── 6de3330eb54f73a57c7860f75123bde8b043dbd2.nq.gz
│   │   ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469.nq.gz
│   │   ├── 95ca35211d23d8baf7646e1f60aa31e3650178a8.nq.gz
│   │   ├── 969fd3957a652ebe90bfe60483a478ad8b88f44a.nq.gz
│   │   ├── 9b95f29c575d73260ec4f5a8c0ea368cf242019e.nq.gz
│   │   ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b.nq.gz
│   │   ├── a5b29ac1025f9bb30f2c9b756f3b171389c2c039.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc.nq.gz
│   │   ├── a8913042b676c510e94fc2b097f6b514ae11a537.nq.gz
│   │   ├── aa3def7d242525e6e854991247c4b68583d15135.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7.nq.gz
│   │   ├── ac61b73da703df53707c31030b4ea51aab22d43c.nq.gz
│   │   ├── b1f60e44d43b13e5272d5b6003f125af9c25c8ad.nq.gz
│   │   ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d.nq.gz
│   │   ├── b85e93d619a323b92c2954da852857e0119d71b8.nq.gz
│   │   ├── ba95e9eac73452d3bccfb5413b00d9a4fe3e4c31.nq.gz
│   │   ├── bfe8e198a13800e3ee8ef8124a8928acb170c843.nq.gz
│   │   ├── c479b73ba6114c0ec1010db86f6eb193fe874c84.nq.gz
│   │   ├── c9016bf464751a02b7e46f8b86504f47d4238784.nq.gz
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0.nq.gz
│   │   ├── d1616473df94b94f0f5ad19d2a6608cfe93b7cdf.nq.gz
│   │   ├── d94029b7e2193ff47b627906a70e06377a09aae8.nq.gz
│   │   ├── d9d85c88aa644af56d5e129634e750ce76e1a765.nq.gz
│   │   ├── d9f85a749488188c286cd50606d159874db94d5f.nq.gz
│   │   ├── dd00949dbded99869981880270d3ec900989e82b.nq.gz
│   │   ├── ddb8c96bd93f3a00fe9eba142e6739533c2b7164.nq.gz
│   │   └── f96a1cfc568beddf1e17ce7609609eca40780be5.nq.gz
│   └── repolex
│       ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│       │   └── chunk-001.nq.gz
│       ├── 04df048cf4b1c3790c56e26c659db764aad62d6f
│       │   └── chunk-001.nq.gz
│       ├── 1af920653cfed1920a576e80cc7a856fe4df2ac9
│       │   └── chunk-001.nq.gz
│       ├── 21758b0694ea53b499e832a993e8d1ada01135b2
│       │   └── chunk-001.nq.gz
│       ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│       │   └── chunk-001.nq.gz
│       ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│       │   └── chunk-001.nq.gz
│       ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│       │   └── chunk-001.nq.gz
│       ├── 2889596e309d30220d1f4ef2e80d4a92a906fa0a
│       │   └── chunk-001.nq.gz
│       ├── 2a57bc5758075a9248cc0d87f66a2ff678338478
│       │   └── chunk-001.nq.gz
│       ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│       │   └── chunk-001.nq.gz
│       ├── 342aff50ff300d96a58e9be22f27fcee771ce98d
│       │   └── chunk-001.nq.gz
│       ├── 361f1e2a61afdef86cb2feb0fa3f302e06c5fe2c
│       │   └── chunk-001.nq.gz
│       ├── 3c3fb0299f5e56613003bc293a9a9082e264c982
│       │   └── chunk-001.nq.gz
│       ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│       │   └── chunk-001.nq.gz
│       ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│       │   └── chunk-001.nq.gz
│       ├── 612cead3f9704716f4ab2a1334a16e0f05fce942
│       │   └── chunk-001.nq.gz
│       ├── 6446fef0cf432ca035169602a1447a0d8ef53e80
│       │   └── chunk-001.nq.gz
│       ├── 64b7f792c8ab62e301147d4115c4bca98529593a
│       │   └── chunk-001.nq.gz
│       ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│       │   └── chunk-001.nq.gz
│       ├── 6de3330eb54f73a57c7860f75123bde8b043dbd2
│       │   └── chunk-001.nq.gz
│       ├── 6f2ad7ca0cdde53751bab29cbc10bcc965bb4387
│       │   └── chunk-001.nq.gz
│       ├── 720f484b605f18887a48eef448d0084e2b76902d
│       │   └── chunk-001.nq.gz
│       ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│       │   └── chunk-001.nq.gz
│       ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
│       │   └── chunk-001.nq.gz
│       ├── 95ca35211d23d8baf7646e1f60aa31e3650178a8
│       │   └── chunk-001.nq.gz
│       ├── 969fd3957a652ebe90bfe60483a478ad8b88f44a
│       │   └── chunk-001.nq.gz
│       ├── 9b95f29c575d73260ec4f5a8c0ea368cf242019e
│       │   └── chunk-001.nq.gz
│       ├── 9c2c2307dd1d6af504e09aac0326d86ee3597a0b
│       │   └── chunk-001.nq.gz
│       ├── a5b29ac1025f9bb30f2c9b756f3b171389c2c039
│       │   └── chunk-001.nq.gz
│       ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│       │   └── chunk-001.nq.gz
│       ├── a8913042b676c510e94fc2b097f6b514ae11a537
│       │   └── chunk-001.nq.gz
│       ├── aa3def7d242525e6e854991247c4b68583d15135
│       │   └── chunk-001.nq.gz
│       ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│       │   └── chunk-001.nq.gz
│       ├── ac61b73da703df53707c31030b4ea51aab22d43c
│       │   └── chunk-001.nq.gz
│       ├── b1f60e44d43b13e5272d5b6003f125af9c25c8ad
│       │   └── chunk-001.nq.gz
│       ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d
│       │   └── chunk-001.nq.gz
│       ├── b85e93d619a323b92c2954da852857e0119d71b8
│       │   └── chunk-001.nq.gz
│       ├── ba95e9eac73452d3bccfb5413b00d9a4fe3e4c31
│       │   └── chunk-001.nq.gz
│       ├── bfe8e198a13800e3ee8ef8124a8928acb170c843
│       │   └── chunk-001.nq.gz
│       ├── c479b73ba6114c0ec1010db86f6eb193fe874c84
│       │   └── chunk-001.nq.gz
│       ├── c9016bf464751a02b7e46f8b86504f47d4238784
│       │   └── chunk-001.nq.gz
│       ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│       │   └── chunk-001.nq.gz
│       ├── d1616473df94b94f0f5ad19d2a6608cfe93b7cdf
│       │   └── chunk-001.nq.gz
│       ├── d94029b7e2193ff47b627906a70e06377a09aae8
│       │   └── chunk-001.nq.gz
│       ├── d9d85c88aa644af56d5e129634e750ce76e1a765
│       │   └── chunk-001.nq.gz
│       ├── d9f85a749488188c286cd50606d159874db94d5f
│       │   └── chunk-001.nq.gz
│       ├── dd00949dbded99869981880270d3ec900989e82b
│       │   └── chunk-001.nq.gz
│       ├── ddb8c96bd93f3a00fe9eba142e6739533c2b7164
│       │   └── chunk-001.nq.gz
│       └── f96a1cfc568beddf1e17ce7609609eca40780be5
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
    ├── 013699f8226a3ac9b2a5ca4e279c26b0c899cd81.nq.gz
    ├── 016484d2971840524515b85cb2bc04494c471797.nq.gz
    ├── 019d1511d56b977ac3b396100d2d3ce353acea45.nq.gz
    ├── 01f02738d0ecc489a58abfdc16603a41e13cb534.nq.gz
    ├── 01f08eee80e52f42c19e3967d0e6545ca89a0dc6.nq.gz
    ├── 0235aab323d27ad0e38e3bd708bde269fc34afad.nq.gz
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
    ├── 03f2780c754d15c2550ee2f29f0f88928a67cb3c.nq.gz
    ├── 0456cceba47b16ae6784458cc17eaa528a517ffa.nq.gz
    ├── 04a94c2bca8e1d69ce27fc38cf4d4988b8a51e58.nq.gz
    ├── 04a97a88700ebe51c170ebbf214e5e4183307fde.nq.gz
    ├── 04e65f8cd4a1e1ce402a61cb4b316b45059135ab.nq.gz
    ├── 05bfefe74cbbb3db1dd715199124135482fef160.nq.gz
    ├── 05cac9ca0ed0eee09ec0d663aaae321130bc1046.nq.gz
    ├── 0603236e971d83f490725350f8830f3e48d42ad7.nq.gz
    ├── 06167207c25060aec713b2dcbbbccf90a79f9045.nq.gz
    ├── 069aa198709cccbed3e3bce49016a6dc20d0fc8c.nq.gz
    ├── 069cd2742cf51f2c619386d7efacecbfc6459b65.nq.gz
    ├── 069f726cb85a5e3722f974adf8d5a617f9fef4a9.nq.gz
    ├── 06db4a0e186920bc84a8fce3a52d369ba73528c5.nq.gz
    ├── 081877b1374dee09a91aa56c7498f5a2915f290f.nq.gz
    ├── 08277e97e0c93ede67e6730e3fe50846e610f9f2.nq.gz
    ├── 083854d1b04810e174b31fe2cd087401d3065597.nq.gz
    ├── 0855f00a2a370c229ba8fa16584863876c98d9ed.nq.gz
    ├── 085d1dbafdb3d8141523b2b0e93fdd26845e3aa0.nq.gz
    ├── 0872ed770117096a8decf02e099a5c4148e018f3.nq.gz
    ├── 09024d4798c748c7e13b5d82b715c580d0df013f.nq.gz
    ├── 095cf3c16b9debf6bd3f77e75e26b0ab9c2a7612.nq.gz
    ├── 09b08eeb0591d9229114dda04eae217b7a8eb19c.nq.gz
    ├── 09cfa1c7840b1518df27c1d629f2bbc4e7b106dc.nq.gz
    ├── 0a026da0a8357e324ded47b82b24042713b9bf06.nq.gz
    ├── 0a4573e7d9848499cd86450bed8721936333c058.nq.gz
    ├── 0a5eb6616406ac491e09b377a0c40c326ccdde01.nq.gz
    ├── 0a74c79b5eaa972c895d3e857f02ced555c5d792.nq.gz
    └── 0ab1b3a2453a06370d01cd6411c446d3efb1409f.nq.gz

104 directories, 200 files
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
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
