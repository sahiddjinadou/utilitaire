*releases*: 28, *current install size*: 1.2 MB 

# Changelog


## [v0.0.29](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.29) - 2024-01-31
<!-- bump-type:patch -->
### New Features

- **goToDefinitions**: add settings to configure template definitions ([#21](https://github.com/zardoy/vetur-extended/issues/21))

## [v0.0.28](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.28) - 2024-01-25
<!-- bump-type:patch -->
### Bug Fixes

- **goToDefinitions**: remove component goto definition in script setup ([#20](https://github.com/zardoy/vetur-extended/issues/20))

## [v0.0.27](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.27) - 2023-07-21
<!-- bump-type:patch -->
### Bug Fixes

- **readme**: add ts extension for native features! [`945d18f`](https://github.com/zardoy/vetur-extended/commit/945d18f9fce0fd560ee1d78282e084740979e716)

## [v0.0.26](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.26) - 2023-05-05
<!-- bump-type:patch -->
### New Features

- support js/ts for pinia store code acton ([#18](https://github.com/zardoy/vetur-extended/issues/18))

## [v0.0.25](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.25) - 2023-03-30
<!-- bump-type:patch -->
### Bug Fixes

- add skipping 'at' rules by default ([#17](https://github.com/zardoy/vetur-extended/issues/17))

## [v0.0.24](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.24) - 2023-03-29
<!-- bump-type:patch -->
### New Features

- **createCssClassCommand**: add create css class command ([#16](https://github.com/zardoy/vetur-extended/issues/16))

## [v0.0.23](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.23) - 2023-02-17
<!-- bump-type:patch -->
### New Features

- introduce pinia store register code action ([#14](https://github.com/zardoy/vetur-extended/issues/14))

## [v0.0.22](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.22) - 2023-02-16
<!-- bump-type:patch -->
### New Features

- add copy component name command ([#15](https://github.com/zardoy/vetur-extended/issues/15))

## [v0.0.21](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.21) - 2022-12-04
<!-- bump-type:patch -->
### New Features

- **componentLinks**: support new import type ([#12](https://github.com/zardoy/vetur-extended/issues/12))

## [v0.0.20](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.20) - 2022-09-13
<!-- bump-type:patch -->
### New Features

- add auto expand tag + command ([#11](https://github.com/zardoy/vetur-extended/issues/11))

## [v0.0.19](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.19) - 2022-08-27
<!-- bump-type:patch -->
### New Features

- `focusVuexMapper` command for components API
You can now quickly focus vuex mapper or create one! [`8aa7bc4`](https://github.com/zardoy/vetur-extended/commit/8aa7bc49e450b9297d0bb59a8df1da330db3d4f0)

## [v0.0.18](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.18) - 2022-07-24
<!-- bump-type:patch -->
### New Features

- add command `Copy Styles with Clases From Template` ([#10](https://github.com/zardoy/vetur-extended/issues/10))
to bootstrap `<styles>` content using for all classes from `<template>` [`efbe63c`](https://github.com/zardoy/vetur-extended/commit/efbe63c95342c1f51580dd784a5baa3d8352b933)

## [v0.0.17](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.17) - 2022-06-21
<!-- bump-type:patch -->
### New Features

- enable web support
should've enabled it a long time ago, hope it'll work
however it sill relies on the Volar outline in the web [`791da7e`](https://github.com/zardoy/vetur-extended/commit/791da7e33c62d74eaf7e6d69437f707c73bf1674)
### Bug Fixes

- **completions**: exit early on dot-property access (it was just too annoying) [`ac13cce`](https://github.com/zardoy/vetur-extended/commit/ac13cce64a7e7dffb3842f2a9f4f52cf6b162ff0)
- **completions**: skip unknown values [`ac13cce`](https://github.com/zardoy/vetur-extended/commit/ac13cce64a7e7dffb3842f2a9f4f52cf6b162ff0)
- **references**: don't match false results that had `-` e.g. `component` and `component-variant` are different [`5486ed7`](https://github.com/zardoy/vetur-extended/commit/5486ed7ab38c9d454e0a3e86b6f9e4dde03b9d96)
- show completions when modifier is used e.g. `@click.prevent` [`b3fbc2a`](https://github.com/zardoy/vetur-extended/commit/b3fbc2abe0ab1542915e4eacdc15705f95f2cb06)

## [v0.0.16](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.16) - 2022-05-26
<!-- bump-type:patch -->
### Bug Fixes

- **findReference**: fix false results dut to part-matching [`55e3f51`](https://github.com/zardoy/vetur-extended/commit/55e3f51e7bca324d9e1837dcdc49fdba65769632)

## [v0.0.15](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.15) - 2022-05-24
<!-- bump-type:patch -->
### New Features

- Add find component references button ([#7](https://github.com/zardoy/vetur-extended/issues/7))
Thanks @ILScc [`f93a0fb`](https://github.com/zardoy/vetur-extended/commit/f93a0fbf43bbea47e8471ae3c78f6b794f59874d)

## [v0.0.14](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.14) - 2022-05-24
<!-- bump-type:patch -->
### New Features

- improve `findComponentReferences`
now seeks for kebab-case variant as well [`1aa4b2a`](https://github.com/zardoy/vetur-extended/commit/1aa4b2a794fb9e1b7331619f51c0ad6de843a039)

## [v0.0.13](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.13) - 2022-05-19
<!-- bump-type:patch -->
### Bug Fixes

- correctly parse outline if using an older TS/Volar(takeover) versions
an editor might steel need to be reopened on initial launch in this case [`e23cb61`](https://github.com/zardoy/vetur-extended/commit/e23cb61ed0c35acac753f219078caa9cefd0a0b1)

## [v0.0.12](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.12) - 2022-05-19
<!-- bump-type:patch -->
### New Features

- add experimental command for debugging webpack aliases [`6ebb8e4`](https://github.com/zardoy/vetur-extended/commit/6ebb8e4b76dec04d19957f0686bc0b626506ecba)

## [v0.0.11](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.11) - 2022-05-19
<!-- bump-type:patch -->
### New Features

- add support for path & __dirname webpack aliases
also ([#5](https://github.com/zardoy/vetur-extended/issues/5))

## [v0.0.10](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.10) - 2022-05-18
<!-- bump-type:patch -->
### New Features

- add definitions (goto) for copmponents in `<template>` ([#4](https://github.com/zardoy/vetur-extended/issues/4))
Co-authored-by: @ILScc
- It brings restriction for using generics in TS script, since it is enabled globally per vue file
- Can't be via disabling `enableLinks` [`0678ff7`](https://github.com/zardoy/vetur-extended/commit/0678ff7024295a6a245a37e1f55e93582c428750)

## [v0.0.9](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.9) - 2022-05-18
<!-- bump-type:patch -->
### New Features

- add links for vue paths in import statements ([#3](https://github.com/zardoy/vetur-extended/issues/3))
Co-authored-by: Vitaly Turovsky <vital2580@icloud.com> [`47d5986`](https://github.com/zardoy/vetur-extended/commit/47d5986e2ea671b8bd8cab3c8c926cfbdf0d6840)

## [v0.0.8](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.8) - 2022-04-08
<!-- bump-type:patch -->
### Bug Fixes

- fix completions (provider failed) in components where not all types of completions were defined [`b87e464`](https://github.com/zardoy/vetur-extended/commit/b87e46472c0ab56e4afd699028137344190f5e78)
- allow number in prop [`b87e464`](https://github.com/zardoy/vetur-extended/commit/b87e46472c0ab56e4afd699028137344190f5e78)

## [v0.0.7](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.7) - 2022-04-07
<!-- bump-type:patch -->
### Bug Fixes

- add readme [`fd4c283`](https://github.com/zardoy/vetur-extended/commit/fd4c283126edc79033c2394ea59ed2e97fa4884a)

## [v0.0.6](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.6) - 2022-03-15
<!-- bump-type:patch -->
### New Features

- volar and other ext support ([#1](https://github.com/zardoy/vetur-extended/issues/1))

## [v0.0.5](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.5) - 2022-03-14
<!-- bump-type:patch -->
### New Features

- generateJsconfigAliases command [`b556574`](https://github.com/zardoy/vetur-extended/commit/b5565740407c34392673b2dcf45692daa89a522a)
### Bug Fixes

- fix interpolation regex with hyphens [`b556574`](https://github.com/zardoy/vetur-extended/commit/b5565740407c34392673b2dcf45692daa89a522a)

## [v0.0.4](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.4) - 2022-03-11
<!-- bump-type:patch -->
### New Features

- show completions everywhere by default in attributes (not only in start) [`fadd464`](https://github.com/zardoy/vetur-extended/commit/fadd4640a270e932c954cb886979b484a74456be)
- made behaviour described above configurable via new setting [`fadd464`](https://github.com/zardoy/vetur-extended/commit/fadd4640a270e932c954cb886979b484a74456be)

## [v0.0.3](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.3) - 2022-03-10
<!-- bump-type:patch -->
### New Features

- goToDefinition provider [`300c888`](https://github.com/zardoy/vetur-extended/commit/300c888faf85885a6066e3340888d4dab2fe39ef)
- hover provider [`300c888`](https://github.com/zardoy/vetur-extended/commit/300c888faf85885a6066e3340888d4dab2fe39ef)
- add command for finding component references [`a15224c`](https://github.com/zardoy/vetur-extended/commit/a15224c59dbcd89af8792b3abb5df7140fdcc1a6)
### Bug Fixes

- fix findReferences basic usage. improve multicomponent search [`a15224c`](https://github.com/zardoy/vetur-extended/commit/a15224c59dbcd89af8792b3abb5df7140fdcc1a6)

## [v0.0.2](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.2) - 2022-03-10
<!-- bump-type:patch -->
### New Features

- move suggestions above volar suggestions [`5ebb946`](https://github.com/zardoy/vetur-extended/commit/5ebb946cf8e4314fc686d0042c47a06bca9ad30f)

## [v0.0.1](https://github.com/zardoy/vetur-extended/releases/tag/v0.0.1) - 2022-03-10
🎉 Initial release