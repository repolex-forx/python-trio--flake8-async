# Repolex Knowledge Graph of python-trio/flake8-async

RDF knowledge graph data for [python-trio/flake8-async](https://github.com/python-trio/flake8-async), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/flake8-async
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c695f61dd9e237375c197f20f3a3eb41885b4eca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c695f61dd9e237375c197f20f3a3eb41885b4eca
│           └── chunk-001.nq.gz
├── blob
│   ├── 008ee5ca06c74d30950068a6f9a67708932238d7.nq.gz
│   ├── 00e092f5f8ac71126ca861433299420f7cd5b1cf.nq.gz
│   ├── 0137f891800f0d3242a8cf94804d1981e39e0d6c.nq.gz
│   ├── 01e07dcb1862b546a10e533edb94662e1db5acb4.nq.gz
│   ├── 040c39c1db0640cf0a0e7538bd5d7f8172f20562.nq.gz
│   ├── 04861d0786396e641215f8a5347a3ff54613cffe.nq.gz
│   ├── 054b5160accb8aa438fd245199cd4bac16c05434.nq.gz
│   ├── 0648408445dc8a5be912e04f1223bde757bdb865.nq.gz
│   ├── 09934d9845b1f5af9969baf9f9adbdf03a3509f3.nq.gz
│   ├── 09d944d4dd67828aefccc401ac362226ba51fa69.nq.gz
│   ├── 0abaf85b0c6e62eddd0b045c37040a6b088e4ffc.nq.gz
│   ├── 0c1bdc41f0bd4a5211e8d667c3a51c311a9211ee.nq.gz
│   ├── 0fc3af26eb1a868c2c76b878cdc9efd0cc51b872.nq.gz
│   ├── 1011ffb598ab780bd33543913b49021eac5f719f.nq.gz
│   ├── 118e77ab6f36ef6b3480d98aceaa27e5d0706ae9.nq.gz
│   ├── 11fce2377b15a3dea73d1e60f4fa0bd23488e40b.nq.gz
│   ├── 139e2e5d01409771f957a64fe2a4c2b7ffb672f1.nq.gz
│   ├── 13aa61253f138a0f7472bde9cca1be06f3146c2f.nq.gz
│   ├── 13bfea66e7f59bea92988b35bb2df114812137d9.nq.gz
│   ├── 13e3f5b20832a0122b57f416e7b8c154a98cf640.nq.gz
│   ├── 17740c298203f7ce5ac10ed75f30629609cce97b.nq.gz
│   ├── 180ce4d71321ff1cfd1026c9c31e86fc49b949e1.nq.gz
│   ├── 1a1a344029015e5ecf36a0f95c0c275965865720.nq.gz
│   ├── 1cf69e4508ffec0a2d2108cd4978877f57b8a9ef.nq.gz
│   ├── 1da27970715db8c93d809880b55a5ae4af31e935.nq.gz
│   ├── 1fa24e0abffd73c39d76090f6822fd96a00512f5.nq.gz
│   ├── 2082bcc6ad2676500cef505d57f006b140d78e96.nq.gz
│   ├── 22f907f1772adf92d9eb8176e529f0023b26c728.nq.gz
│   ├── 26c263830fc470b0e81b837f81c5256c295858cb.nq.gz
│   ├── 281d6139bbb69aeaf17e61c66e6c91ea58bc11b6.nq.gz
│   ├── 28fc0a1f95aa450ad2e8840a19c302d8e5c336f5.nq.gz
│   ├── 29f7c1b6c4ca3d3bf6703b75132362ddc808a8c4.nq.gz
│   ├── 2a33a7e1df6baea5c043b9eea65648d502bc4a19.nq.gz
│   ├── 2a9a3229aaded2374aa0a260c9aad0e7c7daef08.nq.gz
│   ├── 2b5baa44cf799dd552cdd13fb4b66239505d2f56.nq.gz
│   ├── 2d6961ca687fdaa5a422f5a79d9ce9d9006d958f.nq.gz
│   ├── 2df13ef3d38f059cce197a1233d02a3a9a2c8833.nq.gz
│   ├── 2f2850de460d177ab426c6497e7a96146477e65a.nq.gz
│   ├── 2fcd088dcf551bacc45ea636dd239c344553570d.nq.gz
│   ├── 30744be3f2a5a0e299a6e1e504a6a248eaaa3a22.nq.gz
│   ├── 33e36e1e654b4ecdbd62961d84f513acb870088b.nq.gz
│   ├── 343a0f3dd1fe501490f8d56a09f31adf6f4abb69.nq.gz
│   ├── 34e70b38dc66e1dda01316f6beaf902256775dd3.nq.gz
│   ├── 3583774ac84439045316b3f3631bc3b00096833a.nq.gz
│   ├── 35bf401405c71caa15e3b7ca18d2f0d54f614e36.nq.gz
│   ├── 35de765be7f996ecfed711386f13771993365266.nq.gz
│   ├── 35e03f60eb4b01d922d2cafa58de73e1e2ccd84f.nq.gz
│   ├── 370e0cd79eb827df31d9f75de8177c0d96a04a6a.nq.gz
│   ├── 3b6f5b0b2a12731596be4dfaddd60bd83fa2b2c7.nq.gz
│   ├── 3dcdd986c71b1fd1230b87a555ca06236128e470.nq.gz
│   ├── 3f86d507b8e1b5cff29c861129ec189d582a9ccb.nq.gz
│   ├── 419eb27da6064723c331adff06a5d56dbd2e7323.nq.gz
│   ├── 43f31a34e1713f639135b35b3003f99599498b27.nq.gz
│   ├── 4410dabd14e68ce058bcee0022de62159187b32f.nq.gz
│   ├── 4474ed262e34ead5f8e4465ad1d4d7ffd92bbf6f.nq.gz
│   ├── 44dd0252f62dcf480a3a8b090f891fc6c2cb50bf.nq.gz
│   ├── 46029224dbcb33241c2588f590f742ac2cfb8827.nq.gz
│   ├── 46118aba3493c632b5f2f1c8edf46c4dcee9a11a.nq.gz
│   ├── 487169f60673084be681ddbdd0a54e36e1eaeb8a.nq.gz
│   ├── 4a8a96eba02091e83e41e12c5a9660373b55c68c.nq.gz
│   ├── 4cebdb1b4df7039f560d4a0a9de9e48a147932f6.nq.gz
│   ├── 4eb7e7e4e66b5fc88965514c3675f4a058186067.nq.gz
│   ├── 50a2ea34add940d033f7157996d65f9c0a4397e9.nq.gz
│   ├── 51044db31d427f3afa0df59ae9186177754bdcea.nq.gz
│   ├── 51a4f6f3423d0efed265b3f69d6133362c149a90.nq.gz
│   ├── 520bcc76399aee178cc6055f07009d56b9e1d394.nq.gz
│   ├── 5332bd9ac8aba374ed4da6c3dc13df0ff54dc71f.nq.gz
│   ├── 550c47cd1e8cd26bcfbe11dc4a1ec894313edeee.nq.gz
│   ├── 5547e49d543cef82693f524a13739eece9945433.nq.gz
│   ├── 5a03e587971f854935a2db6f900308f9bc6e0b0a.nq.gz
│   ├── 5adce03dea72c560963b2a224ec9bc5e210c3d11.nq.gz
│   ├── 5d2754c534df45735e2926c26ec6664cfcfd41a5.nq.gz
│   ├── 5f40dd31af369e1343cd8adb87b9445e2b35586c.nq.gz
│   ├── 60aea33670c3b7dca3d88c93c3b3243229bac835.nq.gz
│   ├── 6119acf8497d26efa9ea17934a021b3d90fb1dc1.nq.gz
│   ├── 6160a81d6c70c592229f20db67e069cc32244594.nq.gz
│   ├── 61d535d9a1b03b517b7241e47b9ed4326b0bf050.nq.gz
│   ├── 62a0c3c1a38fb2c9de83bfa6132462fe2d2f38fc.nq.gz
│   ├── 63e9fbdd13a47358e3ee54a1e1beb00969dd1b68.nq.gz
│   ├── 64ea9476179e173b590cc3be3917794e2d0acf4a.nq.gz
│   ├── 65544cd6bbc1cc243a8125cf3e21183c2e5391e2.nq.gz
│   ├── 67039ec5ac59576ff3cdd9fa729cd5c90066fa49.nq.gz
│   ├── 694127f03a7977b758d10d48a277f0847e0558ee.nq.gz
│   ├── 6ca47f12f889103354107d65f8e9f9c902994726.nq.gz
│   ├── 6e0a70096ec5a5b19811a4cc39c70e5e621e66ff.nq.gz
│   ├── 6f158ffe9e4a71934055c2418e5a4deaf2cd6140.nq.gz
│   ├── 6f85d2a6275ae6128324b5bf88bbc2729a3cc41b.nq.gz
│   ├── 7092dd03bb5991913e93959ceaafdc5de3d3cfa1.nq.gz
│   ├── 713aa51bbae5e142fda7b17a681dd498b705c17b.nq.gz
│   ├── 713de228df99f2caf742ec467a0fbdbb77109315.nq.gz
│   ├── 76157ed4ac341682f0a4d6e7a4a22a0e454740ff.nq.gz
│   ├── 778684696cad4149fe25e59412686db0bf8b41d3.nq.gz
│   ├── 78881f0202ab85032d289435df4479bbb9b7e289.nq.gz
│   ├── 7de037709c87212c7a8bb2aee04134a351a2872c.nq.gz
│   ├── 809347be2dd809f822ac9ab172d441b83d6813b1.nq.gz
│   ├── 815733b10f7e3fcd18005c43546569a5c2ba3899.nq.gz
│   ├── 8abb4dba397bf37838829d61ddadf71b8efc10ba.nq.gz
│   ├── 8bc95d0a6fdddd9620e8685a64a3007e8b85f154.nq.gz
│   ├── 8cf036ecc8a344176a2868e82aec05648737e549.nq.gz
│   ├── 90cdf568e17fac3d8b14d8d6cd34a8528d57645f.nq.gz
│   ├── 935a31858d666e31a0c0ba0a9c2684abcec79066.nq.gz
│   ├── 97c0e35daf87afaf955c6e59bdfda0bc2d9cd6d0.nq.gz
│   ├── 9871d52691ec056cb70c874712df94ec2b52fdef.nq.gz
│   ├── 98866654950e3db54f32beee79b73a1b84cd1cb5.nq.gz
│   ├── 99b0dd7e1d489b6f27150cdb0577c02d2a884a43.nq.gz
│   ├── 9a1a0336361ffeec87cc126a68496367d3f1bdcf.nq.gz
│   ├── 9ac4a2c01dc22f4ea826a184433cb87ef5976f59.nq.gz
│   ├── 9b4a5bb4b84cd43448118d0afca5d29e795c1320.nq.gz
│   ├── 9c5583917f1d5ce7f52e02fb7ac61bbdb0d665ed.nq.gz
│   ├── 9e9559ec59335de67c92c417c251332a5414ddee.nq.gz
│   ├── 9e9738fb4299f9ef99cf742b97b9d3271fa04006.nq.gz
│   ├── 9f3b1e176a6aa98f4f14cf6bab6d4f6c21410147.nq.gz
│   ├── a063e011e7d320976790dfeb16850b8e79292f57.nq.gz
│   ├── a2989b39c994b753d20aa3441cdfe2985261f77c.nq.gz
│   ├── a58896448f64ba04c4d7ebe77e7c3487dd38e9b1.nq.gz
│   ├── a749d70c4900abaf6de3309e3fe49d2fadd16d06.nq.gz
│   ├── a79b25031cbee38ca10b69ee132ac2cd2203e2b2.nq.gz
│   ├── a80806b22d07674321fe385e4a1340fb5807ef16.nq.gz
│   ├── a8bef0cc0535e5f874e1c6c94244a5ebb32e656c.nq.gz
│   ├── a97345bc6ab45f87f22bf67a6d6613f6f838b5f7.nq.gz
│   ├── aab725db858aa79bcba5d662662e17c5c5899362.nq.gz
│   ├── ab66ef4cbd3eff6b886378f2c31a278e4dd8ae83.nq.gz
│   ├── ac63cca6be13506ef2e849c4364398053ba0d033.nq.gz
│   ├── b032abbf89c57b24ee0249df67a0cb874a96244c.nq.gz
│   ├── b1b7f1f88b02a636ccf2e2c096d9cb9b38121838.nq.gz
│   ├── b2a70d81b34917160ca39a9f1c0d8257a78f4770.nq.gz
│   ├── b32fb105068598406ad25ca316a09fd98cc2250e.nq.gz
│   ├── b4a1c48640d6d035bbf77395b948e55c68e30b6c.nq.gz
│   ├── b55942c4b2c30cb130a19d3c8b60dbc39ee3c8bd.nq.gz
│   ├── b60e5f99f6f0b87c5b07dbd7276b053b941a47db.nq.gz
│   ├── b6b86cb37808588b13fa465cf73c030fa8f081d6.nq.gz
│   ├── ba8475b19db926d2a6aac1ebe6244fc083f653d2.nq.gz
│   ├── ba9bd0b171cd265cd6e741514725ae02099d3885.nq.gz
│   ├── bac389b99e8d6dcae10f412031a0bff576140be4.nq.gz
│   ├── c0c4b7970e36c6dbbef815cad7a22f87eb5ca398.nq.gz
│   ├── c0dd856e5791bb92a00994410c110a11c91da3e5.nq.gz
│   ├── c347e50a7f2a21e21dc846dcb15cec556529b8ae.nq.gz
│   ├── c41474a466ce424b5ed892688ada20d690b7735e.nq.gz
│   ├── c493f311c56cdcfbafa69066beab7b68eab69273.nq.gz
│   ├── c4a899655a01356d96684e3f583ec5fbf78f3746.nq.gz
│   ├── c51e0afd81cce2ec2da9499d87a2b61404963444.nq.gz
│   ├── c5fd6336383155221e9fe1ce99ce8dd34a65e8dc.nq.gz
│   ├── c630b74d8c85e13c93fbef06979c2a95d4d60407.nq.gz
│   ├── c6bea96feaa0168ef8d3a9a8a8912c2ff108fe59.nq.gz
│   ├── c9ad061f2f71aeeb1ce6f4af136a0858e37492e2.nq.gz
│   ├── ccda813c02c896b82716815d0a51c153ee18ee74.nq.gz
│   ├── cecdb322afdaf77071a254423fcf4c2c0f017238.nq.gz
│   ├── d0e1691021836318e16cc4a33cb2658a87863c13.nq.gz
│   ├── d45305bc4c37d4b138ed281d36f3966e8cf39df8.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d855dc176a118248cb711af17019991bb1f9ee17.nq.gz
│   ├── d956c91a6ec5d6af7e762185d6c93be2c19479b0.nq.gz
│   ├── d96c956117f1021d5a9628deef926c918e020b92.nq.gz
│   ├── daad4f8fa33620006d170dfc9cb16e08aea24f30.nq.gz
│   ├── dae79a1b2bd2f7dd29138f00428d359ef050d722.nq.gz
│   ├── dc1312ab09ca6fb0267dee6b28a38e69c253631a.nq.gz
│   ├── dc1672879ac780e6734afeceb50345144fdfbab8.nq.gz
│   ├── dee5b7dd28bd834d0b13f4dac7f2be53b6867b74.nq.gz
│   ├── e187579ccd94940c6dbb68981fb1d45e9bde38d3.nq.gz
│   ├── e267dd41c2c1f83fd775ddfe3633edd8029e9287.nq.gz
│   ├── e4f54983714eed9fe3ad94b4df2517fa05b99663.nq.gz
│   ├── e522b4c7766e2bda391b4986477f65e7f899735a.nq.gz
│   ├── e60b9b8ed18080ec5de396fd3dd5fd98f8aad486.nq.gz
│   ├── e65eb6585baeaaf50a18ead258645187d321cab5.nq.gz
│   ├── e8b8e275ec0297538be78320bae62d781808d836.nq.gz
│   ├── e8bd478c712b64985f6413f54aaf6bdc517cb839.nq.gz
│   ├── eaf853331d66e95fbbe0b572735f0c768018486c.nq.gz
│   ├── eed3344c99244b9c2d240b5db3bf1174c8ec9493.nq.gz
│   ├── f0dabd5d0b7bd63c2bad23936ccb24538edc7fe1.nq.gz
│   ├── f285597677e4b88a59e169913abe1fc420947f0f.nq.gz
│   ├── f4149b5ea3187396ccd551997b47357c4b551e6d.nq.gz
│   ├── f640d4157497d784358c0378bbd4e1b4f6c4fc7e.nq.gz
│   ├── f736c5d8064d12cfa21cea5a5b1fc550ed682f22.nq.gz
│   ├── f936b8761df037e726fe5ffb7897656d83bc28aa.nq.gz
│   ├── f9b91d1acb88b90eda52d5b50c9047b4030132a3.nq.gz
│   ├── fb8d7a49dde19dcb6cc47f10dd5dc7ba6d409d4a.nq.gz
│   ├── fcbd338afd8a5a9741ff99481dc3c8c4a47fec9a.nq.gz
│   ├── fd5beb20b7d20ca258574abf5c217aa2b747504b.nq.gz
│   ├── fde01cf3e9eab874f1b1b8adb4b00a75b8b59e55.nq.gz
│   ├── ff089bdc6ee4ca898d638c257b54820885240f29.nq.gz
│   └── fff342e9626fda33b7076261bbc11865bb233493.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c695f61dd9e237375c197f20f3a3eb41885b4eca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 189 files
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

[python-trio/flake8-async](https://github.com/python-trio/flake8-async)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
