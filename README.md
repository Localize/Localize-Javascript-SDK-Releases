# Localize Javascript SDK Release Notes

Please the [Localize Help Center](https://help.localizejs.com/docs/library-api) for SDK usage and configuration documentation.

## Introduction

There are two methods of loading the Localize Javascript SDK script tag.

1. **Unversioned script tag**: 
    - `<script src="https://global.localizecdn.com/localize.js"></script>`
2. **Versioned script tag**:
    - `<script src="https://global.localizecdn.com/localize.VERSION.js"></script>`

Localize occasionally updates the Localize Javascript SDK with new features and bug fixes. The unversioned script tag receives these updates automatically, while the versioned script tag requires manually upgrades.


**Additional notes**:
- New versions of the Javascript SDK are backwards compatible with prior versions.
- When using the unversioned script tag, we recommend upgrading to the latest version every 3-6 months.
- We recommend watching this repository to receive alerts when new versions of the SDK are released.


**Subresource Integrity (SRI)**

If you wish to load the Localize script using [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity), you must use the versioned script tag. You can find the SRI hash in the release notes for each version below.


## Release Notes

## Version 426 / 2020-08-28
===================
 * This is the initial release of the versioned SDK.
