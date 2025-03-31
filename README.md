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
## Version 507 - March 31, 2025
* **[Fix]**: Resolves a header incompatibility in support of the `Localize.translateImmediate` frontend API.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.507.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.507.js" integrity="sha512-8ewZ3L/VlBOYB8nVZ7Kk0WDDRTO4knXa4/y2X7Jsv9/Iphmi/RWDhzBYe7LRpJc01HB+A9j9ylSO0EZanpElnw==" crossorigin="anonymous"></script>
```

## Version 506 - March 3, 2025
* **[Feat]**: Localize In Context Editor (ICE) related internal updates.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.506.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.506.js" integrity="sha512-RraHPR/vuqGxxI1MWYbwVuqJ1D48fLQIq64NbPjmlJ6xVEuq2rslX6Twv2QezKtfYwt4RKmR9Bh0MDwXLUWvPw==" crossorigin="anonymous"></script>
```

## Version 505 - February 27, 2025
* **[Fix]**: Improve handling of `&` in source language phrases to harden against unwanted phrase duplication.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.505.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.505.js" integrity="sha512-qcMEWWLNLFhuhDsoqtoVZ2Oh3PM2hhUMvG2YcZ1VYyFS6LWu9dHgqDZP0LCE7XUGrTfFnRdW88YodTT2rk8dzg==" crossorigin="anonymous"></script>
```

## Version 504 - February 20, 2025
* **[Fix]**: Pluralization enhancements for dynamic content within the source language experience; support for `data-pluralize` attribute syntax added
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.504.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.504.js" integrity="sha512-rA+qBT/pxTcZD05fUOFwO2+Br+e4bZej0kTaGL/oC3DUv69OTPHX82ooZVZnTKl+Yu2oaHFQ4byGuPBmYLXTNQ==" crossorigin="anonymous"></script>
```

## Version 503 - February 10, 2025
* **[Feat]**: Added support for `srcset` when `localizeImages` project setting (aka 'Customize image files by language') is enabled
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.503.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.503.js" integrity="sha512-sNL6exsfZwKMynKWK8SOqb/YUfKDSgaCQD1m7MRgjUNGNb4d7D9bWT1uTAWg3eHn1gFinnu0VD9cvVJe40vG7w==" crossorigin="anonymous"></script>
```

## Version 502 - January 30, 2025
* **[Feat]**: Frontend API validation enhancements
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.502.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.502.js" integrity="sha512-yClhMtQd9bM/Pihxdgnlg0BcUBLcPkVSPEuw1zCNkkYLEE2++w/kEMcfH4EdPpipfi7cGQV0m1d9GC+I0Oqf+A==" crossorigin="anonymous"></script>
```

## Version 501 - January 16, 2025
* **[Fix]**: Improves cache handling for widget positioning updates.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.501.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.501.js" integrity="sha512-ondK4IfA6IuiS8C8y2cAOr+PK0dVGoPpoTEJf9iBtO3HTCo0zIgyWcPwgBHd8XZKJm4Y7ucfWBXUh0E+An1BWA==" crossorigin="anonymous"></script>
```

## Version 500 - January 9, 2025
* **[Feat]**: Introduces configuration support for fixed or relative widget display positioning.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.500.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.500.js" integrity="sha512-7LTG6+UZXQBmmeoZEPH/LMpnCNH2lhygt3qyDvLF7Cwwo8/iWPL7yME+DLk09t62gOObOQYSHFs84gJveFJKYA==" crossorigin="anonymous"></script>
```

## Version 499 - December 5, 2024
* **[Feat]**: Introduces a new `enableResilientDOMMode` configuration option to `Localize.initilize()` to respond gracefully to unhandled DOM mutation conflicts with other scripts.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.499.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.499.js" integrity="sha512-84aAdylbthz/pj7F5IEpcTsRTLPlc7Jmk6/ZyoxmksOFeHlyXdqcePlEqPO6BwS+nF9tRT6t4H/vMAEv8cSa/Q==" crossorigin="anonymous"></script>
```

## Version 498 - December 2, 2024
* **[Feat]**: Localize In Context Editor (ICE) related internal updates.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.498.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.498.js" integrity="sha512-nXtk/mOYYNjYGr8mxzWzwBJOcBTLXZ3H9moAmv0PBIpLCGxNH2dYzCF7gQot+Uej2rJgJBYK6P0EbaIFDqlEQg==" crossorigin="anonymous"></script>
```

