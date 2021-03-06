# habitat CHANGELOG

This file is used to list changes made in each version of the habitat cookbook.

## v0.4.0 (2017-04-26)

- Backwards incompatible version, requires habitat 0.20 or higher
- Add `hab_sup` resource for managing Habitat supervisor. See readme for usage.
- Rewrite `hab_service` resource to manage services in Habitat supervisor

## v0.3.0 (2017-02-21)

- Add property for ExecStart options. See readme for usage
- Add property for depot_url. See readme for usage
- Added restart action to the resource

## v0.2.0 (2016-11-30)

- Added `version` and `channel` properties to install resource
- Added `depot_url` property to hab_package resource

## v0.1.1 (2016-11-10)

- Removed Chef 11 compatibility in the metadata
- Resolved Chefstyle warnings
- Resolved foodcritic warnings
- Added a chefignore file
- Updated the gitignore file
- Improve the readme format and add badges
- Update all test deps to current
- Remove the apt testing dependency
- Add integration testing in Travis using kitchen-dokken

## v0.1.0 (2016-11-08)

- add `hab_service` resource
- make the `hab_package` resource convergent
- add chefspec and inspec tests
- better documentation through README updates

## v0.0.3 (2016-07-14)

- Initial release, includes `hab_package` and `hab_install` resources
