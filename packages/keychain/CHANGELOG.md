# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [0.6.0](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.4.0...@blockstack/keychain@0.6.0) (2020-06-24)


### Bug Fixes

* attempted fix for [#439](https://github.com/blockstack/ux/issues/439), [#437](https://github.com/blockstack/ux/issues/437) ([d0b31c2](https://github.com/blockstack/ux/commit/d0b31c2239f684e8abd4059503fe8db8f11b0e46))
* bump keychain version ([de7a816](https://github.com/blockstack/ux/commit/de7a816071facc3fc2c8323961a941d722454e6d))
* keychain package was behind published version ([acbd4b0](https://github.com/blockstack/ux/commit/acbd4b064db61a60f01ce60ab75f9f2f39456eb8))


### Features

* add fn to generate 24-word phrases ([8e6077b](https://github.com/blockstack/ux/commit/8e6077b5f0c54e7f9916615ee72448bfa4b48d1f))





# [0.4.0](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.3.5...@blockstack/keychain@0.4.0) (2020-05-15)


### Bug Fixes

* add trailing slash to apps storage url, [#356](https://github.com/blockstack/ux/issues/356) ([024c903](https://github.com/blockstack/ux/commit/024c903724e17678dea205d95fcae01aa946e29e))


### Features

* publish public key, [#357](https://github.com/blockstack/ux/issues/357) ([7c0a1bb](https://github.com/blockstack/ux/commit/7c0a1bb0a6966b29a34a62301dace01325ecacb8))





## [0.3.5](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.3.3...@blockstack/keychain@0.3.5) (2020-05-06)

**Note:** Version bump only for package @blockstack/keychain





## [0.3.3](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.3.2...@blockstack/keychain@0.3.3) (2020-04-30)


### Bug Fixes

* safer logic when fetching profiles, [#322](https://github.com/blockstack/ux/issues/322) ([e0a67fd](https://github.com/blockstack/ux/commit/e0a67fd745f7556846766b912340438eb41d36f6))





## [0.3.2](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.3.1...@blockstack/keychain@0.3.2) (2020-04-17)


### Bug Fixes

* profile info not set in authResponse ([9e48475](https://github.com/blockstack/ux/commit/9e4847544e89dc1c8abcebeda6d34dc2bf8a4c7f))





## [0.3.1](https://github.com/blockstack/ux/compare/@blockstack/keychain@0.3.0-beta.3...@blockstack/keychain@0.3.1) (2020-03-10)


### Bug Fixes

* remove alpha/beta versions from ui, keychain ([81dee96](https://github.com/blockstack/ux/commit/81dee96113f26fa5609dbe753d503c909b98ec5f))





# 0.3.0-beta.3 (2020-03-10)


### Bug Fixes

* **keychain:** fixes TS error when deriving config key ([08f9b18](https://github.com/blockstack/ux/commit/08f9b1827c8588aeb42a5b90fe1bd4d786509474))
* **wallet:** typo when fetching config ([816e46b](https://github.com/blockstack/ux/commit/816e46b5dc37fa519d4508f647a62f5a85d3177a))


### Features

* recursively create identities by looking up username ([d5b20ea](https://github.com/blockstack/ux/commit/d5b20ea4cdb94aa2a92c6096642e9abad467e966))
* restore identities from walletConfig ([61ae914](https://github.com/blockstack/ux/commit/61ae914247c45b46a7c1ef42805a37d51309fc03))





# `@blockstack/keychain` Changelog

## 0.2.3 - 2020/2/4

- Added `Wallet#walletConfig`, which allows storing private settings and information related to the current wallet. Data is stored in Gaia, and is encrypted with a uniquely derived wallet-level private key.

## 0.2.0 - 2020/1/27

- All included in PR [#15](https://github.com/blockstack/blockstack-keychain/pull/15)
- Fetch and store a profile.json
- Register subdomains
- Fetch existing usernames
- Update profile.json `apps` section with the `publish_data` scope

## 0.1.1 - 2019/12/2

- Export `encrypt` and `decrypt` from `index.ts`

## 0.1.0 - 2019/11/25

- Integrate asynchronous code from `blockstack.js`
- Use `tsdx` for deployment
- MVP keychain-related methods
