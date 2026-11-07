# Repolex Knowledge Graph of ansible-collections/cisco.ios

RDF knowledge graph data for [ansible-collections/cisco.ios](https://github.com/ansible-collections/cisco.ios), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/cisco.ios
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6a98dc1668619e938589f0e394ae6f1a91287a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c6a98dc1668619e938589f0e394ae6f1a91287a2
│           └── chunk-001.nq.gz
└── blob
    ├── 0027504e416358355c591950ccc98002e3870c1b.nq.gz
    ├── 005fa29ef40ed609552e73ccbb5b1eed76d30ad2.nq.gz
    ├── 0155d22d0b0c2e8caf9352d4c36b633a1fc4ea19.nq.gz
    ├── 018f024a9130390878e59ff7475992a40e1193f5.nq.gz
    ├── 026ab9922c3b54df292f5ab8d0485b2a6804f037.nq.gz
    ├── 02969ffe04d4b53dab73318f7de670a03960cfc0.nq.gz
    ├── 029c2dec0174e05c3d5da4fe9bf412c7630b92b2.nq.gz
    ├── 02fa44d19911ce0b5744b25009fe396926909b21.nq.gz
    ├── 03eb7883b68adada4a3baac467097aa12b593462.nq.gz
    ├── 041b6856effffb48ee5938f5b5a5f3878c8c50f8.nq.gz
    ├── 04239f16d827c3c333f2ca85e6542c6e0753b4ae.nq.gz
    ├── 0451e7fd99dd239cbfa39934f9746f67acd85556.nq.gz
    ├── 04a25993a194372b970f33b5ccb0ecb307a69bb3.nq.gz
    ├── 05a1b220c22a64d4556120a687c9be0585064b7e.nq.gz
    ├── 06228c48dfe47a7ed8dc2615a4e5b928ba984160.nq.gz
    ├── 064f7fcb049b4bbd8e4c49fa45b48b22a3de0051.nq.gz
    ├── 072566724da2882072262aa9e1ed3ad8a90a1333.nq.gz
    ├── 0808df76d2865f210bc0eb66345d216bf3bd83af.nq.gz
    ├── 08395589b9cbb5a81138313f2839793f19dced14.nq.gz
    ├── 08ca57eb20cbca059ece41a81d69d709deee4f63.nq.gz
    ├── 09847c318c744c6f13b24029ee41550db90f48ca.nq.gz
    ├── 098506a43d0eff9c74bf827fd1f0cbc20168604e.nq.gz
    ├── 0a2d35f8fb84dd51e4ef27270cf974ec5ae7eaa3.nq.gz
    ├── 0c504c16063b4fde84e0c1c4eb82e07edb6a5fea.nq.gz
    ├── 0c81de1248f01516c956c9b669c8c81e8f8c8326.nq.gz
    ├── 0d1008d1a29e70729dd19e02d2cc931454e352b0.nq.gz
    ├── 0dc34f2ab70f7ede8cdbfb791fd6d2677995054e.nq.gz
    ├── 0e6fc0d8c3f034b229386c8b3b05b6029b7d6d0a.nq.gz
    ├── 0f53850258f7d1ca552bc22cbcd5929fd7fd9edf.nq.gz
    ├── 0f96732a1da70d5d0519256574111e861a7566e2.nq.gz
    ├── 0facc8624abc7734c62678c2694893d479641ac0.nq.gz
    ├── 10e2c784c363e44e206b441691ca14e052a423a7.nq.gz
    ├── 1134b097494115ebce94d20f30385eb9fe92c380.nq.gz
    ├── 11e319b292d977b66f5ce8d723b7e5398057df1a.nq.gz
    ├── 11f1f570c5b07e174e5ef19815771c46e3983c22.nq.gz
    ├── 126633caac42cf7172c9179d43ccae441748da23.nq.gz
    ├── 138cd5715e9f721da9ee90c35951550ef3a3736b.nq.gz
    ├── 144fb1063aff44fb1306dd7becbdbc2c91161384.nq.gz
    ├── 1499ed7292564d2e5ead0b0a1961dc35751e5b03.nq.gz
    ├── 14db123ba80f627a7119c79d5009713b2084036d.nq.gz
    ├── 150c04e19b8332241e7ea99bc994bc8fc2832406.nq.gz
    ├── 1580d2575c66b19b0d7226bd8bcaf0d5db432acc.nq.gz
    ├── 16053c325b352abbbd1f84a46d1afe47c5048a31.nq.gz
    ├── 164afead284de6add13c8f514561691b2f1c8dba.nq.gz
    ├── 17721e238e15b11e12828ddc4bdc8dab4cb4b8d2.nq.gz
    ├── 17eb030eb17877d2d67b2835db323ab19fc8b03d.nq.gz
    ├── 17ee40e99b225b4312a804e0c3ae08246578fb0e.nq.gz
    ├── 1857551c07dd4d73b9ea330e63f6dc5663aa9108.nq.gz
    ├── 1976f2424fcafeca5d1edfd95c692eafffaad853.nq.gz
    ├── 199d2f69ab369c62a4a22710a31719f44d95bdfb.nq.gz
    ├── 19e306a9d10b7e7daceb0e5cf38e0101170cd231.nq.gz
    ├── 1b3a0f0939c8cd5f040efad4f9c6b76343a87022.nq.gz
    ├── 1b7bde1aee0c3fc46abd2146269fc70ab4b3a06b.nq.gz
    ├── 1c1120e7fe588e5344905566a379028fd22f65cd.nq.gz
    ├── 1cc97d147a7fb0a635ad5a9461b4ebcc7aa4cd49.nq.gz
    ├── 1cffb658e89d1ec4f8dbb472525b09e2033c23ee.nq.gz
    ├── 1d16f4d3d19a48921ed5dcbaf8f6b36cb8d1e164.nq.gz
    ├── 1d92726174a0f84fd236bdaa78c01ed98d89a3b2.nq.gz
    ├── 1ea843247f085f1a7da51514377b4060841d367a.nq.gz
    ├── 1ecb46b6632c1e475e4094b774f2048cb5247ad2.nq.gz
    ├── 20121ab5433f17ca6101f242046beb72ce387ae7.nq.gz
    ├── 20cfe02e3a736b23d299f093e29081d3ab8ac0dd.nq.gz
    ├── 20f5758e40a8e249fc34b0bff534ab79b49579f0.nq.gz
    ├── 2123c9468e451e99660c1149100b835e1099e852.nq.gz
    ├── 21d07f55f6a6939e86611a1ee45dcc4b8cc6c3b3.nq.gz
    ├── 21f74be2f565ecb5a2b6016cc8a04a6938a243f8.nq.gz
    ├── 22606cedaf905b40eff0020b15da16aee9afcb46.nq.gz
    ├── 226fa4cb651d34ed7fb20e6c80df67c6a3d44411.nq.gz
    ├── 23a7aab01addf18d0fcaa993bad040751ee07753.nq.gz
    ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
    ├── 24617f00bad62aa15e12c82138e5c1fcd1d4d655.nq.gz
    ├── 24a79db4904843ced8f1f55cbd10830afe6738db.nq.gz
    ├── 24bd4abe1ce357f24a1af8aa4a66c98e8e3f3f94.nq.gz
    ├── 24c1af190c03b0f206b6f87aa99b6cf6b2261cf3.nq.gz
    ├── 24db56f2273d0ccf581512f7ba3987560610ce61.nq.gz
    ├── 2506c7e5023f99bf28196a1bcb98cf479bb2c0f5.nq.gz
    ├── 25bd6026db767eb550f3860a1d391d239ce9deff.nq.gz
    ├── 25c50045aa7274d7d43ff907ed4cf24523e2ee12.nq.gz
    ├── 267508196914ae11b7f14af6ba105fa38944b550.nq.gz
    ├── 26ad5bf8909aabd8df2f898b9c13bbd25ce234cd.nq.gz
    ├── 2729fed50679e3d2310445dcc8a6e075e6a8559d.nq.gz
    ├── 272bc82d555c71f3a868fb9260d0735008a0244a.nq.gz
    ├── 27f07c04b708cbce8d3490e8f2822b3b569bb479.nq.gz
    ├── 2894240b92e2e6efe2e742583ad0348ac922b9a6.nq.gz
    ├── 29332f73e1e2bc345068ce1ffca3b7d9b3823759.nq.gz
    ├── 2956517506a015a8c136d9afb20a7dd2171e933d.nq.gz
    ├── 2be44a1303049e24a1b7cbf3c09515efebf3505d.nq.gz
    ├── 2c504a6ac2e7a93c986764ab2b5714ee46a73267.nq.gz
    ├── 2d31449a59b64e64e5351b31d6b5fe71279cfa1c.nq.gz
    ├── 2ed1dc04b459afbdbab87976090115140b1f608b.nq.gz
    ├── 2f0a249a983623bb78c3cef44f619f085acfc7c7.nq.gz
    ├── 2f1db29b7ebb96f8b8a94aa913d8580dcf6945c8.nq.gz
    ├── 2f1ec5c7770159c3ff8d2c2eb6c0d8ccbdd21a13.nq.gz
    ├── 2f334a79f2c09aa47aecebbfe4ca3aef6bfbd389.nq.gz
    ├── 2f7cb11bc24e786a75fe4f48f48e2981c9bf7598.nq.gz
    ├── 2f8c87af688aa54885fef50fc5ef8dc7c12c401f.nq.gz
    ├── 2f99e6da06d8c6d50e8cd4cd373ebffafa40b7a7.nq.gz
    ├── 2fb623c43bda978f263e1e9ff35805cf7da16154.nq.gz
    ├── 31a33c76e948205607e4c1eea96e263e2ab773b6.nq.gz
    ├── 320ec9f926899a6bf48e0304ad15ad17f4072916.nq.gz
    ├── 3234569ce60485f115f0b64d403e1df4b3590e69.nq.gz
    ├── 323a2fd7859d30c973e7e0a0b4dfb3588a088e74.nq.gz
    ├── 329ac4aa7cda61f9a762a282e8569b2b4dabc162.nq.gz
    ├── 32a68ae6a60e0e43c09b94288ce5611f8cd3c3fc.nq.gz
    ├── 32e8acfc656526add75a3d47233b3f177017416a.nq.gz
    ├── 3304b895f7d3fc541e130cb53860b38165d9038f.nq.gz
    ├── 33b3fe1fabf0ec62310d5754024c420ce524a704.nq.gz
    ├── 33fdc91495df28a8d43a41e9725aa9f57b0baefe.nq.gz
    ├── 3415fc29d1a669ad03ba95fca0475889145835b2.nq.gz
    ├── 34709588090642cfff482506b6f8095574320cfa.nq.gz
    ├── 35274d8e22ea05e646acaab68d7a02775e9aad69.nq.gz
    ├── 3534bce7d60efa322bd3927e1aadcfa0a9e5a490.nq.gz
    ├── 359cf562a0cbe34c68ab6d18a79aa5d448f333f8.nq.gz
    ├── 36c3e745d10b082a8ae45efeaf629f18578b61bb.nq.gz
    ├── 37096169310a6e5396b627a406ac9d373177668d.nq.gz
    ├── 371c0d279ea32ba9483cd53aeb29196d5d1a5c7f.nq.gz
    ├── 377a1959b1d9c3eca26f6bf90eda1f07f7bbdc6f.nq.gz
    ├── 379052459b2872350a20c66d698a2ba2a3a535f6.nq.gz
    ├── 37d20f420469597d81682bb79e12a0febd061703.nq.gz
    ├── 37d9521f88964d579a5bff9fa5cafb9da21433bb.nq.gz
    ├── 3867295cad45d65cc270608216e0f098e69d771b.nq.gz
    ├── 38f2e1d5cf78772a039d6ea1557f3d1c7799030b.nq.gz
    ├── 395221308989846d4057823ca14d515d011652c3.nq.gz
    ├── 3971459060b4160b234d8ac0fee479a166554d77.nq.gz
    ├── 39923de4f959ed804d664cf844e40d36dcddaeda.nq.gz
    ├── 39b17268f694a02dc7b99746d6c310a8435431aa.nq.gz
    ├── 3a2d27673f4a288f6ebac2f2a864e7db18475a87.nq.gz
    ├── 3a8c2c37518a40e02936f3294821d2f1cacf98bc.nq.gz
    ├── 3aa1b60533bc66b1b80d1e353784c5232e221d55.nq.gz
    ├── 3ae0577c0d8adbaf38200d0802e45a32261fff56.nq.gz
    ├── 3af2253c88ea8221f2fa1a1598df1b99b5018f1a.nq.gz
    ├── 3b3eb2d7fe4d39c050d62b97b9a619fa8c6c4244.nq.gz
    ├── 3bdf810d1dfea329a48a0687e9714c02fe4675c2.nq.gz
    ├── 3d08590fb0e23277e582eb0d3f12d56f58d8b15b.nq.gz
    ├── 3d32bae959d51764e2ebe454f1db8c90ca6aecec.nq.gz
    ├── 3d5479c843376054f4523a3fc4d64dc763752937.nq.gz
    ├── 3d62758a5b84fefd1c33dfc5d70157fa0040dff0.nq.gz
    ├── 3daa3888f20b8feac00f8ec7db352fdf4b79babe.nq.gz
    ├── 3db4a1fb6b1829266d75d56a7d0b45a979dde88f.nq.gz
    ├── 3ed288f731f0fda67af5856b5f6a7af892d04048.nq.gz
    ├── 3ed5819f761739532f5cbd224d002a89b449d84a.nq.gz
    ├── 3f18c62135a6c174c668c366ed5cd8d69dbfdeff.nq.gz
    ├── 3f5f30560e8738d1c0e403ae4ba231507b57b3b3.nq.gz
    ├── 3fbaa739e1781e1fa84edf7f18fd928882a400b7.nq.gz
    ├── 4034115e5b66f8d91caf81ce3efbbbdc6421f9c0.nq.gz
    ├── 40fc944a4a7136fc2e5d056c86c067d1b1945d40.nq.gz
    ├── 41a784791ff3654fde6a52f00704ea885a6cad95.nq.gz
    ├── 41acead980ea58aa81a16599c14c7626a8609f55.nq.gz
    ├── 42329c733b673911b7091448f77141032aaae50c.nq.gz
    ├── 42adb080714ee4e303c98432fde05e5f4cfe6e25.nq.gz
    ├── 433d4bd0715a712180f5dfb8ada806930f7ab8ba.nq.gz
    ├── 442aafee6a427cf660b4bb818b0fb1667a707cd6.nq.gz
    ├── 447e7938da343775a1067d60e054ce267b4f479b.nq.gz
    ├── 46150c4d90052ed33cddb114740ead82fcbb6543.nq.gz
    ├── 4654e6ca111126f862505509dbdfe0b75527b47a.nq.gz
    ├── 46ecf2e1db02d1ca63349b825cd16a99a334f492.nq.gz
    ├── 481027944d22443a22ee76d2632b03e9878b147a.nq.gz
    ├── 4818d982888109b3f2474d2f02c6a112429c3b08.nq.gz
    ├── 48b821e14021026e2ecaedab79346c165dc14e4d.nq.gz
    ├── 48f5764faf6b92ae646fb5115e30755d19f6395f.nq.gz
    ├── 4a70b9f4e6e2516a99545b109777cdf4f5a9c7fe.nq.gz
    ├── 4a77a6453d1c9258cf97fdab8dcdd11cfb358e4b.nq.gz
    ├── 4a78d5a5e89954dccbb3aa1715d2a663a2c9da5a.nq.gz
    ├── 4b485ee30afcffb35b42685b117d49cd16dc31d4.nq.gz
    ├── 4bce16fde63583320312e102ebf618efb9a4322a.nq.gz
    ├── 4d435781511967444e6c1fb046ec8dab1ff25df1.nq.gz
    ├── 4d59af9a688df4e21c90b07a2c60f0e4a8537832.nq.gz
    ├── 4dd12e8410d85c1c23974b0afe2f5c45eae58310.nq.gz
    ├── 4dddd76b0f644210af2ff8b59e5a0d98ed2aadf1.nq.gz
    ├── 4dee91efecd0123d57350ffa8ee4d20cbd7fe6cc.nq.gz
    ├── 4e2c4c18d724514776805234f859475bfa0df98f.nq.gz
    ├── 4e6b4448a12e90c5fa10e4fb5532c76b44068614.nq.gz
    ├── 4ee7194b6a408ea060b0f0ac3443b25c0bf4d2dc.nq.gz
    ├── 5015ae18ec22497ea4f590cb412b0eb196762913.nq.gz
    ├── 5046ba01c286f9c953724ffafd09c4bc8b2c8a91.nq.gz
    ├── 50551a5c0dfb3781c3a13e171bf61766e212a033.nq.gz
    ├── 50e83f768675d5ca101abfba8217a71d8d7ad321.nq.gz
    ├── 515ba99c980e14033dc54940284cfa9f98c40093.nq.gz
    ├── 51bf9bc3db06b01dfce8faff6fff2c2fa7d5d688.nq.gz
    ├── 52175441e7812a4697b3737f071ecef169432f19.nq.gz
    ├── 527a8a0b52eae6f73fdd6e3f4ea3ee9772b6a83a.nq.gz
    ├── 52c43242f4ec8bb12c939d209e78e20c24c03a5b.nq.gz
    ├── 538dbc741358135613b47158159d1c65c4d4e1ad.nq.gz
    ├── 53b3dc8afceda5693f8c4d2095b179be3eef4a13.nq.gz
    ├── 53cba4e0cf2a24c0cc6f8b0178713fd162b8987b.nq.gz
    ├── 5433e7a1332424e2466889301d80f4929d3042e4.nq.gz
    ├── 54a30e103094b266af0f23abf4f6e433bd292fc3.nq.gz
    ├── 553cb862fa6998b1fb41e7eba9b3573c550bb853.nq.gz
    ├── 5560ec3f2f964b4a8598b8e5f1d5dc14da935c30.nq.gz
    ├── 5591186276ba965ecf5ccae6decd53535bcd138d.nq.gz
    ├── 564763c7b03e34595f47192b87483ca69dc01349.nq.gz
    ├── 5694eecfbf75e72d11d98f4b7ad06f3e4651e68f.nq.gz
    ├── 56c5cc7fbed27268815ce6381d2d07fd1f5db00c.nq.gz
    ├── 56f169ad5618a5314078ba6c579959e41100e433.nq.gz
    ├── 576d4bd26891bf5c220dd040c474b13c21697a82.nq.gz
    ├── 58322c80b4317ce9305bb376d9f09d3d28477635.nq.gz
    ├── 5898b2b5e34645c926d2783609aa17b0354d5666.nq.gz
    └── 5a696fdb373445fb09f226c64a4a58e26838307d.nq.gz

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

[ansible-collections/cisco.ios](https://github.com/ansible-collections/cisco.ios)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