## Version 497 - November 4, 2024
* **[Feat]**: Enhancements in support of the Localize In Context Editor (ICE), including SVG, Shadow Root, and editor-reload related updates.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.497.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.497.js" integrity="sha512-Zju/MvBtkRfiwVYX8tnIUxOm4q38CxIbd8tcbR228ETTBtN0aPYbMkhNS3X+HYYjH+pxk2Z9/Z7DZS35Qz7BpA==" crossorigin="anonymous"></script>
```

## Version 496 - October 31, 2024
* **[Fix]**: Handles an edge case related to 3rd party browser extension content-blocking detection.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.496.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.496.js" integrity="sha512-ybwOkEHYG+52h08ekfuaPQiVWr56LHRIohg85sqD8lJRllHHIxQMiqsqNTEp+ANqf6sZK4zfB/TXcHU+aHzCWA==" crossorigin="anonymous"></script>
```

## Version 495 - October 24, 2024
* **[Feat]**: Auto-blocks phrase content that is dynamically inserted by the 3rd-party ‘Translate’ Chrome browser extension.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.495.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.495.js" integrity="sha512-hMjuEEpdrauJL6903G/6ffIcvqvE3hW92T+oMO/K+rZ4A4ZOfRZ3ORp3KvUz79fLI+DaeB2Cfox0I7AVi8zvlg==" crossorigin="anonymous"></script>
```

## Version 494 - September 17, 2024
* **[Fix]**: Allow `hideLanguagesInWidget()` and `setWidgetLanguages()` methods to take immediate effect without the need for a refresh.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.494.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.494.js" integrity="sha512-bA+YPvsD1WEpwhMeEXg1gmdK9d4fEjcDvla+PmiAr3j0s8/IVGAf+5z+C1QYWT0MFCHO5j71yzvNmbsIendYoA==" crossorigin="anonymous"></script>
```

## Version 493 - August 28, 2024
* **[Fix]**: Allow for mixed case languages and locales when setting through ljs parameter. For example, `ljs=en-UK` and `ljs=en-uk` are both acceptable.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.493.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.493.js" integrity="sha512-wAEFhVJSg5EpSjly8iMbPvgg9A987KgpmyMFkbNcobGLiHf2rFb5IEgS785cRulLvtVeE2R/KPcG3O/4zwiZOw==" crossorigin="anonymous"></script>
```

## Version 492 - August 26, 2024
* **[Fix]**: Fixes issue where turning off widget while using targetLanguage parameter caused translations to not be delivered to websites.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.492.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.492.js" integrity="sha512-FO4C1MTdtbffvfaWwV6LSBCCLgaRF4Jm00eI7Q1gK+0RX1xl7oWtW5pwFxrPCAjerBKGC9fZc5mXTT8IpYYjzw==" crossorigin="anonymous"></script>
```

## Version 491 - August 22, 2024
* **[Feat]**: Add configuration options to allow for complex css blocking per project.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.491.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.491.js" integrity="sha512-sIoSfurpM0OiGo7WymAgg2ZBIA38QUcQUyRJKceKSnmMfr8nNURTERs93JgxDAL330U13pT9muz9YZVuWE3aaA==" crossorigin="anonymous"></script>
```

## Version 490 - August 15, 2024
* **[Feat]**: Supports the ability to hide particular languages within the Localize widget via new `setWidgetLanguages()` and `hideLanguagesInWidget()` frontend API methods
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.490.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.490.js" integrity="sha512-TuHJ1Y9lykBfFwWNRJBgSSabROadeKFZ/Rph6Tkw+OMTRiC39BdkdCSOejmRh8rQlLgBpSn6QCltrsPfxXcNMg==" crossorigin="anonymous"></script>
```

## Version 489 - August 8, 2024
* **[Feat]**: Add shadow root support for ICE
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.489.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.489.js" integrity="sha512-0QTL2MFFPCmU8hp5XVyfv9VOL+c2PavZr/LjH1R/YYdv74Besi5IYgUU6XsosXtJSd+dsBLzFDSRLAlLDQd7xA==" crossorigin="anonymous"></script>
```

## Version 488 - July 18, 2024
* **[Feat]**: Temporarily revert support for complex CSS selectors to give time for performance tuning of the feature.*
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.488.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.488.js" integrity="sha512-FWDLlPO935v8p3F45sFtryKN2yqHunu/FHGIuvokAXxoSg4a8mEZye/Z8hl35Mb6jzciewgK/eLQSi+kY+FJyw==" crossorigin="anonymous"></script>
```

