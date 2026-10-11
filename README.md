# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-qthelp

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-qthelp](https://github.com/sphinx-doc/sphinxcontrib-qthelp), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxcontrib-qthelp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 783caf58e9ba9cf0450746b7f65d4bc8229ccd8f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 783caf58e9ba9cf0450746b7f65d4bc8229ccd8f
│           └── chunk-001.nq.gz
├── blob
│   ├── 005143ed2112e47724cb25cd889d27d7fc757114.nq.gz
│   ├── 00e966b65478c3be480a1b17e6e088f1f104e4bb.nq.gz
│   ├── 010386b6638c4b228734132fd36f01ee2640d052.nq.gz
│   ├── 0110f11b37ba54b71a05e0c70dda49ea398ef164.nq.gz
│   ├── 032089a333b195ff675619e6cef905cc90b426d4.nq.gz
│   ├── 034b098b0c7340fa3f15b0d0a2a8f953e99f96cf.nq.gz
│   ├── 05ed1f47e1311870340f6590e8d26ae87ba51eca.nq.gz
│   ├── 07dd0a0a3b9b87600cfbd84c5dcd3809d923902e.nq.gz
│   ├── 0948d3c47df094e8333ee2242f1197fba59e1081.nq.gz
│   ├── 0b3cff860edc4a5e40fba9925e93b3ad5a0d0862.nq.gz
│   ├── 10cef947b5c9825090a209f2e6a9f0409e20de24.nq.gz
│   ├── 115125c02ac5e2b5fc8ecb56f6848b7722e3b0f2.nq.gz
│   ├── 14e80e504fdb6e82978579867d4c2dcbe577da3d.nq.gz
│   ├── 1663b0c81608095446dbc487630662436924a3df.nq.gz
│   ├── 18666d9cc935f62890182ac82f30f16904ef7f3c.nq.gz
│   ├── 1c17c86034755a7eae357d2d2225b89104b290e8.nq.gz
│   ├── 1cccd3cb760503dde6a2b98453b589662b03c023.nq.gz
│   ├── 1e8251fdddfec330a828c4aa32ef3b0dee581e06.nq.gz
│   ├── 1f83bc3a7580529532547caf110e7e961decdb76.nq.gz
│   ├── 20bd699cc683de4fd0725bc399ff8857ebd96519.nq.gz
│   ├── 26176b9477e9602df2fd655da28c90cd097ac00a.nq.gz
│   ├── 2a8f2e131f841a647d0947dc89c4cdae43626e55.nq.gz
│   ├── 2ae378228e208f861234ec0efa78057ccb0a4733.nq.gz
│   ├── 2dd024267b8f3ecd1c1858b356282fadf4659e57.nq.gz
│   ├── 2f00636d0e0f86ea27f654b5b2d41f77b55bb737.nq.gz
│   ├── 30e08d183f591062034b4ef39a9af9355b135caf.nq.gz
│   ├── 314602262af22815f464c361b6f51babfcf8bdeb.nq.gz
│   ├── 31dc39a193b03135aef1b8111fdf85c70a20ba69.nq.gz
│   ├── 3934d3fc39cf1fbfb6ff26d92dddffb9b818bb43.nq.gz
│   ├── 394c1efc03895098672d05472434bfcccee1ac46.nq.gz
│   ├── 3b3f69d6493db0f2ccfceaf9f33c351198c56d12.nq.gz
│   ├── 3f82b6e87fa000c5b8b550b432bc59179bb960f0.nq.gz
│   ├── 3fef9755dc50ba57f061e995090021b053f2a3f9.nq.gz
│   ├── 400ac7375d1da19657a2c48d9e7c0c6daed335dd.nq.gz
│   ├── 402dab65fc837e97ed990cd92943ec6b51494256.nq.gz
│   ├── 4148ca3c92cc84da6b13ce4e31192b2a9b6b2293.nq.gz
│   ├── 425b0f0e407fed5ebae7c30480f171b117856cf2.nq.gz
│   ├── 438ee542159fe05dc8a18a22cbacea27001281b8.nq.gz
│   ├── 45751e24db61f72fb36dd2ba53733c70c4e4af22.nq.gz
│   ├── 45b157b9985f0087d554cc3155679aa3d5f20afd.nq.gz
│   ├── 45bbedc9136904a116783f0a2d5ca37fb2bb374b.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 4817a0cd8dae7054503b292acb1ea76a20624c1e.nq.gz
│   ├── 4866e84a5bc05226ebfc795eafae95df75798c62.nq.gz
│   ├── 49ed4beb34ded579d820af700451aff4b653843a.nq.gz
│   ├── 4b7dd2a5ac321d8dca7fcecd8e6507f3da934aa8.nq.gz
│   ├── 4d04279ea3131593b526aec9c1d358fde1f8593c.nq.gz
│   ├── 505bea48497bde42c01bd5caa5acc1242c1a46f7.nq.gz
│   ├── 50f84ad6f02a28f590c4d24a4097be4b007c95c7.nq.gz
│   ├── 52e2e72ac4d666b381ec597b35ee510982a08c1e.nq.gz
│   ├── 53f999043d202545341e763415124f39a2d46b95.nq.gz
│   ├── 563b5e50469bb4ab1a5d9c5b0eb83359549760de.nq.gz
│   ├── 56c41fa4850964cbaf8d8d2bc172d1279fd4bdcd.nq.gz
│   ├── 58141b6f9832d34945aa90a1b78175e51611f1d3.nq.gz
│   ├── 5cf93d4ea99b05d70160d7c29abee5a003bd2f4d.nq.gz
│   ├── 5d4b23ca0d8fe3269e32674c5fa6356abfb11cf2.nq.gz
│   ├── 6794e99070a2e2926c1fac0d2222cb2863e7a200.nq.gz
│   ├── 6ab2cab97c90b3404e9d180512ef4f5a960d9034.nq.gz
│   ├── 6c3b65e611061e6a9cd323f24776e9cfa87a2431.nq.gz
│   ├── 6c505b74f5d20e6f2837937569246c7d96873000.nq.gz
│   ├── 6ec85f8451272aeed38322a451dd11466a368c97.nq.gz
│   ├── 7031eccdfd0fc7f1904ab4afa111b295aaa2cb40.nq.gz
│   ├── 704cf24072d00a440b9a01c48ebf02c46443fd1d.nq.gz
│   ├── 70859b3fcc4942c4f8a7b94b0662283c410832dc.nq.gz
│   ├── 722d8d208d71bf7e8b549235dcc9188b2ee3945b.nq.gz
│   ├── 745b019d43c40324d6149a1d04eb91cd9288c434.nq.gz
│   ├── 7768b47c1cec5ee9d3826bf29684dba8ffdaa5d9.nq.gz
│   ├── 7773b0646e58b81bc14719ebae79268a6e7688ac.nq.gz
│   ├── 798bbd818ba160ecff6085f8b62410a8cd8a6aa1.nq.gz
│   ├── 7a068c90565fc9c600bb49bd5b9dbc64c2d74f4f.nq.gz
│   ├── 7bb68b0e21eaa3adde54831d4e30db4bae14302e.nq.gz
│   ├── 7d3b64753af95438e1a13d090d9264f640dd81f0.nq.gz
│   ├── 7eca3826d449705624c0a317e3bbe078a8565bcb.nq.gz
│   ├── 8305be535016347aa41550e43a5038b12870db43.nq.gz
│   ├── 8cc04effd65f3e2b40a10ff1aac732cd96152fe4.nq.gz
│   ├── 8dce37520a2e47e0d50b5b38e2733c2090c45e9d.nq.gz
│   ├── 8f0e7229b02f6418381bebda30c6a1e8afd05ae8.nq.gz
│   ├── 924e0dc3a329157f579b114112f99843a8060273.nq.gz
│   ├── 97451a2e3712bfc3c3667843589d9c5ed2be8089.nq.gz
│   ├── 9855402ac8ceca338bac7fd6a110ecc3de7f4c6d.nq.gz
│   ├── 9a8d2877a61143a6aefb9c1ca784cf346ffced2e.nq.gz
│   ├── 9fbbc7b3cb54ebc56b420a43a86634dc74ead37f.nq.gz
│   ├── a72209946c6cc3bc58628dc0e81cda9bce4f22da.nq.gz
│   ├── a7908452d16cedfb37950bfe50780e43f9aa9e8b.nq.gz
│   ├── a7f671d428aa0b4f460fb7bbd65ec659c1688309.nq.gz
│   ├── abd3052716a1ad06232aaea24d40f3007fc7c7e7.nq.gz
│   ├── aed09b396a4fe3d157ec2b4c1fc7488594149dde.nq.gz
│   ├── b28702a1aa2c664f5d231202bf6f3bef74d6ac31.nq.gz
│   ├── b301f8613354ada66a2b738e1adef379909d3a0e.nq.gz
│   ├── b5e98293daf2f9c149d901cf0f29c663453a8d8d.nq.gz
│   ├── b7f67d423503288dbf1aa5fb792df5900cc8d333.nq.gz
│   ├── ba8b74022ba1ee2d61a57de9663c11b83287216b.nq.gz
│   ├── bb158200d06cfa3a998e2f78f721e9e9776c25ed.nq.gz
│   ├── bbc1e3bce649e34a834f2a3d9ed8209e39170056.nq.gz
│   ├── bbd9ed77b748ae723a106e9b90ef88f3a66ada2c.nq.gz
│   ├── bfafee0ae846631fa78265a2f9c9e4727b676598.nq.gz
│   ├── bfe086e822beba9898a748c65b60f05784bc1637.nq.gz
│   ├── c588f6ac748a45b39aa969f09d60acefbba85ccc.nq.gz
│   ├── c62eadc392b0509abf8afbce41ecb172e2259329.nq.gz
│   ├── c704a7f90f2829483d3b4983df8631c2a40ae384.nq.gz
│   ├── c8088759afaf4882fb5af5f048e2562f4567f136.nq.gz
│   ├── cb550d5787231e077bed0616656410605b8fd1e7.nq.gz
│   ├── cb6e599bdd793710a162f7ce86ab4eace72fffa8.nq.gz
│   ├── cf108b275b3a064e99ea3e37bb1ab819cfc36580.nq.gz
│   ├── cfeb648a984def7bc0b86b3d2f351d776b2fe5d6.nq.gz
│   ├── d0a7c281c7c1c84f206b0a2c57d14de637ace24a.nq.gz
│   ├── d2a8b6aa7e805c57d9936c6d07b8b19ef3cc7a5f.nq.gz
│   ├── d344be359af5787d7f40c134d2d576c92f2b81c4.nq.gz
│   ├── d37d6dec1d4c71f0239550f10ab9169a51213119.nq.gz
│   ├── da69f2b317fc4455c1fe243d751d357e62879761.nq.gz
│   ├── dca9c83bf830a2663419dc0ef406f4ae9fa109b9.nq.gz
│   ├── e278c721baa3ff16337e8a5a6ce6a7486ddd5133.nq.gz
│   ├── e337f0f6b13a21f1bb165fd67cec569e65c94ad5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c152a4d50433d1838b103813332d575088c482.nq.gz
│   ├── e783fd477f2ed036894611571be6af12a0b2ba52.nq.gz
│   ├── e80dec5daa58af9d6f9c34d13cd79be0c932df9b.nq.gz
│   ├── e9da453a450b18fe15fc70aa380659e883159bf6.nq.gz
│   ├── ec659c76e7c7433bb39f4183e84a3212da95f662.nq.gz
│   ├── ee3d6a5aef07281434fa4e36fb57235ceea29934.nq.gz
│   ├── eecb239189a4622f1db4a1feb9d20df56e4e4466.nq.gz
│   ├── f31bd73acbfd7df5ee0f0cc354de55b4020bbaeb.nq.gz
│   ├── f4a1867cac8bee2e790a98a2de2438beac4272fa.nq.gz
│   ├── f713199220038b6afa1850c2fafd05f2e635251c.nq.gz
│   ├── f793917792d3fd42c2fd594830505c1850a27b4e.nq.gz
│   ├── fdae4255bad339c1ba5cdd659f34d901867d1515.nq.gz
│   └── fe12eaa1488c5ae81b4b88ea49da09235f45ef19.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 783caf58e9ba9cf0450746b7f65d4bc8229ccd8f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 134 files
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

[sphinx-doc/sphinxcontrib-qthelp](https://github.com/sphinx-doc/sphinxcontrib-qthelp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
