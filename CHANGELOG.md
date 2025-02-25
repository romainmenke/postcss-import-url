# [7.1.0](https://github.com/unlight/postcss-import-url/compare/v7.0.0...v7.1.0) (2022-11-30)


### Features

* Support imports into `[@layer](https://github.com/layer)` ([7f42a8e](https://github.com/unlight/postcss-import-url/commit/7f42a8eb0e0bd547a135413de0e157770615fcf5)), closes [#28](https://github.com/unlight/postcss-import-url/issues/28)

# [7.0.0](https://github.com/unlight/postcss-import-url/compare/v6.0.4...v7.0.0) (2021-02-13)


### Bug Fixes

* Set element source property [#27](https://github.com/unlight/postcss-import-url/issues/27) ([a4687df](https://github.com/unlight/postcss-import-url/commit/a4687dfb5c9a77531b6869711d1ce38d09d17a6a))


### BREAKING CHANGES

* Node LTS is required (v12+)

## [6.0.4](https://github.com/unlight/postcss-import-url/compare/v6.0.3...v6.0.4) (2021-02-13)


### Bug Fixes

* Revert set element source property ([da4afb8](https://github.com/unlight/postcss-import-url/commit/da4afb82207ebcb04871eac184e2866528f5f9a1))

## [6.0.3](https://github.com/unlight/postcss-import-url/compare/v6.0.2...v6.0.3) (2021-02-13)


### Bug Fixes

* Set element source property ([da96061](https://github.com/unlight/postcss-import-url/commit/da96061bdd53253e02bc23e1ce86d2e38347aeed)), closes [#27](https://github.com/unlight/postcss-import-url/issues/27)

## [6.0.2](https://github.com/unlight/postcss-import-url/compare/v6.0.1...v6.0.2) (2021-02-13)


### Bug Fixes

* Revert set element source property ([e7207c8](https://github.com/unlight/postcss-import-url/commit/e7207c8ea7ad2f28e8ae2771781b4e20d38dd8e3))

## [6.0.1](https://github.com/unlight/postcss-import-url/compare/v6.0.0...v6.0.1) (2021-02-13)


### Bug Fixes

* Set element source property ([8405f32](https://github.com/unlight/postcss-import-url/commit/8405f32b9aa09bef534e67717bf7de3d52477547)), closes [#27](https://github.com/unlight/postcss-import-url/issues/27)

# [6.0.0](https://github.com/unlight/postcss-import-url/compare/v5.1.0...v6.0.0) (2020-12-09)


### Features

* Support PostCSS v8 ([2d17367](https://github.com/unlight/postcss-import-url/commit/2d173670da93ab88a428ade3a05a792f79503b7e))


### BREAKING CHANGES

* Support PostCSS v8

# [5.1.0](https://github.com/unlight/postcss-import-url/compare/v5.0.0...v5.1.0) (2020-04-04)


### Features

* supports multiple url resolves ([4997931](https://github.com/unlight/postcss-import-url/commit/4997931bf216c8b740fae7518c13cb457e840053))

# [5.0.0](https://github.com/unlight/postcss-import-url/compare/v4.0.0...v5.0.0) (2020-03-01)


### chore

* Added development stuff (prettier, eslint, etc.) ([70e5497](https://github.com/unlight/postcss-import-url/commit/70e5497a750dd7e7935ed4f08fde76f30b69b955))


### Features

* Resolve relative URLs in property values ([c11c03d](https://github.com/unlight/postcss-import-url/commit/c11c03d10f8d5016d4cec811f40fed6f6140e6f1))


### BREAKING CHANGES

* Node 10+ is required

# [4.0.0](https://github.com/unlight/postcss-import-url/compare/v3.0.4...v4.0.0) (2019-01-03)


### chore

* Updated dependencies ([b1ed8b2](https://github.com/unlight/postcss-import-url/commit/b1ed8b2))


### Features

* Added semantic release ([69c494a](https://github.com/unlight/postcss-import-url/commit/69c494a))


### BREAKING CHANGES

* Node 6+ is required now

## 3.X.X

* 3.0.4 (04 Jan 2018) - fixed [#15](https://github.com/unlight/postcss-import-url/issues/15)
* 3.0.3 (02 Jan 2018) - fixed [#13](https://github.com/unlight/postcss-import-url/issues/13), set peer dependency as range >=6 <7
* 3.0.1 (30 Oct 2017) - updated dependencies (postcss 6), moved postcss to peerDependencies
* 3.0.0 (27 Oct 2017) - using `atRule.source.input.file` to resolve urls
* 2.2.0 (19 Nov 2016) - added option modernBrowser
* 2.1.1 (19 Oct 2016) - added to readme google font notice
* 2.1.0 (09 Jul 2016) - replaced Object.assign by _.assign
* 2.0.0 (08 Jul 2016) - added recursive option
* 1.0.0 (01 Nov 2015) - first release
