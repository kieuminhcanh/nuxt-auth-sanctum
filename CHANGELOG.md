# Changelog


## v0.1.0


### 🚀 Enhancements

- **origin:** Set to optional ([dfe0805](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/dfe0805))
- **origin:** Fix indent ([a50d2c7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a50d2c7))
- Upgraded nuxt dependencies ([2c82ae6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2c82ae6))
- Handle cookies in read-only mode ([632abab](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/632abab))
- Add Origin header to the request ([6387379](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6387379))
- Added separate error page ([79ce7b2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/79ce7b2))
- Implemented global middleware ([6322fd3](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6322fd3))
- Added logger support ([9a62a8f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9a62a8f))
- Added logs into plugin ([79e2558](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/79e2558))
- Added publish workflow ([3c8baef](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3c8baef))
- ⚠️  Added guest mode for global middleware ([50f2a10](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/50f2a10))
- Added support for custom interceptors ([2795998](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2795998))
- ⚠️  Dropped support for excludeFromSanctum page meta ([5d09e71](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5d09e71))
- Added token storage support ([2ebcfbf](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2ebcfbf))
- Configure redirect if unauthenticated ([9574818](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9574818))

### 🩹 Fixes

- KeepRequestedRoute ([5b75851](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5b75851))
- Remove redundant config from playground ([8288cc0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8288cc0))
- Revert nuxt 3.10 to 3.9 because of bugs ([1eb3f0a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1eb3f0a))
- Dumped compatibility version to 3.9 ([1268ffc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1268ffc))
- Added required config to fixture env ([09b621d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/09b621d))
- Updated nuxt dependencies and fixed test behavior ([e06cb36](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/e06cb36))
- Opt in to `import.meta.*` properties ([99e98c9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/99e98c9))
- Prevent redirects to the same page ([01daa22](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/01daa22))
- Prevent redirect on 401 response from login page ([380d4a6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/380d4a6))
- Removed mistaken command from contributing rules ([f4fbf82](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f4fbf82))
- Adjusted tsc directories to check ([de23cbb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/de23cbb))
- Remove git push with tags ([03b28d4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/03b28d4))
- Prevent infinite redirect for guests ([20e7cc9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/20e7cc9))
- Removed redundant empty line ([6426309](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6426309))
- Reset user only when it expires ([d314b86](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d314b86))
- Request identity once on plugin init ([c88fbdf](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/c88fbdf))
- Push main branch after bumping release version ([cc76b0e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cc76b0e))
- Resolved constant visibility issue ([5cbd7a3](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5cbd7a3))
- Include history and write permissions in release pipeline ([220e16b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/220e16b))
- Added npm credentials config ([51d76ef](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/51d76ef))
- Added id-token permission for pipeline ([72b08ea](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/72b08ea))
- Keep config type exported in composable ([3862bfb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3862bfb))
- Added github token for automatic release creation ([84fac56](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/84fac56))
- Request csrf only when not set ([569dbdc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/569dbdc))
- Added csrf cookie for secure ssr calls ([8b45e06](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8b45e06))
- Fixed cookie parses dependency ([bd6ef34](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/bd6ef34))
- Dropped extenal cookie parser to use h3 ([1410179](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1410179))
- Disabled typecheck in the playground ([cd77036](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cd77036))
- Export module types ([b1a513b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b1a513b))
- Use common request header ([2536f21](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2536f21))
- Updated exporting nuxt schemas ([fa608f6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/fa608f6))
- Expose type via templates ([d1ed3a4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d1ed3a4))
- Export public runtime config as part of module ([43fd15c](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/43fd15c))
- Removed workspace from dependencies ([a648ae9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a648ae9))
- Expose page meta augmented type ([b49fdfb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b49fdfb))
- Adjusted path for page meta type ([c0ddc35](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/c0ddc35))
- Hardcode absolute path to node_modules for page meta ([eb0d555](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/eb0d555))
- Changed path with typo ([1c9c963](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1c9c963))
- Experimental support for cloudflare workers ([9146cba](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9146cba))
- Use updated csrf token on first login ([14f5c63](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/14f5c63))
- Use resolved path for augmented types when using pnpm ([050c006](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/050c006))
- Fallback to #app augmented type for page meta ([cbf8a6c](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cbf8a6c))
- Trim trailing slash on redirects ([d24014d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d24014d))
- Do not trim single slash in the url ([81c87d0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/81c87d0))

