# Repolex Knowledge Graph of pyg-team/pytorch_geometric

RDF knowledge graph data for [pyg-team/pytorch_geometric](https://github.com/pyg-team/pytorch_geometric), parsed by [repolex](https://repolex.ai).

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
rlex download pyg-team/pytorch_geometric
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1f2f8642387b6e0563d6aee227c39130746c738
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d1f2f8642387b6e0563d6aee227c39130746c738
│           └── chunk-001.nq.gz
└── blob
    ├── 018f922e27e2b991aa7b210c803e35abd89c9863.nq.gz
    ├── 02347a026709f454521a67f1b9e994138495025c.nq.gz
    ├── 052cb134d866191f78d9abffa4b80cd00673d820.nq.gz
    ├── 061529ab8f8e4556e9012753e8510d5615e4722a.nq.gz
    ├── 0743281a74b5f0997271964b10af4de74fe0e5dc.nq.gz
    ├── 07f570bc78afe2ca85741110a025a69eabd1005e.nq.gz
    ├── 083dcf9683626ab80e856482d071da5bda1aeb8a.nq.gz
    ├── 084bfcc15c9bab808e9e03b3ad947a773bf8c9f4.nq.gz
    ├── 0882bb8cda00331d9c9cfee2cabb731c122b99fa.nq.gz
    ├── 091851022d8cf95303a370313a243746d3d7130e.nq.gz
    ├── 091af1bfc520d2f86984828a7657984404bd4b13.nq.gz
    ├── 095fde3d6756ba6884830b0b9547e7c250f2d795.nq.gz
    ├── 09a873d18a5a572a71f9ba4b6fb1dbc4bf8a0169.nq.gz
    ├── 0ae6618bfe5f371a22d5024be9a83cbadc421cf7.nq.gz
    ├── 0b4b71c12bec8bf9080f954b85449f616aa5d223.nq.gz
    ├── 0ce593be5d39526afa054f5936ea0d8a987782e9.nq.gz
    ├── 0de023708fd873051b2013c1ea6e1c8046590f83.nq.gz
    ├── 0ea8f73ad584bd7a6561f8ce130fd05f1c1c39d2.nq.gz
    ├── 0ec27bf7e05fc852d86632a9044b672c4353eb5f.nq.gz
    ├── 0f722b12323afd2da561fe6fc84d9e5c1a25c31e.nq.gz
    ├── 0fa202c12c0b1634f35b803336e772fe5736d7b6.nq.gz
    ├── 0ffc8a33412055e1ab9906020c8333b00f582215.nq.gz
    ├── 1034e6a9be9b8625257d11d8cb4724cd66267b54.nq.gz
    ├── 10d063648370b0fe401b5d02ded6caa3edb24cfa.nq.gz
    ├── 112ee0362dcfe6a7b4aff4c417fc1c692ed3b7e7.nq.gz
    ├── 126cc71960fc86d05fd80965d9558262bd550872.nq.gz
    ├── 12c9cc3699a3f2153da9fb726e58bd2b2b488ec8.nq.gz
    ├── 12f573306f62614a52f3b44a2c13c9a71385e8dd.nq.gz
    ├── 13750ff5608e98462d33893ce2be73130508ae11.nq.gz
    ├── 13f79c33958e6e66228847146df151924c90b24b.nq.gz
    ├── 1429d557636d191c2875112efa99a33aa5723c78.nq.gz
    ├── 142b973a55af3eb64636c870cf6b928790356203.nq.gz
    ├── 14a3ff0ac9b41115fcf4fd140f9b3507e40f9fd6.nq.gz
    ├── 14ee8f30e14bcdc8e272cd4cc7e303f9e3bae075.nq.gz
    ├── 1585ae0caeb937c2d216d29d84059fffe0969c47.nq.gz
    ├── 15e5256a091f11dbd0a1f55564f1647a283d1db3.nq.gz
    ├── 15fef95ca1baafeee7c85dbc7ba7bee779e41b00.nq.gz
    ├── 167ad18aa367b4338900f4333eb9ae589686caab.nq.gz
    ├── 1701e4ef56ce4e54d8421d2a65cefd575f88dfab.nq.gz
    ├── 1737feaff36f3346b0b57d1d7e5d2890eaa7ef5f.nq.gz
    ├── 177e819f78ce61c070ea63a6f821567f5f0cf297.nq.gz
    ├── 1814c45cf33389c271b0dec53bbfcbd15896c58d.nq.gz
    ├── 182aba1be1da5c3df3c304bd3d1138124b78b470.nq.gz
    ├── 19067d84d30f7e647084c0d51c0e6481064efb7c.nq.gz
    ├── 1984d1928c601d465687aaa627e4d57802c959f6.nq.gz
    ├── 1a4ea4ab7fdb8c01abc3cd4b4a60c8ef095afc9f.nq.gz
    ├── 1a6260294d997b8fad7df5f5d1e6e0932f9b602e.nq.gz
    ├── 1a631eeaaf1f6b3b649a0291cf322e09d703ed7e.nq.gz
    ├── 1adef0199219ed6aee147f8071f028857a7894f5.nq.gz
    ├── 1b1e24ac0971146bd6305a4afd563a21876b07c0.nq.gz
    ├── 1cd8c71babf0093396f2015b90e6f0899aad8d47.nq.gz
    ├── 1e0b091de99afe681d2fb5fe82ddf5a5227ecee0.nq.gz
    ├── 1e16b61fb4f1561cb297788e734044675d69d1b7.nq.gz
    ├── 1e5c4bd0171eababfcee1b3a466e04d254b0128f.nq.gz
    ├── 1ea2bf24cd246689f8fc8765c92b4e08b5f3752f.nq.gz
    ├── 1f5e3b6b33924cace8c8a30f191b05dfdb5f95eb.nq.gz
    ├── 1f7ee570c28c68143439ec470a88a6cd70a770d6.nq.gz
    ├── 1f8c477c1f2ff0bbd87554ef8ee2b5408517d602.nq.gz
    ├── 1f9ebe899c99a76339588995e5c12672f1d74e72.nq.gz
    ├── 2103620974d4090cc0d0266aa3e3a6455ebb8005.nq.gz
    ├── 21c1ab3887c31b4bc78001879434d569aae2bc52.nq.gz
    ├── 21f16fdf9b122c25085e404b4d6cbcae5191284a.nq.gz
    ├── 22d3039f4c8384b1255ed6cfd7cf7c625fcf9856.nq.gz
    ├── 22ff4402ad72e0a056f5a697ea3e558eca2e3b46.nq.gz
    ├── 232976619c2fbe916f33da8305e15a622637fccc.nq.gz
    ├── 247ad2d81395773d75a091b0ba9fa2ed70d5e04e.nq.gz
    ├── 252da6fd213a4dd1ff67483846ef728666461358.nq.gz
    ├── 271429261874271afe22ff1681d41bdaf3dce466.nq.gz
    ├── 27238636ac14f80748d20b042c28e88fe2f331ed.nq.gz
    ├── 283fac627c05a42c2a8bab39c736479854443368.nq.gz
    ├── 28e7ef86ab5341b324ecc537eaeda5d7118f0f33.nq.gz
    ├── 29629f05e5a2438bafdb9ee83d1d5b87a0bb5a11.nq.gz
    ├── 2989e48998d91258fc7d15bca18a41e022163672.nq.gz
    ├── 2a5aff7e839df300b059c42553607084cae7090b.nq.gz
    ├── 2ab84c8b1e41e08a3faa96a7327554bea5016572.nq.gz
    ├── 2aeb1c5a50cc74c9b60fc61d92a364320d5bb31d.nq.gz
    ├── 2b43b6cfc5c6e96e1e715515f5b70ef92554ede2.nq.gz
    ├── 2b49f5944841c9ba082d9e39189f1c45cb5e9c95.nq.gz
    ├── 2c132ca0059b89c3b6cee77fe01200a0c3df8302.nq.gz
    ├── 2c8657aa9bebce72cf9077af7561cec926620b31.nq.gz
    ├── 2e3e584d2c62e70f778cc590ca087ce3173d54ad.nq.gz
    ├── 2ea67e7bbf74f19f3a4ef9145d93e947df4588a6.nq.gz
    ├── 2ec02331f1a732295a692fbc930f0d5d3b9992d1.nq.gz
    ├── 2ef6348f344d91728a2fd67a36d7ecd552d27c12.nq.gz
    ├── 2f616b664531f52c952b2bbba96bebf90f3d3b77.nq.gz
    ├── 31b89c0709f6271547bad28917ec58d60f5dae43.nq.gz
    ├── 31d1e4c7a7af8eea9cf3740971cd78c4f0c80752.nq.gz
    ├── 333fa5e740d1c41c6fe6ebf73f938658503bb46d.nq.gz
    ├── 3395b6097c882276e48f8c33b806623693b2003f.nq.gz
    ├── 33e7c8ad7f8bbb0f2bacc360307aca75552798dc.nq.gz
    ├── 340c1ac9c88c9634218793064385dad5f80cde39.nq.gz
    ├── 340eacb459dc31ef06174dfb7d6b09df90867e7f.nq.gz
    ├── 3504ed5d41d432e9ad32735ee60f8dec089faaa8.nq.gz
    ├── 3588433b4596e57ab17e0f3575d485509b7d0d7a.nq.gz
    ├── 367b1dd66a97177b6f347af07008d31bd389706c.nq.gz
    ├── 36ebf45a9263e0969c6385d8dcd8f58b7adf9b0a.nq.gz
    ├── 378e98d3d9468b4ba749d1e964d92c027a158778.nq.gz
    ├── 383d02d889a3ce6bc0e23529ed227d8fdb1c505c.nq.gz
    ├── 385bb43f2dbeb5ab94f972ca4efe2d558201c6e6.nq.gz
    ├── 38918bb49dafa0f60dd7e6f5d5af9ed95732eeed.nq.gz
    ├── 3a45117741d2e331ab653fa397750e57c9c7adb1.nq.gz
    ├── 3b4275de3daf6e8a3aa46a21e0e8958fde0c23de.nq.gz
    ├── 3b5600cb45bd1980cc90db75c9b7ae0738209aad.nq.gz
    ├── 3c040b93f0fc0eb8acddc73e01448105d8dc6834.nq.gz
    ├── 3c7c609f64bc483c4e3544fa0945b8b845e40f6a.nq.gz
    ├── 3c9d9a4c8b5d9f2d76e614800b035448d9e60807.nq.gz
    ├── 3ce5c160f521779f3c37b35ba4a25e7e599e6a21.nq.gz
    ├── 3dec3f26461b8ae5a88e69b5a65f010a7c85b132.nq.gz
    ├── 3ee0f51a07bc7ac7094398451ae6680f3a4961d3.nq.gz
    ├── 3f2d4cc57f1392d20e9ac514970002f28ade8c74.nq.gz
    ├── 3f65982cfc9edaf23fc8092a92e07d4e0b21c9e8.nq.gz
    ├── 3fa05e7420339fbfc75ff45e1939aa8f87313802.nq.gz
    ├── 40f01d53d984e17952c68c1a3056a200ba6dbf4f.nq.gz
    ├── 41369cbf7a8f68d4a2277011bd6fa42e865b66b4.nq.gz
    ├── 41ac9e465a7445e1f0c6bf50990944f9888879fe.nq.gz
    ├── 41cc29feb20dd62e3cd1108803726f130fc440e0.nq.gz
    ├── 41e71da7b7b5fb2d6d4ea519fbf98ab1a98cb12c.nq.gz
    ├── 42a7a54ede2097ed62b5afe9a236517eab3e86ae.nq.gz
    ├── 43df9dec526399aed75559c2d4bbf3d160d40b6e.nq.gz
    ├── 444efbfd9445c3419d5a89f387dacf6ddd424c0b.nq.gz
    ├── 4502eb7883298136a0b04751d0794677f566d20f.nq.gz
    ├── 45979ac06ba780b44702b932f234eb89c565d2f6.nq.gz
    ├── 45cc9943b655312c43c532339a71fab60bc353fc.nq.gz
    ├── 4636c7750238c0ffe322a4fa428211da4c055772.nq.gz
    ├── 4677d94b0f3c7a56d885c42452a1f0d864d90004.nq.gz
    ├── 46dbe85673b75c7a0d268ce369714b78118288e5.nq.gz
    ├── 471889428d36bd70702b4c2ab9ef2ab5924bf7ff.nq.gz
    ├── 47aeea3349ef1724c6b2dd982f73005693f4a44e.nq.gz
    ├── 483796721f277fe842384b346005c0ba109bc0c7.nq.gz
    ├── 48b8d7bd84333518b4f97170b03343f266343a75.nq.gz
    ├── 4990b6ec6cdb51c0ba2d422ec27449d77981d9d0.nq.gz
    ├── 49d6cc0bccb573133d3ce71b65c88c989e21ef48.nq.gz
    ├── 49eaa30bcd245480d1c9e546d1e418047ef58e64.nq.gz
    ├── 4a16992a308c761a68386964f993b4d4a3d5177c.nq.gz
    ├── 4a32b026dd1d7d2b779b6f0eee85726740b116d2.nq.gz
    ├── 4a73d6ae9075a3b1607d8aa8cf7b5e2b6a9344eb.nq.gz
    ├── 4a87398bfc29d908d24e848d1380ecd92dcd7036.nq.gz
    ├── 4b36bb54527ec159d21890b4e03ca0f61e811b19.nq.gz
    ├── 4b55220f2d2f0dd9d44203ecbf55836e5cf92a23.nq.gz
    ├── 4c9dbf8e79360533dcf1376f3b689636a05f46d7.nq.gz
    ├── 4cb3ea0434d32bb827c4bd949a9cd8441f9af9b6.nq.gz
    ├── 4e4dc5c7a461805c9d780c3b99de8b2de336863e.nq.gz
    ├── 4ed101874e7c8e7bcfcfccd01c4183586706f93e.nq.gz
    ├── 4ed2a42ca849d00b66dc46e6f97e13003bf4d4f1.nq.gz
    ├── 4f10e6d59fc6a4f5c5f323d6d04ca2a5a4b6ee2d.nq.gz
    ├── 4f83934e575a038c17e7a87411f7efc500b9aca2.nq.gz
    ├── 5124fdd42ec4fb14dffea01f5cd01e1bd1b7c89a.nq.gz
    ├── 5156ed9ec881c0aeb9e5fc555baaf448bfa1fe15.nq.gz
    ├── 51c637a88c1d756bc13eae34c55d31f80d3c664f.nq.gz
    ├── 525f5bfc6efceba6c6f301d3d02108532ba9de4e.nq.gz
    ├── 538b56a700f27a439412b81d42c8d4d99801a45a.nq.gz
    ├── 54fc0d08242d0e9e68dc75fb5d15562fb7259bb2.nq.gz
    ├── 551beecb493877147686acd118ee157f832a77f3.nq.gz
    ├── 55283e5a4ad1a3bb2b54b0000755fc33028bc1aa.nq.gz
    ├── 553ebfca8678dd59ea8113a6e6e41bba57a21634.nq.gz
    ├── 562dd74a071085dd766693ff141d5a4397b4e9a2.nq.gz
    ├── 564b4bdab0994c3b2e5802bc21d1495ab4e155e5.nq.gz
    ├── 56930fc4d1509e92a23b5376724899d637deee24.nq.gz
    ├── 5747dfcbe2d8abecfb72209ffc6b08c4a2ac8166.nq.gz
    ├── 57abbfd3daef6aa9bc4ac5bf1dbd120d26ded14f.nq.gz
    ├── 589d8361eb8aa5b4c0994f20f6f362cb1d031839.nq.gz
    ├── 598c7b61936b5d75657bdd2ad59501f98db8458a.nq.gz
    ├── 59d5976a5a0b78b49e3f1da568bcc8d93a265535.nq.gz
    ├── 59d5da75e7419fc094d7ab159298f144156f94ae.nq.gz
    ├── 5a8fc667391d8d92cb31dea873ccab1eb950869d.nq.gz
    ├── 5aca4c20eb5ad65db7667a21a7caa9c5ec8fa85d.nq.gz
    ├── 5aec59e4be645701386d9e050854621fd044b243.nq.gz
    ├── 5b2dd3d9f6500bafa855487c7571ebd139c55daf.nq.gz
    ├── 5bca3fc114843cc4dd3e214c2be6fb9ddc57f025.nq.gz
    ├── 5bed483de7a58246d2fcec15e85bee65ab211640.nq.gz
    ├── 5c0e12b82c9b8e740c76812ab21e30d29087e5e0.nq.gz
    ├── 5c561fb2b8f5b50a46a88c18913324fb7b98cffb.nq.gz
    ├── 5c59515cf8ddce07e15c8d4c7e00c2ebf81a18e4.nq.gz
    ├── 5c9a03065768bbbef03f801920fd5ee5cef7c641.nq.gz
    ├── 5ca5758956e5fc72af80d40125797ec5ef865972.nq.gz
    ├── 5d425663bb8c598722bb69a9d0af850731f0eaa3.nq.gz
    ├── 5dc7b52ee8a58ebd9506c8aa0bc9a4b68aac436b.nq.gz
    ├── 5ec7cc73a0c386f45b1013c66dbd50d9fe23c6df.nq.gz
    ├── 5ef197aeac8e4529031d655efaf511c9c47fb639.nq.gz
    ├── 5f09440d49611011efb5d4c127c82a9284ceab05.nq.gz
    ├── 601a2a91924f4361638651e0fa803f703215a9fa.nq.gz
    ├── 6102e1aff8337894dc889ce32af1efdb8c6e4339.nq.gz
    ├── 6232b938dbfa822f203896f11daa6afb8417a865.nq.gz
    ├── 623a6c944eb84a8d0fb3217f2930f533868e451b.nq.gz
    ├── 62f73e1dcb9300a2d577c6e5c7be02a6e6dc8b90.nq.gz
    ├── 62fff2c60e6da15c6f92238a104f94f457868856.nq.gz
    ├── 633be1a7a181f3ab78103555c50e23640730e8cd.nq.gz
    ├── 63b9c6596f25344a9e0e1561683fb1ec0563d87d.nq.gz
    ├── 63f4e47882d76c5106248501520e6f6c2bd59e7a.nq.gz
    ├── 646279c661b3a951a3f07d0953ceb3cda0444ecb.nq.gz
    ├── 64c97e598665c42f572d61c45d7602537932bcf4.nq.gz
    ├── 655d3625ff2d896b450c3d2df0edd9e441859294.nq.gz
    ├── 6744cde8f9ca5d215c07f8542fb05d78bf59ee5e.nq.gz
    ├── 67b1077b2555e8eac61a5efcb484b91161c87cce.nq.gz
    ├── 67f05d2b1472fa5433211fa71e31756727549f2f.nq.gz
    ├── 68b16435091a1a867d5b48c8a7968f46ca01076a.nq.gz
    ├── 69c6ab55a7bfa67ee2f81f02b687c2670568a5bf.nq.gz
    └── 69e19bd6e9e0bdaa7bff2b61e4fac093e775575e.nq.gz

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

[pyg-team/pytorch_geometric](https://github.com/pyg-team/pytorch_geometric)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