## Version 487 - July 16, 2024
* **[Feat]**: Support complex CSS selectors for phrase blocking.  For example, you can now enter something like #my-id .my-class.
*
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.487.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.487.js" integrity="sha512-ewIc1gQgvL9xHaz+K2sQRKWDccA3/YlEL9tZCh31s4aCBvT7V90HC5bEc4T1GRnaNCHzUCKYnRReaxKudxFAXQ==" crossorigin="anonymous"></script>
```

## Version 486 - July 11, 2024
* **[Feat]**: Supports new initialize options to keep navigation in sync as languages are selected via the Localize widget for sites that use subdomains or subdirectories.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.486.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.486.js" integrity="sha512-ZKTgUUGib6lkN4Hpnm0SfvXwlHy2HzhmF+KuOqckStnPQc+gyo/JADu8O9x3AB032FsdjgH8v6Qlq5P08zXi1A==" crossorigin="anonymous"></script>
```

## Version 485 - May 28, 2024
* **[Fix]**: Fixes issue where In Context Editor would not load due to timing issue of document ready state.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.485.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.485.js" integrity="sha512-RokgHpdVvWFhJsb6AnlfnYSkmoDGu4iU0oonAORfPl0WXihuZJv+ge34YRvVQNcFbFJi0LoZc9+qPbXyeRsQAA==" crossorigin="anonymous"></script>
```

## Version 484 - April 29, 2024
* **[Fix]**: Update timing of dictionary downloads when using `retranslateOnNewPhrases` to correct potential timing issues between front end and back end processes.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.484.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.484.js" integrity="sha512-hgqyxVtUWRh8CsO783wzSrBJols8mATH42lgPGDxDpIBkbxqyI2L5TA6wuuaL1+MZx+VmOPXpGOFu1Jdy4jgmQ==" crossorigin="anonymous"></script>
```

## Version 483 - April 4, 2024
* **[Fix]**: Update to support list item selection within an isolated div in the In-Context Editor (ICE)
```
// Script tag without SRI
https://global.localizecdn.com/localize.483.js

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.483.js" integrity="sha512-gIeF7k6sUWFYi5aJVdrhOjgrhTEPko5A31oktOj66RP/RIAH2a9ikYBPQGEraTeHo3onJ2932NlgRJyIjQOjNg==" crossorigin="anonymous"></script>
```  

## Version 482 - March 7, 2024
* **[Fix]**: Update to disable the widget when a project key has been deleted, rotated, or is missing
```
// Script tag without SRI
https://global.localizecdn.com/localize.482.js

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.482.js" integrity="sha512-pSAmBAzW/TlvyQNaNu633ga5yMkHK3Ew9ykjYLDtva8VYqOK7bu1jYXEF4stQlykmt0N3vD2OAqdBzCgWv/fSg==" crossorigin="anonymous"></script>
```  

## Version 481 - February 19, 2024
* **[Fix]**: Fixes flicker introduced in version 480
```
// Script tag without SRI
https://global.localizecdn.com/localize.481.js

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.481.js" integrity="sha512-NJ5OK4TNItqXTWM6LgLKQXcqNEFL26UwINmC+7AjdHbBMf1VFyjkqeHYIKtBkOb02DR0waQH/EjKTDY0gAtwtg==" crossorigin="anonymous"></script>
```  

## Version 480 - February 15, 2024
* **[Fix]**: Fixes edge case of target language ingestion
```
 // Script tag without SRI
<script src="https://global.localizecdn.com/localize.480.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.480.js" integrity="sha512-NMmMurL+Ai7ObZtr9aK41p3yBQeAY14GnAXYgTw5IebWi3vZem12kOwQjKbxwKVFSkLWPpV1ZM9dVtXyPEtL4Q==" crossorigin="anonymous"></script>
```

