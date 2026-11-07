# Repolex Knowledge Graph of huggingface/new-model-addition-cwm

RDF knowledge graph data for [huggingface/new-model-addition-cwm](https://github.com/huggingface/new-model-addition-cwm), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/new-model-addition-cwm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5baf598d184ce668c685fc05c53a0a663ab6ef70
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5baf598d184ce668c685fc05c53a0a663ab6ef70
│           └── chunk-001.nq.gz
└── blob
    ├── 004f67291979424d2f51c503a33fe62feaa50087.nq.gz
    ├── 0065cf56b3bf75e176f54bbcec37d1a4efdf6723.nq.gz
    ├── 00ce40e97607ae11acfe2c4ddb93533f0c00ad1f.nq.gz
    ├── 021c6f4aa6529de87c8d83cab1680cfea9bcdce8.nq.gz
    ├── 04566ab34ab090fe9bb453196b04ee83f73b411d.nq.gz
    ├── 057d59f569ac54fa3662befb96f1202410af06cd.nq.gz
    ├── 0593e9940bd68413bae0977228d986d02aa62dab.nq.gz
    ├── 05d2813f98ca744684d532393572862f39aca065.nq.gz
    ├── 05e855d333b59996aa850becf43bc4f1d77eec48.nq.gz
    ├── 069978176865993816d46d842a93a372d0858df6.nq.gz
    ├── 069fa7b776e23277995738d3ba2425d2d7536ccd.nq.gz
    ├── 06d5e03437eff93bd3a27ea60ddd7a40ca68eeb0.nq.gz
    ├── 0779236859e7b36d87fa516576f5efa541201558.nq.gz
    ├── 0876da773805837c0776b6c7bbfa804590429342.nq.gz
    ├── 08aaac3617ff65b5f9e8306bb04ea454e20be5ee.nq.gz
    ├── 08b74d14ca871a7752b61fb71f08b7a7886d80f7.nq.gz
    ├── 0a5dbc3ce4c84e179d028b297ba1d3b75c249c3c.nq.gz
    ├── 0ba200936ebe02e62a894beaf9a23eb39e5ed746.nq.gz
    ├── 0c4eca628db764e8a10abca08a435913d0e641ae.nq.gz
    ├── 0cf54b7884848784ac7e94062be8da91f4fedcf7.nq.gz
    ├── 0d56840436c246f6b509d89c1e0af8ae1a155238.nq.gz
    ├── 0d5c936e8adca36cf69054ec7d7952ccb0125f75.nq.gz
    ├── 0dab34123de4fe9496a1dd72e8cfa784482d51c8.nq.gz
    ├── 0e0df9b66ef34f7d847ba8a50d2cdd3d27eec333.nq.gz
    ├── 0e4732f270629ae9587ace02e644a8ba1d7963b1.nq.gz
    ├── 0fa68184c88526ccc793a336a64bce798f6d7759.nq.gz
    ├── 1023aa7c589dab5b249c6dff3d61e4d6e523eda8.nq.gz
    ├── 10a00a869915fcdb9a047426e58ed88409a3fc7e.nq.gz
    ├── 10aacdb74ef40038f06e9693a29f6b94dd373ee3.nq.gz
    ├── 116316199b1efb549c38e9bd13309bdce18f242c.nq.gz
    ├── 128f83c23ad721dd925ff65073aed7154887de8e.nq.gz
    ├── 12b774ed88622da9ec721dd3dbdd08381d589c16.nq.gz
    ├── 13dca4845c132b1e735bcc34d2df2b81111cc97d.nq.gz
    ├── 1490f78436e5a7ed1e7f94f4703d17640f4b5f5e.nq.gz
    ├── 15e96c57669f6830d569d523644f931a6c5ed89a.nq.gz
    ├── 15fb457331811c6b8cfce23a53766057e816a058.nq.gz
    ├── 165a2b887423d8eba9ff78376eb4a6e11108c095.nq.gz
    ├── 165b00b6129c89279f7da6b25505ca340029bed3.nq.gz
    ├── 166c7955c1b5a91839a5b72ecdfb5c4b48660813.nq.gz
    ├── 16b064c98f7e6a9ed4fe72d7149fb867380c904d.nq.gz
    ├── 17281403af4d5ef5d2d1a5aef4e42a527a5bd67b.nq.gz
    ├── 17c79e8aeeed547655d59eb8543333b0b7425319.nq.gz
    ├── 17e5e305c610344d02793384d6265325003c5408.nq.gz
    ├── 180ad756dc8839ff090abf7eb21453d7658d6be4.nq.gz
    ├── 1840d7e4ed7a1eddc15eea8bc5a255bc6e7c2e55.nq.gz
    ├── 188db542f7c01f00396e64184e376bfea13744ec.nq.gz
    ├── 19051f55b683a55d23634c41f013ca97e763bdbf.nq.gz
    ├── 19090ab12477d9389cbc69804ef43180ce0e1f66.nq.gz
    ├── 1929a01c34d94726d1e820924933cec1412a02d6.nq.gz
    ├── 19823ba4ac734a9cb36c54ff1e32ef5c64453b12.nq.gz
    ├── 1a48062cb5c1d489156f3ac4f90650b6aa594da7.nq.gz
    ├── 1a52661fe20faec0836230d401b511e438704d5d.nq.gz
    ├── 1b6c03ee1032bdfd6fe08f4992642229c05b6add.nq.gz
    ├── 1c125dac4f32c2c2ab71303272582028bea27fc8.nq.gz
    ├── 1c22dfd71a7b6a2c139f55dbd442a1c86762484f.nq.gz
    ├── 1c2bbcb6e4a8ad7572f8ad507a71bde18d981711.nq.gz
    ├── 1c3df45b2a3b14a72b36362c87833298be8fce48.nq.gz
    ├── 1c57c68e8c87d41cc2ee46fd077fd2e05e48ee0d.nq.gz
    ├── 1c58e4e6cdd0d0a8c87b9b94ca896c87970b5654.nq.gz
    ├── 1cd5da18c64545a1ae5ba6a343c7a79951487fd5.nq.gz
    ├── 1d155cd1fb9ddbc0f4c70b16faeba261b75f573f.nq.gz
    ├── 1dd32b42687e8279cef4a6fe5a22a650226d75ff.nq.gz
    ├── 1e4271960726fd34235e8377fd42d438bda1d35c.nq.gz
    ├── 1e4d63f9b9a068512471043d57cb7a21b45818b9.nq.gz
    ├── 1e76608b1520e0678e082a84a5e227a603d05748.nq.gz
    ├── 1e913ba34576d8479e34bbce47d5f01a4d5eb01e.nq.gz
    ├── 1eb1078b6aceb27128001eac79e0161396cc0387.nq.gz
    ├── 1ebd50519c180421b729bce0c95a5b83554fcd8d.nq.gz
    ├── 1f7ee3051bfcd563bc31eb5333c97835444d38a4.nq.gz
    ├── 20144c8ffc401fc9e4dd25c5736cab463f7479f1.nq.gz
    ├── 205f268fe6a5fccc2226c2ec1be3dca30f197d67.nq.gz
    ├── 20727620269813cdcd23bc1d4c88e699adc97dc8.nq.gz
    ├── 2095e9877c2c7759dd1d8668b65ecbb2f980ca30.nq.gz
    ├── 20c0def10fd144af8b100a9d1889b1c074113df6.nq.gz
    ├── 23cda58bfe723d7674a51e6c3f478f207464f639.nq.gz
    ├── 24142232241f9a7a20b8fa081f63bae70b0abcd2.nq.gz
    ├── 241fe66f25e35708dbea00f2614c109e33bb6d0b.nq.gz
    ├── 24401835c7fc62d916802c90aa7d9fede3e9db42.nq.gz
    ├── 24f0f37a8c8e0b54fec2999d2372d04d8855274a.nq.gz
    ├── 252f41f214ea5645d5ec86b49419c76d7e924d0c.nq.gz
    ├── 2546b51279021fc680fa844558ee67c62ed3bff5.nq.gz
    ├── 260a82e5143e157301f4d590270504e6205ae9ea.nq.gz
    ├── 26f2053a93aa71c890599c2f060123aa4b4fb672.nq.gz
    ├── 271bea0549311a42288c0dccf03137e14fb864a0.nq.gz
    ├── 27de691c845369b97805fb53a8e509b7e948b386.nq.gz
    ├── 282202cb79e16246fd50d36d41e8fd30c6724b15.nq.gz
    ├── 28b21dffabef2dfaba083f3e5da84856a6106224.nq.gz
    ├── 28e4fb68726902f715b73b572d658daf08e5b9fd.nq.gz
    ├── 297470a2e17190d216c106d78e66da233fa718bf.nq.gz
    ├── 29c23a356509d828ed98160a3bc0f9ebf8118b21.nq.gz
    ├── 2ae32af0441cf40788633ef123fd82688e886c01.nq.gz
    ├── 2b3964d194bed041987c6236b5c60bfcf3b7caf4.nq.gz
    ├── 2b6030f6d7924584d4cce8bb043e6249c40ae136.nq.gz
    ├── 2ba1b8ecede3f963d4b7a9811ca7cf32da7694ca.nq.gz
    ├── 2c2e50fc560d99d095a848b95dedd338282d554b.nq.gz
    ├── 2c5ec3600599e6ad3f2708880ce35a9ec9a626e1.nq.gz
    ├── 2df4da02555a068a4f0ab16d78f6ea6b1b5ecf96.nq.gz
    ├── 2e197e5b321e0c2ffa83e0b3adabc22a414ed1c5.nq.gz
    ├── 2e521e2b7b4af83b4a95df0c3e28f17f957ba411.nq.gz
    ├── 30261966b3d0df0081a62d4821e97a1d8faf22c8.nq.gz
    ├── 30419f8b7efa318f44c3d48c13edb221795b5e3a.nq.gz
    ├── 316ab3b1f5b9689ae0acacd2fc354ea34ad5f679.nq.gz
    ├── 316b3c4343234803c0dacefbbab771ecc62dd010.nq.gz
    ├── 31c284f8d5f722b9436fd92404e4c297a4beac34.nq.gz
    ├── 324a8cfb1c29e01bcaccae84e8c5a566f2d5dfbb.nq.gz
    ├── 325703f782c0163ee738e0bd78295318285d3b33.nq.gz
    ├── 3258fda73e69cec3ce330da5718255b9ec3d585e.nq.gz
    ├── 325e0f65b47cad8116615b78c4579e48e63c0408.nq.gz
    ├── 336e67ce42b6b433e79fc6a701d39fc5d035d4f3.nq.gz
    ├── 33d156ec93fe0221f6fd115568d900fc6cdd034b.nq.gz
    ├── 3406309aa3251997d5bbf3790014508277349c59.nq.gz
    ├── 345f86283d1293727ac2d421e06637e35267ac56.nq.gz
    ├── 349766fe575e80db7ae02d5947b471a9c8642d7a.nq.gz
    ├── 357b8b2c368198ed1365279d85872561257d43c9.nq.gz
    ├── 35df3b5a3f054e70a6d861a27428ff9abe362893.nq.gz
    ├── 368a301ec3ab4a36c6a21086e4ba748aad242a5e.nq.gz
    ├── 370055c90ea03de383a8ca0aaa6461bd7e83a1cd.nq.gz
    ├── 3773ad4174d1a44095e3f75bcbd6cc8a440a24a4.nq.gz
    ├── 3798640026d5a069f81d8fac6663d12d0e0d289a.nq.gz
    ├── 3818946d031325e3f7b74ffdf7a519a471317faf.nq.gz
    ├── 386b288ff0a628623f30e5a8a0a9ccdb9dc8e6a6.nq.gz
    ├── 398514cafe3f6b3a669e0ec44d52a9754a3baf87.nq.gz
    ├── 39da9e27d32ef389204dca1585a2de5ae30a9244.nq.gz
    ├── 3a7e2b5ff9537d46ac5409adba76efd185ee10d7.nq.gz
    ├── 3aafeaf50c09455cffeecb3776eb3598c8ceccf2.nq.gz
    ├── 3b7c4d0eb2280f7ded1f67a226f55be642c9758e.nq.gz
    ├── 3c1fdb8b0a8c05e3ca341814ff08ba6ba4ba9e9c.nq.gz
    ├── 3cd809cba6a28454b7eec12b319e6c962ee71291.nq.gz
    ├── 3d2fdb2ba34c839dee6795481022551fa15f8545.nq.gz
    ├── 3d362bacf491ea32dcbc89e7b8bba4d9ae1a9261.nq.gz
    ├── 3de9a19d1bd73e52b5f9819bbe67cc816bc10503.nq.gz
    ├── 3e828ca9e0b56151de256497ad3c19d918d3c8ed.nq.gz
    ├── 3ea84ed3394160fc2d7ffa1f85c4caabc920aff3.nq.gz
    ├── 3f317a063b3acf701768b0dbe7b165b5f41e847e.nq.gz
    ├── 3fcbd936af9b6522fb70a2fabef27da3c0c64114.nq.gz
    ├── 400c023e02849140eaed44fd4e5ad811337a79e8.nq.gz
    ├── 4033ef319ff8cbec11f6c29d075e59b741710513.nq.gz
    ├── 409e51000588ac419e19cb532ed609d0aa90bfe4.nq.gz
    ├── 41a0bdb7e5d18119032fcc25f4f3f0c23e555cf3.nq.gz
    ├── 432622f1595d1a0d8bb1b3c9b9774b7d1e387d3e.nq.gz
    ├── 435324721d8678125f9df61c9d550b6fadc8cf8c.nq.gz
    ├── 43576e815d074845360010d61f81bf525b6853d0.nq.gz
    ├── 44a154a614c56d51a3905ca9ede6d6a3b7b4c170.nq.gz
    ├── 45333859e8fdf61b7973b1e8c03389a5509c5946.nq.gz
    ├── 45de422adc437d60edba6b07e589a9cfa95567db.nq.gz
    ├── 4665c2961b3f23ddd22d129776c5f6bd91e80e5d.nq.gz
    ├── 4834f66816672aaa6784a4b3464ac7d090f88ead.nq.gz
    ├── 4871311e114b0d1ea9d2d3314956a5d1b371035a.nq.gz
    ├── 48a329608039b1a4a96ac1f99c20ee427f845cd9.nq.gz
    ├── 48bfda0a4d85df742f11dc6ef9dab73a48f6b270.nq.gz
    ├── 49666ab1154d33c0d06930c01aa6d43b4a963d74.nq.gz
    ├── 49b640a6468037b9ec168a4c728085bed188ab58.nq.gz
    ├── 49d0dfb85b015f89d72bce7857204fdf2c57fe3e.nq.gz
    ├── 49d879e2bd3a58d3e1a95c125b0146fe576c2eea.nq.gz
    ├── 4a25eff859e719f8cba28ebaaa963e2c9cbd119f.nq.gz
    ├── 4ab85689ab1559aa25cae26c05fc463ef1ce3c27.nq.gz
    ├── 4c1bad6da2537ecf2f0c7aabeb5799449295e81e.nq.gz
    ├── 4e205906ea709ee2c20f25b0bf6f4fa66ab1f4a4.nq.gz
    ├── 5096298affd1115880e09ccf5cc4ea00dfde4717.nq.gz
    ├── 50cec9c153d31b0c4ad3cbce45646896e5ab17ac.nq.gz
    ├── 5158bafa395ab49a96d00ef97d87f44e6e48c03f.nq.gz
    ├── 5277f1c4e13bcf9c7ef0a57e79a093916777cf77.nq.gz
    ├── 529f9074649a4475164b9afa49cbd7063578e506.nq.gz
    ├── 52fee59ae9b96d14361a771cbc58089d5e5811f2.nq.gz
    ├── 538ec08dc1ca2b159b9b3c7d7e6d239603c91b7e.nq.gz
    ├── 54568caac37a9e55ba360cb0560af5c89e128067.nq.gz
    ├── 54d0d9e2c3997c4b2865b5a47e7b64c39ed40b68.nq.gz
    ├── 559bb858ca85cff6d970d24add1b8d6463666af8.nq.gz
    ├── 5622ab252fed8ec7c52ddda0a28e41d7fa35f635.nq.gz
    ├── 5668772c2636763f8c546f1c11846af4f2737cb2.nq.gz
    ├── 566cb31fea78a52c0c7cfaa3e509437c55dab578.nq.gz
    ├── 5822cad62017c8e390806afb3bb67101e4568837.nq.gz
    ├── 5823883c6cb8ba35c0964d62d4f32e5ca3d24d64.nq.gz
    ├── 594524c8dd1ca2c17c3fef98792958be663e4fb6.nq.gz
    ├── 594eb84b02a1ec0a46e75c779dc307e955e5b234.nq.gz
    ├── 59e84daea5c50ba3a2e7062e6cf8a895517bbf27.nq.gz
    ├── 5a072214406c20a6a13e3da258a26bc0bf609487.nq.gz
    ├── 5b0d7e406993cc0cc8c06bd3b41ba3f9d8ddd610.nq.gz
    ├── 5b814856c63f44ef8c082726ae19285a4faec26c.nq.gz
    ├── 5cdb326098a30020f0d9d2cc4c083090bce70d5a.nq.gz
    ├── 5e0e461862a8b32be02330e7c5897f030f04a137.nq.gz
    ├── 5f04d3857cb8c14113cb0a8b38ac03b076c18bfc.nq.gz
    ├── 5f850211d7ca9ffb379dcb1f309d2a881dd9b4c7.nq.gz
    ├── 5fe48bc47e7bc481aba8a265336ec9721d83d83a.nq.gz
    ├── 60128f882dd3d3d018c3f10888ee1528f17bf074.nq.gz
    ├── 60560217d27c6775c2b7c975748fe3ff4d6dad9f.nq.gz
    ├── 60e546f321209f38b1a02e984b98ddb8e6590dc1.nq.gz
    ├── 61fa18153902888c7537e73a6c9bf4bb9ae9ff80.nq.gz
    ├── 62f9d3a3c083b606cce34cd35cf02442860be541.nq.gz
    ├── 630f6238e76e949fdeb3c34e74168adb6591c251.nq.gz
    ├── 63d7f49bf33302e97192540ccd3fa102e883222c.nq.gz
    ├── 6455a27d642b11908dc1e24c58d59ce28f154850.nq.gz
    ├── 65286eb8428d43a41c722cb094cd854991d321da.nq.gz
    ├── 662b4b495fe4e31f1cc2cc5fe3f1a2deaa3ea194.nq.gz
    ├── 6721ba69a92521147026c1f11357b44afabc8567.nq.gz
    ├── 67cdcbbf488a53abcd51db017de963cea48ea647.nq.gz
    ├── 68367464c3cf75a093c0469a3e44c65e4a3bbd27.nq.gz
    └── 686528002b09c9689d66a057ed55eb1a43b0d256.nq.gz

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

[huggingface/new-model-addition-cwm](https://github.com/huggingface/new-model-addition-cwm)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
