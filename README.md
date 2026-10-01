# Repolex Knowledge Graph of anysphere/relay

RDF knowledge graph data for [anysphere/relay](https://github.com/anysphere/relay), parsed by [repolex](https://repolex.ai).

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
rlex download anysphere/relay
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d4d4a7ae743926d62b6c2008741d8d91573ce560
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d4d4a7ae743926d62b6c2008741d8d91573ce560.nq.gz
│   └── repolex
│       └── d4d4a7ae743926d62b6c2008741d8d91573ce560
│           └── chunk-001.nq.gz
└── blob
    ├── 010f9423e56e03576c9b4f06787cfebc7570ec86.nq.gz
    ├── 020a7b379a38ae00e76d2e88b02145e74e9ba6f4.nq.gz
    ├── 021c552594d7bb9b9c65917e8d7f81ff0fab893f.nq.gz
    ├── 03439831886b54129e6dfddce643c298fe0ce533.nq.gz
    ├── 03da4409b24355dcac03e3b84175bfa1ca0c6d91.nq.gz
    ├── 03e4aed9df0f9c74f307daeb7fbf88312421c201.nq.gz
    ├── 047c84d6fddbe323f3fd205dee2be0f646044241.nq.gz
    ├── 047e973052e9dcca19a57154bad113ce1d2be8dc.nq.gz
    ├── 054120ca876456326ac8cf3ae04541019287b994.nq.gz
    ├── 056f859b1ba8db58f11184184ce485b42b148788.nq.gz
    ├── 0576d272cc997598516b728881364be3a0742650.nq.gz
    ├── 066e2e8013562dc9b349517671f9a98a5ec4f645.nq.gz
    ├── 06ba71aedccb8575751116c0ad68f3201ce22847.nq.gz
    ├── 075dbd5c3484991077cdcb12de95040fe69552a1.nq.gz
    ├── 07f2c1935d325aa304e8d4b46e92622ee3d4508f.nq.gz
    ├── 08bfb0adc38a5fcab9ce97d4ceea7b474e9ac55d.nq.gz
    ├── 08c40951812fba75fe439ab5faaa5feade2e9793.nq.gz
    ├── 08ffbd43b7d3f122420aac24ff9eb938d781c36b.nq.gz
    ├── 09a1cf867078d9ce25726a53b9795ead5f0eef32.nq.gz
    ├── 09fef4d9272afad6d60cafd1c36e6721d8d4c83a.nq.gz
    ├── 0a5c96cdb4df37399920fe7a97ad37de517c8918.nq.gz
    ├── 0a747e4fad1b1cecfd85171f4320704f932c26d9.nq.gz
    ├── 0aca2a7fa1881a270423addd2e0c75e22b994f35.nq.gz
    ├── 0b39071e6c6b7a565b3ea05f261c1c714e58e7af.nq.gz
    ├── 0b3f3a78c3347e4f3b8a36c6f82bc8f52769a53d.nq.gz
    ├── 0bb88e93335cea653dafaf5407368223345c99e9.nq.gz
    ├── 0be74e8b5398816996eb48506757476b36af0ab0.nq.gz
    ├── 0c058ca616c98b12b2bafa027a01a2c3820a40d1.nq.gz
    ├── 0cc5a7714c641354c681125e71d246ea8efb6457.nq.gz
    ├── 0d103ce4c3882d0b9d74c2b8a5bce79d8bbedd0b.nq.gz
    ├── 0d2c02dbfbdcc8b5153730151f31c877922a62b9.nq.gz
    ├── 0d510b08b2392724c7b059156bad4583299f03b2.nq.gz
    ├── 0d64d2f4359f2443e10007383f5866875bed109a.nq.gz
    ├── 0e69508c1eced04471b8c04e043849f26cf68fc0.nq.gz
    ├── 0e807df418fbef35b8448d9eeb5a45070493e8ae.nq.gz
    ├── 0f8b7a1b82c2413ddc60aa350476563b49866ba9.nq.gz
    ├── 0fd23b4cfda21c7a3bf0590f82f4356536dd9ac1.nq.gz
    ├── 100b2d2f62c7a57ab932ecc87130b84c903f3caf.nq.gz
    ├── 1014c40bb72604a98500b0de5923daae4c68acee.nq.gz
    ├── 119556872b916011de7d40512cbd380b23e14de3.nq.gz
    ├── 11aa12d50659315a147e23bb69febbf38cb7826a.nq.gz
    ├── 11bdf734ee63e691963c47b819d2995f20c5c524.nq.gz
    ├── 12f5d2c27d05676101860c6d6643d60ebbffe343.nq.gz
    ├── 12fec9b1fb6b3a8501b9d0f54f70064fd2e97603.nq.gz
    ├── 131da7639642b649dfb0d428bcd76cca4854829f.nq.gz
    ├── 1326c64f856bb48ab732bbc12955b69bc760f29a.nq.gz
    ├── 13815a3d1a06f5ce0896b690c71376cce131067a.nq.gz
    ├── 13fa5b2b94ee0cc2618142e0e6d31b9e2b593725.nq.gz
    ├── 140dfea79cadf96f778cfd959f7ffb62408952c7.nq.gz
    ├── 1475a270c923b7cc5653bcdc30b6b9ae41343c8c.nq.gz
    ├── 14d58037d29bb535fdc2cc0c411f366d597cb828.nq.gz
    ├── 15ad55c64c9383f5ea3520852b211268e7e92292.nq.gz
    ├── 15c990405630541a1285bd0319740ffe90d77d0e.nq.gz
    ├── 185144389bd10344f6f1144857490c6826231957.nq.gz
    ├── 18e66f7bcf0c9c51d4ab172fc19a93e0c4d49f1f.nq.gz
    ├── 19640b39e6af3970f07e893632e8443cf7f9c019.nq.gz
    ├── 19f467c6977d7ca0b82d029e9a5d6530f15d4cf0.nq.gz
    ├── 1a7e5c40159bca85ce7b7c11b748addeb1686208.nq.gz
    ├── 1b856259ea67918e1ee1c8a0b3a606d3da33c33a.nq.gz
    ├── 1b8fb4487923154d518b00b6b6599e4f62716ae9.nq.gz
    ├── 1bb22adf59c8559219e8dfa7b0801759e71f9054.nq.gz
    ├── 1c73b18ac324ae419e77a329f2fbf716110cc613.nq.gz
    ├── 1d37e82fd6278972c928f422a48c078c82fc4dba.nq.gz
    ├── 1d4de46f88859bcafd246bbdd710280da5fca277.nq.gz
    ├── 1d5d0a81d7613e4a156386d10998eb8556eac3b1.nq.gz
    ├── 1db2f05e4654a7ab76d1c31cad7c777b2ff8bd61.nq.gz
    ├── 1e427015f5930f14dc87fadcfe0eef20e0eaf943.nq.gz
    ├── 1e5f0bc7719c291c9651396c6aaa3aa9a2416fca.nq.gz
    ├── 1eafb84f0b4bb5e53df1ae65d2e3e2ddfdccc927.nq.gz
    ├── 1f28ca849909c0164d261020c73a44e97966f7cd.nq.gz
    ├── 1f5ff4cf83ad0b9471847b7ce947a9d5ba7d7c8e.nq.gz
    ├── 20557128deb5a91d4f3fd845a750334ef76f1b93.nq.gz
    ├── 20703731a87a240b127b5346869c9bb4c3fbd1de.nq.gz
    ├── 20e520cd17bcebfba4dad334ff1b21fecd5b2430.nq.gz
    ├── 217bae1e8f234ef5bda8d824c93cde7523a55d2f.nq.gz
    ├── 21a39f074641a579cbc2bec1075e1411d38bda9d.nq.gz
    ├── 22c6ce16395ebfb3ab4a11b5a720aa55f4d3e7f9.nq.gz
    ├── 2341b928d3811dae5a68259ab70cad4cc996c7eb.nq.gz
    ├── 2368a787b01d126b588f92189e1ee06cf5485729.nq.gz
    ├── 239b271f01ed75c5df87213a4a788e99f6bff8fe.nq.gz
    ├── 239d3fbeccaab608cffc53d0ea65aa0fc3062b69.nq.gz
    ├── 2420d2a88f571b5474899431ace5be9f3cae020f.nq.gz
    ├── 24bf29b4621ffc9a13c8fc46b0e09aa0f282c36d.nq.gz
    ├── 257de6f70f07aff538feb92792caa980057d35bf.nq.gz
    ├── 25b7b1dbd2c1e633fb9a9707c0215728440e1f16.nq.gz
    ├── 26aca75bf0d224c9a36b95d2c09489066c9e2bcb.nq.gz
    ├── 27477e18e8d18bd93741cfb60318644a761addc4.nq.gz
    ├── 278c9f389424659cda03504b974ce9cfd13ebc1f.nq.gz
    ├── 27c471f835ecd49b0cc7b525c670a6a3428185f3.nq.gz
    ├── 28bf5449f15f160c4d7eb5ff85c4678e880bdc80.nq.gz
    ├── 290fab13add701a94177f6aba3ef15b710c10d9d.nq.gz
    ├── 29546704a7c78605acda357d991e6ff932a53fec.nq.gz
    ├── 2a336b9d0d267a9ed21456022fd67c4835fac204.nq.gz
    ├── 2ac512e69c71ddc2cb37f363e26bfb9c29f310a8.nq.gz
    ├── 2ba32da87e935ac688cf1486608dd6c1e07b8441.nq.gz
    ├── 2ce7b0990092034f144994d87df35a396cc190a9.nq.gz
    ├── 2d0995594d59e44333cb2b4328e2bea85ede6037.nq.gz
    ├── 2d289d19ba9d3cb80eaeac91147c64d0d6eaa8e6.nq.gz
    ├── 2e596e790c7df2767dc92ff9a929ed301bd09325.nq.gz
    ├── 2f67d4e6cf830ed53ca871bb1e966c117c23af13.nq.gz
    ├── 301ae0b23901604975778ac5ec87c909b90e6569.nq.gz
    ├── 30b97eef96ca049ee113b1c163ba7fc5aaf6f0ee.nq.gz
    ├── 3102803496a39731a7d275a615b759cb144e9658.nq.gz
    ├── 31135aa06e368b1703e42c0151f478435038ce35.nq.gz
    ├── 311abea398c9a1a9d6db171cf5cf700de5f624cb.nq.gz
    ├── 31b107f84294eae62937c0f61d2ea9ea53dd520c.nq.gz
    ├── 32589fdaa241714c8cac5c12313549fa6f7edbde.nq.gz
    ├── 331c4471f74060dfaccc227169e0bb009ef859ed.nq.gz
    ├── 3356f9c8330c38be6f9c84199223c37a3d75e99d.nq.gz
    ├── 337f79b57d26afd222e6e61b8f43f4615eecfee9.nq.gz
    ├── 344f8bf8ed00865f05e5a4cb48417cddcb4dc9df.nq.gz
    ├── 34806998a1e12412f6e50e1bacc875741e752f3a.nq.gz
    ├── 35823353f43f6bcbbbad4251f481c238c24b4060.nq.gz
    ├── 35c06cd0ec06926951c9fb50ee03fadab70a2a38.nq.gz
    ├── 35f6cd0a8898ea59c1ddee4c9ecc6b641d1db6fa.nq.gz
    ├── 373c0ebe0aa72c0d1b2f36f32bc00367c2d660e9.nq.gz
    ├── 37620490534d6f4a41fee6a2de3815a023e72651.nq.gz
    ├── 37eef1cbe64f517dcffb6502ca578e1c20f27f61.nq.gz
    ├── 37f7799c37e02132ad986e5b61da40a6a0baee47.nq.gz
    ├── 383a42df36be653209e780c9d92bd885e375f962.nq.gz
    ├── 38d65a5d01b04d2547160c729bc1f8a57c00a6d6.nq.gz
    ├── 3aaab2fc1ae3acbbb437bcc52a0e9fa86d1c2e58.nq.gz
    ├── 3b0b0121c9d213134ac2cb91001e485e7125cf2f.nq.gz
    ├── 3b477a46af8fce5196bcb7f51babd21270dd0480.nq.gz
    ├── 3b7c4b6146f4cf5a64795adc0631d0451ae2832a.nq.gz
    ├── 3cd22f5f91be25b284078cf25a84ae631ddb01a1.nq.gz
    ├── 3d0bd9f38f3d0ab9282427a5e4009d7e06ef1622.nq.gz
    ├── 3dee8855271eb4e456d0f8880ca418ac1c44e194.nq.gz
    ├── 3f6ef6d27946bf6a9636a71f2d0f61b781c109df.nq.gz
    ├── 3fed3c03a52761723724c494ea5c91eb99f196ce.nq.gz
    ├── 402cf4f6c625cf083d2c178eb1fd40148f244709.nq.gz
    ├── 40424bad0d208f0a4c51f74e3d323fa4e691a841.nq.gz
    ├── 40b213dced260a6cae0aebaf4594fb384716c12f.nq.gz
    ├── 40b34d2361241e2f03a82ee26f82d68a8d16aad0.nq.gz
    ├── 40b6cbf3c318be3fa0c10a9ceddf8f1781934219.nq.gz
    ├── 40c0ff74072e5cb1db21bf1509762ea9ca07233b.nq.gz
    ├── 40e820d8613f6e67f9da7329798646d93c8a988b.nq.gz
    ├── 4236d41ee1f3109f336b3e1cbb73e66e0faddb84.nq.gz
    ├── 42deb387195d0b7e8cfe6b3aa4f05d24da10d323.nq.gz
    ├── 431e8c24c076e41be93e5be126a9066711411873.nq.gz
    ├── 4342c649539dfbc18bcb24b7255c3f4cda7c55ba.nq.gz
    ├── 438d7fe101c909ca3436c8e8c1c0e0019bdcd5c7.nq.gz
    ├── 43c18da81d8da529526fd24289ad69f1b6c1aa41.nq.gz
    ├── 43f03a07dca54847b64945087f2b2462923d3074.nq.gz
    ├── 44b1aedbe5e67dcb6ec0f5613eef48ce90da092b.nq.gz
    ├── 452deacdd65a23bf348903b5c6e23ab4ad44b9da.nq.gz
    ├── 45cd02693268f39e85dfce61aba8dbc4403f00ee.nq.gz
    ├── 464200ea19c274f6676e661b3fb52bb749e4cebe.nq.gz
    ├── 46bc00f091bd450a3908f9c446d44aca1c9634f2.nq.gz
    ├── 46e989c64588ccff573ebd6eb248fcfa6cb552c3.nq.gz
    ├── 478c4f900600b2640efb3fb7cc7a994a0da9e754.nq.gz
    ├── 47e9b1a644fb931a9fc603d6fd29b6216fb9157b.nq.gz
    ├── 486b8cd04f4d1289bb3a0302d42a070a942a2848.nq.gz
    ├── 48c83ca0c26ad06bc5c103b451a61e205c93e549.nq.gz
    ├── 48f11c8fef38755b9dbe0fef142f2c6ab9bddb31.nq.gz
    ├── 4963ba1b294bb16c21431fe9e1819d1a8c0ef99f.nq.gz
    ├── 49a9fe1982d05394979ca9e1bfc29cec96890cab.nq.gz
    ├── 4c80f1bf329a9b1f9afcb7f8538e7d75b8cd0ba2.nq.gz
    ├── 4ca979edc45a7fc74611ebbc6534d2e3852aec01.nq.gz
    ├── 4dc45dfea9f03c866dedb876244cb33b57373b26.nq.gz
    ├── 4e829871d8366e23fa68183a10c44b5fee02105d.nq.gz
    ├── 4ea7146f6850ea5334229c146f01e1aa5e4b30a8.nq.gz
    ├── 4f4faaa9409ef1c4e38a19b1fc3609d703387686.nq.gz
    ├── 4f7ce6b6ce7b761862230045e07d450de04bfa31.nq.gz
    ├── 507836ed24f4a3c2cde0593ad6c36f1b4d6673e3.nq.gz
    ├── 507a2672abd06ddef0efd7d37dcd06e7f37fb749.nq.gz
    ├── 51cde420d0c07b022ea9d0945730ee66e0fdefbe.nq.gz
    ├── 540fdef8893beaccd9ed5707c07115601ebca82c.nq.gz
    ├── 5496c95ff284e9dd31e443f2090f50c45bd8d3c7.nq.gz
    ├── 549b20c2786697e03fb95d0d06b10654e317c4f3.nq.gz
    ├── 549cad2423284879a73498242c2f6363a80373c0.nq.gz
    ├── 55a41bcf2aacfc2196e52e2ede8a649a3475e239.nq.gz
    ├── 55c8e76a1885828d810189c3b06cf13d76ed1eed.nq.gz
    ├── 564f41b23b9f5dc0370d86969d7cfd0ce26ffca5.nq.gz
    ├── 566ffd6ccc1ff48feaddb20eedb5d50fa954e966.nq.gz
    ├── 56d9520a13481063f110038dac33b3d5e5b0fda0.nq.gz
    ├── 573990edd36a39143081525a61602dccfe17fdee.nq.gz
    ├── 577ef0b886e55b894373f17c57c6876a027730a6.nq.gz
    ├── 579145afd9a07d487856b94c3f1df32997b25cdf.nq.gz
    ├── 58945ca63fa4c93cd0d84f87eac174df7485a2e8.nq.gz
    ├── 58ace372622b3b911341a408c2c934944f0208be.nq.gz
    ├── 59b267d0979f73b1bed3c421fca844594b5a6846.nq.gz
    ├── 59cb72d1147d9a3093a0c353b19d06ca761628b4.nq.gz
    ├── 5a1ed2cf8f776ad166f264b2f2cac2c1108decad.nq.gz
    ├── 5a4cf379b5d44c2f26572f212ff012dff11c0d20.nq.gz
    ├── 5a60b000f3ccc6dc2521939f5f5d1db315c69ce1.nq.gz
    ├── 5b9b14d75a9d6375e77403ba602f20fa3ca123b5.nq.gz
    ├── 5d1c319adbf9303cb6ec3fef10b46cc6a6e71e28.nq.gz
    ├── 5e1517c0f12d85e3ca73f489fef9dff9b0dcf52d.nq.gz
    ├── 5e632c19f455f4e90a65150a9ccf9d2f9cb14ee2.nq.gz
    ├── 5ea3aec46e59e785812c3e52d4948fb772bcb640.nq.gz
    ├── 5ed37a3040bb4d4b2250b8b8f69c665fceed505f.nq.gz
    ├── 600687d50d9de63f6d88aa0e4e91f4ab3fd35293.nq.gz
    ├── 6008d91340b0e26a2d4259b8d546184d0773df39.nq.gz
    ├── 613c0b7dcbd6f2496cbb8a3a3b97b01ca10123e1.nq.gz
    ├── 6199ae1917b0246e7c34dbaa701e71a988bd4a61.nq.gz
    └── 626ed644bc0201567f1f292a19d26d7d5c07695f.nq.gz

8 directories, 200 files
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

[anysphere/relay](https://github.com/anysphere/relay)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
