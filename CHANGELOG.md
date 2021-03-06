# Change Log

## 1.0.7

### Added
- Added support for markdown-it-decorate attributes
- Added "Create Module.json" command.

### Changed
- Made page, group, and module IDs more deterministic in generation - based off the Module ID.

### Fixed
- Fixed heading underlines extending into stat blocks in preview

## 1.0.6

### Added
- Added statbock table style and additional table handling (column span, cell span, etc.)

### Fixed
- Improved handling of selection when using format toggles
- Improved detection of word selection on format toggles
- Fixed bug in group slug generation
- Fixed blockquote styling
- Fixed background image being broken again.

## 1.0.5
### Added
- Added Visual Studio Code Extension part of Module Packer
  - Previews markdown as it would appear in EncounterPlus
  - Can invoke module packer from Visual Studio Code
  - Adds tools for working with Markdown in Visual Studio Code
- Added support for setting Module properties via `module.json` file
- Added help button to Module Packer
- Added support for additional markdown syntax: underline, subscript, superscript, mark
- Added {.headerTitle}, {.green}, {.blue}, {.red}, {.yellow}, and {.gray} styles attributes for tables

### Changed
- `ModuleOutput` folder was renamed to `ModuleBuild`
- Codebase was changed to use typescript

## 0.9.3
### Added
- Support for image size attributes
- Allow drag-and-drop of module folder onto window

## 0.9.2
### Added
- Support for creating groups based on directories in Module folder
- Support for cover images on pages generated from pagebreaks

### Changed
- If pagebreaks are specified, but none are detected, a page will still be created
- Made module output generate in its own `ModuleOutput` folder rather than modifying contents of the original folder

### Fixed
- Fixed errors in font names in CSS style
- Fixed default page background image not rendering in some viewers