# Repolex Knowledge Graph of sunshinejr/SwiftyUserDefaults

RDF knowledge graph data for [sunshinejr/SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults), parsed by [repolex](https://repolex.ai).

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
rlex download sunshinejr/SwiftyUserDefaults
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 558c015e49524ebf5031b66980a722a4c225c302
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 558c015e49524ebf5031b66980a722a4c225c302
│           └── chunk-001.nq.gz
├── blob
│   ├── 0118829632c948b73dca928fea13f79ddbe54c68.nq.gz
│   ├── 08df991967790e8d6acd58b5352056e4edd280ce.nq.gz
│   ├── 096b0d9bad9f808d55783fcc870a2493ae87b36c.nq.gz
│   ├── 16d112b110e647a5c3639703727a668ef917b7ad.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 18e9c26e34224edd9ab364f029a34880da93cd72.nq.gz
│   ├── 190754ebd42b1e3b0bb4e2a18377b09237ce0f84.nq.gz
│   ├── 1ceafd983acf7b56cfb3af5b3e21d734b1713568.nq.gz
│   ├── 1e832c118b6088be6a61725d6677d26ca619df80.nq.gz
│   ├── 2202ab6b9975e58f930386ca5bb8c21edc40360e.nq.gz
│   ├── 25ac25ce88fe814aa2a6759b4ffa275f29b606a6.nq.gz
│   ├── 29127dbfb3e52c4db1a62f2cd797ed1548143eae.nq.gz
│   ├── 2bd546da89d8a37802b466f2edd8df937fecb5e7.nq.gz
│   ├── 32615a6070fa655b169312ffe509e17f263d3495.nq.gz
│   ├── 3a38dda990e307caaebe488e81e0e5ee2a884a94.nq.gz
│   ├── 3b66e9202eb3905b87fc1250c7ce6fce5f6d688d.nq.gz
│   ├── 43322da28ca092418aeefcfe0974937fdb9ada55.nq.gz
│   ├── 435f2c32eab032f4302371155a6be306539eea50.nq.gz
│   ├── 48ba4dcb4bd816718cb5f23d5f9036cf9ad8ca9f.nq.gz
│   ├── 500a7e254ae2964c5a2aaa6e1a60fc8ee0107fbc.nq.gz
│   ├── 57ada9f9d59f688e51c347028163d0b0c1522abf.nq.gz
│   ├── 585038f10608f4b01983b19a2d3eaef0013faf73.nq.gz
│   ├── 5fb7391d06d011da064f99e719a523a5172f3ae9.nq.gz
│   ├── 66973e060f21fec3a7d9294e02a90dcb72616354.nq.gz
│   ├── 6c2460d1341bccca1d351c1387d011014960d569.nq.gz
│   ├── 75938dd23909345e363fc117925edfd852012e5b.nq.gz
│   ├── 76f0038bea5579385b97c08c3195acae0f297fa5.nq.gz
│   ├── 7c23420d026058e6193fbf4dbcd4b8ce56d50440.nq.gz
│   ├── 7d92bcd905904ad64167cb30cf88e280946985a0.nq.gz
│   ├── 7fedcd8497ab4ae929891301ae800598f6d851c5.nq.gz
│   ├── 80a2d1e5921831652f6b24132d73cb04399ec21e.nq.gz
│   ├── 80b89be28b9a3faee2da8299223662d8f9ebe0de.nq.gz
│   ├── 83f50fecc0910c1d4d78c2edb3042a32435fe2f1.nq.gz
│   ├── 856791609618588e920ec52c00d14f3a2e2c8cda.nq.gz
│   ├── 889a212288c8afeb192f9aa5a09e74c06ad6b339.nq.gz
│   ├── 8a727265608550fbaf74e1763f94e4808bea2c87.nq.gz
│   ├── 9293b164432c3437a8d1bc99324494ee8fe211ea.nq.gz
│   ├── 97082d1a4da77daeb1478537221a0e286eaf6686.nq.gz
│   ├── 988a5ce3fd67d5d3330cdbc58038634c8966d8a3.nq.gz
│   ├── 98994bf53bb9536dd163ce43078d7fc220499706.nq.gz
│   ├── 9a2c84d2ddd575a0658e6b162f52d7c11df97028.nq.gz
│   ├── 9dcd04ac0714d0bf1f4ddbf889363aa066307829.nq.gz
│   ├── a72dc2b4c88a990725fad8c904a18052cd8b50ff.nq.gz
│   ├── a877260db9e0b45a1f043d4b274cb632723d4796.nq.gz
│   ├── a90fb5532f79f9f9d2faa62a7443b58291c94b27.nq.gz
│   ├── ab7349bbb25531d588b65294d1265f28c31a0837.nq.gz
│   ├── aba4316e6fc69d1bca7e9f2978090958ab708854.nq.gz
│   ├── ad6460b5486748a4120181dd287bd625a34ca12e.nq.gz
│   ├── b2b50f2871b083e8e8e797bf9d232f4d09d6359d.nq.gz
│   ├── b5004914268c664c9c6fcee93460447ff3a0460b.nq.gz
│   ├── b6309b84c3f260b02b40013c348ba032703f61ce.nq.gz
│   ├── b8c228eb4a1c3a12865a20fb9f24c38ae0399234.nq.gz
│   ├── c75ee0280bf5cc98c5ebb938c4de4397ea89d7a4.nq.gz
│   ├── cbd28355b1bacd3a6673b01ec005e20b565d19bd.nq.gz
│   ├── d5d418d8cef7035ca44fab425631d50181b86aee.nq.gz
│   ├── d7fb4e5fa84b4c7e532bcefc4b4c85a09d618f06.nq.gz
│   ├── db633379f340bf5ed95777379d4baccd5277c092.nq.gz
│   ├── e288094576ac25af5d04fb647cb58960b0ae001b.nq.gz
│   ├── e36394a6bd4fb5a1605c720f5626bbe08650900c.nq.gz
│   ├── e3c3bc9b040a6e811865cd01c49a3876ebd93141.nq.gz
│   ├── e8cbd48ee0e2cd987a7edbcc63dc05d9a82b3017.nq.gz
│   ├── ec1ca4fe0983f1745fec1bd41028473e72b24142.nq.gz
│   ├── eeb1bfacae5e740711fb6d27cfdfcca921c30f8b.nq.gz
│   ├── f85fdf49d45fe4507f67b21283dede7ef57c6724.nq.gz
│   ├── fe1aa713e49cb61676c22107abf2c87048747947.nq.gz
│   └── fee2d7258a31801c82552073a06368d7efc6d136.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 558c015e49524ebf5031b66980a722a4c225c302.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[sunshinejr/SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
