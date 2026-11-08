# Repolex Knowledge Graph of vllm-project/vllm-ascend

RDF knowledge graph data for [vllm-project/vllm-ascend](https://github.com/vllm-project/vllm-ascend), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/vllm-ascend
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28e9e97ba254b076a88275e8a275556cb9a11664
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 28e9e97ba254b076a88275e8a275556cb9a11664
│           └── chunk-001.nq.gz
└── blob
    ├── 0013939ce6d5068d516455396fba80eea3546ae1.nq.gz
    ├── 00711c4f5ef5ec8d29d1d975f021f22501d705ec.nq.gz
    ├── 00d1274435dc3c1c091fcc11af27810cf6592157.nq.gz
    ├── 03064097ad85a5b5070ca84a12877131dde1418a.nq.gz
    ├── 03d65ba39691450df0bbee1a3c8cd697de60b1cb.nq.gz
    ├── 042e7a23fa7e1e96eb9f90bf90231dab2a6c0ad7.nq.gz
    ├── 048bdca05ed27fd97d3bee75be05ccb636b032e4.nq.gz
    ├── 0494b5e321f832ad2f32e4e529fcb699bdd3f9b4.nq.gz
    ├── 04a288ea8eda636aee191f42d82c28293ecd6c81.nq.gz
    ├── 058335d0960661d192357f2b0f2bb29fe465eea0.nq.gz
    ├── 05e1b2de6694c81d3e86fb17f692a7bf47e21b0b.nq.gz
    ├── 0637828252b363dee1df0b9e776fb79f8d9a3ec1.nq.gz
    ├── 067a2c51a7e88a1121005275a6e7fdfe1671348e.nq.gz
    ├── 06815a28cb57e3a4bd122623b4704b19362b919e.nq.gz
    ├── 06dd0edad5e14ce12bc916837cb9a7a5ee20ab04.nq.gz
    ├── 076495d2f9b41a67131b4002870e06106a583707.nq.gz
    ├── 07eece6bdc301b8e26ef13787a74d8fc74d786e6.nq.gz
    ├── 07fd28dada22623e98b5672aeb68d8689fe2a01b.nq.gz
    ├── 08664f315a1675654a95445a80d61443c1fcdce8.nq.gz
    ├── 089d9d2da5f6a4ed344d197318e7025489f1e27f.nq.gz
    ├── 08c784f15020962d13887c6a6b211a791cc692af.nq.gz
    ├── 095c4b6d9813cc81fa75480cff324b0082105bed.nq.gz
    ├── 09645b8aea597ed9598715399f368554ccf24d58.nq.gz
    ├── 0a0f54fbb3900d83491c5fed7385864629b4de44.nq.gz
    ├── 0a64d07ed26517e51536e750e1a64666bde82fbb.nq.gz
    ├── 0b83e9519060e01f0c53c32ad7dff1f5fc3dbc2e.nq.gz
    ├── 0bf2713b296051edb664726851de56624b13252f.nq.gz
    ├── 0c3e843b38c3432ec2ec4db7ef6d6d257a95abfd.nq.gz
    ├── 0c7fdf9155b9c97e0c1a5cda62ac371b260c53e9.nq.gz
    ├── 0dab97710193fe96b8319b5a68569e6964b6bbcf.nq.gz
    ├── 0e471003f42dec0fc02fff491e32a27b5c108432.nq.gz
    ├── 0e73f88979c2a890b4bbb552204845fe54aa9392.nq.gz
    ├── 0f32b4a5b942adfe5fe0d1cdb99e780806e192be.nq.gz
    ├── 0f340604fd598228f1e46fd035c4cfb0d76514dd.nq.gz
    ├── 11918997414e687a74ba5c4e8fb362054f126649.nq.gz
    ├── 127a6a86e6263fc45480e60b74bb148675b54457.nq.gz
    ├── 129e7e59bf738792bfc6070fa5e4a7e403ac0631.nq.gz
    ├── 12e8546275de2fcccf838054177cb5d5385bcd52.nq.gz
    ├── 13fde8db27f0d854104071ba80db1f87e21ec4cb.nq.gz
    ├── 141cc399c89ab4b1499ff66b1df07eef93159a5f.nq.gz
    ├── 142605aeb9d07850559b06769e93e6b0bf5eb30f.nq.gz
    ├── 143a52761fd3e616a9de347054a969abb84f4d0a.nq.gz
    ├── 14ebaed3e4a0d591b4ace7ca3623e3338229159c.nq.gz
    ├── 167a9e1de4c903a215965e87bff5fd594438aa19.nq.gz
    ├── 16c0eac58bd1d35acbfbde1214273afe74e42bfc.nq.gz
    ├── 16d07a90948076b2dd461298ad28d119c0741abd.nq.gz
    ├── 178ea770f26fd8d9224f064e33b6377812335de4.nq.gz
    ├── 18288d7e9eb94ab93e8a2f0435ff0a2c51608fb6.nq.gz
    ├── 185a7ea38bf7298bfa4c5412279d9fcce977c360.nq.gz
    ├── 18e5aed5cdfee38e183f3d32f533d255d98e13e2.nq.gz
    ├── 1966c5269dc22846d8fea53da726b91cfc9a0a0d.nq.gz
    ├── 1afa46dbd4c46644e60e8dc1da96a7a7f20cb775.nq.gz
    ├── 1b5410f7df24a22b5670e9b35c676e220da48cdd.nq.gz
    ├── 1c035e944541791635f3e3b4c74d7d8e099843d0.nq.gz
    ├── 1d08705b64e1c7a8c76ee96f40d1ac6408fa55ff.nq.gz
    ├── 1d2402781124c05ce5bef4d9d2bb0076f33a7f9c.nq.gz
    ├── 1d94f4a133230d9abc5002ea3c723a8000af7b28.nq.gz
    ├── 1e0535fc72032888247168a7f96f949dd38a92a4.nq.gz
    ├── 1fcbe346e6af4fa42408fab6796f1fc485534be7.nq.gz
    ├── 203afb6a6a16a0d51655f5dd61c12098f83501d6.nq.gz
    ├── 2065ac8bb24dc5c52a19189fd313afdbc8919ec0.nq.gz
    ├── 211a80b776c6f5e6e561a0a5c7a6bfc7c53d000a.nq.gz
    ├── 211e8ab3a888d817663c94ae7f86c10a4978bed8.nq.gz
    ├── 2253d759fa174bfbb6c144c9408e3b0b18a545e6.nq.gz
    ├── 2282b56db8bdefc21bcf12ea4bcfaf995426988e.nq.gz
    ├── 22a29e9b08c33119d76a1cf92e265d9abafd3f51.nq.gz
    ├── 22dec325e1328577a3fa3286a3b5a4e102861c14.nq.gz
    ├── 2459481eff37ec05213e84501903546217398cf3.nq.gz
    ├── 2459b2eab37fbf4e011e414e28f62b3a68ca3cd6.nq.gz
    ├── 24c221d09756ad9ebf545b35590d8f8cf790cfd9.nq.gz
    ├── 2599fa75993a2cc72957ddce5ad754e6f5b781f5.nq.gz
    ├── 25a4507ff647d429c0749deae65d441bfb32e343.nq.gz
    ├── 25b1a201132994d56cb7ed5b7d72c1c095f0d2e5.nq.gz
    ├── 25ed7abc87407a986ed49af7a2cd357c1f223175.nq.gz
    ├── 261f58ae38d7c4631ab94c8a3f038d0b361c90ef.nq.gz
    ├── 27563c79a56bf28fd1669d23e3027c4abb8c43b5.nq.gz
    ├── 28271c2041e1c6f34bb646ad26d87dccfce7ba49.nq.gz
    ├── 28542fe4c503f8fd967e41472e1804725d5e7e70.nq.gz
    ├── 291827c8bbebe9aedd1d04074e92f2411e53e563.nq.gz
    ├── 298ed56778f2d4330b1287343c98d24bcd54f678.nq.gz
    ├── 29a79f0896a6a4d2976b1972a5a217971363d74c.nq.gz
    ├── 2a9d6f94b468ff4c738d5810a115ced07ed98498.nq.gz
    ├── 2aa829d98ea1b5ff741c5c1902b1fd748f3a445f.nq.gz
    ├── 2b68ca4e0a4d41f1de0fc9630fea3feed4864692.nq.gz
    ├── 2c04111731243da043ee099ef7406cfa2363d2ba.nq.gz
    ├── 2cbf4eec18a551b7972854d96f17430f50785767.nq.gz
    ├── 2d46bd5b28fca94c57f6b7aa4870844dbc1a3b97.nq.gz
    ├── 2dbca20866747604cd56d234aca984e123fa9193.nq.gz
    ├── 2df484d98c40c96a395297c74de27c4b23750cdd.nq.gz
    ├── 2f2c3e4ae0f4761a6067f891d584d9efff7d6689.nq.gz
    ├── 31603c685c5a85e1c6fcd94e4be4b412df3566db.nq.gz
    ├── 3218cb6cb512dab5905b5800cae632ab694c0b99.nq.gz
    ├── 3249138e1789079de8127af48626b73165543715.nq.gz
    ├── 32c3d5c35ac9aceafd805fe005c58b9e5d708a87.nq.gz
    ├── 33000ab35505655a2064cdd8a683481e4883bb25.nq.gz
    ├── 3311f9a3ba230a434f00e1e59d56bf518121df45.nq.gz
    ├── 3359bc204358aaf24f7d71271645b6a17f3ba09d.nq.gz
    ├── 33adb09a185068078d0edbb9f126e994ad084a8a.nq.gz
    ├── 3447b9cfc89e454c96b0d05b1be15a09a4962983.nq.gz
    ├── 3491adc5b0389f903b14f1d03946899016a064db.nq.gz
    ├── 35083f1227e9ade94a5f7162317e0042ce34cecc.nq.gz
    ├── 35cc6e72798b75ffe66f72ff8e562c481ec126f4.nq.gz
    ├── 36391577dc1c249cf0886b5c8cb89d0f55e4714b.nq.gz
    ├── 365e36d528e3b2c2ade5bcd96108746d9dd25eff.nq.gz
    ├── 3679c7be2cbc25e659ceae129d3690004bdd7f0f.nq.gz
    ├── 37282c36d837af0c18802d4b3e57b3a02916a269.nq.gz
    ├── 37603b87c12b3fac597a3840343f5c3c39423282.nq.gz
    ├── 3876158ef580636a1d23f87438a315089fd1b5a2.nq.gz
    ├── 3918b1ace73436733c15817d09604aad81a2f0b4.nq.gz
    ├── 39505afce3fa0d39eb9bc58647b7380cfa7738e3.nq.gz
    ├── 398856853c468421a78263901500d60412462700.nq.gz
    ├── 3a16d95c9bc52ff634ba12f8448f5a5e3990612b.nq.gz
    ├── 3a255b2e6dc9091e3887ddec812f51e3ce7e0474.nq.gz
    ├── 3a8f103e8edbab2235cb8a4a616b36b6ded637d1.nq.gz
    ├── 3b00efc7690dbfa2c8de3bdd47cd1ee306d34a9e.nq.gz
    ├── 3bbff7a7b3adce5d92098ce0eda0549e5bcc2f7a.nq.gz
    ├── 3bebc25ebca39152d1a7934aa40812986392f397.nq.gz
    ├── 3c741b49eb279f77c69373d14ef2f15d9859017b.nq.gz
    ├── 3ca9bc54d1c9a6dc476dd4ba0fa4a39590981212.nq.gz
    ├── 3defb4f77abf4b2883886b60acea8fbd4abb4ad4.nq.gz
    ├── 3f5d1f4993603b88cacda97272ca01c77b624fcf.nq.gz
    ├── 3f6c47582b095763571da56b67cc8a3cfd9069fd.nq.gz
    ├── 3f996e8c344d42cea3a0443ce413706c176f3bd6.nq.gz
    ├── 3fd3561b0832b7111346b20ef6ec079848874956.nq.gz
    ├── 3ff0b0eca8c47532aebff973c00cdf0228fb93a1.nq.gz
    ├── 400145f78de548c7a0654c80d031cb05f04eebf2.nq.gz
    ├── 4037b1756922d7ffb36c32cb0dec2450b2a7fdc9.nq.gz
    ├── 405348765b9c7cecf5ed3723452c9eac5ca3788e.nq.gz
    ├── 407bf0ab5f907585c5fab4318eae54dc4660b069.nq.gz
    ├── 40b594611e12eef01d277fe8f34af9488039a5a3.nq.gz
    ├── 41bee5057b43749085bc92f8cab51e29b1e67ce9.nq.gz
    ├── 424bbf50f78c30431f761e7cfb3c9b3a7cc6ff4c.nq.gz
    ├── 4254b776fb20d31be47a5a95432b9186f848edeb.nq.gz
    ├── 42ac048a52d7cd3c27f589678ca9b658cacd8d4b.nq.gz
    ├── 42bbc6f62c5d4221cd6c5b8d92ecc8c58ac4deea.nq.gz
    ├── 4385d9cff944d19417244ed6d3e348eaee1a5770.nq.gz
    ├── 43a67050bb963149ee74de06f3a42a2bb80ecb91.nq.gz
    ├── 43baf819c6ea801e9ea4d5769be3af063f5844f7.nq.gz
    ├── 445361d9c09b998d286043b369dbfa97677e8e17.nq.gz
    ├── 4503614aeadc8a24652a3248f15c4e506c194533.nq.gz
    ├── 45a9a8d18c8386ccf52bf8fda084354f3c4c9f04.nq.gz
    ├── 46063cda95e78bbcb9d4bc7a4dceaa703ac4397a.nq.gz
    ├── 46d818d166380227d4c7bc09c754aa7a474f538c.nq.gz
    ├── 4792dc9dd2a88111fff42b81a36c78ddcb5183af.nq.gz
    ├── 489b11fbb069d91ed65638ca74061ee0ffa16047.nq.gz
    ├── 49b371c48386b4342c244e4730792730ca58e126.nq.gz
    ├── 49b8cb0549267a8176467738b172a63d86eff436.nq.gz
    ├── 4a0b143e2a12e41df9995a3fb361da6e1e02398e.nq.gz
    ├── 4aa0af8e2b232a6f5dcef3daf82979a0284cce53.nq.gz
    ├── 4b6f9ed06825f700766d553b4c215905276351ee.nq.gz
    ├── 4b84a35a08043fa3eb14ac4fe40081b7b61086a2.nq.gz
    ├── 4c25e762d49526e584dec249609b65ae74be85d6.nq.gz
    ├── 4d1d30f457a68fb47ad6350200bc79541ec5da7e.nq.gz
    ├── 4d631d9dc379629ba68ebff4057137aa0d20e3de.nq.gz
    ├── 4ddc85b9c79661563e8e03348e26dbbf27df8923.nq.gz
    ├── 4ddd94e0350530f7d7dfdec27df6b81e5ebfd513.nq.gz
    ├── 4e47ea33e990763041c29a9e62dfd5ae93fde5db.nq.gz
    ├── 4f222c6112c3bb437c05e9b99d0c62171307568f.nq.gz
    ├── 501011e2609213f8f31f267eaa57d52c60bf7c4b.nq.gz
    ├── 5028a03d4a91245d0a3d07a35d8dcd6a56903dfd.nq.gz
    ├── 50abeaf2bf46e50da90e27f1ddb0205bb1ba70d1.nq.gz
    ├── 5109f8de8f52b7ca3271cab03dbfc73431e996cb.nq.gz
    ├── 51412708b6b157d910e90020385d12344242df14.nq.gz
    ├── 5212a6d32ac08bc5543e6e338a356798b927770a.nq.gz
    ├── 542115f8f385ee24746898dca801983ce79ea732.nq.gz
    ├── 544325f6068d42fc97bc3d75e8a8200659cac875.nq.gz
    ├── 5448ff426216195231619097a44b12462c0f3892.nq.gz
    ├── 549b5c14cdfbc3fe6e94a84ccfa704b3ac124ddd.nq.gz
    ├── 55605892e0798c636826abfe6b5debb5bb96043b.nq.gz
    ├── 5568878f5ae6b40c611581c2f3b3cbe411efe155.nq.gz
    ├── 558f1fbc9a24f207f123b88576ceab9e72781cc7.nq.gz
    ├── 5783810553649a384b10912067944f1f7a764b7b.nq.gz
    ├── 581312a0bd5e738eacd40d55495256e9b3e16257.nq.gz
    ├── 5847fb4179beaca17c86e30ac53377e1f3b1ff82.nq.gz
    ├── 585bfe1d5d4ba3e6055c327fa580556e9abd5e3b.nq.gz
    ├── 585d5772f9150c910d930dffbc335b754ac8a983.nq.gz
    ├── 59c337fc936a454ecdb9cd89418754737e75653b.nq.gz
    ├── 5a10e41b830b98313c08bf01eda8b9121840918e.nq.gz
    ├── 5a74d03365a0c7c257916f92875c95db2880a36e.nq.gz
    ├── 5a7fda4683f563be845f743429343d0ab4f3f876.nq.gz
    ├── 5a89e3e591ef07166ff718d118b6b1e759b1f37c.nq.gz
    ├── 5b3220422ad23948797880949689b825a52c501e.nq.gz
    ├── 5b32211b2cf0eeaaaad00be58a9aeeec7cae321a.nq.gz
    ├── 5c7a894730e774be4e501a676c97fd6acc3cac51.nq.gz
    ├── 5d9d6831052add022fdc4e3ab6d686167628a499.nq.gz
    ├── 5dc9a58c1255775b8518a34b64850fabe3d560f1.nq.gz
    ├── 5e5693ddca77a0fa4b6f6ee72670941fe7bb3aa8.nq.gz
    ├── 5e68eb66d482260f01138873b04716f3717c67dd.nq.gz
    ├── 5eca7f0b7180fe1899898f8ad317fbdaf12cc0e4.nq.gz
    ├── 5f8184edcd23f0b7e49d4c1362d3372032ca2374.nq.gz
    ├── 60a6662cadc194534702425400ebeeab3df5156c.nq.gz
    ├── 60c884f9653d267b4bf4a3df5b905d45bd23c3db.nq.gz
    ├── 61353a17e755ff6b18ff233263a502a56ecd4c1f.nq.gz
    ├── 6137688adabee3427f470eb0e0567291eaa45c42.nq.gz
    ├── 61db94c06d84ba77f1400020ce155d0cd242ba15.nq.gz
    ├── 61e4f8173e71216597560a6fe409c7af5a39ddd3.nq.gz
    ├── 621b4e6a288f04f0d24a268a39bc223513834f1a.nq.gz
    └── 6364a8704305459417f34f618b11723f52521b27.nq.gz

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

[vllm-project/vllm-ascend](https://github.com/vllm-project/vllm-ascend)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
