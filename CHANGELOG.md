# Change Log

All notable changes to the "nightlion-aptana-devstyle" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2025-01-26

### Added

- v1.0.1 - Minor Features
    - Added colorization for constructors.
    - Added colorization for JSON keys seperate from the colorization for Strings.
    - Resolved an issue where the image of the theme in the README was not showing up on the VS Code Marketplace.

## [1.0.0] - 2025-01-26

### Added

- v1.0.0 - Initial release
    - Complete support for the NightLion Aptana theme for Java.
    - Partial support for the NightLion Aptana theme for the following languages:
        - JavaScript, Python, Go, C/C++, C#,, CSS, HTML, JSON, PHP, Ruby, Shell, SQL, Swift, TypeScript, XML, Markdown.
    - All languages have native support for the following features:
        - Comment stylization to differ between `//` and `/* */` for single-line and multi-line comments, as well as documentation comments (`/** */`).
        - Native support for highlighting of TODO comments without the need for a separate extension.
        - Strikethrough stylization of deprecated elements.