# Repolex Knowledge Graph of mrmlnc/fast-glob

RDF knowledge graph data for [mrmlnc/fast-glob](https://github.com/mrmlnc/fast-glob), parsed by [repolex](https://repolex.ai).

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
lexq download mrmlnc/fast-glob
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24a29c5c582966a95a9a8cca89b154d101434305
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 24a29c5c582966a95a9a8cca89b154d101434305.nq.gz
│   └── repolex
│       └── 24a29c5c582966a95a9a8cca89b154d101434305
│           └── chunk-001.nq.gz
├── blob
│   ├── 01927807dabec70da122cb1b3b3e547a55b72a6d.nq.gz
│   ├── 030beb81d8f32b3c42f74ebbc8423de1095c5c63.nq.gz
│   ├── 06994a0db3515c855a1036f92478570b0aad1aa6.nq.gz
│   ├── 079819d9055eb6407949bcde19a88d32fce7d935.nq.gz
│   ├── 090fe0ff30777c357d03e90c52306a8cfdb97249.nq.gz
│   ├── 0cc5a122e004cc25cc0fb06ca4361cd664e02cd3.nq.gz
│   ├── 0f18c51eded924d8218c8292109a3cee3f5df766.nq.gz
│   ├── 105c5fd17a2e1ae775aed3ff97f94645b9d6a6af.nq.gz
│   ├── 1085b69af998f09779848b6c5b710fceb3a4af22.nq.gz
│   ├── 12eb2e230e7223fe8c4c6337a8fa886c277a4335.nq.gz
│   ├── 200f482adf37bf2f324127632aec5d7a0ee7d5b5.nq.gz
│   ├── 209416292168f54a2271f56111a3f7f7ae520ce1.nq.gz
│   ├── 241e7757d915b678a2d7196705e3f4fab593273f.nq.gz
│   ├── 24e6c593cc1c542c23b347f14bfdcc90bc6a8a6a.nq.gz
│   ├── 278dc902e02413cbe5ecb09855e718323809d992.nq.gz
│   ├── 286fab4c01746901c8c01f5713f5d92878dadbb7.nq.gz
│   ├── 28fe6662640973430c6adb8ed7d58c7eb9c2cbe2.nq.gz
│   ├── 2988c8f4f7faf9a8ae5383a43925dd6587afb83b.nq.gz
│   ├── 2f070acae500533f26fad0bb7f23b7dd8f943ca7.nq.gz
│   ├── 30e1b299b344d5912f30e435ca8550c460d7d2fd.nq.gz
│   ├── 39096f1472667635bb462844489b7d3911c3da5b.nq.gz
│   ├── 3b5580827e1bb49d74752f21eb1d794c0a2e2441.nq.gz
│   ├── 3d4848426fcc2a3b4e6ce0cbf7af4e42719e3b2a.nq.gz
│   ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
│   ├── 4502b50d41da66251168be76737f14ed213a9f20.nq.gz
│   ├── 456f468f420505f0c95957ed0eb8f1fd01e0b2c2.nq.gz
│   ├── 4669a07ffda405974d8e002e275aa283b9dcdd7f.nq.gz
│   ├── 4817eedbf5755d3710c9a3c24af0bf7ca5681255.nq.gz
│   ├── 494dd9ad45dea9317a85e01c9a4d979bbc139992.nq.gz
│   ├── 52b0e8122aa2e78a8f91daa8833ee3e497327131.nq.gz
│   ├── 54ab5e3a2e872bff9a936d4ecb949128a9ad8f12.nq.gz
│   ├── 58554d49ad9129de6b807f1794fc629421154560.nq.gz
│   ├── 5895937122be0e276bb632c57a7eca78a718635c.nq.gz
│   ├── 5adf5b64cf5163088b3b07b7307bd6939c89b517.nq.gz
│   ├── 5c290d2c402da38fc02c649e73e33913809ea267.nq.gz
│   ├── 5e293f0b480309d23658553f89f5c7fbc3fc1e43.nq.gz
│   ├── 5eef4b01f7facc41cd59505a90af9a461be71f15.nq.gz
│   ├── 5efc6882fb2e1526533738bd65aac71b0935d162.nq.gz
│   ├── 624cac5b999a09234635ca5822da4de4b2c3ab00.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 643c577103b51ba3224fc7ed7e7be4e3efc9704b.nq.gz
│   ├── 646ed42efa20930a81d01f568b50a344690289fe.nq.gz
│   ├── 65a999460170355f6383b8f122da09e66e485165.nq.gz
│   ├── 662e444f07bb208cba5ae5e86bd551a0732bb282.nq.gz
│   ├── 676db3fe43a575b176f3b18666872327db471f8e.nq.gz
│   ├── 67d9b7ebed7d0e97ad1c20b92c361ed60a153e44.nq.gz
│   ├── 6be520a325df60dd8c039f7decaadb46ec2c114a.nq.gz
│   ├── 707bccc59c0d9be44b3ac2c4426a4ef3a66d873b.nq.gz
│   ├── 70bbd28dcd56d42361a8a99dd9a8942e34f8e829.nq.gz
│   ├── 76707907c2b7f3cfaf77672f5de2cbf689b3d483.nq.gz
│   ├── 77c38f5744960cf03097be37c0bd6a2d2ead765a.nq.gz
│   ├── 7b8aacb1ea30789f932da4eeeebb50f442816be2.nq.gz
│   ├── 7c999239ed98c6ed4e6474cde572d6a67cded4f1.nq.gz
│   ├── 7f0fdc36ebbc2731f2b4211ac82a44526b2e0d52.nq.gz
│   ├── 800b3a3ed28950b11ca03fe563986705d8e0d5b5.nq.gz
│   ├── 80a26f1a1b46b364febe2b61026e065fc06590e2.nq.gz
│   ├── 80fcb73ce5bf45fcf9e58184352436993e3d70c4.nq.gz
│   ├── 82796b532c04228aa21e4604458e4aabd27e8ac3.nq.gz
│   ├── 82ab376d5e14b3ed784fdd6bc3c8df99a7cb0a87.nq.gz
│   ├── 838cf149745c021cb969c95f7f332e7bef75f51c.nq.gz
│   ├── 85a018d92eb2320ef8b444c32c754a7b59f8824e.nq.gz
│   ├── 8dc397210c9536cb9969d1b2aa0ec982c7001caf.nq.gz
│   ├── 9524d3047bd65bb25a21777a8b367b3adb657cfd.nq.gz
│   ├── 9694058cdcbee0ddc459d398427b9e5dc5c42e4d.nq.gz
│   ├── 992dabd5260e9a8c556cd01a5c2b44bc52dc1ab8.nq.gz
│   ├── 99f4b624ea29cd5758cc634068ddc732a82816fd.nq.gz
│   ├── 9a8a1081a0f1c6d9743da39dce56358bf706e86c.nq.gz
│   ├── 9a9462e14bc2ad58f7b259bfca208e24a808ecce.nq.gz
│   ├── 9c3ca1c7b1e759d73450e4cabcfca714438c8418.nq.gz
│   ├── a06be6a59d7241302e2d8b4ef9913b3f43df7dbd.nq.gz
│   ├── a10628fa567546fa449a3d320dd9c40f85cc584b.nq.gz
│   ├── a2d02332cd8c4a72c1d36698780d701bded335ce.nq.gz
│   ├── a7113ebbd5241c26afe3362157fd571a4c67b2a7.nq.gz
│   ├── b004f454aadf7e131bacaf379fe995fa87d0d423.nq.gz
│   ├── b24bb37c845241e1b76b15dcde9d0343f1e3ffca.nq.gz
│   ├── b49802617b487f58c91ef68f89e60bb42ba7880a.nq.gz
│   ├── b91ee179698e95764115b435804f6968e93297dc.nq.gz
│   ├── beac14d0688001e52a3eb94c018989206c01b717.nq.gz
│   ├── bf1ee51c222ae35d8738c7eb6cb6457f8f712a49.nq.gz
│   ├── c0b18dd13df9cd17edf0cd4aeed31c1e93afc20d.nq.gz
│   ├── c8f3d4bc8e68654933c0a243ce8be4ba9d60be43.nq.gz
│   ├── c9dcc83851e5dfa4860ba28b6c0b1e079a843025.nq.gz
│   ├── c9f083fc99f37e3b2472a97eedc5d763eca61b27.nq.gz
│   ├── cc5aa7a9ed73cc962ac1bc81203341d6257f9e5a.nq.gz
│   ├── d2b5eb580298a59fa6d37f67424152b2006964a9.nq.gz
│   ├── d351472cc5ea634de868c7bae3605be13f73df6a.nq.gz
│   ├── d3a775ac172781301939d7fd2c88e8331f7ef608.nq.gz
│   ├── d7a947ef67f53dd504d43faccc272761b4d826f6.nq.gz
│   ├── df3f7d9330a1b6ee59c8041c246bd37319844519.nq.gz
│   ├── e4edd7a9bd1ef13d55636fbff7016e76836441d4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── efccb43f5fbc6ebc44e0a292506df88d5558f61f.nq.gz
│   ├── f0671ec6252416be12eb4618f301865878b5ee7c.nq.gz
│   ├── f65aa5a178b1dbd70ba8bb4eeffe1a4adf6c0ca6.nq.gz
│   ├── f698d58ac48df7f1152d6a5eb4ae1c87c7bfb325.nq.gz
│   ├── f7312500189ade6bef86d900fe475addd023b8b0.nq.gz
│   ├── f7647a04f9de4942a0aae03e19fca614af168b05.nq.gz
│   └── fe7628ab8a96396852632ae1c72234c4f7fcc79e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 24a29c5c582966a95a9a8cca89b154d101434305.nq.gz
├── filetree
│   └── 24a29c5c582966a95a9a8cca89b154d101434305.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 108 files
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

[mrmlnc/fast-glob](https://github.com/mrmlnc/fast-glob)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
