# NSM Fields Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 0.0.7 - 2017.12.08
### Fixed
- Fixes #15 Cannot read property 'serialize' of undefined - Address.js:88 

## 0.0.6 - 2017.12.04
### Changed
- Added LICENSE.md

## 0.0.5 - 2017.12.03
### Changed
- Craft 3 beta 36 compatibility
- Address Field Updates:
    * Always show country selector
    * Set the default country code for new entries

## 0.0.4 - 2017.06.31
### Added
- Added person name field
- Added gender field
### Changed
- Craft 3 beta 23 compatibility
- All fields store `null` in the DB if empty. Templates also receive `null` if the value is empty


## 0.0.3
### Added
- Added embed field
### Changed
- Craft 3 beta 20 compatibility
- Updated plugin handle to nsm-fields from nsmFields

## 0.0.2 - 2017.06.12
### Fixed
- Hooked up autocomplete field settings with plugin

## 0.0.1 - 2017.06.04
### Added
- Initial release
