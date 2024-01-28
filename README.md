# caesar

Caesar is an open-source project reimplementing Discord's desktop bootstrapper and core modules[^1].

## The What

Caesar is a free and open-source, stability- and performance-oriented reimplementation of the Discord desktop bootstrapper application. This is commonly referred to as the `app.asar` file[^2].

Caesar will be distributed both as a packed ASAR archive to be used with an existing Discord installation and also as a standalone application.

## The Why

Discord's official bootstrapper is slow, bloated, and unhackable. Caesar aims to fix this. Alternatives exist, such as [GooseMod](https://github.com/GooseMod/OpenAsar) and my own personal (and now unmaintained) fork [steviegt6/nucleus](https://github.com/steviegt6/nucleus), but they are unsatisfactory.

The two main reasons to create an alternative to OpenAsar instead of forking it and potentially contributing back are 1) OpenAsar reuses large swaths of proprietary code and 2) the project scopes are simply different; OpenAsar aims to reimplement the main bootstrapper while Caesar has its eyes further set on reimplementing modules used by the bootstrapper.

Caesar also intends to provide first-class support for many client modifications, with compatibility as a focus.

## The How

skillz

...and also:

-   [GooseMod/OpenAsar](https://github.com/GooseMod/OpenAsar),
-   [steviegt6/nucleus](https://github.com/steviegt6/nucleus),
-   [OpenAsar/discord-desktop-datamining](https://github.com/OpenAsar/discord-desktop-datamining),
-   and more.

## Installation

TODO, there is a GTK installer in the works for easy end-user installations. Documentation for building from source is also TODO.

## Licensing

Caesar is currently licensed under the GNU Affero General Public License v3.0. I would like to keep it this way, though it may be subject to change.

[^1]: Not all core modules will be reimplemented. Effort is required to reverse-engineer native modules.
[^2]: The most notable example of this is [GooseMod/OpenAsar](https://github.com/GooseMod/OpenAsar).