### 📖 Documentation

- Added separate gitbook as module docs ([f7c4edc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f7c4edc))
- Added toc to readme ([497386b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/497386b))
- Use new `nuxi module add` command in installation ([d74c007](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d74c007))
- Update second step ([93e365d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/93e365d))

### 🏡 Chore

- **release:** V1.0.1 ([79ffcc1](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/79ffcc1))
- **release:** V0.0.1 ([2ca1216](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2ca1216))
- **release:** V0.0.2 ([a89ed12](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a89ed12))
- **release:** V0.0.3 ([e0c33a2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/e0c33a2))
- **release:** V0.0.4 ([6a25e07](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6a25e07))
- **release:** V0.0.5 ([d52546e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d52546e))
- **release:** V0.0.6 ([6c7e3fa](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6c7e3fa))
- **release:** V0.0.7 ([4c23c6f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/4c23c6f))
- **release:** V0.0.8 ([56a8145](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/56a8145))
- **release:** V0.0.9 ([27c3cd0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/27c3cd0))
- **release:** V0.0.10 ([36dcdf6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/36dcdf6))
- **release:** V0.0.11 ([99c0a85](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/99c0a85))
- **release:** V0.0.12 ([8230041](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8230041))
- **release:** V0.0.13 ([abcbd9e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/abcbd9e))
- Test bundler module resolution ([4dc2cde](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/4dc2cde))
- **release:** V0.0.14 ([5149966](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5149966))
- **release:** V0.0.16 ([33431ac](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/33431ac))
- **release:** V0.0.17 ([3e6fc83](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3e6fc83))
- **release:** V0.1.0 ([9199a71](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9199a71))
- **release:** V0.1.1 ([1cfaee8](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1cfaee8))
- **release:** V0.1.2 ([f23e51a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f23e51a))
- Code style improvements ([32b0a64](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/32b0a64))
- Simplified middleware checks ([1c186b9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1c186b9))
- **release:** V0.2.0 ([09048f1](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/09048f1))
- **release:** V0.2.1 ([cf80175](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cf80175))
- **release:** V0.2.2 ([f7813b2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f7813b2))
- **release:** V0.2.3 ([0397aa5](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/0397aa5))
- Dropped support of old versions ([8366255](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8366255))
- **release:** V0.3.0 ([c877a12](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/c877a12))
- Upgraded setup-node to v4 ([3f6226d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3f6226d))
- Removed temp pipeline for publishing ([3bd6027](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3bd6027))
- **release:** V0.3.1 ([63a638a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/63a638a))
- Added debug log for user initial request ([409b3ae](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/409b3ae))
- **release:** V0.3.2 ([6c11a85](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6c11a85))
- Upgraded yarn to 4.2.2 ([007a7e4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/007a7e4))
- **release:** V0.3.3 ([5f0a5f6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5f0a5f6))
- **release:** V0.3.4 ([47f7b2e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/47f7b2e))
- Upgraded module build dependencies ([16cdde6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/16cdde6))
- Extracted default module options ([e0f2c7a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/e0f2c7a))
- Applied formatting to system files ([ae7918f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/ae7918f))
- **release:** V0.3.5 ([41134ce](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/41134ce))
- **release:** V0.3.6 ([ba50302](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/ba50302))
- **release:** V0.3.7 ([ebd22f7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/ebd22f7))
- **release:** V0.3.8 ([8fa0db2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8fa0db2))
- Added typing for interceptors ([8446f6a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8446f6a))
- Added transpile build option ([40fe0b2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/40fe0b2))
- **release:** V0.3.9 ([806db7e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/806db7e))
- **release:** V0.3.10 ([329671d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/329671d))
- **release:** V0.3.11 ([763ea69](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/763ea69))
- **release:** V0.3.12 ([0ad2e08](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/0ad2e08))
- **release:** V0.3.13 ([b84511e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b84511e))
- **release:** V0.3.14 ([1ad62df](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1ad62df))
- Updated playgorund config to breeze-api ([5644023](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5644023))
- Indicate compatibility with new v4 major ([54869f7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/54869f7))
- **release:** V0.4.0 ([89ad786](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/89ad786))
- Updated github templates ([932fd0f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/932fd0f))
- **release:** V0.4.1 ([34da1e4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/34da1e4))
- **release:** V0.4.2 ([675cbb0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/675cbb0))
- Upgraded nuxt version ([0cd2d51](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/0cd2d51))
- **release:** V0.4.3 ([112650c](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/112650c))
- **release:** V0.4.4 ([971f9bd](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/971f9bd))
- **release:** V0.4.5 ([b814c3a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b814c3a))
- **release:** V0.4.6 ([a8f64e7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a8f64e7))

