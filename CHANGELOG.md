# Changelog
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [3.0.1] - 10-03-2019
### Changed
- Laravel 5.8 tests
## [3.0.0] - 27-05-2018
#### BREAKING CHANGES, PLEASE SEE [DOCUMENTATION](https://docs.laralabs.uk/toaster)
### Added
- Groups - groups of messages can now be created
- Group Helper Functions - width(), classes(), position(), max() and reverse()
- Message Helper Functions - duration() and speed()
- Vue component npm package created to remove need for excess code/instructions [laralabs-vue-toaster](https://github.com/Laralabs/vue-toaster)
- @toastcomponent blade directive to echo component markup into view
- 'toast_stagger' config option - stagger message duration using the 'toast_lifetime' and 'toast_interval' config options 
### Changed
- Overhaul to work with a more advanced frontend component [euvl/vue-notification](https://github.com/euvl/vue-notification)
### Removed
- expires() function.
- 'js_namespace' config option removed, namespace will always be 'toaster'
## [2.0.1] - 29-01-2018
### Changed
- composer.json updated to fix packagist
## [2.0.0] - 19-09-2017
### Added
- Support for using redirect()
- @toaster blade directive
### Changed
- Unit tests altered to reflect changes
### Removed
- toast() function no longer needed
- 'bind_js_vars_to_this_view' config option
## [1.1.0] - 12-09-2017
### Added
- update() function to mass update previous message properties
- Unit Tests