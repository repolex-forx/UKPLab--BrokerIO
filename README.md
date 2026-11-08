# Repolex Knowledge Graph of UKPLab/BrokerIO

RDF knowledge graph data for [UKPLab/BrokerIO](https://github.com/UKPLab/BrokerIO), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/BrokerIO
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 50638fc4df33900f35fd2c2a35d9cf03715c0819
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 50638fc4df33900f35fd2c2a35d9cf03715c0819
│           └── chunk-001.nq.gz
├── blob
│   ├── 0036d08ff3acfda83bef7a915ef7f4e941f20a4e.nq.gz
│   ├── 0349625cc866ca2c7ffd03401399d352c77f6fe9.nq.gz
│   ├── 083f950e04596ec447ee454e6804734978f34ffb.nq.gz
│   ├── 08e2db7f9044c7afe758c4c25c59d5a93385d369.nq.gz
│   ├── 0c0116233fe72a0d3e3557c9dc0bcf4386eec63a.nq.gz
│   ├── 0cd746df594ed849bbed93c74dec2b0a6eec6bc4.nq.gz
│   ├── 0d433f76882b1b272877942fd50433b88da75678.nq.gz
│   ├── 0d6e6c5a59371dd12519fa9111b9ddb562efa945.nq.gz
│   ├── 0dbf6601a34d2c6bb3f2cd1ecbdb63a13d362794.nq.gz
│   ├── 0f83d1f455bdbc73f5c2dbdb0ef857e6f02ab868.nq.gz
│   ├── 101e44139532deedf162b771f7cbef733f7dc969.nq.gz
│   ├── 12eeb4297efbe7355debab0da4f56b6da58239c4.nq.gz
│   ├── 13713f2109990bc3b88448c97296c8f0de277d41.nq.gz
│   ├── 139debb4bdcd91533c70c962de981d5ad0beee69.nq.gz
│   ├── 19f754d89e1fe4b5b0a5d6956e07ced4e46de655.nq.gz
│   ├── 1a12f0d143aca7347faeee84554c4e5d33491cae.nq.gz
│   ├── 1bc643bcf0c71640c69c52f7f9b20b66d5b2942a.nq.gz
│   ├── 1d1fe94df492104ae6b144c08727a0fa8f15ab86.nq.gz
│   ├── 23956316cd815d0f7f2667ad393ae45236ef8d5f.nq.gz
│   ├── 26521a45a0104126cebf7c21956e4c38d78e858d.nq.gz
│   ├── 27dcb010346c57eb3228b239a830ae69f3f171ad.nq.gz
│   ├── 29854dcda2b96429f8037e04e6c2f5f57038f20a.nq.gz
│   ├── 29e46c91ded2af9ebf302be2303fa22b8d326fd6.nq.gz
│   ├── 2a9fc93c7f9c825c5dff20eccae1d6eb6b6f44a9.nq.gz
│   ├── 2b29ab9959d731f4a80413ecc6448d6da3290acf.nq.gz
│   ├── 2e2a293cb4383e0a36c67796a187e8404a447735.nq.gz
│   ├── 30483b307e1789cd8a8545774cbf5f17b38a38fa.nq.gz
│   ├── 3146183c8896d1c67079c3d7b76df2dccb13c9f3.nq.gz
│   ├── 31cffd57f81e3b2c5e6fc5bffd501c8ccff9f27f.nq.gz
│   ├── 3213b290879a435076223143b81ffc7b5f2970ce.nq.gz
│   ├── 351b2ce909198a89a61d8972b8f210f18607b25a.nq.gz
│   ├── 363ecbea2fd583384d873022639e182eb54e0bc2.nq.gz
│   ├── 37e47a9d9e2c379afc497a3be93d2b79d44c4c64.nq.gz
│   ├── 37eb4189879a52feac84b32b38d98d95a7a4bf90.nq.gz
│   ├── 38a1cce9d707ae2aaee663deae22e347e9902132.nq.gz
│   ├── 3e2b34212eb322cf1f15fb6a6e815485f2e10ce0.nq.gz
│   ├── 4305fe26eb3066c990d110dcbd48eeb10d1ea7c8.nq.gz
│   ├── 44039793e678bc49bf52aff5fbad5ed41a00a1bb.nq.gz
│   ├── 4670c9e45c900b106074f7cfdb6f753eda3a522f.nq.gz
│   ├── 46b2f050458cb83e3085ce50142c661b0d9766f1.nq.gz
│   ├── 46fbc07c5243c14629058df1298f7f4f4fb1073f.nq.gz
│   ├── 4c3df1dc07f53fd8b54ae8200882994b506a209b.nq.gz
│   ├── 4cadc5ea9b6b894578875aeb85e52fe18ef7f6a4.nq.gz
│   ├── 505930ba68875b4d20343d906e6f2238058516a0.nq.gz
│   ├── 55a433545a5db6a4c89ef66bbc678cda7f777827.nq.gz
│   ├── 5e60a763a3f9bae8480c9394ab181b5393a96c64.nq.gz
│   ├── 5ec87f8bc29fc8efe728b8c8f1cad51723265bd3.nq.gz
│   ├── 5fe7d4d75ab574393c33a826d6881f344659419a.nq.gz
│   ├── 63709c29acf38e76053c557beb5683b5534544ea.nq.gz
│   ├── 6373f01b82be3125e485ed42654c43cc0d31af1e.nq.gz
│   ├── 650bf066b1b4aa2ea340b62be66ff82967bb47fd.nq.gz
│   ├── 69217851ab8288ed5008e0661695768fb78b476b.nq.gz
│   ├── 6b1db9feab5765894e01a5ee0f7f7aa8163cd987.nq.gz
│   ├── 7090e4b6c7dc3b750674c5188595c672a8e3aeda.nq.gz
│   ├── 713bf4adf3faa093f00ff17e2ed9ce50e4852a91.nq.gz
│   ├── 71e09d6d966d3c4063a38e27f2ebc42bfba71141.nq.gz
│   ├── 7667f155175945496780bc48db78601591cc6273.nq.gz
│   ├── 786016de78bc1aff5897ef15e4db1bf51559c039.nq.gz
│   ├── 79386580ba4b954ce187b65a7fe1238e7da5171c.nq.gz
│   ├── 7abdcba72647def363f64f8198201b9fd7f54473.nq.gz
│   ├── 7ffaaa9f5ef332706a4ce7f7d98f2cc09957a413.nq.gz
│   ├── 809deabb06957856dd0c299a841adefd6926206f.nq.gz
│   ├── 81d164253b5a83824e0042657291d6360751234c.nq.gz
│   ├── 839efa831c1361a2735775840061259633c8f55f.nq.gz
│   ├── 856ac10a481dca93674b20edcbe49a52013ec58c.nq.gz
│   ├── 86450d09e70d9d99c06daf46494ab7f5ed614b22.nq.gz
│   ├── 86cbe991282c572714587fe2b2eccfe2e538a561.nq.gz
│   ├── 8a309b9b136c3f6a7b7e495f272557b822266c9a.nq.gz
│   ├── 8a72556eccf7aa8ce2579a9f5ef7330460627fa2.nq.gz
│   ├── 8e3b99d229b7d05fd6f99132dc8850705ff52b79.nq.gz
│   ├── 93ed2b62009b397af69d6aa0e06b6b739cb0919b.nq.gz
│   ├── 93fda1f9cdb48568552a7b9120f0fef8537e1c86.nq.gz
│   ├── 947966aeef9c2e0a8a89681fcb1ce3f9664572f1.nq.gz
│   ├── 948e37b2d853618e5e9c4592694e8acbfb85eb49.nq.gz
│   ├── 974fe528f0de8fffed4dd8ad2fe73a4d03e4cd03.nq.gz
│   ├── 9a198af700d15b389ba863bb4015fe6fb21da5db.nq.gz
│   ├── 9ae637f13cd528a1823ec240ed01b3bdaaa19967.nq.gz
│   ├── 9afffb8c1402e9429e2d27436365209405019b96.nq.gz
│   ├── 9b14517ccd64a4f34cb7f5f8975bf84fc06cf2bb.nq.gz
│   ├── 9e711cb5360756bbc4e4749e1dc0e5e1b6d6caa1.nq.gz
│   ├── a02300a230b11c341a52110f6082e8740914058f.nq.gz
│   ├── a16e966561ca0f4e1282e0be3d69a78aa2f89383.nq.gz
│   ├── a3cb3c54594a42a9c3813398ebc016bcad189c51.nq.gz
│   ├── a4ad027af2438b2289a16972e4cd94a9dd386be4.nq.gz
│   ├── a53644cedeafba6b6e44507e71fbeff525b5f94c.nq.gz
│   ├── a58416e69bb383a78dff2f1e584eacab9ff36a41.nq.gz
│   ├── a5f51aeed465f7a6054dca6a5f53bf1730584de6.nq.gz
│   ├── a6408bd4d8279939fd68e2fcb0a0919eda4136ec.nq.gz
│   ├── aa69424c5ea7eb025dce3f4cf576be74ba781734.nq.gz
│   ├── ab96411eb0e37ef7bc53ed1b4443a12caf0e103e.nq.gz
│   ├── accfa34ea46b1130ad397d6ee28ccf8b6e04b0cd.nq.gz
│   ├── ae96279e91ad270fe797b010f30582d6e980d200.nq.gz
│   ├── b1484c5c3d4acd49a724ac9653086e847f4939fa.nq.gz
│   ├── b5c311c2714e52fd0702237b02cfb90c4545e992.nq.gz
│   ├── b7ef3c075b6fd0723dd42a84f9852d94f89c21ec.nq.gz
│   ├── b920606f3d74791815ea27e31187db38a48d21a4.nq.gz
│   ├── ba62b6ece41df126d89fa93e476c4c305bb68450.nq.gz
│   ├── bab7d125f4b069eddba2dfa8b8006ed5fdc3ecf1.nq.gz
│   ├── c35ac3bebe1f7ede430e5a97fe8f605c956db9ee.nq.gz
│   ├── cbf2b929a4ef0b35b0b2bc76e1cf92e275cfd71e.nq.gz
│   ├── ce45b9ad4a9ba5c376e120d03a5d20c14594826e.nq.gz
│   ├── d07eda7ad4b9ed0f033934b83bc4dc69c82851c5.nq.gz
│   ├── d090b14054b5e56fb3df35c64a578b7741a6f312.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d460d519243ca0e572c7c884056fb4371631dbf9.nq.gz
│   ├── d82fa4dcd670092ebc3f6d2e98b144871ebc28b4.nq.gz
│   ├── d88309ccf3c76bc8523c30e54ae7bbbf139f77b2.nq.gz
│   ├── dbe315a785e0ae1590762b536e1553d693ea93a2.nq.gz
│   ├── dc1312ab09ca6fb0267dee6b28a38e69c253631a.nq.gz
│   ├── dd3c36939ec542e0eba4c6eb4ee7a37498094d7f.nq.gz
│   ├── de6683422a4f9dd22f7dfbc1724bee35a4437275.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e55fd64b5aeece8f7dc1d3f8c3c25da8c86bc6.nq.gz
│   ├── eb5470fe9872829854a88933313e615fae85ef08.nq.gz
│   ├── eb934b21503ff4751a06b2bf722dd3790f343db5.nq.gz
│   ├── ec55442b3cf7dae54581456adb64347424720409.nq.gz
│   ├── f23cd389b0fdfeca4e2240f45d6f98401da848d3.nq.gz
│   ├── f25b4fc5f69f12680a2fbf0a39c2ef1c64c8a856.nq.gz
│   ├── f6efbbbfb34a3a9c775f33b696600cfb34492e70.nq.gz
│   ├── f8434ce44c73054b8d0a0cfed5610672f62e94c9.nq.gz
│   ├── fa5c68e2462a09efaf3155b32ef9b0f92b89ce6b.nq.gz
│   ├── fa69eefe557612861fb50dbea30a2d6ad07ee60f.nq.gz
│   └── fd41c2caee6465a9b2fca091182a4f781091d420.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 50638fc4df33900f35fd2c2a35d9cf03715c0819.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 129 files
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

[UKPLab/BrokerIO](https://github.com/UKPLab/BrokerIO)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
