# Repolex Knowledge Graph of mne-tools/mne-installers

RDF knowledge graph data for [mne-tools/mne-installers](https://github.com/mne-tools/mne-installers), parsed by [repolex](https://repolex.ai).

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
rlex download mne-tools/mne-installers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc232046fde2a20f6bc851ee8ae3ee46cc4996fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cc232046fde2a20f6bc851ee8ae3ee46cc4996fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0668be497b70e9c061d04d6ecb23de6f5f2a04da.nq.gz
│   ├── 06bfbff2c7443e25c21780789054aba3e7dca979.nq.gz
│   ├── 08aef9aa3fe1fb4c6dfafefdb1997536f9d1ec3e.nq.gz
│   ├── 098321af99084bf0f67eac9f68877c488204debb.nq.gz
│   ├── 1d6320874ae93cca2883c589c56c0f41cd659ac2.nq.gz
│   ├── 1f6830265e7d2dfd62468cdec786605a240de620.nq.gz
│   ├── 21a263cfa84f85a0446c01ef4394e654e7040912.nq.gz
│   ├── 22a90e2275c0874c5adaf295b9b75754c273a75d.nq.gz
│   ├── 245e8ec50b6f30358087b576306165625e5c431c.nq.gz
│   ├── 24a4118058ba90627b1e8afb8d0a57e512242adf.nq.gz
│   ├── 25045d106d9826eb7437d46762b1608175e100a8.nq.gz
│   ├── 27ed89768d174443d16bbd85ed4364bc27241bd7.nq.gz
│   ├── 2a22e6668347244939764452423d62c463c1b9f5.nq.gz
│   ├── 2cdc8fccd27e353af07c4e23011f7ad6d4a090b7.nq.gz
│   ├── 35d6afefbd2765cac2f954908032f5453510f60d.nq.gz
│   ├── 38e22e63a9f810bbc12a35fd5f906060bc49c5bd.nq.gz
│   ├── 3c7896f60fee9bfa43f5ddfe8c1b0fd74bc0d30a.nq.gz
│   ├── 4551a138ce3981cbdec67a967a79dde61c604352.nq.gz
│   ├── 4bd29352001c7dfeb303e29b3de638446764a35d.nq.gz
│   ├── 518b0f941c3cbf58e6707253d1b3247ed64c9a08.nq.gz
│   ├── 5a88da41bad7a72cc00f73c957d68187e49d06ce.nq.gz
│   ├── 5a9f8258a4f47e90821ffcf96e3b383b2d84a5f9.nq.gz
│   ├── 5bea83f4a971ac4b913940fe07252de308d7bfe1.nq.gz
│   ├── 5d72d8bfd27d746abe6ec2161f42e131f6ae92e4.nq.gz
│   ├── 632174652f033063c11a563ed280302a5c61f652.nq.gz
│   ├── 635cde1b0684960bd9d1946f959ec32a02cdc24d.nq.gz
│   ├── 6443281112da2af9077260602edb465ac37e6f6d.nq.gz
│   ├── 66f945fb50c9adcbfda911e0115f1d2da9ee9f7f.nq.gz
│   ├── 6d21e70fcf886902dfbc652601abeb7cf19880f4.nq.gz
│   ├── 6ddc01b342cbe012df12e97581a3ec5423e35145.nq.gz
│   ├── 6ee1948857e5031f3f7138f912aeae7af2f6124c.nq.gz
│   ├── 6f3ddb57a9d42364dfc72bc09bda69ce313d9b54.nq.gz
│   ├── 70026f2469390facf6e32cd10196024b91f4db0d.nq.gz
│   ├── 70ec8b36e5cb06bcc6e09bbb5d1ea87ba50d097c.nq.gz
│   ├── 75d6e94731ef5e8f3a4ec9c848afa599e4aec84b.nq.gz
│   ├── 79af6b8c643fac63e121e9ed9bc92a0edef5c9d7.nq.gz
│   ├── 7bf90e6c14972fb519d8e795cdd8817397799247.nq.gz
│   ├── 7bff80fc581291b0c762c067f5ac2d58c67a9634.nq.gz
│   ├── 7cecbfcd2986d25d883a50d62fc4cf97beef42cc.nq.gz
│   ├── 7f791eb22c1f8c351a4f995caadce1c6812ee6e9.nq.gz
│   ├── 7fee3ad20eae84ccd9a60e8abe74b6ff6b78c159.nq.gz
│   ├── 836099c53a785cf922fb8c7d22b32dac825ea26f.nq.gz
│   ├── 8531136ebcce53e0b84f72c98827dd6d0fddce16.nq.gz
│   ├── 864f8160be8992ac58a32f3d06c59a9dc1a4fb15.nq.gz
│   ├── 8a4fd07fd384c1d0e3aa0fdd849292417917fc33.nq.gz
│   ├── 8f106917b096282368777e8800ba248a59a3aba6.nq.gz
│   ├── 907c3bc43ff01ec04029bb845692774d35ca0dcb.nq.gz
│   ├── 934843977c54f4582a939db34c078d608a7308b0.nq.gz
│   ├── 94abc5faed0a325e60bf3301c8c1c19bf1b7b82f.nq.gz
│   ├── add72c08d3ea4b9b913f661ba77409857ca61439.nq.gz
│   ├── af3f6b075a174de8d224ba2b086c829c4a8cf141.nq.gz
│   ├── b00e9f3237e4164abda7ad4e0a1f24fac4ac4555.nq.gz
│   ├── b465f32d5e4843d2594998f0fae7931aae7de783.nq.gz
│   ├── b61987850aae032152f9d1beffe7e6a3b489ad66.nq.gz
│   ├── b9ef83f89f71ce169c7628001687722abb4720ce.nq.gz
│   ├── bb5e8ba312f3e17d2bad6328ff534363e3bc38e8.nq.gz
│   ├── bea9c1912903eaf051cc5363f1f87c81f8fe2973.nq.gz
│   ├── c0b1471b8fa1a361c8c443d3b682208820fe0fce.nq.gz
│   ├── c104b239186445215a39fe7f4a0376db10487abb.nq.gz
│   ├── c5b42b4b41d495a4adf395246b3ad216a7975d63.nq.gz
│   ├── cf42223f2387d9e30c7e56abfda698e571ee807b.nq.gz
│   ├── cf4966a4226eb8412e16f3b265af3f9676677c38.nq.gz
│   ├── cf824a41ecdabd2adf5c5d0d68ca0e6eca8497d2.nq.gz
│   ├── d11497c6b147c2fdefaf025a314ab23d599df917.nq.gz
│   ├── d41678774967c161ececa9a9b37d1963429a2034.nq.gz
│   ├── dc41502dcddab6a6a43a857654a5c9e3ec5f33b5.nq.gz
│   ├── dda557417f4194a15c03c8a28f0973fa06761475.nq.gz
│   ├── e371bd212bfa695b0ba36c37a406a4299ab0adeb.nq.gz
│   ├── e52f4d1749c686e5401fdd483a8a92cc7abab3b7.nq.gz
│   ├── edb4607b129d54593274026f4fe6af2a45bda796.nq.gz
│   ├── f7166bb5cc54e86beeadac979eb216de91cf3a5b.nq.gz
│   ├── f85b57588c6f6446186ec582e1c8c588df7c4f18.nq.gz
│   ├── f92369c54cfec5ff9ef6148e4ae1c5d394a4a670.nq.gz
│   ├── fc976b6f2004149f7fb056de00bc8ad6d7ae8fb9.nq.gz
│   └── fd97cd2c7fd4b4a9a26979ec16f56b55e7f8bcc7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cc232046fde2a20f6bc851ee8ae3ee46cc4996fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[mne-tools/mne-installers](https://github.com/mne-tools/mne-installers)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
