# Localize Javascript SDK Releases

Please see the [Localize Help Center](https://help.localizejs.com/docs/library-api) for SDK usage and configuration documentation.

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

## Version 447 - August 10, 2021

 * **[Fix]**: Under the hood changes that improve overall compatability of the In-Context Editor across a wide variety of edge cases [DEV-2688]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.447.js"></script>
// Script tag with SRI
<script src="https://global.localizecdn.com/localize.447.js" integrity="sha512-+mzz5ZxGKX4RJFGT0H+X+sIB5S+eYQLn+TAl9fMeZTHT73W153HkkuncXRt8xqwAHI2W+rgweg1uHQeiCZDEyw==" crossorigin="anonymous"></script>
```

## Version 446 - July 16, 2021

 * **[Fix]**: Using the "isolate" attribute on a container with a `<br>` tag caused the phrase to be broken apart [DEV-2553]
 * **[Change]**: Within SVGs, group together `<tspan>` elements that are adjacent to one another [DEV-2152]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.446.js"></script>
// Script tag with SRI
<script src="https://global.localizecdn.com/localize.446.js" integrity="sha512-+mzz5ZxGKX4RJFGT0H+X+sIB5S+eYQLn+TAl9fMeZTHT73W153HkkuncXRt8xqwAHI2W+rgweg1uHQeiCZDEyw==" crossorigin="anonymous"></script>
```

## Version 445 - June 8, 2021

 * **[Fix]**: Resolve issue with arrow functions breaking compatibility with certain versions of IE

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.445.js"></script>
// Script tag with SRI
<script src="https://global.localizecdn.com/localize.445.js" integrity="sha512-in79nKZ9JljhnbUFi3seLHtGcUF9qHI+fFJdmlS3SO8418r7ddNu2qm3Hi6pVNaNpxtf7uX+T60FV0BkQ9a5OA==" crossorigin="anonymous"></script>
```

## Version 444 - June 7, 2021

 * **[Feature]**: Allow wildcards when defining what domains new phrases can be detected from [DEV-2308]
 * **[Improvement]**: Save detected phrases from both source and target language when a project is first created [DEV-2109]
 * **[Fix]**: Make in-progress reviewable translations visible in the in-context editor [DEV-2201]
 * **[Fix]**: Remove unneeded reference to S3 when retrying failed dictionary file fetch [DEV-2316]
 * **[Fix]**: Language not remembered when returning from disabled page when the widget was disabled [DEV-2090]
 * **[Fix]**: Additional fix for the bug: certain phrases injected into the DOM weren't translated (in certain edge cases involving nested nodes) with the library options `translateBody: false`, and `retranslateOnNewPhrases: true`  [DEV-2339]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.444.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.444.js" integrity="sha512-CpuIvzLGGVF+XVqIB0zjQA21CbceoL685q7Eema3sCrkX67BlJ6zPNvSJqFhWcqKDENDKkWObquIwR8S0FY8NQ==" crossorigin="anonymous"></script>
```

## Version 443 - May 24, 2021

 * **[Fix]**: Certain phrases injected into the DOM weren't translated (in certain edge cases involving nested nodes) with the library options `translateBody: false`, and `retranslateOnNewPhrases: true`  [DEV-2339]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.443.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.443.js" integrity="sha512-fT1vG/WLbqiiGK8HFShu883aiLL80tydfxMWOOwFBLeKHrn9BAojQrsKyrEX8NvezadkdpG7SuetqI7IRI3iZQ==" crossorigin="anonymous"></script>
```

## Version 442 - May 21, 2021

 * **[Fix]**: The `isolate` attribute was not respected when a SVG existed as a child node [DEV-2090]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.442.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.442.js" integrity="sha512-HTva+vkfBKviP6npLJS6C37A969TZrl2IzgxUDlv+/OJdCGoAUxjHrlspVo5HUC9nUYmwckAegACC2+ll+iTIA==" crossorigin="anonymous"></script>
```

## Version 441 - Apr 7, 2021

 * **[Fix]**: Language not remembered when returning from disabled page [DEV-2090]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.441.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.441.js" integrity="sha512-oJQkAwLDbUurUphYse7eCAKDXUFdgXlxiX4cTp7fVd+ntElWMdHgPEyXLLG5kBxylgBxFcqWW9Z6IPG/PK2amg==" crossorigin="anonymous"></script>
```

## Version 440 - Apr 1, 2021

 * **[Fix]**: Resolved issues with SVGs not being properly handled in the In-Context Editor

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.440.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.440.js" integrity="sha512-1kjlhC8A9d1v1lb6iXZjBfCTrs8RJp7+c65nR/35PgRt/4LjjhADjtmRiAnrfcCU2AaQEC8g4y3A/tsxaApC0Q==" crossorigin="anonymous"></script>
```

## Version 439 - Mar 19, 2021

 * **[Fix]**: Resolved issue with Disabled Pages not allowing disabling of just the root domain of a site.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.439.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.439.js" integrity="sha512-GIiPt9oVH9Rw+rI3fphCY9G6KB+9/y1iuApLtnQ0sOWT2lvYYrBq90XrEN24ROHj2gr+FzldbWXf/wmS3WEw1Q==" crossorigin="anonymous"></script>
```

## Version 438 - Feb 8, 2021

 * **[Fix]**: Resolve issue with widget showing up when it's being hidden by the Disbaled Pages dashboard setting in certain edge cases.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.438.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.438.js" integrity="sha512-9KEqteRrrJGzPUX1/qVgDaRFXZjcXDAMHKQ0Na85JMKNuLvl1edFcNYgDy97I3bo5VXBnaiav4ZB0DDb9BpvxQ==" crossorigin="anonymous"></script>
```

## Version 436/437 - Jan 2, 2021

 * **[Fix]**: Remove unnecessary API calls to minimize network usage

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.436.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.436.js" integrity="sha512-hsCAfwS229YHCa/X/zbXFz0/geM8c9TNXxnyAdhepklDeRbQ+lPyjrxF4F2TmNse8BJcEhN0fOVx+cXGiDZiSw==" crossorigin="anonymous"></script>
```


## Version 434/435 - Dec 7, 2020

 * **[Feature]**: Adds ability to restrict what domains new phrases can be saved from based on a whitelist provided in Library Settings within the Localize Dashboard.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.434.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.434.js" integrity="sha512-chQZjGd6k5TXstV9NYYARx1QRlL6wuMlnF+WqEgq56Mf6EgylNJKE80pTZTwmoVlYKq77Ap7Jxr3f0x4skgiWg==" crossorigin="anonymous"></script>
```

## Version 433 - November 16, 2020

 * **[Bug fix]**: Resolves a recently discovered edge case where MutationObserver doesn't pick up text changes properly

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.433.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.433.js" integrity="sha512-UzRXwYAJM/Rq+6gcp69t7Ut2ydAwQNq9CGHz4ZjkL6vkEgi7kyp5q8tPr0R7BgHTpH+zanUOwpDv0kHxHxWNdA==" crossorigin="anonymous"></script>
```

## Version 432 - November 11, 2020

 * **[Performance]**: Embed the marketing integration project settings within the dictionary file to reduce latency + improve performance.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.432.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.432.js" integrity="sha512-pA8siNHj+dM8Gq0GlN9efU8Rj2xy/QoeXJBzQ3XCaWW1EFibEykPwt0y/gLco9hlFkUjMjhcNXz/VFtJy0eX1A==" crossorigin="anonymous"></script>
```

## Version 431 - November 8, 2020

 * **[Bug Fix]**: Resolves an edge case where `&` was sometimes rendered as `&amp;`
 * **[Performance]**: Embed the "Send debug information" project setting within the dictionary file to reduce latency + improve performance.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.431.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.431.js" integrity="sha512-DZcNM3Yh0RWkIrCY7eBwov/sNNsjrx7/D5K8x2MxHxFneCx8hJshW14LFFGlKSPJKaSGL45k0dJkwtQ2fTwSCg==" crossorigin="anonymous"></script>
```

## Version 430 - October 20, 2020

 * **[Bug Fix]**: When the Localize <> Google Analytics integration is enabled and analytics.js (`window.ga`) is used, the `nonInteraction` option is now set to `true` rather than unspecified so that GA accurately reports bounce rates. The previous fix for this bug only resolved users of `window.gtag`.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.430.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.430.js" integrity="sha512-jictTmnoWsYW0s2Gq7Y4LYaF4hXOvETkCPYEdb6bPF7ph0E+z8fKYm7r2OKzb7Srw4qHyBd/2Vx7dFJ8JNP+Zg==" crossorigin="anonymous"></script>
```

## Version 429 - September 25, 2020

 * **[Bug Fix]**: When the Localize <> Google Analytics integration is enabled, set the `non_interaction` option to `true` rather than unspecified so that GA accurately reports bounce rates.

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.429.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.429.js" integrity="sha512-PiH4+oAVpsCsyO8SFlx7xCCV6k/BRIDvMHvMdvwKJyRQsXvxe+88J7uilEZwUwzz+4oOdcMa+z2NBTHXfo5uJQ==" crossorigin="anonymous"></script>
```

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