## Version 479 - December 4, 2023
* **[Fix]**: Prevent ingesting of html content added by third party browser plugins. This most commonly happens when users have password managers, such as Dashlane, installed.
```
 // Script tag without SRI
<script src="https://global.localizecdn.com/localize.479.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.479.js" integrity="sha512-i2cYsm2Jag+tncmkh/i6fPWm2jD0B13gway+rwP6grlr8L6allz635lj8a3ErYsrWUDx1HTlo1I2/v/emBu0Ug==" crossorigin="anonymous"></script>
```

## Version 478 - September 18, 2023
* **[Feature]**: Allow reinitializing project keys within a single page application. You may now specify use `Localize.initialize` with different project keys within your code even if the page does not refresh.
```
 // Script tag without SRI
<script src="https://global.localizecdn.com/localize.478.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.478.js" integrity="sha512-ZTJKh33vjnd051lAy9M3bzhkdXaUoa7YljvvkaXQAyPZ8BgI38ccMgq9JMvBix2AUqasEq4S3a0O+SJo9T0cWQ==" crossorigin="anonymous"></script>
```
## Version 477 - September 8, 2023
* **[Fix]**: Allow for phrases containing zero width joiner characters.
```
 // Script tag without SRI
<script src="https://global.localizecdn.com/localize.477.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.477.js" integrity="sha512-NtU0nxRzwnDaS54Ev71Qs6PPTcAV6s72ZbdQG44o+6I1K+S+6oLsYkjkanNZpGG02bL8T/xsVUz6QaNOf0iciA==" crossorigin="anonymous"></script>
```

## Version 476 - June 30, 2023
* **[Fix]**: Ignore `Link` tags in header when detecting phrases.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.476.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.476.js" integrity="sha512-hUe5E8nDx5DBz2LkyGs+aQAt3pAj3s4CS4zrwPd/ZhoPA3VIYV5gSQsGTSwI663xkEVjgtqNqAuT/0jVWZduXw==" crossorigin="anonymous"></script>
```  

## Version 475 - June 19, 2023
* **[Feature]**: Add `translateImmediate` method for real time translations. This new feature is available on selected, advanced plans.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.475.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.475.js" integrity="sha512-XOICBgs7kZuPsWAhfe8O7MUTYiNotyIGaZf6FKAAVs3dAH16eiip1NWzG58Pwh9++lnNWaQ8QRjPQh2Vce9Ibg==" crossorigin="anonymous"></script>
```

## Version 474 - May 22, 2023
* **[Fix]**: Allow translation of meta data while using the In-Context Editor.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.474.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.474.js" integrity="sha512-/KqPiRH028feTaJMEpIdUdmtYQUDnGLnzQCY7IDfXBh/DjqFS9i2/opQ6F/gPsQWTjkaR2ZA/OHRKxQDNwOUng==" crossorigin="anonymous"></script>
```

## Version 473 - April 24, 2023
* **[Fix]**: Filter executable code from `Localize.translate` method when using variable interpolation. 
Fixes an issue where words beginning with "on" and followed by an html tag were incorrectly removed within `Localize.translate`.
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.473.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.473.js" integrity="sha512-p7sq2PQMHGvyyQ0oBPt2cI/3k6bfAD/cCV7KplwuyWcAaf43wI4EU4ivBu1q36SzZkGM+SFjXeKj9v/pBahjug==" crossorigin="anonymous"></script>
```


