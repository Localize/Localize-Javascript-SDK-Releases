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


## Version 426 - August 28, 2020

 * Initial release of the versioned SDK.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.425.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.425.js" integrity="sha512-32/RzxRSnAlOpinrZE21dIg560KP/pnpQenzrYtgXoVFq+ZGJsWaaCpYRAmcfM4OQcWDsPcdQNBIcetGke9wyg==" crossorigin="anonymous"></script>
```
