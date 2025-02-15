# Changelog
All notable changes to this project will be documented in this file.

## 0.0.5 - 20 September 2022
### Added
- New "Mask Padding" option that allows you to easily expand the boundaries of the selected mask region

## 0.0.4 - 19 September 2022
### Added
- Support for mask prompt delimiter, use `|` to specify multiple selctions which will be stacked additively to produce the final mask image

### Changed
- Fixed a possible issue with the clipseg weight downloader
- Fix for crash related to inpainting at full resolution

## 0.0.3 - 19 September 2022
### Added
- Added option to show mask in output

## 0.0.2 - 18 September 2022
### Changed
- Readme and Changelog moved to `docs/txt2mask` so as not to conflict with Automatic's repo

### Removed
- Model weights are no longer included with the repo as they will not download properly through Github's website, instead the model files will be fetched by the script if they do not exist on your filesystem

## 0.0.1 - 17 September 2022
### Added
- Initial release