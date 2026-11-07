# Repolex Knowledge Graph of plotly/dash-deck

RDF knowledge graph data for [plotly/dash-deck](https://github.com/plotly/dash-deck), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-deck
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a4821cb46f7b2cef718f3655ae8b2ef1e9064938
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a4821cb46f7b2cef718f3655ae8b2ef1e9064938
│           └── chunk-001.nq.gz
├── blob
│   ├── 0712cd672a471272a3ef10318e6780d4f338faff.nq.gz
│   ├── 0836d9c354ff183f5fbb35ad62a7f2d3104dd502.nq.gz
│   ├── 089c9fb4d1b21ed483f7600e57504add45b754d3.nq.gz
│   ├── 09a1a7ae34e950c8d5c491c5709040b5386704ed.nq.gz
│   ├── 0a851ff68df68f22bbcd09eb08670f8692146187.nq.gz
│   ├── 0bafa5870bc7554a20a1d5cf5873b7a50bf7fd2d.nq.gz
│   ├── 0bb1753afa634b98fe05d36c31fdc3425a5e3ff5.nq.gz
│   ├── 0ff6d1357cbafdebc7011a8e9c091e5c70383cf2.nq.gz
│   ├── 111b286fdc0261812acdd6817e71ac2a8c8f0fc1.nq.gz
│   ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
│   ├── 19277e8ce2e48f0e90a04c46d99ca1b6206eb647.nq.gz
│   ├── 1a162024ec68d15bbaae8698965cba767f0c55e4.nq.gz
│   ├── 1f542069ad26fdf3771e87cb319f0b8ad2762fed.nq.gz
│   ├── 22d3cdf5ac7769a171ea6b825f258856b9ed32db.nq.gz
│   ├── 252d48bc4f247009df552920487f15f2a6b13513.nq.gz
│   ├── 2b958936d284db112bcad05df31beff53f40bb70.nq.gz
│   ├── 2e4b774250d1ae22b045f1efcfaa081ddca073d1.nq.gz
│   ├── 31907c1fade0c1a85e46459f856553ae4ca0fbda.nq.gz
│   ├── 364d9ddfb996e36d27ddf11c737aa51167083303.nq.gz
│   ├── 393011e49978137b0fc3620f007cf67bb78d2876.nq.gz
│   ├── 3c701927f74ce3837046030745206115bd49b0e0.nq.gz
│   ├── 424485e45b8cee6a4ced0a8cb08713036902e5ed.nq.gz
│   ├── 44e15dd7d7263d7e32b7ae7306555a8fa3729bcc.nq.gz
│   ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
│   ├── 4f5412b86667a1c6f61dab663103b6a3786337ea.nq.gz
│   ├── 50020af6051ac8931eb240d7dd808bb2e97e6cfd.nq.gz
│   ├── 56629602904ed28f2b0ccbb7c9076a582ebfe444.nq.gz
│   ├── 57643f375afeb6d19f8f100d90b219a972e51d7d.nq.gz
│   ├── 59ce01a5e450b95c295669a960fb0a3a4c92e1c6.nq.gz
│   ├── 5e3fd58782775d20d46740045d492ed4d74f84c6.nq.gz
│   ├── 60c9f49fb01a54c7df8a6430ad87c022b9af1ffa.nq.gz
│   ├── 6cf4ce386be2461f1069f780d123bbb11c212ebd.nq.gz
│   ├── 70442b5d00ce79c83e3c9e3199654344eb1c21c9.nq.gz
│   ├── 706f3a75df3cdec548b4fdea2342b5b58ef6245f.nq.gz
│   ├── 7079dfacab17b06bd7f9c7e7895bff570669b065.nq.gz
│   ├── 7312dfad82b44a9d62662986cc47d0b6826e6b4d.nq.gz
│   ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
│   ├── 7c5acc9635ddd88b0db930bd0e3f16d41d7c5789.nq.gz
│   ├── 7d9714910cb9966a1b829379f39839e87d598626.nq.gz
│   ├── 8338a1d20b3a6a96e990a727ce96ef1bf76edce2.nq.gz
│   ├── 903649ed4294633e25600935368387719694b0a3.nq.gz
│   ├── 91062b0a4ff637738ee76cbfca997d240ae590bf.nq.gz
│   ├── 97753b76459f2e859f572367df4e98fc2990f6e2.nq.gz
│   ├── a033b99e025e166db17d9bb0507e15bbf3bf7d55.nq.gz
│   ├── a088935d545952092377339c1a2e9b0c8af29f43.nq.gz
│   ├── a1e8f61da95f80f755bc1f66bbb01c23e8a90307.nq.gz
│   ├── a3c4553e7ff9a0482d2908145bd18637e7cdaf77.nq.gz
│   ├── aee9cc306ed859f90a68a19776e9efb33e1e960b.nq.gz
│   ├── b300a82196103d25a3e3d463dade2a58b3a501d6.nq.gz
│   ├── b597a44232c2a3b77943c95857fa5c6075cf69d8.nq.gz
│   ├── b6302a609ca04e8b666ba4a70e4a516341363243.nq.gz
│   ├── b676d10f14ef779d3716ccff035dcd500ae06edc.nq.gz
│   ├── bc20de28efa3e84e15de25e3ccfde781944366c8.nq.gz
│   ├── bc8371522911dae5c57fa15028a9c84eeb316709.nq.gz
│   ├── bf80c42c077218e43bb351352b7c1684e70cfd61.nq.gz
│   ├── c12890b56044cca4f4301e0ed5a2010828cb95f0.nq.gz
│   ├── c2d6494696432cf159274907e5e0110947dc97ca.nq.gz
│   ├── c40c7e16cd8f7019555a3048e8c4767892dd0e98.nq.gz
│   ├── c55b514b0ad8b172be1b7665d553944b4269847e.nq.gz
│   ├── c693ca6142853e1e609440a37c160c8c03d0ff81.nq.gz
│   ├── ca53eb62e0134ab788ef5e44aebc568069732c7b.nq.gz
│   ├── cab4bab1a9cfd905fe8ce69fbf93e116dd013b6d.nq.gz
│   ├── cbf3928a6c7db2f62c5daeea6a3328b81d8c7154.nq.gz
│   ├── ccff499a5c4b0abb42070eedbab7e086a54f9ff0.nq.gz
│   ├── cf79a252cca56cf91cd07856d7a87f1631cb0500.nq.gz
│   ├── d63f16bfedb233288c6242660ecfdae05d3f74c0.nq.gz
│   ├── d8681e06bfebbaa437eeb0f61114c51c6a1cc3a9.nq.gz
│   ├── d8f37f1c0691ec5e834de12df20f0abbefc6e39b.nq.gz
│   ├── e1c9d7173cf4aaa6e1f438d96c0648cd889bec1a.nq.gz
│   ├── e438c4a17265fed4d1e414799ec7c5b98ff4c061.nq.gz
│   ├── e527b8c82b888aeb646f3c6a484d7ee9af9d44a3.nq.gz
│   ├── e67c584debb3b81caa81b18856ee05cfb4485174.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a4515383b2756ac9d54dd1abe654f1fe229858.nq.gz
│   ├── eb81a49a94228fc85213e5bd9c8d45722b89887d.nq.gz
│   ├── ec424d8421d60b609d9c87a7a6c9d247740a8a02.nq.gz
│   ├── ee141450a050fe4a38eaa5ad939127e0d5ea16f9.nq.gz
│   ├── efb58b51dc9d67098deab4cba338a19d86cffc18.nq.gz
│   ├── f1202ac91ae7dbad7079e3aa48c8f93a6dc92b24.nq.gz
│   ├── f16dfc1ae218c5645028c4ca1da03d445eede8a1.nq.gz
│   ├── fb9d1b95277622f001a2262f07b903b6ef6443d6.nq.gz
│   └── fe098ef7b8e765595be978ca8d11173b944368c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a4821cb46f7b2cef718f3655ae8b2ef1e9064938.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[plotly/dash-deck](https://github.com/plotly/dash-deck)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
