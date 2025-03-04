# Changelog

## [3.5.0](https://github.com/nodejs/node-core-utils/compare/v3.4.2...v3.5.0) (2023-09-24)


### Features

* create git-node security release command ([#715](https://github.com/nodejs/node-core-utils/issues/715)) ([6d68c99](https://github.com/nodejs/node-core-utils/commit/6d68c99f3dd7b90b8de552c3a1f42583e1212459))
* **git-node:** improve backport workflow ([#732](https://github.com/nodejs/node-core-utils/issues/732)) ([be11c08](https://github.com/nodejs/node-core-utils/commit/be11c0840a6e3435b0619b40468cfc830686205e))
* **release:** add skipBranchDiff option ([#724](https://github.com/nodejs/node-core-utils/issues/724)) ([d103f28](https://github.com/nodejs/node-core-utils/commit/d103f281f1d2649627f06b3d52525f9445a6eee6))

## [3.4.2](https://github.com/nodejs/node-core-utils/compare/v3.4.1...v3.4.2) (2023-09-15)


### Bug Fixes

* **v8:** fix `git node v8 backport` ([#728](https://github.com/nodejs/node-core-utils/issues/728)) ([ba4e0c0](https://github.com/nodejs/node-core-utils/commit/ba4e0c0b3238a3747824c905e0fdbf10ac9b6516))

## [3.4.1](https://github.com/nodejs/node-core-utils/compare/v3.4.0...v3.4.1) (2023-09-12)


### Bug Fixes

* **v8:** fix spawning of subprocesses ([#726](https://github.com/nodejs/node-core-utils/issues/726)) ([992f9eb](https://github.com/nodejs/node-core-utils/commit/992f9eb44ac9086e950e11a2e6dc2a7dfa54dd3c))

## [3.4.0](https://github.com/nodejs/node-core-utils/compare/v3.3.0...v3.4.0) (2023-09-04)


### Features

* add autocomplete ([#720](https://github.com/nodejs/node-core-utils/issues/720)) ([6efa5ed](https://github.com/nodejs/node-core-utils/commit/6efa5ed36918dbf77e26015ec301f906473ecaac))
* **git-node:** add `git node vote` ([#704](https://github.com/nodejs/node-core-utils/issues/704)) ([7b9d962](https://github.com/nodejs/node-core-utils/commit/7b9d9622643791062ee161542ebb0a2145f698fa))


### Bug Fixes

* fix security proposal filterLabel ([#717](https://github.com/nodejs/node-core-utils/issues/717)) ([4bf1e32](https://github.com/nodejs/node-core-utils/commit/4bf1e322ee96f6bd5128173ce3338566e5e37e1c))

## [3.3.0](https://github.com/nodejs/node-core-utils/compare/v3.2.1...v3.3.0) (2023-07-13)


### Features

* support security release prepare ([#665](https://github.com/nodejs/node-core-utils/issues/665)) ([bdc9a6b](https://github.com/nodejs/node-core-utils/commit/bdc9a6bbcef523b064d5f04f53f320eb7dd2655d))

## [3.2.1](https://github.com/nodejs/node-core-utils/compare/v3.2.0...v3.2.1) (2023-07-04)


### Bug Fixes

* enforce markdown when generating changelog ([#711](https://github.com/nodejs/node-core-utils/issues/711)) ([80b9550](https://github.com/nodejs/node-core-utils/commit/80b9550c7f3261b07db6add9d95233ae127f86cd))
* update changelog list when preparing release ([#712](https://github.com/nodejs/node-core-utils/issues/712)) ([418f194](https://github.com/nodejs/node-core-utils/commit/418f194d81d4933e1a73de967d4bbc9fa66cfce4))

## [3.2.0](https://github.com/nodejs/node-core-utils/compare/v3.1.0...v3.2.0) (2023-06-26)


### Features

* **git-node:** add support for `amend!` commits ([#710](https://github.com/nodejs/node-core-utils/issues/710)) ([d8ae7c7](https://github.com/nodejs/node-core-utils/commit/d8ae7c76d7dbc6e9e75b9b3521e7c5fab9ee6400))


### Bug Fixes

* **git-node:** properly terminate pr landing sessions ([#708](https://github.com/nodejs/node-core-utils/issues/708)) ([015bf20](https://github.com/nodejs/node-core-utils/commit/015bf203aecb918d9af7949280c9b8c936fef7b7))

## [3.1.0](https://github.com/nodejs/node-core-utils/compare/v3.0.0...v3.1.0) (2023-06-12)


### Features

* **git-node:** add support for the `--gpg-sign` git flag ([#684](https://github.com/nodejs/node-core-utils/issues/684)) ([92d621e](https://github.com/nodejs/node-core-utils/commit/92d621eebc5bd2d9548d9f728ebfb2ac7d64f62c))
* **land:** allow empty commits with fixupAll ([#681](https://github.com/nodejs/node-core-utils/issues/681)) ([e0d6d0d](https://github.com/nodejs/node-core-utils/commit/e0d6d0dea47f594fef7d311501d3719401819fb5))


### Bug Fixes

* accurately define ncu-ci report condition ([#697](https://github.com/nodejs/node-core-utils/issues/697)) ([02a9163](https://github.com/nodejs/node-core-utils/commit/02a91637010fffff1dca46350627cfff4787e8da))
* **pr_checker:** do not count non-approving reviews ([#680](https://github.com/nodejs/node-core-utils/issues/680)) ([b9c443b](https://github.com/nodejs/node-core-utils/commit/b9c443b8b2240a6c6343fa8eb803ce5370118936))
* update maintaining-dependencies.md on major v8 update ([#699](https://github.com/nodejs/node-core-utils/issues/699)) ([a8b1812](https://github.com/nodejs/node-core-utils/commit/a8b181218459652a088f912a94be6c1f05aaf853))
* use correct V8 tag for minor updates ([#695](https://github.com/nodejs/node-core-utils/issues/695)) ([cf03df4](https://github.com/nodejs/node-core-utils/commit/cf03df4a0ef1cd3d4951cf2603b7b01987dd5daa))

## [3.0.0](https://github.com/nodejs/node-core-utils/compare/v2.1.3...v3.0.0) (2023-03-08)


### ⚠ BREAKING CHANGES

* Node.js 14.x is no longer supported.

### Features

* ignore .md files when do `requiresJenkinsRun` check ([#641](https://github.com/nodejs/node-core-utils/issues/641)) ([62f266f](https://github.com/nodejs/node-core-utils/commit/62f266fa685d849ef43943ed0e816fcab4b8affe))


### Bug Fixes

* do not run `git cherry-pick --abort` on failure ([#671](https://github.com/nodejs/node-core-utils/issues/671)) ([1e6f5d3](https://github.com/nodejs/node-core-utils/commit/1e6f5d3cbc7e837f1590122458b15f24ff9b378d))
* switch to undici for requests to fix stream close errors ([#666](https://github.com/nodejs/node-core-utils/issues/666)) ([f759e7a](https://github.com/nodejs/node-core-utils/commit/f759e7a9495bb079abcbbcc5c2df4f311e67b779))
* treat `fast-track` with not enough approvals as non-fatal ([#676](https://github.com/nodejs/node-core-utils/issues/676)) ([b324c99](https://github.com/nodejs/node-core-utils/commit/b324c99bca3a77be9076a208598b34196cf9413b))
* use correct V8 tag for major updates ([#675](https://github.com/nodejs/node-core-utils/issues/675)) ([ebcf18e](https://github.com/nodejs/node-core-utils/commit/ebcf18e402d5a3e647c7eae6fb799f3a049ee244))
* **wpt:** remove stale fixtures before pulling fresh ones ([#679](https://github.com/nodejs/node-core-utils/issues/679)) ([b78efc5](https://github.com/nodejs/node-core-utils/commit/b78efc5199856d11157de45ccb06d2ce34cb2b56))

## [2.1.3](https://github.com/nodejs/node-core-utils/compare/v2.1.2...v2.1.3) (2022-12-06)


### Bug Fixes

* **cli:** handle spinning states ([51a3b24](https://github.com/nodejs/node-core-utils/commit/51a3b24aaeacb5c9b71c94cb8d024b2d2935fa06))

## [2.1.2](https://github.com/nodejs/node-core-utils/compare/v2.1.1...v2.1.2) (2022-11-22)


### Bug Fixes

* use case-insensitive string comparison for fast-track approvals ([#658](https://github.com/nodejs/node-core-utils/issues/658)) ([8ad4b37](https://github.com/nodejs/node-core-utils/commit/8ad4b377c270e8495a8cf8fece1e6a439304e327))
* **v8:** add ittapi as V8 dependency ([#552](https://github.com/nodejs/node-core-utils/issues/552)) ([20713c0](https://github.com/nodejs/node-core-utils/commit/20713c08b4ba7b594b1179bd7e3991f41bd49319))

## [2.1.1](https://github.com/nodejs/node-core-utils/compare/v2.1.0...v2.1.1) (2022-10-27)


### Bug Fixes

* add missing await ([#655](https://github.com/nodejs/node-core-utils/issues/655)) ([7e4dc88](https://github.com/nodejs/node-core-utils/commit/7e4dc886f7b2030457cda5d89bb84759a0012466))

## [2.1.0](https://github.com/nodejs/node-core-utils/compare/v2.0.1...v2.1.0) (2022-10-22)


### Features

* add --since option to ncu-ci ([#649](https://github.com/nodejs/node-core-utils/issues/649)) ([e01ca12](https://github.com/nodejs/node-core-utils/commit/e01ca12368677e1f8f72f97c4170b386cb250fb8))
* add auto run v8 ci ([046bc0d](https://github.com/nodejs/node-core-utils/commit/046bc0dbea44dafdb42f92bc1006d7cdd7a5f286))


### Bug Fixes

* only parse commit messages during git node backport analysis ([#651](https://github.com/nodejs/node-core-utils/issues/651)) ([4e59a64](https://github.com/nodejs/node-core-utils/commit/4e59a647a1ffd87b79ad953936d20de495505bd0))

## [2.0.1](https://github.com/nodejs/node-core-utils/compare/v2.0.0...v2.0.1) (2022-07-31)


### Bug Fixes

* add a specific error message for the commit queue ([#645](https://github.com/nodejs/node-core-utils/issues/645)) ([3d6ece6](https://github.com/nodejs/node-core-utils/commit/3d6ece6e2d25d66be1fcec65eea26ae695f793e8))
* parse ci failure error ([#640](https://github.com/nodejs/node-core-utils/issues/640)) ([0d49eda](https://github.com/nodejs/node-core-utils/commit/0d49edaf6736b393b0597ee67d70381cd5841b40))
* respect existing trailers in commit messages ([#632](https://github.com/nodejs/node-core-utils/issues/632)) ([f442797](https://github.com/nodejs/node-core-utils/commit/f44279701b6a426341e1e665d16e0182a5787336))

## [2.0.0](https://github.com/nodejs/node-core-utils/compare/v1.31.4...v2.0.0) (2022-06-22)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 12 and 17.

### Bug Fixes

* broken enquirer in listr2 ([#636](https://github.com/nodejs/node-core-utils/issues/636)) ([460b50d](https://github.com/nodejs/node-core-utils/commit/460b50dcea878a6234021448441395efefaeb2bf))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([40a1ee2](https://github.com/nodejs/node-core-utils/commit/40a1ee220b058a1ce2b6e513d75d2a5ea0124633))

### [1.31.4](https://github.com/nodejs/node-core-utils/compare/v1.31.3...v1.31.4) (2022-04-25)


### Bug Fixes

* add trailing line feed to formatted JSON ([#623](https://github.com/nodejs/node-core-utils/issues/623)) ([1bcc72b](https://github.com/nodejs/node-core-utils/commit/1bcc72baa60c8d660f1b493c09017d1da4093b8c))
* check last fast-track request comment ([#606](https://github.com/nodejs/node-core-utils/issues/606)) ([19ddfb6](https://github.com/nodejs/node-core-utils/commit/19ddfb64bf53b0cceab9a4a039fe74af79cdee9d))
* **config:** add file path to error message when parsing fails ([#608](https://github.com/nodejs/node-core-utils/issues/608)) ([7c73862](https://github.com/nodejs/node-core-utils/commit/7c73862b1f2817983d986ae2aaa1c35f57210aa3))
* use res.arrayBuffer() instead of res.buffer() ([#624](https://github.com/nodejs/node-core-utils/issues/624)) ([03b4b70](https://github.com/nodejs/node-core-utils/commit/03b4b704065d5d6b9294cf6913f03de0b8072f92))

### [1.31.3](https://github.com/nodejs/node-core-utils/compare/v1.31.2...v1.31.3) (2022-04-19)


### Bug Fixes

* use `getUrlFromOP()` for `fixes` links ([#614](https://github.com/nodejs/node-core-utils/issues/614)) ([4b0e94b](https://github.com/nodejs/node-core-utils/commit/4b0e94b08a81e98aa04d7912e582f66dc5726b1e))

### [1.31.2](https://github.com/nodejs/node-core-utils/compare/v1.31.1...v1.31.2) (2022-04-08)


### Bug Fixes

* correct username and token validation ([64a977c](https://github.com/nodejs/node-core-utils/commit/64a977c1739be74a0e4b78f2004b43f9ddcb6615))
* update permitted GitHub token characters ([dc3d3ef](https://github.com/nodejs/node-core-utils/commit/dc3d3efb320a838380aef2eb231644036aa015ec))

### [1.31.1](https://www.github.com/nodejs/node-core-utils/compare/v1.31.0...v1.31.1) (2022-03-17)


### Bug Fixes

* comply with markdown style guidelines ([13d7b2d](https://www.github.com/nodejs/node-core-utils/commit/13d7b2dbb174a73f3f32010ab4b7396143bd986e))

## [1.31.0](https://www.github.com/nodejs/node-core-utils/compare/v1.30.1...v1.31.0) (2021-12-21)


### Features

* check fast-track approvals ([#588](https://www.github.com/nodejs/node-core-utils/issues/588)) ([d0215d6](https://www.github.com/nodejs/node-core-utils/commit/d0215d6bdcaa7ec087992dbc29ebcae15e81dff5))


### Bug Fixes

* allow pending dependabot checks in PR checker ([829c68d](https://www.github.com/nodejs/node-core-utils/commit/829c68dbfed0b56a0f56534aa1ca6de5a6289b30))
* fetch first 100 check suites in PR checker ([e98d72e](https://www.github.com/nodejs/node-core-utils/commit/e98d72ef49d32d8b8a0605cce222cb8aaab8c128))

### [1.30.1](https://www.github.com/nodejs/node-core-utils/compare/v1.30.0...v1.30.1) (2021-11-17)


### Bug Fixes

* **deps:** revert to node-fetch ([#595](https://www.github.com/nodejs/node-core-utils/issues/595)) ([e475060](https://www.github.com/nodejs/node-core-utils/commit/e4750602c59ae40c06835a86da92782ff2693ecf))
* fixupAll flag should take precedence over autorebase ([#593](https://www.github.com/nodejs/node-core-utils/issues/593)) ([b62fe29](https://www.github.com/nodejs/node-core-utils/commit/b62fe296a0de54eb55d80992cb2e437448b06732))

## [1.30.0](https://www.github.com/nodejs/node-core-utils/compare/v1.29.1...v1.30.0) (2021-11-08)


### Features

* **land:** avoid landing on the wrong default branch ([#586](https://www.github.com/nodejs/node-core-utils/issues/586)) ([48d4641](https://www.github.com/nodejs/node-core-utils/commit/48d4641ffa9034e37f8d7b7890c6c7c95e14f15d))
* spawn the user's editor to edit commit messages ([811de87](https://www.github.com/nodejs/node-core-utils/commit/811de87206806246a98033c60c5db2557d56da12))
* suggest `gh pr` commands to finish landing ([#583](https://www.github.com/nodejs/node-core-utils/issues/583)) ([25b452d](https://www.github.com/nodejs/node-core-utils/commit/25b452d61c49cf723be5ea2ae3b927b3878ad902))


### Bug Fixes

* add missing new line in changelog ([#591](https://www.github.com/nodejs/node-core-utils/issues/591)) ([e7a95a4](https://www.github.com/nodejs/node-core-utils/commit/e7a95a4ec4b166b9311c673f1d4617da4a13d2bc))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://www.github.com/nodejs/node-core-utils/issues/581)) ([f28ec2d](https://www.github.com/nodejs/node-core-utils/commit/f28ec2d50ce68965a87ed61182660763bd642543))
* update detection of changelog links ([#587](https://www.github.com/nodejs/node-core-utils/issues/587)) ([4cd1beb](https://www.github.com/nodejs/node-core-utils/commit/4cd1beb07a0a9d44ca1d8dd9708a29929d566956))
* use COMMIT_EDITMSG file name to edit commits ([2a23e37](https://www.github.com/nodejs/node-core-utils/commit/2a23e3734dd3ac2326fee43ac0221924c36d9bf9))

### [1.29.1](https://www.github.com/nodejs/node-core-utils/compare/v1.29.0...v1.29.1) (2021-10-31)


### Bug Fixes

* prepare for one last README change ([#578](https://www.github.com/nodejs/node-core-utils/issues/578)) ([ef1edc7](https://www.github.com/nodejs/node-core-utils/commit/ef1edc78504ad3b26bb1889685f206a9ce575768))

## [1.29.0](https://www.github.com/nodejs/node-core-utils/compare/v1.28.2...v1.29.0) (2021-10-28)


### Features

* **cli:** prompt user when landing PR with several commits ([#572](https://www.github.com/nodejs/node-core-utils/issues/572)) ([89925c3](https://www.github.com/nodejs/node-core-utils/commit/89925c306728ba8147413b0ad622e55a6dd5475e))


### Bug Fixes

* update detection of changelog links ([#573](https://www.github.com/nodejs/node-core-utils/issues/573)) ([44c6fc8](https://www.github.com/nodejs/node-core-utils/commit/44c6fc878178af17def7b0e047fc5b155796f927))
* update detection of changelog links (take 2) ([#575](https://www.github.com/nodejs/node-core-utils/issues/575)) ([e66ba17](https://www.github.com/nodejs/node-core-utils/commit/e66ba171e81d77abcf38adc9f3bca966523e7b19))
* update for recent changelog format change ([#576](https://www.github.com/nodejs/node-core-utils/issues/576)) ([8f1fa9c](https://www.github.com/nodejs/node-core-utils/commit/8f1fa9c47f93c40ce7b80a375940bffcd6eabdf2))
* update proxy-agent to 5.0.0 ([#570](https://www.github.com/nodejs/node-core-utils/issues/570)) ([3091f99](https://www.github.com/nodejs/node-core-utils/commit/3091f99cca1683f29cf5cd4358738338fe013aba))

### [1.28.2](https://www.github.com/nodejs/node-core-utils/compare/v1.28.1...v1.28.2) (2021-10-04)


### Bug Fixes

* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://www.github.com/nodejs/node-core-utils/issues/567)) ([8ccf184](https://www.github.com/nodejs/node-core-utils/commit/8ccf184773f660cc1765f26af3103870729cb8b2))

### [1.28.1](https://www.github.com/nodejs/node-core-utils/compare/v1.28.0...v1.28.1) (2021-09-25)


### Bug Fixes

* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://www.github.com/nodejs/node-core-utils/issues/565)) ([96d46ab](https://www.github.com/nodejs/node-core-utils/commit/96d46ab0322aeea9fbf6dcd7121e8a87505e568c))

## [1.28.0](https://www.github.com/nodejs/node-core-utils/compare/v1.27.2...v1.28.0) (2021-09-20)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 10 and 15.

### Features

* prepare ncu for new README format ([#561](https://www.github.com/nodejs/node-core-utils/issues/561)) ([6898338](https://www.github.com/nodejs/node-core-utils/commit/6898338653c6edea657fd7e9a36fb3890fead0e1))


### Bug Fixes

* **cli-separator:** negative value on a long text ([#553](https://www.github.com/nodejs/node-core-utils/issues/553)) ([3e8b07d](https://www.github.com/nodejs/node-core-utils/commit/3e8b07decef270b127b7e2584051b950c686114d))
* **v8:** use V8's main branch ([#555](https://www.github.com/nodejs/node-core-utils/issues/555)) ([241055b](https://www.github.com/nodejs/node-core-utils/commit/241055b22c89b0b89efa9aebb06ea41039eece9d))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([dafcdd6](https://www.github.com/nodejs/node-core-utils/commit/dafcdd69fad7e80ca3dea4c6387afe9d504c02c4))
* release 1.28.0 ([0044734](https://www.github.com/nodejs/node-core-utils/commit/00447343615a111a18864e9c7192463b0a38f653))

### [1.27.2](https://www.github.com/nodejs/node-core-utils/compare/v1.27.1...v1.27.2) (2021-07-03)


### Bug Fixes

* **update-v8:** force-add all files after cloning V8 ([#549](https://www.github.com/nodejs/node-core-utils/issues/549)) ([f23ff61](https://www.github.com/nodejs/node-core-utils/commit/f23ff6166bdd774090269352ca9da56132c3d574))

### [1.27.1](https://www.github.com/nodejs/node-core-utils/compare/v1.27.0...v1.27.1) (2021-06-10)


### Bug Fixes

* **pr-checker:** shouldn't fail on SKIPPED ([a578cd7](https://www.github.com/nodejs/node-core-utils/commit/a578cd739b785cdb6ac6c4358dda73d22a7ac690))

## [1.27.0](https://www.github.com/nodejs/node-core-utils/compare/v1.26.0...v1.27.0) (2021-02-26)


### Features

* update CI requirements for landing pull requests ([#533](https://www.github.com/nodejs/node-core-utils/issues/533)) ([ad3c76b](https://www.github.com/nodejs/node-core-utils/commit/ad3c76b3af9e934ff3c3c6b7e44419f518a7bc84))


### Bug Fixes

* **wpt:** download files as buffer instead of text ([#535](https://www.github.com/nodejs/node-core-utils/issues/535)) ([d6fad2a](https://www.github.com/nodejs/node-core-utils/commit/d6fad2a20955a3b7a7eb1626289146609298dabb))
* **wpt:** order version keys alphabetically ([#536](https://www.github.com/nodejs/node-core-utils/issues/536)) ([308982b](https://www.github.com/nodejs/node-core-utils/commit/308982b9cd69c781e4fbd3eb8ed5e68b137a28ca))

## [1.26.0](https://www.github.com/nodejs/node-core-utils/compare/v1.25.0...v1.26.0) (2021-02-08)


### Features

* automate creation of the first LTS release ([#514](https://www.github.com/nodejs/node-core-utils/issues/514)) ([53e68b4](https://www.github.com/nodejs/node-core-utils/commit/53e68b4737c59fae88c740330770f8245bde774b))
* make --checkCI optionable for git-node-land ([#528](https://www.github.com/nodejs/node-core-utils/issues/528)) ([b0be3dd](https://www.github.com/nodejs/node-core-utils/commit/b0be3dd365005236c596396026d8dce9378306a6))


### Bug Fixes

* accommodate case changes in README header ([e8ef932](https://www.github.com/nodejs/node-core-utils/commit/e8ef9329bf3fa23a64915da6d2b3741df5ce6a70))
* fetch most recent 100 commits ([#520](https://www.github.com/nodejs/node-core-utils/issues/520)) ([3c862d1](https://www.github.com/nodejs/node-core-utils/commit/3c862d1d298917287339b0d2d558b522bb2255cf))
* throw on missing info during release prep ([#519](https://www.github.com/nodejs/node-core-utils/issues/519)) ([223d075](https://www.github.com/nodejs/node-core-utils/commit/223d075fc91f421c7f1201b691e9197767b8d465))
* **v8:** correct order of ternary ([#513](https://www.github.com/nodejs/node-core-utils/issues/513)) ([6dab341](https://www.github.com/nodejs/node-core-utils/commit/6dab341314966dea25d277e2bd79ef8d58b4a71b))
* undefined failures & JSON error ([2c0cf83](https://www.github.com/nodejs/node-core-utils/commit/2c0cf834232867e0d0a40cf988ad111dafe17e25))

## [1.25.0](https://www.github.com/nodejs/node-core-utils/compare/v1.24.0...v1.25.0) (2020-09-29)


### Features

* allow to fixup everything into first commit with fixupAll ([4ad4a58](https://www.github.com/nodejs/node-core-utils/commit/4ad4a58a9471d3fd4e27e3b19bae979d91916cef))
* support NCU_VERBOSITY=debug environment variable ([4f84166](https://www.github.com/nodejs/node-core-utils/commit/4f841663818ace8721af1c18212f1f5928e5ce46))


### Bug Fixes

* git node metadata arg passing ([#500](https://www.github.com/nodejs/node-core-utils/issues/500)) ([55c780e](https://www.github.com/nodejs/node-core-utils/commit/55c780e52f03ecf38fc74177f8ee0d1e950ffd8d))
* handle citgm failures better ([#497](https://www.github.com/nodejs/node-core-utils/issues/497)) ([a429893](https://www.github.com/nodejs/node-core-utils/commit/a4298938f84382588db3101dcf611d89f6f0f1e9))

## [1.24.0](https://www.github.com/nodejs/node-core-utils/compare/v1.23.0...v1.24.0) (2020-08-21)


### Features

* check Actions and handle doc-only changes ([855f1d4](https://www.github.com/nodejs/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* implement autorebase for PRs with multiple commits ([17ea885](https://www.github.com/nodejs/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* make lint check opt-in ([b567c1e](https://www.github.com/nodejs/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* **git-node:** add git-node status ([ebc8fb2](https://www.github.com/nodejs/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))


### Bug Fixes

* allow opt-out of Fixes/Refs metadata ([#474](https://www.github.com/nodejs/node-core-utils/issues/474)) ([df5c572](https://www.github.com/nodejs/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* lint during the landing process ([#435](https://www.github.com/nodejs/node-core-utils/issues/435)) ([de6d1e2](https://www.github.com/nodejs/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* prevent duplicate and self-refs ([#478](https://www.github.com/nodejs/node-core-utils/issues/478)) ([95300fd](https://www.github.com/nodejs/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* properly handle failure to start CI ([48c306b](https://www.github.com/nodejs/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* return value for validateLint ([#482](https://www.github.com/nodejs/node-core-utils/issues/482)) ([e379e9f](https://www.github.com/nodejs/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://www.github.com/nodejs/node-core-utils/issues/471)) ([746e5e5](https://www.github.com/nodejs/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* repo/path mismatch in v8 update ([#465](https://www.github.com/nodejs/node-core-utils/issues/465)) ([57b7df8](https://www.github.com/nodejs/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
