# KSP Config Support

Provides support for [Kerbal Space Program](https://kerbalspaceprogram.com) configuration files.

![syntax highlighting example](img/examples.png)

## Supported Features

* Syntax highlighting for KSP `.cfg`, `.craft`, and `.sfs` files
* Full [ModuleManager](https://github.com/sarbian/ModuleManager) syntax support

## Known issues

* Tuples of floats using the exponent syntax (ex. `2.03E-09`) are sometimes highlighted as strings
* Erratic behavior when a closing brace is not placed on its own line
