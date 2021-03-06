# CHANGELOG

## Introduction

This CHANGELOG tells you:

* when a release was made
* what is in each release

It also tells you what changes have been completed, and will be included in the next tagged release.

For each release, changes are grouped under these headings:

* _Backwards-Compatibility Breaks_: a list of any backwards-compatibility breaks
* _New_: a list of new features. If the feature came from a contributor via a PR, make sure you link to the PR and give them a mention here.
* _Fixes_: a list of bugs that have been fixed. If there's an issue for the bug, make sure you link to the GitHub issue here.
* _Dependencies_: a list of dependencies that have been added / updated / removed.
* _Tools_: a list of bundled tools that have been added / updated / removed.

## develop branch

The following changes have been completed, and will be included in the next tagged release.

## v0.2.1

Released Tuesday, 26th May 2020.

### New

* Added `addExtension()`
  - based on the older `addExtensions()` function
  - name better reflects that we can only add one type of extension at a time

### Deprecated

* `addExtensions()` is now deprecated
  - use `addExtension()` instead

## v0.2.0

Released Thursday, 21st May 2020.

### Backwards-Compatibility Breaks

* `augment()` is now `addExtensions()`

### New

* Added `hasAllMethodsCalled()`.
* Added `buildDeepProtocolDefinition()`.
* Added `buildProtocolDefinition()`.
* Added `implementsProtocol()`.
* Added `PrototypeDefinition`.

## v0.1.0

Released Wednesday, 20th May 2020.

### New

* Added `augment()`
