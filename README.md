# Repolex Knowledge Graph of PyCQA/vscode-bandit

RDF knowledge graph data for [PyCQA/vscode-bandit](https://github.com/PyCQA/vscode-bandit), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/vscode-bandit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d3210e1244d2c0d20ff63dc283f4adff8912c727
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d3210e1244d2c0d20ff63dc283f4adff8912c727
│           └── chunk-001.nq.gz
├── blob
│   ├── 0059836bc32ddb27414e14de1b3a3c341d752768.nq.gz
│   ├── 0179fff82ab5a7b1a196fbad808ead7bdf585046.nq.gz
│   ├── 03afd29441fac4cb28a766efa9d04e05a3004533.nq.gz
│   ├── 0435aa8c049c79c6e38dc8357832fc1c161c8556.nq.gz
│   ├── 0b52a26c2c7eac3b22247dc48883855c3376cda5.nq.gz
│   ├── 0bdf62e445c7d3f040b99368224115908fd64803.nq.gz
│   ├── 0d0d3d1e553bf4947dab177f4151a5a9ca09e934.nq.gz
│   ├── 105df1a8d251c59dc9270c8ca2e084b5504753b3.nq.gz
│   ├── 155460c49aa2f45ce6f438053607b059af330a0b.nq.gz
│   ├── 17013d80300b5f35c0d6431ae77918797454e43a.nq.gz
│   ├── 193c2d2b5e8c1756526ec1fcd17190016309fafc.nq.gz
│   ├── 22b14091f742656bff5d0cb1d3f331292937534a.nq.gz
│   ├── 26327f27eafb581fa0278b088d91de1ec18e6ccc.nq.gz
│   ├── 2694fcc757a9785ed00ea81d0ec53d16ce6285e9.nq.gz
│   ├── 2e2237cdeb70744dcd3a7dcd6a9d6be96c1c0ffb.nq.gz
│   ├── 2e6f1b5a15d75d38a4dd669e98ad45e4a46b9bc1.nq.gz
│   ├── 2ed80871a894ffaebb5cb72f5e95a9fa4d00d19c.nq.gz
│   ├── 34d3a0a516eec66558aa5617d2138688b2adbea9.nq.gz
│   ├── 3e852f6b85c54f1a19cc7c4b43621f303340789b.nq.gz
│   ├── 429054e366ac8f18d6e0d4069c6c9d21d10041b9.nq.gz
│   ├── 44045a23affa75b37a5005dc57ffed5bc06cd0cc.nq.gz
│   ├── 48ea6616b5b8581df3401872996cecf1f8b08a0d.nq.gz
│   ├── 50120677227f215e40785722dc3626a55dedb246.nq.gz
│   ├── 507d3d6f96642448e4b8e5d7f8281d7653a51dc8.nq.gz
│   ├── 55f5c2d6daeee6a603a2a7b644e3a6fb2d8b41b5.nq.gz
│   ├── 5b2a3b1ad2ef791b895b6b7f4bd73d114e32685b.nq.gz
│   ├── 5b7f7a925cc054db9e518cec6849ff369e1b35b6.nq.gz
│   ├── 60aeac82176e92fc42d4520e42ab1e0509b6a29e.nq.gz
│   ├── 67e8a09c4b8dec6961cebcd6a90364a4a08eff3f.nq.gz
│   ├── 69c114e39e5a29103565947e4345d236b8bca3ee.nq.gz
│   ├── 6a39032ce1623b106286a4c4d7f95db0f57cec7c.nq.gz
│   ├── 6a962377fae3c7ded5e4018976a247f7a1c8dadc.nq.gz
│   ├── 6b613871be68328ab69b144878e49cbf08011142.nq.gz
│   ├── 6c8771b95e09bd8452ae3c5f2d1a0d075f138c36.nq.gz
│   ├── 718cb7d75db495ad9889dd56349dba72b4dddb19.nq.gz
│   ├── 7a33c420a9756be97155a95653f9517d14d8b933.nq.gz
│   ├── 80ad7c92320778c47c2a9035a2dd6ab9be0bea23.nq.gz
│   ├── 876202adad0016b37107d282cea1ff8e12bf1e27.nq.gz
│   ├── 87a94b7bf466640546bfe37ce2a2314a5c766948.nq.gz
│   ├── 8830325cee30be69a5091077f36b3765afed5855.nq.gz
│   ├── 8f33e13efe7968b03df08303245cdc0c313c7234.nq.gz
│   ├── 98125eb363a8263e2501a496d70329a49fcf80a0.nq.gz
│   ├── 9b83106f366c21ff643b650c116461af8483bc26.nq.gz
│   ├── 9fe1407f0d93cedc5718081fa35e261c332e87a7.nq.gz
│   ├── aac723ecfc76dda71728470e93eeaa015d76f5f0.nq.gz
│   ├── aecdee752d2f7817336065eb780ba7a4d971dee3.nq.gz
│   ├── b12799a3660db21818fb39a9d8af0d13518c4dff.nq.gz
│   ├── b667bb9c22bc4a91495e070723acf24de2cc075e.nq.gz
│   ├── b989dedc3ce46d834905f69bd851b9faa83409ea.nq.gz
│   ├── c4c6852cd73b533bd5eaae29c972136976a84fa3.nq.gz
│   ├── c65d849c4a2e2658bccf6b36d2c828ad43db30a2.nq.gz
│   ├── c8502536f01457ea7a4e6ff37d131a5c981b7a09.nq.gz
│   ├── c88abd2070d58340a9a805a6dcd15df381521c24.nq.gz
│   ├── c905b93262b629bc18bd35dc3afabd04237bd4a8.nq.gz
│   ├── c9427626198a51062356c200622a91f05b65b91b.nq.gz
│   ├── d2c3671f8fe32f7e04cf274a704ce6a3b55ce73c.nq.gz
│   ├── d462c950d0fabe27c267f665b28825e7cbeb1399.nq.gz
│   ├── e000b9a6e555498f1496118130ac69df152d1418.nq.gz
│   ├── e33f333ddbe757ba29d034bb19bc0effd04a366c.nq.gz
│   ├── f2f006bf9518fc956367bbb441161da023608e4f.nq.gz
│   ├── f5c3603de12f02152845bd7b5d37e7ceb8bd9b20.nq.gz
│   └── f9b22b793c2998a2d5b65850b80b8a459bab32f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d3210e1244d2c0d20ff63dc283f4adff8912c727.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[PyCQA/vscode-bandit](https://github.com/PyCQA/vscode-bandit)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
