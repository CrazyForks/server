# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.22.14](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.13...@standardnotes/websockets-server@1.22.14) (2025-04-29)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.13](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.12...@standardnotes/websockets-server@1.22.13) (2024-06-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.12](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.11...@standardnotes/websockets-server@1.22.12) (2024-01-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.11](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.10...@standardnotes/websockets-server@1.22.11) (2024-01-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.9...@standardnotes/websockets-server@1.22.10) (2024-01-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.8...@standardnotes/websockets-server@1.22.9) (2024-01-03)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.7...@standardnotes/websockets-server@1.22.8) (2024-01-03)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.6...@standardnotes/websockets-server@1.22.7) (2023-12-29)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.5...@standardnotes/websockets-server@1.22.6) (2023-12-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.4...@standardnotes/websockets-server@1.22.5) (2023-12-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.3...@standardnotes/websockets-server@1.22.4) (2023-12-26)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.2...@standardnotes/websockets-server@1.22.3) (2023-12-14)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.1...@standardnotes/websockets-server@1.22.2) (2023-12-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.22.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.22.0...@standardnotes/websockets-server@1.22.1) (2023-12-07)

### Bug Fixes

* logger meta information ([a2b1323](https://github.com/standardnotes/server/commit/a2b1323568f5ced74b41aa4634340a6ca0668683))

# [1.22.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.21.4...@standardnotes/websockets-server@1.22.0) (2023-12-07)

### Features

* replace websocket connection validation with grpc ([#954](https://github.com/standardnotes/server/issues/954)) ([d5c1b76](https://github.com/standardnotes/server/commit/d5c1b76de068a64b334c4347cbefa973447a0f60))

## [1.21.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.21.3...@standardnotes/websockets-server@1.21.4) (2023-12-07)

### Bug Fixes

* **websockets:** remove connection trace when it is gone ([#953](https://github.com/standardnotes/server/issues/953)) ([96a2a67](https://github.com/standardnotes/server/commit/96a2a67aa6baa70ddb2d69a9ccbf62df044605e5))

## [1.21.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.21.2...@standardnotes/websockets-server@1.21.3) (2023-12-06)

### Bug Fixes

* **api-gateway:** add grpc logs for internal errors ([529795d](https://github.com/standardnotes/server/commit/529795d393442727833f318234d308543c1ea731))
* **websockets:** change error message on unknown errors ([79ae076](https://github.com/standardnotes/server/commit/79ae07623fa392f1f60160ecdc34a0fcfa4d9a48))

## [1.21.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.21.1...@standardnotes/websockets-server@1.21.2) (2023-12-01)

### Bug Fixes

* upgrade aws deps ([#946](https://github.com/standardnotes/server/issues/946)) ([49cd5be](https://github.com/standardnotes/server/commit/49cd5be3521cf9500509adc2b542703efa052203))

### Reverts

* Revert "chore: upgrade deps" ([341f69e](https://github.com/standardnotes/server/commit/341f69e301036aa48588957fc930405d0344e6ce))

## [1.21.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.21.0...@standardnotes/websockets-server@1.21.1) (2023-11-28)

### Bug Fixes

* pass session uuid to websockets token ([bcd1d83](https://github.com/standardnotes/server/commit/bcd1d830e6125fc5f8cc1312e581284221aaac8f))

# [1.21.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.20.4...@standardnotes/websockets-server@1.21.0) (2023-11-28)

### Features

* send event to client upon items change on server ([#941](https://github.com/standardnotes/server/issues/941)) ([69b404f](https://github.com/standardnotes/server/commit/69b404f5d45f32530ebadbdbbec01d4e335dbbe9))

## [1.20.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.20.3...@standardnotes/websockets-server@1.20.4) (2023-11-27)

### Bug Fixes

* repository config in package.json files ([ed1bf37](https://github.com/standardnotes/server/commit/ed1bf37287af23a25b8388ada95f0acdec8f71ea))

## [1.20.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.20.2...@standardnotes/websockets-server@1.20.3) (2023-11-27)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.20.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.20.1...@standardnotes/websockets-server@1.20.2) (2023-11-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.20.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.20.0...@standardnotes/websockets-server@1.20.1) (2023-11-22)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.20.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.19.2...@standardnotes/websockets-server@1.20.0) (2023-11-16)

### Features

* add grpc sessions validation server ([#928](https://github.com/standardnotes/server/issues/928)) ([4f62cac](https://github.com/standardnotes/server/commit/4f62cac213a6b5f503040ef6319e5198967974ce))

## [1.19.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.19.1...@standardnotes/websockets-server@1.19.2) (2023-11-13)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.19.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.19.0...@standardnotes/websockets-server@1.19.1) (2023-11-13)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.19.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.18.0...@standardnotes/websockets-server@1.19.0) (2023-11-10)

### Features

* add keep-alive connections to subservices ([#924](https://github.com/standardnotes/server/issues/924)) ([daad76d](https://github.com/standardnotes/server/commit/daad76d0ddae34c59dce45eedc4a055c4a11456d))

# [1.18.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.8...@standardnotes/websockets-server@1.18.0) (2023-11-10)

### Features

* add graceful shutdown procedures upon SIGTERM ([#923](https://github.com/standardnotes/server/issues/923)) ([c24353c](https://github.com/standardnotes/server/commit/c24353cc24ebf4b40ff9a2cec8e37cfdef109e37))

## [1.17.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.7...@standardnotes/websockets-server@1.17.8) (2023-11-09)

### Bug Fixes

* remove unused axios dep in subservices ([45d4920](https://github.com/standardnotes/server/commit/45d4920e0fc2848a28ce888d139201e68c4b416f))

## [1.17.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.6...@standardnotes/websockets-server@1.17.7) (2023-11-09)

### Bug Fixes

* reduce websockets api communication data ([#919](https://github.com/standardnotes/server/issues/919)) ([c4ae12d](https://github.com/standardnotes/server/commit/c4ae12d53fc166879f90a4c5dbad1ab1cb4797e2))

## [1.17.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.5...@standardnotes/websockets-server@1.17.6) (2023-11-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.17.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.4...@standardnotes/websockets-server@1.17.5) (2023-11-07)

### Bug Fixes

* remove open telemetry from code ([#903](https://github.com/standardnotes/server/issues/903)) ([751f3b2](https://github.com/standardnotes/server/commit/751f3b25476c5be3d663ad8540c43266acd39493))

## [1.17.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.3...@standardnotes/websockets-server@1.17.4) (2023-10-26)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.17.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.2...@standardnotes/websockets-server@1.17.3) (2023-10-26)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.17.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.1...@standardnotes/websockets-server@1.17.2) (2023-10-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.17.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.17.0...@standardnotes/websockets-server@1.17.1) (2023-10-18)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.17.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.7...@standardnotes/websockets-server@1.17.0) (2023-10-17)

### Features

* add wrapping sqs receive message with open telemetry ([aba4f90](https://github.com/standardnotes/server/commit/aba4f90485e1b40baac34561321a5381945aa27e))

## [1.16.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.6...@standardnotes/websockets-server@1.16.7) (2023-10-13)

### Bug Fixes

* reduce the amount of metrics gathered in telemetery ([32fe8d0](https://github.com/standardnotes/server/commit/32fe8d0a8523d6e1875cd0814c0cbdf27d8df7b3))

## [1.16.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.5...@standardnotes/websockets-server@1.16.6) (2023-10-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.16.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.4...@standardnotes/websockets-server@1.16.5) (2023-10-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.16.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.3...@standardnotes/websockets-server@1.16.4) (2023-10-12)

### Bug Fixes

* disable opentelemetry tracing on async worker jobs ([e0b19ef](https://github.com/standardnotes/server/commit/e0b19ef011197c854cb6e833dbaa982f661e8d17))
* disable sqs open telemetry manual tracing in favour of automated instrumentation ([337eae7](https://github.com/standardnotes/server/commit/337eae73c6cb18ae872527b06f6c23e1c48b6dff))

## [1.16.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.2...@standardnotes/websockets-server@1.16.3) (2023-10-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.16.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.1...@standardnotes/websockets-server@1.16.2) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.16.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.16.0...@standardnotes/websockets-server@1.16.1) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.16.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.15.4...@standardnotes/websockets-server@1.16.0) (2023-10-11)

### Features

* add opentelemetry tracing in distributed system ([72c9b28](https://github.com/standardnotes/server/commit/72c9b28ebe108a2011d1a598fd4682132a533126))

## [1.15.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.15.3...@standardnotes/websockets-server@1.15.4) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.15.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.15.2...@standardnotes/websockets-server@1.15.3) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.15.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.15.1...@standardnotes/websockets-server@1.15.2) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.15.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.15.0...@standardnotes/websockets-server@1.15.1) (2023-10-11)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.15.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.5...@standardnotes/websockets-server@1.15.0) (2023-10-10)

### Features

* remove newrelic integration ([#862](https://github.com/standardnotes/server/issues/862)) ([efb341e](https://github.com/standardnotes/server/commit/efb341eb991d37efab7c1efce035ee07ad0a101e))

## [1.14.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.4...@standardnotes/websockets-server@1.14.5) (2023-10-10)

### Bug Fixes

* opentelemetry instantiation ([08f7c54](https://github.com/standardnotes/server/commit/08f7c5447b020fee71a1e49d382db32082bb9044))

## [1.14.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.3...@standardnotes/websockets-server@1.14.4) (2023-10-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.14.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.2...@standardnotes/websockets-server@1.14.3) (2023-10-09)

### Reverts

* Revert "Revert "fix: setting parent span on workers"" ([76ae6f5](https://github.com/standardnotes/server/commit/76ae6f5a882a82ab5f635452e3bc7b2b16709531))

## [1.14.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.1...@standardnotes/websockets-server@1.14.2) (2023-10-09)

### Reverts

* Revert "fix: setting parent span on workers" ([3fc07a5](https://github.com/standardnotes/server/commit/3fc07a5b60c26b583efd88e8a80d4c4321e71efb))

## [1.14.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.14.0...@standardnotes/websockets-server@1.14.1) (2023-10-09)

### Bug Fixes

* setting parent span on workers ([1c54d18](https://github.com/standardnotes/server/commit/1c54d18c3ca75353701ba921492a5ecfaa2e3572))

# [1.14.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.13.0...@standardnotes/websockets-server@1.14.0) (2023-10-09)

### Features

* add custom tracing on workers ([65ced2c](https://github.com/standardnotes/server/commit/65ced2cc7b0686dc8af5cdad499412fc8fd29d1d))

# [1.13.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.12.1...@standardnotes/websockets-server@1.13.0) (2023-10-09)

### Features

* add opentelemetry to all services ([5e930d0](https://github.com/standardnotes/server/commit/5e930d08eb60a0da800081342315e7edaf130951))

## [1.12.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.12.0...@standardnotes/websockets-server@1.12.1) (2023-10-09)

### Bug Fixes

* remove xray sdk in favor of opentelemetry ([b736dab](https://github.com/standardnotes/server/commit/b736dab3c1f76c9e03c4bc7bbf153dcb3309b7cb))

# [1.12.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.10...@standardnotes/websockets-server@1.12.0) (2023-10-06)

### Features

* add xray to analytics scheduler and websockets ([f0531d6](https://github.com/standardnotes/server/commit/f0531d68cb77036222f2a34602819f11e6a2697d))

## [1.11.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.9...@standardnotes/websockets-server@1.11.10) (2023-10-05)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.8...@standardnotes/websockets-server@1.11.9) (2023-10-05)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.7...@standardnotes/websockets-server@1.11.8) (2023-10-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.6...@standardnotes/websockets-server@1.11.7) (2023-10-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.5...@standardnotes/websockets-server@1.11.6) (2023-10-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.4...@standardnotes/websockets-server@1.11.5) (2023-10-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.3...@standardnotes/websockets-server@1.11.4) (2023-10-03)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.2...@standardnotes/websockets-server@1.11.3) (2023-10-03)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.1...@standardnotes/websockets-server@1.11.2) (2023-09-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.11.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.11.0...@standardnotes/websockets-server@1.11.1) (2023-09-27)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.11.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.53...@standardnotes/websockets-server@1.11.0) (2023-09-26)

### Features

* refactor handling revision creation from dump ([#854](https://github.com/standardnotes/server/issues/854)) ([ca6dbc0](https://github.com/standardnotes/server/commit/ca6dbc00537bb20f508f9310b1a838421f53a643))

## [1.10.53](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.52...@standardnotes/websockets-server@1.10.53) (2023-09-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.52](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.51...@standardnotes/websockets-server@1.10.52) (2023-09-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.51](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.50...@standardnotes/websockets-server@1.10.51) (2023-09-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.50](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.49...@standardnotes/websockets-server@1.10.50) (2023-09-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.49](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.48...@standardnotes/websockets-server@1.10.49) (2023-09-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.48](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.47...@standardnotes/websockets-server@1.10.48) (2023-09-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.47](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.46...@standardnotes/websockets-server@1.10.47) (2023-09-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.46](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.45...@standardnotes/websockets-server@1.10.46) (2023-09-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.45](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.44...@standardnotes/websockets-server@1.10.45) (2023-09-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.44](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.43...@standardnotes/websockets-server@1.10.44) (2023-09-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.43](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.42...@standardnotes/websockets-server@1.10.43) (2023-09-15)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.42](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.41...@standardnotes/websockets-server@1.10.42) (2023-09-15)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.41](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.40...@standardnotes/websockets-server@1.10.41) (2023-09-13)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.40](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.39...@standardnotes/websockets-server@1.10.40) (2023-09-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.39](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.38...@standardnotes/websockets-server@1.10.39) (2023-09-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.38](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.37...@standardnotes/websockets-server@1.10.38) (2023-09-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.37](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.36...@standardnotes/websockets-server@1.10.37) (2023-09-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.36](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.35...@standardnotes/websockets-server@1.10.36) (2023-09-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.35](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.34...@standardnotes/websockets-server@1.10.35) (2023-09-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.34](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.33...@standardnotes/websockets-server@1.10.34) (2023-09-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.33](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.32...@standardnotes/websockets-server@1.10.33) (2023-09-06)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.32](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.31...@standardnotes/websockets-server@1.10.32) (2023-09-05)

### Bug Fixes

* **websockets:** add missing region parameter in api gateway client ([6bb44af](https://github.com/standardnotes/server/commit/6bb44afd91b030facec486c128f80d533996e98b))

## [1.10.31](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.30...@standardnotes/websockets-server@1.10.31) (2023-09-05)

### Bug Fixes

* **websockets:** issue with sending messages to active websocket connections ([#806](https://github.com/standardnotes/server/issues/806)) ([72ab08a](https://github.com/standardnotes/server/commit/72ab08a0d09a18700298544c136ba3d202962d07))

## [1.10.30](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.29...@standardnotes/websockets-server@1.10.30) (2023-09-04)

### Bug Fixes

* **websockets:** stringify response from the AWS Api Gateway ([002074e](https://github.com/standardnotes/server/commit/002074e4d126e103294d0aaea1f22afc3edbfc96))

## [1.10.29](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.28...@standardnotes/websockets-server@1.10.29) (2023-09-04)

### Bug Fixes

* **websockets:** add response debug on websockets sending ([8f96f0e](https://github.com/standardnotes/server/commit/8f96f0ed7a7f7e43f31c6163b9b6801f5896eece))

## [1.10.28](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.27...@standardnotes/websockets-server@1.10.28) (2023-09-04)

### Bug Fixes

* **websockets:** add debug logs ([c7b0c7d](https://github.com/standardnotes/server/commit/c7b0c7dfa87504c52bf76def527abeff15f8d2f5))

## [1.10.27](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.26...@standardnotes/websockets-server@1.10.27) (2023-09-01)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.26](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.25...@standardnotes/websockets-server@1.10.26) (2023-09-01)

### Bug Fixes

* inserting revisions instead of upsert ([#803](https://github.com/standardnotes/server/issues/803)) ([27ff25b](https://github.com/standardnotes/server/commit/27ff25b70e6b65dfe89aa35582422dce682a4105))

## [1.10.25](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.24...@standardnotes/websockets-server@1.10.25) (2023-09-01)

### Bug Fixes

* remove the alive and kicking info logs on workers ([1bef127](https://github.com/standardnotes/server/commit/1bef1279e6dbf3cbdfa87e44aa9108ed6dbb3b0f))

## [1.10.24](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.23...@standardnotes/websockets-server@1.10.24) (2023-08-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.23](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.22...@standardnotes/websockets-server@1.10.23) (2023-08-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.22](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.21...@standardnotes/websockets-server@1.10.22) (2023-08-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.21](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.20...@standardnotes/websockets-server@1.10.21) (2023-08-24)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.20](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.19...@standardnotes/websockets-server@1.10.20) (2023-08-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.19](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.18...@standardnotes/websockets-server@1.10.19) (2023-08-22)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.18](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.17...@standardnotes/websockets-server@1.10.18) (2023-08-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.17](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.16...@standardnotes/websockets-server@1.10.17) (2023-08-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.16](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.15...@standardnotes/websockets-server@1.10.16) (2023-08-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.15](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.14...@standardnotes/websockets-server@1.10.15) (2023-08-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.14](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.13...@standardnotes/websockets-server@1.10.14) (2023-08-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.13](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.12...@standardnotes/websockets-server@1.10.13) (2023-08-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.12](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.11...@standardnotes/websockets-server@1.10.12) (2023-08-03)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.11](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.10...@standardnotes/websockets-server@1.10.11) (2023-08-02)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.9...@standardnotes/websockets-server@1.10.10) (2023-08-02)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.8...@standardnotes/websockets-server@1.10.9) (2023-08-01)

### Bug Fixes

* controller naming ([#678](https://github.com/standardnotes/server/issues/678)) ([56f0aef](https://github.com/standardnotes/server/commit/56f0aef21d3fcec7ac7e968cb1c1b071becbbe26))

## [1.10.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.7...@standardnotes/websockets-server@1.10.8) (2023-07-27)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.6...@standardnotes/websockets-server@1.10.7) (2023-07-26)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.5...@standardnotes/websockets-server@1.10.6) (2023-07-26)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.4...@standardnotes/websockets-server@1.10.5) (2023-07-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.3...@standardnotes/websockets-server@1.10.4) (2023-07-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.2...@standardnotes/websockets-server@1.10.3) (2023-07-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.1...@standardnotes/websockets-server@1.10.2) (2023-07-17)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.10.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.10.0...@standardnotes/websockets-server@1.10.1) (2023-07-12)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.10.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.8...@standardnotes/websockets-server@1.10.0) (2023-07-12)

### Features

* domain items ([#655](https://github.com/standardnotes/server/issues/655)) ([a0af8f0](https://github.com/standardnotes/server/commit/a0af8f00252e1219e58cb7e066c11a8e71692e9d))

## [1.9.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.7...@standardnotes/websockets-server@1.9.8) (2023-07-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.6...@standardnotes/websockets-server@1.9.7) (2023-07-06)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.5...@standardnotes/websockets-server@1.9.6) (2023-07-05)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.4...@standardnotes/websockets-server@1.9.5) (2023-06-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.3...@standardnotes/websockets-server@1.9.4) (2023-06-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.2...@standardnotes/websockets-server@1.9.3) (2023-06-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.1...@standardnotes/websockets-server@1.9.2) (2023-06-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.9.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.9.0...@standardnotes/websockets-server@1.9.1) (2023-06-02)

### Bug Fixes

* **home-server:** streaming logs ([a8b806a](https://github.com/standardnotes/server/commit/a8b806af084b3e3fe8707ff0cb041a74042ee049))

# [1.9.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.6...@standardnotes/websockets-server@1.9.0) (2023-06-02)

### Features

* **home-server:** add overriding environment variables in underlying services ([#621](https://github.com/standardnotes/server/issues/621)) ([f0cbec0](https://github.com/standardnotes/server/commit/f0cbec07b87d60dfad92072944553f76e0bea164))

## [1.8.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.5...@standardnotes/websockets-server@1.8.6) (2023-06-01)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.8.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.4...@standardnotes/websockets-server@1.8.5) (2023-06-01)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.8.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.3...@standardnotes/websockets-server@1.8.4) (2023-05-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.8.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.2...@standardnotes/websockets-server@1.8.3) (2023-05-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.8.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.1...@standardnotes/websockets-server@1.8.2) (2023-05-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.8.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.8.0...@standardnotes/websockets-server@1.8.1) (2023-05-30)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.8.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.5...@standardnotes/websockets-server@1.8.0) (2023-05-30)

### Features

* upgrade to node 20.2.0 ([#616](https://github.com/standardnotes/server/issues/616)) ([a6b062f](https://github.com/standardnotes/server/commit/a6b062f638595537e1ece28bc79bded41d875e18))

## [1.7.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.4...@standardnotes/websockets-server@1.7.5) (2023-05-29)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.7.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.3...@standardnotes/websockets-server@1.7.4) (2023-05-17)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.7.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.2...@standardnotes/websockets-server@1.7.3) (2023-05-16)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.7.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.1...@standardnotes/websockets-server@1.7.2) (2023-05-15)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.7.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.7.0...@standardnotes/websockets-server@1.7.1) (2023-05-09)

### Bug Fixes

* node engine version requirement in package.json files ([62a0e89](https://github.com/standardnotes/server/commit/62a0e89748ab306566c4aa10b9dc0385fb0f1684))

# [1.7.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.16...@standardnotes/websockets-server@1.7.0) (2023-05-08)

### Features

* upgrade to node 20.1.0 ([#590](https://github.com/standardnotes/server/issues/590)) ([8fbb94d](https://github.com/standardnotes/server/commit/8fbb94d15ab664cca775ec71d51db465547c35ee))

## [1.6.16](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.15...@standardnotes/websockets-server@1.6.16) (2023-05-05)

### Bug Fixes

* remove sentry ([c6122d3](https://github.com/standardnotes/server/commit/c6122d33b9ef493758eb2f40837ae0ab90554a67))
* remove unused imports ([990140c](https://github.com/standardnotes/server/commit/990140c3924456ba05d85ef535c953081b217e4b))
* upgrade prettier ([a1e1603](https://github.com/standardnotes/server/commit/a1e16031e0a4113126ab172c426b2ccd48b68791))

## [1.6.15](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.14...@standardnotes/websockets-server@1.6.15) (2023-05-02)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.14](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.13...@standardnotes/websockets-server@1.6.14) (2023-04-27)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.13](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.12...@standardnotes/websockets-server@1.6.13) (2023-04-27)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.12](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.11...@standardnotes/websockets-server@1.6.12) (2023-04-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.11](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.10...@standardnotes/websockets-server@1.6.11) (2023-04-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.9...@standardnotes/websockets-server@1.6.10) (2023-03-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.8...@standardnotes/websockets-server@1.6.9) (2023-03-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.7...@standardnotes/websockets-server@1.6.8) (2023-03-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.6...@standardnotes/websockets-server@1.6.7) (2023-03-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.5...@standardnotes/websockets-server@1.6.6) (2023-03-01)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.4...@standardnotes/websockets-server@1.6.5) (2023-02-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.3...@standardnotes/websockets-server@1.6.4) (2023-02-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.2...@standardnotes/websockets-server@1.6.3) (2023-02-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.1...@standardnotes/websockets-server@1.6.2) (2023-02-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.6.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.6.0...@standardnotes/websockets-server@1.6.1) (2023-02-15)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.6.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.20...@standardnotes/websockets-server@1.6.0) (2023-02-15)

### Features

* optimize memory on server utilities ([881a696](https://github.com/standardnotes/server/commit/881a6967aca57d68795af0792114f848ddddf120))

## [1.5.20](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.19...@standardnotes/websockets-server@1.5.20) (2023-02-06)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.19](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.18...@standardnotes/websockets-server@1.5.19) (2023-01-30)

### Bug Fixes

* sqs configuration for aws sdk v3 ([b54c331](https://github.com/standardnotes/server/commit/b54c331bef0d4ad1ba1111700dc9f1bf64c1ea51))

## [1.5.18](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.17...@standardnotes/websockets-server@1.5.18) (2023-01-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.17](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.16...@standardnotes/websockets-server@1.5.17) (2023-01-24)

### Bug Fixes

* **auth:** add pseudo u2f params on non existing accounts ([e4c65ca](https://github.com/standardnotes/server/commit/e4c65ca631938d8b1d635a40e463d5544051e4a1))

## [1.5.16](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.15...@standardnotes/websockets-server@1.5.16) (2023-01-24)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.15](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.14...@standardnotes/websockets-server@1.5.15) (2023-01-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.14](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.13...@standardnotes/websockets-server@1.5.14) (2023-01-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.13](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.12...@standardnotes/websockets-server@1.5.13) (2023-01-20)

### Bug Fixes

* **websockets:** bundling issue ([27f45f7](https://github.com/standardnotes/server/commit/27f45f7cf67f68989dc737863582912de789878f))

## [1.5.12](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.11...@standardnotes/websockets-server@1.5.12) (2023-01-20)

### Reverts

* Revert "chore: upgrade @standardnotes/* dependencies" ([5bf3ecd](https://github.com/standardnotes/server/commit/5bf3ecdf42e1e5b9cb538cad08a18fb6e4054129))

## [1.5.11](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.10...@standardnotes/websockets-server@1.5.11) (2023-01-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.9...@standardnotes/websockets-server@1.5.10) (2023-01-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.8...@standardnotes/websockets-server@1.5.9) (2023-01-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.7...@standardnotes/websockets-server@1.5.8) (2023-01-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.6...@standardnotes/websockets-server@1.5.7) (2023-01-19)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.5...@standardnotes/websockets-server@1.5.6) (2023-01-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.4...@standardnotes/websockets-server@1.5.5) (2023-01-17)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.3...@standardnotes/websockets-server@1.5.4) (2023-01-13)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.2...@standardnotes/websockets-server@1.5.3) (2022-12-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.1...@standardnotes/websockets-server@1.5.2) (2022-12-20)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.5.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.5.0...@standardnotes/websockets-server@1.5.1) (2022-12-19)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.5.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.53...@standardnotes/websockets-server@1.5.0) (2022-12-19)

### Features

* **auth:** add session traces ([8bcb552](https://github.com/standardnotes/server/commit/8bcb552783b2d12f3296b3195752168482790bc8))

## [1.4.53](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.52...@standardnotes/websockets-server@1.4.53) (2022-12-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.52](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.51...@standardnotes/websockets-server@1.4.52) (2022-12-12)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.51](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.50...@standardnotes/websockets-server@1.4.51) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.50](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.49...@standardnotes/websockets-server@1.4.50) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.49](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.48...@standardnotes/websockets-server@1.4.49) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.48](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.47...@standardnotes/websockets-server@1.4.48) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.47](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.46...@standardnotes/websockets-server@1.4.47) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.46](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.45...@standardnotes/websockets-server@1.4.46) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.45](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.44...@standardnotes/websockets-server@1.4.45) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.44](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.43...@standardnotes/websockets-server@1.4.44) (2022-12-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.43](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.42...@standardnotes/websockets-server@1.4.43) (2022-12-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.42](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.41...@standardnotes/websockets-server@1.4.42) (2022-12-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.41](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.40...@standardnotes/websockets-server@1.4.41) (2022-12-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.40](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.39...@standardnotes/websockets-server@1.4.40) (2022-12-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.39](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.38...@standardnotes/websockets-server@1.4.39) (2022-12-08)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.38](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.37...@standardnotes/websockets-server@1.4.38) (2022-12-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.37](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.36...@standardnotes/websockets-server@1.4.37) (2022-12-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.36](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.35...@standardnotes/websockets-server@1.4.36) (2022-12-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.35](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.34...@standardnotes/websockets-server@1.4.35) (2022-12-06)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.34](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.33...@standardnotes/websockets-server@1.4.34) (2022-12-05)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.33](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.32...@standardnotes/websockets-server@1.4.33) (2022-11-30)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.32](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.31...@standardnotes/websockets-server@1.4.32) (2022-11-28)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.31](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.30...@standardnotes/websockets-server@1.4.31) (2022-11-25)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.30](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.29...@standardnotes/websockets-server@1.4.30) (2022-11-24)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.29](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.28...@standardnotes/websockets-server@1.4.29) (2022-11-23)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.28](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.27...@standardnotes/websockets-server@1.4.28) (2022-11-22)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.27](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.26...@standardnotes/websockets-server@1.4.27) (2022-11-21)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.26](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.25...@standardnotes/websockets-server@1.4.26) (2022-11-18)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.25](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.24...@standardnotes/websockets-server@1.4.25) (2022-11-16)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.24](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.23...@standardnotes/websockets-server@1.4.24) (2022-11-14)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.23](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.20...@standardnotes/websockets-server@1.4.23) (2022-11-14)

### Bug Fixes

* versioning issue ([7ca377f](https://github.com/standardnotes/server/commit/7ca377f1b889379e6a43a66c0134bf266763516d))

## [1.4.20](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.19...@standardnotes/websockets-server@1.4.20) (2022-11-14)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.19](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.18...@standardnotes/websockets-server@1.4.19) (2022-11-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.18](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.17...@standardnotes/websockets-server@1.4.18) (2022-11-11)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.17](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.16...@standardnotes/websockets-server@1.4.17) (2022-11-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.16](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.15...@standardnotes/websockets-server@1.4.16) (2022-11-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.15](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.14...@standardnotes/websockets-server@1.4.15) (2022-11-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.14](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.13...@standardnotes/websockets-server@1.4.14) (2022-11-10)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.13](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.12...@standardnotes/websockets-server@1.4.13) (2022-11-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.12](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.11...@standardnotes/websockets-server@1.4.12) (2022-11-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.11](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.10...@standardnotes/websockets-server@1.4.11) (2022-11-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.10](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.9...@standardnotes/websockets-server@1.4.10) (2022-11-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.9](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.8...@standardnotes/websockets-server@1.4.9) (2022-11-09)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.8](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.7...@standardnotes/websockets-server@1.4.8) (2022-11-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.7](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.6...@standardnotes/websockets-server@1.4.7) (2022-11-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.6](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.5...@standardnotes/websockets-server@1.4.6) (2022-11-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.4...@standardnotes/websockets-server@1.4.5) (2022-11-07)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.3...@standardnotes/websockets-server@1.4.4) (2022-11-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.2...@standardnotes/websockets-server@1.4.3) (2022-11-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.1...@standardnotes/websockets-server@1.4.2) (2022-11-04)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.4.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.4.0...@standardnotes/websockets-server@1.4.1) (2022-11-03)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.4.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.5...@standardnotes/websockets-server@1.4.0) (2022-11-02)

### Features

* **auth:** add processing user requests ([2255f85](https://github.com/standardnotes/server/commit/2255f856f928e855ac94f8aca4e1fb81047f58f7))

## [1.3.5](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.4...@standardnotes/websockets-server@1.3.5) (2022-11-02)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.3.4](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.3...@standardnotes/websockets-server@1.3.4) (2022-11-01)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.3.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.2...@standardnotes/websockets-server@1.3.3) (2022-10-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.3.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.1...@standardnotes/websockets-server@1.3.2) (2022-10-31)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.3.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.3.0...@standardnotes/websockets-server@1.3.1) (2022-10-26)

**Note:** Version bump only for package @standardnotes/websockets-server

# [1.3.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.2.0...@standardnotes/websockets-server@1.3.0) (2022-10-24)

### Features

* **auth:** change accepting invitations to be an authorized endpoint ([771a555](https://github.com/standardnotes/server/commit/771a555b4f33452311cd5bf0b8cfcbc4f2f1c4dd))

# [1.2.0](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.1.3...@standardnotes/websockets-server@1.2.0) (2022-10-19)

### Features

* building server applications in ARM64 architecture for Docker ([fd92866](https://github.com/standardnotes/server/commit/fd92866ba1a86b22769b23cc4c8387a83f87979a))

## [1.1.3](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.1.2...@standardnotes/websockets-server@1.1.3) (2022-10-13)

**Note:** Version bump only for package @standardnotes/websockets-server

## [1.1.2](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.1.1...@standardnotes/websockets-server@1.1.2) (2022-10-13)

### Bug Fixes

* **websockets:** add http client binding ([4e21edc](https://github.com/standardnotes/server/commit/4e21edce6b034312f121db4dce716e82ff7d5eaa))

## [1.1.1](https://github.com/standardnotes/server/compare/@standardnotes/websockets-server@1.1.0...@standardnotes/websockets-server@1.1.1) (2022-10-13)

### Bug Fixes

* **websockets:** remove unnecessary sns bindings ([2f7ef49](https://github.com/standardnotes/server/commit/2f7ef497ab4875685d6a0f282eeae11005900bc3))

# 1.1.0 (2022-10-13)

### Features

* **websockets:** add websockets service ([d28c268](https://github.com/standardnotes/server/commit/d28c268e86644f34f5550eeded5bb4a7407d4a99))
