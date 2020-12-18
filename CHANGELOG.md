# Changelog

## [3.3.0](https://www.github.com/rchenzheng/streetmerchant/compare/v3.2.0...v3.3.0) (2020-12-18)


### Features

* remove stale user agents, use top 50 ([6e2a162](https://www.github.com/rchenzheng/streetmerchant/commit/6e2a16238c54bc448f3ae5243ef8729f384ea59b))
* **azerty:** add ryzen 5000 series  ([#878](https://www.github.com/rchenzheng/streetmerchant/issues/878)) ([ca59777](https://www.github.com/rchenzheng/streetmerchant/commit/ca59777917777401affc5b72a68238983f286237))
* **discord:** dynamic currency symbol ([#1328](https://www.github.com/rchenzheng/streetmerchant/issues/1328)) ([cccfde2](https://www.github.com/rchenzheng/streetmerchant/commit/cccfde245affc11506c69d1ef6c30c09953307d4))
* **docs:** add mkdocs ([243109a](https://www.github.com/rchenzheng/streetmerchant/commit/243109a4ffdfe1d1efe961af0b5cf28fd7e6ef1d))
* **docs:** add table sorting ([#1258](https://www.github.com/rchenzheng/streetmerchant/issues/1258)) ([5955d10](https://www.github.com/rchenzheng/streetmerchant/commit/5955d10a7f2106c5ae1275fadacf2945626ca008))
* **lookup:** handle Cloudflare DDoS protection ([#1434](https://www.github.com/rchenzheng/streetmerchant/issues/1434)) ([f86a825](https://www.github.com/rchenzheng/streetmerchant/commit/f86a8259f37f0ed25b00e243b29aa28c3e68bdff)), closes [#1297](https://www.github.com/rchenzheng/streetmerchant/issues/1297)
* **lookup:** use random user agents ([#1335](https://www.github.com/rchenzheng/streetmerchant/issues/1335)) ([b599c23](https://www.github.com/rchenzheng/streetmerchant/commit/b599c23b51735212e5369ce03a44bbd1bccafa42))
* **notification:** add discord groups ([#1211](https://www.github.com/rchenzheng/streetmerchant/issues/1211)) ([2632386](https://www.github.com/rchenzheng/streetmerchant/commit/2632386a5b99f3b23166e88f92af809f0036a6b7))
* **notification:** add sound player executable option ([#1301](https://www.github.com/rchenzheng/streetmerchant/issues/1301)) ([8d19231](https://www.github.com/rchenzheng/streetmerchant/commit/8d192317badfd71a7cd8f0115ba9e6fc951c1874))
* **playstation:** add queuing selector ([#1173](https://www.github.com/rchenzheng/streetmerchant/issues/1173)) ([67b19a7](https://www.github.com/rchenzheng/streetmerchant/commit/67b19a7a8b3dead5f5ab9575ee2b4f09924ce851))
* **proxy:** fallback to a global proxy list ([#1388](https://www.github.com/rchenzheng/streetmerchant/issues/1388)) ([be1953b](https://www.github.com/rchenzheng/streetmerchant/commit/be1953b2069fce72969904c1bc18055df73f4b6b))
* **store:** add darkhero motherboard to asus and microcenter ([#1336](https://www.github.com/rchenzheng/streetmerchant/issues/1336)) ([29175c7](https://www.github.com/rchenzheng/streetmerchant/commit/29175c77a8fcbc082c944b057a919dfcc22ba606))
* **store:** add EBGames ([#1281](https://www.github.com/rchenzheng/streetmerchant/issues/1281)) ([27cfb94](https://www.github.com/rchenzheng/streetmerchant/commit/27cfb94de8d9ccef3c7fc76b250aee17d7c80257))
* **store:** add Irish store variants ([#1373](https://www.github.com/rchenzheng/streetmerchant/issues/1373)) ([f70998f](https://www.github.com/rchenzheng/streetmerchant/commit/f70998f0d9a6cdfbc59fb31fecb87f801b0b3037))
* **store:** add Megekko ([#1216](https://www.github.com/rchenzheng/streetmerchant/issues/1216)) ([30bed2a](https://www.github.com/rchenzheng/streetmerchant/commit/30bed2ac016e9e543f67b1098819a484bc1394c3))
* **store:** add several Australian stores, add some 3080 brands/models ([#1367](https://www.github.com/rchenzheng/streetmerchant/issues/1367)) ([579cb97](https://www.github.com/rchenzheng/streetmerchant/commit/579cb97a0d151cc374a37493b043ba4a399b55db))
* **store:** add Toys R Us ([#1257](https://www.github.com/rchenzheng/streetmerchant/issues/1257)) ([ac0bd2a](https://www.github.com/rchenzheng/streetmerchant/commit/ac0bd2ac14d686a0f30931e885da65a1d7af6856))
* **store:** add Walmart (CA) ([#1253](https://www.github.com/rchenzheng/streetmerchant/issues/1253)) ([b535b47](https://www.github.com/rchenzheng/streetmerchant/commit/b535b470cad38af034889b4d27578b20136e166d))


### Bug Fixes

* **adblock:** proxy another function to produce less errors ([#1379](https://www.github.com/rchenzheng/streetmerchant/issues/1379)) ([eb70076](https://www.github.com/rchenzheng/streetmerchant/commit/eb700762a4eee3a802bd81f0fb62e76243027c42))
* **amazon-it:** maxPrice selector and links ([#1239](https://www.github.com/rchenzheng/streetmerchant/issues/1239)) ([84f2cb7](https://www.github.com/rchenzheng/streetmerchant/commit/84f2cb7d52fac7c3dbdd31318a51330e25808784))
* **amazon-nl:** inStock selector ([b6964b0](https://www.github.com/rchenzheng/streetmerchant/commit/b6964b02f38c947fd476d86de35d5983e5b229dd)), closes [#1366](https://www.github.com/rchenzheng/streetmerchant/issues/1366)
* **bestbuy-ca:** add outOfStock text ([58f0a9c](https://www.github.com/rchenzheng/streetmerchant/commit/58f0a9c7740c46f3d820c8765dee5b0fc8516353)), closes [#1269](https://www.github.com/rchenzheng/streetmerchant/issues/1269)
* **bestbuy-ca:** update selectors to help false positives ([#1278](https://www.github.com/rchenzheng/streetmerchant/issues/1278)) ([0525119](https://www.github.com/rchenzheng/streetmerchant/commit/0525119b9bae47425a6c01720d6a1ea6ab8e6a02)), closes [#895](https://www.github.com/rchenzheng/streetmerchant/issues/895)
* **ci:** mkdocs deps ([1f63e99](https://www.github.com/rchenzheng/streetmerchant/commit/1f63e9980499ac567845473dc48e51cab78c838e))
* **config:** disable docker by default ([dca916b](https://www.github.com/rchenzheng/streetmerchant/commit/dca916b64e9ac2d05d5e6af19e5466b8a0623ed5))
* **config:** remove quotes ([ef452d8](https://www.github.com/rchenzheng/streetmerchant/commit/ef452d8e586536a5039ee532d655d2951d551ac3))
* **discord:** notification groupings ([ad0b2fe](https://www.github.com/rchenzheng/streetmerchant/commit/ad0b2fe525d6403735ddcbf4ef55b91eb36ac10a))
* **docker:** run in docker, and build scripts for docker ([#1291](https://www.github.com/rchenzheng/streetmerchant/issues/1291)) ([c74ea28](https://www.github.com/rchenzheng/streetmerchant/commit/c74ea28014ee0d827ea216083844f92e30f142c9))
* **eprice:** inStock selector ([5e1dfc3](https://www.github.com/rchenzheng/streetmerchant/commit/5e1dfc35680029620a1de7bc7a523140f2dae8af)), closes [#1067](https://www.github.com/rchenzheng/streetmerchant/issues/1067)
* **lookup:** check out of stock before price ([#1422](https://www.github.com/rchenzheng/streetmerchant/issues/1422)) ([02d29c3](https://www.github.com/rchenzheng/streetmerchant/commit/02d29c3c64a7976622da6cbdf099b76b455082d0))
* **lookup:** remove mobile versions of user agent ([96ae818](https://www.github.com/rchenzheng/streetmerchant/commit/96ae818e84c99d0597e0ddd7b5ecfe1a0615d1ed))
* **newegg:** dedupe nitro+ models ([#1300](https://www.github.com/rchenzheng/streetmerchant/issues/1300)) ([7329c6e](https://www.github.com/rchenzheng/streetmerchant/commit/7329c6ede0a5ab6d644b30ac878f4e7da11e43a8)), closes [#1230](https://www.github.com/rchenzheng/streetmerchant/issues/1230)
* **newegg:** price selector and mobile inStock ([c3beedc](https://www.github.com/rchenzheng/streetmerchant/commit/c3beedced82141e6bbb0735b3edb7c573907aa7a)), closes [#1356](https://www.github.com/rchenzheng/streetmerchant/issues/1356)
* **proxy:** fix requests with proxies ([#1408](https://www.github.com/rchenzheng/streetmerchant/issues/1408)) ([f65df4c](https://www.github.com/rchenzheng/streetmerchant/commit/f65df4ce56891c368dab8dd6fe85a584cf9e6f49))
* **proxy:** update proxy module ([#1451](https://www.github.com/rchenzheng/streetmerchant/issues/1451)) ([ab03702](https://www.github.com/rchenzheng/streetmerchant/commit/ab037029b654f5e169a97c9e7a2c4dfa6cf1e768)), closes [#1437](https://www.github.com/rchenzheng/streetmerchant/issues/1437)
* **store:** italian store checks ([#1212](https://www.github.com/rchenzheng/streetmerchant/issues/1212)) ([e3eb386](https://www.github.com/rchenzheng/streetmerchant/commit/e3eb38655a3cefb85c4dbd573494955e06c72f71))
* **store:** update UK stores ([#1372](https://www.github.com/rchenzheng/streetmerchant/issues/1372)) ([02825d0](https://www.github.com/rchenzheng/streetmerchant/commit/02825d009bd028f6dcdca02e2c155e77a7df8654))
* **webui:** handling of file serving ([#1383](https://www.github.com/rchenzheng/streetmerchant/issues/1383)) ([445689e](https://www.github.com/rchenzheng/streetmerchant/commit/445689efc49bf8edb0b5a027611f02ea0d0f126f))
* `.env` backwards compatibility ([9b7c7e2](https://www.github.com/rchenzheng/streetmerchant/commit/9b7c7e2881d756909af191094bda435ca7ef7e9b))
* add setRequestInterception ([#1312](https://www.github.com/rchenzheng/streetmerchant/issues/1312)) ([a44621f](https://www.github.com/rchenzheng/streetmerchant/commit/a44621f8f50cac9ba6614b0f89320d210370047a)), closes [#826](https://www.github.com/rchenzheng/streetmerchant/issues/826)
* **pushover:** add `expire` and `retry` ([0072dda](https://www.github.com/rchenzheng/streetmerchant/commit/0072dda90b637b93647cf3a35dc612cf43d89445)), closes [#983](https://www.github.com/rchenzheng/streetmerchant/issues/983)


### Reverts

* allow users to still use `USER_AGENT` ([3386e8f](https://www.github.com/rchenzheng/streetmerchant/commit/3386e8f50da27a800c5289c3b6bd7a1f76e77a49))
