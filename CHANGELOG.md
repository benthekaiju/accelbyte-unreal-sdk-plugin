# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [4.0.0](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/branches/compare/4.0.0%0D3.2.0) (2021-08-02)


### ⚠ BREAKING CHANGES

* **Achievement:** Change the type of LatestValue of FAccelByteModelsUserAchievement model from int32 into float.

### Features

* add awscognito platform type ([0610ef2](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/0610ef28ab6907069be6402d1d887b87a155a487))
* Add digital signature check to plugin ([94e8843](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/94e8843875a10f41f6e976000198afef40e7e5d7))
* **core:** add scope lock-free mechanism on HttpRetryScheduler for thread-safety ([c731dcb](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/c731dcbbec20e44cfd207c36a3e7abdb064c4418)), closes [#2](https://accelbyte.atlassian.net/browse/2)
* **jenkins:** jenkinsfile - remove ue 4.20, 4.21 and add 4.26 ([a152ca6](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/a152ca62e85dbe4c9f04439f6b53e6d1defd8ee9))
* **jenkins:** make build linux & windows parallel + separate build editor and game to make ci faster ([3a98e60](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/3a98e60f5840eb3c28f4c595a234aa952c71176a))
* **jenkins:** use the new justice-sdk-builder ([472995e](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/472995ed380f6125a81b09d6412fed869dada6b3))
* **lobby:** add get & getAll session Attributes ws commands ([4208e56](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/4208e56fb3dc7510714a624c4ca584fa188e185a))
* **lobby:** add GetOnlineFriendPresence, and marked OnGetAllUSerPresence obsolete. ([eaf18ef](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/eaf18ef389fd2ebd84f2ed3bb0a3753f0ff8968b))
* **lobby:** Generate party code ([2e04734](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/2e04734c03b06a91e40646533899f4c3cb5f5b2d))
* **serverloby:** add Set, Get, GetAll user session attribute ([1d69966](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/1d699664354896f936ddb1dc4fbaf04f50b3f486))
* **session browser:** add get session data by session id ([6982214](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/6982214c52344b03b415286c56f8bd11c0e38e63))
* **ue5ea:** Jenkins - Build.ps1 - remove superficial option ue4exe ([d93e2d2](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/d93e2d28538a4f646f606568cd9ed042d6ce9f38))
* **ue5ea:** Jenkins - RunTests.ps1 - add alternate unreal editor exe for UE5 and UE4 ([2c9deca](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/2c9deca8fcb2a40490651ae7370dc9fa14d91126))
* **ue5ea:** jenkins.config.json - add ue 5.0ea ([21bb301](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/21bb301287e4de1ffc059fd8091b9a8b1f1eda3e))
* **unrealengine:** remove support for ue < 4.25 ([a5b7791](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/a5b7791fa7799f0773c6556f09a70a0e092f963f))


### Bug Fixes

* **Achievement:** Fix the User Achievement model difference with the Backend response. ([1581d57](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/1581d57a4f34d73a10de47f127280d85c3b1a0ec))
* **files order:** Fix signature algorithm to ensure files and directories order consistent and update digital signature ([57f9688](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/57f968814d190d598b20a2b8f37734dcbb070790))
* **lobby:** Response.Code always empty ([134429c](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/134429cefcabfb6e0f72ae33dd7dd4f0ad321ec7))
* **Oauth2:** Fix the GetTokenWithAuthorizationCode() using v1 endpoint ([1e642ae](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/1e642ae06b83b08af9cb624bc3b94d1def4390d1))
* **Telemetry:** Change GetSeconds() to GetTotalSeconds ([c8b57de](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/c8b57de210f1c91b5bc6979015d1eddb4f82d4f1))
* **UGC:** Fix the integration test naming ([889e2f6](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/889e2f64393448fc3fd3e44fad55a4cc6ca0bf68))
* **UGC:** Rewrite the inline documentation: fixing from copy-paste mistake, and not standard writing. Fix the copyright. ([25b909a](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/25b909a3281b5de4271e55c75d012655a4a84056))
* **uplugin:** remove unicode literal in PrebuildSteps ([ac08206](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/ac082067a8a69c636cb421a4456e022860c6dd9b))


### Documentations

* add version.json, changelog, and readme ([5aa4cf2](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/5aa4cf2b662917f0383f159d69f5138791979daf))


### Tests

* **AUser:** fix test regression due to invalid partial query result assertion ([37e7a98](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/37e7a986670b9120e2bfa30942ce9b226ac335a2))
* **AUser:** make STEAM_KEY environment variable optional ([eb0d5c5](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/eb0d5c526047600758fbb54471676053492789ef))
* **basic:** check steam ticket before testing with steam in AUser tests ([e1d06ae](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/e1d06ae4a93df953fc41d2cb7d615c94962e08b4))
* **general:** fix incorrect token retrieval for the admin user in test utilities ([448d23c](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/448d23c5b444c7a842976c984330b281313c3088)), closes [#19](https://accelbyte.atlassian.net/browse/19)
* **play:** add random element in lobby user test emails ([ccf71a1](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/ccf71a1e287a7e7632a50f4aec51394c7daabacd))
* **play:** fixed lobby, serverlobby, joinablesession & session browser tests ([c705f48](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/c705f48bfab962dfeb9a90bdde222457f2360e73)), closes [#375](https://accelbyte.atlassian.net/browse/375)
* **subscription:** fix error categoryPath /game ([8ad19c8](https://bitbucket.org/accelbyte/justice-unreal-sdk-plugin/commits/8ad19c8a46d4034da4939418a4d0ab298305835c))

## [3.2.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/3.2.0%0D3.1.0) (2021-07-07)


### Features

* **Achievement:** remove redundant test code + fix identifier naming according to ue4 guideline ([4340c75](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4340c759a78b5ac2b01408528078e91e47cea116))
* **jenkins:** Convert scripts to powershell ([d8c6faf](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d8c6faf794b1e64696f094e2ad69cb2e6af1aaef))
* **jenkins:** Convert scripts to powershell ([973cd4a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/973cd4a3006da5ddbced29a5bde52cb3976e4a78))
* **Json:** Remove empty string fields from FJSonObject ([176e210](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/176e210fc41928491052afb0474d3591e8fccb33))
* **lobby:** add errorNotif and move admin function into new file ([af5ddbc](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/af5ddbcc773d35810ca3db360ecc530dd7c0edcf))
* **lobby:** Add Send Notification to User ([4f46c75](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4f46c756d3c8f590ef4f23e067572005543b4142))
* **ugc:** Add UGC into SDK ([8bb8e87](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8bb8e87a55a85dce51675d25cdb2b629ae136e71))
* **UserProfile:** add BatchGetPublicUserProfileInfos ([759f4d5](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/759f4d52e853b9a6d6de2e8bb01fc96964ed903a))
* **UserProfile:** Get custom attribute other user id ([1dce0a5](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1dce0a5659a63d128c9969b799e453b628813697))


### Bug Fixes

* **CloudSaveTest:** Disable concurrent record test ([02ed0a4](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/02ed0a4493c022f69b19995ab416b8bd71ff0aae))
* **CloudSaveTest:** Disable concurrent record test ([1aa8263](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1aa82637d0dc335d51c71127546edb1e275c1e30))
* **Jenkins:** Revert unfinished work to convert scripts to powershell ([3cbcc1e](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3cbcc1eb58c65a1d8c2924202e8c2999ae641b18))
* **User test:** test failed due to missing waiting ([faf6818](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/faf6818563c985d492532be37a6775e6abdade2f))


### Reverts

* Revert "test(Achievement): make test variable declarations static to keep it local + make the names shorter" ([f1e8785](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f1e8785b3ffffb3704709df4996e97779ffe0854))
* Revert "test(MultiRegistry): make test variable declarations static to keep it local + make the names shorter" ([bd0f2ea](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/bd0f2ea376c1cd464f96721f3c323b0bcf2d3e20))
* Revert "test(GameProfile): make test variable declarations static to keep it local + make the names shorter" ([e7c84bd](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e7c84bd24c04657de05bb1c57c4ed2f1c685c199))
* Revert "test(UserIntegration): make test variable declarations static to keep it local + make the names shorter" ([879f5ba](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/879f5bad209aaf0ab8a3561ed88a7fd45d6de92c))


### Tests

* **Achievement:** deduplicate QueryAchievement tests ([d5c8bf2](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d5c8bf2b082d664689e37654c56c327e4c404f95))
* **Achievement:** deduplicate QueryAchievement tests (more) ([63daee4](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/63daee4b9a2efdab1a182f0b2448f9afbebce583))
* **Achievement:** remove unnecessary http flush ([b76e99a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b76e99afcf4bed5e559f6b9187b98b48717adc33))
* **Achievement:** rename identifiers according to ue4 guideline ([651e5ad](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/651e5ad92c730f0d16de99becf71b3a930e9b082))
* **Achievement:** setup - use reference on achievements loop ([9b070d9](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/9b070d9ec17e8ef608803feda03e91a70ed96153))
* **CloudSave & GameTelemetry:** change check macro with AB_TEST_XXXX that doesn't crash if failed ([93dff77](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/93dff775262ce1a3bcd88d3f2d51d4543e11f18a))
* **eCommerce:** Change check macro to AB_TEST_XXX to not crash test automation ([4c067a0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4c067a07e9081729900b3234dc630b566c0cd3ef))
* **Ecommerce:** fix sdk tests (max draft 1 be changes, remove unnecessary http flush, remove code redundancy) ([6742f8f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/6742f8f109ec7b2d8164370d8de4cfe4492b44e2))
* **lobby:** fix lobby test stuck ([8744a3f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8744a3fde575fb7c4dea2182a6d6d021262c5a91)), closes [#364](https://accelbyte.atlassian.net/browse/364)
* **MultiRegistry:** use setup/teardown test users from utilities ([f98b2a5](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f98b2a5f8027acda604462a3b4e37239f15e9c10))
* **serverlobby:** fix serverlobby test cases stuck ([c7ecf6d](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/c7ecf6d2fd4e1aa9ed25199eaea0a42fd2f87435)), closes [#366](https://accelbyte.atlassian.net/browse/366)
* **Social:** change check macro into AB_TEST_XXX to not crash automated test ([469b04c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/469b04c1fbc2e5fe33d87225154036f418915286))
* **UserIntegration:** BatchGetPublicUserProfileInfos - use setup/teardown test users from utilities ([1efcbad](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1efcbadc2be96af8236dbddedbdef0c2f73e77d6))
* **UserIntegration:** BatchGetPublicUserProfileInfos - use setup/teardown test users from utilities (more) ([95667f3](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/95667f318d0c3d0a06ed5a2a40f30a91e222fb1d))
* **UserIntegration:** clean up ([31b0d58](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/31b0d58c5c753e81674bb59f577785973c54c5f8))
* **UserIntegration:** fix error due to missing waiting in GetUserByDisplayName, GetUserByEmailAddress, GetUserByUsername ([6f0bb58](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/6f0bb582c60ef7a020a8bf4d809fd4ead79d5236))
* **User:** Replace check macro with more descriptive TestXXX-based AB_TEST_XXX macros ([8643f1e](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8643f1efeba008abb11c83d8ad2beed12467132c))
* **Utilities:** move LatenciesPredicate to its proper place ([57e8ad3](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/57e8ad3ceaa5c6a6b7ea0fef1828249543176768))
* **Utilities:** remove redundant get required environment variable logic ([0f52026](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/0f520268e56cdfdf8fd912819c1aed71ec35482b))

## [3.1.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/3.1.0%0D3.0.1) (2021-06-23)


### Features

* **apigw:** remove apigw and adjust endpoint, add Registerv3 accept legal policy when create new account ([db83fb6](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/db83fb6919fc3f082bb0b825d2caf6d59eacfd58))
* **FMultiRegistry,FApiClient:** allow multiple users to be signed in at one ([503d2c9](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/503d2c994ee0b104011e129d8c9332a1bf4566e8))
* **lobby:** Bulk get user presence ([e7fcfe4](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e7fcfe432379b379be27e2e25172b7e9d75caadb))
* **lobby:** Invite and Join Party via Code ([6c19a0e](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/6c19a0e52e539d43b65ac738d11307461a8a7330))
* **lobby:** Promote party leader request ([f2348b8](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f2348b8f33efa4bdf8a63f1b243e179103913a26))
* **lobby:** Reject party invitation ([98c016c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/98c016cc23d0d44e524223d9ceb74ed51f0b9ff2))
* **Party:** Get party data by party id ([ac412e4](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/ac412e4f685cb47c1c50fca7a8e4a232b94318d6))


### Bug Fixes

* **Tests.AUserProfile:** remove redundant delete profile function ([b873b1c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b873b1c5af1c389cc75578e6ff81e65e2f2e5f46))
* **Tests.AUserProfile:** remove redundant delete profile function ([5d97c87](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5d97c874b2182159ef3fec6d0b8f2fda4b987bc2))

## [3.0.1](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/3.0.1%0D3.0.0) (2021-06-09)


### Features

* **ecommerce:** add some entitlement endpoint to server sdk ([e284472](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e28447288bd8a96816e3a63c69c140679cd210e8))
875da0fe172fc5120ed60ca9fc276d80302fd2cd))
* **lobby:** unfriend, cancel friend, and reject friend notification ([099489a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/099489a0316f84be9caddf45198469e3f77782e9))

### Bug Fixes

* **user:** Fix login with other platform function ([f6624fa](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f6624fa749d924f739891dc1f53b068ec67e421e))
* **entitlement:** change appid to string ([78592c5](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/78592c5da61355a2534bdcb9fd24a91f797c3705)

## [3.0.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/3.0.0%0D2.35.0) (2021-06-09)


### ⚠ BREAKING CHANGES

* **AUser.Tests:** Fix breaking change caused by removal sensitive info
* **tests.AUser:** Fix breaking change caused by removal sensitive info

### Features

* **ecommerce:** redeem code feature from VE repo ([875da0f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/875da0fe172fc5120ed60ca9fc276d80302fd2cd))
* **lobby:** add lobbySessionId to be able to reconnect using same token ([1bf75c8](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1bf75c8e25f3538c90383b260540099378b1e932))


### Bug Fixes

* **AUser.Tests:** Fix breaking change caused by removal sensitive info ([4cecd53](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4cecd53d8e310262e3eac360b84dc27197ecfe60))
* **log:** github sync, removed nonfunctional verbosity set functions. ([9528e97](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/9528e970be64ddd405af5c2f41ba7ab5323c7d54))
* **tests.AUser:** Fix breaking change caused by removal sensitive info ([f0a4d79](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f0a4d7929948dcd2ced4ba0bc7580ad27b8fbfff))
* error compile need to include AccelByteError.h on file AccelByteUtilities.h ([3d18b10](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3d18b10d66286147839fdb6abfb2d9361f24a268)), closes [#312](https://accelbyte.atlassian.net/browse/312)

## [2.35.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.35.0%0D2.34.0) (2021-05-25)


### Features

* **dsm:** add RegisterLocalServer with public ip address & moved GetPublicIp to AccelByteUtilites ([62a2d53](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/62a2d53395e8a462ee0cc39ecaa10bb04e5c2711)), closes [#307](https://accelbyte.atlassian.net/browse/307)
* **lobby:** add SetSessionAttribute function & matchmaking with extra attribute field ([3f3dcdc](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3f3dcdc69df550905a12cd2bdb3aeda8de18c677)), closes [#303](https://accelbyte.atlassian.net/browse/303)


### Bug Fixes

* **Utilities:** fix FAccelByteModelsPubIp undefined in UE4 4.20 ([8495c02](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8495c02526ce04c5a7b9706b2956af24c1659658)), closes [#310](https://accelbyte.atlassian.net/browse/310)

## [2.34.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.34.0%0D2.33.0) (2021-04-28)


### Features

* **cloudsave:** add Cloud Save APIs for Server SDK ([d050d14](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d050d1469f0c29c535e5fabc93514d01a1b30c14))
* **ecommerce:** add bulk entitlement lookup ([e86769b](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e86769ba214f565893b5d2fb337f807139e9d1ba))
* **ecommerce:** add Debit wallet ([5355b33](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5355b33a92dbd2a1fccbfb293d1ca07704e296ca))
* **lobby:** add custom port field in DSNotice lobby model. ([d7a2722](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d7a27223776817022409482f9c7888b097a7ac5b)), closes [#288](https://accelbyte.atlassian.net/browse/288)
* **lobby:** add custom port field in DSNotice lobby model. ([faeef4b](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/faeef4bca4341cd2b69995fc5a94b8ac3e00d255))
* **server:** Re-Login mechanism to renew token on Server SDK ([295cd02](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/295cd0267696366c9e12e485f31432e15917a92f))


### Bug Fixes

* **ecommerce:** fix integration test for bulk query entitlement ([e3b8241](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e3b82414275cb1f8933f87c5feb25467a0bd2ccb))


### Tests

* **dsmconfig:** fix missing protocol field in dsmconfig ([cdf912b](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/cdf912b98137e59f9fafab8dbbb2a3b96c9aec8f)), closes [#294](https://accelbyte.atlassian.net/browse/294)

## [2.33.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.33.0%0D2.32.0) (2021-04-14)


### Features

* **entitlement:** add entitlement sync for 3rd party platform purchases ([aef37f1](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/aef37f1264049659e32aa8e8b907d9e539227bcb)), closes [#272](https://accelbyte.atlassian.net/browse/272)
* **iam:** add endpoint to retrieve JWT from particular session id on apigw ([8611590](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/861159011c16b012515a005e562a6c4716795fc7))
* **server:** remove agones ([3653a4f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3653a4f0798a68f544c36d96c8cb886215743a20))


### Bug Fixes

* **http:** fixed http flush on shutdown ([7521cf9](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7521cf91406f08901fce45f0d1d588f96ec83182))
* **http:** Not started http requests needs to wait for timeout before return error ([7014eed](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7014eedd6671cd8d36021ce7eaf31d4a7e2ba0fe))
* **lobby:** create a new websocket instance when connection state error ([8ceae30](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8ceae30b4219dbc71f439dce1a95942c3131aa75))
* **lobby:** fixed websocket instance connection error state reconnecting ([5690f02](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5690f02c2074237e043ba0b148387dbc7b696763))

## [2.32.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.32.0%0D2.31.0) (2021-03-17)


### Features

* Add ability to set AccelByteReportLog's verbosity ([94d07c0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/94d07c0568c9c9bd97b6a0b1de3c26bf124a661d))
* add session browser api ([4f86f6e](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4f86f6e2cfd9a024ca0d9d1b6bfc026bbb91886d)), closes [#270](https://accelbyte.atlassian.net/browse/270)
* add signaling p2p to lobby ([90ca01c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/90ca01c08719d61f1b31d33279a56776733f561c)), closes [#263](https://accelbyte.atlassian.net/browse/263)
* **plugin:** remove platform whitelist ([5a52ebb](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5a52ebb682ee8351e8e832a1835c99738061c15a))


### Bug Fixes

* **error:** check field before try parsing ([070bfc0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/070bfc0e8a8e85ec1ecd9d4b4f243a8715a7b777))
* AccelByteUe4SdkDemo project blueprint ([5e68276](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5e682765384cca02f4d9e1361a6912a3e68ebe0f))
* Remove #pragma once from cpp file, which can cause compilation failures on some platforms. ([4a85981](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/4a85981803fc6131d644126073620d557372964e))
* **error:** check field before try parsing ([e0caf24](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e0caf240e980852d92a1c78af1f03d32d4faea3e))


### Tests

* **joinable:** fix joinable test case failed because of persisting party between test session ([7f1c4db](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7f1c4db434fea016cfad13db925bffc657a66d87))

## [2.31.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.31.0%0D2.30.0) (2021-03-03)


### Features

* **partyStorage:** add party storage client function ([d824de7](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d824de7a4dbfc1f1b02be9d54baaf82400e18793))
* **serverLobby:** add party storage ([5ff594f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5ff594ffe5abae83e2f79ad49cc5d3ea8bd3a9e3))


### Bug Fixes

* **chore:** remove array ([fb1c9bc](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/fb1c9bcfe3a37782bbf9b2a8cc5643d1969373e6))
* **serverLobby:** simplify baseUrl ([929a221](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/929a221e836d6de8b594c52d1a2ade1d0648558d))
* fixed request content was not encoded for type x-www-form-urlencoded ([e3078cc](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e3078cc0ef453424e64a20cb96e839e2736169dd))

## [2.30.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.30.0%0D2.29.2) (2021-02-17)


### Features

* **config:** make service url config optional ([c8b1741](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/c8b1741a9df6582d1e1ab4346255f162a4d0fe02))
* **Matchmaking:** implement joinable session ([fc127fc](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/fc127fcead48d9039e8f6e6ba74c8284a029b608)), closes [#258](https://accelbyte.atlassian.net/browse/258)
* **Server:** Add query party by userId in server ([2f290c0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/2f290c04873b77a6918cf06ce584b5cdd5a3b3ab)), closes [#242](https://accelbyte.atlassian.net/browse/242)
* **user:** add login with other platform ps5 enum ([bcc94c2](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/bcc94c28329ad5cdb528aa7fed6fc53a03878d87))


### Bug Fixes

* undefined ENGINE_MINOR_VERSION preprocessor on AccelByteUserModels.h ([1535744](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1535744683d1dc0b6898e8c97aa16f5d8ceb2a13))
* **GetDeviceId:** Suppress deprecation warning for GetDeviceId ([e58f645](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e58f645734c9fbd4371bf1251b8fa5adbb8e2f10))

### [2.29.2](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.29.2%0D2.29.1) (2021-02-03)


### Bug Fixes

* **dsm:** fixed parse match request content length checking lead to uninvoked callback ([e4def25](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e4def254497115967253ffab05497dceffa16140))

## [2.29.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.29.0%0D2.28.1) (2021-01-20)


### Features

* **Automation Metric:** SDET-1300 Integrate SDK Test Result to Automation Metrics ([d002eca](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d002eca6d98f2ddcf260582129db2743445e3f47)), closes [#237](https://accelbyte.atlassian.net/browse/237)
* **Automation Metric:** SDET-1300 Integrate SDK Test Result to Automation Metrics ([9b824e3](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/9b824e37af6589416d1a04a4cae48f615b1c6985))
* **core:** remove AccelByteCustomWebBrowserWidget ([82cbb1a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/82cbb1ac8ad6ba85a9e1b604e15ec7b080d2a694))
* **core:** support UE 4.26 ([d2d4b22](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d2d4b2232be2a368ef7abe7321479280dd78493f))


### Bug Fixes

* **config:** add config null check ([d56a651](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/d56a6513d7e8a53fbe387709458a61388d4a5fbb))

## [2.28.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.28.0%0D2.27.0) (2021-01-06)


### Features

* **dsm:** adjust get DSM region url, get region and provider value from run args, select DSM client based on region and provider (backward compatible) ([5cabf1a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/5cabf1a0ab58d1af53732efd0eea07d7fcc7b45f))

## [2.27.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.27.0%0D2.26.0) (2020-12-10)


### Features

* **lobby:** parse object value, parse quoted array element, only show parse error for known messages ([f72578c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f72578cb4e53f2cec4261baf4d82e0620cc590dc))


### Bug Fixes

* **lobby:** fixed lobby crash on exit ([b667537](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b6675370b99c58d28ebd5594db32bbf36c154f3a))

## [2.26.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.26.0%0D2.25.0) (2020-11-25)


### Features

* **lobby:** add party attribute option for the StartMatchmaking request ([7a85dff](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7a85dfff97ccbf7c2dd817774cfcb15f24581693))


### Bug Fixes

* **partyAttribute:** restrict the matchmaking party attribute to Map<string, string> and affect the sent request + heartbeat parsing at the server ([f0a26a7](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f0a26a761ced9184917e1c5a55d8e5c9fabd24bf))

## [2.25.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.25.0%0D2.24.0) (2020-10-28)


### Features

* **user:** add epicgames and stadia platformType ([533aa8a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/533aa8a19866a69da00f58f81cedce54bf3470f4))


### Bug Fixes

* crash on RemoveTicker on game telemetry API ([2e0a5fd](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/2e0a5fd09e399c320aed8d61a4368534fdd3154b))
* GetPlatformLinks and UnlinkOtherPlatform namespace ([f0ab180](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f0ab180e3417a7a8ad4e6a1bcb23e0d2801316de))

## [2.24.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.24.0%0D2.23.0) (2020-10-14)


### Features

* **User:** add search filter param in SearchUser ([7565805](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7565805425472096e94d21894a63c77dd3956fb4))


### Tests

* **Daily Test:** SDET-1166 Run SDK Automation Test Daily and Send report to slack channel ([3f7f34f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3f7f34f92ba5012fd310722b89a80e3b61c16a79))

## [2.23.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.23.0%0D2.22.0) (2020-10-01)


### Features

* **lobby:** implement global chat ([3773b11](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/3773b11f5bd5553fcc5b3806946c7a7f51ae88ad))
* **user:** add username parameter for register, upgrade, and search ([54b3ed7](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/54b3ed7a998a9f8723b3441d70feecf08cdf0028))

## [2.22.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.22.0%0D2.21.0) (2020-09-16)


### Features

* **Subscription:** add CheckEligibleUserCheck blueprint node ([fa0182c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/fa0182cb7687bc58b1759f34308ec743069b811c))


### Bug Fixes

* **Subscription:** updated check flow to latest using check any entitlement ownership API ([7335ef8](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7335ef813b7a655d9182e154e96833db9760ce18))


### Tests

* **Achievement:** fix achievement invalid ID test to comply to UUIDv4 format ([8a1ff0f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/8a1ff0fdda5baf1e84679852fd2ef7bf8e3746e7))
* **ecommerce:** fix invalid case because not UUIDv4 format ([7ee52e2](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7ee52e2ccbeb8f03ac59ddf0ca9f4992f7fd4f4d))
* **ecommerce:** wrong UUIDv4 format ([2217521](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/221752133149bc0c34487ad5abeb754ad3cce73b))
* **Ecommerce:** fix another invalid id error ([a3f7f0f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/a3f7f0f9f923ce28f85f269ae35e9d2098417409))
* **sub:** changed sub test users ([b6de67e](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b6de67ecf3c452129fa0251c297cdf3aa97da65e))
* **subscription:** make app id static in sub test ([b9c76d8](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b9c76d8baa2a1b0805def56bc267b46598a3648a))

## [2.21.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.21.0%0D2.20.0) (2020-09-02)


### Features

* **User:** added `ps4` and xbox `live` enum for 3rd party login ([430b2e0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/430b2e0635a8ceaf8e31a9bdc1c7b89030e29f24))


### Bug Fixes

* **config:** fix DefaultEngine.ini default server setting value ([9f868f2](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/9f868f2aadd95be027ec7d94c3bfda6d5be16a24))

## [2.20.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.20.0%0D2.19.0) (2020-08-19)


### Features

* **Achievement:** bringback achievement from VE ([1f3e6be](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/1f3e6be1b85b8a194d32fa28d9f56a987d19cff0))


### Bug Fixes

* **test:** additional incremental Achievement test ([71fba3a](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/71fba3a48e3c447992659c49230e24faf43ad147))
* fix ue 4.25 build ([9e2b24c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/9e2b24c79913fe49335b5a23b8b299f6394ac277))


### Tests

* **gameTelemetry:** fix game telemetry test ([240df45](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/240df45e9699a35095abeb1c2eeeb8557daa0429))


### CI

* **jenkins:** add target parameters ([a9d6d4d](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/a9d6d4d0fede4e120a106e8ceb9908d2d32b2a6b))

## [2.19.0](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.19.0%0D2.18.6) (2020-08-05)


### Features

* game telemetry scheduler ([e2bebe6](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/e2bebe69196d27c044414c91e8537039ff1c492d))


### Bug Fixes

* **cloudstorage:** Fix CloudStorage API documentation. ([b030ce0](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/b030ce0aa02a7f45af3bf1777e2f50b254b8fe2e))
* **cloudstorage:** Mark Status field as DEPRECATED and add Size field in the FAccelByteModelsSlot model. ([64a0a6f](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/64a0a6f6b4d6fa22a94619aec201ce25e531e5ca))
* **cloudstorage:** Mark UpdateSlotMetadata function with filename  parameter as deprecated ([22f2df3](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/22f2df3ac8bac90f2fc2c8f2305384e8f21931ef))
* **cloudstorage:** Overload UpdateSlotMetdata()  function. ([7aeea01](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7aeea01466a753e49539b86940078acd089103eb))
* **config:** remove leaderboard server URL from server SDK config ([7b25fce](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/7b25fceec67171efa82b2223095c01dc9b869c01))
* **jenkins:** add SERVER_STATISTIC_PREFIX for jenkins config ([f09f161](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f09f161a00d521447841c08e945045857d09e30e))
* **statistic:** Update statistic error codes. ([f0c050c](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/f0c050c1146de38749a870234597c5c47cb748f5))


### CI

* **jenkins:** temporary social service env flag ([41ec02d](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/41ec02d7114e1a5889ed6919467c691963bbe85f))

### [2.18.6](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.18.6%0D2.18.5) (2020-07-22)


### Refactors

* **envar:** clean up warning and refactor envar ([ee90f12](https://bitbucket.org/accelbyte/justice-ue4-sdk/commits/ee90f1275334ea78f3b4234951db4359820febd6))

### [2.18.5](https://bitbucket.org/accelbyte/justice-ue4-sdk/branches/compare/2.18.5%0D2.18.4) (2020-07-08)

## 2.18.4 (2020-07-03)
### Changed
- Agreement
    - GetLegalPolicies
        - Add policyType and tags param
    - GetLegalPoliciesByCountry
        - Add policyType and tags param

## 2.18.3 (2020-07-03)
### Fixed
- Lobby Api Blueprint
  - Fix delegate notif not executed

## 2.18.2 (2020-06-30)
### Fixed
- Telemetry Api
  - #include header path not complete
- Server DSM Api
  - Agones preprocessor
  - ServerDSMApi warning C4458 signature hides class member

## 2.18.1 (2020-06-25)
### Fixed
- Server DSM Api
  - Move args parsing from constructor

## 2.18.0 (2020-06-22)
### Added
- CloudSave
      - Add SaveUserRecord
      - Add ReplaceUserRecord
      - Add GetUserRecord
      - Add GetPublicUserRecord
      - Add DeleteUserRecord
      - Add SaveGameRecord
      - Add ReplaceGameRecord
      - Add GetGameRecord
      - Add DeleteGameRecord
      
## 2.17.0 (2020-06-19)
### Added
- Agones SDK UE4 plugin
- Register server using Agones provider

## 2.16.0 (2020-06-16)
### Added
- Agreement Api
### Fixed
- Fix third party platform string

## 2.15.0 (2020-06-03)
### Added
- Game Client SDK
  - User
    - Add UpgradeWithPlayerPortal 
    - Add GetCountryFromIP
  - Entitlement
    - Add CreateDistributionReceiver
    - Add GetDistributionReceiver
    - Add DeleteDistributionReceiver
    - Add UpdateDistributionReceiver

## 2.14.0 (2020-05-29)
### Added
- ServerTelemetry Api

## 2.13.0 (2020-05-29)
### Added
- GameTelemetry Api

## 2.12.1 (2020-05-28)
### Added
- User
    - added `ps4` and xbox `live` enum for 3rd party login

## 2.12.0 (2020-05-20)
### Added
- Lobby
    - Adding Bulk Friend Request
- User
    - Adding BulkGetUserByOtherPlatformId function

## 2.11.0 (2020-04-29)
### Added
- Leaderboard Api

## 2.10.0 (2020-04-08)
### Added
- UserProfile Api
    - GetCustomAttributes
    - UpdateCustomAttributes
### Changed
- UserProfile Api
    - UpdateUserProfile success result handler
- UserProfile Blueprints
    - UpdateUserProfile success result handler

## 2.9.0 (2020-04-06)
### Added
- UserProfile Api
    - GetCustomAttributes
    - UpdateCustomAttributes
- ServerQosManager
    - GetServerLatencies
    - GetQosServers
- ServerDSM
    - GetRegionDSMUrl
    - GetPubIp
### Changed
- Game Client SDK 
  - Retry network error request
  - Changed FAccelByteModelsSlot DateAccessed, DateCreated, DateModified from float to FDateTime
- Lobby
    - Fix lobby reconnect backoff retry, reconnect timeout, ping delay
- ServerDSM
    - Register Server will check DSMUrl, Provider, and Public Ip first before send request.
    - Add ErrorRetry param on ConfigureHeartBeat
    - Will stop sending heartbeat after errorRetry number reached
### Fixed
- Game Client SDK 
  - Fix Lobby UnbindEvent
  - Fix Linux compilation error
  - Fix AccelByteReport response invalid handler
  - Fix credentials is not cleared after logout

## 2.8.0 (2020-03-26)
### Added
- Session Management
    - Automated session refresh

## 2.7.0 (2020-03-03)
## Added
- Game Server SDK
  - ServerCredentials: stores ClientAccessToken, ClientNamespace, and MatchId
  - ServerSettings: stores server's settings such as ClientId, ClientSecret, IAM URL, DSM URL, etc.
  - CustomWebServerApi: to open a WebServer for accept DSM claim request
  - ServerOauth2Api
    - LoginWithClientCredentials
  - ServerDSMApi
    - RegisterServerToDSM
    - SendShutdownToDSM
    - RegisterLocalServerToDSM
    - DeregisterLocalServerFromDSM
  - ServerStatisticApi
    - CreateUserStatItems
    - IncrementManyUsersStatItems
    - IncrementUserStatItems
    - GetAllUserStatItems
- Game Client SDK 
  - Statistic
    - CreateUserStatItems
    - IncrementUserStatItems
## Removed
    - GetUserStatItemsByStatCodes
    - GetUserStatItemsByTags
    - BulkAddStatItemValue
    - BulkAddUserStatItemValue
    - AddUserStatItemValue
    
  - ServerEcommerce
    - GetUserEntitlementById
    - GrantUserEntitlements
    - CreditUserWallet
- Game Client SDK 
  - Entitlement
    - GetUserEntitlementById
    - ConsumeUserEntitlement
  - Qos & QosM Api
    - GetServerLatencies
    - GetQosServers
## Changed
- Game Client SDK
  - Lobby
    - SendStartMatchmaking(FString GameMode) -> SendStartMatchmaking(FString GameMode, FString ServerName, FString ClientVersion, TArray<TPair<FString, float>> Latencies)
## Removed
  - CustomWebServer
  - CustomWebServerApi
## Fixed
- User Integration Test
  - Fix UpgradeHeadlessDeviceAccount

## 2.6.1 (2020-02-07)
## Fixed
- Game Client SDK
  - Fix LoginWithOtherPlatform PlatformType

## 2.6.0 (2020-01-29)
## Added
- Game Client SDK 
  - User Api
    - GetUserByOtherPlatformUserId

## Changed
- GetUserByEmailAddress -> SearchUser
  - const FString& EmailAddress -> const FString& Query
  
## 2.5.0 (2019-11-25)
## Fixed
- Platform
  - ErrorCode Refactor
  - Models
    - FAccelByteModelsFullCategoryInfo -> FAccelByteModelsCategoryInfo
      - FString CreatedAt -> FDateTime CreatedAt
      - FString UpdatedAt -> FDateTime UpdatedAt
    - FAccelByteModelsItemInfoRegionData -> FAccelByteModelsItemRegionDataItem
      - FString CurrencyType -> EAccelByteItemCurrencyType CurrencyType
      - FString PurchaseAt -> FDateTime PurchaseAt
      - FString ExpireAt -> FDateTime ExpireAt
      - FString DiscountPurchaseAt -> FDateTime DiscountPurchaseAt
      - FString DiscountExpireAt -> FDateTime DiscountExpireAt
    - FAccelByteModelsItemInfoImage -> FAccelByteModelsItemImage
      - FString As -> Added
    - FAccelByteModelsItemInfo
      - FString BaseAppId -> Added
      - FString EntitlementType -> EAccelByteEntitlementType EntitlementType
      - bool Stackable -> Added
      - FString Status -> EAccelByteItemStatus Status
      - FString ItemType -> EAccelByteItemType ItemType
      - FString ThumbnailUrl -> Added
      - FAccelByteModelsItemInfoImage ThumbnailImage -> Deleted
      - FString Clazz -> Added
      - FString BoothName -> Added
      - int32 DisplayOrder -> Added
      - FString Ext -> Added
      - FString LocalExt -> Added
    - FAccelByteModelsPopulatedItemInfo -> Added
    - FAccelByteModelsItemCriteria -> Added
    - FAccelByteModelsEntitlementItemSnapshot
      - FString BaseAppId -> Added
      - EAccelByteEntitlementType EntitlementType -> Added
      - bool Stackable -> Added
      - FString ThumbnailUrl -> Added
      - FAccelByteModelsItemInfoImage ThumbnailImage -> Deleted
      - FString TargetItemId -> Added
      - int32 MaxCount -> Added
      - FString BoothName -> Added
    - FAccelByteModelsEntitlementInfo
      - FString GrantedCode -> Added
      - FString BundleItemId -> Deleted
      - EAccelByteEntitlementSource Source -> Added
      - FString GrantedAt -> FDateTime GrantedAt
      - FString CreatedAt -> FDateTime CreatedAt
      - FString UpdatedAt -> FDateTime UpdatedAt
    - FAccelByteModelsOrderInfoCurrencySummary -> FAccelByteModelsOrderCurrencySummary
      - FString CurrencyType -> EAccelByteItemCurrencyType CurrencyType
    - FAccelByteModelsOrderInfo
      - FString PaymentOrderNo -> Added
      - bool bSandbox -> bool Sandbox
      - FAccelByteModelsOrderInfoPaymentUrl PaymentUrl -> Deleted
      - TArray<FAccelByteModelsOrderInfoTransaction> Transactions -> Deleted
      - TArray<FString> EntitlementIds > Deleted
      - FString Status -> EAccelByteOrderStatus Status
      - FAccelByteModelsEntitlementItemSnapshot ItemSnapshot -> Added
      - FString CreatedTime -> FDateTime CreatedTime
      - FString ChargedTime -> FDateTime ChargedTime
      - FString FulfilledTime -> FDateTime FulfilledTime
      - FString RefundedTime -> FDateTime RefundedTime
      - FDateTime ChargebackTime -> Added
      - FDateTime ChargebackReversedTime -> Added
      - FString CreatedAt -> FDateTime CreatedAt
      - FString UpdatedAt -> FDateTime UpdatedAt
    - FAccelByteModelsOrderHistoryInfo
      - FString Namespace -> Added
      - FString CreatedAt -> FDateTime CreatedAt
      - FString UpdatedAt -> FDateTime UpdatedAt
    - FAccelByteModelsOrderCreate
      - FString Region -> Added
      - FString Language -> Added
    - FAccelByteModelsWalletInfo
      - FString Status -> EAccelByteItemStatus Status
      - FString CreatedAt -> FDateTime CreatedAt
      - FString UpdatedAt -> FDateTime UpdatedAt
  - Api
    - Entitlement::QueryUserEntitlement()
      - Param: int32 Page -> const int32& Offset
      - Param: int32 Size -> const int32& Limit
    - Item::GetItemsByCriteria()
      - Param: const FAccelByteModelsItemCriteria& ItemCriteria -> Added
      - Param: const FString& Language -> Deleted
      - Param: const FString& Region -> Deleted
      - Param: const FString& CategoryPath -> Deleted
      - Param: const EAccelByteItemType& ItemType -> Deleted
      - Param: const EAccelByteItemStatus& Status -> Deleted
      - Param: int32 Page -> const int32& Offset
      - Param: int32 Size -> const int32& Limit
    - Item::SearchItem()
      - Param: int32 Page -> const int32& Offset
      - Param: int32 Size -> const int32& Limit
    - Wallet::GetWalletInfoByCurrencyCode()
      - Url: "%s/public/namespaces/%s/users/%s/wallets/%s" -> "%s/public/namespaces/%s/users/me/wallets/%s"
    - Order::FulfillOrder() -> Deleted
    
## 2.4.0 (2019-11-11)
## Fixed
- Basic
  - Follow API Standardization
    - Endpoint Url:
        - UserProfile::CreateUserProfile() "%s/public/namespaces/%s/users/me/profiles" -> "%s/v1/public/namespaces/%s/users/me/profiles"
        - UserProfile::GetPublicUserProfileInfo() "%s/public/namespaces/%s/users/%s/profiles/public" -> "%s/v1/public/namespaces/%s/users/%s/profiles/public"
        - UserProfile::UpdateUserProfile() "%s/public/namespaces/%s/users/me/profiles" -> "%s/v1/public/namespaces/%s/users/me/profiles"
        - UserProfile::GetUserProfile() "%s/public/namespaces/%s/users/me/profiles" -> "%s/v1/public/namespaces/%s/users/me/profiles"
  - Cleanup user profile on integration test
## Changed
- Statistic API Standardization
  - Model:
    - FAccelByteModelsUserStatItemInfo
      - UPROPERTY change: profileId -> userId
    - FAccelByteModelsBulkUserStatItemInc
      - UPROPERTY change: profileId -> userId
- Statistic API Standardization
  -API:
    - GetAllStatItems() & GetStatItemsByStatCodes() -> GetUserStatItems()
      - URL change: `GET` "/public/namespaces/%s/users/%s/profiles/%s/statitems" -> `GET` "/v1/public/namespaces/%s/users/%s/statitems"
    - BulkAddStatItemValue()
      - URL change: `POST` "/public/namespaces/%s/statitems/bulk/inc" -> `PUT` "/v1/public/namespaces/%s/statitems/value/bulk"
    - BulkAddUserStatItemValue()
      - URL change: `POST` "/public/namespaces/%s/users/%s/profiles/%s/statitems/bulk/inc" -> `PUT` "/v1/public/namespaces/%s/users/%s/statitems/value/bulk"
    - AddUserStatItemValue()
      - URL change: `POST` "/public/namespaces/%s/users/%s/profiles/%s/stats/%s/statitems/inc" -> `PUT` "/v1/public/namespaces/%s/users/%s/stats/%s/statitems/value"
  - Model:
    - FAccelByteModelsUserStatItemInfo
      - Add member TArray<FString> Tags
## Added
- Log
  - Add HTTP Request/Response Log
  - Add Current Function Log
- Statistic
  - Add GetUserStatItemsByTags()
    - URL: `GET` "/v1/public/namespaces/{namespace}/users/{userId}/statitems"
    - Query param: "tags"
    
## 2.3.0 (2019-10-15)
## Fixed
- Ecommerce Test
  - Change CurrencyCode from "Ue4SdkCoin" to "SDKC"
  - Change Store name separator from '_' to '-'
- Automation
  - Change package format from "AccelByteUe4SdkPackage-{GIT_SHA}-BUILD-{BUILD_NUMBER}.7z" to "AccelByteUe4SdkPackage-{GIT_SHA}-{SDK_VERSION}.7z"
- IAM
  - Follow API Standardization
    - Models:
        - FRegisterRequest.LoginId -> FRegisterRequest.EmailAddress
        - FResetPasswordRequest.LoginId -> FResetPasswordRequest.EmailAddress
    - Endpoint Url:
        - User::GetData(): "%s/v2/public/users/me" -> "%s/v3/public/users/me"
        - User::SendResetPasswordCode(): "%s/v2/public/namespaces/%s/users/forgotPassword" -> "%s/v3/public/namespaces/%s/users/forgot"
        - User::ResetPassword(): "%s/v2/public/namespaces/%s/users/resetPassword" -> "%s/v3/public/namespaces/%s/users/reset"
        - User::LinkOtherPlatform(): "%s/v2/public/namespaces/%s/users/me/platforms/%s/link" -> "%s/v3/public/namespaces/%s/users/me/platforms/%s"
        - User::UnlinkOtherPlatform(): "%s/v2/public/namespaces/%s/users/me/platforms/%s/link" -> "%s/v3/public/namespaces/%s/users/me/platforms/%s"
        - User::GetUserByLoginId(): "%s/namespaces/%s/users/byLoginId?loginId=%s" -> "%s/v3/public/namespaces/%s/users?emailAddress=%s"
        - User::GetPublicUserInfo(): "%s/v2/public/namespaces/%s/users/%s" -> "%s/iam/v3/public/namespaces/%s/users/%s"
    - New Endpoint:
        - User::UpgradeAndVerify(): "%s/v3/public/namespaces/%s/users/me/headless/code/verify"
    - Response Changes:
        - Register: FUserData -> FRegisterResponse
- Integration Test
  - Follow new password input restriction
  - Statistic: add test teardown
- Model
  - Add GeneralModels
  - Add FBan and FPermission on UserModels
  - Add FRegisterResponse
  - Update UserData
## 2.0.0 (2019-09-06)
## Added
- Session Management
  - Implementing API Gateway
- Supported Game Profile Service Features
  - Create Game Profile
  - Get Game Profile
  - Update Game Profile
  - Delete Game Profile
- Supported Statistic Service Features
  - Get StatItem
  - Update StatItem from Client
- Supported Lobby Service Features
  - Ready Consent
  - DS Notif
- Updated to v2.0.0 for Justice release v2.0.0 

## 1.0.0-beta.1 (2019-03-13)
### Added

- Supported IAM Service Features:
  - Login With Username and Password
  - Login With Other Platforms (Google, Facebook, and Steam)
  - Login With AccelByte Launcher
  - Login With Device ID
  - User Registration
  - User Verification (via email)
  - Upgrade device account and other platform account to proper AccelByte account with username and password
  - Update User Data
- Supported Basic Service Features
  - Create User Profile
  - Get User Profile
  - Update User Profile
  - Delete User Profile
- Supported Platform and E-Commerce Service Features:
  - Get Wallet Info
  - Create Order
  - Get Entitlements
  - Browse catalog (categories and items)
- Supported Lobby Service Features
  - Private Chat
  - Party
  - Friends
  - Matchmaking
  - Notification