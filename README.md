# Repolex Knowledge Graph of arviz-devs/arviz

RDF knowledge graph data for [arviz-devs/arviz](https://github.com/arviz-devs/arviz), parsed by [repolex](https://repolex.ai).

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
rlex download arviz-devs/arviz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7d8d55517b826c585ed0e1ddcb2ae4f4dc0b48c9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7d8d55517b826c585ed0e1ddcb2ae4f4dc0b48c9
│           └── chunk-001.nq.gz
├── blob
│   ├── 00718458576fc003adf0317d224f6dc98f45fb2c.nq.gz
│   ├── 0530d2675d5fadcf45d884285b7b453969941be0.nq.gz
│   ├── 09e578bdc31854c3744681410fd75f68171b7db1.nq.gz
│   ├── 0d4861892d261c6dbd173f358e608d14b2730f3e.nq.gz
│   ├── 0ef9d829216f9ede870ca7a9d0d0067b6d6ba02c.nq.gz
│   ├── 108ef2320b3064eb9bf804c702a26064e2a7b1f1.nq.gz
│   ├── 1133ee564af17f2a91f68d07184920a7ff37e4d5.nq.gz
│   ├── 13e2634ce4999162ab66cf36cf0582aa3029d0d5.nq.gz
│   ├── 185ac037827ca84d7fe877e650f4b0e6079ea258.nq.gz
│   ├── 186d535fa61abe03f26d7e89fb4b88f889561e57.nq.gz
│   ├── 1bbbc9f3455a459af13c9738af37c3a3e2ed993c.nq.gz
│   ├── 21141a692c32bd78bbfb85815a633cb3c41fe184.nq.gz
│   ├── 21296ebb582220b635b45fe9bcfc146660f3be2c.nq.gz
│   ├── 22e11150db5fd9fc7e805614395ef468f5c227cd.nq.gz
│   ├── 23edd0d8503bc8c42cb8d6cfd6c284ae6e37253c.nq.gz
│   ├── 23fc0aa6ecbed136adcbfe10f64dfd85eef21b2e.nq.gz
│   ├── 284eb00f37fcfff95b16d26a43a683c2eab5a727.nq.gz
│   ├── 2987f4e7ea3799b5d362babf2d9d3893789c1fd8.nq.gz
│   ├── 2a692b0cad06f569cf08c3bd413860d2fb1d564b.nq.gz
│   ├── 2bdda7ef9216d5a18cc361ff26ed7f9912bf0524.nq.gz
│   ├── 385564a832632d0b9a3a3083f22c5f8ab2ce5737.nq.gz
│   ├── 3a8de0cf854de7d552f4ddcb8bb0fdfd233b3ade.nq.gz
│   ├── 3a94261ca18f0397273ee67e93129af9f2a82b79.nq.gz
│   ├── 3b78792593426b361a11901cd8243d22dc59252f.nq.gz
│   ├── 3f2b607bb6cab31ca058416edcc1ae1cb172b8ed.nq.gz
│   ├── 422c9fbcf5d72b16763ca301a25a74750b99e112.nq.gz
│   ├── 4561bd49ba15b6309496bd2a70a3b4aebba38530.nq.gz
│   ├── 45baef297aa58b152aa0287c8349f4ec0db60a81.nq.gz
│   ├── 47b9fe7c4033a54b84a664db90d9950be7dcd84d.nq.gz
│   ├── 489c954db1544735bfdb6043afccbe0f8fb7a602.nq.gz
│   ├── 4b2d182488409e2f725a4117ed7ed3cd98c8bd85.nq.gz
│   ├── 4cba37f6d645bba1b2e7755f092d59e9192c01e1.nq.gz
│   ├── 4cbb034c12e33d35aadaa1481f67859b507ec9b3.nq.gz
│   ├── 4f002225af7861bfb1fe83304f69374848d88dd6.nq.gz
│   ├── 51cc1c0d3c1e0e9a6f207d18e8f0c8dab6bd4076.nq.gz
│   ├── 53a7202917cd2ab4ac6c8a23f4a49ad681fdd9fa.nq.gz
│   ├── 53ababa3f5e7c706d1fb1eddc0dafd906eb6bce0.nq.gz
│   ├── 5a7ad470fb4c1213c17b7134d6401479ad4e8bd0.nq.gz
│   ├── 6168de639bd48f72ee9dbf3b63139993e366c7b5.nq.gz
│   ├── 61b68d0d16cfa8e064f9448897441539aa173286.nq.gz
│   ├── 61e8cbe4cfa817255fc34768f90d8bd90a263768.nq.gz
│   ├── 646a59435c71376818c5c2321b66609034f1a7f5.nq.gz
│   ├── 6e72f9cbc7ad68af4c555f958df0f10f12e1205e.nq.gz
│   ├── 6e8dcd2d147bc99c32dd79c342689919c5d3cdf4.nq.gz
│   ├── 73af413851c38019ea82575c6a873fe935f963f6.nq.gz
│   ├── 7cba0f81e512775889b031cb2d04623f509c8803.nq.gz
│   ├── 7e03cc61e22f42efcb575dac76b9b0a686ca49ff.nq.gz
│   ├── 877e2bf17b2fb49e2e1ea5c9b62cd0f94e684381.nq.gz
│   ├── 8b25551a97921681334176ee143b41510a117d86.nq.gz
│   ├── 8bdefa86f02d7d800966574f1fee190d4ca3d5cf.nq.gz
│   ├── 8c8f09846de7fa9d259b93bbe6299116200b3b11.nq.gz
│   ├── 8dada3edaf50dbc082c9a125058f25def75e625a.nq.gz
│   ├── 9101f64d3ecdcf6d86a02111b88c986a81cf0bb1.nq.gz
│   ├── 91da013ebbee7598a53faf21a1b7a8a02ec5458b.nq.gz
│   ├── 973580e43d1ba22ac8b54b1e29d4aea3e09a2d35.nq.gz
│   ├── 9740c76ae388405181ccdc59de89e50b0f41fe07.nq.gz
│   ├── 9994a6cf2ce3c08e3ef4d9619435a1aaf1a918a2.nq.gz
│   ├── 9bcb66e494c72654d3e09cfa7bac9c86c27a2be3.nq.gz
│   ├── 9cbb7093ad71af9b4e1eb0af5e6dfa308da4126e.nq.gz
│   ├── a1daebf574f42baef94bbb6db87c0161bb0d0c18.nq.gz
│   ├── a6e8c9a645ed0a752d5a4c0ed201406e7f276176.nq.gz
│   ├── a9da11c846444b1965e7b037ca39301447f173c3.nq.gz
│   ├── b0f2d773b5daf66ffd5be90a93e3539483717ec8.nq.gz
│   ├── b25805e62badd12dbe0ff83cebc3f7bf3cf1c3f7.nq.gz
│   ├── b941d3355ee056194dfd5cf7d6fecc3067117959.nq.gz
│   ├── ba56fcb5ecb0603b47890193dc9cac0e26323ecb.nq.gz
│   ├── bce00f9ba9049b364dc5c24236427d532656d7bb.nq.gz
│   ├── c2728d01d88044a427d2d997165fd79435d11cc1.nq.gz
│   ├── c350216b4d34eacdafae1497c74b26e91878a202.nq.gz
│   ├── c3768bb5a111c2a0437949481130dfac1cd3d245.nq.gz
│   ├── c572dff311c700520150c22dba669d1ed07e9c28.nq.gz
│   ├── cbe24e54124cfc5fdf0a640eaede28af92202e06.nq.gz
│   ├── d15d73295208100fad56f0a16a980639a4d4da99.nq.gz
│   ├── d1ef5bba41470e2204642c4d408edb09dae46a40.nq.gz
│   ├── d693e0fa2309e32dbe829194025c6c8189d1c635.nq.gz
│   ├── d73a6f7b0129e1e7f148715a3a53fe7997c69776.nq.gz
│   ├── d94dd2bda81f43fc6a9140f303155390801e80f0.nq.gz
│   ├── da55fe7a2eafa2345c83d68a57a7760809728c53.nq.gz
│   ├── dba659170cd659da69d141ea20e471e9a7d3cb84.nq.gz
│   ├── df4d58fa74954e7252aae6717a3f78a145b05764.nq.gz
│   ├── e16029b269dc3f4af6c908bcbecb40f44e82109b.nq.gz
│   ├── e4a88a0f45fdae210e373a13c9d64f60d4018cef.nq.gz
│   ├── eb33e49ad8dcd559c0de2d87db7182c548a85224.nq.gz
│   ├── eba01e74a7bae1bdd0afb45d0b541723c34d24fb.nq.gz
│   ├── ed354f0f23e6e36dc5ea2e3e9a471e74198fa509.nq.gz
│   ├── f4116d94ec4d607c2cdb7f88becedfda1823c600.nq.gz
│   └── fe9d6e7998ab8266c0699a73080cb68415edd432.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7d8d55517b826c585ed0e1ddcb2ae4f4dc0b48c9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[arviz-devs/arviz](https://github.com/arviz-devs/arviz)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
