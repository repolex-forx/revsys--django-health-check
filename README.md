# Repolex Knowledge Graph of revsys/django-health-check

RDF knowledge graph data for [revsys/django-health-check](https://github.com/revsys/django-health-check), parsed by [repolex](https://repolex.ai).

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
rlex download revsys/django-health-check
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24b9269ab09bf7a97a9ffc374dd806d6f29cd25f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24b9269ab09bf7a97a9ffc374dd806d6f29cd25f
│           └── chunk-001.nq.gz
├── blob
│   ├── 028da3b37d9b69edec395b17f6d9e6761a945197.nq.gz
│   ├── 06badd8765b9655e67d25f79b8c0a4bfc56f9444.nq.gz
│   ├── 0a2a740ca65b3704f55352fd1e1b64c6039f2c30.nq.gz
│   ├── 147e069ddb345fd80d7768995f891fc53dc18a3c.nq.gz
│   ├── 19dbb18680cb1cf14a64e90cf4f7e8602fcd2cbc.nq.gz
│   ├── 1a382bad96312c07c1a66327671835ef2e0e9093.nq.gz
│   ├── 1b6a36ccff9bede56919cd7a3e83a24d52a2cc8b.nq.gz
│   ├── 1c506d1d2ac13bfcfef77cd88be7393357ba2bc8.nq.gz
│   ├── 1cc018e9ebaaeb8f7b903442e7f2922ff46d8463.nq.gz
│   ├── 247fe034e3a660818d5347ecc2bd303106ec9a51.nq.gz
│   ├── 2d90ca6b7c7053097e520f49e7f4606dd64fe1d5.nq.gz
│   ├── 3227b87b5e6782dee34e9b2e0a80fe7222874171.nq.gz
│   ├── 380c5cc54a3c7c8e1ef67e11a6df7b65dcf49e58.nq.gz
│   ├── 3fae969bc9b0a8510648f28bea2567b69a840b60.nq.gz
│   ├── 40418065163a88b8d83f92cb73dbad609cf7598c.nq.gz
│   ├── 427c2899f829ae7f44e476440fe7f52ac1914776.nq.gz
│   ├── 439c23a9a3c00ba50aa1ae723e2275cad7ac8817.nq.gz
│   ├── 450fe18b98d8fc0aec0bc12fc2a5274057b1ad05.nq.gz
│   ├── 4ddad357cf5b39140dfb850e8f3cfc31fa8b0766.nq.gz
│   ├── 4ec044609b04cc60e1f272533bf252f64decad6b.nq.gz
│   ├── 4eeb49645c4e98dc1cd2c874ad66c14ab0a60d05.nq.gz
│   ├── 4f92523d8c1eaf3af3281b37231f0783da27c96b.nq.gz
│   ├── 50d502ce917fc3d95759fee37ef3644d692cab8e.nq.gz
│   ├── 54cb50f7b6afe7db9b5df83ce2d9c79ed05acbf9.nq.gz
│   ├── 581b2a4f5b9bde3c35afcfda27870966bd996599.nq.gz
│   ├── 59a5062f0982d3978e8441a8a6c054afea802911.nq.gz
│   ├── 5f5d141343db50706b93febef6c38dd430aa4e15.nq.gz
│   ├── 636276702d98a1fab3f6a51bdd1c6a23a9031630.nq.gz
│   ├── 6d07e789623160a1e8f5ec84d099a233f919fbd2.nq.gz
│   ├── 714443ad68c2500d78f51b4ca4a58d429326551d.nq.gz
│   ├── 747db705719a3b7205e540198964b8fcf8ae8ae8.nq.gz
│   ├── 78e7b50d15e60ac5bd54fe8d204ebdb861d5b2a6.nq.gz
│   ├── 7bde2016ac205990fccdc92a204e1b336652f0cf.nq.gz
│   ├── 86abd9c6f239f3290eab59bec4c81699bde087e7.nq.gz
│   ├── 936469ee517f38fe3289fa12ac9c5b1b31dff615.nq.gz
│   ├── 969dcc38aa4f468e52fe223833e091b308d78ddb.nq.gz
│   ├── 9960669661556614935e9289200f90fc1987e5d9.nq.gz
│   ├── 9b56215e7b5c41af0be51bac4b5b63b9456610ae.nq.gz
│   ├── 9db22700c0ec0a540e6b7aa2c15892e4fd7a749f.nq.gz
│   ├── a280711b1ad0ee3700576ae7cd1e8a6259268a4f.nq.gz
│   ├── a821382cfe2d5916e40302aad19f28cf93955214.nq.gz
│   ├── be38ddf83317f8328c039b3e68528d2bf3c8e9e6.nq.gz
│   ├── beaf26d091775964197a08a288cecbaf69d06ca9.nq.gz
│   ├── bf379ea82e688df1672c093cf85c37eabf559e85.nq.gz
│   ├── c6a3c542a5451a1a4d12d43919460c6816256ab9.nq.gz
│   ├── d2957d38ac66f2b1212869f7eecd4c2cd518ee6e.nq.gz
│   ├── d724ceb2e340e78977399a3d3bdb001ec487c429.nq.gz
│   ├── d7894fd704bff8fcf22f984b3ccea55c898f6148.nq.gz
│   ├── da06b0dbd60e5c0c1a2dfa12e82f0ac49aa4888a.nq.gz
│   ├── dd44f72cbd1b84c0ba9f1dca2f8c3fe3970c9b11.nq.gz
│   ├── dd93a24172bc3abe7c30b764a9ba270b2a9f9a95.nq.gz
│   ├── dee6062ee5eff2f60b5e45201c50050e16fff492.nq.gz
│   ├── df46cc91f2b1917ce3e2f048ab859a2ebbf03810.nq.gz
│   ├── e0f13597a18cb4f3b31da6fba9b8af7a571ea00e.nq.gz
│   ├── e289b1b12d516a3d0877637407cd6a50e1ef701f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eadb11073687cf168dc3b902c6372ce04a823de6.nq.gz
│   ├── eddbcb4e29a4dda3b61219d3963b6b5f76bc75fa.nq.gz
│   ├── ef456010e2cc6366d189aef96f042052db0d3ce2.nq.gz
│   ├── f0315bdc65c765b8a24055589334b2b3cbd1889e.nq.gz
│   ├── f1f786dd98b5c09a7f8e844b9d456b7dbbc28829.nq.gz
│   ├── f9726f9e67d10a596ac6efaeb114a6c479fa24ca.nq.gz
│   ├── fba0d25dbe5148f97f3583b6530b1e06b2d3dfc3.nq.gz
│   └── fca532ff093a4584bc58837b840e27c289d6c729.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24b9269ab09bf7a97a9ffc374dd806d6f29cd25f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[revsys/django-health-check](https://github.com/revsys/django-health-check)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
