# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.0.5](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v1.0.4...v1.0.5) (2021-04-08)

### [1.0.4](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v1.0.3...v1.0.4) (2020-12-30)


### Bug Fixes

* fix wrong setting of criticalCss option ([eb50379](https://github.com/freddy38510/quasar-app-extension-ssg/commit/eb5037970c32f267d41a84b14af74027bee19ba7))

### [1.0.3](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v1.0.2...v1.0.3) (2020-12-16)


### Bug Fixes

* **workbox:** compile service worker for InjectManifest mode ([dc2fd5c](https://github.com/freddy38510/quasar-app-extension-ssg/commit/dc2fd5cbcc00662536cda58af6bfd47d1266e4b4)), closes [#32](https://github.com/freddy38510/quasar-app-extension-ssg/issues/32)
* **workbox:** keep default options close to Quasar ones ([ed42942](https://github.com/freddy38510/quasar-app-extension-ssg/commit/ed42942a5e522c4b9f3d0a43ff4a992afe57a362))

### [1.0.2](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v1.0.1...v1.0.2) (2020-12-14)


### Bug Fixes

* **workbox:** add missing injectManifest method ([6ccc578](https://github.com/freddy38510/quasar-app-extension-ssg/commit/6ccc578463c7630dff6eef4273a7a166171eb38c)), closes [#31](https://github.com/freddy38510/quasar-app-extension-ssg/issues/31)
* **workbox:** delete exclude option after all user options have been merged ([c053d0a](https://github.com/freddy38510/quasar-app-extension-ssg/commit/c053d0a8a1b8006be2c298fb65fef6a18520bfd7))

### [1.0.1](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v1.0.0...v1.0.1) (2020-11-30)


### Bug Fixes

* make @quasar/app v2.0.0 compatible ([237e92b](https://github.com/freddy38510/quasar-app-extension-ssg/commit/237e92be348430ee15617e4a15209161c3001f87))

## [1.0.0](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.8...v1.0.0) (2020-11-29)


### Features

* add an option to disable/enable critical css ([13d7bfe](https://github.com/freddy38510/quasar-app-extension-ssg/commit/13d7bfe5f318137f85c25049bd13cad3ff0feeb9))

### [0.9.8](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.7...v0.9.8) (2020-10-08)


### Bug Fixes

* make extension compatible with @quasar/app below v2.0.0 ([e3a7ce4](https://github.com/freddy38510/quasar-app-extension-ssg/commit/e3a7ce4e19f52de30cc997a596250e0b88df846f)), closes [#26](https://github.com/freddy38510/quasar-app-extension-ssg/issues/26)

### [0.9.7](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.6...v0.9.7) (2020-09-17)


### Features

* add inspect command ([2cd21a2](https://github.com/freddy38510/quasar-app-extension-ssg/commit/2cd21a2abaaa08524f4493bde5e6c88d2bca6233))


### Bug Fixes

* **server:** use http-proxy-middleware the right way for its v0.19 version ([1c7d714](https://github.com/freddy38510/quasar-app-extension-ssg/commit/1c7d7148ec09af51dd9ea0d13bf4314cd2d7149a))
* remove http-proxy-middleware from dependencies and require it from Quasar ([1d298d5](https://github.com/freddy38510/quasar-app-extension-ssg/commit/1d298d53aa48e016faf68f4e944a07d7e61dd208)), closes [#24](https://github.com/freddy38510/quasar-app-extension-ssg/issues/24)
* **inspect:** print right usage when help paramater is provided ([44c5a62](https://github.com/freddy38510/quasar-app-extension-ssg/commit/44c5a62f17f09142f811e39af4d09fbbe6fb0afd))

### [0.9.6](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.5...v0.9.6) (2020-09-16)


### Features

* **build:** add compatibility for future version 2.1 of "@quasar/app" ([afd9e25](https://github.com/freddy38510/quasar-app-extension-ssg/commit/afd9e2549dde6fb44dcf964a534183db97067294))


### Bug Fixes

* **build:** fix compatibility with @quasar/app 2.1.0 ([588dfd9](https://github.com/freddy38510/quasar-app-extension-ssg/commit/588dfd9eb384912ed3c1a0340cc058670bb6bfdf)), closes [#25](https://github.com/freddy38510/quasar-app-extension-ssg/issues/25)

### [0.9.5](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.4...v0.9.5) (2020-09-10)


### Features

* provide an option via prompts to inline critical CSS ([d682826](https://github.com/freddy38510/quasar-app-extension-ssg/commit/d6828266a1b038d1791031cab58b4a75c52700cd)), closes [#23](https://github.com/freddy38510/quasar-app-extension-ssg/issues/23)


### Bug Fixes

* **prompts:** use default distDir for serve:ssg script ([fcd4e96](https://github.com/freddy38510/quasar-app-extension-ssg/commit/fcd4e96c5e8f7bcfe370478ce85cf09d8073df2e))

### [0.9.4](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.3...v0.9.4) (2020-09-02)


### Features

* **prompts:** add scripts for building and serving to package.json ([b93e310](https://github.com/freddy38510/quasar-app-extension-ssg/commit/b93e31058743502d07a2eaa0572ecf5772593088)), closes [#21](https://github.com/freddy38510/quasar-app-extension-ssg/issues/21)

### [0.9.3](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.2...v0.9.3) (2020-09-01)


### Bug Fixes

* **quasarconf:** use custom distDir when provided ([6b4ad3f](https://github.com/freddy38510/quasar-app-extension-ssg/commit/6b4ad3faecc54825a7c6ce58cb5b417a69cd4867)), closes [#20](https://github.com/freddy38510/quasar-app-extension-ssg/issues/20)

### [0.9.2](https://github.com/freddy38510/quasar-app-extension-ssg/compare/v0.9.1...v0.9.2) (2020-08-30)


### Bug Fixes

* **workbox:** do not fallback when navigating to service-worker and workbox ([e42ff45](https://github.com/freddy38510/quasar-app-extension-ssg/commit/e42ff455b43c36d10d2160b2b4d6a2d0fcd2e0c4))

### 0.9.1 (2020-08-21)


### Bug Fixes

* **serve:** use posix paths ([99aa6b5](https://github.com/freddy38510/quasar-app-extension-ssg/commit/99aa6b5c8a82c989b1c00503ecfa6116d89192f2)), closes [#17](https://github.com/freddy38510/quasar-app-extension-ssg/issues/17)
