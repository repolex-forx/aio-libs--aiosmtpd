# Repolex Knowledge Graph of aio-libs/aiosmtpd

RDF knowledge graph data for [aio-libs/aiosmtpd](https://github.com/aio-libs/aiosmtpd), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiosmtpd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07e5f26b0c27a10c71b860c0ebd699f369c4c6e0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07e5f26b0c27a10c71b860c0ebd699f369c4c6e0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c2e137eeab501aa1ea2b7db622883692374875.nq.gz
│   ├── 0665cff109c4413416229e2be38169c09845a828.nq.gz
│   ├── 06e355ce6164610154f2311989ae0c047efc2fae.nq.gz
│   ├── 0a902130455d77cc362401b06bae9e629559501f.nq.gz
│   ├── 1484777bfde673f6caabde68bece95d5f5f0b73e.nq.gz
│   ├── 22d33ccc7a5ec0899fe9ed63f43e3633b72c75a3.nq.gz
│   ├── 22d6040cfb4c5f26adea1b65e496a693787443fa.nq.gz
│   ├── 2c4faffe8b0b7dcf96c87cdc010c07c2010ec557.nq.gz
│   ├── 312031a7ef4333f5693af07dd9de92a502959020.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 38c8b83667a502d6dd3df50161701ccfa852b96a.nq.gz
│   ├── 3dcaf557230ef112fc927ed09570684524c69fab.nq.gz
│   ├── 3f47bbf56fc2355c40bc3a0cc665a1e73efad9ec.nq.gz
│   ├── 40c00961e233490d77d73d71716836e801ab43cc.nq.gz
│   ├── 4268926807d04d2867a84908b6e7ae7cb5c69991.nq.gz
│   ├── 47a11dab9bba586a13abd69fef59958ebf21f2e4.nq.gz
│   ├── 4a711852636f7fd8716ccd22fc89aa86e60f1186.nq.gz
│   ├── 4e153d73d40ee8f2164c2deebd798b5a38ab89f9.nq.gz
│   ├── 50cf36ea741b38e47e029a7b8b1c4df904b01f6d.nq.gz
│   ├── 52207973c372141ac619b9f3e3e04ada9dd2463e.nq.gz
│   ├── 52698ea43a9d8ccf2cfff44ea6f0bf5212299a8e.nq.gz
│   ├── 573ce1d2c35f8678c06ea2a44ae9ac00966cceb9.nq.gz
│   ├── 5c1978869dae5919136c2ff2dc26ebea7178e3bb.nq.gz
│   ├── 5ce5a5919cc61bbe12a92b5412b6b0513c27b98f.nq.gz
│   ├── 5ec8ea5442dc5e42de70014e7db8a53253d9eeaf.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 62878611e7267af0b6368f773ef1a664755507d6.nq.gz
│   ├── 656b6cd1cb772886dd5879a7f07c6d5e3a6535ed.nq.gz
│   ├── 66c4bfd432c17f083cdb5c2c1903ba42da1e3a61.nq.gz
│   ├── 67ba73bcd89d1fc72309b6489ab8154ef3e98af3.nq.gz
│   ├── 696b909db2913bd568e6505cba4daf7fb6adad50.nq.gz
│   ├── 6f19089c12d3c288ee702c99457e93e6b8a459f0.nq.gz
│   ├── 7860c7987bc62bde59c573f6f03e505a342aaa27.nq.gz
│   ├── 78c9a34d5faf6c4d07b03005c2a260570d3b3274.nq.gz
│   ├── 808920d6bd316b409192ac16631162e8b8e0a868.nq.gz
│   ├── 81b01931c113534351003b169c1921afafb17c4b.nq.gz
│   ├── 83fe46dd6974dcf4ddc6246076b1cd3a3dd415ad.nq.gz
│   ├── 87161793750de8ab72a7aa55a6426d0539a781a8.nq.gz
│   ├── 8a3094765e5e0747fddfd74166434b1631234ae3.nq.gz
│   ├── 8acf33a89ae1c5826c7e2504182273d05f86e4b8.nq.gz
│   ├── 8d32a264987de5b8deea277d0bc73e644406046b.nq.gz
│   ├── 8ee630a7e185829c9da01d2a85b782ac1f000219.nq.gz
│   ├── 8f17087f28e8a30b0847ff7df15fb76ba85ad45e.nq.gz
│   ├── 90e727b336241d4870b3c3f7069e0ceb071a39c3.nq.gz
│   ├── 94359c6cb9c73f5ac2303a84760d063aab7986e3.nq.gz
│   ├── 94f1489ac6978ac90c8f52d0ac3720ed0f6ec6d4.nq.gz
│   ├── a0ecf0e4341711c00abba758a87cacdf25218849.nq.gz
│   ├── a3b64ba82d0d6ea62af2666b925fdbf6496ce670.nq.gz
│   ├── a7f6da8f8024bb3dc27d16228c7c9fe182c68a7c.nq.gz
│   ├── a8fc7d71653ff82fc9ec47e87d55d8ffd20b3f32.nq.gz
│   ├── a915b085731a778b9ba02e957ea7fd28f768da25.nq.gz
│   ├── b8d3c586880387fe06cc459237a4445f867d699d.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── bdc2bcda7d94b232cc691d6b74c74f1e417c78e5.nq.gz
│   ├── be5d54d05471ee9ee914fbdeda4a6513c4758a03.nq.gz
│   ├── c0c773f23e029770af042a645021fb0886ce516f.nq.gz
│   ├── c1d43d4c671cb6a76a3324f08ed8d190ea0e08de.nq.gz
│   ├── c78e6fc886cfd81f221fb67eb1fa61adc92cf951.nq.gz
│   ├── cad3e9b345e7724f574a142ffb8900537dd5c7ba.nq.gz
│   ├── cd3ee738ef7608a65e43e94ab6cb48680d8c12de.nq.gz
│   ├── d6c5c14bf0b8d6c97fd55651203e7c0d5d1aa0ca.nq.gz
│   ├── d8891f66821cd7ba16f1aec7aca4be80c4f9dd0d.nq.gz
│   ├── db20c6115172719bdc67a54c2b2244ff35dd0b1f.nq.gz
│   ├── dbb2d1f77eb2651f8873901d5b86e0b58ba53593.nq.gz
│   ├── de688080ed3993ebf7b021064c7999b243f42dbe.nq.gz
│   ├── e107131101264c4bc55bcf4389eec1e058f20b42.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e49fac80d91a3714d3269ec945d6cd8135ebe7bf.nq.gz
│   ├── e4cf845139d0a7c4af48f9644b0b24b5b3ec7e43.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e714a9801d73ba8cb24c33598cf632457b41b7.nq.gz
│   ├── e70869a22cc26438c57cb0b5de937573770d7f2e.nq.gz
│   ├── e9371928d2f131b14b76adfafaf8d8903b113202.nq.gz
│   ├── ee1e17254e06f7a1531f5cfa1e6e7b1fa2256aea.nq.gz
│   ├── ee2de38ee88a013d84f342bcefa1a0f7f6d055fd.nq.gz
│   ├── f6abfaaeb324527c1f6f7feea0c7dfc9d3face96.nq.gz
│   ├── fb877b2ac61548e4347bb0252fc60a9391235737.nq.gz
│   └── fe8f5f165367eb72478cd06ab8c1b61b2754fbc9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 07e5f26b0c27a10c71b860c0ebd699f369c4c6e0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[aio-libs/aiosmtpd](https://github.com/aio-libs/aiosmtpd)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
