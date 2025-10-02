# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased](https://github.com/idealista/kibana_role/tree/develop)

## [3.0.3](https://github.com/idealista/kibana_role/tree/3.0.3)
### Fixed
Fix combine with recursive=True to properly merge deep keys one by one. @adrian-arapiles


## [3.0.2](https://github.com/idealista/kibana_role/tree/3.0.2)
### Fixed
Fix typo combine 2 list for lib dependencies. @adrian-arapiles

## [3.0.1](https://github.com/idealista/kibana_role/tree/3.0.1)
### Added
Add gpg missing dependency in deb installation. @adrian-arapiles
Add the posibility to override lib requirements. @adrian-arapiles


## [3.0.0](https://github.com/idealista/kibana_role/tree/3.0.0)
### Added
Add support for debian bullseye. @adrian-arapiles  
### Changed
*[22](https://github.com/idealista/kibana_role/issues/22)* Remove support of archived opendistro project. @adrian-arapiles
Removed tests for debian stretch. @adrian-arapiles  
Updated test-requirements dependencies. @adrian-arapiles  

## [2.1.0](https://github.com/idealista/kibana_role/tree/2.1.0)
### Added
- *Add fqcn to warn-list due to ansible-lint* @adrian-arapiles
- *Add tags on tasks* @adrian-arapiles

### Changed
- *Update requirements dependencies to latest* @adrian-arapiles
- *Remove step changing folders on deb installation due an idempotence error* @adrian-arapiles
- *Update docker base image buster* @adrian-arapiles

## [2.0.0](https://github.com/idealista/kibana_role/tree/2.0.0)
### Added
- [#16](https://github.com/idealista/kibana_role/issues/16) *Support for install kibana as unzipped tar as previous versions for default installation mode* @adrian-arapiles
- [#16](https://github.com/idealista/kibana_role/issues/16) *Support for install kibana as debian service.* @adrian-arapiles
- [#16](https://github.com/idealista/kibana_role/issues/16) *Support for install kibana (opendistroelasticsearch distribution).* @adrian-arapiles

### Changed
- *Update test-requirements dependencies and goss* @adrian-arapiles
- *Update default versions to current* @adrian-arapiles
- *Tests with stretch and buster distribution* @adrian-arapiles

## [1.2.0](https://github.com/idealista/kibana_role/tree/1.2.0)
### Added
- [#6](https://github.com/idealista/kibana_role/issues/6) *Add support of custom parameters to kibana.yml* @adrian-arapiles
- *Upgraded test-requirements*   @adrian-arapiles
- *Added Pipfile and Pipfile.lock* @adrian-arapiles
- *Remove unnecessary files of molecule* @adrian-arapiles

## [1.1.1](https://github.com/idealista/kibana_role/tree/1.1.1)
### Fixed
- *Fix pid directory creation error in start* @acuervof

## [1.1.0](https://github.com/idealista/kibana_role/tree/1.1.0)
### Added
- [#1](https://github.com/idealista/kibana_role/issues/1) *Support of oss version with new molecule scenario **oss*** @adrian-arapiles

### Changed
- *Molecule change to privileged:false* @adrian-arapiles
- *Elasticsearch config on tests with **discovery.type: single-node** for avoid to change vm.max_map_count* @adrian-arapiles
- *Add flag **--allow-root** for check version task* @adrian-arapiles

### Fixed
- *Rename group name on test to avoid conflict with host name* @adrian-arapiles

## [1.0.0](https://github.com/idealista/kibana_role/tree/1.0.0)
### Added
- *First release* @acuervo
