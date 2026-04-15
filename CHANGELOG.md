# Changelog

## [0.3.0](https://github.com/gemini-cli-extensions/spanner/compare/0.2.6...0.3.0) (2026-04-15)


### ⚠ BREAKING CHANGES

* update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968))
* release upgraded docsite ([mcp-toolbox#​2831](https://redirect.github.com/googleapis/mcp-toolbox/issues/2831))
* **http:** sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654))
* add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846))
* remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806))
* **source/spanner:** restructure prebuilt toolsets ([mcp-toolbox#​2641](https://redirect.github.com/googleapis/mcp-toolbox/issues/2641))
* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566))

### Features

* **auth:** Add generic `authService` type for MCP ([mcp-toolbox#​2619](https://redirect.github.com/googleapis/mcp-toolbox/issues/2619)) ([f6678f8](https://redirect.github.com/googleapis/mcp-toolbox/commit/f6678f8e29aa3346f4f73ce33cec37b4753d6947)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **auth:** Add Protected Resource Metadata endpoint ([mcp-toolbox#​2698](https://redirect.github.com/googleapis/mcp-toolbox/issues/2698)) ([b53dcf2](https://redirect.github.com/googleapis/mcp-toolbox/commit/b53dcf20694599f8b961c501a532bd122630b6f4)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **auth:** Support manual PRM override ([mcp-toolbox#​2717](https://redirect.github.com/googleapis/mcp-toolbox/issues/2717)) ([283e4e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/283e4e33172571e4b20fa6a3ea0cfc632a565e6a)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **auth:** Support opaque token validation for `generic` authService ([mcp-toolbox#​2944](https://redirect.github.com/googleapis/mcp-toolbox/issues/2944)) ([c924701](https://redirect.github.com/googleapis/mcp-toolbox/commit/c924701adede95877594423d78b7ae72fe0b9c82)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **bigquery:** Add conversational analytics tools for Data Agents ([mcp-toolbox#​2517](https://redirect.github.com/googleapis/mcp-toolbox/issues/2517)) ([2490a4b](https://redirect.github.com/googleapis/mcp-toolbox/commit/2490a4b4fb3c9232270f6f4347b8556d2d6e0390)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **cli:** Add migrate subcommand ([mcp-toolbox#​2679](https://redirect.github.com/googleapis/mcp-toolbox/issues/2679)) ([12171f7](https://redirect.github.com/googleapis/mcp-toolbox/commit/12171f7a02bcd34ce647db10abdb79bb2dac7ace)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **cli:** Add serve subcommand ([mcp-toolbox#​2550](https://redirect.github.com/googleapis/mcp-toolbox/issues/2550)) ([1e2c7c7](https://redirect.github.com/googleapis/mcp-toolbox/commit/1e2c7c7804c67bebf5e2ee9b67c6feb6f05292fd)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **cloudsqlpg:** Run `SELECT 1` after successful connection attempt ([mcp-toolbox#​2997](https://redirect.github.com/googleapis/mcp-toolbox/issues/2997)) ([6ed9700](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ed9700e15f08b31e65eb0afa605f4a8ea937e66)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **dataplex:** Add support for lookup context tool. ([mcp-toolbox#​2744](https://redirect.github.com/googleapis/mcp-toolbox/issues/2744)) ([facb69d](https://redirect.github.com/googleapis/mcp-toolbox/commit/facb69d01fe0c7ff9e2e1c40804dd00762e508a6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **dataproc:** Add dataproc source and list/get clusters/jobs tools ([mcp-toolbox#​2407](https://redirect.github.com/googleapis/mcp-toolbox/issues/2407)) ([cc05e57](https://redirect.github.com/googleapis/mcp-toolbox/commit/cc05e5745d1c25a6088702b827cd098250164b7e)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **embeddingModel:** Add Backend API selection fields ([mcp-toolbox#​2592](https://redirect.github.com/googleapis/mcp-toolbox/issues/2592)) ([912aa9e](https://redirect.github.com/googleapis/mcp-toolbox/commit/912aa9edd7bc3ce932828003fbd67d1a3b9c2348)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **http:** sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** Attach user agent metadata for generated skill ([mcp-toolbox#​2697](https://redirect.github.com/googleapis/mcp-toolbox/issues/2697)) ([9598a6a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9598a6a32597b9c9abdb0f20c06d86a01b0d011f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** One skill per toolset ([mcp-toolbox#​2733](https://redirect.github.com/googleapis/mcp-toolbox/issues/2733)) ([5b85c65](https://redirect.github.com/googleapis/mcp-toolbox/commit/5b85c65960dba9bfaf4cadca6d44532a153976e1)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** Update skill generation logic ([mcp-toolbox#​2646](https://redirect.github.com/googleapis/mcp-toolbox/issues/2646)) ([c233eee](https://redirect.github.com/googleapis/mcp-toolbox/commit/c233eee98cd9621526cb286245f3874f5bd6e7da)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add additional-notes flag to generate skills command ([mcp-toolbox#​2696](https://redirect.github.com/googleapis/mcp-toolbox/issues/2696)) ([73bf962](https://redirect.github.com/googleapis/mcp-toolbox/commit/73bf962459b76872f748248bb5e289be232a30b6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add Claude Code support to generated scripts ([mcp-toolbox#​2966](https://redirect.github.com/googleapis/mcp-toolbox/issues/2966)) ([a1609e1](https://redirect.github.com/googleapis/mcp-toolbox/commit/a1609e10a2eaf4ea68eae36acec3eed355b8a052)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add codex user agent ([mcp-toolbox#​2973](https://redirect.github.com/googleapis/mcp-toolbox/issues/2973)) ([070e939](https://redirect.github.com/googleapis/mcp-toolbox/commit/070e9399c02f088d43175ce6bf343378beb7f584)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Tool invocation via npx ([mcp-toolbox#​2916](https://redirect.github.com/googleapis/mcp-toolbox/issues/2916)) ([377dc5b](https://redirect.github.com/googleapis/mcp-toolbox/commit/377dc5b00145a0044eef39314dd6b0ef5966fcd7)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **source/spanner:** restructure prebuilt toolsets ([mcp-toolbox#​2641](https://redirect.github.com/googleapis/mcp-toolbox/issues/2641)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **source/spanner:** Restructure prebuilt toolsets ([mcp-toolbox#​2641](https://redirect.github.com/googleapis/mcp-toolbox/issues/2641)) ([ea2b698](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea2b698b03517c400bbaef27f56c4d3abead8b2c)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ui:** Make tool list panel resizable ([mcp-toolbox#​2253](https://redirect.github.com/googleapis/mcp-toolbox/issues/2253)) ([276cf60](https://redirect.github.com/googleapis/mcp-toolbox/commit/276cf604a2bb41861639ed6881557e38dd97a614)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ui:** Update to use `/mcp` endpoint ([mcp-toolbox#​2829](https://redirect.github.com/googleapis/mcp-toolbox/issues/2829)) ([c3059c2](https://redirect.github.com/googleapis/mcp-toolbox/commit/c3059c233502a1e99abb4d87e4b9bfe7c6ea7a4a)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846)) ([7a070da](https://redirect.github.com/googleapis/mcp-toolbox/commit/7a070dae4f1833671649ea605f36659675d402a9)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* add Claude Code plugin config ([#107](https://github.com/gemini-cli-extensions/spanner/issues/107)) ([9e4007d](https://github.com/gemini-cli-extensions/spanner/commit/9e4007d2bf3dd71757e247bdc765f669c2ebd7c4))
* add Codex plugin config ([#109](https://github.com/gemini-cli-extensions/spanner/issues/109)) ([e91ea1b](https://github.com/gemini-cli-extensions/spanner/commit/e91ea1bfd7155eaceda4f82dc630ac5708c7c295))
* Add MCP tool annotations to all remaining tools ([mcp-toolbox#​2221](https://redirect.github.com/googleapis/mcp-toolbox/issues/2221)) ([ea09db9](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea09db90ce3ed78225dc246cedefd30064a88fad)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Add polling system to dynamic reloading ([mcp-toolbox#​2466](https://redirect.github.com/googleapis/mcp-toolbox/issues/2466)) ([fcaac9b](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcaac9bb957226ee3db1baea24330f337ba88ab7)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* add support for skills ([#105](https://github.com/gemini-cli-extensions/spanner/issues/105)) ([9b89c1f](https://github.com/gemini-cli-extensions/spanner/commit/9b89c1fed5d36dfd65ce7d0bfbe9a455ee90d4a8))
* Add user agent to embeddings generation ([mcp-toolbox#​2572](https://redirect.github.com/googleapis/mcp-toolbox/issues/2572)) ([287251a](https://redirect.github.com/googleapis/mcp-toolbox/commit/287251a0cfed4d24617e5d0d957026a94f65d820)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Added basic template for sdks doc migrate ([mcp-toolbox#​1961](https://redirect.github.com/googleapis/mcp-toolbox/issues/1961)) ([87f2eaf](https://redirect.github.com/googleapis/mcp-toolbox/commit/87f2eaf79cdecca7b939151e1543eccf2f812a69)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* release upgraded docsite ([mcp-toolbox#​2831](https://redirect.github.com/googleapis/mcp-toolbox/issues/2831)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806)) ([ab64c95](https://redirect.github.com/googleapis/mcp-toolbox/commit/ab64c9514a467d92a4547eda5a4ecdd08f86b0c9)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([131d764](https://redirect.github.com/googleapis/mcp-toolbox/commit/131d764f895c14908e29914b3c0c273d91a2654f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))


### Bug Fixes

* **bigquery:** Add impersonateServiceAccount to prebuilt config ([mcp-toolbox#​2770](https://redirect.github.com/googleapis/mcp-toolbox/issues/2770)) ([9c3a748](https://redirect.github.com/googleapis/mcp-toolbox/commit/9c3a748de43eb588586f22590ff74bd433b24d68)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ci:** Add path for forked PR unit test runs ([mcp-toolbox#​2540](https://redirect.github.com/googleapis/mcp-toolbox/issues/2540)) ([04dd2a7](https://redirect.github.com/googleapis/mcp-toolbox/commit/04dd2a77603c7babf01da724dfb77808e3f25fe5)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ci:** Implement conditional sharding logic in integration tests ([mcp-toolbox#​2763](https://redirect.github.com/googleapis/mcp-toolbox/issues/2763)) ([1528d7c](https://redirect.github.com/googleapis/mcp-toolbox/commit/1528d7c38dfaa30bdecbe59c79ba926fa6d18356)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ci:** Remove search index generation from preview deployment workflow ([mcp-toolbox#​2859](https://redirect.github.com/googleapis/mcp-toolbox/issues/2859)) ([f8891b8](https://redirect.github.com/googleapis/mcp-toolbox/commit/f8891b82fcaaef240e1031cd9f784749d91d4210)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **cloudloggingadmin:** Increase log injesting time and add auth test ([mcp-toolbox#​2772](https://redirect.github.com/googleapis/mcp-toolbox/issues/2772)) ([50b4457](https://redirect.github.com/googleapis/mcp-toolbox/commit/50b4457095ec4ac881b3b12719da24d35141f65d)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **docs:** Skip empty folders in pagination & reduce PR comment noise ([mcp-toolbox#​2853](https://redirect.github.com/googleapis/mcp-toolbox/issues/2853)) ([9ebd93a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9ebd93a8ecb9bae673aa77a859803629fc7a4e1d)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **docs/adk:** Resolve dependency duplication ([mcp-toolbox#​2418](https://redirect.github.com/googleapis/mcp-toolbox/issues/2418)) ([4d44abb](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d44abb4638926ca50b0fa4dcf10a03e7fab657f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **docs/langchain:** Fix core at 0.3.0 and align compatible dependencies ([mcp-toolbox#​2426](https://redirect.github.com/googleapis/mcp-toolbox/issues/2426)) ([36edfd3](https://redirect.github.com/googleapis/mcp-toolbox/commit/36edfd3d506e839c092d04cbca1799b5ebc38160)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **http:** Sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654)) ([5bef954](https://redirect.github.com/googleapis/mcp-toolbox/commit/5bef954507c8e23b6c9b0eb2551265e4be32b452)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **knowledge-catalog:** Rename dataplex to knowledge-catalog across docs ([mcp-toolbox#​3039](https://redirect.github.com/googleapis/mcp-toolbox/pull/3039)) ([45c05e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/24ce6ce3bc6468d2b4b11a86b90ea223daa7e6cf)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **looker:** Convert configuration yaml to flat format ([mcp-toolbox#​3022](https://redirect.github.com/googleapis/mcp-toolbox/issues/3022)) ([45c05e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/45c05e37eac867c5a444d950bc51fdf1b1b687ea)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **mcp:** Guard nil SSE session lookup and return 400 for missing session ([mcp-toolbox#​2681](https://redirect.github.com/googleapis/mcp-toolbox/issues/2681)) ([f66189f](https://redirect.github.com/googleapis/mcp-toolbox/commit/f66189fe43cb711da3a041fa31edbacd7bbc7153)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **oracle:** Enable DML operations and resolve incorrect array type error ([mcp-toolbox#​2323](https://redirect.github.com/googleapis/mcp-toolbox/issues/2323)) ([72146a4](https://redirect.github.com/googleapis/mcp-toolbox/commit/72146a4b1605bcdd3e1038106bfb1f899e677e39)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **oracle:** Normalize encoded proxy usernames in go-ora DSN ([mcp-toolbox#​2469](https://redirect.github.com/googleapis/mcp-toolbox/issues/2469)) ([b1333cd](https://redirect.github.com/googleapis/mcp-toolbox/commit/b1333cd27117655f8ab09f222721e14bea74b487)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **oracle:** Update oracle-execute-sql tool interface to match source signature ([mcp-toolbox#​2627](https://redirect.github.com/googleapis/mcp-toolbox/issues/2627)) ([81699a3](https://redirect.github.com/googleapis/mcp-toolbox/commit/81699a375b7e5af37945f4124aa4c5f2a1a9f7a6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **postgres:** Update execute-sql tool to avoid multi-statements parameter ([mcp-toolbox#​2707](https://redirect.github.com/googleapis/mcp-toolbox/issues/2707)) ([58bc772](https://redirect.github.com/googleapis/mcp-toolbox/commit/58bc772f882f0d9e00f403e73fbec812dd8a03ac)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **quickstart:** Robust tool lookup and modernize dependencies in Python samples ([mcp-toolbox#​2863](https://redirect.github.com/googleapis/mcp-toolbox/issues/2863)) ([4c0845d](https://redirect.github.com/googleapis/mcp-toolbox/commit/4c0845dc9081d79046dea5f28a032d531faff40f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **server/mcp:** Guard nil dereference in sseManager.get ([mcp-toolbox#​2557](https://redirect.github.com/googleapis/mcp-toolbox/issues/2557)) ([e534196](https://redirect.github.com/googleapis/mcp-toolbox/commit/e534196303c2b8d9b6e599ac25add337e6fc9b8f)), closes [mcp-toolbox#​2548](https://redirect.github.com/googleapis/mcp-toolbox/issues/2548) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **server/mcp:** Scope defer span.End inside loop iteration ([mcp-toolbox#​2558](https://redirect.github.com/googleapis/mcp-toolbox/issues/2558)) ([c88a62d](https://redirect.github.com/googleapis/mcp-toolbox/commit/c88a62dcf4c16118ae706cc43d18cad827e7496d)), closes [mcp-toolbox#​2549](https://redirect.github.com/googleapis/mcp-toolbox/issues/2549) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** Fix env variable propagation ([mcp-toolbox#​2645](https://redirect.github.com/googleapis/mcp-toolbox/issues/2645)) ([5271368](https://redirect.github.com/googleapis/mcp-toolbox/commit/52713687208994c423da64333cb0a04fb483f794)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Fix integer parameter parsing through agent skills ([mcp-toolbox#​2847](https://redirect.github.com/googleapis/mcp-toolbox/issues/2847)) ([4564efe](https://redirect.github.com/googleapis/mcp-toolbox/commit/4564efe75436b4081d9f3d1f7c912bc64c13f850)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Fix skill generation template ([mcp-toolbox#​2914](https://redirect.github.com/googleapis/mcp-toolbox/issues/2914)) ([a01a15e](https://redirect.github.com/googleapis/mcp-toolbox/commit/a01a15ed1aa9a83eda8362578fed2e3a3c8dde99)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Improve flag validation and silence unit test output ([mcp-toolbox#​2759](https://redirect.github.com/googleapis/mcp-toolbox/issues/2759)) ([f3da6aa](https://redirect.github.com/googleapis/mcp-toolbox/commit/f3da6aa5e23b609a1ac9ecc098bccea02f2388ab)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Prevent empty strings overriding optional env vars in node scripts ([mcp-toolbox#​2963](https://redirect.github.com/googleapis/mcp-toolbox/issues/2963)) ([c52adeb](https://redirect.github.com/googleapis/mcp-toolbox/commit/c52adeba76fc13d0e6e415f6393def0648e478d6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **telemetry:** Histogram buckets from OTel standard to MCP standards ([mcp-toolbox#​2729](https://redirect.github.com/googleapis/mcp-toolbox/issues/2729)) ([87cd4a0](https://redirect.github.com/googleapis/mcp-toolbox/commit/87cd4a0bf48605225ef25ca554cc787def976d11)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **test:** Address flaky healthcare integration test run ([mcp-toolbox#​2742](https://redirect.github.com/googleapis/mcp-toolbox/issues/2742)) ([9590821](https://redirect.github.com/googleapis/mcp-toolbox/commit/9590821bc7d86c5cbacd29b21d4f85b427a87db4)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **tests:** Resolve LlamaIndex dependency conflict in JS quickstart ([mcp-toolbox#​2597](https://redirect.github.com/googleapis/mcp-toolbox/issues/2597)) ([ac11f5a](https://redirect.github.com/googleapis/mcp-toolbox/commit/ac11f5af9c7bcf228d667e1b8e08b5dc49ad91a0)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **tests/bigquery:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2547](https://redirect.github.com/googleapis/mcp-toolbox/issues/2547)) ([479d842](https://redirect.github.com/googleapis/mcp-toolbox/commit/479d8424046406d50af02b0602e6bac58aea534f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **tests/Bigtable:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2880](https://redirect.github.com/googleapis/mcp-toolbox/issues/2880)) ([a769f15](https://redirect.github.com/googleapis/mcp-toolbox/commit/a769f15c3ab8d631198546909a6dd1f09446e6b0)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **tests/postgres:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2377](https://redirect.github.com/googleapis/mcp-toolbox/issues/2377)) ([8a96fb1](https://redirect.github.com/googleapis/mcp-toolbox/commit/8a96fb1a8874baa3688e566f3dea8a0912fcf2df)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **tests/postgres:** Restore list\_schemas test and implement dynamic owner ([mcp-toolbox#​2521](https://redirect.github.com/googleapis/mcp-toolbox/issues/2521)) ([7041e79](https://redirect.github.com/googleapis/mcp-toolbox/commit/7041e797347f337d6f7f44ca051ae31acd58babe)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **ui:** Remove module from script ([mcp-toolbox#​2703](https://redirect.github.com/googleapis/mcp-toolbox/issues/2703)) ([6943ab6](https://redirect.github.com/googleapis/mcp-toolbox/commit/6943ab6839d21da7b6a4241700c7891c6f4a9b2c)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Deflake alloydb omni ([mcp-toolbox#​2431](https://redirect.github.com/googleapis/mcp-toolbox/issues/2431)) ([62b8309](https://redirect.github.com/googleapis/mcp-toolbox/commit/62b830987d65c3573214d04e50742476097ee9e9)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Enforce required validation for explicit null parameter values ([mcp-toolbox#​2519](https://redirect.github.com/googleapis/mcp-toolbox/issues/2519)) ([d5e9512](https://redirect.github.com/googleapis/mcp-toolbox/commit/d5e9512a237e658f9b9127fdd8c174ec023c3310)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Improve list locks integration test for postgres ([mcp-toolbox#​2279](https://redirect.github.com/googleapis/mcp-toolbox/issues/2279)) ([d9ebe5d](https://redirect.github.com/googleapis/mcp-toolbox/commit/d9ebe5d4bf1b7ca04cae47386b36c38ca5b77b8a)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Return AllParams for GetParameter() for tools with templateParameter([mcp-toolbox#​2734](https://redirect.github.com/googleapis/mcp-toolbox/issues/2734)) ([bfd7ba6](https://redirect.github.com/googleapis/mcp-toolbox/commit/bfd7ba601a52294fa71623d88af71bd0288bf887)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Update error for ConvertConfig function ([mcp-toolbox#​2993](https://redirect.github.com/googleapis/mcp-toolbox/issues/2993)) ([62bdabb](https://redirect.github.com/googleapis/mcp-toolbox/commit/62bdabb512d7875d2760c1cd8eb331221b58a09c)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968)) ([3aae809](https://redirect.github.com/googleapis/mcp-toolbox/commit/3aae8097f1bda00e41667fb41c02094167c96ace)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* Update toolset attributes naming ([mcp-toolbox#​2554](https://redirect.github.com/googleapis/mcp-toolbox/issues/2554)) ([3d6ae4e](https://redirect.github.com/googleapis/mcp-toolbox/commit/3d6ae4eeaf5acfbde83374a244573edd8fc9012b)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))

## [0.2.6](https://github.com/gemini-cli-extensions/spanner/compare/0.2.5...0.2.6) (2026-02-18)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.27.0 ([#83](https://github.com/gemini-cli-extensions/spanner/issues/83)) ([0a7c828](https://github.com/gemini-cli-extensions/spanner/commit/0a7c828af00ac9aa79f690975ea279c4799ab8be))

## [0.2.5](https://github.com/gemini-cli-extensions/spanner/compare/0.2.4...0.2.5) (2026-01-29)


### Features

* add dialect and configuration instructions ([#79](https://github.com/gemini-cli-extensions/spanner/issues/79)) ([a1dbc8c](https://github.com/gemini-cli-extensions/spanner/commit/a1dbc8c284fed0d3d1b3a0212f8399f66a46885d))

## [0.2.4](https://github.com/gemini-cli-extensions/spanner/compare/0.2.3...0.2.4) (2026-01-27)


### Features

* add Configuration settings ([#73](https://github.com/gemini-cli-extensions/spanner/issues/73)) ([5c7cf28](https://github.com/gemini-cli-extensions/spanner/commit/5c7cf28d7b4773741e39a57c2b67b9b267e78e92))

## [0.2.3](https://github.com/gemini-cli-extensions/spanner/compare/0.2.2...0.2.3) (2026-01-26)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.26.0 ([#75](https://github.com/gemini-cli-extensions/spanner/issues/75)) ([7b8248b](https://github.com/gemini-cli-extensions/spanner/commit/7b8248b2754a1d8cf7315d4064830d2ecf9ccb5d))

## [0.2.2](https://github.com/gemini-cli-extensions/spanner/compare/0.2.1...0.2.2) (2026-01-15)


### Bug Fixes

* **spanner:** Move list graphs validation to runtime ([mcp-toolbox#​2154](https://redirect.github.com/googleapis/mcp-toolbox/issues/2154)) ([914b3ee](https://redirect.github.com/googleapis/mcp-toolbox/commit/914b3eefda40a650efe552d245369e007277dab5)) ([39e9e56](https://github.com/gemini-cli-extensions/spanner/commit/39e9e562a65351dd04dd165477a48222eea9d430))
* List tables tools null fix ([mcp-toolbox#​2107](https://redirect.github.com/googleapis/mcp-toolbox/issues/2107)) ([2b45266](https://redirect.github.com/googleapis/mcp-toolbox/commit/2b452665983154041d4cd0ed7d82532e4af682eb)) ([39e9e56](https://github.com/gemini-cli-extensions/spanner/commit/39e9e562a65351dd04dd165477a48222eea9d430))

## [0.2.1](https://github.com/gemini-cli-extensions/spanner/compare/0.2.0...0.2.1) (2025-12-05)


### Features

* **tools/spanner:** Add spanner list graphs to prebuiltconfigs ([mcp-toolbox#​2056](https://redirect.github.com/googleapis/mcp-toolbox/issues/2056)) ([0e7fbf4](https://redirect.github.com/googleapis/mcp-toolbox/commit/0e7fbf465c488397aa9d8cab2e55165fff4eb53c)) ([4737df6](https://github.com/gemini-cli-extensions/spanner/commit/4737df6ccecaa3a9e1485aca14257527c2d80cb3))

## [0.2.0](https://github.com/gemini-cli-extensions/spanner/compare/0.1.1...0.2.0) (2025-11-26)


### ⚠ BREAKING CHANGES

* **tools/spanner-list-tables:** Unmarshal `object_details` json string into map to make response have nested json ([mcp-toolbox#​1894](https://redirect.github.com/googleapis/mcp-toolbox/issues/1894)) ([446d62a](https://redirect.github.com/googleapis/mcp-toolbox/commit/446d62acd995d5128f52e9db254dd1c7138227c6))

### Features

* **tools/spanner-list-tables:** Unmarshal `object_details` json string into map to make response have nested json ([mcp-toolbox#​1894](https://redirect.github.com/googleapis/mcp-toolbox/issues/1894)) ([446d62a](https://redirect.github.com/googleapis/mcp-toolbox/commit/446d62acd995d5128f52e9db254dd1c7138227c6)) ([5215916](https://github.com/gemini-cli-extensions/spanner/commit/52159168bde85bda8e6094780362083cd6b929eb))

## [0.1.1](https://github.com/gemini-cli-extensions/spanner/compare/0.1.0...0.1.1) (2025-09-30)


### Features

* additional instructions for the context file ([#32](https://github.com/gemini-cli-extensions/spanner/issues/32)) ([8a7e5a7](https://github.com/gemini-cli-extensions/spanner/commit/8a7e5a749c8280ab24b14298f5b8dfc8158e56b3))
* standardize mcp server names ([#30](https://github.com/gemini-cli-extensions/spanner/issues/30)) ([0ae42f0](https://github.com/gemini-cli-extensions/spanner/commit/0ae42f0ae65e43d156b429a52798416a866ef869))

## 0.1.0 (2025-09-21)


### Features

* add Spanner Extension ([#16](https://github.com/gemini-cli-extensions/spanner/issues/16)) ([1d12c5f](https://github.com/gemini-cli-extensions/spanner/commit/1d12c5fecb92330e55938951a448d99fe05d0599))
