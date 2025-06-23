# Changelog

All notable changes to the Workflow Documentation Tool (WDT4vRO) will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Initial changelog file

## [1.0.0] - 2024-06-23
### Added
- GitHub icon and "Open Issue" button in the top navigation
- Dynamic visibility toggling for GitHub and Open Issue buttons
- Improved download functionality for workflow diagrams

### Changed
- Updated UI to hide GitHub and Open Issue buttons when a workflow is loaded
- Enhanced error messaging for download operations
- Improved SVG selection for more accurate diagram exports

### Fixed
- Fixed issue where download button was capturing GitHub icon instead of workflow diagram
- Removed duplicate event listeners for the download button
- Added proper dimension handling for exported SVG images

### Security
- Added proper error handling for external resource loading
- Improved security by ensuring proper cleanup of temporary DOM elements

---
*Note: This changelog was started on 2024-06-23. Previous changes before this date are not documented in this file.*
