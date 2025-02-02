# Change Log

All notable changes to the Defold Kit extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2.1.1] - 2023-11-11

### Changed

- Optional extensions are now unselected during setup by default. Most people obviously don't need them.

### Fixed

- Fixed confusing false start of an old build, in case of new build error. Now the old build is deleted in this case to avoid accidental launch.

## [2.1.0] - 2023-10-19

### Added

- Added the `Open Defold` command to open the current project in the Defold Editor.

## [2.0.8] - 2023-10-10

### Changed

- Changed the build path to avoid conflicts with the Defold Editor build.

## [2.0.7] - 2023-10-03

### Fixed

- Fixed the soft migration of the workspace launch configuration.

## [2.0.6] - 2023-10-03

### Changed

- Renamed the category of tasks and commands from `Defold` to `Defold Kit` to avoid conflicts.
- Renamed all the settings keys from `defold.` to `defoldKit.` to avoid conflicts.
- Renamed launch configuration to `Defold Kit` to avoid conflicts.

### Added

- Soft migration of user settings from `defold.` to `defoldKit.` keys.
- Soft migration of the workspace launch configuration from `Defold` to `Defold Kit` name.

## [2.0.5] - 2023-09-30

### Removed

- Removed everything related the `Launch (without debugger)` and `Build to Launch` commands to avoid confusing.
- Now the only way to launch the game is using the `Run ang Debug` panel.

## [2.0.4] - 2023-09-30

### Fixed

- Fixed the launch command for a project with spaces in the path.

## [2.0.3] - 2023-09-26

### Added

- Added an additional annotations source to the settings — [d954mas/defold-api-emmylua](https://github.com/d954mas/defold-api-emmylua).

## [2.0.2] - 2023-09-22

### Fixed

- Fixed `dmengine` selection bug for macOS with Intel during preparing for launch.


## [2.0.1] - 2023-09-19

### Fixed

- Unwrapped `require('debugger.debugger’)` calls in the docs and in the `debugger.script`file to avoid problems with Defold code analyser before build

## [2.0.0] - 2023-09-18

- Initial release