#### ⚠️ Breaking Changes

- ⚠️  Added guest mode for global middleware ([50f2a10](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/50f2a10))
- ⚠️  Dropped support for excludeFromSanctum page meta ([5d09e71](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5d09e71))

### ❤️ Contributors

- Changelog_action ([@manchenkoff](http://github.com/manchenkoff))
- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))
- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Ugo Mignon <ugomignon@gmail.com>
- Putra Fajar H <putrafajarh@gmail.com>

## v0.4.6

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.5...v0.4.6)

### 🩹 Fixes

- Do not trim single slash in the url ([81c87d0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/81c87d0))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.5

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.4...v0.4.5)

### 🩹 Fixes

- Trim trailing slash on redirects ([d24014d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d24014d))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.4

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.3...v0.4.4)

### 🩹 Fixes

- Fallback to #app augmented type for page meta ([cbf8a6c](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cbf8a6c))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.3

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.2...v0.4.3)

### 🩹 Fixes

- Use resolved path for augmented types when using pnpm ([050c006](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/050c006))

### 🏡 Chore

- Upgraded nuxt version ([0cd2d51](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/0cd2d51))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.2

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.1...v0.4.2)

### 🚀 Enhancements

- Configure redirect if unauthenticated ([9574818](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9574818))

### 🩹 Fixes

- Use updated csrf token on first login ([14f5c63](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/14f5c63))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.1

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.4.0...v0.4.1)

### 🩹 Fixes

- Experimental support for cloudflare workers ([9146cba](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9146cba))

### 🏡 Chore

- Updated github templates ([932fd0f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/932fd0f))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.4.0

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.14...v0.4.0)

### 🚀 Enhancements

- ⚠️  Dropped support for excludeFromSanctum page meta ([5d09e71](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5d09e71))
- Added token storage support ([2ebcfbf](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2ebcfbf))

### 🏡 Chore

- Updated playgorund config to breeze-api ([5644023](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5644023))
- Indicate compatibility with new v4 major ([54869f7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/54869f7))

#### ⚠️ Breaking Changes

- ⚠️  Dropped support for excludeFromSanctum page meta ([5d09e71](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5d09e71))

### ❤️ Contributors

- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.14

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.13...v0.3.14)

### 🩹 Fixes

- Changed path with typo ([1c9c963](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1c9c963))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.13

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.12...v0.3.13)

### 🩹 Fixes

- Hardcode absolute path to node_modules for page meta ([eb0d555](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/eb0d555))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.12

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.11...v0.3.12)

### 🩹 Fixes

- Adjusted path for page meta type ([c0ddc35](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/c0ddc35))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.11

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.10...v0.3.11)

### 🩹 Fixes

- Expose page meta augmented type ([b49fdfb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b49fdfb))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.10

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.9...v0.3.10)

### 🩹 Fixes

- Removed workspace from dependencies ([a648ae9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a648ae9))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.9

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.8...v0.3.9)

### 🩹 Fixes

