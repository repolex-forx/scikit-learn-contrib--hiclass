# Repolex Knowledge Graph of scikit-learn-contrib/hiclass

RDF knowledge graph data for [scikit-learn-contrib/hiclass](https://github.com/scikit-learn-contrib/hiclass), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/hiclass
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6384239b29c691b50f25f1c467a4d5dab6cfb901
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6384239b29c691b50f25f1c467a4d5dab6cfb901
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bbb6e92d8ce1d3bd7c11f53a45d504c2a5c179.nq.gz
│   ├── 01111d452af3cf80b284d5d065500815ee2ec149.nq.gz
│   ├── 03daeeb823f24b66d7859bd68fd5635e871ec786.nq.gz
│   ├── 04df3f8ebf79a454d4250fc736c4c1b073910d7b.nq.gz
│   ├── 07d70c758bf514af55cad42082e383b1189f5dcb.nq.gz
│   ├── 0a18aa57ff2525ebf02d6570bbdda3181fea6df3.nq.gz
│   ├── 0a87745d2b684038e6c09d8e7e3052d0bfcd74d9.nq.gz
│   ├── 0c2cd9897e75a3562032359deee0c4a2f208411c.nq.gz
│   ├── 0cc0083f65f545bea4c2383bceb77e4eb49a57e4.nq.gz
│   ├── 0de62d7e42dc8b3b017b0b93882dda499394d302.nq.gz
│   ├── 0f20b9df0b8fcd2e7cf44dda4d3ec8299554324b.nq.gz
│   ├── 0fb585fe3ac43a7a61bd3d87f09b7d8ed1de2592.nq.gz
│   ├── 122a5e7ef73ebfadb5f548a1ffc35a0c9120787e.nq.gz
│   ├── 12d915a2dc452aca9594690fb9c9c452c058f615.nq.gz
│   ├── 18aeeb2368c0a689fac3121436c8e3482da0dafe.nq.gz
│   ├── 197389096fc523c99057709233d53b658cd1a57f.nq.gz
│   ├── 1b8ce281907aa77900356bee89155035a041bd64.nq.gz
│   ├── 1c01a0d7d47cafaeeaa44b7000ec2d23716d55f4.nq.gz
│   ├── 1dbf94e3f496fac26274e7da4f7e77009d227b75.nq.gz
│   ├── 1e937eeee064df0cc3bf68b2c6445f217e25210b.nq.gz
│   ├── 21d8832b00b863c2ae627e9980286dfc24e856a8.nq.gz
│   ├── 224a2b32437c4981bf777b607afe293ffb0bc88c.nq.gz
│   ├── 252d91670e52ef1fb3a8a53e5f3f550e7d5bfaa8.nq.gz
│   ├── 25a6e9891aa1c34f96685ab3e18c48c19de7c1ba.nq.gz
│   ├── 270e765af55b296cc9dd0c5151a42b0239ee8510.nq.gz
│   ├── 290ce2a30bca76551f9e82370ab7c51670b3c64d.nq.gz
│   ├── 291baf12831eb329e03907f23f66e21357614633.nq.gz
│   ├── 2a57bb5488966089577e4305c070455ebede1157.nq.gz
│   ├── 2b045634c5a3fedcf8c707ae10ee766a9dfd37e1.nq.gz
│   ├── 2d0ad4876f3669de5dc8e3230a0f5ae48b29c5e6.nq.gz
│   ├── 2d4a49dae86a34f5a6a7d2357be511c41684ba08.nq.gz
│   ├── 2dc4e1c21227f678339638c2d79a5bc01ba80978.nq.gz
│   ├── 2ff13577b8dc5b54b5b4533099203d0d9704be8b.nq.gz
│   ├── 34d81bb12fd89c6496cfe010b00889f21e371a6d.nq.gz
│   ├── 376ebfabf130b1c6771f0bc1722c19f5e5fb1e89.nq.gz
│   ├── 379729a54c32bf4f954137405841423ef838b51b.nq.gz
│   ├── 37de29264d0047d9b75c9a47ce397717618a64e2.nq.gz
│   ├── 394550876e5a218f34d66780a248f23fc93ad62d.nq.gz
│   ├── 3a6a459a894653d388840c2b9cfef4e917c240cc.nq.gz
│   ├── 3bc7759cdff7dc9694d93f158edb3c66d87b1a29.nq.gz
│   ├── 3be42d3b28193f07a23bf84fd57fd36c961d0e9e.nq.gz
│   ├── 3f0b42b5c6706db72425ab5d7ec528ef1c319d30.nq.gz
│   ├── 3f3450c40cd0eb61b4b9a4cdcccbad1aa07fea66.nq.gz
│   ├── 3ff9ccaa5de9ca01afa76c8f1c7bae7755869e25.nq.gz
│   ├── 4622d5ff361f18e4d3919b9b4c9c0da63e1da3b7.nq.gz
│   ├── 4658973e17ed47b903076787c5f5cc1387c91e4a.nq.gz
│   ├── 47395cc86d24decab57a9052c625d4d9385c8d08.nq.gz
│   ├── 4986d12eaa1d8e17b76ad3c6a8cf487860036d93.nq.gz
│   ├── 499779bc00059dc6d2f003660d8a7b0ef8d3a1ef.nq.gz
│   ├── 4e7723e28b07284475162766ebd071b61de416ad.nq.gz
│   ├── 4f5b76bfc7ab4dccffcf1f6c09bdfcac7904ad45.nq.gz
│   ├── 5052ef1df8d503eedb37872d389af4812eb3d69a.nq.gz
│   ├── 50e9a5201ddecab5764b7597cfdde8217f964c5a.nq.gz
│   ├── 54bec5f80d568722979ccb46be16c123112f4206.nq.gz
│   ├── 56ce74ecf17893ea12fae4667d988b66bd7b2bf9.nq.gz
│   ├── 5836189d26cf33056052eab17e6b935b00b4e958.nq.gz
│   ├── 58e377873f1573472b8f660dea8ee54bf115b01b.nq.gz
│   ├── 5bb3ab73511a66f5cffc1176f3af303f04c42171.nq.gz
│   ├── 5d59f6cae1acd990d88dc90c684cbda54537f72a.nq.gz
│   ├── 5e6a11adfc0fe43013c8823931213dc9a3461232.nq.gz
│   ├── 5e882692ae8e2310c9f1e0f94821130a54c5210f.nq.gz
│   ├── 5eb147480134fd27c0202dad0e76da5c9fc9f5de.nq.gz
│   ├── 60d73e8e798f94ca9ac063a243aa90baf98672cc.nq.gz
│   ├── 67813012dc049d637b11afedd6dfef2549e2f462.nq.gz
│   ├── 691a003f7e2c398abaa4b97c03ce95a6e422123e.nq.gz
│   ├── 69f55796f3d2b80b6c6362ffb3e58885e7eff926.nq.gz
│   ├── 6a33d8bb212fd0d050a99141d130447189ea20cb.nq.gz
│   ├── 6ab3c295b7090476967e8eaaa16377a910e0a8c9.nq.gz
│   ├── 6bb5d9a52c0c7a75c0aa88f8a98e829f77d4d157.nq.gz
│   ├── 6bd3c5912dcc2fe5228378faa1e42768f44d9934.nq.gz
│   ├── 6c690fd9aba500ca26c569a6cd2a4b2224c8c957.nq.gz
│   ├── 6d4f542d2a02ae201744f0957dd55e9d6352cd64.nq.gz
│   ├── 6daa88f108ced77a48a12e5e69c047faeea43372.nq.gz
│   ├── 72f23e268661feb17372708e9becaf045e010b52.nq.gz
│   ├── 744740bea593577b1359b77bde1a7b32a4a1c4a0.nq.gz
│   ├── 76b2edfaa1477cfbb8c61df7cda6a0868a52e654.nq.gz
│   ├── 7851d5f3e088044ebdbb50c947d9962ee2c38974.nq.gz
│   ├── 7af72bd3df9cd0e1dde770842866fc33cc5ec464.nq.gz
│   ├── 7b7780495cd0e22b976e826c70c1a624aa6f9f46.nq.gz
│   ├── 7cb091123efbb246f8496032c0b0d526403e2500.nq.gz
│   ├── 7cc24de4af63cd29bcf5307dce4c0258692f2e72.nq.gz
│   ├── 7df0e7dde808d69decb015ea7d51e7bbadda5505.nq.gz
│   ├── 7e6ab574f193dc16066f3b30ebeafafd72eb15bd.nq.gz
│   ├── 7eecb9bddb019bbf0ac31c8fa048c527cd2949eb.nq.gz
│   ├── 7f0e22a163f96635e302f5e1be5923d4a7609998.nq.gz
│   ├── 7f5220c24930526b8c62eb4e3f95ab5d8d22a05f.nq.gz
│   ├── 7f941b5fb5874e5b467a293cea76b3e796f19918.nq.gz
│   ├── 7fbb5d49b638c7b6af94a4d0e1b507a7f72c2f2b.nq.gz
│   ├── 8010f82fd272a83435b250f306e0a6cbf285cd3b.nq.gz
│   ├── 80576526625a4a79be26fd9738707712b777caf3.nq.gz
│   ├── 82523d35be2125d5e027c711bfce39471ea49cc8.nq.gz
│   ├── 8276a9f09179f4e84a0343f3a7c70fab37034886.nq.gz
│   ├── 8295384e5cd90a4e0c34152260311b7afbf43da2.nq.gz
│   ├── 82c3f611833d2cbf3231404d04e945ff02222245.nq.gz
│   ├── 83c353bd99e20f0581e454c16b03f86f28f591d3.nq.gz
│   ├── 852a7a8de87d148db85458d17df8580097109c3f.nq.gz
│   ├── 86689999fd99ac085d397a29125119adb682af81.nq.gz
│   ├── 8679e89516dfbfc95bfd912d2a4b283cc9bda4fd.nq.gz
│   ├── 86bba88fbd59415c000672062d217982c17b010d.nq.gz
│   ├── 87135a486beeb5cb6994e63bad87d69e0613f7a8.nq.gz
│   ├── 874aa89b53742fe8fbaab7e386c142ac6dbc3d21.nq.gz
│   ├── 8c8827fa7bf92536fdedb6797810b3f1257ea09b.nq.gz
│   ├── 8fe588571192842748be6dddd736784b86753c88.nq.gz
│   ├── 90865ee2e24aefd9a758d789fe24968ebb250e24.nq.gz
│   ├── 920a17ece75c090d9f0e26077a8b821ed97ee781.nq.gz
│   ├── 92605ad20ba21360ec9e7c6d815158c4e4c06432.nq.gz
│   ├── 92cee9ecb431697d52fd0097a4bedfa03d304085.nq.gz
│   ├── 9534b018135ed7d5caed6298980c55e8b1d2ec82.nq.gz
│   ├── 95a1aa62e9034b7be614937dfe02e0e4f8d7a65f.nq.gz
│   ├── 97411ed07f86d09386786132a73d70197982ef76.nq.gz
│   ├── 98789b532f0efa2d10d707e68dc730a1d4b71623.nq.gz
│   ├── 98dccb5632b21c00aea93035caedc517396f67af.nq.gz
│   ├── 9aab4dd83c3dca3470edb291fd9a21fb1c64f229.nq.gz
│   ├── 9b17af1ac6c66d5b502233cfbd4a9e2e9dfd44a5.nq.gz
│   ├── 9b22a0bdcfd241c6fe0d45c2600cd64930c057c0.nq.gz
│   ├── 9c6c8edbe4b4636acf58d5b4ea5f2ae4e84b1318.nq.gz
│   ├── 9c7a3e9dd8ed2e46e5cae8f6e8eb07cd60bfba5c.nq.gz
│   ├── 9c992c0d47fb79fa194d2d1d0fed2ac7fc7fc721.nq.gz
│   ├── 9df47539df355615263fd4d78173c3def97fcb41.nq.gz
│   ├── 9e08192d5a78036526674ba37bb57e88950f1dcd.nq.gz
│   ├── 9ee33b01e6afdd3a8fc6b52d99e80481ce09b500.nq.gz
│   ├── 9f3325971f04b2bf50f20c52039a8e0e41091360.nq.gz
│   ├── 9f643c63b1d7a472a39a490f96cfcff154c73bd0.nq.gz
│   ├── 9fbc905d0bd52f3d0d3048fde3ce54bdf3c13b73.nq.gz
│   ├── a129e39f6aa115a1a1322210fa809f140840fe8e.nq.gz
│   ├── a1d25adaf3aea031a9b52a97952b2d6ccaeee14b.nq.gz
│   ├── a1f4f3b7c743775d776d036b1bb258271c3fe35e.nq.gz
│   ├── a41f9d9201a22846286ca6c1f073311630676b8f.nq.gz
│   ├── a48232070aba18465bcf48c303c4c2d5e854c570.nq.gz
│   ├── a55883b19a0bae0872c139bc64d8b97f56ee94a3.nq.gz
│   ├── a67d970674a35f28e60b8571cf4edad304736bd8.nq.gz
│   ├── a6997f1147743f9b5516b9870c87564163139ab3.nq.gz
│   ├── a6bb40c70dfd1475010eb1619192ad6644c7b4bd.nq.gz
│   ├── a88049149d38c301af2b5f4b2c1bc6dc866dc902.nq.gz
│   ├── a9f21aa73485cf98eb840ee32e7d2ecf53568df2.nq.gz
│   ├── aaeda19d28c266983342d487c5599c7893f09122.nq.gz
│   ├── af64a0817aedce3d0199bbe1f1bbb67f635475ac.nq.gz
│   ├── b0071c7e82bebcb7d2e534155390a6965b9f0571.nq.gz
│   ├── b06fbdeae013fec54e295c703a5f14f9592b85ff.nq.gz
│   ├── b0b2c73e2b54c39590a7bdce242764f33ca975bf.nq.gz
│   ├── b58f3a61944c86392de3549c954b554818d72fc1.nq.gz
│   ├── b86c0307e36d418f8507b96e76aa98bd628e2372.nq.gz
│   ├── b8af6c2518005e1e516365c1af2231dce1e4d071.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bbd5451d0207094558d36af3c7dd0db71335f47c.nq.gz
│   ├── bc16c6c13db4e7aeb9d74dd85614313edc3b5d0b.nq.gz
│   ├── bd6453a0205eaa62b5db8fd7d6ca3f4b44da5ef4.nq.gz
│   ├── bd7bf11ecc8f14b7afac5d4102e05094806e8767.nq.gz
│   ├── bd9e41847264017756914d86eab1f6705ae2f7de.nq.gz
│   ├── bee20835cb2f370cf38501cd44bf5fb431d7704b.nq.gz
│   ├── bf76288366252c4b5dc910b0399e2c710003cc20.nq.gz
│   ├── c02341ee279c6043832a5a140049138b33f8a941.nq.gz
│   ├── c0c3db6c3cfaeec6107fa12ad36085b7bbb15757.nq.gz
│   ├── c1bffa37829e16f0bc3f80434761da9a7233b461.nq.gz
│   ├── c1ea6731521a64b73b140ebc8fdcac5877e4c595.nq.gz
│   ├── c5ec1509aad07aea5eff718968a5fcdc85bf462a.nq.gz
│   ├── c602093da6035eb4d242ffffe8f9a554cb5f79b4.nq.gz
│   ├── ca4f4a434f29a2406ee27e724e3f5fed9d2ce340.nq.gz
│   ├── ca510dc2910438eb76fa0cc7ff4dc9bf0ce4d447.nq.gz
│   ├── cdb9db32f937e57ce794ac16e5dccc45151b3e18.nq.gz
│   ├── ce89787d325fbf17c1aef1a5e2083288b6904b6c.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d0fa4450dd49ce7bed28650ac3fa4a879fc53fcc.nq.gz
│   ├── d11a11f3b63261c9222713c06b922f7da9cbd38f.nq.gz
│   ├── d2dac8c98548b3a10d9548eea2cb75757dc164e1.nq.gz
│   ├── d45cea907dff2033be331e029fe4efc4e2609fd1.nq.gz
│   ├── d52c4f0a35478f7d2005c2435618a24b65cfa7af.nq.gz
│   ├── d535d4e59e0efef1145ee9f04115dafdf887849c.nq.gz
│   ├── d53e3a28338a0f2a28c6a55b57e72b31a56be14b.nq.gz
│   ├── d5d8da31efc26ebdc749a74a0bb659ec0c2b7eea.nq.gz
│   ├── d6c583d31c03dbb4b656e3fffe0e5f287ab37764.nq.gz
│   ├── d957772c912aee86062b2f6659baa09e083f1e10.nq.gz
│   ├── daf1d281eb0a64d5069445ec87da9d293d722429.nq.gz
│   ├── daf863544a734092d3e5beb8211d9419d6cca96a.nq.gz
│   ├── dc46e935cf318a5dce12106aa6ccb9622602e081.nq.gz
│   ├── dd3cdaf131a8146b9cc2a30b8b168fed0fe7fb14.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── ddbfb4d529b3f60b3a5c0f2706ae0eac5b6c748e.nq.gz
│   ├── dfb9971361b1f21fc92ecb16f81ac9f1de5be03a.nq.gz
│   ├── e16ce067506ea6c85d482dcad5b55a8f2d75edeb.nq.gz
│   ├── e255a1d26a7bbc5fb240d7a64ec51320225b82ef.nq.gz
│   ├── e693f9407442f0bd19b7cae6f0e077edef97c017.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70f8f58aee826723785f7365a7c996c284be939.nq.gz
│   ├── e84ff2ad2e9b77127be871aaa642aee65f8a4c04.nq.gz
│   ├── e996e313ef0144d04339b6048737f2b82b70f86f.nq.gz
│   ├── ebebfb3c47c4bc69920c4a67441f2d09fd5de04e.nq.gz
│   ├── ec2dd90cbd9b7da268ce3685ee6770c691800f90.nq.gz
│   ├── ec44edb58375c3a0253fb59dc3d8e3f46ffb6fdc.nq.gz
│   ├── ef80c474491659427fbb20a199878f1decc18195.nq.gz
│   ├── f553b9ecc4d3bc14daefa07360c3be7345fe4e0f.nq.gz
│   ├── f5bd7483a9c8192353a1b7d024f0649b19879aaf.nq.gz
│   ├── f6c159b2003297d04198fb98b64caac36cd43425.nq.gz
│   ├── f756d5de0cbbc1bdd7c4c6739dbf45ac80c884ed.nq.gz
│   ├── f80518f927d4a9731fa57c9c73eca12f333248d9.nq.gz
│   ├── f9312178974606c006aa6b4dd64acb1cb28ca458.nq.gz
│   └── f967c637f8649439cb3587abd719b428c2f380ae.nq.gz
└── branch
    └── branch.nq.gz

8 directories, 200 files
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

[scikit-learn-contrib/hiclass](https://github.com/scikit-learn-contrib/hiclass)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
