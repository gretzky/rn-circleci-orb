## [1.2.3](https://github.com/gretzky/rn-circleci-orb/compare/v1.2.2...v1.2.3) (2022-01-27)


### Bug Fixes

* **android:** use headless emulator ([3e5eb2d](https://github.com/gretzky/rn-circleci-orb/commit/3e5eb2d5ea7bda75833cd054cd74dab32dcbfd5a))

## [1.2.2](https://github.com/gretzky/rn-circleci-orb/compare/v1.2.1...v1.2.2) (2022-01-27)


### Bug Fixes

* **android:** fix emulator acceleration ([a5900ec](https://github.com/gretzky/rn-circleci-orb/commit/a5900ec207c6261efc3720a048381ef35d07cba0))

## [1.2.1](https://github.com/gretzky/rn-circleci-orb/compare/v1.2.0...v1.2.1) (2022-01-27)


### Bug Fixes

* **haxm:** remove intl-haxm ([29a93ed](https://github.com/gretzky/rn-circleci-orb/commit/29a93edf8ebfc560ddb2889cd14417dd39403d1c))
* **macos:** update use_homebrew param ([656af8e](https://github.com/gretzky/rn-circleci-orb/commit/656af8eb129b899230fb485d71b60a0e2469de05))

# [1.2.0](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.6...v1.2.0) (2022-01-27)


### Features

* **android:** add intel-haxm to macos emulator ([b3ffea5](https://github.com/gretzky/rn-circleci-orb/commit/b3ffea56976636537c6993250e2320143cf0c0b7))

## [1.1.6](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.5...v1.1.6) (2022-01-26)


### Bug Fixes

* **detox:** add params ([3a2243f](https://github.com/gretzky/rn-circleci-orb/commit/3a2243f8ae5b452955bd1796340be62b8d727da3))
* **detox:** add screenshot option ([5a8155e](https://github.com/gretzky/rn-circleci-orb/commit/5a8155e6086f52e0148cc7c9a07f0d88a5b16737))

## [1.1.5](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.4...v1.1.5) (2022-01-26)


### Bug Fixes

* **xcodebuild:** update xcodebuild command ([c20b3cf](https://github.com/gretzky/rn-circleci-orb/commit/c20b3cfc33d95c5d26ce9c656d5ee03644091810))

## [1.1.4](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.3...v1.1.4) (2022-01-26)


### Bug Fixes

* **android:** add use_cache command to android build ([f36d7fa](https://github.com/gretzky/rn-circleci-orb/commit/f36d7faae7f25d69867a1a7939ff4258845d9e3e))
* **android_build:** update android_build command to set caching as a booelan ([7c7a21b](https://github.com/gretzky/rn-circleci-orb/commit/7c7a21babf59a8830c0b27f8221206a3872e48c3))
* **ios:** add background parameter for ios simulator ([6b90388](https://github.com/gretzky/rn-circleci-orb/commit/6b903884a8d2bd6d2c287a4ea38157ad4a2435ed))
* **ios:** update install_pods to make caching optional ([cd8b643](https://github.com/gretzky/rn-circleci-orb/commit/cd8b643b00bd21372c5893f4865618c0a851d0f2))
* **ios:** update ios_build command to make caching optional ([99e7d83](https://github.com/gretzky/rn-circleci-orb/commit/99e7d83a4306cf68d1e01b178f86c8c56b5a6faf))
* **jobs:** update jobs ([8036735](https://github.com/gretzky/rn-circleci-orb/commit/8036735dde2f596ab0c797954859d472173299c3))
* **macos:** update nvm and add optional caching to setup_macos ([2933e38](https://github.com/gretzky/rn-circleci-orb/commit/2933e388815369f35dbd0570053c5359b08df947))
* **yarn:** update yarn install ([52262bb](https://github.com/gretzky/rn-circleci-orb/commit/52262bb73edddad110dcef16ba87208cc0c6705a))
* **yarn:** update yarn_install cache param ([243a7ae](https://github.com/gretzky/rn-circleci-orb/commit/243a7ae93961ef8e3ee9f8060b99888ef1308817))

## [1.1.3](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.2...v1.1.3) (2022-01-26)


### Bug Fixes

* **ios:** add pod_install_directory param to install_pods commands ([eda3922](https://github.com/gretzky/rn-circleci-orb/commit/eda3922810154e80177b710ab016310e176229c3))

## [1.1.2](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.1...v1.1.2) (2022-01-26)


### Bug Fixes

* **ios:** make default device consistent ([c8b0d35](https://github.com/gretzky/rn-circleci-orb/commit/c8b0d354d2c17a83b7a77b8ff4ad973005adf8cf))

## [1.1.1](https://github.com/gretzky/rn-circleci-orb/compare/v1.1.0...v1.1.1) (2022-01-26)


### Bug Fixes

* **ios:** set configure_detox to true for ios_build_and_test ([8d79fb6](https://github.com/gretzky/rn-circleci-orb/commit/8d79fb677828e8a51cd582d72a48a2fa22271c4c))

# [1.1.0](https://github.com/gretzky/rn-circleci-orb/compare/v1.0.3...v1.1.0) (2022-01-25)


### Features

* **macos_executor:** add configure_detox variable for whether or not to setup detox on macos ([8832a12](https://github.com/gretzky/rn-circleci-orb/commit/8832a12c531ca23602f869eda6b6a574d5d263b6))

## [1.0.3](https://github.com/gretzky/rn-circleci-orb/compare/v1.0.2...v1.0.3) (2022-01-25)


### Bug Fixes

* **linux_android:** update java_options to replace UseCGroupMemoryLimitForHeap ([fa6c853](https://github.com/gretzky/rn-circleci-orb/commit/fa6c853aa90ce318e7860b2d2c80bbffc3abd97b))

## [1.0.2](https://github.com/gretzky/rn-circleci-orb/compare/v1.0.1...v1.0.2) (2022-01-25)


### Bug Fixes

* **macos:** remove usr/local/homebrew from cache ([32bd0a9](https://github.com/gretzky/rn-circleci-orb/commit/32bd0a90aaf57070f18b1933d2a9da5abd9b5e25))

## [1.0.1](https://github.com/gretzky/rn-circleci-orb/compare/v1.0.0...v1.0.1) (2022-01-25)


### Bug Fixes

* **detox:** update macos executor command to setup detox appropriately ([eeffd25](https://github.com/gretzky/rn-circleci-orb/commit/eeffd25baa360344d815acb59834f784a3cba2b5))

# 1.0.0 (2022-01-12)


### Features

* **init:** initial commit ([0a12f55](https://github.com/gretzky/rn-circleci-orb/commit/0a12f557388fcde9f80617cec8af27538029a015))
