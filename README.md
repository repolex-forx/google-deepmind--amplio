# Repolex Knowledge Graph of google-deepmind/amplio

RDF knowledge graph data for [google-deepmind/amplio](https://github.com/google-deepmind/amplio), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/amplio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5476089b60703d2874d1536ab0123f6b4560d931
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5476089b60703d2874d1536ab0123f6b4560d931
│           └── chunk-001.nq.gz
└── blob
    ├── 00869cb9969e10b75cbab020d35646822a7ab91c.nq.gz
    ├── 00979d5d389156e9949e9d0bdf5cb64e3a7c3d38.nq.gz
    ├── 00af162731922f6f92f07b458dfd4b34974a53e1.nq.gz
    ├── 00dd069f14099c53e6f0a6d6cc619ee34a6a8550.nq.gz
    ├── 01caa6cb177643390f69e32340383fbd315fe646.nq.gz
    ├── 021b2f4b298b486adfe8761ebb129a216a885fdd.nq.gz
    ├── 0347ea9aa7003420d9d2a8dd6d0709d24e328a18.nq.gz
    ├── 0412b93d7c141b71dc23a354421ae723c7e98f9e.nq.gz
    ├── 0412e36e2558ab52d7c97a1d679656dd61a44e21.nq.gz
    ├── 0492a74def57e520d4d7477048ff3c26167b5d66.nq.gz
    ├── 0497cab0bc24732399b6f529787517d0c060695f.nq.gz
    ├── 04accb06ade968fa40118dd6f6df347f5bb06e8d.nq.gz
    ├── 051a1a4af08255405041b1e4dc728c1e46ace5dd.nq.gz
    ├── 05e935a8c8c2b44f6d344b11752259fe23976ec1.nq.gz
    ├── 0610e42a3b963db04d40bae0b9b16f32cb8bf76d.nq.gz
    ├── 0626ad4693368ff3fa2f83dd044cdb5d788a01da.nq.gz
    ├── 06b80593c86c3e3f541ff45c02111468b2516fa8.nq.gz
    ├── 0722187807455c92f903d4136ed864aab6fc6169.nq.gz
    ├── 0847ebe92ca95c3fa286541e98beb92ce6b29733.nq.gz
    ├── 090d2e0b367f771a0098806a7392dfd092cb4ba0.nq.gz
    ├── 097009428cc6e541d0d31afe3e0a24376bab8347.nq.gz
    ├── 0ab0951eaa5c2e44ab0f92961db69c2265846caf.nq.gz
    ├── 0acea8772661dd3492dd5735d39757cefbd08945.nq.gz
    ├── 0b58962ec910258a28a785a719e30fa65b33933a.nq.gz
    ├── 0c300f7bec7fd830768bd83014635152394a9d06.nq.gz
    ├── 0e4f982966d3483ebffe3e06f1c041ee897c1e75.nq.gz
    ├── 0eaca4abb4575d52259915451889075a583d496e.nq.gz
    ├── 0fb51a020725093ea99e972fdb9251556ccf76c8.nq.gz
    ├── 11073d814f368d315752641ab168e77a815aa600.nq.gz
    ├── 115fde2477e92fa70f18827d0ce1b5bddca11fcd.nq.gz
    ├── 11c7a8f1d7e5b8e10cce91dc90e60c2990cff15a.nq.gz
    ├── 12e47bb3d0a670d8abd35b8c21ac1a361e8159f8.nq.gz
    ├── 1306113147c3cac3fc1948cffdb2b87fce2bcf7e.nq.gz
    ├── 132b82848df2d51c3b9f275c5310e497c180d4ce.nq.gz
    ├── 138dcc5d5f8282c51d810fe7db4d3d290b04c4c0.nq.gz
    ├── 138e279699828f479fb4cd8dee29f04c6439edc3.nq.gz
    ├── 1466648c913cebba4242b5c596463b197dc93dae.nq.gz
    ├── 14787d9b11555f1c2bbc0f2429601423d253e6ee.nq.gz
    ├── 14db629bc2b9b6d9243845f9b8fdc4ba8a5323e3.nq.gz
    ├── 15857b55e44afb20124dfaea16635a2f528bb7bd.nq.gz
    ├── 15a5464988689f85f24b880e6cf9306e93491215.nq.gz
    ├── 17cdd18bc8f23795281a2f797dcfde89a8fe2432.nq.gz
    ├── 1990ab77ed7b90c23fdd22a7035a3241b6d7a47c.nq.gz
    ├── 1992966da97996b4990af56a5a915c62f16f8328.nq.gz
    ├── 1aa02d27ab447f8bd9db455439426d7672106c09.nq.gz
    ├── 1b67986076b5ca09ae79b6d27e9ac01ad0e300b4.nq.gz
    ├── 1b87eb9831f9ebaa74ce72297ff8c749b529ff90.nq.gz
    ├── 1bedf399a3ec91339597f56c2b374148b320b9bd.nq.gz
    ├── 1cc3671db511dffe13e142dfefba2230721ab860.nq.gz
    ├── 1cd02806a7d0292694cca00069e8d9acc3c7343c.nq.gz
    ├── 1d68a00ce4d76feaf02cb8285b6c7cb05ce53e34.nq.gz
    ├── 1e04c0d2cbd88d8df1e1343826e64e523f3fa26e.nq.gz
    ├── 1f30cdc1e245afdfe545c781ccf7ce324b2d2bba.nq.gz
    ├── 1f5aed9f8f6e0bdc15fe94c32731abd7886abf1c.nq.gz
    ├── 1fa1664ae37c97a4813706926cd49564c98161da.nq.gz
    ├── 1fcf3f1ff644e9da972bd3c1afda2220a2f8dc45.nq.gz
    ├── 21632765690528596dad5eb4ce64e86823d167f1.nq.gz
    ├── 21be9222d12afd787a4a3f3898310796b5190bb0.nq.gz
    ├── 22ec5be9127c22c0b934d48afaea4692df43473f.nq.gz
    ├── 2309738f545ce0ae567b88315326a55133ce959b.nq.gz
    ├── 2347a37bc3185cf6c531180fdbcb6744aab2bf0d.nq.gz
    ├── 240485da81da72e28e183269bae8fccafee6363b.nq.gz
    ├── 241024b578a5815ec18b0ee221c811d2c5740ce8.nq.gz
    ├── 243454314d65f77a13dbe05bc750a7a9026b02a5.nq.gz
    ├── 245451edd6ee9ed719151a1151246733e0f28302.nq.gz
    ├── 2545a3b0032261a938ca2b7633cb12d100281ffa.nq.gz
    ├── 25bfa1d35bef617ec8efb289f1b416311e80398a.nq.gz
    ├── 26dfda271263a2a624e53d56a451e23bd6ae9c06.nq.gz
    ├── 2712d1dfa4b7a683063073436c13d65fbf15e9c7.nq.gz
    ├── 2779dd63257c59d3bbe227617d28ae0f3202d49f.nq.gz
    ├── 278c08515b4291ad3ebfa1a416efd24b0f0f072c.nq.gz
    ├── 286a4482151340377b575596bdf9226de42c4369.nq.gz
    ├── 28c920cd4b7b609d1db7ab68dfcae7102db9ea4c.nq.gz
    ├── 29419bb4f211caa2706041f43936dfa89496176c.nq.gz
    ├── 2a303f1eb401fa113f9af0a3badbd1d1842dda93.nq.gz
    ├── 2aa9750c498267a22e9651a73c42703ef6364780.nq.gz
    ├── 2ae16d3d2ee9a417c4b54ccb572995d929147e25.nq.gz
    ├── 2b20cb62da69dad5551168ce06212013506bdc42.nq.gz
    ├── 2b7188d6298a0f98790e69bbb921f4cbbdd674d3.nq.gz
    ├── 2c1c101576646ee32137e4fad8df1f859906c51e.nq.gz
    ├── 2ce74f71ad8795ca6b593a7bf47e837b9c1e5a1b.nq.gz
    ├── 2dba85aa4792915abffb9b982696ae030446a960.nq.gz
    ├── 2e5b2a09c66ed18cd68c606dcc9bea90975a47af.nq.gz
    ├── 2ea9836ccc8e084e67e706294fe2ac27400658bb.nq.gz
    ├── 2f14c3690edc811cb43f408844d3c9b201da8e75.nq.gz
    ├── 2f6571999afc2d0234f27a5bb339cf4753f049ff.nq.gz
    ├── 2fbb34be40820df97fdb478bf6dcb2dec412588d.nq.gz
    ├── 300f5b82a296898c245ecc1a3e2b7ef4ab610bc4.nq.gz
    ├── 32121eeffc5ebc2548f215704607c7addd2bf4fb.nq.gz
    ├── 324713a4d63055afc9a5fc82077acdf55ca3f7e6.nq.gz
    ├── 32bb32f710ba05328df3e4c9aeef79c58b702b92.nq.gz
    ├── 33cbb8e331894bd7a42201839402e4bc312ab689.nq.gz
    ├── 34ecf3f4f709051591e39f0ea9cb9c7172d618e1.nq.gz
    ├── 351161f696d24c07bff375a280791b2fff3aff59.nq.gz
    ├── 351e61a5f9babda5dbeb7b1a31d5099628494b5e.nq.gz
    ├── 3525e896bf3e46acc50472dee06d1f39ba2b9c69.nq.gz
    ├── 354c2fd5aae40e05251a392d7d06e63ffbba8cc0.nq.gz
    ├── 3571698be97b5468ae989810611a9cfdc87383af.nq.gz
    ├── 3591983953d3a76f8983f2ee1f1d8120161180a1.nq.gz
    ├── 35a713e07cc0a57cf749ec50d630a9b3c150d816.nq.gz
    ├── 367cd531b5e7b84c818e29bf46f3be398e46ac28.nq.gz
    ├── 36872517da123e22ed48d8213a366ec536470518.nq.gz
    ├── 36d543533d59fd9430a1f7050acdf24a15773fed.nq.gz
    ├── 36dd2d41cd51746dc3093bf97b8fcba4d39cb8a6.nq.gz
    ├── 370e4fff77f045db5313e6850c36c91d9fdc548d.nq.gz
    ├── 38f290611c4b0b789dc7ce700c25ed20475c7da3.nq.gz
    ├── 38fcaac3fbab69358bbc0b67a7fdcb9f350dae42.nq.gz
    ├── 3b462cb0c4158547145078184d816bdcf314eaba.nq.gz
    ├── 3bb0108ef1c6f76707da6e23ab6e59bba8f7327f.nq.gz
    ├── 3bbf821b0e05e2aca40963ebebf0380483252942.nq.gz
    ├── 3bc0f478b51caa8e49b9205ebe4e7fa9beab288d.nq.gz
    ├── 3e8f7070549b08ab6f9356d5248d62281892eda3.nq.gz
    ├── 3e93e849d83686f52d905b351db2335bed59fe15.nq.gz
    ├── 3e96812e0e6984b403ecda4a35d8d376f99c4c66.nq.gz
    ├── 3e98f3b01bc34c722a9752aaf2e9b197dd7d6b7b.nq.gz
    ├── 3ecd6584c4a058a819ee54081caf38abb57c323b.nq.gz
    ├── 3f443d5d92909c6417152584f117cfa1c8cc6885.nq.gz
    ├── 40a3b3fb3929a4886ac41a1bbac124c987648248.nq.gz
    ├── 40f63be6dce5ebf53ef509682cbe89ef111e9dfd.nq.gz
    ├── 41769505dc9917fe1d1b3bad5e9f1c5e3bdae811.nq.gz
    ├── 41bb1b22ba3664c4d11c4784c77dc63230ce7373.nq.gz
    ├── 4278cb98f42838b0c1178a44e3b0d2b9cceb33dd.nq.gz
    ├── 42ae6069a78fbc7c2a5094860793baed3c76a3d7.nq.gz
    ├── 434ba2d9eff85b76b1145b8b10400eddb44707af.nq.gz
    ├── 441ebb8f41a4f53a5c840150cdc62d56cf608ebd.nq.gz
    ├── 446773256262a7c0072f5d6549831413e350ce42.nq.gz
    ├── 46389f9c9923e8ff8b3c8cf9b09696497a228c6f.nq.gz
    ├── 470400c05791fc4270e98c311097066523cc2e00.nq.gz
    ├── 4871e6c0d0a2ed4842dc70709c493ebdfd5dd95a.nq.gz
    ├── 48d6dd0005a67d49e4315e6f43e0aa41812d1b32.nq.gz
    ├── 4906303e24a00c32ceda376fefab236e9adf5791.nq.gz
    ├── 4a32d5cd35e24c647648de4996425c763f0c567d.nq.gz
    ├── 4a65c2a19f477eb27c0856bb675b3a03c52bbcb1.nq.gz
    ├── 4a66e4c4c86fa2bc28f2a0fbdbb2b8d2d50586ba.nq.gz
    ├── 4b1ae43d4ed9793963ab05069299f94d3767bb32.nq.gz
    ├── 4b7f7d8e2e729b13dca08f2b529f58b61b6d047c.nq.gz
    ├── 4d8ae61d7bacc165b6e332b4357be3be9d681f01.nq.gz
    ├── 4e48945e3adcfb405ea7fe795b7e667cf0ed4489.nq.gz
    ├── 4f2573398cf8194936508dda03904c9482c466f5.nq.gz
    ├── 5047f52bda4021d1a04448c6fb9b2446e40f85aa.nq.gz
    ├── 507cba4e0e7d3650baa2d12461c832a96b8821e5.nq.gz
    ├── 50b432268d7cb5adcbc443b228a0b7cc9e9ff9f6.nq.gz
    ├── 50da36addfaa6a51d65d5ee56aa159356c3cf1e9.nq.gz
    ├── 5160ca5736450f0746f5ae2151c56ee7e39a30bf.nq.gz
    ├── 51c9caf5564b5ab21562389c8877e42d215ebcf6.nq.gz
    ├── 51cfa517817f38cd8e4137b906bfd351ac880b9c.nq.gz
    ├── 51e6fb5c3a1b89ac4cc3086cb55d2be258403d7b.nq.gz
    ├── 522b6a00354ee30109820d00b7deaf86fca23a1b.nq.gz
    ├── 529b75943d175e2c2ec2e4cb0af1fe0fb44d73bc.nq.gz
    ├── 52de1e0a78d355b10405ca6fa7de4db98cf1250e.nq.gz
    ├── 52e4f9b2453636dcf46058a8e5a126ebdf63ad3d.nq.gz
    ├── 5334a26014b6ac8290455208f25bd0b1c8925614.nq.gz
    ├── 54f10cc9a7cdc41212a964325039c1ae523b5c27.nq.gz
    ├── 555abff54e33074aea8eed443a414b1b38684f43.nq.gz
    ├── 57f5b6075257d650aa75eb2980a5900b14f12d97.nq.gz
    ├── 59a2c70a8789ac27c676c36e27af06c47d7f0cf6.nq.gz
    ├── 5a60090cdf08f37d150ceb9805dd1e3497855201.nq.gz
    ├── 5b73da97c86dc46bdb92963585ab775b3d84c43a.nq.gz
    ├── 5d65a1e29cd26de1833ffe36960bc29ae3862cbc.nq.gz
    ├── 5e46d0fda4d8d8bf51aaa50cc8f856168eb17de6.nq.gz
    ├── 5e4eecb993b7ee6935fbcf621d86b228ee55e14a.nq.gz
    ├── 5e72186fcb244d0f92496d844b8501aae6c821ef.nq.gz
    ├── 5e8507b4266a2e8d622a92a0cd5ddde6873014e9.nq.gz
    ├── 5f3913bdf2f2182f172113e5ef542714eaa1240b.nq.gz
    ├── 5f5cade6692a9d0f1d12873ab46d102754535e7a.nq.gz
    ├── 5fb7302ba442d80a8248818a7ee3c49edabdb2cb.nq.gz
    ├── 6153311e72473960402334bff18e217143254cf2.nq.gz
    ├── 616106a0c09426fcce7a3964a0f0a31f16655dbb.nq.gz
    ├── 617ead0bb6489bf775e9ead91b7099e432810e30.nq.gz
    ├── 618147da952a9c1a2df4994bee7ede5bc2706ffe.nq.gz
    ├── 62b7081d45151820821e16180dc0d2a44d116f9d.nq.gz
    ├── 636fd61ab6448344738768f0200edad174ee732f.nq.gz
    ├── 63a1f17c9bf286b01ab8dade18249cf7b8620e0f.nq.gz
    ├── 63cac914c8ce58935df6e242c50c127b0b4a3c2e.nq.gz
    ├── 649c29cbd5972552ddd4fe21d4d0d68f4f12ec8c.nq.gz
    ├── 6519f9c54d97e86aacc9a64d85bddc104c892525.nq.gz
    ├── 654c00b1e22eceb3f370be8d80c4cb2fd8b12202.nq.gz
    ├── 6618ba0c78d94563ef45524143d7c2526b504fb6.nq.gz
    ├── 663c2313747ca9d1637579bfa3bef0b96657cc9f.nq.gz
    ├── 676f6c0ccb4cc9dad44fa483f0056c9bcf94fd81.nq.gz
    ├── 67aad211f56916c41b70ffe78048157a05f56288.nq.gz
    ├── 67ae29eb5b0bd82ee73671aa586c160df6a65162.nq.gz
    ├── 68455ad3152ef5102addedc69c91e5f1da66ba57.nq.gz
    ├── 685236cbbc8a3e076b19d806d52db6edc8d3edb7.nq.gz
    ├── 688258062019f1a198ab98689cc2345a85c709a8.nq.gz
    ├── 68a7b755517b5280e3897afa9f265f80dbe16439.nq.gz
    ├── 6909213914ecf23c523595e35ba3fa6258823df7.nq.gz
    ├── 69c125ff6f473f97bda195a6f8199bc6d55a1335.nq.gz
    ├── 69db1beb5e688ac9fd50d602a0fc3a8dbf29d6d7.nq.gz
    ├── 6b146924b4b5344db7d11b9cb252f0ffff486191.nq.gz
    ├── 6c06087e86b9903af367253668a85a44a14203e9.nq.gz
    ├── 6c24b19fdecac053fdcc93635012950413e0b67d.nq.gz
    ├── 6cc55c50e569b99244806debb911c558cf3e21d3.nq.gz
    ├── 6d66d0e2d0779d98312d7ce0186c2ef4933785d3.nq.gz
    ├── 6d7f85ae1f3c638a0b9efbf6900eb18e2425f5ae.nq.gz
    ├── 6db3e08b2d3a551a7063852417c86d11655fa23f.nq.gz
    ├── 6ed6f1a67925a0c2e2ef681ba5b31aae2b1dcc11.nq.gz
    └── 707b6fe4d2e2aa9f6eda08711eb813b0416f0c20.nq.gz

7 directories, 200 files
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

[google-deepmind/amplio](https://github.com/google-deepmind/amplio)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