## Version 472 - April 10, 2023
* **[Fix]**: Added handling for languages with a four character locale which is not strictly upper case, e.g. zh-Hans. After this change a domain such
as `zh-hans.example.com` will properly switch the user's language to Chinese (Simplified).
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.472.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.472.js" integrity="sha512-QLLKS3P9UpSVpWGwrFJunDXw5FQ5xXOg0bMuHoW2IqS1PsYvocAv79WFNnV4ZSQXxMmmYi2MShseo6p9Fk35CQ==" crossorigin="anonymous"></script>
```

## Version 471 - March 13, 2023
* **[Feature]**: Added `vueSafe` boolean parameter to Localize.initialize call which instructs our library to not add support for the React virtual DOM.
Supporting React can cause compatibility issues with VueJS.

* **[Fix]**: Filter executable code from `Localize.translate` method to prevent cross site scripting attacks.

```
// Script tag without SRI
https://global.localizecdn.com/localize.471.js

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.471.js" integrity="sha512-uvZiTAPMTXs3XrgM6J0+zBcBs6TudWf8/fYYRoEPxR4PIV31KdoYW8i5MZUKsWmVKZ2lIqKRNE7iprtJy54wJg==" crossorigin="anonymous"></script>
```

## Version 470 - February 14, 2023
* **[Feature]**: Remove inline widget code to better support Content Security Policy headers without `unsafe-inline`. 

```
// Script tag without SRI
https://global.localizecdn.com/localize.470.js

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.470.js" integrity="sha512-DYkowFJZNmW3Og4+MMC3g4a3Qy9J2Y3WPYgdZToxfw7O4VkhQUIBwC0OE/VJdQ/izXciKG/6l4QQszDeTc3LbQ==" crossorigin="anonymous"></script>
```

## Version 469 - January 12, 2023
* **[Fix]**: Handle Node removed during translation. [DEV-4990]
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.469.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.469.js" integrity="sha512-k6N9HR6+fhWX20ilqOXEyNfCyIwqRXegym9UkTUWzjvgJrXTzqPvBgg2M/djP8ytsdlsiz0Zyrmgf2HrKfRBJw==" crossorigin="anonymous"></script>
```

## Version 468 - January 4, 2023
* **[Fix]**: Handle React modifications when replacing or removing child nodes in DOM. [DEV-4911]
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.468.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.468.js" integrity="sha512-fGkRLg056X6IdWOu7BZrtVLMvKTT6J9cLcJcf7Fpq6iKfnw4l2NX+TynKWN1O2MsPGeBV7oQaRyQAeEwZgw1ZQ==" crossorigin="anonymous"></script>
```

## Version 467 - December 20, 2022
* **[Fix]**: Auto-close widget. [DEV-4908]
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.467.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.467.js" integrity="sha512-mOBznnNZzf/H4nTLMldH3M8idCy0O7it/OXUV3A9JbYvq5tHpkvQ7U3d+AQB9pIJPbVBuhjmsKgE3ToaQCmkJA==" crossorigin="anonymous"></script>
```

## Version 464 - November 16, 2022
* **[Fix]**: Handle duplicate title tags in page. [DEV-4777]
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.464.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.464.js" integrity="sha512-wqeScHC9risVspWPcyuhbcHtd3SSVlq2vaBX+E8+cxqYOWHvmdzjl3O3PPLWQ0WXaX5M4BFM+q0fjML0GOpWdw==" crossorigin="anonymous"></script>
```

## Version 463 - November 8, 2022

* **[Fix]**: Handle case where title tag is missing in a page. [DEV-3934]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.463.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.463.js" integrity="sha512-eXbltVqfWF9J/6RtEce3g76U4jCXP/wgZIqdNq+PCc6f3DEn+YBxZzomO7cYDS4zorpXgO7qAF1v11839LBCtg==" crossorigin="anonymous"></script>
```

## Version 462 - October 31, 2022

* **[Fix]**: Handle edge cases related to partially modified, nested content [DEV-4009]
* **[Fix]**: Respect initialize options for autodetectLanguage [DEV-3851][DEV-4340]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.462.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.462.js" integrity="sha512-mS5dL8QV2TV+dTQY9hSvx0k/NrW079LWkuerpgmtKcMs0n+uejQvUAZZTaU3fRUxNtod0uTPYY8FYBck3Ql2JA==" crossorigin="anonymous"></script>
```

## Version 461 - July 27, 2022

 * **[Fix]**: Prefer data-var name for variables  [DEV-3901]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.461.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.461.js" integrity="sha512-L8U3KigUh7Yyka3z7g1IoWgAGUK4xgFNYGkupB8fAJxR4W6kRO8sa8ERNPQqS6n89zBu0fyIKBGuBBrNx8X01w==" crossorigin="anonymous"></script>
```

## Version 459 - June 3, 2022

 * **[Fix]**: Resolves an issue where hreflang tags were being added to blocked pages  [DEV-3645]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.459.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.459.js" integrity="sha512-T8DMcDgL3Pm/wKQWdhKxhWxvF+qRXVznBpWUpYJhPMIRtrlFFk+TtPKgs9wRSsUP8TvcyZiI0yGi5hjk3YgDjw==" crossorigin="anonymous"></script>
