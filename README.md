# Repolex Knowledge Graph of py-pdf/fpdf2

RDF knowledge graph data for [py-pdf/fpdf2](https://github.com/py-pdf/fpdf2), parsed by [repolex](https://repolex.ai).

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
rlex download py-pdf/fpdf2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aee7cd1174342356bb8e76740a21db4bd25666aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aee7cd1174342356bb8e76740a21db4bd25666aa
│           └── chunk-001.nq.gz
└── blob
    ├── 0020e30abce628538ee7bebd1ba76efe20179f52.nq.gz
    ├── 0045aade37693484bd88e4c5a86b111cf6c3daaa.nq.gz
    ├── 00a7cea6c2d3c36627718a502eb14c812b0b7c46.nq.gz
    ├── 00a9c50dee06a693659ba31dd0678974229ffe8e.nq.gz
    ├── 0159444b994e15b23b77115a7991eb755f5024aa.nq.gz
    ├── 039c9a85f115f4325ad1937f12e9ac5bd8b042f0.nq.gz
    ├── 046c23f50d785917390048ddd4c05e58cead9808.nq.gz
    ├── 04e1713d5b137fc9ddc537b78a7ca46d391713f0.nq.gz
    ├── 052f2f8072d6132f74ffce2595ab63447474bbd7.nq.gz
    ├── 05711676ea80750f3c48c2f8460847d6546a915a.nq.gz
    ├── 06b35cf053d63aafb1e1aa059a851fd9f8b7bab4.nq.gz
    ├── 06f7dec5bdbf65a8d9d2980b7ef155e3d4363b9d.nq.gz
    ├── 074bcdd7c8ca54bebc2cad9ca07ae8283fa0f4a5.nq.gz
    ├── 07822461f1751cad3e985d7d03eb548d99c2313d.nq.gz
    ├── 088e9db5b364f87eb0d393e64848a4e97fd0405c.nq.gz
    ├── 0890ee125b1c7721d2bdd2bb7d32d638d93e998f.nq.gz
    ├── 08a016a14fdaa147f091ed7fa79abdd99aa41221.nq.gz
    ├── 091a6df2295b0e9122067f1b21d4bc162959d1ff.nq.gz
    ├── 092637deb79f8ce94c938702dac059af5df66bd6.nq.gz
    ├── 0928b660dd227033c1878d905dcc56071480e745.nq.gz
    ├── 09326947ffd729aa11a159a4f71d1d90089a85ff.nq.gz
    ├── 0b09c1a12cc14ab9583dfb1f726563d101b71542.nq.gz
    ├── 0bc497a1b624bf6714fcf6b061e4f495aff28a3f.nq.gz
    ├── 0c393cf6d8be375b757065e406e067028a8adfd0.nq.gz
    ├── 0ceb7e06233b6377bdb9e9971613d2df0fa2708e.nq.gz
    ├── 0d8de9cb734f021c85657222e697cf52a1d0f2d3.nq.gz
    ├── 0ddad07e5f5de86a61bf43d8b89e138d7f1ea8ad.nq.gz
    ├── 0e710c2c397e371e4feab66add6a9f9763ce0c27.nq.gz
    ├── 0fbf9e827b467d65dc252db937d6590478bbf88e.nq.gz
    ├── 0fd6e18fbe35d4eb1c7e5a236c4fedf39d8f843a.nq.gz
    ├── 101f087d4713af7cb206101e8e1fe5db7ca2f105.nq.gz
    ├── 1061068377cd971bd57a451c4c13c1c3f0c8081a.nq.gz
    ├── 1143962d2ae740432403d4bce3205b2f075312b4.nq.gz
    ├── 1258dc2e480fcfb6ff31e1d67f781184009ad216.nq.gz
    ├── 1299d728150dbb3695faefe11aed83061706f45a.nq.gz
    ├── 12e62724c4147a2dfcc4b748e5a3528fc42e4af6.nq.gz
    ├── 1306ab87f117012556c34018398a600b7ddcb239.nq.gz
    ├── 13c0890b2b279beb1b70bd292e15258c2ccc94fb.nq.gz
    ├── 13eb019fcd3ca3cbbe589429e72e89fd53b9f4bd.nq.gz
    ├── 1499b89e75319e54a973f81b8ebef8d8fcbebe40.nq.gz
    ├── 158713d719efa8477296a328b1a36dd9fe90f1d4.nq.gz
    ├── 15c755762e1678731198ab8a5a159a413251d93c.nq.gz
    ├── 16811bfba52446ba6f749b2bf695125ae733aa6f.nq.gz
    ├── 16ad86401ff1b1043644a4705c66fb738f3cce42.nq.gz
    ├── 1726419d00415cd5e7e02f14a669ed65dd280dc5.nq.gz
    ├── 17f2991484c2a269925be2140f5a60ab15a0dc43.nq.gz
    ├── 182ef4ad008a2eed646b7bf7ab6687269de5e809.nq.gz
    ├── 1871beb4bd24f1a66ca9b598ba601f76cf6a1eb2.nq.gz
    ├── 189de6aadfb3878bc154c8e4f41c6be984d930f1.nq.gz
    ├── 1b6a6be2ca571956ce45bae5470c03cd2266fd89.nq.gz
    ├── 1c9ec3600c9ae74b2b195124d5ca4569e55f45c9.nq.gz
    ├── 1ced56948353b4298e81eb26b7c71c2ce93982dc.nq.gz
    ├── 1d65bd309db1a64d14ae3a0c4bdcb3cf5da66301.nq.gz
    ├── 1d929a4ae2b31442b2024364767c31355a360439.nq.gz
    ├── 1f120e435e8ac9ba6f7fe2dd740324dda7b0f79a.nq.gz
    ├── 20015505c9d44fda6483acf62a83853bfaaa451b.nq.gz
    ├── 204639e1309e2ec9d3aab699364bf4452963676b.nq.gz
    ├── 21426ad495aee4173a8d8392adae0c92f6b91e0b.nq.gz
    ├── 2174747339b4b1682b1a795bc970f10c880d2ae8.nq.gz
    ├── 219112739d08748101673e4639d69144e1078649.nq.gz
    ├── 221ae5f66436144c2e68c6fb17b649486770fc73.nq.gz
    ├── 22caeb26bcdeb463ef99b6d357e2809eca6a55cb.nq.gz
    ├── 245ffed07fa7a29ff5842735141c155af06723c0.nq.gz
    ├── 248ddedcfce117e8db489401e60de6cfa56845d1.nq.gz
    ├── 25473494c9c94391b4ed23281567461210b183d5.nq.gz
    ├── 257684cd0c246d64a05f82ab38f0a53d96fbc8e0.nq.gz
    ├── 267c8ee7ea57b1156f1ecd164c99b79ffea693c5.nq.gz
    ├── 269f4a1eb217969e5e03644dbda5994996b175e8.nq.gz
    ├── 26a39c65d02bc08809888116e4460eefceecb6de.nq.gz
    ├── 2712bc3637d5d4842bdf021fbc970bcb68ecf2b2.nq.gz
    ├── 2748576e7fa9c11447b93be0294e129332ff06cb.nq.gz
    ├── 27dfc6c826d2a82d4095a043754b4628f6ba924f.nq.gz
    ├── 27f050cef34ba13b046f7f6a33ac4072db68c919.nq.gz
    ├── 2802c6169bd50e28fca305a5bed3ba8c18c54c8d.nq.gz
    ├── 28096ffceb427cd726945a9086ccfdbc880673d4.nq.gz
    ├── 29535b1987a14d4d9c1a23f442884a1e14e0d7b9.nq.gz
    ├── 297babde3524b0ca9ca55dfc24b6437e846b6101.nq.gz
    ├── 2a1d12595f29540b0537da8663b5d58cb3e6093b.nq.gz
    ├── 2a546cf43250ee4814039fe24f9e500724e23e43.nq.gz
    ├── 2abfdaef8bea1b27f2c5384f0c2dc5ad84b39946.nq.gz
    ├── 2bad470f758ebfa50030ee51f46233302892d586.nq.gz
    ├── 2e208462f1f7c73eb361434433b0255fca4420bd.nq.gz
    ├── 2f001610a85a662d8baa0c1f02c06adc02cfa20f.nq.gz
    ├── 2f089b3fa0883027d68f3bac3df0fe012894a73d.nq.gz
    ├── 2f2236757a4c6c9b56c78f282d349dedd5245e12.nq.gz
    ├── 2ffebe62c85914ea5b44de59b5b8b930e2d85465.nq.gz
    ├── 30bdc15f3887fb85155e9f126a8bcc439ab084b5.nq.gz
    ├── 30e68c301189c45c9d2451c030c62e41b988f210.nq.gz
    ├── 3161ce2a62ca94a6fb87a4fb7849eee0e8f4737b.nq.gz
    ├── 31da99753fd43678d1da091aabbcda3c83f0b6f2.nq.gz
    ├── 31efea7737ca45e25dbe1c521e9e56a4c30eeebd.nq.gz
    ├── 32395b76c9c0e1cb962743e8a9c8c41f319a26bd.nq.gz
    ├── 32666d331fb1f11fc479537f75f8e24ac7e8c807.nq.gz
    ├── 32f8d6600866173afd28ecb521ce38382fa9af5e.nq.gz
    ├── 33015cc43eb38ca8570030c2e4774e3aca422a7e.nq.gz
    ├── 333465fcdc9f10f7f25b2d999b558f5421983ecc.nq.gz
    ├── 34d412d37f5bc7b7d64f853f9773ca70b8e86ced.nq.gz
    ├── 34da080e3a43eb96ca5ed5492e952804cef7d728.nq.gz
    ├── 353873ebbd0ca66c57ec7f6488e8f18a1c3517ac.nq.gz
    ├── 3584252141b72cf2490b84088b92f159f88732ee.nq.gz
    ├── 36621d1ce3c3b8436b02222a5409266015648e1f.nq.gz
    ├── 37c6dfa0a6f57f32da4b89f32ff6f705f6365c7d.nq.gz
    ├── 38aeafa0023cd436d0dc56bf76239d965a87ae6e.nq.gz
    ├── 391065662f0d3f2b45c4fe6c1d448850f8c53ad1.nq.gz
    ├── 394c6407f4a7255758d81309ffe6a8f518222f55.nq.gz
    ├── 39acff270922d7351044e90e11c604180844c0ba.nq.gz
    ├── 39e0e1092b561d5d8a7e9ad287d68ca3ad355fcf.nq.gz
    ├── 3ac8994b6893e1d62b7912d8d73d42ff2e5c2aa0.nq.gz
    ├── 3becb286d28c11570b49c1d91ff4a8e56b3159cf.nq.gz
    ├── 3cb2a0b50e29b9575a0810f9e358f3b3a9eea30d.nq.gz
    ├── 3d3fb7121bd42bada0113e0db461b20e36ac2b63.nq.gz
    ├── 3e6029fb5504d38a3584f13c263c57541dc6d7bf.nq.gz
    ├── 3e911ef85bcef3c784d3b5a900127e3f64f0c2ce.nq.gz
    ├── 3faf213972921b4d6f2a897229f482dc066f3728.nq.gz
    ├── 4034ef603b63fda54845b204fa49c1c27cd3750d.nq.gz
    ├── 40e561806fc11c73b1ad6f825a5e44ed9ab1fa80.nq.gz
    ├── 41083ca80f964707b6b89e1cc1266e381710175e.nq.gz
    ├── 4181533ad81b739fb7b4f3b024f632cd7baa85c5.nq.gz
    ├── 4259261a9e78505bdc9f4e1972d6a68430e5b21a.nq.gz
    ├── 429d6baf95c3ccacd3742d9c74df26a1758be1a8.nq.gz
    ├── 438c5aea3651c822f945032f8066369182cdfb73.nq.gz
    ├── 448b93d3f05615f3c425251eaeccc450c58034c4.nq.gz
    ├── 45237a1d294f7432c06ae45769727d9745250221.nq.gz
    ├── 456ada3200643ae917af3ea3f9fa0df7471c0660.nq.gz
    ├── 45a007596753f6627224931755c073a3362be88c.nq.gz
    ├── 45cce1467e91155ef8f5e28a58d0d35e5bc47862.nq.gz
    ├── 46f098adfb86dfd67fba881a16a8616ead4f648a.nq.gz
    ├── 46f9f9ddd6ced6e83b4670996b58a1502076faee.nq.gz
    ├── 4735611ecb7518fd42086227fddac1daca1b1c56.nq.gz
    ├── 47c24817b79c1e2df8eb3f4fe43798f249a063d6.nq.gz
    ├── 48530a665299d8a913cde1cb5f78d50bf18c1e7f.nq.gz
    ├── 485808735a4f93aec101e85e60c41324535f86e6.nq.gz
    ├── 48e7746e468aee36e1d7032530394ba80a0666ae.nq.gz
    ├── 495b73340c98979aff9974778e4942a46a9db1e7.nq.gz
    ├── 4994474d935b879c2a2246c739d49dc3d13d3b1f.nq.gz
    ├── 49a8422185014bef3775cb3c1b4723a39f3485f2.nq.gz
    ├── 49afbfef10f22a1832590b68369d2f248ea553b9.nq.gz
    ├── 4a537376e6f36707cb36880ea15c6d39d7eb0bd6.nq.gz
    ├── 4a801fecf621382985df5de7bee492332b4cf472.nq.gz
    ├── 4b1848c76f867fa8c90572cdd3e19884d20f926f.nq.gz
    ├── 4c9b8c7c9e51ced7324f6a271358d1a2e2922d86.nq.gz
    ├── 4cbe766355929701b9d0277baa5eaaf344633176.nq.gz
    ├── 4d0c0c413489907f98cda536eece50e078f06af2.nq.gz
    ├── 4d593172e03ba7db227b90d1226672e30f2b47cd.nq.gz
    ├── 4d90467bce441bd1b7e3483f6d3e15f250807d1b.nq.gz
    ├── 4e358be418efc06947cdfb57b92516ec742d5a45.nq.gz
    ├── 4ea66cafa4f14065f30ffe04145a68ff4ced1664.nq.gz
    ├── 4f045d07e6f3031d58e53e0ca970b546584bb069.nq.gz
    ├── 4f4c65a46067519ac3ac1ecb58e7a4ce745283e8.nq.gz
    ├── 4f943c6175f31c3609bf4458fff9d3c591f112f7.nq.gz
    ├── 50c1343a68f41a2cbe08c7657d44fc02c6ef9b1b.nq.gz
    ├── 50cdef2a85ecc8a8f61687567c16a6c2b863816b.nq.gz
    ├── 537635d409847d2b46d2c5ff1f82b07b92d28e56.nq.gz
    ├── 5408c36ede76656c997c7b01f5fc9774863d259e.nq.gz
    ├── 54ff3ad3a1336cc6cfae381abd724cfac74f970d.nq.gz
    ├── 5561211c54e90dca98c6089d2c6c6a65935ee3eb.nq.gz
    ├── 559e5261e705daf7a562a18eee445ccc35990e97.nq.gz
    ├── 560ce302cef7bb1d3d81a67df87889601ceb58f4.nq.gz
    ├── 56a07aa9aa306916f15a2fbf403c966fd00f5b06.nq.gz
    ├── 56eb734991497525b489b9baaf275d2e71d25683.nq.gz
    ├── 58b3d68a5045336234dbe0f78f480a17445816cc.nq.gz
    ├── 597346460f1999fb225a46c941751a063ce744f4.nq.gz
    ├── 59c340838de9533a99a9e2fed9c068da876eb2f3.nq.gz
    ├── 5a8e95aba75added3bb61750ac246033862ec97e.nq.gz
    ├── 5b6a144016b7ab20009351a3147dd3341a88fa9e.nq.gz
    ├── 5bbf7d4bfd155d1026bbd3ad72c19bbc92b6608c.nq.gz
    ├── 5c27b930b27a5c5e76d4e773b9004f2d2c02fb8b.nq.gz
    ├── 5cca0d621047cacf1637cf7d77e997d51cc6b15a.nq.gz
    ├── 5d4d7db28f281537203da5a92a4d11bcb5d8cf9a.nq.gz
    ├── 5e493c20008baec923ecd51fc9a148bab3e04355.nq.gz
    ├── 5e56897ac98d37a0a9f8c0ecc76da40399c2449b.nq.gz
    ├── 5e951b383b7e1562fd46c3fc7b177a9a0223cb08.nq.gz
    ├── 5eb8441ab9d0cb805662089612e3e27c858f8cc4.nq.gz
    ├── 5ebf4e817886ab8dbab30996864f3c2d8b318fc8.nq.gz
    ├── 5f191a78ee5601a45f1add2a3ad7a77b7b1ae0f1.nq.gz
    ├── 60396c95af19fc5f14aff9f83d391331a32b3dab.nq.gz
    ├── 604bf515875b11939711cad95c4ce3d6ebeef335.nq.gz
    ├── 614c5d99088b7ff34117a73c3d73490a300d7a10.nq.gz
    ├── 62886a7665c6bbbf5088ff9c686f330017b49c07.nq.gz
    ├── 63021b2b4978c9e838ec3111f930ab0d846db717.nq.gz
    ├── 64e887d46ae6711390bbdd423b1419304a3cb6ac.nq.gz
    ├── 653afd4fce0f87a90483150a8bb6cc9caae16705.nq.gz
    ├── 65d07ddadd9e16c2eb1abdc6b5bd5809d3fd9107.nq.gz
    ├── 6600f1c98d995efe077a253b2314cf26e633f32e.nq.gz
    ├── 661a5f3cbe044f8c215b07e13c1a35a89066a67b.nq.gz
    ├── 6678a4dee32544acff3ccf3c499ddec4ceb3d3aa.nq.gz
    ├── 66e9c5e012e3c04ced62e1943f67c5f28450443e.nq.gz
    ├── 67cef556d1815e6ec7a01d8b7b450d352bc4ca6d.nq.gz
    ├── 68598d7e11aee0bea43734222cf4249812904004.nq.gz
    ├── 6863135efe171a5216b18951b58ce9a3065b0f83.nq.gz
    ├── 68b4d566c8b6f77493c4c0b657f2a2d91cc6bb2e.nq.gz
    ├── 6941cabb9aab92f4162520fbd6c20f2d369b5356.nq.gz
    ├── 695a20a54b2aaa2c4a7c7e6dc7f04cb27fa0cb4d.nq.gz
    ├── 69fdcbff36e6fd65a4cca70485d8cf5f44d38037.nq.gz
    ├── 6a0d1f2616a4d66b8c363785f6d87c3f4bc44cd8.nq.gz
    ├── 6a44fd6d594d5afdc145ba9229537417db8cedb8.nq.gz
    ├── 6b00f9b9972f667c86b75ca6132b8e36f28fdf10.nq.gz
    └── 6c02175744bbda5467c042e7c27a6094b2a298d2.nq.gz

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

[py-pdf/fpdf2](https://github.com/py-pdf/fpdf2)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
