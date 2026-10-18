# Repolex Knowledge Graph of dbcli/litecli

RDF knowledge graph data for [dbcli/litecli](https://github.com/dbcli/litecli), parsed by [repolex](https://repolex.ai).

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
rlex download dbcli/litecli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aa53bb0c1530cd1dfb30534babb0bf47df33c60a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aa53bb0c1530cd1dfb30534babb0bf47df33c60a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d6f5adf97fc4068e64bbe1045f3a67848af3d4.nq.gz
│   ├── 02634473cfb69e6e10ec97d4750cce5d080b65c2.nq.gz
│   ├── 07a3a030154596ba588fd73ebd8b3896f1da5675.nq.gz
│   ├── 08f7bd500166371fdff18a746857ec43a2608feb.nq.gz
│   ├── 159c2b6603d0a0c53357f75cf6a996e559f85b6e.nq.gz
│   ├── 194cdc7bec1d93e414c0f53c520f4c7e5fa08f97.nq.gz
│   ├── 1a5cd6d9aa6868f881c946b0642ba6adef7ba5e1.nq.gz
│   ├── 1d9131734921a29e129e13789d2847a89836f32e.nq.gz
│   ├── 1fa4cf03651c52deb32cb84e9dec521fafaf3fdd.nq.gz
│   ├── 21ad5b654e58260f617b83be94d44c2560a06811.nq.gz
│   ├── 22d23184b60970d23e65ae6a827a0e120d98dd45.nq.gz
│   ├── 2de74ce730290545df766954e51c9081a9e14454.nq.gz
│   ├── 30d19a67f3ac552bafd8209ffe61a8dd18140682.nq.gz
│   ├── 32da6bd89220e57db7e330838cc275f97650954d.nq.gz
│   ├── 3c053333c5e789da014372e907d1ff4bddd9296a.nq.gz
│   ├── 3dd2a898ddc058547a9c5aa1d5498940d6c4d5c6.nq.gz
│   ├── 3e14cc7c260454384c9ed71d298c26561ca6e6bb.nq.gz
│   ├── 3fdaef112fd7848d563caaafe9f3ac1900b53c26.nq.gz
│   ├── 4083b4dfa664adbf01fce6e86c48c460a648bb4b.nq.gz
│   ├── 434a96fe9a24ceec20422c0842ef22392cd007c4.nq.gz
│   ├── 4e76faa87c2c61bb235f2b4c56bdd40f29d53046.nq.gz
│   ├── 5391e8a30f23041932702711a696324072901aed.nq.gz
│   ├── 58e2ebcb2cc37d2cc5e74e147842a9accf4b1723.nq.gz
│   ├── 5e52b73230311663391707221cbfcba511880258.nq.gz
│   ├── 5eddb632a90c2f651e26760bedabadd4b0a7b756.nq.gz
│   ├── 63c3eb65739e71607f6dd3dac6cbc3f4c9008aae.nq.gz
│   ├── 6470ee10cd8a9a666be9b1c17b83f4f4c0e786af.nq.gz
│   ├── 65e33d04b37d3713862770fa20e92c442185623c.nq.gz
│   ├── 6ca999e1c89903868a04a9fc1bf8e56db6d3bf6d.nq.gz
│   ├── 71f1be5f4f72cb293e1877818d6dbf3cd2ec40cc.nq.gz
│   ├── 8009d19d0149fcb259126f0800849e2f99f91b11.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 91f7df9070481063299c5e42104d382651e6dede.nq.gz
│   ├── 9260a17209e28d27e69351fd4e431525dcd54558.nq.gz
│   ├── 953bc16961ce450ead5a9df29c657573bcd723ec.nq.gz
│   ├── 9c4973d73c36de2e35f64684ef669d49f38239c9.nq.gz
│   ├── 9cfd80c639a06e87a2ca1be94a0fa4b4e03e3332.nq.gz
│   ├── 9d723bea14c09eb38eb26b11d61c2f604e068655.nq.gz
│   ├── a4d5f2d84ec735b718af844f9cd645883c3d560e.nq.gz
│   ├── b364872585d33e7c38f833e5a0d8df2700c7a0a8.nq.gz
│   ├── b62a8b99c5a6e2ac7f739bd9c3d6782b6eacfb0f.nq.gz
│   ├── c3bbe961cc0f42a3470ecb2f4acccf12c3e4eaa5.nq.gz
│   ├── c433202347bab2d15260131c4e1e4ac0a01b5a27.nq.gz
│   ├── cd67aa8c052846299b549bc3365025da7a771355.nq.gz
│   ├── d4142eb5c55607d03f5143b1f218b05bc389bb09.nq.gz
│   ├── e0b5d8a20837fcbf2ed4fd16bc30b6d87b5f536c.nq.gz
│   ├── e2e097bdec8c0013f1173cae5d2beaebfefb129e.nq.gz
│   ├── e3bc6ee1b5202cab4736d1d92e08b9351bfabc88.nq.gz
│   ├── e4391d739ce93a0de6fde47f9e7bd04cb1866a86.nq.gz
│   ├── e661b48f87e6598ec82d7ca31dcf9febec3b1a79.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec162d3219faaea257c9bc3bfeff79076a8abf90.nq.gz
│   ├── ecd8a1e96f838a08fb5bb1a2e44026e405e02af0.nq.gz
│   ├── f1ff0f61a1f09330917ea8367890e4fd26c9dc3e.nq.gz
│   ├── f2a8a76024b8c64046aa0513007adf652b300a58.nq.gz
│   ├── f556d522c5f77c024d0f57c3bc17129f4d665ce8.nq.gz
│   ├── f7bf346dcd059a2d378d3acdee738368926d2bd7.nq.gz
│   ├── fa732c3b400fa3bae52d50242df11c8f6b63e966.nq.gz
│   ├── fbdf8c10fbc2f6afea23d9da9dbff18986912f7c.nq.gz
│   ├── fdb33176e5bee84557ba6048cd2e18b18c0c41f3.nq.gz
│   └── fe7119207daf892fc148f4e7eea5d9dd9ac50d39.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── aa53bb0c1530cd1dfb30534babb0bf47df33c60a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[dbcli/litecli](https://github.com/dbcli/litecli)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