```

## Version 457 - February 23, 2022

 * **[Feature]**:  SEO settings added to library which allow for HREFLANG tags to be injected based on input in the Localize dashboard [DEV-3272]
 * **[Feature]**:  Localize.number() - Format a number based on locale [DEV-3333]
 * **[Feature]**:  Localize.currency() - Convert a value from one currency to another [DEV-3334]
```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.457.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.457.js" integrity="sha512-U9gqRaAgQjjeYtdaPeaZnu5932fTICNclYt5Kq5CrnG2jZXDwmSULQMRQoKuktu1XKsczbmjIfh80y6odExIOA==" crossorigin="anonymous"></script>
```

## Version 453 - February 2, 2022

 * **[Maintenance]**:  In-context editor refactor/cleanup

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.453.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.453.js" integrity="sha512-i3nj8yZtiJhNYdwrcstrqKa3ZP2+jFEGBhVstPHgtT4l9xzB0Q7wLEomNRGeI9EenlKu4mVltn3RnE7sG2gFyw==" crossorigin="anonymous"></script>
```

## Version 452 - December 3, 2021

 * **[Fix]**: Resolves an issue where the "disabled pages" setting did not work when matching pages with `#` or query strings in the URL  [DEV-3124]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.452.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.452.js" integrity="sha512-FKna3gj8yrVbUYMxZNsgZJ7WzukQLwohabsuKMV5OJm260CIhzDJTAJ3Ktp4avtS91a7We/R0ph42sx9Qp5CqQ==" crossorigin="anonymous"></script>
```

## Version 451 - October 28, 2021


 * **[Fix]**: Resolves an issue within the in-context editor that caused the original translation to display after publishing a new translation [DEV-3052]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.451.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.451.js" integrity="sha512-Jto56tvEGWRvHQdFZ8pALU4b798iecdwCPS6gnB+RZaaw7FPnvmZJCrUQcNPAGoWa6lNhyPaKbcsPIG2buDi1w==" crossorigin="anonymous"></script>
```


## Version 450 - September 24, 2021

 * **[Feature]**: New library option `allowInlineBreakTags` that, when enabled, allows a `<BR>` tag to be exist inline within phrases. By default, break tags split phrases up and this setting allows for overriding the default behavior. [DEV-2799]
 * **[Fix]**: Rendering fixes for translations edited in the in-context editor [DEV-2775]
 * **[Fix]**: Resolves edge cases that may result in translations being detected as new phrases [DEV-2852]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.450.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.450.js" integrity="sha512-+Gh3Rjg9YB+j5Pq1t5vYN1Lj2glakoYalMm5NxQnGjUBNhBmwbLq1dLrDlYa1zmvmUR/AhYsduOT4L63sCEY9A==" crossorigin="anonymous"></script>
```

## Version 449 - August 18, 2021

 * **[Fix]**: Resolve issue with the in-context editor introduced in version 448

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.449.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.449.js" integrity="sha512-7JBrRO9n7ptMEOPVBf5bxKltCnS/6D9l7y5WwQzm5jD18wDGXN7Bzu3wHc68TtcZtwHuj0hIGjz0wT5U/2MGfg==" crossorigin="anonymous"></script>
```

## Version 448 - August 16, 2021

 * **[Fix]**: Rendering fixes for SVGs in the in-context editor [DEV-2633]
 * **[Fix]**: Allow the use of `data-ignore`  [DEV-2643]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.448.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.448.js" integrity="sha512-NDzwdgsoFCcntYby7RORDl9VHrJDIR5Sze9Hicex1NAdEeSrDlnIQcWfhS0rZqZqCTOBBj1MLuLyxhGb9c+gzw==" crossorigin="anonymous"></script>
```

## Version 447 - August 10, 2021

 * **[Fix]**: Under the hood changes that improve overall compatability of the In-Context Editor across a wider variety of use cases [DEV-2688]

```
// Script tag without SRI
<script src="https://global.localizecdn.com/localize.447.js"></script>

// Script tag with SRI
<script src="https://global.localizecdn.com/localize.447.js" integrity="sha512-9B398RrAm4ysH0d7VQMwH/o3gOH40cyksQkupngd292cgSEnkt1p0HIx3N1D3nqYZmAWEi/iXGCXFgH5LeMvXQ==" crossorigin="anonymous"></script>
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
