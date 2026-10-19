# Repolex Knowledge Graph of pysal/spopt

RDF knowledge graph data for [pysal/spopt](https://github.com/pysal/spopt), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/spopt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aeea0e690ef68193d439a42a8ec6f84470bdfb8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aeea0e690ef68193d439a42a8ec6f84470bdfb8c
│           └── chunk-001.nq.gz
├── blob
│   ├── 002419782640d8f620c62304185b18734de33693.nq.gz
│   ├── 006fb26ba6961ef818400451c4848f33d734940d.nq.gz
│   ├── 0234c1409f72101c8ee142bd2e849be6cccbfa52.nq.gz
│   ├── 02cac2d075961f20d00c19296d5f422a3f0a7bb3.nq.gz
│   ├── 039f91a4b3f303e189bff2bdae4c1caafa7f14f7.nq.gz
│   ├── 0607fbce1c5f4e3573bd131c220f3230da4b27f1.nq.gz
│   ├── 06700a59d9611a8805d24cda6fe978e41e79a8c7.nq.gz
│   ├── 06e209c4809cc7294289d9f73a353a1ce072810f.nq.gz
│   ├── 0aa3d2f68ff2e1d1a310278c78feb9cce53864ea.nq.gz
│   ├── 0ca29bb1e5813242911ce9eddde1143b9e0f1f2f.nq.gz
│   ├── 0e7e73dc788780d9ce77dc770a7daeaf00f7bcb1.nq.gz
│   ├── 0f0a0b4132c5b62ddde7bdb403eed645ff0abb03.nq.gz
│   ├── 0fe0ea09701f41ad134072e7142a1ba6dcfc378a.nq.gz
│   ├── 10e3f2aa23f2505ae43cbda1532eb8e11a10d528.nq.gz
│   ├── 12914402838232c4f342ae49807511d54eed7f37.nq.gz
│   ├── 1481ace8e366e741fedb89f0a34312cc8844e3ea.nq.gz
│   ├── 17401972f19c732966ac6212ade21d09180ef2cd.nq.gz
│   ├── 18fa38a6d1cc7c56d7716f35b1827030e3d6d04c.nq.gz
│   ├── 1bce58ed94ee63ca02edb34f841e6fcb1b05ee8b.nq.gz
│   ├── 1c7b0889adb6bd3baaf10e3a26ce62af1176970c.nq.gz
│   ├── 1c9d46c32130819952f39e18c75439da8223dbeb.nq.gz
│   ├── 1d1f3f9f90d24aab36bc966b3841ebc4adf21bdf.nq.gz
│   ├── 1fd315505fdc0081eebbfe3600364bc7b640785d.nq.gz
│   ├── 1ffdaa23e9bd596c18cfe49e22971291bbe8ae25.nq.gz
│   ├── 2013c558c3d2934c677a4dba77b24ec458c4a16f.nq.gz
│   ├── 218d539e2bcec7a54c208f7dcbac3ae2c2b7e8ad.nq.gz
│   ├── 222f04393156c72fe8a5816ad2fb8e6813f3d533.nq.gz
│   ├── 2551e1818976c10db8348279e34cc3fdda08e043.nq.gz
│   ├── 25a918d7a240d0096b722cfd49b1800a057f407f.nq.gz
│   ├── 2636c17023b4a6819d01f1488d56ac2010166995.nq.gz
│   ├── 282d8e08ca4c7c9f545032d64e5267c3f11baece.nq.gz
│   ├── 2c071d2d193fbe5f4379fe45261ad593f6452e37.nq.gz
│   ├── 2c4b58c8f756b2d2dcfab8a105ed93fd5078e3c3.nq.gz
│   ├── 2d91d2b6959cccabc4d7d2f2608792dac22732b4.nq.gz
│   ├── 2db3b1ad9a26cc5673754a838d26e84fad34c04c.nq.gz
│   ├── 2ed86f3d5b463f01e1e3492fec51e79388fa6069.nq.gz
│   ├── 2f1b5306018476930d601cac0fbb54091c2411e6.nq.gz
│   ├── 30d174eec15209e4380066c684646eec84e9f8a0.nq.gz
│   ├── 35671efeff6908eda106743af97851fba9fb542e.nq.gz
│   ├── 3698d46058d7c4e03bfd508351c4cb7580ece4f5.nq.gz
│   ├── 3916d48e60de79d051cbc8c8f187d502f49bd44f.nq.gz
│   ├── 3ac2ba3783dfca194358f7945b81d450f5129d39.nq.gz
│   ├── 3b2d8ab2271b462345cc77e3f10721dfac93c56d.nq.gz
│   ├── 413ea4517d0a9a0afd46a3fb7b6d06072da5a9b2.nq.gz
│   ├── 4180af682026d5af26af44362a7fce5412af67b0.nq.gz
│   ├── 475a78675ba8ed3aa4e013eb80f96b2621e3367f.nq.gz
│   ├── 4aa40ea5fee72e6bf6deb80cb0e9f9b1c97aa13c.nq.gz
│   ├── 4dfa0b11012c565e8621b7ee262ad7ca000658a4.nq.gz
│   ├── 4e1790d5fab476e766ac0d71d89094777768baeb.nq.gz
│   ├── 501fe001a918cce86a521f26df2bf92d2f830cdf.nq.gz
│   ├── 5126409c9b64ed5a4a71559e533264bf80ff30e7.nq.gz
│   ├── 52402685f6a890a2efca081763daccad214d07db.nq.gz
│   ├── 538af48b1cd2ed7c7ef2e7e10710bd0e22f54c7b.nq.gz
│   ├── 5449ad3906558206e514abdb9c70c9dfd321df13.nq.gz
│   ├── 577ce034459987e2caf59b830bd3cfb853ad3087.nq.gz
│   ├── 59fce9521277138ec5d287567dea68c66ac79de6.nq.gz
│   ├── 5ba6b0d6201d0efcc920b2bf290799e5f02c65fe.nq.gz
│   ├── 5bdbb681ec481ef1e598d9ce5149ec1cd261e867.nq.gz
│   ├── 5de7c22021943af0fb181c9d44b2ddf7a4ddf4bc.nq.gz
│   ├── 5e3363f165e3d808f01fb5ba67dfa490d32dac97.nq.gz
│   ├── 5e50f3c5071212b626b923b4183aaa9cf414315e.nq.gz
│   ├── 63980f1a9c798c6c26291011ef1a5ed6cf14f061.nq.gz
│   ├── 65062f077df158b1670534088887280d22aeca11.nq.gz
│   ├── 659579a2a4bb66574a268cf449c1ed4923088ba5.nq.gz
│   ├── 6c07d761408cbdf6560e251cdd96bf4339b67288.nq.gz
│   ├── 6db5869e688bedd42bc2a3ba5d16e7966d01a6e4.nq.gz
│   ├── 704f03aef688609c3257d5737886b9a940e547fc.nq.gz
│   ├── 7527068d2531dcd4d25af7afabd59fc267d5f651.nq.gz
│   ├── 7548b770f8bed33b80b8cb98b7d8bda651d3d281.nq.gz
│   ├── 76fcf5f500565923ca098193ec1318cc6453b215.nq.gz
│   ├── 78d1ec3fe2cdeb9a5d6d6c4b1d581b42bcfb41c7.nq.gz
│   ├── 7aadb241bac69e9cba0c56696b30a43ccb9e120b.nq.gz
│   ├── 7c99db17bb6f705cc4350cafa48dd256679db91a.nq.gz
│   ├── 82c95dd7e8678489fc919f33ca5367709f74116e.nq.gz
│   ├── 82f5851c650d588d44813236a0dd12b2e69b2aa3.nq.gz
│   ├── 8370f5df78ab4d366509f0dfcbe723e60abf3a8f.nq.gz
│   ├── 84cfa603a7fc0ad7044c00514ec622ff346e88d2.nq.gz
│   ├── 8843e73fcd2e10644abd3ad3eb6b17721be74df9.nq.gz
│   ├── 886445f7edb0154dfeff0ec587d33e84c7184163.nq.gz
│   ├── 88ef6c602f727aece57b0cb39bf644ffcea71730.nq.gz
│   ├── 8e588d5a7a6d13d02ff688047f528ca75618e2e1.nq.gz
│   ├── 905721275c11e6191d043e24313c1699a72a85ee.nq.gz
│   ├── 9221bcb3c13dd3f99c36bbea65dc7f5788affb22.nq.gz
│   ├── 945b29bc51d4e5249b83d7ec8141c13ee94e215e.nq.gz
│   ├── 95e3aa8415a10b9f083fb6a82c70d4606496d6b8.nq.gz
│   ├── 99ea342b9972cfb3bc03c069ba7b432c01414a01.nq.gz
│   ├── a142aa9ffeb09f0f4e969b0ce3134e1460a13657.nq.gz
│   ├── a270119b47078487d351cbed74815965ffb70222.nq.gz
│   ├── a38e9f6af259f0781b4d2ce821b7251d47306aeb.nq.gz
│   ├── a4e18999eae58daf26d66740d594ed2b7316fb80.nq.gz
│   ├── a5a5bc781c3a8f9cd5259b25c4c17cfe8c7d8c09.nq.gz
│   ├── ac8f740db7be5c3206c893cfd04d444a866d096b.nq.gz
│   ├── ad2c0831e65f389bfd511ed6ca3e4249f5509295.nq.gz
│   ├── ae2ee68479861ae0da25bffba61fe0b77368f06c.nq.gz
│   ├── b13d1cd948139cf139ff9a0d0d54adc10ab4f8ec.nq.gz
│   ├── b15ce8f8a0e10c4a16e39fb33c7de1675d4b555a.nq.gz
│   ├── b33de329a335a0436d7ec997d3c67c54dbe9face.nq.gz
│   ├── b3df74f80b4526f95e1b9ea91c3e6a0c67ba2d12.nq.gz
│   ├── b4549d117925e9e229cde791293459ee6993d570.nq.gz
│   ├── b73701eca9e9f4b85c1e53eae4d8ae6bf8fd69d0.nq.gz
│   ├── bb67fe714eadcb0e0bfd2b56b3dbe811a1a31c84.nq.gz
│   ├── c013f38c98ba28ff05c978d6ad4559d6bc655b6d.nq.gz
│   ├── c07fded27a05034ab74fd75398a85d49c63e3252.nq.gz
│   ├── c0f9eb50423fd8c9481791ca362d678a70826780.nq.gz
│   ├── c34df19873a71987d9e7e85249c31d1ed2c2f448.nq.gz
│   ├── c36d78b6ffdb12c08856d521e348b2f9d07b5baf.nq.gz
│   ├── c38a525917c4083467a907af9665b6cef7da6225.nq.gz
│   ├── cbeda928b7a2ccf5ea94594dc3e0c471294b7364.nq.gz
│   ├── cd07ac5c2f3a45c1e6709496e834219c6553574f.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── cf1e809facc868918d970188a25a0534625ab008.nq.gz
│   ├── cf4693b6ff7e436590263a0738b34e53fb61a58e.nq.gz
│   ├── cfb0bd14d98fcf6c5349d98bccc763cda23407da.nq.gz
│   ├── d361de2c71e274836aaad523b71bb5d1ce1986be.nq.gz
│   ├── d4adc94c2b12badf445d7fd7a7bd688798a49086.nq.gz
│   ├── d7c3c14116628285e531e93dff3a3db697006ad2.nq.gz
│   ├── da867368ed26829f1befc8f5ce1588f161a2f029.nq.gz
│   ├── dc8747e7a945b7051acb5954de67b1e468ae5e3e.nq.gz
│   ├── dcd9508d44c678312e363031ba96559840ab6718.nq.gz
│   ├── e0724175d5149697055429d3164287852af9b178.nq.gz
│   ├── e29313bc6707e230e07fc0372002dfc235437c74.nq.gz
│   ├── e399955ba5046716f429d7087784fe0b47f783e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e927a385496190c89ee50b98dff00c1482a5fa13.nq.gz
│   ├── e9520fd20632117547c9e1b345d06e7de90e708a.nq.gz
│   ├── ea08e83613ed6da8017db757e153a6ee07d68b02.nq.gz
│   ├── ecc37da454268801ec5a83dca20cb0531f6881de.nq.gz
│   ├── ed76b9c2728a9df9030af6761d9c82862ceef927.nq.gz
│   ├── ef4090a35708499db47a02a3323e28a31779191a.nq.gz
│   ├── f05231bdb454ef2647fac7fc027a19fca23742bb.nq.gz
│   ├── f0dfb7cc0ce56d197d8f4f69e55eb70e772013b8.nq.gz
│   ├── f1782a0d9e657ecf21bc55998432336d7037f482.nq.gz
│   ├── f2a0648312234a1971ee5b60bec0bf570fa70ec7.nq.gz
│   ├── f4c7e5f018f631dc0da4de60c67faad93903dafe.nq.gz
│   ├── f5160c9aeffc7e8355d1a85f6c323f3b4d26c768.nq.gz
│   ├── f71f35bd8e4fb4b91c8312d32d5b5203ef69eb33.nq.gz
│   ├── f742783e5d6c33475c1d7dc72879b69ea5a3c810.nq.gz
│   ├── f95673e3dcee2928fcf753c63afaaf181be48cc6.nq.gz
│   ├── fc2816caa8ba34bef7ef093fc39946920f1383f7.nq.gz
│   ├── fd34423b36d156282b46cf159ef6d037020ac7cf.nq.gz
│   └── ffd626ce75ba69cffa29a2e426b0b42dde6fb74b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── aeea0e690ef68193d439a42a8ec6f84470bdfb8c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 149 files
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

[pysal/spopt](https://github.com/pysal/spopt)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
