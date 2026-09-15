# Repolex Knowledge Graph of import-js/eslint-plugin-import

RDF knowledge graph data for [import-js/eslint-plugin-import](https://github.com/import-js/eslint-plugin-import), parsed by [repolex](https://repolex.ai).

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
lexq download import-js/eslint-plugin-import
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 67103e698dcaa02a95f95145d2db6a04f1a573f8
│   │   │   └── chunk-001.nq.gz
│   │   └── 68cea3e6b6fe5fd61e5cf2e2c7c0be9e8dc597cb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 67103e698dcaa02a95f95145d2db6a04f1a573f8.nq.gz
│   │   └── 68cea3e6b6fe5fd61e5cf2e2c7c0be9e8dc597cb.nq.gz
│   └── repolex
│       └── 67103e698dcaa02a95f95145d2db6a04f1a573f8
│           └── chunk-001.nq.gz
└── blob
    ├── 002bd8cb66b2ce137aabb30854b9126c30fc4f2a.nq.gz
    ├── 00c93fcba1b105b7cd19fb6f797ae6ff0f5c8066.nq.gz
    ├── 012c3a7c7b554edc1a56f6aa96311e7ed033ed9b.nq.gz
    ├── 013433455818c3f07d8b93af2e1eeac65083cf16.nq.gz
    ├── 01ff4f36f2c503f473b44b2f5074f0d1583a2218.nq.gz
    ├── 0274e43745594286b0195605cf7bbfb99386279c.nq.gz
    ├── 027aed07975a5c299c50a1d9d77f1519103e45ca.nq.gz
    ├── 0421413833bf216b27130debe8f4f96eec2a062b.nq.gz
    ├── 043b375628fff40390d733e44889be15d33f0717.nq.gz
    ├── 043d6994241b31fda7e37731703675b56c2ec1e6.nq.gz
    ├── 04ac20265bad32a321ad974a9cfb691e6f6d816a.nq.gz
    ├── 04d6de0577a07f8bf981cdf7ef2fd0e26aee1ed8.nq.gz
    ├── 05328e51e9152ffb1c07ebde9b06ee68f9c57aa1.nq.gz
    ├── 057711e9bf3244bfae861c7d0a0828b9cd0be341.nq.gz
    ├── 05860cde1e0fde2f3bfefcab8ea42261e4518820.nq.gz
    ├── 05ed0a52109e589641b0e452308a884b9435421d.nq.gz
    ├── 05ef4ef3270fdd70c8640df94607cdd3bce41b86.nq.gz
    ├── 066e52a6f7622988da1791d66f293e505e75989d.nq.gz
    ├── 068eb911c3fb918fc8158be8a53805827179df73.nq.gz
    ├── 06aad44699425af4604f934eefd32f7d8f371275.nq.gz
    ├── 06cd8afce7d0a3418b39287bb75d5208ab37e0a8.nq.gz
    ├── 06d938e40b08605a2a0673318cb6792316f1527c.nq.gz
    ├── 06dc48a9dcc2dda715a7bbc52c5b3cbfce6058a4.nq.gz
    ├── 07068866bed581159a11138b8ad63ed3f89c44e7.nq.gz
    ├── 076e59fd761ed81ac35c236e48924ef80659a91b.nq.gz
    ├── 08371931f2a6c76fa9b0996db4af8e0aa22c305b.nq.gz
    ├── 08674714227bfbf5e954aa79d6d966b5dbe517c4.nq.gz
    ├── 0894d29f28bb8284af8ce872473c31d6d22fdc97.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 096df7728190cdc897252697733d5f304cde7647.nq.gz
    ├── 09a6328118945eb95e2700b04d7dde9fed99557c.nq.gz
    ├── 0a0e128dc0591ac2d489924c82eb08f74f542136.nq.gz
    ├── 0a5fb6e237f9ea78fd70534639a30cf2f68be705.nq.gz
    ├── 0bd805612b70a67cc7d0e1d6295d0c983e4be9fe.nq.gz
    ├── 0be6eb2fd6625c11013ef58aabbc6af40dbed065.nq.gz
    ├── 0c632c24767df8e45ba548eaf703a8243d571bbd.nq.gz
    ├── 0cffc87d1994b9fe3ae13679fc897c970b944e22.nq.gz
    ├── 0d5e1870a7d3d9341c2c022fc04191457e05a5c1.nq.gz
    ├── 0dad14e067c986f58bb6117947af4af927c5a6d0.nq.gz
    ├── 0db9b05f499d84d09750017647aeed996d788cc6.nq.gz
    ├── 0dbd8cb86c179834548c440d079abc222e09a470.nq.gz
    ├── 0dc5fc09546b48bf944d041ce56af981643e746f.nq.gz
    ├── 0dcd5266bb73156f4e462c915ca9bd4277b923c7.nq.gz
    ├── 0de787c33cb52be21451ccc8f67b513aa3d12a95.nq.gz
    ├── 0e4a12c68ab0a0c09cd108afa0da207ef63862d8.nq.gz
    ├── 0ef28872fdbd01b312a6a30968bff5f62c934627.nq.gz
    ├── 0f0af7d06b02090a8d31d090c9a76b500f8109b8.nq.gz
    ├── 0f697cc2546b4c9f9d5fc1e7c0d5301e7b1ddb8e.nq.gz
    ├── 0f7bb6d371d3add73c4068d41491af2b7f89ba96.nq.gz
    ├── 0fceac591585e8835bbe384abc4aaa1176a5efb3.nq.gz
    ├── 0fe78c5218340589bc34a89122f1914d720e7ccc.nq.gz
    ├── 0ff881e349afd7c409734f99086f6d30cf2cb87a.nq.gz
    ├── 103f2fd6fe6427b92f4c2cc67e5fc965e6f88560.nq.gz
    ├── 1084360870c9774162f15a30bc8f6c9a9407d4fc.nq.gz
    ├── 1091770f7f0d086cac1684da379b866766534f1d.nq.gz
    ├── 10a17c3b1952e8c368af9a8d52f9383008aa0205.nq.gz
    ├── 10ba76b79d4ad1b0518d33aa4cc865f27ea102ab.nq.gz
    ├── 10eab3796ccec7f6458671d1ef8c333b72bf4c87.nq.gz
    ├── 116a4bfd4fac46317b7119673faeefcbc2067079.nq.gz
    ├── 116c89cf57f8ba1edd0c60df08bbb8d14d0226b4.nq.gz
    ├── 11934599ee1ae91386f252707eb8721a20954544.nq.gz
    ├── 11bc1f52a4b06733a958c13162fac6421d9da99a.nq.gz
    ├── 124b1745d205e79175ca89ed44b82f0c0b188064.nq.gz
    ├── 127c29a0cca94138b39843b8c34e688a1053f232.nq.gz
    ├── 12a7650082ec97200ad448c70e40a5f9d56afa9c.nq.gz
    ├── 12f790ecb5e805d79d3457efe4b854f475fb2457.nq.gz
    ├── 12fb8b7a23783519fbf1c31c131c7a751a2db69a.nq.gz
    ├── 13135e3925bee5691bf968948c9101d1d41ffa16.nq.gz
    ├── 131604ad953559dff1813543071840858b9dc5c1.nq.gz
    ├── 134f23bbce3626733029216288d1debc0e473da7.nq.gz
    ├── 139457ff606b2dcb46424d6d9af3ca88adb35fbd.nq.gz
    ├── 13ea63ad739de4b68dc574e8c46934b6b69d67bc.nq.gz
    ├── 14006c5dc62b61909d1a3c57ba662a154c6694fc.nq.gz
    ├── 1432652658de1a825a512864ed555eeaba222b76.nq.gz
    ├── 154dbeef9524c4861bdda44ba53d54e6d73e7ddc.nq.gz
    ├── 15c67470ef12f88907e464e7e7bea31cb58a8772.nq.gz
    ├── 1605a22035ca3f1f5d19cb18e4050b62582cb8be.nq.gz
    ├── 1626bb2720c5d491a5b9de31f68b81ba55e5eed9.nq.gz
    ├── 1679224189c017f8c84cec0f2815f8877aff8d66.nq.gz
    ├── 170b10e1a13f42af1218e4c880ae4bd2be8d7207.nq.gz
    ├── 17406e80ebb8ba54ef19cd1613fe5b6b85cf3de5.nq.gz
    ├── 17406f1bbdbcace05eba46c1aa5d7e203086a920.nq.gz
    ├── 187273589c993048b8fed66ff4559fd34f672b7e.nq.gz
    ├── 18a1e415e56220fa5122428a4ef8eb8874756576.nq.gz
    ├── 19082862fc93def5ae7b665826026cdbfe85198e.nq.gz
    ├── 194a3fd536fb4cb0968188c911d12ebbd96158a9.nq.gz
    ├── 194bb8fc882c4c4b43a87a25ced40481f82edefb.nq.gz
    ├── 1a177f58199cfac30f4338b2ae938ed523efd10a.nq.gz
    ├── 1a3a112f58374ac1643793b6b2b440cfeb8584a7.nq.gz
    ├── 1a5baff5a9a760e4a9b0c129429fbe80462836a5.nq.gz
    ├── 1a706387c01d924627c83cd2422507680e5138d4.nq.gz
    ├── 1ae8e1a51a44c240445c6af77330c72b5fdf2c87.nq.gz
    ├── 1b946b35add917641ecc271031f75254220e2e89.nq.gz
    ├── 1ba6fba79b2a2a654278475d1f9d4c65a2656eb2.nq.gz
    ├── 1bb4b63fafeb72ce462fdfa31e7eed734f0bbfc3.nq.gz
    ├── 1c42b46167a976de7343a2b7068047af657a025d.nq.gz
    ├── 1c572264959f2a3c87e3ec1c6434ff1b55719669.nq.gz
    ├── 1d0fe1bd5e3443982f55926ded20edb443faeb60.nq.gz
    ├── 1d7b55ff51b7bbed57b8f4b36e427c74a5edd24b.nq.gz
    ├── 1da867deffdd82639bc6920a4140cb156c00add9.nq.gz
    ├── 1de6d020c8aa666b9b9d5ea77139e4c3b6908350.nq.gz
    ├── 1df57a23aa8a18b47a2c32083f97bdec69598c1e.nq.gz
    ├── 1e3207d20890f7653a65c71f6d1ec1804c0f8adc.nq.gz
    ├── 1e79f8339c2e8385e66676039735c4e70dec2e68.nq.gz
    ├── 1ecbca64d3241bc699c34449c5a52929ab34c973.nq.gz
    ├── 1ed0e31df572fe7c6b5d50f388845b67659b1409.nq.gz
    ├── 202103085ce76c654eae0528cbd05a6c47304560.nq.gz
    ├── 20306c1829324dfa741a8b5fee39052e51759c2a.nq.gz
    ├── 20fe1e5af443d5d13df9d5d451a5854e53e0ea58.nq.gz
    ├── 211fd972f6e40f2227e1abf91a3ac9b9bc114c10.nq.gz
    ├── 218c3cff7c0b4354bbe9e6644e8534bd946dbf76.nq.gz
    ├── 21a7070fb73e63f7784942f34cb40ebcd9a1fc88.nq.gz
    ├── 21c1a7c6441a07054f4cc694c6cb9e1b50a7a964.nq.gz
    ├── 21d9a5f704881f0126ad8a1a042a1136c9148c59.nq.gz
    ├── 21ed524a9f8483170da34fdedde9d484fd4a571e.nq.gz
    ├── 225adab22221b508ce51c9ea56b27c025cc522fa.nq.gz
    ├── 22c4bf965b223215ed029ac64089e3048d56d472.nq.gz
    ├── 231f1b667dcb42d1563c7682779ff8e7f883053d.nq.gz
    ├── 23e584bcc9c2f52839cbd4cfae908be759108421.nq.gz
    ├── 2491fad3ebfd1b0b6b067eac6842a669eff62ffb.nq.gz
    ├── 24c76849ddc5c7d9d5edc2b7023c2b8cbe085bfe.nq.gz
    ├── 24d5504a71c269e4181fcee3f67cae62333900a3.nq.gz
    ├── 24e6bc0ac5e5798c869b70673a4143ac7bee6d27.nq.gz
    ├── 2528e5207608a90e51c471d82dc7907d22b1d284.nq.gz
    ├── 259feb4cd98e41921a0748135b11d8034e9a0fa1.nq.gz
    ├── 25a91aef513530766e26859d57135162fc6f8437.nq.gz
    ├── 261989a75c0f4934c5f998bd33b42235c389ac01.nq.gz
    ├── 26f3534d7bb9cc0e223b6e8ce37caf650e55d41d.nq.gz
    ├── 271c76ca8223e8ba48c3db94b893927cb64092fd.nq.gz
    ├── 278e4c472508174038a32a9dade911fe051a792e.nq.gz
    ├── 27d5dcc1e1e28973bf34cc74f3949a120f0ff7c5.nq.gz
    ├── 27dec2033dbca1581f0d89ca4b09790f414fdac2.nq.gz
    ├── 28272c6fef3f5af26c39bc70a0fac4ea1d8facd6.nq.gz
    ├── 285a377f27dbf4f442ab20198da391cdec62c438.nq.gz
    ├── 290946735f79a8fbd00b57c7a130bc7cdfc2f1cd.nq.gz
    ├── 2917b03f51a7bd240f650bfa1cb75c81a597b514.nq.gz
    ├── 291b1c058a57e282be5cd34c93a2f45888ccf84e.nq.gz
    ├── 291daee48427a797d0fca2ac62b1a2ce3031628d.nq.gz
    ├── 292055fcdc20b5f225f42cd883c2dc6ed5e71590.nq.gz
    ├── 293bb8ae60b7150c3f617977b0f07fdbe60a6b07.nq.gz
    ├── 29c16f15d166fae4f52413402c490c19d548d16b.nq.gz
    ├── 29fae41015cc16825e14538d5922ed31120eb659.nq.gz
    ├── 2a2d45185001caa863db8d3129a49f5ae7f8ec17.nq.gz
    ├── 2a31d57e1924c26179edc79955043a7ff4fa196b.nq.gz
    ├── 2ad4822f7c4af14414e1195c7a04c3d093efd5dc.nq.gz
    ├── 2aeef64758d20a3d3d3fffd454eba27a36e7b309.nq.gz
    ├── 2b2126c8b5d5f331f51b6f4d6340ee7459f2a0ac.nq.gz
    ├── 2b5a2d41efd3f394e74a37bb452dd595e7ce7f04.nq.gz
    ├── 2bc5e42242f3aa5519d46a714c848018713ead80.nq.gz
    ├── 2bef94ec2b997226fbf4bba0555050ee6cc0329a.nq.gz
    ├── 2c63c0851048d8f7bff41ecf0f8cee05f52fd120.nq.gz
    ├── 2d36b837ed001a39426ac08a73d8ce91208a03d3.nq.gz
    ├── 2d4eab380f442d11921517183dc5e853609d8abf.nq.gz
    ├── 2d7500a680c1f9443467d451f9a5dfce8c229063.nq.gz
    ├── 2d8dd35269e7ac19431a76fe36020f92ffefe237.nq.gz
    ├── 2df24714753426a8bdc07126ec570f0581a64eca.nq.gz
    ├── 2e1bc608c6bc79b25fb29b30314d83a11ca9cec6.nq.gz
    ├── 2e7984cb95a1989ba9b1516437e46c768e6c355b.nq.gz
    ├── 2e9a7c1c293ee8abc264b364d0ec940f09d7fc87.nq.gz
    ├── 2ecae48cdb891239c18f53e96dbce02826a4cf6d.nq.gz
    ├── 2f49ad6c6a3cd8bff06371a690e106ad8085a0b5.nq.gz
    ├── 2f98042715ab97ef1c420552b4bc4e228365eb45.nq.gz
    ├── 2fc07cd9a335443969050bfd880b3ae9fa669195.nq.gz
    ├── 2fd502539c3b47fa20933c88737e35b14287432e.nq.gz
    ├── 2fee9f4502b2cde11c7aa0fb62b5988453fd01c0.nq.gz
    ├── 305e8e60501a17bcfb2c15a05774374ec0988ab6.nq.gz
    ├── 3113adc1ab250257f3a9187ade76aefe735001cc.nq.gz
    ├── 3163544b95fe3361214e2b9cd5b89200aba55725.nq.gz
    ├── 3211c085a7416bcc9c93f114d16ed5610c881da7.nq.gz
    ├── 3212781363bac9093e9d3d2239e234cd09f178ca.nq.gz
    ├── 32bbbc6249522926d540a06208de3fb5ca3c44b5.nq.gz
    ├── 32dd3db4eac9458890823a2170432a03c62a5736.nq.gz
    ├── 32e200f1defcbdcc3d2d13f0800fd42ae2e2d058.nq.gz
    ├── 338501511c29199ec114db241459a1fb2cc9384c.nq.gz
    ├── 33b77da597a1d1dfe99f4dc8e2be2bd2cfdae06b.nq.gz
    ├── 33cf714e0dd462fc4ee1f6fa14846fc3539e2c48.nq.gz
    ├── 340d66bf69474922781b2467b296f03e66415b70.nq.gz
    ├── 34412202f14d0723a77faa1be201e640cd479413.nq.gz
    ├── 349372067bd3b3e6b3ac73eb0fa45ca62f553c10.nq.gz
    ├── 34f5a6e8205ca539a87d4a2ee5de6bcbed01500d.nq.gz
    ├── 3516f09b9c797fc9c57a6902cf6f4eadf1e6aedc.nq.gz
    ├── 357d890b9d83c1ee0ec47fa78d40a9b49bc19f12.nq.gz
    ├── 3587a71dca394fae9e3a4e5efbe0a96f3e575468.nq.gz
    ├── 35a6b14b5792c63db13f58208810a9eb54eff8ee.nq.gz
    ├── 35f46e66c292b4aba911092bf2579c7b6e876f5d.nq.gz
    ├── 360d4a2e70c96a1c540c3cffcbc4ce4030070436.nq.gz
    ├── 36205b1935f51267df72b053cd95e007b6f4a8d1.nq.gz
    ├── 365f02b6e0fe01c7f904e4f435ea2a756a262c9b.nq.gz
    ├── 366f3ebb6ecce906d1f31ed55c1b75bc064743d9.nq.gz
    ├── 36a3183866ce2095915189c2b2e1bdf7618a1043.nq.gz
    ├── 36bf5c313c58fb0660ffe9aebbe30e6612af8765.nq.gz
    ├── 370f47579dd256ff1cdfaffd828a109805547b19.nq.gz
    ├── 376b783ce17a14b2e630b58b108b134194b59aa9.nq.gz
    ├── 377a10d20c1d0ca318eead0a293c6b376e771d0d.nq.gz
    └── 37b3009f0ce7c3b02652535cad9d117be9fe26e2.nq.gz

9 directories, 200 files
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

[import-js/eslint-plugin-import](https://github.com/import-js/eslint-plugin-import)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
