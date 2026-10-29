# Changelog

## [2.6.0](https://github.com/bkobus-bbx/blebox_uniapi/compare/v2.5.9...v2.6.0) (2026-10-29)


### Features

* add index and name properties to sensors, switches and lights ([#185](https://github.com/bkobus-bbx/blebox_uniapi/issues/185)) ([20faf7a](https://github.com/bkobus-bbx/blebox_uniapi/commit/20faf7ad60600b3ff34af90a2bf1f21ed0163155))
* add is_calibrated property to Shutter and is_slider guard ([#193](https://github.com/bkobus-bbx/blebox_uniapi/issues/193)) ([5f0be49](https://github.com/bkobus-bbx/blebox_uniapi/commit/5f0be498f94ce7db49f3ba03b47fb2a7b88376f4))
* add is_position_inverted to expose position convention per device type ([#181](https://github.com/bkobus-bbx/blebox_uniapi/issues/181)) ([be63c03](https://github.com/bkobus-bbx/blebox_uniapi/commit/be63c035388d240867d1d94a3109974f0e5ab951))
* add new methods to cover feature enabling handling of tilt open/close actions ([dcc7319](https://github.com/bkobus-bbx/blebox_uniapi/commit/dcc7319759e5e76ec781d0a1faf16d47575927dc))
* add new methods to cover feature enabling handling of tilt open/close actions ([6ee8678](https://github.com/bkobus-bbx/blebox_uniapi/commit/6ee86782286a45f4b9b12cf934314aaf13a2e53d))
* add new ShutterBox control types and tilt properties ([#190](https://github.com/bkobus-bbx/blebox_uniapi/issues/190)) ([a977239](https://github.com/bkobus-bbx/blebox_uniapi/commit/a977239fbe233c880110b66dc58cb0cd75568fa6))
* add reactive energy sensors for energyMeter ([#192](https://github.com/bkobus-bbx/blebox_uniapi/issues/192)) ([19de0f5](https://github.com/bkobus-bbx/blebox_uniapi/commit/19de0f5786b0e9a6696415dd606cf89be4d68396))
* add support for CO2Sensor ([#195](https://github.com/bkobus-bbx/blebox_uniapi/issues/195)) ([ac05dfc](https://github.com/bkobus-bbx/blebox_uniapi/commit/ac05dfc05c62fcc8c5b29df1015195bab03da428))
* add support for inputSensor ([#183](https://github.com/bkobus-bbx/blebox_uniapi/issues/183)) ([cb08d4a](https://github.com/bkobus-bbx/blebox_uniapi/commit/cb08d4a8cf19df1d47d886b6f486975133d910e3))
* add support for openSensor as both generic and binary sensor ([#184](https://github.com/bkobus-bbx/blebox_uniapi/issues/184)) ([a4e0a64](https://github.com/bkobus-bbx/blebox_uniapi/commit/a4e0a6437b1baecdfb6fb750166fd5861180c4a5))
* add temperature sensors to thermoBox ([#189](https://github.com/bkobus-bbx/blebox_uniapi/issues/189)) ([775510e](https://github.com/bkobus-bbx/blebox_uniapi/commit/775510ec628994a4be8725bcf33a167da31e68f6))
* add voltage measurement support for switchBox ([#194](https://github.com/bkobus-bbx/blebox_uniapi/issues/194)) ([964adf6](https://github.com/bkobus-bbx/blebox_uniapi/commit/964adf632424807e2d40cc3128fa79d6e8e6050b))
* BleBox Multisensor Illuminance Integration ([#161](https://github.com/bkobus-bbx/blebox_uniapi/issues/161)) ([dbd5e11](https://github.com/bkobus-bbx/blebox_uniapi/commit/dbd5e1163df86fe6e61881cf7f89e5e6dcbdeb59))
* expose gateBox extra button output as a button entity ([#201](https://github.com/bkobus-bbx/blebox_uniapi/issues/201)) ([eb72cb4](https://github.com/bkobus-bbx/blebox_uniapi/commit/eb72cb434eb132a18cf1c365ae5fc129640ad5f7))
* expose product on Box for HASS device model display ([#200](https://github.com/bkobus-bbx/blebox_uniapi/issues/200)) ([7ff36de](https://github.com/bkobus-bbx/blebox_uniapi/commit/7ff36deb0eaf60c69171716fba6309a40986ddcd))


### Bug Fixes

* add round with 1 decimal place for wind speed value ([9977712](https://github.com/bkobus-bbx/blebox_uniapi/commit/997771274a2ed993c9433608351e0fb209e512b6))
* add sensor_id and name parameters to Open and Input binary sensor classes ([#186](https://github.com/bkobus-bbx/blebox_uniapi/issues/186)) ([1c308d9](https://github.com/bkobus-bbx/blebox_uniapi/commit/1c308d9263534efc12c2acc17f745ff6b125e45f))
* added default api level to dimmreBox ([c6fb0c9](https://github.com/bkobus-bbx/blebox_uniapi/commit/c6fb0c938f65e2f5b5ae7302f04ef6f059812369))
* bring back switchbox (non-d) power measurment ([1d7ae73](https://github.com/bkobus-bbx/blebox_uniapi/commit/1d7ae73a904a4f91d48ead4f7e24f8e5a5587b65))
* bump2version setup and config ([#199](https://github.com/bkobus-bbx/blebox_uniapi/issues/199)) ([89dd112](https://github.com/bkobus-bbx/blebox_uniapi/commit/89dd112e2e9edee118c89745cd559cf33455896d))
* color mode logic to restore last color value correctly ([#187](https://github.com/bkobus-bbx/blebox_uniapi/issues/187)) ([dfbf3bd](https://github.com/bkobus-bbx/blebox_uniapi/commit/dfbf3bd79c4bc8a0629cb48af2ec75a428ce0fd3))
* correct api path ([4678bd2](https://github.com/bkobus-bbx/blebox_uniapi/commit/4678bd216988f5b85ca5144217833ca5fc780b05))
* Energy sensor feature returned if in extended state ([577f577](https://github.com/bkobus-bbx/blebox_uniapi/commit/577f57767ae5a2a65fa1070b6e34ec10c626a0d9))
* ensure sensible_on_value returns list for MONO mode ([#182](https://github.com/bkobus-bbx/blebox_uniapi/issues/182)) ([bc3a78c](https://github.com/bkobus-bbx/blebox_uniapi/commit/bc3a78ce11e7dad475b3be8b563757911fdfb8c2))
* For cctx2 set proper length mask, deppending on desired color ([f9852e7](https://github.com/bkobus-bbx/blebox_uniapi/commit/f9852e726a94258898699b4838deec70a7490ae2))
* handle sensor state and thermoBox safety off ([#202](https://github.com/bkobus-bbx/blebox_uniapi/issues/202)) ([1321ce5](https://github.com/bkobus-bbx/blebox_uniapi/commit/1321ce505fa3864276a5408ab6b30e8c6d45e9fa))
* if boost,set is_on true ([d1b71fc](https://github.com/bkobus-bbx/blebox_uniapi/commit/d1b71fc7f85c223e30c41ff2f5a6e7c6f4be2a4b))
* in doorBox extraButtonType doesn't exist in payload ([0f1b68d](https://github.com/bkobus-bbx/blebox_uniapi/commit/0f1b68d0dbf9d897dc2bbbd8269a7f42570541ae))
* log caught API-call exceptions at debug instead of error ([#198](https://github.com/bkobus-bbx/blebox_uniapi/issues/198)) ([f25183e](https://github.com/bkobus-bbx/blebox_uniapi/commit/f25183e83db0a7ac8773861c588c5b64fca88e2c))
* multisensor current and energy sensor scales ([#180](https://github.com/bkobus-bbx/blebox_uniapi/issues/180)) ([06f2b4d](https://github.com/bkobus-bbx/blebox_uniapi/commit/06f2b4de706d0465af8d17ec363541c39ed844ab))
* query both info endpoints in OTA check ([#203](https://github.com/bkobus-bbx/blebox_uniapi/issues/203)) ([a6683c4](https://github.com/bkobus-bbx/blebox_uniapi/commit/a6683c4cf92e932278d2ed653bae05bc9b56230b))
* race condition between relay/sensor state in switchbox + all documented switchboxd api sets ([da18bbc](https://github.com/bkobus-bbx/blebox_uniapi/commit/da18bbc26c66df439ab0b5138142fee268ded1b5))
* rectify ambiguity around powerConsumption and wind sensor types ([0b00027](https://github.com/bkobus-bbx/blebox_uniapi/commit/0b00027a66f6fa673d14047cae34e540bc608f3f))
* Refactor sensor_factory ([#163](https://github.com/bkobus-bbx/blebox_uniapi/issues/163)) ([5a1c536](https://github.com/bkobus-bbx/blebox_uniapi/commit/5a1c5363c83cdc9abb49ab86364ce6c78652231a))
* reorder specs for switchboxd and fix wrong api definitions ([4848ddb](https://github.com/bkobus-bbx/blebox_uniapi/commit/4848ddb46f10edafeaf83aab718a95a17cd0dd3c))
* resolve regression in v20180604 (oldest) switchbox support ([9630c32](https://github.com/bkobus-bbx/blebox_uniapi/commit/9630c3262cefba185e048999bef551b084bdbea1))
* resolve regression in v20180604 (oldest) switchbox support ([d982d96](https://github.com/bkobus-bbx/blebox_uniapi/commit/d982d9615a0a082babb522a8815e7e8955c01939))
* resolve regressions in cover and climate due to jmespath introduction ([#173](https://github.com/bkobus-bbx/blebox_uniapi/issues/173)) ([19a01f1](https://github.com/bkobus-bbx/blebox_uniapi/commit/19a01f1dd54217c07f18da2c9b8f5c91fdec2d0e))
* return correct state in gateBox when currentPos unknown ([ee22fd0](https://github.com/bkobus-bbx/blebox_uniapi/commit/ee22fd0d0b8f127d79a74a82cf36f4f7fdc14c26))
* small refactor efter tests ([61de765](https://github.com/bkobus-bbx/blebox_uniapi/commit/61de7659a1ec7168bf43e9d77119141968c375b6))
* switchbox with v20220114 api level support ([066af0d](https://github.com/bkobus-bbx/blebox_uniapi/commit/066af0dcfced32e8fab5da8eaf005df2d5e8ad89))
* tankSensor liquidHeight and volume are reported in mm and ml ([#206](https://github.com/bkobus-bbx/blebox_uniapi/issues/206)) ([7512f43](https://github.com/bkobus-bbx/blebox_uniapi/commit/7512f4394c2452c77c7d65e9c2d2c645a58019a3))
* test against latest switchboxd boxtype manifest ([b7eb1c7](https://github.com/bkobus-bbx/blebox_uniapi/commit/b7eb1c7491a1c477d9ca2e4825eb9be28a774e8c))
* turns out switchbox v20190808 also supports power measuring sensor data too ([7229949](https://github.com/bkobus-bbx/blebox_uniapi/commit/7229949276f773b11e4da561168f909615d2a79b))
* turns out switchbox v20200229 also supports power measuring sensor data ([2b1e0d5](https://github.com/bkobus-bbx/blebox_uniapi/commit/2b1e0d56c32921b4c02fdd33544f883257e24d73))
* update box_type manifests for switchbox ([01ad7e1](https://github.com/bkobus-bbx/blebox_uniapi/commit/01ad7e1018fe0ad67288a7eaa7417598167db82f))
* wind value is divided by 10 to get proper raw m/s value ([d345dd3](https://github.com/bkobus-bbx/blebox_uniapi/commit/d345dd321ab7a7b505a8cfb966559ab07123e747))
* wind value is divided by 10 to get proper raw m/s value ([d8a809d](https://github.com/bkobus-bbx/blebox_uniapi/commit/d8a809d46a637993f9dab34b5c9d737deaaf4e25))


### Documentation

* remove defunct badges ([06038a0](https://github.com/bkobus-bbx/blebox_uniapi/commit/06038a0ccfc1499c406cb4ea7f340a0ff51eed34))
* update release info ([fcddc98](https://github.com/bkobus-bbx/blebox_uniapi/commit/fcddc98f7e99a7345086d8ba3247745ae9f438ec))
* Version bump ([3cef0a4](https://github.com/bkobus-bbx/blebox_uniapi/commit/3cef0a41406942ac97150754ee685bd4ab1d9a29))
* version indicator changed in related docs ([ead8d16](https://github.com/bkobus-bbx/blebox_uniapi/commit/ead8d1695d8d0a12219801dfcead822bc28a85d5))

## [2.5.9](https://github.com/blebox/blebox_uniapi/compare/v2.5.8...v2.5.9) (2026-10-18)


### Bug Fixes

* tankSensor liquidHeight and volume are reported in mm and ml ([#206](https://github.com/blebox/blebox_uniapi/issues/206)) ([7512f43](https://github.com/blebox/blebox_uniapi/commit/7512f4394c2452c77c7d65e9c2d2c645a58019a3))

## [2.5.8](https://github.com/blebox/blebox_uniapi/compare/v2.5.7...v2.5.8) (2026-10-01)

### Features

* support tankSensor ([#204](https://github.com/blebox/blebox_uniapi/issues/204)) ([2f93dac](https://github.com/blebox/blebox_uniapi/commit/2f93dac7ad020cd504921e7f5c710e6a4549ed21))

### Bug Fixes

* query both info endpoints in OTA check ([#203](https://github.com/blebox/blebox_uniapi/issues/203)) ([a6683c4](https://github.com/blebox/blebox_uniapi/commit/a6683c4cf92e932278d2ed653bae05bc9b56230b))

## [2.5.7](https://github.com/blebox/blebox_uniapi/compare/v2.5.6...v2.5.7) (2026-08-12)

### Bug Fixes

* handle sensor state and thermoBox safety off ([#202](https://github.com/blebox/blebox_uniapi/issues/202)) ([1321ce5](https://github.com/blebox/blebox_uniapi/commit/1321ce505fa3864276a5408ab6b30e8c6d45e9fa))

## [2.5.6](https://github.com/blebox/blebox_uniapi/compare/v2.5.5...v2.5.6) (2026-08-06)

### Features

* expose gateBox extra button output as a button entity ([#201](https://github.com/blebox/blebox_uniapi/issues/201)) ([eb72cb4](https://github.com/blebox/blebox_uniapi/commit/eb72cb434eb132a18cf1c365ae5fc129640ad5f7))
* expose product on Box for HASS device model display ([#200](https://github.com/blebox/blebox_uniapi/issues/200)) ([7ff36de](https://github.com/blebox/blebox_uniapi/commit/7ff36deb0eaf60c69171716fba6309a40986ddcd))

### Bug Fixes

* log caught API-call exceptions at debug instead of error ([#198](https://github.com/blebox/blebox_uniapi/issues/198)) ([f25183e](https://github.com/blebox/blebox_uniapi/commit/f25183e83db0a7ac8773861c588c5b64fca88e2c))

## [2.5.5](https://github.com/blebox/blebox_uniapi/compare/v2.5.4...v2.5.5) (2026-06-09)

### Features

* add support for CO2Sensor ([#195](https://github.com/blebox/blebox_uniapi/issues/195)) ([ac05dfc](https://github.com/blebox/blebox_uniapi/commit/ac05dfc05c62fcc8c5b29df1015195bab03da428))
* add voltage measurement support for switchBox ([#194](https://github.com/blebox/blebox_uniapi/issues/194)) ([964adf6](https://github.com/blebox/blebox_uniapi/commit/964adf632424807e2d40cc3128fa79d6e8e6050b))
* add is_calibrated property to Shutter and is_slider guard ([#193](https://github.com/blebox/blebox_uniapi/issues/193)) ([5f0be49](https://github.com/blebox/blebox_uniapi/commit/5f0be498f94ce7db49f3ba03b47fb2a7b88376f4))
* add reactive energy sensors for energyMeter ([#192](https://github.com/blebox/blebox_uniapi/issues/192)) ([19de0f5](https://github.com/blebox/blebox_uniapi/commit/19de0f5786b0e9a6696415dd606cf89be4d68396))

## [2.5.4](https://github.com/blebox/blebox_uniapi/compare/v2.5.3...v2.5.4) (2026-05-25)

### Features

* add OTA firmware update support via Update feature ([#191](https://github.com/blebox/blebox_uniapi/issues/191)) ([b3bfbf6](https://github.com/blebox/blebox_uniapi/commit/b3bfbf671335443294691ce72b719b57196b534d))
* add new ShutterBox control types and tilt properties ([#190](https://github.com/blebox/blebox_uniapi/issues/190)) ([a977239](https://github.com/blebox/blebox_uniapi/commit/a977239fbe233c880110b66dc58cb0cd75568fa6))
* add temperature sensors to thermoBox ([#189](https://github.com/blebox/blebox_uniapi/issues/189)) ([775510e](https://github.com/blebox/blebox_uniapi/commit/775510ec628994a4be8725bcf33a167da31e68f6))

### Bug Fixes

* RGBWW brightness and channel ordering ([#188](https://github.com/blebox/blebox_uniapi/issues/188)) ([02251d9](https://github.com/blebox/blebox_uniapi/commit/02251d944fca3991a341bcd1fdcffdfda60435ff))
* color mode logic to restore last color value correctly ([#187](https://github.com/blebox/blebox_uniapi/issues/187)) ([dfbf3bd](https://github.com/blebox/blebox_uniapi/commit/dfbf3bd79c4bc8a0629cb48af2ec75a428ce0fd3))
* add sensor_id and name parameters to Open and Input binary sensor classes ([#186](https://github.com/blebox/blebox_uniapi/issues/186)) ([1c308d9](https://github.com/blebox/blebox_uniapi/commit/1c308d9263534efc12c2acc17f745ff6b125e45f))

## [2.5.3](https://github.com/blebox/blebox_uniapi/compare/v2.5.2...v2.5.3) (2026-05-08)

### Features

* add support for openSensor as both generic and binary sensor ([#184](https://github.com/blebox/blebox_uniapi/issues/184)) ([a4e0a64](https://github.com/blebox/blebox_uniapi/commit/a4e0a6437b1baecdfb6fb750166fd5861180c4a5))
* add index and name properties to sensors, switches and lights ([#185](https://github.com/blebox/blebox_uniapi/issues/185)) ([20faf7a](https://github.com/blebox/blebox_uniapi/commit/20faf7ad60600b3ff34af90a2bf1f21ed0163155))
* add support for inputSensor ([#183](https://github.com/blebox/blebox_uniapi/issues/183)) ([cb08d4a](https://github.com/blebox/blebox_uniapi/commit/cb08d4a8cf19df1d47d886b6f486975133d910e3))

### Bug Fixes

* ensure sensible_on_value returns list for MONO mode ([#182](https://github.com/blebox/blebox_uniapi/issues/182)) ([bc3a78c](https://github.com/blebox/blebox_uniapi/commit/bc3a78ce11e7dad475b3be8b563757911fdfb8c2))

## [2.5.2](https://github.com/blebox/blebox_uniapi/compare/v2.5.1...v2.5.2) (2026-04-24)

### Features

* add is_position_inverted to expose position convention per device type ([#181](https://github.com/blebox/blebox_uniapi/issues/181)) ([be63c03](https://github.com/blebox/blebox_uniapi/commit/be63c035388d240867d1d94a3109974f0e5ab951))

## 2.5.1 (2026-04-21)

* fix: multisensor current and energy sensor scales

## 2.5.0 (2024-08-20)

* feature: expose sensor_id in sensors and alias in all features by @swistakm in https://github.com/blebox/blebox_uniapi/pull/176

## 2.4.2 (2024-06-04)

* fix: add missing support for active power sensors on switchbox/switchboxd devices by @swistakm in https://github.com/blebox/blebox_uniapi/pull/175

## 2.4.1 (2024-06-04)

* fix: rectify ambiguity around powerConsumption and wind sensor types

## 2.4.0 (2024-06-03)

* Fix: Refactor sensor_factory by @Pastucha in https://github.com/blebox/blebox_uniapi/pull/163
* Order in BOX_TYPES by @Pastucha in https://github.com/blebox/blebox_uniapi/pull/164
* Feature: smart meter by @swistakm in https://github.com/blebox/blebox_uniapi/pull/168
* Smartmeter by @pvsti in https://github.com/blebox/blebox_uniapi/pull/170
* fix: resolve regressions in cover and climate due to jmespath introduction by @swistakm in https://github.com/blebox/blebox_uniapi/pull/173

## 2.3.0 (2024-03-13)

* feat: add new methods to cover feature enabling handling of tilt open/close actions by @swistakm in https://github.com/blebox/blebox_uniapi/pull/154
* add support for flood sensing for multisensors as binary moisture sensor by @swistakm in https://github.com/blebox/blebox_uniapi/pull/153
* feat/fix: Add Ruff and Pre-commit Configuration, Resolve Undefined Name by @Pastucha in https://github.com/blebox/blebox_uniapi/pull/158
* gatebox and shutterbox improvements: by @swistakm in https://github.com/blebox/blebox_uniapi/pull/156
* BleBox Multisensor Illuminance Integration by @Pastucha in https://github.com/blebox/blebox_uniapi/pull/161

## 2.2.2 (2024-02-07)

* fixed wind reading units to get proper raw m/s value (division by 10, see PR #150)

## 2.2.1 (2024-01-26)

* fixed support for power measurement capabilities of switchBox and switchBoxD devices

## 2.2.0 (2023-08-29)

* added last_reset to energy sensor class
* added BasicAuth support to http client

## 2.1.4 (2023-01-03)

* added tilt position support for `cover.Shutter`
* added `Wind` for wind sensor of multisensors
* added `Energy` sensor class for power consumption tracking
* implementing `default_api_level` for
  * dimmerBox
  * wLightBox
  * wLightBoxS

## 2.1.3 (2022-10-27)

* thermoBox boost mode doesn't corrupt state

## 2.1.2 (2022-10-17)

* fixed CCT, CCTx2 modes for wLightBox v1 & v2

## 2.1.1 (2022-10-11)

* added support for thermoBox devices:
  * added thermoBox config to `BOX_TYPE_CONFIG`
  * `Climate` uses factory method implementation
  * added test coverage

## 2.1.0 (2022-08-05)

* added support for multiSensor API:
  * `airQuality` moved to sensor module
  * new binary_sensor module, introducing `Rain` class

## 2.0.2 (2022-07-06)

* added `query_string` property in `Button` class
* fixed test assertions after changes in error raised ValueError

## 2.0.1 (2022-06-01)

* used `ValueError` type instead of `BadOnValueError` in methods:
  * evaluate_brightness_from_rgb
  * apply_brightness
  * normalise_elements_of_rgb
  * _set_last_on_value
  * async_on

## 2.0.0 (2022-06-21)

* extended support for color modes in wLightBox devices
* initial support for tvLiftBox device
* major backward-incompatible architectural changes to enable dynamic configuration of devices
* removed products.py module and replaced with factory method on Box class
* general overhaul of public interfaces

## 1.3.3 (2021-05-12)

* fix support for wLightBoxS with wLightBox API
* fix state detection in gateBox

## 1.3.2 (2020-04-2)

* use proper module-level logger by default
* fix formatting

## 1.3.1 (2020-04-2)

* never skip command requests
* improve error messages

## 1.2.0 (2020-03-30)

* expose device info
* always add ip/port in connection errors
* fixed gateController support
* support for sauna min/max temp

## 1.1.0 (2020-03-24)

* fix bad wLightBox API path
* wrap api calls in semaphore (to serialize reqests to each box)
* throttle updates to 2/second (to avoid unnecessary requests)
* rework error handling and hierarchy (for cleaner usage)
* use actual device name (to help recognize the device)
* handle asyncio.TimeoutError (to handle timeout-related errors nicely)
* properly re-raise exceptions (to avoid lengthy call stacktraces)
* rename wLightBoxS feature to "brightness"

## 1.1.0 (2020-03-24)

* fix switchBox support
* fix minimum position handling
* drop Python 3.6 support (still may work)
* misc fixes, cleanup and increased test coverage

## 1.0.0 (2020-03-24)

* Fixed wLightBox issues
* Fixed wLightBoxS issues
* Fixed shutterBox issues
* Handle unknown shutterBox position
* Improved error handling + lots of new diagnostics
* Increased tests and test coverage (almost 100%)
* Lots of rework

## 0.1.1 (2020-03-15)

* Fixed switchBox support (newer API versions)

## 0.1.0 (2020-03-10)

* First release on PyPI.
