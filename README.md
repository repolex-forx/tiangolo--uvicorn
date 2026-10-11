# Repolex Knowledge Graph of tiangolo/uvicorn

RDF knowledge graph data for [tiangolo/uvicorn](https://github.com/tiangolo/uvicorn), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/uvicorn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3dd0d44445cc2d96c77037ba1f7bfefd288f370e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3dd0d44445cc2d96c77037ba1f7bfefd288f370e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00dab39b6a23e9d85b82af733900443390fd8c6e.nq.gz
│   ├── 0174bcce6d48de946214d59bcae5543d38d89c3a.nq.gz
│   ├── 02544382040cd438717a91d57820bfb6a45f80a0.nq.gz
│   ├── 09ed69a6cb56eeb6f84b3caa5c88bd7cbdfd7e2a.nq.gz
│   ├── 0d57e87011d8a653273d71f1e290b8274e66f199.nq.gz
│   ├── 0d6b49bdc426ca0417b776c122496e04ceed1c98.nq.gz
│   ├── 0e2fd1eb05efc526f660bcf10e865d2fe781a239.nq.gz
│   ├── 11fc4810f8e025906a9b8107c54583318040113a.nq.gz
│   ├── 153b3d658b4155e544db92e2275301b2459cd8c2.nq.gz
│   ├── 15748a4e82f649f892b1b8424661f857655b6421.nq.gz
│   ├── 15fdd860756b148c68d12074ade5ad6ad8c916cb.nq.gz
│   ├── 1691edd7f61ecfbef3d720375b35890debc36845.nq.gz
│   ├── 1f0b726f8aef8f9a9b22c53988a91c5534129a6b.nq.gz
│   ├── 200e88dc6f7aa0150cd8b7559f891864f8f3bd64.nq.gz
│   ├── 21fd33c2134bb19235e87b7015ca41873b68998b.nq.gz
│   ├── 2285457bf181d31d36b74ba6c368eac604178645.nq.gz
│   ├── 28277e1d60187948fb05e269f94fe259339a6bf6.nq.gz
│   ├── 2b6904b3cac77f1dd7ef26a5be3d819091000980.nq.gz
│   ├── 2e25dd4a9b3bf663046c65b0a0c498a069ef18d0.nq.gz
│   ├── 2f87d94ca10327497ac0f4c0093930826ff76642.nq.gz
│   ├── 32801a8a6c28588d343772474cf9d73b1e70d439.nq.gz
│   ├── 338eba25c03bfdb5e388da6cec906da7729d93cc.nq.gz
│   ├── 34730ec92862c61a5fa2fe045576e7959f2ac6fe.nq.gz
│   ├── 34dfdb1c5e2c25bb8134195464567a322f41ad33.nq.gz
│   ├── 368b982426bf92d96dde6046e1e4ff414079fec3.nq.gz
│   ├── 371fdcaf992afee5d4be1edab7ec1b65e0c232a7.nq.gz
│   ├── 381eca68e4f7a5bbe3120e890aa1c9272036c510.nq.gz
│   ├── 3a510d0ac8529d257b027170d2197589598e91f2.nq.gz
│   ├── 3cc8e19d0394df4a6eda8c53fb4360c097eb1b42.nq.gz
│   ├── 3df267355443a6f818e025b6aea4bcd5677d5da8.nq.gz
│   ├── 3ece31f8813760aab9f6b3b982f65a8661135223.nq.gz
│   ├── 3f04c1dd51ff55f892e102c278171296e5e82bf8.nq.gz
│   ├── 49195978c01a0aa30f24240e24f77929674fcacd.nq.gz
│   ├── 497a09f6b6f2aab18e185a7c6e569017d6314520.nq.gz
│   ├── 4e38223751efdde1eda48258d8422c6d0b32db26.nq.gz
│   ├── 53a4e70db1bcf7dd15b41361504c5c3e05e743d3.nq.gz
│   ├── 55766d3f106da86b7a96d240d8a15a9a2328414b.nq.gz
│   ├── 58927d95eed83505300b3709d4b8d5022f5870d2.nq.gz
│   ├── 62cf4025224401007d5c29fe1f0daa41258148f5.nq.gz
│   ├── 666390ac93173efc412d0ca5f0b6ac4d4790237d.nq.gz
│   ├── 6ce92feb8134915dd94b03f742cfd3caeba987b0.nq.gz
│   ├── 6e2e0c359cb41ef67d09fd6666f2aecc73a65745.nq.gz
│   ├── 74e864ed3db657bfae0dcd8a9a4f382589314d78.nq.gz
│   ├── 75145f73227f9acae2a4598495c9a8b741fa89f1.nq.gz
│   ├── 7929f3a91052da5baedc104e342eaba928aff2ee.nq.gz
│   ├── 7d6cbb864e2fe6475794fa8447127767b429c386.nq.gz
│   ├── 7ecef5559dad3a4bb09ad3f3051fa7a0bee6b8b4.nq.gz
│   ├── 80671396ba940ec2403d4c64ef996c2a88929269.nq.gz
│   ├── 82dc1118ac71e03e8c02801902c195e46a9f9b48.nq.gz
│   ├── 8a1dc979a39e36ce81e987843391479f125d73f3.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 909064651d16528a5e1773ea11c12cd262ca70bf.nq.gz
│   ├── 92378cb9429e9f1d5dd1f40776be7e2d624f856d.nq.gz
│   ├── 94508f55fec5b4a21a11efae7787a4bcd51b939f.nq.gz
│   ├── 96fff19b9fc2212f6f3e8fdff4ad57995f2c1702.nq.gz
│   ├── 987909fd6dbe86f048d967b66ab8630ed326d3be.nq.gz
│   ├── 99c868c3110dc0381edd8dd831e4f0894e8c8600.nq.gz
│   ├── 9c62460fe38cadc65bca511c6adc5d3410b1c066.nq.gz
│   ├── 9c638cc0117acf0081dc8efa19ee77cd925ef73f.nq.gz
│   ├── 9ee622e0d43ac0810a97620a67217835fcf9b5e8.nq.gz
│   ├── a14bec144a97a5e3718a768abe3b6a9e7e93d2c1.nq.gz
│   ├── a2720c574c99861e748a3347c97301ed43a2250e.nq.gz
│   ├── a405c317518333c96b56959b0d9bc0829346d5d4.nq.gz
│   ├── a5b2af17eb7dfebe55636bb4dcd69337ca48c88a.nq.gz
│   ├── a6bba14552c7673a7db57a5750ddb06508264273.nq.gz
│   ├── a92a445ac5bdcfa44d4f9e0a8030e54a54b1a449.nq.gz
│   ├── a9cb73e3a31f4ffa670dd6d51be265dd88ce41fc.nq.gz
│   ├── aa3b0e733b60e0ea9ae15c8371f2d283ebc63e32.nq.gz
│   ├── b0dff4604e55fee28cc7df9a73a7d47653ef1747.nq.gz
│   ├── b1f4cae1bb219904a88eb3839db5e4d559fa99d2.nq.gz
│   ├── b24f4fe0db109f8a1e8dd14dfca4510fb79c6ac3.nq.gz
│   ├── b5d18caccc9a38d560012021c9aa720507b36d82.nq.gz
│   ├── b7730032f339c2dfe497a2f5e21f3f9b94f43ea7.nq.gz
│   ├── b9038ca113b22b96ace2812d6412914a3541eed7.nq.gz
│   ├── bc49f34639e07a427830ddfeea479ec5bb92fe4b.nq.gz
│   ├── c6b2f27812db4f34b7f56dcc751ace64cab8f13e.nq.gz
│   ├── c93e45e858d092b47f327afc88d40b6200efdb71.nq.gz
│   ├── ca06b33a6ad4b9e1d8aeb16f1980e0e6755892a2.nq.gz
│   ├── d463779360a90ed6c2c653f751c9ad9b0b78ea8a.nq.gz
│   ├── d60bcf54e24905f9c64c72e130861c73f9fbf5a2.nq.gz
│   ├── ddd80cf76991d832f0cc36b14074564997b70cba.nq.gz
│   ├── deaf12ede336bdd4fc60b27aee5d9b1888052f57.nq.gz
│   ├── df2415f2e704a0c5cfc72a9ef4d9ba10cfb3301e.nq.gz
│   ├── df642c7b6f585e98f62fa2fd898bb57a493bd4c1.nq.gz
│   ├── dfba2c20c5284a2afee462d00d9ed08df278e570.nq.gz
│   ├── e1516f16af255289df666ce52f215a7740fd9507.nq.gz
│   ├── e1cb311f2e8493240c16e8e4773d308a6ae20bef.nq.gz
│   ├── e458b9234360d1ef90096c50d41268e5d5b6670b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed2bdd01ab2a758593e6ea1eefe52c440dc4e7cb.nq.gz
│   ├── edd300997c861fb10aa968dad9590df20453b7af.nq.gz
│   ├── f32721a6c28b7c371d56620d62385031b555e05a.nq.gz
│   ├── fc8f0af5019d52731f0fd885306449709e05056e.nq.gz
│   └── fee6c5b4cab70e1b038fbd6697472158c5959ca3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3dd0d44445cc2d96c77037ba1f7bfefd288f370e.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 100 files
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

[tiangolo/uvicorn](https://github.com/tiangolo/uvicorn)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
