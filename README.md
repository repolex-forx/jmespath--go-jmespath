# Repolex Knowledge Graph of jmespath/go-jmespath

RDF knowledge graph data for [jmespath/go-jmespath](https://github.com/jmespath/go-jmespath), parsed by [repolex](https://repolex.ai).

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
rlex download jmespath/go-jmespath
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0104c826a24d7c202da8e1dbfb9ea4cfa35d774
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0104c826a24d7c202da8e1dbfb9ea4cfa35d774
│           └── chunk-001.nq.gz
└── blob
    ├── 0073fac4520daf550ecbcd11dbedcfa1e06f6cf0.nq.gz
    ├── 010efe9bfba366f10c4670111b56ff4b0b07c563.nq.gz
    ├── 01cee572bbdfe3cb6f7a4b78aea0509a3d5de12d.nq.gz
    ├── 027177272c5ac9662ab0d6d3c531d54798e1418b.nq.gz
    ├── 02a26491ae4e10011abd42379d44d93cf14f1052.nq.gz
    ├── 03e0c0cb93b3abd1eefdb4dab4155eb77f5230ba.nq.gz
    ├── 047041273f085e94df7ed2b273227d1c2070677b.nq.gz
    ├── 04e9b3ade60f61cf6dcaf09237eed553199ed2ee.nq.gz
    ├── 0561bc26d9a0c883f853c0f7c8bd857eedae4b22.nq.gz
    ├── 0573cfd73fdf1d0ae1dc07fba5f3d826c1feaada.nq.gz
    ├── 06253112e4e7bb70ebc821b28510427ecdb821f5.nq.gz
    ├── 0637a088a01e8ddab3bf3fa98dbe804cbde1a0dc.nq.gz
    ├── 065295bc17ac1be474f2c9725d0560af61f247de.nq.gz
    ├── 066b8d98b78fdce8466bf50c89696557db44b0b8.nq.gz
    ├── 0761ee16dc01ffd2b200dddf4c1c6a803ec427c2.nq.gz
    ├── 078dcee8bc6405849fcbf10cb6f805e12d0ab472.nq.gz
    ├── 07fb57234b8cd2f4a93aff9858a0cb69eb7c9095.nq.gz
    ├── 080e5bb05eba3bbeead140c27618ee0c1854ff72.nq.gz
    ├── 081e93abd98051da48ee1d7c72e103d791cb98a7.nq.gz
    ├── 0852fcc78954ac789a6a037a3df3afd8046e4585.nq.gz
    ├── 08731af69083d1559968a32c0bf07da5283eae03.nq.gz
    ├── 08ab2e1c4205c6306088dd011f263fa839a695f1.nq.gz
    ├── 08b944dad4a76be13f3a4f2620b09d573e955af0.nq.gz
    ├── 08f262b2ce665753589e29c9ed6aa2307bd07b4e.nq.gz
    ├── 08ff0d95ec07f03724da1bc89e46b298c6f0bbe4.nq.gz
    ├── 0918d41559bc9a2132652b738c4eb22110beb952.nq.gz
    ├── 094c0377b5700e0beff7311ce682bc114e3a049b.nq.gz
    ├── 0971c37eaf77c57daae4f9bacd683c156953443d.nq.gz
    ├── 099b20fa72222dd6c024ae02c27774f135f93af6.nq.gz
    ├── 0a25bc68212a831098bf32cbc1d2d096bd6254e5.nq.gz
    ├── 0b24ef53526e3563b5cc722f4fb16916852bd97a.nq.gz
    ├── 0de3229b83e91bc417da8d375d8b7e6eefaeb7ec.nq.gz
    ├── 0e39dfd695d68717ecbc7213ba0e6964739bd320.nq.gz
    ├── 0eccba1d3a0edde13104ddeae6786c486e816063.nq.gz
    ├── 100fa8339d52f58deb265469579ec2cba8d867d9.nq.gz
    ├── 10ed5d3f61f6957076f29cd12aa7403bfd2f80fb.nq.gz
    ├── 116b50ab38b47c4fd245dbe7c22643d556ca937d.nq.gz
    ├── 11e1229d9e3202067641495cee19f663065eec87.nq.gz
    ├── 12330d9902c8a4b0312b58b16d40a04cb93aab8f.nq.gz
    ├── 131f27f705fe852a0b0299fff1cffedcbd7b055e.nq.gz
    ├── 133a9c6272f9b3db368d20986aacf12f76a40590.nq.gz
    ├── 13c74604c2c8eec42d46d439da89d7cb1b7270b9.nq.gz
    ├── 1406be5721fb09e5eabae87688d889fba6b4ad1d.nq.gz
    ├── 15a486ca6e2466011a3b72d3ad8e93ca409ac4b8.nq.gz
    ├── 15f70f7839944cd6eb8a0138d754696657b1aff2.nq.gz
    ├── 16000c003cd4ce05349c4eb9d17b9fb55ee8ad11.nq.gz
    ├── 1661747c04ddafeb37dca5fec2348b95ff8d0b3b.nq.gz
    ├── 18b90446cc918c8a7aed8f3a56c7fd567b248e64.nq.gz
    ├── 18c5daf7bea9a4648d4cfb3eb48f5a0896df735e.nq.gz
    ├── 19102815663d23f8b75a47e7a01965dcdc96468c.nq.gz
    ├── 1921a3d9865c0fd8f4ae634c8fb7851663dca590.nq.gz
    ├── 19c2e2ef41c35dfcfeb5337b27cb5a9086aec247.nq.gz
    ├── 1a27fd80c3c3887e370d0e5366936faacdfc28e9.nq.gz
    ├── 1ab2d9834f800e3678033634a1788ee831d9d6cd.nq.gz
    ├── 1bb84f7d4bd02cef9cae42683b024258708352a3.nq.gz
    ├── 1c1b88eb58872b74ba60ba626c2da60540ad5817.nq.gz
    ├── 1c6fd67198e896cb93822405441d63a34f953e89.nq.gz
    ├── 1d0d03ed3b5e7e800d9898836a057ec14ccfdec7.nq.gz
    ├── 1d19714ffbc272ba0da6eb419d66123c20527174.nq.gz
    ├── 1dcb2338c4c4627f67b6a981a6fd38a76833b20c.nq.gz
    ├── 1e4a3a34155da3ac56a76448434f43f67c37eae0.nq.gz
    ├── 1e7b886e79eb258dd28ec15a29596749e9d62eea.nq.gz
    ├── 1ec43f45fce67a744213c6895b763d4d4914b4de.nq.gz
    ├── 1ec65fa2dfa65318e32c23cc14ab2300c75b6c2a.nq.gz
    ├── 1fe14258edcf2148fb62ee4291b751b9610462ef.nq.gz
    ├── 2024b6f118d70e0296d765367bc73f739cc504d8.nq.gz
    ├── 2080401e1eae1aa648cc282b779d9f604c82f93d.nq.gz
    ├── 20dd081e0e40687203db4bdea1a3136a63c1d89d.nq.gz
    ├── 214917ac068e90aad391fadd8ebbf4be7818001c.nq.gz
    ├── 2294fc54d126faf80d2f382957df117026dde3fc.nq.gz
    ├── 23480cff14c95013ccb3e0073ff66b443f9bd3e5.nq.gz
    ├── 23d27073e9794c024a532ec68946789b4f8a1230.nq.gz
    ├── 2438b25762d1fad448cea9f0efc15210f057188b.nq.gz
    ├── 24ecc222cbfae45f7a3b6498f097438398a0eb24.nq.gz
    ├── 265a6b0f94439f015c0830a189c76d6115d16553.nq.gz
    ├── 26bf7e122de50db472b26068ffee34fcd8e081cc.nq.gz
    ├── 28b9bcbbb52fd88535d350e7cdab4c0da4a784bb.nq.gz
    ├── 29497f4ff5436cf21404b6627dc458dc03303c6d.nq.gz
    ├── 29e1fb20a55b1ff9916e4c2780d7e6b0cee22a5d.nq.gz
    ├── 2a3b993af24e631e87e0f99b82a39aaf7c6906ac.nq.gz
    ├── 2aa159718c84bc52c14d78a95b907b032b3a7a7a.nq.gz
    ├── 2b705185ba784ae2b5f2864dc7fc6681190c752c.nq.gz
    ├── 2c7fa0a9c1ecd32c78aaa2b42c41f63068f6f0c3.nq.gz
    ├── 2cd6618d84ba0f939301bcdffda5fe91c9471304.nq.gz
    ├── 2d4a4454ef50bf34b538568f38ecd5d5f2641ea9.nq.gz
    ├── 2d53bd7cdcdac7f5e662025ed94e9c5b98400ec0.nq.gz
    ├── 2da77934496ef39b1b9a52bb7835d19ec1d71a52.nq.gz
    ├── 2dd54dc390425affec377c910213ffa896c2fcb0.nq.gz
    ├── 2dd8ae218552d41e371cd7076107e50c3fed9cd7.nq.gz
    ├── 30387116349991bcecfe1169cc4d46fb9a00d0e7.nq.gz
    ├── 307f2afd26ea46b2094c64a14813c936abfed88b.nq.gz
    ├── 320558b0053696730bff6642c8f95b348aa1baeb.nq.gz
    ├── 32e16b7bb002d5a3510511fecfd796c554e33e19.nq.gz
    ├── 32ebae8800b7609d095d66305dadfc27006f2639.nq.gz
    ├── 33ac9fba6ff906610f30720499e03fcba23919d7.nq.gz
    ├── 346696563f885134d5aead5eb4458dbf984995e8.nq.gz
    ├── 34bdf7123bf1e6a8fa3cee9443647f8b4b02c5c9.nq.gz
    ├── 3535da2eca6890c62c867db1ec79be942fefdd4e.nq.gz
    ├── 3582a4ee49a717e5febcf682e1ed72d66225a15b.nq.gz
    ├── 35a643ea2139bce978da5c321905a6abf73fab0d.nq.gz
    ├── 36b63e462c4c36c822c6eac85884e9585ce77573.nq.gz
    ├── 37961f6ca424df44b324c994c5a7d53984c0930c.nq.gz
    ├── 37da9fc0b7144fe13b816f8c64d3f6adae49021f.nq.gz
    ├── 398c7f8b06ec648c764d5ade66f3472860b83e87.nq.gz
    ├── 3a65aa7d6f1fdb70a90cce9717303039027e7662.nq.gz
    ├── 3ab0290340ae2769d1e00c04a91efee7e10cc955.nq.gz
    ├── 3b511f13351d197d4dc53731309a2d17762ec3e8.nq.gz
    ├── 3b76c9f64a4158f6e7ffefd3ae11053d4b735036.nq.gz
    ├── 3c1e81f55ae4a96073e3ec74006b3803ef11409a.nq.gz
    ├── 3c835642eb24d73f0d5e3fdfa9fd25a17fa36933.nq.gz
    ├── 3cd7e9460fe574132a2df3926ade98f9bf509895.nq.gz
    ├── 3cee2f56f15799ada0fb46daf6881ee366258827.nq.gz
    ├── 3d15fcc1697897a07e120e03e9d3049b92493e46.nq.gz
    ├── 3debc70f895f64af1ee2d970b8144131f1e51eec.nq.gz
    ├── 3e6dcf3045a208df8ac97b2d7276b1c9e1ce29af.nq.gz
    ├── 3e83c6f730630d77398d359f799bd9841b671626.nq.gz
    ├── 3eb869f435b644c8687a04b266a002385d192e9a.nq.gz
    ├── 3edf5ea1633602688fa522f7c269c8beeba65bed.nq.gz
    ├── 3f13757a10c9b2e95a61ed5a5cd5187d5917498b.nq.gz
    ├── 3f2e5d329fe8acf2e6d5253e670e39a76e244578.nq.gz
    ├── 3f3048a004c2f393dcb385ca069f6e9e7a76004f.nq.gz
    ├── 3fc73fea7633486b3dd0a2212efdf33ab618b75f.nq.gz
    ├── 40b6913a6c0eb9fd24a6092f78a68c208a46eadf.nq.gz
    ├── 416127425c2dee2a19dff501cb837259ca4c2c6e.nq.gz
    ├── 41d2c1dc8adc53fe1a824c9d985a7f06562297ab.nq.gz
    ├── 41ebe5ba9d7b0d671c319c9ad1d1e1deb7004e04.nq.gz
    ├── 420b1a57c450d84eb49d246901f25f1fee353d7b.nq.gz
    ├── 4234ac019228ffbea3214b86b75a1347aadda3ba.nq.gz
    ├── 423a7b02740b40219d299d8d7c8438be38350536.nq.gz
    ├── 42500a368cc68de4a3bce0da1d42ce5c0c4b4dca.nq.gz
    ├── 433a737d65eaf67d1d8265a4ab6cf68c61a3ea1b.nq.gz
    ├── 43d164927d43d35c6a0e740aa57c9bf7cb226b93.nq.gz
    ├── 44ba735ab10f75e8e1069ae1125c93c3c3d1201c.nq.gz
    ├── 455f00ffc29b77345e7b6773f9c8275212f684ea.nq.gz
    ├── 458d0a6ddd090b6aaf4d92c0bb3d97295004cb5f.nq.gz
    ├── 463a2a542db53ce112acda35ee2b77e6181413d0.nq.gz
    ├── 47152dddb730d8fda9932e3b92951f9e6d67289a.nq.gz
    ├── 473c1c351b4c2ba70d01db8da8c5426cbe389aa4.nq.gz
    ├── 4803734b09eed269ad32a18dcd191d3a0fe7f13a.nq.gz
    ├── 4821f9aefcf1e6a5d355c07d2de5438b7895c8a4.nq.gz
    ├── 483e97714f3da543215df80c76d09110744d204e.nq.gz
    ├── 489a42935a68bcb51a6097ee8e8ececf76b63516.nq.gz
    ├── 48e4a7707c740d4f555f56511c04538dae992882.nq.gz
    ├── 493daa673c4fdcd739fa3c47fd6f698bef26bcfb.nq.gz
    ├── 495114d919e5e6d7e65b507af0faa2585a54eb88.nq.gz
    ├── 4958abaec45b3f8759fb7c1a5b00253344f0740a.nq.gz
    ├── 49c5269b12edc54f5923d7aff692c1594c493e41.nq.gz
    ├── 49d9c63a3901feebb2cf7b83bd4ee31898443475.nq.gz
    ├── 4a8a3cff369eb8383dd71061369030b9042b728c.nq.gz
    ├── 4aad20ae69e0d404c825d10ba0c839ff64b37d91.nq.gz
    ├── 4abc303ab4a99a4d5fca6c0f89999e061e21a406.nq.gz
    ├── 4b8f39a468e4442ca77535dcda01cb0ed0b5844b.nq.gz
    ├── 4c002ed80d69a7a8f766d702b6ebbc1930e1743f.nq.gz
    ├── 4c357818919ced32aa09636fc474cd977a38c70f.nq.gz
    ├── 4ca810c50f98ec22b385cf6f41a7d82d5918712f.nq.gz
    ├── 4d448e88b0674aa8c14505fe532deda0062be554.nq.gz
    ├── 4d5f9756e551b47a44c4d38a569390ae07001710.nq.gz
    ├── 4dd897a8afdbf27a50b8cd341bebe2cf987524bd.nq.gz
    ├── 4f1d882a406a0d51c061b200b830367e04802c2a.nq.gz
    ├── 4f58e0e7bd24ef4505264435963864644c098331.nq.gz
    ├── 4f6a6c7a705adabf3d2f697fb2c5299e0e7e38fa.nq.gz
    ├── 4f8e6a17aab51c2bd4205d4dec3761648e8d5578.nq.gz
    ├── 503716b687c6a7b63c6321a732f9046968ca5cf9.nq.gz
    ├── 503f58da6e3018a53294704f05b2441574593552.nq.gz
    ├── 504ff5ae39f3af614e76369952f359dfe6498c87.nq.gz
    ├── 5091fb0736c86b847b768faf85c68c139fbe19fe.nq.gz
    ├── 5197e3a2bf56ae4f92b1b052547988eafe7b8b50.nq.gz
    ├── 5199b9f95d4c758ddf17c5e697657c587614bfbb.nq.gz
    ├── 533dd8e5460f05b1dbc32b91a3c94e296e974d8a.nq.gz
    ├── 54124df1d3bbed65addd5df5f9c57c4ea07d4253.nq.gz
    ├── 549994b6bc4aadfa3838506fbb234e1be2f5c9e7.nq.gz
    ├── 54cc2356eee93f91a3e0de5b2ea32650342d6ef1.nq.gz
    ├── 553b6d08073b189a1e76180c6dcc54635c5f2841.nq.gz
    ├── 554601ea4270c78130f643ad1308adbebd76ae43.nq.gz
    ├── 559a13456be1b2375233bd2f9428d5fb8b0bf9d7.nq.gz
    ├── 55e6257352f13cdc21a2ecb648a47067380c90e3.nq.gz
    ├── 56148d957b7d8ad98a820538d7de3d741342de7e.nq.gz
    ├── 56c384f7530569cf7eb3cb672ca2b6d431d1c505.nq.gz
    ├── 589a214f45351de45662beb300c9c444acda7e27.nq.gz
    ├── 5925a578b52a0f864e1136abb401cc59d3af2694.nq.gz
    ├── 5a373848c30a5aff9dd933513dd04820e13bf291.nq.gz
    ├── 5a5194647ade1f6185ffb8330d8cf1356164ce95.nq.gz
    ├── 5aacdb7cca624915c6d0770d5b92405d006e9fd1.nq.gz
    ├── 5b74e9b593f5cada0594ea320183e987322231c2.nq.gz
    ├── 5bb6d4ae7830122e9df20139c1938779ba481cbf.nq.gz
    ├── 5bc357d9fa6bd05a9a4ec8e002ced349c2cfb36e.nq.gz
    ├── 5c3d683565d98faceb723f0518c1e7f32d57ad25.nq.gz
    ├── 5d48e0205ce42799eb0c35c32b8f4603169e330e.nq.gz
    ├── 5f575ae7fc4c57be8700ba0a7befde545a799dbf.nq.gz
    ├── 5faa483b197d2ca6e012dcdd00e853788ce71cde.nq.gz
    ├── 600d2aa3f49f1fddd14c62d226236b3212485ab7.nq.gz
    ├── 60e5e3023e9ef8dc9dbad7fb4058243a8910ce2a.nq.gz
    ├── 61e5e1b8f716a7a90ddb4a1524eb1d2214d86269.nq.gz
    ├── 6232808f0aecee974399a98cb630fc66a287dcea.nq.gz
    ├── 62540bff045b8b3d3ddff4606d4530eb24d353bc.nq.gz
    ├── 62dd220e71979c764887073d8157a6409b88b29f.nq.gz
    ├── 634f937e555f6e9ec5fb58768224c5d62c70f7a6.nq.gz
    └── 64395761df69634fa5574698d17ea73aa28588e9.nq.gz

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

[jmespath/go-jmespath](https://github.com/jmespath/go-jmespath)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
