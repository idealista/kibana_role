# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased](https://github.com/idealista/kibana_role/tree/develop)

## [1.1.1](https://github.com/idealista/kibana_role/tree/1.1.0)
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
