## [1.2.2](https://github.com/adobe/helix-static/compare/v1.2.1...v1.2.2) (2019-07-05)


### Bug Fixes

* **package:** use latest pingdom-status 1.4.1 ([9513ce1](https://github.com/adobe/helix-static/commit/9513ce1))

## [1.2.1](https://github.com/adobe/helix-static/compare/v1.2.0...v1.2.1) (2019-06-26)


### Bug Fixes

* **package:** update postcss-value-parser to version 4.0.0 ([7290499](https://github.com/adobe/helix-static/commit/7290499))

# [1.2.0](https://github.com/adobe/helix-static/compare/v1.1.0...v1.2.0) (2019-06-26)


### Bug Fixes

* **package:** add [@adobe](https://github.com/adobe) scope to package name ([7c37743](https://github.com/adobe/helix-static/commit/7c37743))


### Features

* **monitoring:** establish consistent monitoring with helix-pingdom-status and epsagon ([aca4c24](https://github.com/adobe/helix-static/commit/aca4c24))

# [1.1.0](https://github.com/adobe/helix-static/compare/v1.0.2...v1.1.0) (2019-05-16)


### Bug Fixes

* **monitoring:** ping this repository instead of helix-publish ([69b7af1](https://github.com/adobe/helix-static/commit/69b7af1)), closes [/github.com/adobe/helix-static/pull/5#discussion_r284569556](https://github.com//github.com/adobe/helix-static/pull/5/issues/discussion_r284569556)


### Features

* **monitoring:** make monitoring response uncacheable ([f139c87](https://github.com/adobe/helix-static/commit/f139c87)), closes [/github.com/adobe/helix-static/pull/5#discussion_r284570089](https://github.com//github.com/adobe/helix-static/pull/5/issues/discussion_r284570089)
* **monitoring:** report status, reponse time and version to Pingdom ([66ffb60](https://github.com/adobe/helix-static/commit/66ffb60)), closes [#4](https://github.com/adobe/helix-static/issues/4)

## [1.0.2](https://github.com/adobe/helix-static/compare/v1.0.1...v1.0.2) (2019-05-14)


### Bug Fixes

* **docs:** trigger re-release due to invalid config ([20743cb](https://github.com/adobe/helix-static/commit/20743cb))

## [1.0.1](https://github.com/adobe/helix-static/compare/v1.0.0...v1.0.1) (2019-05-14)


### Bug Fixes

* **deploy:** use correct package name when deploying ([287ffad](https://github.com/adobe/helix-static/commit/287ffad))

# 1.0.0 (2019-05-14)


### Bug Fixes

* **static:** always return entry path for 404 errors ([552ef3d](https://github.com/adobe/helix-static/commit/552ef3d))
* **static:** cache error responses for 5 minutes ([3173cea](https://github.com/adobe/helix-static/commit/3173cea))
* **static:** handle more 404 errors with path ([2c1ac18](https://github.com/adobe/helix-static/commit/2c1ac18))
* **static:** normalize URLs in rewritten CSS and JS ([f238adb](https://github.com/adobe/helix-static/commit/f238adb))
* **static:** prevent possible XSS by sanitizing output ([0795581](https://github.com/adobe/helix-static/commit/0795581))
* **static:** return the original URL in case a static resource cannot get retieved for an ESI include ([453c724](https://github.com/adobe/helix-static/commit/453c724)), closes [#813](https://github.com/adobe/helix-static/issues/813)
* **static:** turn on ESI processing when ESI flag is set ([a6d96b8](https://github.com/adobe/helix-static/commit/a6d96b8))
* **static:** use .url instead of .esi as extension for immutable resources ([d6c89f8](https://github.com/adobe/helix-static/commit/d6c89f8))


### Features

* **pipeline:** consistently use `context` instead of payload. ([ddea2cb](https://github.com/adobe/helix-static/commit/ddea2cb)), closes [#743](https://github.com/adobe/helix-static/issues/743)
* **static:** add ESI aliasing support for JavaScript modules ([6c0d0d5](https://github.com/adobe/helix-static/commit/6c0d0d5)), closes [/github.com/adobe/helix-pipeline/issues/224#issuecomment-476690621](https://github.com//github.com/adobe/helix-pipeline/issues/224/issues/issuecomment-476690621)
* **static:** Rewrite CSS URLs to Static ESI URLs so that better caching can be achieved ([75b47e5](https://github.com/adobe/helix-static/commit/75b47e5)), closes [adobe/helix-publish#61](https://github.com/adobe/helix-publish/issues/61) [adobe/helix-pipeline#267](https://github.com/adobe/helix-pipeline/issues/267)