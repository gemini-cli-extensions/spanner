# Changelog

## [0.3.2](https://github.com/gemini-cli-extensions/spanner/compare/0.3.1...0.3.2) (2026-07-10)


### Features

* **auth:** Implement MCP auth tool-level scopes validation ([mcp-toolbox#​3049](https://redirect.github.com/googleapis/mcp-toolbox/issues/3049)) ([c528985](https://redirect.github.com/googleapis/mcp-toolbox/commit/c528985149060adb648f85b5486391bd72d6727e)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **auth/google:** Require audience or clientId for mcpEnabled ([mcp-toolbox#​3450](https://redirect.github.com/googleapis/mcp-toolbox/issues/3450)) ([59f7b6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/59f7b6e8eaceffca042cb7e2f2b6e5e9284b6bc3)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **ci:** Add support for windows/arm64 binary distribution ([mcp-toolbox#​3231](https://redirect.github.com/googleapis/mcp-toolbox/issues/3231)) ([10abf3b](https://redirect.github.com/googleapis/mcp-toolbox/commit/10abf3b9e195a03f535e3807b7df9883899ef7c0)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **datalineage:** Add Data Lineage integration ([mcp-toolbox#​3285](https://redirect.github.com/googleapis/mcp-toolbox/issues/3285)) ([19353c3](https://redirect.github.com/googleapis/mcp-toolbox/commit/19353c37e17ab1f3599cafa04337a32a7baec1c3)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **looker:** Propagate client IP from incoming MCP requests to downstream SDK calls ([mcp-toolbox#​3253](https://redirect.github.com/googleapis/mcp-toolbox/issues/3253)) ([75da6c2](https://redirect.github.com/googleapis/mcp-toolbox/commit/75da6c21dd29d7e8e70eac1b747e3946097e7459)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **mcp:** Add URL parameter binding for HTTP transport ([mcp-toolbox#​3112](https://redirect.github.com/googleapis/mcp-toolbox/issues/3112)) ([0cc7b37](https://redirect.github.com/googleapis/mcp-toolbox/commit/0cc7b37b733b6a99dad5281af4024b26d730106a)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **release:** Add digital signature to Toolbox binaries ([mcp-toolbox#​3528](https://redirect.github.com/googleapis/mcp-toolbox/issues/3528)) ([3f0f0af](https://redirect.github.com/googleapis/mcp-toolbox/commit/3f0f0af29007929b01e95ee2caef4fd2015d5f12)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **scylladb:** Adding support for ScyllaDB source and tool ([mcp-toolbox#​3119](https://redirect.github.com/googleapis/mcp-toolbox/issues/3119)) ([2dada83](https://redirect.github.com/googleapis/mcp-toolbox/commit/2dada8306c8737e445c4f8cd3d213b72713c1834)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server:** Add support for toolset filtering in prebuilt CLI flag ([mcp-toolbox#​3245](https://redirect.github.com/googleapis/mcp-toolbox/issues/3245)) ([7cc4f65](https://redirect.github.com/googleapis/mcp-toolbox/commit/7cc4f65a8e767e0da37cf21f0ff2568b38d32b8e)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server:** Ignore unknown tools at startup with `--ignore-unknown-tools` flag ([mcp-toolbox#​3353](https://redirect.github.com/googleapis/mcp-toolbox/issues/3353)) ([5f0304f](https://redirect.github.com/googleapis/mcp-toolbox/commit/5f0304f71231cce322ab2a3e458af07b392a06fc)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **skills:** Generate skills offline without live source connections ([mcp-toolbox#​3388](https://redirect.github.com/googleapis/mcp-toolbox/issues/3388)) ([4c860b6](https://redirect.github.com/googleapis/mcp-toolbox/commit/4c860b66b03f0ebf86205e73cd8521ad90ccebe4)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **skills:** Tolerate missing env vars during offline skills-generate ([mcp-toolbox#​3399](https://redirect.github.com/googleapis/mcp-toolbox/issues/3399)) ([ea5d3e5](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea5d3e5b9e60bf808e10d21b522954d76f7741b6)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **tools:** Decouple tool initialization from sources ([mcp-toolbox#​3355](https://redirect.github.com/googleapis/mcp-toolbox/issues/3355)) ([32a24e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/32a24e35b5bf107bcf5e89af2a9b7af3740747ee)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **tools/spanner-search-catalog:** Implement search\_catalog tool ([mcp-toolbox#​3140](https://redirect.github.com/googleapis/mcp-toolbox/issues/3140)) ([defc086](https://redirect.github.com/googleapis/mcp-toolbox/commit/defc0860c8876fcd465728ac6ce41de8262ed572)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* Enable per source level flags for sql commenter ([mcp-toolbox#​3465](https://redirect.github.com/googleapis/mcp-toolbox/issues/3465)) ([ecce6b7](https://redirect.github.com/googleapis/mcp-toolbox/commit/ecce6b7bb551b947b0951cd684cce627a4b6cf1b)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* Setup SQLCommenter and allow client metadata  ([mcp-toolbox#​3064](https://redirect.github.com/googleapis/mcp-toolbox/issues/3064)) ([9f1f9b3](https://redirect.github.com/googleapis/mcp-toolbox/commit/9f1f9b321dcd05cce55dbff1bbaebfc44a4c9907)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* Support MCP 2026 draft specs ([mcp-toolbox#​3544](https://redirect.github.com/googleapis/mcp-toolbox/issues/3544)) ([d12eaa8](https://redirect.github.com/googleapis/mcp-toolbox/commit/d12eaa856bad70b49ba2b7b9f2882cffbf81220f)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))


### Bug Fixes

* **auth:** Separate Google and Generic MCP OAuth verification ([mcp-toolbox#​3341](https://redirect.github.com/googleapis/mcp-toolbox/issues/3341)) ([dfd66ee](https://redirect.github.com/googleapis/mcp-toolbox/commit/dfd66ee7de6fe9750d932d30bf3b67a2f4d2a176)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **auth/dataplex:** Fix failing source with service account credentials ([mcp-toolbox#​3369](https://redirect.github.com/googleapis/mcp-toolbox/issues/3369)) ([ba4deef](https://redirect.github.com/googleapis/mcp-toolbox/commit/ba4deef140358e5876d73d355d664f629f7aeccc)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **auth/generic:** Enforce issuer presence in opaque token validation ([mcp-toolbox#​3360](https://redirect.github.com/googleapis/mcp-toolbox/issues/3360)) ([1d8df0d](https://redirect.github.com/googleapis/mcp-toolbox/commit/1d8df0df590383ba56091b6e4d7c37ab7d7d9749)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **auth/generic:** Fix generic auth expiration field and integration with `authRequired` ([mcp-toolbox#​3251](https://redirect.github.com/googleapis/mcp-toolbox/issues/3251)) ([f4d16c0](https://redirect.github.com/googleapis/mcp-toolbox/commit/f4d16c09b12c4d3297a9aedca706c9830382a4e3)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **bigquery:** Wire maximumBytesBilled into prebuilt config ([mcp-toolbox#​3385](https://redirect.github.com/googleapis/mcp-toolbox/issues/3385)) ([4abbf6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/4abbf6e82cc4af4c1903d9143337c965987475a9)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **config:** Add doc/line context to parse errors ([mcp-toolbox#​2957](https://redirect.github.com/googleapis/mcp-toolbox/issues/2957)) ([4b097da](https://redirect.github.com/googleapis/mcp-toolbox/commit/4b097daa2143817e55a9e557e8c1dea054bfc7b8)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **mcp:** Support annotations and metadata within Tools to earlier MCP schemas ([mcp-toolbox#​3300](https://redirect.github.com/googleapis/mcp-toolbox/issues/3300)) ([9a88c72](https://redirect.github.com/googleapis/mcp-toolbox/commit/9a88c72792563e4868c82a4f3be55e6af25c1477)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **npm:** Source binary version from cmd/version.txt ([mcp-toolbox#​3417](https://redirect.github.com/googleapis/mcp-toolbox/issues/3417)) ([6ffbdec](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ffbdecaea98db5c16dc9eeca8fb73e4bbc48102)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **oracle:** Remove trailing semicolons from prebuilt tools ([mcp-toolbox#​3215](https://redirect.github.com/googleapis/mcp-toolbox/issues/3215)) ([fcad02d](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcad02de73ffe9c6ecf29572f0f92674aacbe493)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **prebuilt/alloydb-omni:** Require password env var explicitly ([mcp-toolbox#​3398](https://redirect.github.com/googleapis/mcp-toolbox/issues/3398)) ([fcbe3e7](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcbe3e70d3d4e671e97e424187dba907d7c5b10b)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server:** Fail if MCP auth is enabled together with enable-api ([mcp-toolbox#​3435](https://redirect.github.com/googleapis/mcp-toolbox/issues/3435)) ([a6ff910](https://redirect.github.com/googleapis/mcp-toolbox/commit/a6ff910a602adece11f0a6581d6211e5927f7182)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server:** Return errors instead of panicking in InitializeConfigs ([mcp-toolbox#​3397](https://redirect.github.com/googleapis/mcp-toolbox/issues/3397)) ([f48b01d](https://redirect.github.com/googleapis/mcp-toolbox/commit/f48b01dc1775e4583a06689a2e67fb06e5dd3c68)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server:** Return null id for batch request rejection ([mcp-toolbox#​3333](https://redirect.github.com/googleapis/mcp-toolbox/issues/3333)) ([0b18d58](https://redirect.github.com/googleapis/mcp-toolbox/commit/0b18d58aea131baceb1c70f300879de8ecdf569e)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **server/auth:** Centralize tool scopes validation ([mcp-toolbox#​3335](https://redirect.github.com/googleapis/mcp-toolbox/issues/3335)) ([adce4ab](https://redirect.github.com/googleapis/mcp-toolbox/commit/adce4abb27327aae4e9736581df7a544b55c939e)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **telemetry:** Allow GCP project override ([mcp-toolbox#​2960](https://redirect.github.com/googleapis/mcp-toolbox/issues/2960)) ([3c83ba5](https://redirect.github.com/googleapis/mcp-toolbox/commit/3c83ba5ab1d2ab38369e0b5c47396fabf6ecabef)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **tool/spanner-sql,tool/spanner-execute-sql:** Use read-only annotations when readOnly is set ([mcp-toolbox#​3338](https://redirect.github.com/googleapis/mcp-toolbox/issues/3338)) ([8bde0ec](https://redirect.github.com/googleapis/mcp-toolbox/commit/8bde0ec08f8bf455f319523b4faacf32bdbc65ff)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* **tools:** Initialize query result slices to empty array ([mcp-toolbox#​3250](https://redirect.github.com/googleapis/mcp-toolbox/issues/3250)) ([60ddf48](https://redirect.github.com/googleapis/mcp-toolbox/commit/60ddf487468bfd11c7f9346f16a33a8986f89f84)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* Bound MCP HTTP body size ([mcp-toolbox#​3216](https://redirect.github.com/googleapis/mcp-toolbox/issues/3216)) ([d4f4342](https://redirect.github.com/googleapis/mcp-toolbox/commit/d4f434251392fb597779a90a12c63d21533ea187)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))
* Escape delimiter characters in applyEscape to prevent SQL injection ([mcp-toolbox#​2811](https://redirect.github.com/googleapis/mcp-toolbox/issues/2811)) ([932519a](https://redirect.github.com/googleapis/mcp-toolbox/commit/932519a9551861bf5f18787dc43b20d06350343f)) ([49be417](https://github.com/gemini-cli-extensions/spanner/commit/49be417d6a5451e0f244733f5da7f5be2029caa7))

## [0.3.1](https://github.com/gemini-cli-extensions/spanner/compare/0.3.0...0.3.1) (2026-05-07)


### Features

* Add support for HTTPS/TLS listener ([mcp-toolbox#​3126](https://redirect.github.com/googleapis/mcp-toolbox/issues/3126)) ([8bc385d](https://redirect.github.com/googleapis/mcp-toolbox/commit/8bc385d7d6fd9ed2ad13503d9feb503de0b512b1)) ([0e97032](https://github.com/gemini-cli-extensions/spanner/commit/0e97032c469f14e58e177d1c523e94cb2217df51))


### Bug Fixes

* **mcp:** Implement router-level logger injection for MCP auth ([mcp-toolbox#​3067](https://redirect.github.com/googleapis/mcp-toolbox/issues/3067)) ([ccc7cf5](https://redirect.github.com/googleapis/mcp-toolbox/commit/ccc7cf5ee8a1bacb6b57faf41ae5a1cc3da5299e)) ([0e97032](https://github.com/gemini-cli-extensions/spanner/commit/0e97032c469f14e58e177d1c523e94cb2217df51))
* Allow converting string literal block with list ([mcp-toolbox#​3050](https://redirect.github.com/googleapis/mcp-toolbox/issues/3050)) ([36ab2a9](https://redirect.github.com/googleapis/mcp-toolbox/commit/36ab2a98f9f2d03c27eea389d2281bfc4581ffa1)), closes [mcp-toolbox#​3023](https://redirect.github.com/googleapis/mcp-toolbox/issues/3023) ([0e97032](https://github.com/gemini-cli-extensions/spanner/commit/0e97032c469f14e58e177d1c523e94cb2217df51))
* Prevent test.db from being created during unit tests ([mcp-toolbox#​3042](https://redirect.github.com/googleapis/mcp-toolbox/issues/3042)) ([d10d2ca](https://redirect.github.com/googleapis/mcp-toolbox/commit/d10d2caeb7c9eda7d17d6dbd9f63363b2bc23a7a)) ([0e97032](https://github.com/gemini-cli-extensions/spanner/commit/0e97032c469f14e58e177d1c523e94cb2217df51))
* Remove hardcoded \* allowed origin for sse ([mcp-toolbox#​3054](https://redirect.github.com/googleapis/mcp-toolbox/issues/3054)) ([c4c7bd9](https://redirect.github.com/googleapis/mcp-toolbox/commit/c4c7bd917e686de68e2be866cfe3872c3439efae)) ([0e97032](https://github.com/gemini-cli-extensions/spanner/commit/0e97032c469f14e58e177d1c523e94cb2217df51))

## [0.3.0](https://github.com/gemini-cli-extensions/spanner/compare/0.2.6...0.3.0) (2026-04-15)


### ⚠ BREAKING CHANGES

* add support for skills ([#105](https://github.com/gemini-cli-extensions/spanner/issues/105)) ([9b89c1f](https://github.com/gemini-cli-extensions/spanner/commit/9b89c1fed5d36dfd65ce7d0bfbe9a455ee90d4a8))
* update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968))

### Features

* **source/spanner:** Restructure prebuilt toolsets ([mcp-toolbox#​2641](https://redirect.github.com/googleapis/mcp-toolbox/issues/2641)) ([ea2b698](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea2b698b03517c400bbaef27f56c4d3abead8b2c)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** Attach user agent metadata for generated skill ([mcp-toolbox#​2697](https://redirect.github.com/googleapis/mcp-toolbox/issues/2697)) ([9598a6a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9598a6a32597b9c9abdb0f20c06d86a01b0d011f)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skill:** Update skill generation logic ([mcp-toolbox#​2646](https://redirect.github.com/googleapis/mcp-toolbox/issues/2646)) ([c233eee](https://redirect.github.com/googleapis/mcp-toolbox/commit/c233eee98cd9621526cb286245f3874f5bd6e7da)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4)) ([mcp-toolbox#​2733](https://redirect.github.com/googleapis/mcp-toolbox/issues/2733)) ([5b85c65](https://redirect.github.com/googleapis/mcp-toolbox/commit/5b85c65960dba9bfaf4cadca6d44532a153976e1)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add additional-notes flag to generate skills command ([mcp-toolbox#​2696](https://redirect.github.com/googleapis/mcp-toolbox/issues/2696)) ([73bf962](https://redirect.github.com/googleapis/mcp-toolbox/commit/73bf962459b76872f748248bb5e289be232a30b6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add Claude Code support to generated scripts ([mcp-toolbox#​2966](https://redirect.github.com/googleapis/mcp-toolbox/issues/2966)) ([a1609e1](https://redirect.github.com/googleapis/mcp-toolbox/commit/a1609e10a2eaf4ea68eae36acec3eed355b8a052)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Add codex user agent ([mcp-toolbox#​2973](https://redirect.github.com/googleapis/mcp-toolbox/issues/2973)) ([070e939](https://redirect.github.com/googleapis/mcp-toolbox/commit/070e9399c02f088d43175ce6bf343378beb7f584)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Tool invocation via npx ([mcp-toolbox#​2916](https://redirect.github.com/googleapis/mcp-toolbox/issues/2916)) ([377dc5b](https://redirect.github.com/googleapis/mcp-toolbox/commit/377dc5b00145a0044eef39314dd6b0ef5966fcd7)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* add Claude Code plugin config ([#107](https://github.com/gemini-cli-extensions/spanner/issues/107)) ([9e4007d](https://github.com/gemini-cli-extensions/spanner/commit/9e4007d2bf3dd71757e247bdc765f669c2ebd7c4))
* add Codex plugin config ([#109](https://github.com/gemini-cli-extensions/spanner/issues/109)) ([e91ea1b](https://github.com/gemini-cli-extensions/spanner/commit/e91ea1bfd7155eaceda4f82dc630ac5708c7c295))


### Bug Fixes

* **skill:** Fix env variable propagation ([mcp-toolbox#​2645](https://redirect.github.com/googleapis/mcp-toolbox/issues/2645)) ([5271368](https://redirect.github.com/googleapis/mcp-toolbox/commit/52713687208994c423da64333cb0a04fb483f794)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Fix integer parameter parsing through agent skills ([mcp-toolbox#​2847](https://redirect.github.com/googleapis/mcp-toolbox/issues/2847)) ([4564efe](https://redirect.github.com/googleapis/mcp-toolbox/commit/4564efe75436b4081d9f3d1f7c912bc64c13f850)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Fix skill generation template ([mcp-toolbox#​2914](https://redirect.github.com/googleapis/mcp-toolbox/issues/2914)) ([a01a15e](https://redirect.github.com/googleapis/mcp-toolbox/commit/a01a15ed1aa9a83eda8362578fed2e3a3c8dde99)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Improve flag validation and silence unit test output ([mcp-toolbox#​2759](https://redirect.github.com/googleapis/mcp-toolbox/issues/2759)) ([f3da6aa](https://redirect.github.com/googleapis/mcp-toolbox/commit/f3da6aa5e23b609a1ac9ecc098bccea02f2388ab)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))
* **skills:** Prevent empty strings overriding optional env vars in node scripts ([mcp-toolbox#​2963](https://redirect.github.com/googleapis/mcp-toolbox/issues/2963)) ([c52adeb](https://redirect.github.com/googleapis/mcp-toolbox/commit/c52adeba76fc13d0e6e415f6393def0648e478d6)) ([267c8c3](https://github.com/gemini-cli-extensions/spanner/commit/267c8c3ca8641d966778a435f1e2c43b6f7129e4))

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
