# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

# 0.8.0 (2024-06-23)


### Bug Fixes

* **AudioPlayer:** enter Buffering state for resources that are not yet readable ([#98](https://github.com/discordjs/voice/issues/98)) ([686ef19](https://github.com/discordjs/voice/commit/686ef198d1e6a56061c263b7073d396e03e572af))
* **AudioPlayer:** strengthen error event type ([cf933cb](https://github.com/discordjs/voice/commit/cf933cbbbdce99c48fe30fb39cf485e10ac09bb8))
* **AudioResource:** improve accuracy of function signatures ([#113](https://github.com/discordjs/voice/issues/113)) ([e0fd0f7](https://github.com/discordjs/voice/commit/e0fd0f7e048ca33fcdf27bcebaf2b8069003ceb5))
* conditionally apply banner only to esm build ([8c4e8c4](https://github.com/discordjs/voice/commit/8c4e8c4ba5b9013a90de0238a7f2771e9113a62d))
* **DataStore:** stop audio cycles when all players removed ([bdc9162](https://github.com/discordjs/voice/commit/bdc9162bc3847fd7c9d5577c7ca15c4c1c249ee0))
* **esm:** resolve esm imports ([#229](https://github.com/discordjs/voice/issues/229)) ([616f2bc](https://github.com/discordjs/voice/commit/616f2bcfde47e55ac7b09f4faaa07f15d78c11a5))
* **Examples:** change guildID to guildId ([#155](https://github.com/discordjs/voice/issues/155)) ([09c67b1](https://github.com/discordjs/voice/commit/09c67b1dc8927c51e1939c8ec392fbe2bec06990))
* **Examples:** destroy discord.js v12 adapter less readily ([#160](https://github.com/discordjs/voice/issues/160)) ([60307f8](https://github.com/discordjs/voice/commit/60307f87e8a5b0fd47f293641bcb3471c5267000))
* **Examples:** youtube-dl-exec args ([bddd035](https://github.com/discordjs/voice/commit/bddd03525a8414d902b67da9e201d23ac8da65b9))
* fixed type bundling for real ([#151](https://github.com/discordjs/voice/issues/151)) ([6b5d0c3](https://github.com/discordjs/voice/commit/6b5d0c37a1e80754aae58eca248ac683dc0b9eb9))
* **Networking:** assign debug function earlier ([5ff44eb](https://github.com/discordjs/voice/commit/5ff44eb0288e58d16a4458e9e4f374c3fa01818c))
* postbuild script ([644af95](https://github.com/discordjs/voice/commit/644af9579f02724c489514f482640b8413d2c305))
* prism imports for ems ([0bfd6d5](https://github.com/discordjs/voice/commit/0bfd6d5247f89cfc125e7645e9fb7ebfed94bb2f))
* prism imports for esm ([9222dbf](https://github.com/discordjs/voice/commit/9222dbfedd8bfaeb679133dfa41330ea75a03a70))
* **TypeScript:** bundle types at prepublishOnly ([#149](https://github.com/discordjs/voice/issues/149)) ([e439133](https://github.com/discordjs/voice/commit/e439133792599247963c91b75c5a54a4395b2d8d))
* **Util:** increase search depth for dependencies ([5643a08](https://github.com/discordjs/voice/commit/5643a080c3208b1dec487516b5548084a2480a4b))
* **VoiceConnection:** correctly compare subscriptions in state transition ([#28](https://github.com/discordjs/voice/issues/28)) ([0181c95](https://github.com/discordjs/voice/commit/0181c95c2af07bc13a95470a35e8a93777be75b9))
* **VoiceConnection:** disconnect method now actually disconnects ([#140](https://github.com/discordjs/voice/issues/140)) ([a021000](https://github.com/discordjs/voice/commit/a021000f5c243c7f531ef3a8d840d3a864c9862f))
* **VoiceConnection:** handle nullable endpoint in voice server update payload ([#100](https://github.com/discordjs/voice/issues/100)) ([0798520](https://github.com/discordjs/voice/commit/07985202444be0395307b7cb1cfb6d827770ea3f))
* **VoiceConnection:** improve recoverability ([#58](https://github.com/discordjs/voice/issues/58)) ([ddce711](https://github.com/discordjs/voice/commit/ddce7118c68e6bfd5acc0921239ed7454355a442))
* **VoiceConnection:** stuck on signalling state when rejoining the same channel on ready state ([#139](https://github.com/discordjs/voice/issues/139)) ([daf9e29](https://github.com/discordjs/voice/commit/daf9e29a9d8c2f1327f5385136aab5927881635c))
* **VoiceConnection:** unsubscribing + moving channels ([#35](https://github.com/discordjs/voice/issues/35)) ([05f0818](https://github.com/discordjs/voice/commit/05f08187857852e6da93fb74df78a3f21de66c4a))
* **VoiceUDPSocket:** catch socket close failure ([57e6de0](https://github.com/discordjs/voice/commit/57e6de0d5aa843a27ac2506b269065d154d69916))


### Features

* add ping stats ([#77](https://github.com/discordjs/voice/issues/77)) ([b5385fc](https://github.com/discordjs/voice/commit/b5385fcf3386e4f42e8857e50a4d6e11a8e9c4d0))
* allow adapter creator to call a destroy method ([#79](https://github.com/discordjs/voice/issues/79)) ([7420576](https://github.com/discordjs/voice/commit/74205764a1b65c256d2426d4c1d1d405b913b76c))
* allow awaitable void event listeners, fix VoiceConnection disconnected states ([#121](https://github.com/discordjs/voice/issues/121)) ([c57a038](https://github.com/discordjs/voice/commit/c57a03831beac6c7c47aa70b11a1ae6c251127ca))
* **AudioPlayer:** add maxMissedFrames behaviour ([#59](https://github.com/discordjs/voice/issues/59)) ([bec7192](https://github.com/discordjs/voice/commit/bec71922905b4ca50cee289ffaa48a66e1ec8e48))
* **AudioPlayer:** allow playing streams that are not yet readable ([#22](https://github.com/discordjs/voice/issues/22)) ([1451b02](https://github.com/discordjs/voice/commit/1451b026ef958c12bd36ee822d1c2100c0cd2119))
* **AudioPlayer:** make createAudioPlayer options optional ([#39](https://github.com/discordjs/voice/issues/39)) ([4ee68b0](https://github.com/discordjs/voice/commit/4ee68b0d92e9b8fd3772ff4dea3d409ca5451fbc))
* **AudioPlayer:** propagate stream errors ([#32](https://github.com/discordjs/voice/issues/32)) ([c08bf00](https://github.com/discordjs/voice/commit/c08bf008f66215fa85eb3bb49288282dd6511d07))
* **AudioPlayer:** throw when playing ended audio ([#20](https://github.com/discordjs/voice/issues/20)) ([79c2a3e](https://github.com/discordjs/voice/commit/79c2a3ef0ab7f389f71d0845a35800b6a7d49794))
* **AudioResource:** add encoder property, fix type for metadata ([#110](https://github.com/discordjs/voice/issues/110)) ([3ff2983](https://github.com/discordjs/voice/commit/3ff2983c6149bc620294c8dfab9bac889465c422))
* **AudioResource:** make createAudioResource options optional ([#37](https://github.com/discordjs/voice/issues/37)) ([15acb62](https://github.com/discordjs/voice/commit/15acb62311af6547ae937f2df22b376604d5892c))
* createAudioResource now infers stream type ([#85](https://github.com/discordjs/voice/issues/85)) ([e7fbe3c](https://github.com/discordjs/voice/commit/e7fbe3c23421220c937fed3258a9c4be0271efa8))
* debugging utilities ([#13](https://github.com/discordjs/voice/issues/13)) ([a8ece2b](https://github.com/discordjs/voice/commit/a8ece2b7651e7fd9b8df93e387591c740c593244))
* entersState helper function ([#42](https://github.com/discordjs/voice/issues/42)) ([e94fc09](https://github.com/discordjs/voice/commit/e94fc099a53c9d45b16b3cd877267cfa73dc9b01))
* export all public types ([#24](https://github.com/discordjs/voice/issues/24)) ([1ef70dc](https://github.com/discordjs/voice/commit/1ef70dc10554b6e923d1bcf956853d0b85d3d8bc))
* export some types so they render in docs ([#211](https://github.com/discordjs/voice/issues/211)) ([a6dad47](https://github.com/discordjs/voice/commit/a6dad4781fb479d22d7bff99888e42368d6d6411))
* implement voice receive ([#87](https://github.com/discordjs/voice/issues/87)) ([8f7a7bf](https://github.com/discordjs/voice/commit/8f7a7bf85e01d990d8fd5803563bbc34d6dac421))
* initial prototype ([9515f95](https://github.com/discordjs/voice/commit/9515f9553421721576b0bf7d77f02d2d01a87729))
* reason in VoiceConnectionDisconnectedState ([7a2f53f](https://github.com/discordjs/voice/commit/7a2f53f0f4250e98718987012e141cc1e5758853))
* **Secretbox:** throw fallback error when no encryption package installed ([#130](https://github.com/discordjs/voice/issues/130)) ([308b9b8](https://github.com/discordjs/voice/commit/308b9b8e9597c294995984dd5409f1f58e47a7ac))
* stream time statistics ([#75](https://github.com/discordjs/voice/issues/75)) ([ced3102](https://github.com/discordjs/voice/commit/ced31026087a6a87679b85b613ae069d2ac4f223))
* strengthen new state type for status events ([#132](https://github.com/discordjs/voice/issues/132)) ([408999d](https://github.com/discordjs/voice/commit/408999d78962b860f3dd712716c8c76e4464dc37))
* **TransformerGraph:** add FFmpeg opus optimization ([#47](https://github.com/discordjs/voice/issues/47)) ([f1f8f61](https://github.com/discordjs/voice/commit/f1f8f616861ba371073ac240f8a9b1014568ccb2))
* use typed event emitters internally ([#91](https://github.com/discordjs/voice/issues/91)) ([0678cd9](https://github.com/discordjs/voice/commit/0678cd90b5d72dca4332afd5e935022a033c9d27))
* **Util:** add Opus audio probing utility ([#118](https://github.com/discordjs/voice/issues/118)) ([379f9a7](https://github.com/discordjs/voice/commit/379f9a73689577c4ef6458a25976ddba0101b7b6))
* **Util:** support AbortSignal in entersState ([#171](https://github.com/discordjs/voice/issues/171)) ([636f54f](https://github.com/discordjs/voice/commit/636f54fd5d8f805f19fc6482ae9c427da0a91999))
* voice channel groups ([#147](https://github.com/discordjs/voice/issues/147)) ([6fb11e9](https://github.com/discordjs/voice/commit/6fb11e9bac74786e35646b52564e195724ec6102))
* **VoiceUDPSocket:** use new IP discovery packet format ([#90](https://github.com/discordjs/voice/issues/90)) ([9a4e7f4](https://github.com/discordjs/voice/commit/9a4e7f43f5deb6d1bee24926e8112fd31b353afb))



## [0.7.5](https://github.com/discordjs/voice/compare/v0.7.4...v0.7.5) (2021-11-12)


### Bug Fixes

* postbuild script ([644af95](https://github.com/discordjs/voice/commit/644af9579f02724c489514f482640b8413d2c305))



## [0.7.4](https://github.com/discordjs/voice/compare/v0.7.3...v0.7.4) (2021-11-12)


### Bug Fixes

* conditionally apply banner only to esm build ([8c4e8c4](https://github.com/discordjs/voice/commit/8c4e8c4ba5b9013a90de0238a7f2771e9113a62d))



## [0.7.3](https://github.com/discordjs/voice/compare/v0.7.2...v0.7.3) (2021-11-11)


### Bug Fixes

* **esm:** resolve esm imports ([#229](https://github.com/discordjs/voice/issues/229)) ([616f2bc](https://github.com/discordjs/voice/commit/616f2bcfde47e55ac7b09f4faaa07f15d78c11a5))



## [0.7.2](https://github.com/discordjs/voice/compare/v0.7.1...v0.7.2) (2021-10-30)


### Bug Fixes

* prism imports for ems ([0bfd6d5](https://github.com/discordjs/voice/commit/0bfd6d5247f89cfc125e7645e9fb7ebfed94bb2f))



## [0.7.1](https://github.com/discordjs/voice/compare/v0.7.0...v0.7.1) (2021-10-30)


### Bug Fixes

* prism imports for esm ([9222dbf](https://github.com/discordjs/voice/commit/9222dbfedd8bfaeb679133dfa41330ea75a03a70))



# [0.7.0](https://github.com/discordjs/voice/compare/v0.6.0...v0.7.0) (2021-10-30)


### Features

* export some types so they render in docs ([#211](https://github.com/discordjs/voice/issues/211)) ([a6dad47](https://github.com/discordjs/voice/commit/a6dad4781fb479d22d7bff99888e42368d6d6411))



# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.