- Expose type via templates ([d1ed3a4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d1ed3a4))
- Export public runtime config as part of module ([43fd15c](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/43fd15c))

### 🏡 Chore

- Added typing for interceptors ([8446f6a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8446f6a))
- Added transpile build option ([40fe0b2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/40fe0b2))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.8

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.7...v0.3.8)

### 🩹 Fixes

- Updated exporting nuxt schemas ([fa608f6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/fa608f6))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.7

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.6...v0.3.7)

### 🩹 Fixes

- Use common request header ([2536f21](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2536f21))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.6

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.5...v0.3.6)

### 🩹 Fixes

- Export module types ([b1a513b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/b1a513b))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.5

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.4...v0.3.5)

### 🚀 Enhancements

- Added support for custom interceptors ([2795998](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2795998))

### 🩹 Fixes

- Disabled typecheck in the playground ([cd77036](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cd77036))

### 🏡 Chore

- Upgraded module build dependencies ([16cdde6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/16cdde6))
- Extracted default module options ([e0f2c7a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/e0f2c7a))
- Applied formatting to system files ([ae7918f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/ae7918f))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.4

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.3...v0.3.4)

### 🩹 Fixes

- Dropped extenal cookie parser to use h3 ([1410179](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1410179))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.3

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.2...v0.3.3)

### 🩹 Fixes

- Fixed cookie parses dependency ([bd6ef34](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/bd6ef34))

### 🏡 Chore

- Upgraded yarn to 4.2.2 ([007a7e4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/007a7e4))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.2

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.1...v0.3.2)

### 🩹 Fixes

- Added github token for automatic release creation ([84fac56](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/84fac56))
- Request csrf only when not set ([569dbdc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/569dbdc))
- Added csrf cookie for secure ssr calls ([8b45e06](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8b45e06))

### 🏡 Chore

- Added debug log for user initial request ([409b3ae](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/409b3ae))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.1

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.3.0...v0.3.1)

### 🩹 Fixes

- Added npm credentials config ([51d76ef](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/51d76ef))
- Added id-token permission for pipeline ([72b08ea](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/72b08ea))
- Keep config type exported in composable ([3862bfb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3862bfb))

### 🏡 Chore

- Upgraded setup-node to v4 ([3f6226d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3f6226d))
- Removed temp pipeline for publishing ([3bd6027](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3bd6027))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.3.0

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.2.3...v0.3.0)

### 🚀 Enhancements

- Added publish workflow ([3c8baef](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/3c8baef))
- ⚠️  Added guest mode for global middleware ([50f2a10](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/50f2a10))

### 🩹 Fixes

- Include history and write permissions in release pipeline ([220e16b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/220e16b))

### 🏡 Chore

- **release:** V0.2.3 ([0397aa5](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/0397aa5))
- Dropped support of old versions ([8366255](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8366255))

#### ⚠️ Breaking Changes

- ⚠️  Added guest mode for global middleware ([50f2a10](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/50f2a10))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.2.3

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.2.2...v0.2.3)

### 🩹 Fixes

- Resolved constant visibility issue ([5cbd7a3](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/5cbd7a3))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.2.2

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.2.0...v0.2.2)

### 🚀 Enhancements

- Added logger support ([9a62a8f](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/9a62a8f))
- Added logs into plugin ([79e2558](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/79e2558))

### 🩹 Fixes

- Remove git push with tags ([03b28d4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/03b28d4))
- Prevent infinite redirect for guests ([20e7cc9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/20e7cc9))
- Removed redundant empty line ([6426309](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6426309))
- Reset user only when it expires ([d314b86](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d314b86))
- Request identity once on plugin init ([c88fbdf](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/c88fbdf))
- Push main branch after bumping release version ([cc76b0e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cc76b0e))

### 📖 Documentation

- Use new `nuxi module add` command in installation ([d74c007](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d74c007))
- Update second step ([93e365d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/93e365d))

### 🏡 Chore

- **release:** V0.2.1 ([cf80175](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/cf80175))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.2.1

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.2.0...v0.2.1)

