# Repolex Knowledge Graph of crewAIInc/crewAI

RDF knowledge graph data for [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI), parsed by [repolex](https://repolex.ai).

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
rlex download crewAIInc/crewAI
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 40bb2d3b586e8367d206090cc62df5242206008f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 40bb2d3b586e8367d206090cc62df5242206008f
│           └── chunk-001.nq.gz
└── blob
    ├── 001a07967bcc2aa20f8d3d9b1e550dcccef0904b.nq.gz
    ├── 0070b6b9f1c6e88ef7722d9a09df4a48064a257d.nq.gz
    ├── 0094446c5da665f46d00282ae530d827f5fe765e.nq.gz
    ├── 0121e745bf8a459c3710e251e46c7652088fa702.nq.gz
    ├── 0195323481a0c41d46aa22f6164fc0ad1465307d.nq.gz
    ├── 019cb35ea804a2fec7972d623ee0cdefa1c99d3d.nq.gz
    ├── 01e7a49da99e99bfef69abcefd45d04590efc8fb.nq.gz
    ├── 020183e1f8b56235cd7aa1c11e7fceb6c8f9002f.nq.gz
    ├── 02fb973140f00945cd8ebfea38f518adf03b4c05.nq.gz
    ├── 0326fede373886c4aadbb368a1186af16019ba13.nq.gz
    ├── 0331b04cc04a98d531d4d0074af62db8b3c29558.nq.gz
    ├── 0380c4bac87b26c6c5c1ebc94c85a55ebc9df53a.nq.gz
    ├── 03ae18aa32a562525ec5a226c4a5d31a9f3637b8.nq.gz
    ├── 041f80792bbec69de7bfb29354c316347f589d2b.nq.gz
    ├── 045bb5c22aecd50bae93cd0b3c9c9e2e749c5243.nq.gz
    ├── 04dc7ae2a6fc3eb83505ffcf5df6716c7182ba67.nq.gz
    ├── 069e25c319db8f63e7ffae0914311c9bb3dde760.nq.gz
    ├── 07fcfd59da9790d94fd4a941942b4ff9aa5994f5.nq.gz
    ├── 0855b2abbd1ad6b911507c60b6273231742be561.nq.gz
    ├── 0941ae35bccc2a83c090e96492ae6c0000cf8e8d.nq.gz
    ├── 0945c6d50483eb258a49620a038c3ec96769888b.nq.gz
    ├── 097f9287b84127eca0269b41fea9c66c7c916f92.nq.gz
    ├── 09c5ee51887c1d60b43510e63254929a30f41e59.nq.gz
    ├── 0a20c720d087346b0af2e0448cc8ff67bee00523.nq.gz
    ├── 0a493acaf117d6165083765d9763344418569d57.nq.gz
    ├── 0ab1c3754a9adea7772d44016e9ec0c8f89cb8fa.nq.gz
    ├── 0ac00110e234cb5155ad536dd71f027388c7380a.nq.gz
    ├── 0c789c158e5f48663e7166b9782baf0ce7f72e13.nq.gz
    ├── 0cc017ae96bfd42e5f5e6c7e2fcc788c733f8575.nq.gz
    ├── 0d33d5f4e11e3716f9025e4fb74b305cf94e1a82.nq.gz
    ├── 0d575b645f3d5ade5167091cb532986361ab402a.nq.gz
    ├── 0d6ebebe96bb65d53308d1f92201513cf9ebce67.nq.gz
    ├── 0e70edfbd712839a8a489a94552007eca0f96ab2.nq.gz
    ├── 0eee2387a98ebdfdb5b54751434137836f155819.nq.gz
    ├── 0f4a95acbcf36541848b764765856c48a75d6b73.nq.gz
    ├── 105492388d83d56a92ab4271523351b4f96708d0.nq.gz
    ├── 107bf28cf16ee48f59067bbbbf3d32548ef37364.nq.gz
    ├── 10edb565e0c648f5ae3ade3b4c481e7fa4a6a291.nq.gz
    ├── 11a8bd1a02454db238efd1d19d7b5f64141deac4.nq.gz
    ├── 11c902c95a78a8ecc99dbe55abfe612b6e7ea236.nq.gz
    ├── 1207562cc985502ee789b031cec92d3aa97809f1.nq.gz
    ├── 12599a88fb822d3fdbb6cd1caed926f7a1b3e85b.nq.gz
    ├── 1260ea7e3260877681ec3100f3cb4e1d0bdda074.nq.gz
    ├── 12683e8cf94438230abb063d83ae6fcf1edb6c03.nq.gz
    ├── 12b15361251d97746f6151f000381e1bd1c8372c.nq.gz
    ├── 1444eb58dcc19b6464c8bc5c67284b855a46d1b9.nq.gz
    ├── 14e5b705f792d2825ae65befa9bcb6b990a54d96.nq.gz
    ├── 1530d54a9a7f05a3ae49c93373cd758d96562036.nq.gz
    ├── 156fe7ed834dede78ae98bd9f57d9b92361b89ba.nq.gz
    ├── 15e44996c3181b0701a29ec74862a4d01d8d60ea.nq.gz
    ├── 166c89b2c7cdfa25e6902384340891e2143ece84.nq.gz
    ├── 178129690fb4c0f06b5ae73e093e6751f3dd220a.nq.gz
    ├── 184c89770e8ab5ec04a9acc30f4859a2273f50a0.nq.gz
    ├── 186afa2c648ff22e76ab7b5d2335733bbb73a3a8.nq.gz
    ├── 18d0e238fe1ac2f7f247f5f18be4138b647b2ffb.nq.gz
    ├── 192aa53e43c7a7daec19817286c88b19b7c87baf.nq.gz
    ├── 1a1da0a5f5ba3601569ed829cac9c573546a00cf.nq.gz
    ├── 1a56ee8e2b527d575d31537001b3fd0a50452cf2.nq.gz
    ├── 1ad91c95f15a2504eb3fd6b46df90dcbe4fe9f56.nq.gz
    ├── 1ae9eae33d0c4738fdb49b7c99c019f1a883765b.nq.gz
    ├── 1b2ec234eecc515f574ee8fd8b1e9d3062523ed4.nq.gz
    ├── 1b414cac9333c5b43d580b8ca5ed830462cb34f8.nq.gz
    ├── 1bb936f35992ab7a44c39e2bcbdcd7b853a790bf.nq.gz
    ├── 1bbc4a3b4d911ba32615f52b4466eafbc6849fce.nq.gz
    ├── 1bd7f016dbf92ceffc4eba491b5d327b72471f7f.nq.gz
    ├── 1c3c5f2b1c4abe6aee34c5974ed014290c051375.nq.gz
    ├── 1c54dc8d23c03801d01cdc590d4b0355207c6ffa.nq.gz
    ├── 1d200c48d14a3e9ee8e945b772a4a5c82f2b5b66.nq.gz
    ├── 1d3e6ee42dfeb67f7820529a5e94544b5b29119e.nq.gz
    ├── 1e011b7f677a7fe69e11357600de789e360d1e8d.nq.gz
    ├── 1e5a6c842814409f24f4230704ecf06b757e6fc4.nq.gz
    ├── 1e9d7ddee74524aaf27bd9b23feddb8c66cf4a85.nq.gz
    ├── 1fda3e5bde7e53ab0dda829b90c0564c35896d24.nq.gz
    ├── 20e94599c5e221318887a98bda706814a0aef924.nq.gz
    ├── 20f082d185e38e1736974597026ae799b0a1469c.nq.gz
    ├── 21211e9fde561d70dcc3592327a4168a20d51bf4.nq.gz
    ├── 21ab52c85204801f2ffb73b92cd1bd31a26f11f3.nq.gz
    ├── 22f2454e14c96ca9245079688a11fdb3008f07a6.nq.gz
    ├── 2316286f800e602420ffd26e677038e677fe1e4a.nq.gz
    ├── 234a62fcd06d2927855cb34b80cabda37117e8cd.nq.gz
    ├── 241517ed22667be8a0475239f4334fa41d4e422b.nq.gz
    ├── 241e579f433cbd9d95ba80c195e9b8a2c761be26.nq.gz
    ├── 24b17cfcedb8d3d9aeabab2b5e67a44a670fe6e7.nq.gz
    ├── 24b650889c9b1c4df1105a10a64afd1aafb2dd78.nq.gz
    ├── 25499dd5267f0b96c4c2220c694ee63473852037.nq.gz
    ├── 25db59713ecb70ec6ac296d29b8621f7ed05659a.nq.gz
    ├── 282d2d8e28fa429a6de0390a98a3dc02b99f752f.nq.gz
    ├── 28a823f2d80fc18c4dcb9ef9f81be4510db3d209.nq.gz
    ├── 2a5d7c5514bf9e6e69936597e9f02435ebf41c70.nq.gz
    ├── 2a63a30d4875f2f2785c2bb65dc01a4ffbb423cc.nq.gz
    ├── 2a8e2ba252761cf3c031988bcebc68241d4a7461.nq.gz
    ├── 2a9cd9e1c7915d5c663f9309ce513b0b12cd8551.nq.gz
    ├── 2b7a5d278b6aa356cd9998546a4f2460f0e724ac.nq.gz
    ├── 2bb4877f174c4c246424dc976b78cec8d6109bd0.nq.gz
    ├── 2bf28348264e7de5f52f5d7a8c8b2c742ea52a80.nq.gz
    ├── 2c12e72016ab1e3d0c8bd388fbbc0b1f7fd81593.nq.gz
    ├── 2cac627b2f02264b04272af0d8a2380687319f43.nq.gz
    ├── 2ced3395480b4f62f73f4f6a352f4b3f16371bea.nq.gz
    ├── 2d2c94bc6f7cdb7586c54b78e734b09c80d1c6be.nq.gz
    ├── 2d3dccda6590551c624a32c364c4aa5b5282e6f1.nq.gz
    ├── 2dabe49ccfb16c2e845189798337e18e1a7be597.nq.gz
    ├── 2db64982406b831d310caa894bbf3f510f38724f.nq.gz
    ├── 2e288bfcddd925aaedd87c4f06ba32bda11c02df.nq.gz
    ├── 2e2b9b8ac94611791f7592cc935d5338e7eb7306.nq.gz
    ├── 2ec738168801e8aaab01c20309dad131ce06b83f.nq.gz
    ├── 30a85462b87d653a1b45f4416d70c403c42176b2.nq.gz
    ├── 321448477d88ce352f5db7d58ba3de3851502f59.nq.gz
    ├── 3252e82acaa7de29d13a72e71b524b3ac2d408b4.nq.gz
    ├── 32894f44c8d013dc95823b9f11b6b02eee924856.nq.gz
    ├── 32c6a6689d621128a198409956b735a7f97e3564.nq.gz
    ├── 32e05669e1a9cbca3502dae7b4e6428f207457c5.nq.gz
    ├── 335dfface8489b362dc388e92a0b052ccf7d1ef1.nq.gz
    ├── 338cc710511f0e2526f88302b3a75339f73836b6.nq.gz
    ├── 33ec1d6e7b8d90cecfdbaf574516e497a2c57927.nq.gz
    ├── 349546d1c02e44b5b689610915873996ead5f93f.nq.gz
    ├── 34fdc8c668014eeca681134fa65779b52d26abc4.nq.gz
    ├── 3726893354dc6ec83fe17252f1b55a2a551961f1.nq.gz
    ├── 37bac3f12b8c3d392547bd69b8cd011ebc514ac9.nq.gz
    ├── 3819c8fbada651a5f53d1e2bbbe506eadaaea65a.nq.gz
    ├── 38bf02d4c1a04723ae27d26938cd94788e7efe66.nq.gz
    ├── 38f0912ce099c6498893e17a59b748b9cc336df7.nq.gz
    ├── 392570e1f7a2c758249ead08a6b5b2b4bde60f83.nq.gz
    ├── 3931ed6ab513423e065a0bce58d548e3098a00af.nq.gz
    ├── 3963ec454646ac16583fb6297c6dbf323131105e.nq.gz
    ├── 398d38f489b0e67df90198eafb67f4a452058082.nq.gz
    ├── 39e3acd928ae057830250f26ce815c4706f5c205.nq.gz
    ├── 3a18cd1da5cf3217a7b660342aff6b59956561fd.nq.gz
    ├── 3a8f13711559ac663de191934b767a5f788bcc12.nq.gz
    ├── 3b437918d4c7a545a7122324cdf3d0bdd0ccf3bc.nq.gz
    ├── 3b5eb1aed77ea1e8accb9182b26c4cc22acf9c9a.nq.gz
    ├── 3ba3b500e9dcfafe158fbd96ff63cd197a46c4e4.nq.gz
    ├── 3bbb844fec4825d463497c35dff592e04ef19b7e.nq.gz
    ├── 3bd91f1648699e611d7b2f8e84c880592616d2f4.nq.gz
    ├── 3cfcb9a631822e63a17a4302ddd00600ab858f7f.nq.gz
    ├── 3e29b2baf0dda535a644837413746845209f2e84.nq.gz
    ├── 3e387a7b263a54f7ab6b1c3ce1eaebcfc34f19a1.nq.gz
    ├── 3e5e3524685881b82ed1c32f3dda7c9960caf730.nq.gz
    ├── 3f0a0e2277baa8732b139e1240228c745bc6cc1c.nq.gz
    ├── 3fa2a8b48ef84bfb3d7b948b692f9da27c31a6c0.nq.gz
    ├── 3ffdb82be09ac4d45be76cdaec38308f2c3e3b93.nq.gz
    ├── 41be56cb82e6a8c7dd81a5ed0943cf80b6bfbf9b.nq.gz
    ├── 4254f053c8396141834af10e83f100877b0ba62d.nq.gz
    ├── 42726faaaf0ba564d6d58818dd5198abad41fd32.nq.gz
    ├── 4296e35fb9816c7515d2b19cb0623994e5612345.nq.gz
    ├── 4406b9001b2a99c0e6a5dd067f45ebce83d3c624.nq.gz
    ├── 442ab7dbb7d1ceed9b4255599cdf10325196c2d8.nq.gz
    ├── 44305127d2d9d3e04c9af9d04110ea22804f53e3.nq.gz
    ├── 443995ac7a0e117775ee747f5cbfef764580bcef.nq.gz
    ├── 445f99349d74af87afcf87e011f328dfbadd4cfd.nq.gz
    ├── 4464f714a545e41db0cd135c4b8b015dc0412b5f.nq.gz
    ├── 45d54114d29e5f3fa6471861ff33a6bd9039674f.nq.gz
    ├── 468b77edad1dec1c0b22ad899dc03747ecd8a13b.nq.gz
    ├── 468e1acefceaf744dc989c605561ca60307a2282.nq.gz
    ├── 476422e8847bf9074f4afa4225db8390a2b19dd9.nq.gz
    ├── 484d0e490eaa8a88ee584f6963c140d6f38a94d3.nq.gz
    ├── 4889c91f62997f7a7a7c41e41cc3f24c79419b37.nq.gz
    ├── 495a1ef06c5e44fedae1cf6c95774b7ce0c21a1a.nq.gz
    ├── 4a0226145c267a24b2589c62732edc2e9dcd4dcb.nq.gz
    ├── 4a09f396d3ef1e24a1a7b8bea09ab803766ff46a.nq.gz
    ├── 4db577dc77e42e22eef2868b74f2d7da456641ed.nq.gz
    ├── 4eb4bca3cbb20a32b9e6a84781444afd5941f16c.nq.gz
    ├── 4ed351d223fef12458a656d18481b66ab71c440a.nq.gz
    ├── 4f8bb050c5355b30cc51fa69197f87ec372d77a1.nq.gz
    ├── 4f93af6565b99e6de0e26977f1c3c59e6aedd32c.nq.gz
    ├── 4fc1bdab0d18faea486c9fecf338a8ccc0929d94.nq.gz
    ├── 50685ff58ca7c00cab23857e9ae3fbf7c88e2f89.nq.gz
    ├── 51bb672ef041b2e43fe80571bd2512e9ebceeb03.nq.gz
    ├── 51d666fddd3f406000ea342cd83b3015029c048e.nq.gz
    ├── 52c163fd1bdb0d86d755fb97c710a82810e712e0.nq.gz
    ├── 52e568073d31921bc7a73651dd43ade0270f0bcf.nq.gz
    ├── 53aebaceadf7aea6d8fbd2d199ab96b6edaf1491.nq.gz
    ├── 548ebd230cba851cea31fdc290a4ec45bde5ec96.nq.gz
    ├── 54acbf969842345fbe1c56f2b9c34bd9239506a0.nq.gz
    ├── 54e51de2d15bddf3b62ec4e7974e995ee290b368.nq.gz
    ├── 55030845cf60d9170e861edd4d0a870498599dea.nq.gz
    ├── 550ea0823ddc2cceb32a2da05958670756b6a0c4.nq.gz
    ├── 577836ad9cc7b45f1cd7451a2a454cca246d4674.nq.gz
    ├── 57c189c968e574eddf96d492eec90efe72113267.nq.gz
    ├── 58597bb66cb9a85abd6d00cdada119ebd25b2c40.nq.gz
    ├── 5888ac6218201d962e2e8aedf075433d9b35257b.nq.gz
    ├── 58c88a1ec65f62857ab3f31772198d4d87195f78.nq.gz
    ├── 58d441c6e78262a428915d4f8edb48695fa92b67.nq.gz
    ├── 59bb5adb6fd7075b9d2f4e354bc2bbe755b08587.nq.gz
    ├── 5b0bfc3f2965a9740e86209096cdb4d18f296ac3.nq.gz
    ├── 5b73ebcfbd311925cbd9df566ed359e4a00f1e5b.nq.gz
    ├── 5c112b0d1e489b1644af5e7f6ebdd3b479877ab8.nq.gz
    ├── 5c2e21d5a7e42781c3877b2229ed2ab6472a614f.nq.gz
    ├── 5c77295b73f003751b280c61f6a7b1eaddb3abdf.nq.gz
    ├── 5c7914fae288970099994467bd0a7f1f0c2a3ca1.nq.gz
    ├── 5d1c06f60cc9310ca92a4dbbe6e0b0ab067f7ae9.nq.gz
    ├── 5d2c72a30ba55a4b96a5fcdd3106acc367368274.nq.gz
    ├── 5d89a337c6d98b4d4068f20f6869e914b1553f18.nq.gz
    ├── 5e919de949526cd9a715f399f93a5d3ac3336103.nq.gz
    ├── 5f57b783738210de4ed1e26163df174463f257ef.nq.gz
    ├── 5fb460448378d5e74afe0453b4ecd0cc42709578.nq.gz
    ├── 6098bf5506f20796a3c0b3f600eefa26dece6f32.nq.gz
    ├── 60cce293a5fbac58c2580fdf841c094d046447bf.nq.gz
    └── 61ebe65262ac64399afaf6dcc825baabdd5bda27.nq.gz

7 directories, 200 files
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

[crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
