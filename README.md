# Repolex Knowledge Graph of ourownstory/neural_prophet

RDF knowledge graph data for [ourownstory/neural_prophet](https://github.com/ourownstory/neural_prophet), parsed by [repolex](https://repolex.ai).

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
rlex download ourownstory/neural_prophet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ac7d0f555d214fd63437b32141efb426548d400
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ac7d0f555d214fd63437b32141efb426548d400
│           └── chunk-001.nq.gz
└── blob
    ├── 002c6fdd8040c29c8631d0dc9369b13c46768e22.nq.gz
    ├── 00b1efc9ca94643f51addb31585cb59672ee5727.nq.gz
    ├── 00dd06375d9f9051c688cffb91d00e3e0140e369.nq.gz
    ├── 054079f566dabf18fb05c0a88f3c9e179a73ca7f.nq.gz
    ├── 0635ff0bcbb2773c729bfb64272c2740e8774f5b.nq.gz
    ├── 092b12e34db14362d2683ced9162703f74d3566e.nq.gz
    ├── 097b3f3bc7021f347de81b931921998e4d6191fc.nq.gz
    ├── 09a6c70dea278968a476a112a5dad2dcf5040533.nq.gz
    ├── 0ab9e6a5276d1bfa2b604fa94f1bde6b6fcd570d.nq.gz
    ├── 0abe17bd34e0c3dfbf553de619602e38d92fac5b.nq.gz
    ├── 0b90daf92f55b822563e27580734f7999fac08e2.nq.gz
    ├── 0fd002ee77f742b4735f113a18beb274b0ee3e01.nq.gz
    ├── 11183fcf3795edf35fc41fd0133afc3e120d9f36.nq.gz
    ├── 1118d9c091fd4c23401390a5eae276cb12c8502a.nq.gz
    ├── 1188fd51a1fecef15fb343017eec26611676a6f1.nq.gz
    ├── 11be7b4283f988fa595490f9b64c19e09089ea43.nq.gz
    ├── 12133afe57fef8d90bdbd26177d2672e1a0387ed.nq.gz
    ├── 124a43b8eb99b632d7324982fcb845e02800ee38.nq.gz
    ├── 12bd4908bf187ba8cb31298d2a4014d91c9454b1.nq.gz
    ├── 12bfb449021cd9905b0674ecbc33303226e64118.nq.gz
    ├── 15b9169aaa8eedc6125647f2d14055739f3863f9.nq.gz
    ├── 16ea2dc843f4859567d834c8fe28723327b6b37c.nq.gz
    ├── 196cbca2d1f7b92ce758100bffdc41acfb7ae29e.nq.gz
    ├── 1a43e605f90912fbc14aaf6c72b26d3a9dec76fd.nq.gz
    ├── 1bea8b6880a575074b50d04cfd4cba30887e4438.nq.gz
    ├── 1bfa1994e9bc51289cc86bac2d1ed682115fafde.nq.gz
    ├── 1c1c3a048d37cc2fe5f4338495c6a11185e791e3.nq.gz
    ├── 1ef5ccff0fb29cdba57ee6ad9d852c942432d4a9.nq.gz
    ├── 1fada83e46139f8261fb41635b849aab7a1a3b88.nq.gz
    ├── 23980e9f87faae90d8e4422b7589f34b28210b72.nq.gz
    ├── 247c97cbb5ea212327c510399ed24b4cd5d5b61c.nq.gz
    ├── 24ed8d95a47d4c9723ad437648e31c08f42fff34.nq.gz
    ├── 24fe85d1812377a0f70aab4b4d10b24d30c64e2c.nq.gz
    ├── 275fd8b69c2ba1e35b6d7fe8f6b69a0c2e8a37be.nq.gz
    ├── 2776c37e2a3d98871520f26b9d0cec28c3e5fbd2.nq.gz
    ├── 27e399b5681a43d25fe70be5818750184720994b.nq.gz
    ├── 28b678034543929ad5a80ce0cd57639429fcd3a3.nq.gz
    ├── 2a11616cee673a5d99a8e1fffd4b8db4f7fc9c71.nq.gz
    ├── 2a9a0c506e075232aed9f0e20dfc751231755095.nq.gz
    ├── 2b1ecf2de3d1bc6096b41a4e121f678d01880b63.nq.gz
    ├── 308355378ced4eed30e1d0160115217478d94325.nq.gz
    ├── 31d2b71095352eb1f2de674c258c5b695bee8027.nq.gz
    ├── 327acb4ba239829fdd22fef78b08c56e96d2c209.nq.gz
    ├── 329b649dfadb5fac6b951292b16c550116440f20.nq.gz
    ├── 368d742ed55ecb2c36932f44c868c98b8338a236.nq.gz
    ├── 38bd90157602dc61c85c579ba91d87d63a0d86b1.nq.gz
    ├── 3a73d1f67ceb828942fd8e4289157d8815434c67.nq.gz
    ├── 3b3c46f0089497b2c8ac6c8c150140fe1f3c832d.nq.gz
    ├── 3ce3348629df1b26fe8170161304bdd00154c44b.nq.gz
    ├── 3e9f7ee819bed12faebaeeb1fad88bcf9a3fd557.nq.gz
    ├── 3f395cc46868e7a7090079ddfa52504efb58b14c.nq.gz
    ├── 407d15dfbc35330c7a7aac1b5b25d65a20c775e8.nq.gz
    ├── 40cca52eeb1db806321f11985bd02efd3fda1263.nq.gz
    ├── 415f58581047b44e0226ffc788e75af848d811b7.nq.gz
    ├── 419654e17daa279d6b28aff328caf4c0231ca605.nq.gz
    ├── 428810e937e5753b4aebef268fc899270168c2ae.nq.gz
    ├── 429b28bafa018b501b109fe9da9b85d529d5129c.nq.gz
    ├── 45ff195c5f62a01ac36a53a0ee28f9f1d50f1c71.nq.gz
    ├── 4636be765f20645fcb607f6773836393e886db4a.nq.gz
    ├── 4754f905eb584c88026ee2e3a2d56248af8f9e20.nq.gz
    ├── 475f21d6def25ea84fa90f860c9f1737c921fb8f.nq.gz
    ├── 47d05af189408b2b0eb51475e55740531bfcc8b7.nq.gz
    ├── 47edf91184306381759c4fdebce087fe0da14b05.nq.gz
    ├── 4880e33cc6ed34049cde77c77dbd66f49c25a96c.nq.gz
    ├── 48b13af9ed382fbfa3653000f86a91a21b920567.nq.gz
    ├── 48bfff7e2f10a90dae59204b5fffa1ce15da3781.nq.gz
    ├── 4aa756f44fcec19aab6404807afe667fc94b31db.nq.gz
    ├── 4b2f4f2b67a3fe03b441b4cfcb4a245feaeed9fa.nq.gz
    ├── 4b7b824aeb3db1c856059d16217787a158129ae7.nq.gz
    ├── 4d811b64ea4c13950217f620fa162793cc2616ce.nq.gz
    ├── 4ffddf3701087619a2c937666b81500ceb5871e6.nq.gz
    ├── 50bab191980f9c85b35d1b0f9bc7246a3e0197a2.nq.gz
    ├── 52c02726626adb6685f888e3dfa1d2f94e44c72c.nq.gz
    ├── 54d756dc93f72e81a3dc291fd9fa36ee323fd7a0.nq.gz
    ├── 55f3c7097eb110621c1baee6b7ee0779040617b0.nq.gz
    ├── 5645c530a60cfeda91793c35479e9521b0e16dcc.nq.gz
    ├── 572060637e9f49a3e392d698ea1526d99cc1d64f.nq.gz
    ├── 58d68ba3550ac19782275d096e5eed28715534c7.nq.gz
    ├── 5a34628d21a913f78d48b3308127dc819f4ef26a.nq.gz
    ├── 5b31ff443e2ac39d7d146dcdab7fddc8b1571286.nq.gz
    ├── 5c313798fc64cf7fc4c084d99a758d27a7667d05.nq.gz
    ├── 614a9cc96bccfcb6dfea6a4b9cc37dd21725fa31.nq.gz
    ├── 618dc724087de420eea230d0e7223f8c818db9fa.nq.gz
    ├── 62aa59d01e5f57269dc21f400716ca3b516c819e.nq.gz
    ├── 62e232a7c0f414e524d150219ec63dd8b355653f.nq.gz
    ├── 64964a1811eeaf777318d786b7c282daf67c1c2a.nq.gz
    ├── 658121de918d8891e765bd6ef601ff1b9e54daeb.nq.gz
    ├── 65afb79c53a9a31d6844a810adccb8ebf6bf19b2.nq.gz
    ├── 66a02945de2719f1a496897830fc074cf29cf51d.nq.gz
    ├── 66dd2826da9ebb3645847e0adb914fe903f67a84.nq.gz
    ├── 67971fc4a4778f6675cabfc5cd0f301c06529ac4.nq.gz
    ├── 6824cdfc2a160caeb8927680fe1fb7325ab0cc9a.nq.gz
    ├── 6a096bafc736503e3dce9e2ad865b2b6a11dfb04.nq.gz
    ├── 6cfee52435f37f672569848731c70b2168686f6b.nq.gz
    ├── 7007d68c30c8d74bfec816bca7862099f03793b9.nq.gz
    ├── 7093143c539c71fdba941c84e98e84dde9063c45.nq.gz
    ├── 7285cd0bf023c4ad92a1170cfcfa8bd57fb5179b.nq.gz
    ├── 752f5ee13af5747970169e8367fa0833cd22e678.nq.gz
    ├── 76e3522274a1342973cd51825cb7038569860131.nq.gz
    ├── 790ba7db2e84948b5096e7214f745e8328bb14dc.nq.gz
    ├── 7917101ae173812d1a0a9dc57cc34316b787ab97.nq.gz
    ├── 7ceba6cc0fea7e46f067e8f618af70e6b45c75a1.nq.gz
    ├── 8014384300b211ca4396b603dd54cbf473562ec7.nq.gz
    ├── 80ef0f89593bb7814c65492cac1dde8fa4c178e8.nq.gz
    ├── 811a1d3fa805ed8c5af8239a9deaf25655d64657.nq.gz
    ├── 815e56fe7efacdeb13655694c709e7cb5a064170.nq.gz
    ├── 81933c8f12794ce8f78cd45a9021f01ae90fb947.nq.gz
    ├── 836029414d468d24ac12617edffd76a480afe792.nq.gz
    ├── 846882880953eedb903ff10072734ff0c2e1c9d6.nq.gz
    ├── 85116040f1a67922cbbb4e72de6a36900ffe6240.nq.gz
    ├── 8589dd5628faba3e97289758297f4a87236ee92f.nq.gz
    ├── 867c2763031d09d3341591b97f570cc82909aada.nq.gz
    ├── 870dbb4fad7460f912033a955fcc87e794fe9b13.nq.gz
    ├── 8849c48dc02bc32c0bd7ca19ae1dd7e80a3b7289.nq.gz
    ├── 885579f66f7a9518178ffed34f0f8715007e53a7.nq.gz
    ├── 894a9658687585d676d043900aa940ee80ab41f6.nq.gz
    ├── 8b7979efcbe4eaaffa27ce3c7ab5ff820c65d55f.nq.gz
    ├── 8d977d50264e4a2f8d2a5411d7e244130d048913.nq.gz
    ├── 8dfbc18de6fc5c61f1a870cfc8e886b413c88ef2.nq.gz
    ├── 8f347fe384a0fb8854dec9771ccbf9afaf4d2f12.nq.gz
    ├── 8feb525c07878c38423d562658156ee9a1509937.nq.gz
    ├── 900dd0064f5dc9089014f987f0a0ffe71bb0014f.nq.gz
    ├── 93dec62543096f7e7a69349a0219ed40dd32168f.nq.gz
    ├── 94e4936f19a15058cb7ae38c96b22f659653def6.nq.gz
    ├── 9586aca40b6b1fc98f05b96c911909b544f5057d.nq.gz
    ├── 95d4db5e5edabec0c0755c24de6a2c060e062f4c.nq.gz
    ├── 967dbb30a6421f4f5f43af64d366638b28681759.nq.gz
    ├── 9754112e369b9a1cc9d565b918a500cdbf24fc56.nq.gz
    ├── 985f882acd6481a7a33e6abeb4f3db82faf60f74.nq.gz
    ├── 9a5deca664822d7a921bf0bee9fac19a658f1671.nq.gz
    ├── 9a6c76d6d86898f7724b3fc0ebe957998b777c1b.nq.gz
    ├── 9a7320879c923be853f3be0878e5c18763d1f2e0.nq.gz
    ├── 9bbb9ad324f8a69f533bd9dbf6c77f6e18a29adf.nq.gz
    ├── 9c4d9d0ce9aae902e432d4e06f140b1cf3227469.nq.gz
    ├── 9f4635c8123aef210a43067310caebfa898d9e2e.nq.gz
    ├── a11d42d9e850aba41384e9f55d9fc4da51e0d6cf.nq.gz
    ├── a2f9632ada8b43e6c2a527905695bd70fa7350c6.nq.gz
    ├── a3a25f38f925e3e9ca70a1b245138ef8461907c6.nq.gz
    ├── a5b47f6e98df2c2c559b102cc653d1283c0c0937.nq.gz
    ├── a72862226acb8495be0787f00986a46f5b701043.nq.gz
    ├── a7934da84e4e99758bc5f90112ce3db1b270f152.nq.gz
    ├── a8e01cce373aa1155991f53c90c9ee82ac7d7c22.nq.gz
    ├── a93539e2927e2a34ebe6eb121a96a29d0ccd850c.nq.gz
    ├── ab440952f761861c43e344d4681279ad4634c472.nq.gz
    ├── ad651020b18c209b4cf25e764d410c0f2fe924c9.nq.gz
    ├── ae7a20fdf2399b291886be0208ea38e235f87bab.nq.gz
    ├── aea31ec5b756477bc2347882f803fa1a439edb67.nq.gz
    ├── afb5830ff1cd0dda903d9746c9ad0cc678b4d8d4.nq.gz
    ├── b028b9c7c15d483894951c93ac4eb23c6ca73430.nq.gz
    ├── b27a90464442d2f98a633ba6c5b0e060f8127ec5.nq.gz
    ├── b2ad90e760367d71f2a1ff020fa5f96a24650b6e.nq.gz
    ├── b31eb95fceba09cddff05fe73efc4ed90d06516e.nq.gz
    ├── bcb0d9718c83f409db7104297d9e79cfcc2ed838.nq.gz
    ├── bea5c11a5f6422f9489cf12c7a751c243a3b7705.nq.gz
    ├── beb9ccda8001c6856fc000f03b67c8fab705084f.nq.gz
    ├── bf391ad9b44835fe46fcf2207af8a8b5a4b0b866.nq.gz
    ├── c10fd1739dc42cf18ea4d0c3fa99d4ddba13c942.nq.gz
    ├── c3e63d41898cef3c8861b8ee3fb40ed4030151f9.nq.gz
    ├── c481d365d0c71ebfbce4b3e193f984494a81e3c0.nq.gz
    ├── c57badfe0e0d1913e318188f633791772aca2667.nq.gz
    ├── c5f8dfe0acd25c9ed8281b0b2d7d6758f0c3d56b.nq.gz
    ├── c675f83d297fed49068dd0d6b4919d28beee150f.nq.gz
    ├── ce99313f9904c407a0d2c7846962230c792c6b25.nq.gz
    ├── cec72350aeb8ce6c1415d40d5f6c39997fca4e6c.nq.gz
    ├── d006a4e493c89d1d89a8dfb94c504e8d838f41af.nq.gz
    ├── d19c5349bb20f102aebd0be097cdc6b94488c4e7.nq.gz
    ├── d2695395b087542794eb6a434d476661c75e7659.nq.gz
    ├── d36b37586eb19fdfcb6e071014356df92d7808d4.nq.gz
    ├── d37c6d73dafcee28da656d9765633c6ae4710cfb.nq.gz
    ├── d382d244106a73aa0b18e2a7e57d9d9bac58011c.nq.gz
    ├── d4ea18e26558733ce814d152f84fa1dfe74ab508.nq.gz
    ├── d50c83bd87528b8e43bcfed97780b8420b52d4ad.nq.gz
    ├── d5e5b00c8b038529d227ec27fd6671daf5d7b529.nq.gz
    ├── d80c9fb591257bf828dbb2913877ad32b5df6e8d.nq.gz
    ├── d842e856f8c9362ccc4179b94e9bd23d05182436.nq.gz
    ├── d8d0f8e426bbebc0b597cdcd8e14a15e95e34c7b.nq.gz
    ├── d96085affb5197c28cd6fc041170c4bec55341d2.nq.gz
    ├── d96464c3b2c9ecbcdd3449eb13bf7091751b36f8.nq.gz
    ├── d9e69532640d1f21829f058d444084d404de0747.nq.gz
    ├── da323058b30e4a03302a15a422f1d5334a6027f7.nq.gz
    ├── da981f39e522b1f5b56568385616a58a56f149d3.nq.gz
    ├── db0a3675fb8b3dca647a9e1188b514cb02f6c7c5.nq.gz
    ├── dda2feb9bd1463ea38de8123a738231bb887b05d.nq.gz
    ├── ddba5ca41435c84351943d89d3c4dc24e53aeeea.nq.gz
    ├── de32e9e9255bacdf00b270d5896ae0cae2cc1c9f.nq.gz
    ├── df52cfcb877d3d2663e340d63a969e4eda948a64.nq.gz
    ├── e062bd8f6324aa9ccc468a80c6d934bc7746843b.nq.gz
    ├── e2c99f8cebd7a30f0c938cfb4c7dc226b0066e9c.nq.gz
    ├── e3554020ebaf071a402258df1b280428c089aecf.nq.gz
    ├── e394bdccb15671daac79f09a8b998a730af605bc.nq.gz
    ├── e40f38c7503dbacad71ab8969a4ed695c23edd72.nq.gz
    ├── e60dae685dfdb19cb024946cd082d78cf7bcb2ad.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e6d37317621ebe008c9d932c62ee9db9df582c36.nq.gz
    ├── e6f014360a4e9a94824342e3947f668e8c700172.nq.gz
    ├── e6fd8d7e0a9b9a7da6c908bbe26abe2d9a53d89c.nq.gz
    ├── ea6856485db5418c65a80712e749c4e762a44a5d.nq.gz
    └── ebe6a9712e468788a8f40c56214435766b15166c.nq.gz

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

[ourownstory/neural_prophet](https://github.com/ourownstory/neural_prophet)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