### 🩹 Fixes

- Remove git push with tags ([03b28d4](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/03b28d4))
- Prevent infinite redirect for guests ([20e7cc9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/20e7cc9))

### 📖 Documentation

- Use new `nuxi module add` command in installation ([d74c007](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d74c007))
- Update second step ([93e365d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/93e365d))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.2.0

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.1.2...v0.2.0)

### 🚀 Enhancements

- Add Origin header to the request ([6387379](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6387379))
- Added separate error page ([79ce7b2](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/79ce7b2))
- Implemented global middleware ([6322fd3](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/6322fd3))

### 🩹 Fixes

- Opt in to `import.meta.*` properties ([99e98c9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/99e98c9))
- Prevent redirects to the same page ([01daa22](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/01daa22))
- Prevent redirect on 401 response from login page ([380d4a6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/380d4a6))
- Removed mistaken command from contributing rules ([f4fbf82](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f4fbf82))
- Adjusted tsc directories to check ([de23cbb](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/de23cbb))

### 📖 Documentation

- Added separate gitbook as module docs ([f7c4edc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f7c4edc))
- Added toc to readme ([497386b](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/497386b))

### 🏡 Chore

- **release:** V0.1.2 ([f23e51a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/f23e51a))
- Code style improvements ([32b0a64](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/32b0a64))
- Simplified middleware checks ([1c186b9](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1c186b9))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))
- Daniel Roe ([@danielroe](http://github.com/danielroe))

## v0.1.2

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.1.1...v0.1.2)

### 🩹 Fixes

- Added required config to fixture env ([09b621d](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/09b621d))
- Updated nuxt dependencies and fixed test behavior ([e06cb36](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/e06cb36))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.1.1

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.1.0...v0.1.1)

### 🩹 Fixes

- Dumped compatibility version to 3.9 ([1268ffc](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1268ffc))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.1.0

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.17...v0.1.0)

### 🚀 Enhancements

- Upgraded nuxt dependencies ([2c82ae6](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/2c82ae6))
- Handle cookies in read-only mode ([632abab](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/632abab))

### 🩹 Fixes

- Remove redundant config from playground ([8288cc0](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8288cc0))
- Revert nuxt 3.10 to 3.9 because of bugs ([1eb3f0a](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/1eb3f0a))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.0.17

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.16...v0.0.17)

## v0.0.16

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.15...v0.0.16)

### 🚀 Enhancements

- **origin:** Set to optional ([dfe0805](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/dfe0805))
- **origin:** Fix indent ([a50d2c7](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/a50d2c7))

### ❤️ Contributors

- Ugo Mignon <ugomignon@gmail.com>

## v0.0.14

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.13...v0.0.14)

### 🏡 Chore

- Test bundler module resolution ([4dc2cde](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/4dc2cde))

### ❤️ Contributors

- Daniel Roe <daniel@roe.dev>

## v0.0.13

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/list...v0.0.13)

### 🏡 Chore

- **release:** V0.0.12 ([8230041](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/8230041))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.0.12

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/list...v0.0.12)

## v0.0.11

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.10...v0.0.11)

## v0.0.10

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.9...v0.0.10)

## v0.0.9

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.8...v0.0.9)

## v0.0.8

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.7...v0.0.8)

## v0.0.7

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.6...v0.0.7)

## v0.0.6

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.5...v0.0.6)

### 🏡 Chore

- **release:** V0.0.5 ([d52546e](https://github.com/manchenkoff/nuxt-auth-sanctum/commit/d52546e))

### ❤️ Contributors

- Manchenkoff ([@manchenkoff](http://github.com/manchenkoff))

## v0.0.5

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.4...v0.0.5)

## v0.0.4

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.3...v0.0.4)

## v0.0.3

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.2...v0.0.3)

## v0.0.2

[compare changes](https://github.com/manchenkoff/nuxt-auth-sanctum/compare/v0.0.1...v0.0.2)

## v0.0.1

- Initial release
- Added first implementation of the module
- Added readme
- Published NPM package

