# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Glossary](#glossary)

## Report an issue

Have an issue to report? Let us know at <https://github.com/StartBootstrap/pro-feedback/issues>.

Please reference that you're using `SB Admin Pro`
along with details about the issue you're having.

## [2.0.0] - 2021-05-20

- [Updated] Bootstrap 5.0.1 update
- [Updated] Dependencies updated throughout
- [Updated] Bootstrap 5 mixins now being used throughout SCSS and extended components
- [Changed] Spacing in card headers with actions adjusted for uniformity
- [Changed] Badge padding in sidenav adjusted so nav links do not enlarge
- [Added] Upgraded to workerpool for pug rendering
- [Removed] DataTables plugin removed due to dependency on jQuery
- [Added] Simple DataTables plugin added to replace DataTables functionality with JS only
- [Removed] DateRangePicker plugin removed due to dependency on jQuery and inactive development
- [Added] Litepicker plugin added to replace DateRangePicker functionality with JS only

## [1.3.1] - 2021-03-29

- [Updated] Bootstrap 4.6.0 dependency update along with all other dependencies

## [1.3.0] - 2020-11-09

- [Added] New global styling for form inputs and buttons
- [Added] Card angles style variant added
- [Changed] File paths updated for fonts and images referenced in the CSS
- [Changed] Demo images are now local to the project instead of loading from a CDN
- [Updated] Bootstrap 4.5.3 dependency update along with all other dependencies
- [Fixed] Fixed responsiveness of the sidenav to prevent the toggle icon from becoming hidden
on small devices.
- [Fixed] dataTables maxBarThickness moved in bar chart demo (due to dataTables update)
- [Changed] Made asset paths in css files relative for freelancer version via release process.

## [1.2.1] - 2020-11-11

- [Changed] New release process and licenses for startbootstrap.com release. No code changes.

## [1.2.0] - 2020-07-08

- [Added] New demo pages, new components, and general improvements

## [1.1.2] - 2020-03-20

- [Fixed] Normalize window paths to unix with upath
- [Fixed] npm start not working on paths that have spaces in them

## [1.1.1] - 2020-02-25

- [Added] Init sidebar script

## [1.1.0] - 2020-02-25

- [Added] Created two new dashboard demos, multipurpose and affiliate
- [Added] Added an avatars custom component
- [Added] Added the lift utility
- [Added] Added background image utilities
- [Added] Added background overlay utilities
- [Changed] General improvements to SCSS to improve code legibility and compatibility with the SB
UI Kit pro theme
- [Changed] Dropped the `.sb-` prefix namespace on custom components and utilities for ease of use
with Bootstrap's existing elements
- [Changed] Styling updates to the topnav, including the navbar brand and dropdowns
- [Changed] General styling update with new font face and other style improvements
- [Fixed] Resolved alignment issues with the RTL layout topnav
- [Fixed] Resolved responsiveness errors on the cards style reference page
- [Changed] Updated dev dependencies

## [1.0.2] - 2020-02-18

- [Fixed] Windows scss build issue.

## [1.0.1] - 2020-01-14

- [Added] mixin support for pug.

## [1.0.0] - 2020-01-13

- Initial Release!

## Glossary

- `[Added]` for new features.
- `[Changed]` for changes in existing functionality.
- `[Deprecated]` for soon-to-be removed features.
- `[Removed]` for now removed features.
- `[Fixed]` for any bug fixes.
- `[Security]` in case of vulnerabilities.
