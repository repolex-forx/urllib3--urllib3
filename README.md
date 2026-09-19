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
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│   │   │   └── chunk-001.nq.gz
│   │   └── bfe8e198a13800e3ee8ef8124a8928acb170c843
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc.nq.gz
│   │   ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4.nq.gz
│   │   ├── 720f484b605f18887a48eef448d0084e2b76902d.nq.gz
│   │   ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc.nq.gz
│   │   ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc.nq.gz
│   │   ├── aaab4eccc10c965897540b21e15f11859d0b62e7.nq.gz
│   │   └── bfe8e198a13800e3ee8ef8124a8928acb170c843.nq.gz
│   └── repolex
│       ├── 0248277dd7ac0239204889ca991353ad3e3a1ddc
│       │   └── chunk-001.nq.gz
│       ├── 2f68c5363ef632d73dd4d9300289d7ce5ff275b4
│       │   └── chunk-001.nq.gz
│       ├── 720f484b605f18887a48eef448d0084e2b76902d
│       │   └── chunk-001.nq.gz
│       ├── 83f8643ffb5b7f197457379148e2fa118ab0fcdc
│       │   └── chunk-001.nq.gz
│       ├── a5ff7ac3bbb8659e2ec3ed41dd43889f06a7d7bc
│       │   └── chunk-001.nq.gz
│       ├── aaab4eccc10c965897540b21e15f11859d0b62e7
│       │   └── chunk-001.nq.gz
│       └── bfe8e198a13800e3ee8ef8124a8928acb170c843
│           └── chunk-001.nq.gz
└── blob
    ├── 005467cec04f2ebe46d350c07976ae4d8a047a64.nq.gz
    ├── 0079d14e98119a2c0ee1ee8a77ac937a509dc4f7.nq.gz
    ├── 0084df476a6f661c46e005ff80c844660264c0ff.nq.gz
    ├── 0097179fb49c5e3a920d2f3b161799ae50002eab.nq.gz
    ├── 00c0a1b8b82c4b242a586bd8f3c9bb71c0f6ad05.nq.gz
    ├── 0129dda7c2bb3ddbf89d2a09960252a4fc8f5354.nq.gz
    ├── 016484d2971840524515b85cb2bc04494c471797.nq.gz
    ├── 0378aab1b1aba0b61cb2741156dea652591ca2bf.nq.gz
    ├── 0394578287c19042344f338c896c1178ba81fbd6.nq.gz
    ├── 03a1992df71dad49a558356502d3dd99a0a84064.nq.gz
    ├── 03cda714f66f7aba4278c0ae43158c508909a1ce.nq.gz
    ├── 0456cceba47b16ae6784458cc17eaa528a517ffa.nq.gz
    ├── 04a94c2bca8e1d69ce27fc38cf4d4988b8a51e58.nq.gz
    ├── 06167207c25060aec713b2dcbbbccf90a79f9045.nq.gz
    ├── 069aa198709cccbed3e3bce49016a6dc20d0fc8c.nq.gz
    ├── 069f726cb85a5e3722f974adf8d5a617f9fef4a9.nq.gz
    ├── 081877b1374dee09a91aa56c7498f5a2915f290f.nq.gz
    ├── 083854d1b04810e174b31fe2cd087401d3065597.nq.gz
    ├── 085d1dbafdb3d8141523b2b0e93fdd26845e3aa0.nq.gz
    ├── 09b08eeb0591d9229114dda04eae217b7a8eb19c.nq.gz
    ├── 0a026da0a8357e324ded47b82b24042713b9bf06.nq.gz
    ├── 0a4573e7d9848499cd86450bed8721936333c058.nq.gz
    ├── 0ab1b3a2453a06370d01cd6411c446d3efb1409f.nq.gz
    ├── 0b3d7a1fe47d66d96bd6fc783e809f594d34c55d.nq.gz
    ├── 0c1e79347adc04c250d14863fb862f2d1b002f55.nq.gz
    ├── 0ec62457d2436a72fb0830fafde6e06f60697b6f.nq.gz
    ├── 0eeb93f7396ebc3aca4979ec8a6721b483ca5a7e.nq.gz
    ├── 0f4578696fa2e17a900c6890ec26d65e860b0b72.nq.gz
    ├── 107c5e0af7989bcdf062c9854e875a76c290443d.nq.gz
    ├── 11785fa5852a87f74b1cb264285bb23b61566388.nq.gz
    ├── 133e1d8f237f6fddd557ae1c0e0cf738f7cc2748.nq.gz
    ├── 13dd6fd2f95bcbdfade647afea950a8081b3f16e.nq.gz
    ├── 1407431a5c56ba093554072f6137a8da08100dd5.nq.gz
    ├── 140ca9fb6738be217c8a24b02e658888c00d2753.nq.gz
    ├── 1492c952c4da14b16599eb8f0c860efcda960a85.nq.gz
    ├── 14f70b05b4778f91137e4a9e7059d7514aa44d28.nq.gz
    ├── 162d089514b230b7531f069ad6157960a8ebd179.nq.gz
    ├── 176fed4ae4d2c3b8728b7b24d4e30070b6fe180e.nq.gz
    ├── 184edbbe9b8f7b49b1e31159649994f90ecef95e.nq.gz
    ├── 1b6c1364213b990c716c39d7cc6427cb319cb948.nq.gz
    ├── 1cb2703fc0f3b31532562b422ee4415bbfd0b76f.nq.gz
    ├── 1d9d0bbdb6270260743dde03934141cb50d271d8.nq.gz
    ├── 1df677de8faa70ea0660941b0e2049cd9a2474c9.nq.gz
    ├── 1e62c926ed74af84cf3078863f552d5d1e745627.nq.gz
    ├── 1f05b262437ec6736d7b7f5ae8536fd64261740b.nq.gz
    ├── 200f140ce39ca9fac6b4850fa448f59abca892c0.nq.gz
    ├── 219b5d9894ceffed0a90090ff602040538a5af2f.nq.gz
    ├── 23413f5a85c4e2c3249cb05c7a99adb08a90b3d8.nq.gz
    ├── 23605c522b85f940f3af4db2e0561c48b0b0d269.nq.gz
    ├── 24026c367a25843098ec8ef2316b4975f83fcf5c.nq.gz
    ├── 243b86222f90a9be4b6b4ce0bf997eefd29289af.nq.gz
    ├── 244d9ef49cc9882627e97a3b984b667bc6389989.nq.gz
    ├── 25d91000419ea4a860f511ebe669fe171b79254c.nq.gz
    ├── 26a877a07e4b101385a79d6adbd4ddede9193a55.nq.gz
    ├── 278128ebd7c9c053631aecdd78135ab2c1baca92.nq.gz
    ├── 281e4114b52d63edc4f350c765a1664d02881512.nq.gz
    ├── 28ec82f0168543a8aee7cdb79a4b46f10bb2cc91.nq.gz
    ├── 2968669fabb9f4df7f4f6404532fdfc950084fb6.nq.gz
    ├── 297c271bf401c1cb48c6225f8822e78f58c3ca56.nq.gz
    ├── 2ceeb0a5483bef1927a57d03c3dd2cab0d8c9f8f.nq.gz
    ├── 2de9f016372716a00110bd7d0d2df8dfb2de9180.nq.gz
    ├── 30fc163aed5909b9954558215acc3c775379ffdb.nq.gz
    ├── 322ca26fb96c8b0a4c03b89629784f1219e77cc9.nq.gz
    ├── 32cd60b64606faad8e7f1827905526a019adcfb1.nq.gz
    ├── 33e9ce7f33357cbd8e1c6cb5af49f4b70020079c.nq.gz
    ├── 33f567e4d5136dbedf0137f7b1bdbf296d63781d.nq.gz
    ├── 355cb0ff855e120f8cffb7686a4e449fac1f6e23.nq.gz
    ├── 35c77e4025842f548565334a3c04cba90f9283d6.nq.gz
    ├── 35fb1991647ff8d3d1bc4583f8dca78f634a44c9.nq.gz
    ├── 36d7ed5dd63b7219e5606f37cc0c5bb5208d84c1.nq.gz
    ├── 36f599d7b410b2ec2a3df36eddea9c7eb2a12e8e.nq.gz
    ├── 3714500ec2e1c104b92dff1bb8f7244b8b458ed8.nq.gz
    ├── 3721274571739c849bdc488fa5e23c788b4ff1dc.nq.gz
    ├── 37a18aa6c6856d3a1e9e15cc9d6eee886c19c2bf.nq.gz
    ├── 39b1292fa4306411257ec4348ea6dea2b2bd070e.nq.gz
    ├── 3a0685b4cdd0562e508b9dd032765b5c759ea61e.nq.gz
    ├── 3ab4fcf3a52b336342c58ad9f2175b02a6e6a483.nq.gz
    ├── 3d16e7cd18f37ff40546659a7fb6d27657e7fe37.nq.gz
    ├── 3edab4d7728930514b5cc63bff84f6f245821665.nq.gz
    ├── 3ee127a02bbc3aa7734ec1d97714b4becfd24a16.nq.gz
    ├── 3eec0abaab600d8427038119eed1488223210e66.nq.gz
    ├── 3fe782c8a45bbabcf240f3cac4303ac12b0ec274.nq.gz
    ├── 41aa35b9d8a1bab25dd93949a8981d1619bed3cf.nq.gz
    ├── 41bfd2797ffeef54fa50f708026c4cc44b7d2c12.nq.gz
    ├── 43073cb2637813c9e7c8eede7f30b94d26731dfb.nq.gz
    ├── 445bc7e9ec77aec863370cf4bb196ec3a619a2b3.nq.gz
    ├── 453cfd420d835be58b5af581c3065e7b37079ecf.nq.gz
    ├── 45538a6ead65a57778776fa8f913ebb376eb32a2.nq.gz
    ├── 45dee02b8e9d4f189b1e7fe4a0a9249fddf70076.nq.gz
    ├── 46707571e62fc3484f670908e579fda493ec2d65.nq.gz
    ├── 4725e28b57bdc6bc1c151aacfafb9f7791f71036.nq.gz
    ├── 4872e5be7d3e05984aa756537909a94febffa970.nq.gz
    ├── 49c1b27c68216fe18f781d0c6fc34b2fb8337ab5.nq.gz
    ├── 4a932c0de46c9c53bbcb79ce35e1f659326ccee1.nq.gz
    ├── 4bb1be11d9cb06900dd82ecebd06aa6a7c5de916.nq.gz
    ├── 4d81060e5d533bab2af2be9e7b321c0d77d550ed.nq.gz
    ├── 4da6c59ac5a1b0ff76ae53a09e1e93bb641c8505.nq.gz
    ├── 4f0880d14f9e668c4472bc1b9c3548e01678eefa.nq.gz
    ├── 4ff003bde1f50a2d90fd4ac640c841bc09e4118e.nq.gz
    ├── 503f8e803f9d19a42d4b6969c92c76340e200752.nq.gz
    ├── 508136d1a572663fea70c040884e51faa53bd565.nq.gz
    ├── 52c754ee837526ec500bf91faa8fbc6f16df461b.nq.gz
    ├── 534126033c083203649022fa9b753a433f005556.nq.gz
    ├── 53b41c0a42594e78ad040ba1f6f03f8c5a822690.nq.gz
    ├── 5632dab3b2f93df91bf132384c3820a6b5518f43.nq.gz
    ├── 56fe9093adaa86b30085aef2435e49f84841df12.nq.gz
    ├── 5763fea808184690042cca497b3ac358f412c83f.nq.gz
    ├── 582b8f719fb71122f217516e635cafefa6e26402.nq.gz
    ├── 5863033cc702ea503ccba5d57fe8ed76236b108f.nq.gz
    ├── 58723faeb0ca7e5d8e3ba319f8d5acc79c91409c.nq.gz
    ├── 58e1c201670c3f6bd903e5da2ae6ffe263b36318.nq.gz
    ├── 591ac407bcf655610ca59e4aab4f87a9e32022bf.nq.gz
    ├── 592ee6bea21389ee3714892bd489cedc9b3d9861.nq.gz
    ├── 5b82e9329d88b6e993841b75c466fbcac2ccc913.nq.gz
    ├── 5c78c8af1c6fa7b509cde2bf932e75f1b0d8722d.nq.gz
    ├── 5e16c955323298437a0e6144ab0bce09cae555a3.nq.gz
    ├── 5e5e7dd4b0858a4258affbdc1942034608e907bd.nq.gz
    ├── 5f3ea3d919363f08ab03edbc85b6099bc4df5647.nq.gz
    ├── 5f7a73db70647b5aa82ca3f2649989f4af88d9e8.nq.gz
    ├── 6055fd2e72b015d5bbc6ea1780bbdd675bd79e9e.nq.gz
    ├── 60fce65dcc4a7fd2ce671886156afaa762fb310c.nq.gz
    ├── 612cfddc4c28d2f0edf47522278fa6d9b7906623.nq.gz
    ├── 620e2b1827845dbcfb4574ffefc835d0ac683361.nq.gz
    ├── 6321696dbbcb1a0ad9355a227eed53f94b2667a4.nq.gz
    ├── 6370ab1795c380b4b8642383f4b1778f83da49d3.nq.gz
    ├── 63f79dd3be803db09671c909f79316c3f65d6916.nq.gz
    ├── 647c6b82f2908903f5c185d292a343eb061c434f.nq.gz
    ├── 66958217a9fdc8a03eb991d6da2558d7e7910150.nq.gz
    ├── 66c6a687ec06e2da1028b94a0a32b2fcd3580e2b.nq.gz
    ├── 66e3ee5e9086c04d00fa905492afb3e2e423f82f.nq.gz
    ├── 6c2372ba7e777826a4eb124ddfb54f0240b65d67.nq.gz
    ├── 6cbf5a88f1f6095c6123e3150fc64a55255868f2.nq.gz
    ├── 6ceaabb4741320207a02ac71ec8df596a973ccf8.nq.gz
    ├── 6d59bc3bce2489c3a0aa5bcb83b737dcf33c033b.nq.gz
    ├── 6f16f2a430e5993afb915b2d0c2808b87194ffcf.nq.gz
    ├── 7000aa0817c869829c7b7cc717a9bd554f75d22e.nq.gz
    ├── 7011caabe68efd07d28443b76cd7f53f7b100574.nq.gz
    ├── 710b8fbd98a5bff1dca272b3231b031d386c0257.nq.gz
    ├── 733a0d323393e73cfc52dec1726dcd237151e8be.nq.gz
    ├── 750c17246170a785657dc636be26ab127dded340.nq.gz
    ├── 7534b770a87a666f0e6e6c586b5f2aadccbc3ed7.nq.gz
    ├── 76457e8e675945e857d750d2607b57668ce94a98.nq.gz
    ├── 767b463861525a2ba2e7d16f7eb3183c549c6024.nq.gz
    ├── 77904444b1c07b4214681f8199ea467a68e5be42.nq.gz
    ├── 77a3bb2a37f8d3c2718531bf22641d2ac26da8f6.nq.gz
    ├── 77c97312bdd52d43d78861d32aade71a566b95e7.nq.gz
    ├── 7c2377a4c33fb4bf46bf981aab80b016e697a838.nq.gz
    ├── 7f163ab330021aa468298be399bf2ca2cb73a622.nq.gz
    ├── 8082387d94b6559ca2a24126ac1511285389dc6f.nq.gz
    ├── 84603a7f6e7da3938c261a198fb8994744cf361a.nq.gz
    ├── 85206b90caa2ab73d31ae61d2635fbb81ddc73ac.nq.gz
    ├── 86e6661e729e506d651a606cf2742164a1a4e782.nq.gz
    ├── 8714bd7ac085b0ff6eb0e0f1522db07684626798.nq.gz
    ├── 89db60b422774beb03c6e7185760bfc8f227dd9e.nq.gz
    ├── 8a07a8effb7313f864b660e6f6e0853bf4636619.nq.gz
    ├── 8a3c5bebdc151eef715663628a697118bb2932ed.nq.gz
    ├── 8a4c410e33b39d37336ec787825ecf6ff202a819.nq.gz
    ├── 8b9ae652ccfa787ab96969f82930cd8d0205ae34.nq.gz
    ├── 8bd7b258bdfb94098bdde53a35bf55d200bae117.nq.gz
    ├── 8d36b1471b78ed8e617f57ae7e10a87a772a4cf3.nq.gz
    ├── 8d6107aea03915a62344b2e82228a8eb3535e811.nq.gz
    ├── 8e05d3d785d53021a97a713cbdbb1f43708c9150.nq.gz
    ├── 8ea10d80ec4f95ad1602273b0b64c18914740db9.nq.gz
    ├── 8f0c88065eb8c1a0e7181ffe40f6ca122c658d1c.nq.gz
    ├── 9082d90b94626bc0865f5ad4dcd795c521c821ae.nq.gz
    ├── 908fc6621d0afbed16bde2c1957a5cf28d3a84d8.nq.gz
    ├── 90a531fefb2b880f8a4593ebbbd6fb3095bafd89.nq.gz
    ├── 92b0427c59c2fc98896fd03ee22f836e0fc0449c.nq.gz
    ├── 9317a09c98469d84d47969aa6461480621ab4eeb.nq.gz
    ├── 94392a13b97883614dc9327e1d32bccb5958f418.nq.gz
    ├── 9550de8fce975500c4b35b2e14204cf2e3420ee9.nq.gz
    ├── 9552689f221fe13ee55f15fbea1bed39ff142966.nq.gz
    ├── 95d897059febe62835400c5826a258ddd8817d87.nq.gz
    ├── 95dea64fc444613fb6b67452107e56cfc7981431.nq.gz
    ├── 960259ee78423c12a882bf62129af8cfab1afee0.nq.gz
    ├── 966c4c7bc5b3a8421b56f609d0ba7880398a7c21.nq.gz
    ├── 96dfa2f91fc20cfd1a8c5bca4b8d642399426769.nq.gz
    ├── 9723dfdf3cb7ad76c2c1ebf53332d26c2924ad9e.nq.gz
    └── 97b1b2394fe117e5c46b49b5590c10fa5ffe3b17.nq.gz

20 directories, 200 files
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
