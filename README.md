# Localize Javascript SDK Releases

Please the [Localize Help Center](https://help.localizejs.com/docs/library-api) for SDK usage and configuration documentation.

### Introduction

There are two methods of loading the Localize Javascript SDK script tag.

1. **Unversioned script tag**: 
    - `<script src="https://global.localizecdn.com/localize.js"></script>`
2. **Versioned script tag**:
    - `<script src="https://global.localizecdn.com/localize.VERSION.js"></script>`

Localize occasionally updates the Localize Javascript SDK with new features and bug fixes. The unversioned script tag receives these updates automatically, while the versioned script tag requires manual upgrades.


**Additional notes**:
- New versions of the Javascript SDK are backwards compatible with prior versions.
- When using the versioned script tag, we recommend upgrading to the latest version every 3-6 months.
- We recommend "watching" this repository to receive alerts when new versions of the SDK are released.


**Subresource Integrity (SRI)**

If you wish to load the Localize script using [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity), you must use the versioned script tag. You can find the SRI hash in the release notes for each version below.


# Release Notes

## Version 428 - September 22, 2020

 * **[Bug Fix]**: When passing `blockedClasses` or `blockedIds` into `Localize.initialize({ ... })`, Blocked Classes / IDs configured via project settings in the Localize dashboard were not respected.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.428.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.428.js" integrity="sha512-2bpiizy5ZhZl+FjqLvlCAhtztC+rmftJmFUvl1B4r/krctRBW7WKHE/ty42fuOlTnLuf3m3V+rRJ9xAlTUP1RA==" crossorigin="anonymous"></script>
```

## Version 427 - September 11, 2020

 * **[New Feature]**: Add support for disabling the Localize SDK on a per-page basis (or by matching regex) via the "Disable Localize by Page" Library Setting, configurable in the Localize dashboard.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.427.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.427.js" integrity="sha512-RWVE4x0qfgOjY3F0lncL/u36A/UOKf/GJkKHYPbNF6ip0zHKD70kVxFgPQwMjUTOzVdFRJ0On15IUuifmoF1KQ==" crossorigin="anonymous"></script>
```

## Version 426 - August 28, 2020

 * Initial release of the versioned SDK.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.426.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.426.js" integrity="sha384-fZBu/+Xwktt/IKgd806x78V4OAzcdJEbaL9mCtLNUNST5150AyopLNSsG9zXPtcA" crossorigin="anonymous"></script>
```
