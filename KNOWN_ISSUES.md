# Bug/Error Log 

All notable bugs or errors with the "nightlion-aptana-devstyle" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2025-01-26

### Bugs

- The Javadoc comments are not being styled entirely correctly. 
    - Namely, the `@link` and `@code` tags are having issues with the coloring being overridden by other scopes. More specifically, the two annotations are being colored and bolded as a "Javadoc Annotation" (`keyword.other.documentation.javadoc.java`) instead of being colored as a "Javadoc Link" (`comment.block.documentation.other.javadoc.link`/`comment.block.documentation.other.javadoc.code`). 
    - Moreover, any classes, methods, or functions that are being documented with the `@link` or `@code` tags are not being properly colored. They will take on the color of the Class/Method/Function that is being documented instead of the color of the "Javadoc Link".
- Hovering over a method, function, or variable in the editor will improperly colorize the parameters, return types, or other parts of the method/function/variable. This behavior is also present in the traditional VS Code theme, and thus is likely not a bug within this extension. That said, it does appear to behave differently than the VS Code theme and likely has to do with the differences in semantic highlighting vs. token coloring.