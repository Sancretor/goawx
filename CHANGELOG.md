## [1.1.2](https://github.com/roondar/goawx/compare/v1.1.1...v1.1.2) (2023-04-14)


### Bug Fixes

* import schedule type with extra_data ([c82a275](https://github.com/roondar/goawx/commit/c82a27563ddc21d0d02530462a10a6ada1c969e3))

## [1.1.1](https://github.com/roondar/goawx/compare/v1.1.0...v1.1.1) (2023-04-05)


### Bug Fixes

* Use roondar as name ([6634ecc](https://github.com/roondar/goawx/commit/6634ecc36ba5a40fe0037df93dd843ac720dabdc))

# [1.1.0](https://github.com/roondar/goawx/compare/v1.0.0...v1.1.0) (2023-04-05)


### Features

* Use roondar in links ([35199ce](https://github.com/roondar/goawx/commit/35199ce2d80d95fb2e0760fd950f85d0ad7b6b50))

# 1.0.0 (2023-04-05)


### Bug Fixes

* add schedule inventory field ([878b010](https://github.com/roondar/goawx/commit/878b01024ec7e6c03d500bae1e5674cba8b3f964))
* add service to client ([e66e698](https://github.com/roondar/goawx/commit/e66e698ab737d913d6b2a58baa28771c796f2117))
* always workflow node type api call ([#6](https://github.com/roondar/goawx/issues/6)) ([17716db](https://github.com/roondar/goawx/commit/17716dbc2b0b042cfd42969f40043f6638db6352))
* bad authorization header for tokens [#15](https://github.com/roondar/goawx/issues/15) ([#16](https://github.com/roondar/goawx/issues/16)) ([49d273e](https://github.com/roondar/goawx/commit/49d273e4b9dedd877eba9c526ac0e8c06b9839d4))
* remove check not present return parameter ([c1c8f45](https://github.com/roondar/goawx/commit/c1c8f453b3cc2a5818082fcdf852560345bd2571))
* rename schedule service list function ([1d95fc7](https://github.com/roondar/goawx/commit/1d95fc7ec4b7fd8e421498d05e47d65711912db3))
* rename variable after merge ([d90656d](https://github.com/roondar/goawx/commit/d90656d07388b39f867b1878204e3193ed95e1b5))
* unified_job_template is not mandatory for workflow_job_template schedules ([6186119](https://github.com/roondar/goawx/commit/618611919a98ac6dcb0b985d293c12df24c5ba2e))


### Features

* add (job_template,workflow_job_template) notification_templates association disassociation ([a5f3828](https://github.com/roondar/goawx/commit/a5f382810811bac8dec0fac20045433a6c9ea7b4))
* add notification_templates ([24bff42](https://github.com/roondar/goawx/commit/24bff42c6c5573e17f213422c1bcf170ac2626a9))
* add schedule service and rename package ([856e28c](https://github.com/roondar/goawx/commit/856e28c116cb3804e7e8dc807fd167674db53bfe))
* add workflow_job_template_schedule service ([85ffc50](https://github.com/roondar/goawx/commit/85ffc5016ad3636da84e0abc2c53aa4138c7034c))
* Complete ObjectRoles map ([9eb69d9](https://github.com/roondar/goawx/commit/9eb69d942d1d55d9d7e80967119809cf6cb0b482))
* execution environments ([#4](https://github.com/roondar/goawx/issues/4)) ([91b8780](https://github.com/roondar/goawx/commit/91b8780e8d496b6c8f2467360dd332216276c9df))
* feeds team resource ([#17](https://github.com/roondar/goawx/issues/17)) ([d7fd4ca](https://github.com/roondar/goawx/commit/d7fd4ca550c03449c5db4d147ff93880639d7442))
* launch workflow job template ([fd0a966](https://github.com/roondar/goawx/commit/fd0a9665f5ca16a30b340153c83af505855c4ec9))
* manage for instance groups ([#14](https://github.com/roondar/goawx/issues/14)) ([d03a5b5](https://github.com/roondar/goawx/commit/d03a5b5792b55056b0fe2e9be44b9e4f511c251c))
* manage organization Galaxy credentials ([#20](https://github.com/roondar/goawx/issues/20)) ([e45fbfe](https://github.com/roondar/goawx/commit/e45fbfe3cdb6ccabcb071b2a3a7393c9f671cdda))
* user roles ([#18](https://github.com/roondar/goawx/issues/18)) ([4bef306](https://github.com/roondar/goawx/commit/4bef306525626c7e82128dc73dcf092d5198be29))
* **Application:** Added application API suport ([7f173e8](https://github.com/roondar/goawx/commit/7f173e8e4c2f05845c5589ce99bf938a7805bf89))
* **Authentication:** Added ability to construct a token based AWX authentication experience ([60c73f4](https://github.com/roondar/goawx/commit/60c73f4855bd7aebe2bd5565905fa1c1ce4ff937))
* support execution environments (since AWX 18.0.0) ([#3](https://github.com/roondar/goawx/issues/3)) ([ea6baec](https://github.com/roondar/goawx/commit/ea6baecaa65b98e4b2f627618a565ad3189c953b))

# [0.18.0](https://github.com/denouche/goawx/compare/v0.17.0...v0.18.0) (2023-01-10)


### Bug Fixes

* remove check not present return parameter ([c1c8f45](https://github.com/denouche/goawx/commit/c1c8f453b3cc2a5818082fcdf852560345bd2571))


### Features

* launch workflow job template ([fd0a966](https://github.com/denouche/goawx/commit/fd0a9665f5ca16a30b340153c83af505855c4ec9))

# [0.17.0](https://github.com/denouche/goawx/compare/v0.16.0...v0.17.0) (2022-10-31)


### Features

* manage organization Galaxy credentials ([#20](https://github.com/denouche/goawx/issues/20)) ([e45fbfe](https://github.com/denouche/goawx/commit/e45fbfe3cdb6ccabcb071b2a3a7393c9f671cdda))

# [0.16.0](https://github.com/denouche/goawx/compare/v0.15.0...v0.16.0) (2022-10-31)


### Features

* user roles ([#18](https://github.com/denouche/goawx/issues/18)) ([4bef306](https://github.com/denouche/goawx/commit/4bef306525626c7e82128dc73dcf092d5198be29))

# [0.15.0](https://github.com/denouche/goawx/compare/v0.14.1...v0.15.0) (2022-10-31)


### Features

* feeds team resource ([#17](https://github.com/denouche/goawx/issues/17)) ([d7fd4ca](https://github.com/denouche/goawx/commit/d7fd4ca550c03449c5db4d147ff93880639d7442))

## [0.14.1](https://github.com/denouche/goawx/compare/v0.14.0...v0.14.1) (2022-10-25)


### Bug Fixes

* bad authorization header for tokens [#15](https://github.com/denouche/goawx/issues/15) ([#16](https://github.com/denouche/goawx/issues/16)) ([49d273e](https://github.com/denouche/goawx/commit/49d273e4b9dedd877eba9c526ac0e8c06b9839d4))

# [0.14.0](https://github.com/denouche/goawx/compare/v0.13.1...v0.14.0) (2022-10-24)


### Features

* manage for instance groups ([#14](https://github.com/denouche/goawx/issues/14)) ([d03a5b5](https://github.com/denouche/goawx/commit/d03a5b5792b55056b0fe2e9be44b9e4f511c251c))

## [0.13.1](https://github.com/denouche/goawx/compare/v0.13.0...v0.13.1) (2022-07-22)


### Bug Fixes

* rename variable after merge ([d90656d](https://github.com/denouche/goawx/commit/d90656d07388b39f867b1878204e3193ed95e1b5))

# [0.13.0](https://github.com/denouche/goawx/compare/v0.12.0...v0.13.0) (2022-07-22)


### Features

* **Application:** Added application API suport ([7f173e8](https://github.com/denouche/goawx/commit/7f173e8e4c2f05845c5589ce99bf938a7805bf89))

# [0.12.0](https://github.com/denouche/goawx/compare/v0.11.0...v0.12.0) (2022-07-22)


### Features

* **Authentication:** Added ability to construct a token based AWX authentication experience ([60c73f4](https://github.com/denouche/goawx/commit/60c73f4855bd7aebe2bd5565905fa1c1ce4ff937))

# [0.11.0](https://github.com/denouche/goawx/compare/v0.10.1...v0.11.0) (2022-07-22)


### Features

* Complete ObjectRoles map ([9eb69d9](https://github.com/denouche/goawx/commit/9eb69d942d1d55d9d7e80967119809cf6cb0b482))

## [0.10.1](https://github.com/denouche/goawx/compare/v0.10.0...v0.10.1) (2022-07-01)


### Bug Fixes

* always workflow node type api call ([#6](https://github.com/denouche/goawx/issues/6)) ([17716db](https://github.com/denouche/goawx/commit/17716dbc2b0b042cfd42969f40043f6638db6352))

# [0.10.0](https://github.com/denouche/goawx/compare/v0.9.0...v0.10.0) (2022-05-11)


### Features

* execution environments ([#4](https://github.com/denouche/goawx/issues/4)) ([91b8780](https://github.com/denouche/goawx/commit/91b8780e8d496b6c8f2467360dd332216276c9df))

# [0.9.0](https://github.com/denouche/goawx/compare/v0.8.0...v0.9.0) (2022-04-20)


### Features

* support execution environments (since AWX 18.0.0) ([#3](https://github.com/denouche/goawx/issues/3)) ([ea6baec](https://github.com/denouche/goawx/commit/ea6baecaa65b98e4b2f627618a565ad3189c953b))

# [0.8.0](https://github.com/denouche/goawx/compare/v0.7.0...v0.8.0) (2022-01-05)


### Features

* add (job_template,workflow_job_template) notification_templates association disassociation ([a5f3828](https://github.com/denouche/goawx/commit/a5f382810811bac8dec0fac20045433a6c9ea7b4))

# [0.7.0](https://github.com/denouche/goawx/compare/v0.6.3...v0.7.0) (2022-01-04)


### Features

* add notification_templates ([24bff42](https://github.com/denouche/goawx/commit/24bff42c6c5573e17f213422c1bcf170ac2626a9))

## [0.6.3](https://github.com/denouche/goawx/compare/v0.6.2...v0.6.3) (2021-12-23)


### Bug Fixes

* add schedule inventory field ([878b010](https://github.com/denouche/goawx/commit/878b01024ec7e6c03d500bae1e5674cba8b3f964))

## [0.6.2](https://github.com/denouche/goawx/compare/v0.6.1...v0.6.2) (2021-12-23)


### Bug Fixes

* unified_job_template is not mandatory for workflow_job_template schedules ([6186119](https://github.com/denouche/goawx/commit/618611919a98ac6dcb0b985d293c12df24c5ba2e))

## [0.6.1](https://github.com/denouche/goawx/compare/v0.6.0...v0.6.1) (2021-12-23)


### Bug Fixes

* add service to client ([e66e698](https://github.com/denouche/goawx/commit/e66e698ab737d913d6b2a58baa28771c796f2117))

# [0.6.0](https://github.com/denouche/goawx/compare/v0.5.1...v0.6.0) (2021-12-23)


### Features

* add workflow_job_template_schedule service ([85ffc50](https://github.com/denouche/goawx/commit/85ffc5016ad3636da84e0abc2c53aa4138c7034c))

## [0.5.1](https://github.com/denouche/goawx/compare/v0.5.0...v0.5.1) (2021-12-23)


### Bug Fixes

* rename schedule service list function ([1d95fc7](https://github.com/denouche/goawx/commit/1d95fc7ec4b7fd8e421498d05e47d65711912db3))

# [0.5.0](https://github.com/denouche/goawx/compare/v0.4.2...v0.5.0) (2021-12-23)


### Features

* add schedule service and rename package ([856e28c](https://github.com/denouche/goawx/commit/856e28c116cb3804e7e8dc807fd167674db53bfe))
