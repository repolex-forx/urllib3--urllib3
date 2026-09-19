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
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│   │   │   └── chunk-001.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│   │   │   └── chunk-001.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│   │   │   └── chunk-001.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
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
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│   │   │   └── chunk-001.nq.gz
│   │   └── d9f85a749488188c286cd50606d159874db94d5f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
│   │   ├── 04df048cf4b1c3790c56e26c659db764aad62d6f.nq.gz
│   │   ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df.nq.gz
│   │   ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8.nq.gz
│   │   ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4.nq.gz
│   │   ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a.nq.gz
│   │   ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700.nq.gz
│   │   ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc.nq.gz
│   │   ├── 92196a0f08b2c2139117546ccfbdd3429eb72469.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7.nq.gz
│   │   ├── b234aaf7ccbcb64012d8b33d21eb8bc9f768935d.nq.gz
│   │   ├── b85e93d619a323b92c2954da852857e0119d71b8.nq.gz
│   │   ├── bfe8e198a13800e3ee8ef8124a8928acb170c843.nq.gz
│   │   ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0.nq.gz
│   │   └── d9f85a749488188c286cd50606d159874db94d5f.nq.gz
│   └── repolex
│       ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│       │   └── chunk-001.nq.gz
│       ├── 04df048cf4b1c3790c56e26c659db764aad62d6f
│       │   └── chunk-001.nq.gz
│       ├── 2458bfcd3dacdf6c196e98d077fc6bb02a5fc1df
│       │   └── chunk-001.nq.gz
│       ├── 262e3e332209ee93ff70e2b13502c8f20c105ac8
│       │   └── chunk-001.nq.gz
│       ├── 27e2a5c5a7ab6a517252cc8dcef3ffa6ffb8f61a
│       │   └── chunk-001.nq.gz
│       ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│       │   └── chunk-001.nq.gz
│       ├── 54d6edf2a671510a5c029d3b76ffe71a5b07147a
│       │   └── chunk-001.nq.gz
│       ├── 56f01e088dc006c03d4ee6ea9da4ab810f1ed700
│       │   └── chunk-001.nq.gz
│       ├── 69be2992f8a25a1f27e49f339e4d5b98dec07462
│       │   └── chunk-001.nq.gz
│       ├── 720f484b605f18887a48eef448d0084e2b76902d
│       │   └── chunk-001.nq.gz
│       ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│       │   └── chunk-001.nq.gz
│       ├── 92196a0f08b2c2139117546ccfbdd3429eb72469
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
│       ├── c9fa144545eedb5dc4a2cc3f255e95602a1d7db0
│       │   └── chunk-001.nq.gz
│       └── d9f85a749488188c286cd50606d159874db94d5f
│           └── chunk-001.nq.gz
└── blob
    ├── 005467cec04f2ebe46d350c07976ae4d8a047a64.nq.gz
    ├── 0079d14e98119a2c0ee1ee8a77ac937a509dc4f7.nq.gz
    ├── 0084df476a6f661c46e005ff80c844660264c0ff.nq.gz
    ├── 0089cd27e05062cd94398a9d7ae8e9a479f8f919.nq.gz
    ├── 0097179fb49c5e3a920d2f3b161799ae50002eab.nq.gz
    ├── 00c0a1b8b82c4b242a586bd8f3c9bb71c0f6ad05.nq.gz
    ├── 0129dda7c2bb3ddbf89d2a09960252a4fc8f5354.nq.gz
    ├── 016484d2971840524515b85cb2bc04494c471797.nq.gz
    ├── 02b2f622a1b1cfca660f602ba13913530e21992e.nq.gz
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
    ├── 083854d1b04810e174b31fe2cd087401d3065597.nq.gz
    ├── 085d1dbafdb3d8141523b2b0e93fdd26845e3aa0.nq.gz
    ├── 095cf3c16b9debf6bd3f77e75e26b0ab9c2a7612.nq.gz
    ├── 09b08eeb0591d9229114dda04eae217b7a8eb19c.nq.gz
    ├── 0a026da0a8357e324ded47b82b24042713b9bf06.nq.gz
    ├── 0a4573e7d9848499cd86450bed8721936333c058.nq.gz
    ├── 0ab1b3a2453a06370d01cd6411c446d3efb1409f.nq.gz
    ├── 0b3d7a1fe47d66d96bd6fc783e809f594d34c55d.nq.gz
    ├── 0c1e79347adc04c250d14863fb862f2d1b002f55.nq.gz
    ├── 0c46aa1dd3a9ab4186bd576caed3daf02c129597.nq.gz
    ├── 0d41bf1fa681c485a846d41c9efb5c5e9f9303cc.nq.gz
    ├── 0ec62457d2436a72fb0830fafde6e06f60697b6f.nq.gz
    ├── 0eeb93f7396ebc3aca4979ec8a6721b483ca5a7e.nq.gz
    ├── 0f1586336432ff13b67fa05c7c14cbab4343ef0d.nq.gz
    ├── 0f4578696fa2e17a900c6890ec26d65e860b0b72.nq.gz
    ├── 0f4e5cc581c63cbacb0d2b8cc5342df0b3f6abd0.nq.gz
    ├── 0f7e24c26422d97993b99d2b48deb0a62bc3960a.nq.gz
    ├── 0ff7ddb2a1412a7e3b6b8d2bd4f00c62d9e8c099.nq.gz
    ├── 10109fa917e9f0c265cde007f615102b82fbde2f.nq.gz
    ├── 105837dbfaaece95c44fe9f843d4cb17f784e917.nq.gz
    ├── 107c5e0af7989bcdf062c9854e875a76c290443d.nq.gz
    ├── 10b2f2baf841fe7e355ead4979ccca605a16921d.nq.gz
    ├── 10dad117669d33f4ddd09880e52846a9d284682e.nq.gz
    ├── 11785fa5852a87f74b1cb264285bb23b61566388.nq.gz
    ├── 11beb3dfefb7e92c2e37440bd2a29809657d5f47.nq.gz
    ├── 12097ea9c20698dff1b56d8d100f8a3267a33655.nq.gz
    ├── 12c0055493a2a40c69ede93d799ac832d90830bd.nq.gz
    ├── 133579fc1144f81598224ae162c66c18d0dd063b.nq.gz
    ├── 133e1d8f237f6fddd557ae1c0e0cf738f7cc2748.nq.gz
    ├── 138f99abbec0569cbf596adaccb4f1c74ba56db3.nq.gz
    ├── 13dd6fd2f95bcbdfade647afea950a8081b3f16e.nq.gz
    ├── 1407431a5c56ba093554072f6137a8da08100dd5.nq.gz
    ├── 140ca9fb6738be217c8a24b02e658888c00d2753.nq.gz
    ├── 14324fecb26bbfdfbfe31344463ba34e8aa443cf.nq.gz
    ├── 1442827def8e5732518d616349fe53dc8a61c6d3.nq.gz
    ├── 1492c952c4da14b16599eb8f0c860efcda960a85.nq.gz
    ├── 14f70b05b4778f91137e4a9e7059d7514aa44d28.nq.gz
    ├── 15fa9d9157e7a1c075fec33e5bea49b44e1f7e0d.nq.gz
    ├── 162d089514b230b7531f069ad6157960a8ebd179.nq.gz
    ├── 1668b38304896c0c0a2bd51b31ea2bf48a79d952.nq.gz
    ├── 17264d8c507a38b74d915eca41efdfd3275dadcd.nq.gz
    ├── 1748fbdaaef1f80974c43b7815cb806389b8cb98.nq.gz
    ├── 176fed4ae4d2c3b8728b7b24d4e30070b6fe180e.nq.gz
    ├── 184b53bdf01501f772c5c1f169a069b691b038fc.nq.gz
    ├── 184edbbe9b8f7b49b1e31159649994f90ecef95e.nq.gz
    ├── 18891ce8c18b5896eaa12c76b345d98c2bd6f39a.nq.gz
    ├── 1963f853f53d74ed1c24ea5badf86c1f7968b700.nq.gz
    ├── 199ca80179cec7d444099f84df39c6fb1df89a65.nq.gz
    ├── 1b162792096e1c360314158f4b197545e4f30579.nq.gz
    ├── 1b6c1364213b990c716c39d7cc6427cb319cb948.nq.gz
    ├── 1b8c68222922db56fa1bea39703a8b623b1d9711.nq.gz
    ├── 1c90a211fbc4337b08734db0d2fd3de0f4eb0e21.nq.gz
    ├── 1cb2703fc0f3b31532562b422ee4415bbfd0b76f.nq.gz
    ├── 1ced0d9fe25b3f2387dbcbafb8a07ac9ec2fd162.nq.gz
    ├── 1d0f3465adf51558bd3b5111aad11fd4fc189433.nq.gz
    ├── 1d94fceb712728e787c25943154a3259434bbdc6.nq.gz
    ├── 1d9d0bbdb6270260743dde03934141cb50d271d8.nq.gz
    ├── 1df677de8faa70ea0660941b0e2049cd9a2474c9.nq.gz
    ├── 1e0bf37b33dc1ee5ef8783a3451584bb6812e9b2.nq.gz
    ├── 1e5f448cd41bb12f5254d1aca3a6cfa60904a15c.nq.gz
    ├── 1e62c926ed74af84cf3078863f552d5d1e745627.nq.gz
    ├── 1f05b262437ec6736d7b7f5ae8536fd64261740b.nq.gz
    ├── 1f7365b55b1e8cf266a066092b5c90b6716efef0.nq.gz
    ├── 1fe82937ac98c3d0b349ae8eb26a859acc018348.nq.gz
    ├── 200f140ce39ca9fac6b4850fa448f59abca892c0.nq.gz
    ├── 202915ce88dc0ab5530bbad6d4befeb5e620f8d0.nq.gz
    ├── 208073e203ad404bf1aa99362bd0f4fc56ca5927.nq.gz
    ├── 214f4dababe1c1d6ecb6c0a79fc4400d75e3560e.nq.gz
    ├── 219b5d9894ceffed0a90090ff602040538a5af2f.nq.gz
    ├── 23413f5a85c4e2c3249cb05c7a99adb08a90b3d8.nq.gz
    ├── 23605c522b85f940f3af4db2e0561c48b0b0d269.nq.gz
    ├── 24026c367a25843098ec8ef2316b4975f83fcf5c.nq.gz
    ├── 24263dc52f93b3566ecbb9fa68d6c3814a55bb98.nq.gz
    ├── 243b86222f90a9be4b6b4ce0bf997eefd29289af.nq.gz
    ├── 2442c8ad2d7d03cb6e1ca7c303db474ea424698e.nq.gz
    ├── 244d9ef49cc9882627e97a3b984b667bc6389989.nq.gz
    ├── 2479405bd59dc291562b7cdf731d90fb2767c3c8.nq.gz
    ├── 25b633af257f20c87424ec8a341cbd6f5797b804.nq.gz
    ├── 25d91000419ea4a860f511ebe669fe171b79254c.nq.gz
    ├── 2683c9ec620e29f18c9e5dbf61486eb67c7521ed.nq.gz
    ├── 268f79f0dc110e4dd7c2dd0bf3df0c5f9fd71802.nq.gz
    ├── 26a877a07e4b101385a79d6adbd4ddede9193a55.nq.gz
    ├── 2714f1056d52443c374980d2a04df995bd207889.nq.gz
    ├── 278128ebd7c9c053631aecdd78135ab2c1baca92.nq.gz
    ├── 27df7a1aa596bebb5e01f2783493747a809ae0fb.nq.gz
    ├── 27e0fa51498a20f33629f70c2da99fe0c8f9a018.nq.gz
    ├── 27f119e63495f92083df00e0efc02380da52162e.nq.gz
    ├── 281e4114b52d63edc4f350c765a1664d02881512.nq.gz
    ├── 2878cc8d8b6b5c2d915aaa95450427c2940b7cba.nq.gz
    ├── 28ec82f0168543a8aee7cdb79a4b46f10bb2cc91.nq.gz
    ├── 2968669fabb9f4df7f4f6404532fdfc950084fb6.nq.gz
    ├── 297c271bf401c1cb48c6225f8822e78f58c3ca56.nq.gz
    ├── 29ca334879a9561da85feee31750f69904c0dd97.nq.gz
    ├── 29f3786e2792111b4a498b7b028ebd10086d338e.nq.gz
    ├── 2a057441600b68bef13c6dcee205607e04001627.nq.gz
    ├── 2a7a0387b4dea7d1cd4c720fd98e59e94f6fd93f.nq.gz
    ├── 2a9841d9d86e1f0e8be1f872e25d0e424b4ffc70.nq.gz
    ├── 2b33cc9c28164e4b95f23335e1516e46754e6531.nq.gz
    ├── 2bb46d737bc65aa6546f34bb53d5f7d89fed34b0.nq.gz
    ├── 2ceb4579eb549cbd22398e5a7d81130b981d824c.nq.gz
    ├── 2ceeb0a5483bef1927a57d03c3dd2cab0d8c9f8f.nq.gz
    ├── 2d0d43089692080c2268333381c138936ff2aeb7.nq.gz
    ├── 2de9f016372716a00110bd7d0d2df8dfb2de9180.nq.gz
    ├── 2fa25a91ab07b7ea024170f855eae229eaebedf6.nq.gz
    ├── 303b4ee0117d45f0f47aa1c7a6e4fcf594665a9a.nq.gz
    ├── 30fc163aed5909b9954558215acc3c775379ffdb.nq.gz
    ├── 319accb2234174fcc5b1a2fb01d6fa677c881e95.nq.gz
    ├── 322ca26fb96c8b0a4c03b89629784f1219e77cc9.nq.gz
    ├── 32c1f0025f0205192e3962e0d4633ef38fd8d2de.nq.gz
    ├── 32cd60b64606faad8e7f1827905526a019adcfb1.nq.gz
    ├── 32da0a00ab7b6eb0c077926e508cdab6ca18b8e2.nq.gz
    ├── 3314b903ae0a35d5dff537f3a12312051f06dd87.nq.gz
    ├── 33e9ce7f33357cbd8e1c6cb5af49f4b70020079c.nq.gz
    ├── 33f567e4d5136dbedf0137f7b1bdbf296d63781d.nq.gz
    ├── 355cb0ff855e120f8cffb7686a4e449fac1f6e23.nq.gz
    ├── 355cd2258cd78fd48aadd5708e8914d7c22ff9e4.nq.gz
    ├── 356be2d94d033d53b3941a9b851ead569c2617d7.nq.gz
    ├── 35c77e4025842f548565334a3c04cba90f9283d6.nq.gz
    └── 35fb1991647ff8d3d1bc4583f8dca78f634a44c9.nq.gz

44 directories, 200 files
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
