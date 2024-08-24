Below is a list of browser bugs I came across during my web-development-related projects. Some of these I reported, others had already been reported.

## Blink (Chromium)

| Bug # | Description | Status | Reported by me |
| ---:|:--- |:--- |:--- |
| [408528](https://bugs.chromium.org/p/chromium/issues/detail?id=408528) | css gradient hard stops drawn with aliasing | Unresolved | No, but additional info provided |
| [1229700](https://bugs.chromium.org/p/chromium/issues/detail?id=1229700) | Mask-image on element with backdrop-filter breaks when parent has overflow:hidden and border-radius set | Unresolved | No, but additional info provided |


## Gecko (Firefox)

| Bug # | Description | Status | Reported by me |
| --- | --- | --- | --- |
| [1860310](https://bugzilla.mozilla.org/show_bug.cgi?id=1860310) | CSS gradients not anti-aliased | Unresolved | Yes |
| [1860175](https://bugzilla.mozilla.org/show_bug.cgi?id=1860175) | backdrop-filter not applied if element has transform and parent has border-radius and non-default overflow value | Resolved | Yes |
| [1872508](https://bugzilla.mozilla.org/show_bug.cgi?id=1872508) | `canvasContext.drawImage` fails to draw `<video>` element for most codecs | Marked as duplicate of [1526207](https://bugzilla.mozilla.org/show_bug.cgi?id=1526207) | Yes |
| [1526207](https://bugzilla.mozilla.org/show_bug.cgi?id=1526207) | Calling `drawImage()` fails when drawing a video on android | Unresolved | No, but additional info provided |


## WebKit (Safari, any iOS/iPadOS browsers)

| Bug # | Description | Status | Reported by me |
| --- | --- | --- | --- |
| [104169](https://bugs.webkit.org/show_bug.cgi?id=104169) | Data URI SVG Fills/Filters | Unresolved | No |
| [23113](https://bugs.webkit.org/show_bug.cgi?id=23113) | Layer content inside HTML in SVG foreignObject renders in the wrong place | Unresolved | No |

plus a multitude of various SVG-specific bugs, which I hadn't had the nerve to report yet.

## WebKitGTK (Gnome Web)

| Bug # | Description | Status | Reported by me |
| --- | --- | --- | --- |
| [275819](https://bugs.webkit.org/show_bug.cgi?id=275819) | [GTK] `backdrop-filter` is applied incorrectly when element has sibling | Unresolved | Yes |

plus various other WebKitGTK-specific bugs which I haven't got round to reporting (yet), and maybe never will. WebKitGTK is so buggy (it is WebKit-based, which is bad enough, and then adds some bugs on top) and has such a small market share that it's almost not worth one's time to create reports (which takes time to do well).
