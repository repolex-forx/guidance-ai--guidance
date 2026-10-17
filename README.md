# Repolex Knowledge Graph of guidance-ai/guidance

RDF knowledge graph data for [guidance-ai/guidance](https://github.com/guidance-ai/guidance), parsed by [repolex](https://repolex.ai).

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
rlex download guidance-ai/guidance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 21b1d90dfbebff4b141df70c714c8af15aa5f4af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 21b1d90dfbebff4b141df70c714c8af15aa5f4af
│           └── chunk-001.nq.gz
└── blob
    ├── 04a14096d1d8ab275d6851f82ee4b42b0e07f665.nq.gz
    ├── 04e5878ed45456475aba853eed7332490ac0c618.nq.gz
    ├── 052823dff88053cde39f43cfc6105dc6c1a9b8cd.nq.gz
    ├── 05932b7a3de4337d187d95e4a46161c1849857de.nq.gz
    ├── 075746814e372a1a5727d1b7193db18824395274.nq.gz
    ├── 08dbf31adcae21f80bbbe4e0bd9f5906f3e113e4.nq.gz
    ├── 094c747ada000ad60cd527bec8d164585c400977.nq.gz
    ├── 0a618c3eef9be0ac923e4c13cf8aced01fedb83a.nq.gz
    ├── 0a61d63e9d96349df9cd0aad87657d001b8130db.nq.gz
    ├── 0b9e168acb5b7c3a45aa127dbd7d53393698dd6b.nq.gz
    ├── 0c8b38c271174946c4f7aea1c21007f908df7e4e.nq.gz
    ├── 0dd03c8b798248427a6a1d8f5be5a0b335d1f361.nq.gz
    ├── 0ebecc1eb8b3a60161980b8494d2bb2cf202411c.nq.gz
    ├── 0f8200c0efced7f5ecc27574fb807f116689f7f6.nq.gz
    ├── 13bdda084bc0a37562728c0327e0cab21d95c2ec.nq.gz
    ├── 163f74ebc366236245730e266aeb9fc10d84e6ef.nq.gz
    ├── 182c4ca09bcf934ea8f40b4253faeefa3ec1fee3.nq.gz
    ├── 18ef180b2f37c215dbab38607d719c4ae39745b7.nq.gz
    ├── 1969c433432c7fe0d9010f137d9d19a34ac8c6c5.nq.gz
    ├── 19db9c447c7bd75e5ee7ce44f5d9e0e6bc7830aa.nq.gz
    ├── 1b540382740538ae9721140fc459541fb8a5a9a5.nq.gz
    ├── 1c90862e22769a13c1711fa92525f8aa7295d5c3.nq.gz
    ├── 1f3fc4eef394682d6a84997a6328336f8193ff8f.nq.gz
    ├── 21e453f24dace7f5b35a8df2186ce0f0527be96b.nq.gz
    ├── 227886c4a7337d8ea2851758ae3d657735508a6d.nq.gz
    ├── 24024925f56d2f7bc0602587c7624dd34b10bd83.nq.gz
    ├── 246e7966d9774d0c88bd3d641a736e57e3fb298b.nq.gz
    ├── 24d51c36cb51851ace592f1f253fb5c32754cc7b.nq.gz
    ├── 258bb0f010ea5a1338ec4f11679f645f9fa7ccf3.nq.gz
    ├── 2653e55282b05a201629318c4f1dbb2396a32e18.nq.gz
    ├── 26b49d2fe1191124560a94fce2d171a7335c6283.nq.gz
    ├── 2905a8764000622eb3b0dfc0cc0f280aab5ed1b0.nq.gz
    ├── 292e8bf0e67b8ee9f1a234b57357d3778405a113.nq.gz
    ├── 2a22bcd921d7866a263a44081af0ef57d297e693.nq.gz
    ├── 2a8815981513cf379882ef42e9952ddb78a165b0.nq.gz
    ├── 2b51b8987c5ebdb86b8a385e868098a79b32e762.nq.gz
    ├── 2ced9c3269c78a76175ca17e8ff2cd54c4613536.nq.gz
    ├── 2d8ddbb40aa72f4327364820ea6370460a2c2224.nq.gz
    ├── 2e66c0a64be86c99a3acde248cd0f8bd1e6671b1.nq.gz
    ├── 2eafca456960425f89651ae07b84c19ddbd6afcb.nq.gz
    ├── 2ec707fcaca3cdb7291989a4765839861cd8f50f.nq.gz
    ├── 2f11e449886d6c5e6703d310f18c10a338c5ea68.nq.gz
    ├── 30e8044ffff55348f8af6176e1fe9dbeefc21aeb.nq.gz
    ├── 30efb972c6d22999080cba4c770d9ae506b047b2.nq.gz
    ├── 3186f3f0795ab612d5508593672dc9ad94bccca0.nq.gz
    ├── 325d9f2f3ff3281782a0f6bf3ed9fa9995b7fcd8.nq.gz
    ├── 32c0918f5b5e9235caca8208df13bc0a3cb95c09.nq.gz
    ├── 362c89b5a3a80e402bd8c0ce6d193ba1daf71fde.nq.gz
    ├── 3767870caa60cff5d6bab76ec2ee4ba17e210e0a.nq.gz
    ├── 3884180d7d46d38b86fbe8101a630e737dc1fd91.nq.gz
    ├── 399d77a4f4b7d296f53fd99f8da2092ecf2ee900.nq.gz
    ├── 39c17f14de11c9ef37dec72ae7f72d949ef6e64c.nq.gz
    ├── 3cb8b1ca25551f60e4a9faede20fc8cd067abf20.nq.gz
    ├── 3cd0cd3a608751c0465416f6e0684efd98a56d43.nq.gz
    ├── 3d520c641943f7de852cc3404e9363e88ebac09d.nq.gz
    ├── 3dafb34a033209b3f43918f49eacb4f04ab08b67.nq.gz
    ├── 3e624a96517b0b5ed8f6f3a5d1dd4c69dd7f2812.nq.gz
    ├── 3f66ed415253d865d0e750a9ae4dcf5e02b1da42.nq.gz
    ├── 408d0bb3976ddb1a356328a08d918ed462bfd209.nq.gz
    ├── 413f16721fbfa1873f7d60ce5a1b08be7868adb2.nq.gz
    ├── 42578e9d67c5c1249f88eea0e1d2aac6bd50ca45.nq.gz
    ├── 426d67588bd4298219b8e6aa13f6bf2e5dd2d59c.nq.gz
    ├── 43b00136817aad4d273c42c46c8b123017fd2351.nq.gz
    ├── 4404e982f83bdcc7740fb4d8d18406882e75bd67.nq.gz
    ├── 451b09085982c0ee1e39558928d3ce9cc1bcaba1.nq.gz
    ├── 46cbeb35a127c0b53e9fe7ac7bdfb4de87126e59.nq.gz
    ├── 4775920426654adad0446a46b2e16c229250e38c.nq.gz
    ├── 47c11528c3924397e090de6e0b185abd86b156d8.nq.gz
    ├── 48c380048736ed7ab65b999de37bb4ea7efcee7b.nq.gz
    ├── 490aba2a2ab1de92cf1f748164887649393befe0.nq.gz
    ├── 4b42775d9bd25532caff44b722efd188eaed9d4c.nq.gz
    ├── 4bf1eaf43523bb40a469c8727a67327b5de5bd9e.nq.gz
    ├── 4d0a1eb1ba41efebb38c06a725785824920d6abc.nq.gz
    ├── 4dd50613429bf975f45ca0bd88b6333dff175d6a.nq.gz
    ├── 4fc9e78ba62075719e718d460cfd2ea0c736dcfe.nq.gz
    ├── 508cbd6d011f07e4a678b5f7588823b1febddc40.nq.gz
    ├── 519035f3b0235fdd1d89caecdbded45b7142cb46.nq.gz
    ├── 51b78eb5dc2a98b5974077e8a4b5976cdad91eb1.nq.gz
    ├── 531179f9c7f5a06bd3ded1f844fd1af376339419.nq.gz
    ├── 5339dccb1057819524b06e849bdf801b4ed4dbc8.nq.gz
    ├── 53ea97a1b7c048b447a1bae2c4a4e934e067ef0f.nq.gz
    ├── 54d8a4a20a31ce90e248f87799865d51043ddb23.nq.gz
    ├── 55242d31750f94929735ab5cbb2b89ec809e7e09.nq.gz
    ├── 55f47c2c5ca5988f9492073bea9dcf06bd2ae939.nq.gz
    ├── 5612327e152ddc9ac6c0ea196db3aa8b791ffc51.nq.gz
    ├── 561e916169a5ca46058ce8a203a0eea155715dc6.nq.gz
    ├── 57bad7f446076d7079d5fe95aa37141e5c6c9572.nq.gz
    ├── 58271f0b90ba618407a68758ec7f221f6b5f3365.nq.gz
    ├── 5942d6f474062a9e0c94b6550a552c5e9bea17ff.nq.gz
    ├── 59866ade56abba7bdd38a625532016e40b6aa576.nq.gz
    ├── 5a18fd39f581cfd877ce54456d2bd353f9b64f9e.nq.gz
    ├── 5a63fb334e3cd527afd61fd0952f866b365a14c9.nq.gz
    ├── 5ac9827066b980219bb8a43790696e76c7912ea9.nq.gz
    ├── 5ba79e1eab3c1cd0f884d46d383dc79ff20383ec.nq.gz
    ├── 5bdbf95d47e29c4f0c7f2c9eee8e73dc3af2be8b.nq.gz
    ├── 5c7d815def4c6d3b38ec3212604d9b79a99a20ed.nq.gz
    ├── 5cb2bf38ac7e34869ec7785541e93243604b29f7.nq.gz
    ├── 5e425769a2b1514d790a29adf39d3ed9df861488.nq.gz
    ├── 5f73020b0e778ab5548b5efc6647c032fcca34f5.nq.gz
    ├── 609c25296d24c9b222ed8b1d9ceb3c8eedfd83b9.nq.gz
    ├── 610c038d8c44361a60c94296ece5c0566aa5ad00.nq.gz
    ├── 610e634b1bc82db883a54a6a7080e541b6a4bdce.nq.gz
    ├── 61493d6f8cd7e853586442ef13eab1b9ce7fcd02.nq.gz
    ├── 6329e99e415d1f94683b1f63817e28796302b90e.nq.gz
    ├── 6431de3d4fb3dcc31c3864ec01427385cdffddc5.nq.gz
    ├── 643bcda9a0d9015ee6896aa1ff44d665102c3d0e.nq.gz
    ├── 64e2466968221f1f9624d401564218dbb4a17701.nq.gz
    ├── 6548b2414d6de5e433328c98f6e218d0e6dc0540.nq.gz
    ├── 66b187faf78ac4bc4279e3f6780f9a84fd81a9f3.nq.gz
    ├── 670082b10e35028da7650ced3b0c17f7fe43e54b.nq.gz
    ├── 694d38d9047dcc13eaf6cae1ef79341a236d4998.nq.gz
    ├── 6975a4c8eb2e36a1a9ee95ef4a8450732d414772.nq.gz
    ├── 6aac721642d983c619df6455abf8b059aba81cae.nq.gz
    ├── 6b882bc4893191394e74a4b91e006215e0f25476.nq.gz
    ├── 6cf7d6863fbdbedc849a64c3a2545da31d0365aa.nq.gz
    ├── 6e6ce543b18602634eb87997b5884881efc1200c.nq.gz
    ├── 6eb125ee461282720efe7fb5ad1d4118dc3284e2.nq.gz
    ├── 6ee73110d0214708f60b1caa6b4c5a19e7c2bc46.nq.gz
    ├── 6f7986155b963377b4ccc9fc8e35604e6d7ae290.nq.gz
    ├── 6fe2f2a8d2757234a2c415866c28e30b577119c5.nq.gz
    ├── 737e3e680aae1ed3fc77d762142bcc975bcb6c61.nq.gz
    ├── 74120b9154f0af15a3973fa0e1f26446a3e1193d.nq.gz
    ├── 74177af8262386772cad237748597f1e55679219.nq.gz
    ├── 74d4706badad46cb73a0bac814df860d00234483.nq.gz
    ├── 75da8a020f6add7cd0963a072f0256322f9ef597.nq.gz
    ├── 76fd08da4f4a3e42870d886bcd2ab022011781ff.nq.gz
    ├── 78ff7a7d917c90088671daaf8a7d44b4b20478c6.nq.gz
    ├── 7936dc09092f5a02a4e228f4c6cd9a7d7240696d.nq.gz
    ├── 79453a3aecfcd81be6ad883b331fcf34e339269d.nq.gz
    ├── 79d581687264833d55afcf5eeb21c47a234c30c4.nq.gz
    ├── 7a3d79e8d72c7556923b83520986d7007c58dfed.nq.gz
    ├── 7a4b54a9a77df974e65672e618f2edfd08d28600.nq.gz
    ├── 7bd63dc1f84a675aac74c0b773311c4694a71712.nq.gz
    ├── 7c133044993b6052be06c82004a3efbcf6d3d609.nq.gz
    ├── 7d21d16bcf56af14bac4bfba1c0781b8d4b2faf9.nq.gz
    ├── 7db7818b2053bf2be07397422be1d6c66addc2c3.nq.gz
    ├── 7faa48c438fb5da4fe4599d2a8c83172d71d8f43.nq.gz
    ├── 8058ca05b52de1e67c5887aea0b564666cd30ace.nq.gz
    ├── 80ad8a61b2f734722aa03860b464b0f219494157.nq.gz
    ├── 83092ff726f1cbb720b0ce96a2d94f9d9fc55803.nq.gz
    ├── 844885332f485b0c0d7921b35dd99aa5ff65fa33.nq.gz
    ├── 846be30e5ef53cc4ef828441baecd843a4cab72b.nq.gz
    ├── 8499a4183f55d9923866f8b7e31944c39d553afe.nq.gz
    ├── 851bc25252d93f3847d6a9a14d40704e61d74008.nq.gz
    ├── 86e6f65defdc08e89d3471aa976e46c7ea5d5084.nq.gz
    ├── 86fbee4a81c8def7d91ad1b29cf24dc5c45352e7.nq.gz
    ├── 872a80f17624c5d82424525a18f3a59331d9703c.nq.gz
    ├── 883e471617fb4b552c86e6ed2c2d075b59705b80.nq.gz
    ├── 897ea2c42f910a4e61360968f607343305e6c3c6.nq.gz
    ├── 8a3933431819d23dfc40b1aec4ddfda2834b40c7.nq.gz
    ├── 8a4a28614eb523328a4088615cef3c94b27a185b.nq.gz
    ├── 8c0abf37e2d771495e399ab896aa27fade4a7a5a.nq.gz
    ├── 8e505954941d15296c627ab86e453766f41a7e79.nq.gz
    ├── 8f2243c1181ee71ea409d14244b8d325936a716e.nq.gz
    ├── 9051ba4988d9287d7a43eb4e3946a1214c111eac.nq.gz
    ├── 92232e3dd4102edef3aad57b1d7e18ec4d36c6d9.nq.gz
    ├── 929a01ecbc027b1ac9c97e54bd8be5ae57af50db.nq.gz
    ├── 931d2261be74e48409ce27d2643585cefd599284.nq.gz
    ├── 9437f6feb47bd3e8ea63afe32d3d1eb3a0138de9.nq.gz
    ├── 948aa7db67d9c697ab32c9dbda92eb6413b25564.nq.gz
    ├── 96eb344ecff10f55049a96fba2a0fbad90565f02.nq.gz
    ├── 96fd9f86b4f48fbac2db14286fb0d0789d2b0592.nq.gz
    ├── 97739947e5ee8c9f12fc530a2172ecbc65e3e1ad.nq.gz
    ├── 97865d512c07ee29644124154e0ca6d5366b29d0.nq.gz
    ├── 980aff6d217139f9bc8445f86bec201675bac545.nq.gz
    ├── 9a1d0f6cbe12b3617b20ce9e0f3ad3daf21bf2fa.nq.gz
    ├── 9a32d2c76c789f1990a350077ccfcd08f5eee1fb.nq.gz
    ├── 9b313a3b0119b1506c0198f7aac0d74d34b829fc.nq.gz
    ├── 9be8e68e12a2ce7d18ad58accf385b5304f6e054.nq.gz
    ├── 9be90f240d3b3ea84046bdb3e1704d3a7c059c95.nq.gz
    ├── 9c4aa7c43008a9148229b9eb4ed63ccab7083388.nq.gz
    ├── 9ded7f7ab80178eac3cddbd485105ae2ca746c52.nq.gz
    ├── 9f54953980eeffa2f82d0cf9ad46f0564574a9e8.nq.gz
    ├── 9fb27ea5baaf7d463e1fb93d746c4df3bae5e242.nq.gz
    ├── a010e5a14fa961428b0518e19f5f79016dd17425.nq.gz
    ├── a0b872d749f835433903c6ab494f0dd760a7d399.nq.gz
    ├── a2cc0f9d81d82e6b5411b9fd0a2e3ca10fedf9b9.nq.gz
    ├── a32164ec7b8c5e92e46270e518c886dff2d0e1a9.nq.gz
    ├── a38961629ce17fc7b94c9f84abac9f1af93f9b2f.nq.gz
    ├── a4a64e8f6764e83d8b65512a36ff0db42c2c260d.nq.gz
    ├── a58b7a552beb92b873216ec2f0241793187f9d6e.nq.gz
    ├── a627cd343edc6eabbb7cc9f83aa0d3e23f02101d.nq.gz
    ├── a6e122cd7cdbca4379ddfd3f6838a2b318f8bf2c.nq.gz
    ├── a8fbbb05937788f9b1c44131ccd51475a15a3499.nq.gz
    ├── aa46655c86ecedd8c7d8e47800e6727dfd11b589.nq.gz
    ├── aa8ed44c8eba354365d1c0683952284be065eac0.nq.gz
    ├── ab16bc37d006aebd116d2d444375717180311fa4.nq.gz
    ├── ab5a6ba84eacc131656935e5e492384ddd16760d.nq.gz
    ├── abccbb227ca4d23ea16fdf2c4d2839a442593bac.nq.gz
    ├── ac2bd94d7db162035f9761e606ef6de35c1372e7.nq.gz
    ├── ac9079c7766cabf63c64c6f53ef89ce7921eea2d.nq.gz
    ├── aca445f8f85c826cd3857f4268c867787187334b.nq.gz
    ├── ad0c35a666b1aaaa4f15b81a4da79569cc34eb76.nq.gz
    ├── ad0edd44f2396d7e34696000ad052789ef187536.nq.gz
    ├── ad409606b34c48594b24f916939c0f9365338409.nq.gz
    ├── ada926172428f7415cf53a0e562662e5f08a5ff3.nq.gz
    ├── ae4694d623696883055426a45097261560d15625.nq.gz
    └── ae991c08d802001f21d1c0b9c5a5311046367051.nq.gz

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

[guidance-ai/guidance](https://github.com/guidance-ai/guidance)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
