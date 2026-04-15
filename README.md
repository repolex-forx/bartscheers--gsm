# Repolex Knowledge Graph of bartscheers/gsm

RDF knowledge graph data for [bartscheers/gsm](https://github.com/bartscheers/gsm), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download bartscheers/gsm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bff22f16d25dc87880e0a215aea5c2f6e551ae9e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bff22f16d25dc87880e0a215aea5c2f6e551ae9e.nq.gz
│   └── repolex
│       └── bff22f16d25dc87880e0a215aea5c2f6e551ae9e
│           └── chunk-001.nq.gz
├── blob
│   ├── 008f319330533452b97f14aea428d920bfecb874.nq.gz
│   ├── 00d247113a25f4943721718d1cd0eb7c81cd0e73.nq.gz
│   ├── 084d3b2c38fc06a3359fb999aed4ed7152b9805f.nq.gz
│   ├── 0a463f06ebe74f964880f5fd2f764a1cd7b9f3a5.nq.gz
│   ├── 0f6a5c3a9debf5439095767c410c6968ad99619b.nq.gz
│   ├── 0f7c5c613339cc40033c4c39a52b1029b7a90fd9.nq.gz
│   ├── 114e11c4ec61b0f2ab85650991213534da46aa8a.nq.gz
│   ├── 121e1e01e14d879c0a6333d321cc69d0218400b0.nq.gz
│   ├── 16df0229798f4da0fae1f6880c79cddafdbaa876.nq.gz
│   ├── 180b428c020a537e4595a265b406b09f746bbb81.nq.gz
│   ├── 1911089454c1efeb95f06c35fee61c2fccaa0dd8.nq.gz
│   ├── 1a5265198eb885feb0f54b4e255edd963943b80a.nq.gz
│   ├── 20685a18eaffb43b6d17d89f3d692b348b3136f5.nq.gz
│   ├── 221cd00eb0731c46f77823206284d474c0ae2bd3.nq.gz
│   ├── 22e8b631259afbe6fc0fb4e0b917c5ad02df44c7.nq.gz
│   ├── 2ef69e2c0e9573cf9a953e9d0c69f9383e2e1c42.nq.gz
│   ├── 2f07b4967ce5bd8b12ea534fd0371e61188360a2.nq.gz
│   ├── 2f63535d4c0747e13c3c9495eb780e23f1b14f3d.nq.gz
│   ├── 31e86e0675ebca965b52da0877727b9ba35d1549.nq.gz
│   ├── 33419fbebcce7d3833fb17e774d681a0bb3ab1b3.nq.gz
│   ├── 3849693d0c1b5d86408ed251ad85b2abb87a14ab.nq.gz
│   ├── 416438f55e14857456943624f60a04142b758bd5.nq.gz
│   ├── 466657d521d24994e9465e4119219c7b7ee9d93a.nq.gz
│   ├── 471bd69626f9b6b58e814ab38dd78049d4bfc5de.nq.gz
│   ├── 48cd44a57ca243c58c97e8caf4f2e687dd8b3d0b.nq.gz
│   ├── 4a1015a13e94f62a15e47cc23fc254f0d7306f66.nq.gz
│   ├── 4c80df631020cb4e3caa16e418c003f0c232816e.nq.gz
│   ├── 4e86e2d8c53982d48abddaf0458983cf8bd4615f.nq.gz
│   ├── 4e8c94c6d0c56e43fcea7abacbb6b8b0ab45aef2.nq.gz
│   ├── 519c5dbca097382aaf69927e5d8a39d2f2553ace.nq.gz
│   ├── 528d0598a9ec8dba82d11b1f8b3415f23cc11b09.nq.gz
│   ├── 5b62bcaa7114261b978d4c69f063b5959e03ee68.nq.gz
│   ├── 602096ac3a1f2e5202d0ab07e6cc3cd402f288bc.nq.gz
│   ├── 66a444b0b1ee0a45a9a38bcbe6a65d6a612dff16.nq.gz
│   ├── 6a24d16e5927636b7a202e3ec859338483b0a97b.nq.gz
│   ├── 6a26d3aaa769eb66c7055def4798786f50249340.nq.gz
│   ├── 71c483c47447dc03a3f1102829c2431efe61cbfb.nq.gz
│   ├── 732eac97e4255b5ac27b8b6cbf1b51db706e37f7.nq.gz
│   ├── 7f7f41ed056aae2afe94c84a332d83b3d88d9bbb.nq.gz
│   ├── 814333147bf4eb7e953e3994c3c62de8f64764b1.nq.gz
│   ├── 81aa4ab376f9bb86ba173ce1d1760c9476852f3a.nq.gz
│   ├── 8c213bcaf990bed8db899514bc3e62708a55256f.nq.gz
│   ├── 8fad3df679697eb3c3459fcd5c2ff154a0e69e44.nq.gz
│   ├── 92e7524a6c5e32316a57aa4f6d8485b482a3c36c.nq.gz
│   ├── 976eb424afdb7f8d5285ca8fdee8a68379bea616.nq.gz
│   ├── 978e2be399c40132ffcc294dcb47d58146f3896b.nq.gz
│   ├── 994fb43c17b0b33fcda5b0c248311bf5553f3daf.nq.gz
│   ├── 9a1bfb19a5fcae644fa3daac95a4364f283124c5.nq.gz
│   ├── 9c5431092fccf9bc5357f9d3d3f1372bf36fd7d8.nq.gz
│   ├── 9d7027116cd416637125f9e3be3072f17979a6a2.nq.gz
│   ├── a59e9d7aa42a60686af77ff2ff8368b037292bfb.nq.gz
│   ├── aa6afcd543af3751b462fe385af37542480e8445.nq.gz
│   ├── af1288fc42428a924200f47551d7b86400ad7bf4.nq.gz
│   ├── af48744045c520c3d5244aaa7bfc22e1cec2dd3f.nq.gz
│   ├── b07e86097d8ae05ad636e6b71ac5e2ea81404da9.nq.gz
│   ├── bde3f91de7de8b315db3bb063f13333bd510d853.nq.gz
│   ├── c033837746b110d0b1a3cdf3256a6e3f9704ae7e.nq.gz
│   ├── c1c069bdaead4b1e56e4df4a37a360e2e7169e27.nq.gz
│   ├── c4a8e63483247c395263cf7186498faf35f8b9dd.nq.gz
│   ├── c4ec802b1175012a2b007b08257635c4d740ad69.nq.gz
│   ├── cb785fe5ebf46aa85209d88db0d7312832e4e440.nq.gz
│   ├── cf9a6b98c26ae88b0e911c9d23eafaa8ee335ddc.nq.gz
│   ├── d150962e81ffd60d01b479e839ba4be8b82d80b5.nq.gz
│   ├── d308cd0b21f74a4ba08c1b367e1b8e0d33cabca6.nq.gz
│   ├── e664823c2ed370cae2aefd110831cf1488c0833e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea55404d26d8287f028c3066617979fa0a9b9095.nq.gz
│   ├── ee84c9eddec68984522750cfcb771d78d21591b1.nq.gz
│   ├── efa492265bc6b2b8c3c70d4542bd1515adaeceb5.nq.gz
│   ├── f84c8482d4befd995df1459a940258b410dad007.nq.gz
│   ├── fa3d2c38024a6f935836b0681d114b44fb67503a.nq.gz
│   ├── fb1354adc53efa6ada8873a961f5c1c3fed7dd80.nq.gz
│   └── fd6d8bafc5998829782c8fd61fe5d2e875e05884.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── bff22f16d25dc87880e0a215aea5c2f6e551ae9e.nq.gz
├── filetree
│   └── bff22f16d25dc87880e0a215aea5c2f6e551ae9e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 83 files
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

## Source repository

[bartscheers/gsm](https://github.com/bartscheers/gsm)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
