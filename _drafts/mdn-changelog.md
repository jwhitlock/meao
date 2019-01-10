---
layout: post
title: MDN Changelog for December 2018
author: John Whitlock
---

Here's what happened in December to the
[code, data, and tools](https://github.com/mdn/)
that support
[MDN Web Docs](https://developer.mozilla.org):

- [Item 1](#item1-dec-18)
- [Item 2](#item2-dec-18)
- [Item 3](#item3-dec-18)
- [Shipped tweaks and fixes](#tweaks-dec-18)
  by merging 124 pull requests,
  including 27 pull requests
  from 26 new contributors.

Here's the plan for January:

- [Plan 1](#plan1-dec-18)
- [Plan 2](#plan2-dec-18)
- [Plan 3](#plan3-dec-18)

Done in December
===

<a name="item1-dec-18">Item 1</a>
---
Here's the first item, including lots of images.

<a name="item2-dec-18">Item 2</a>
---
The second item is also important.

<a name="item3-dec-18">Item 3</a>
---
Everyone stopped reading.

<a name="tweaks-dec-18">Shipped tweaks and fixes</a>
---
There were 124 PRs merged in December:

- [65 mdn/browser-compat-data PRs](https://github.com/mdn/browser-compat-data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [22 mozilla/kuma PRs](https://github.com/mozilla/kuma/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [20 mdn/interactive-examples PRs](https://github.com/mdn/interactive-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [4 mdn/bob PRs](https://github.com/mdn/bob/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [3 mdn/data PRs](https://github.com/mdn/data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [2 mdn/infra PRs](https://github.com/mdn/infra/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [2 mdn/learning-area PRs](https://github.com/mdn/learning-area/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [2 mdn/kumascript PRs](https://github.com/mdn/kumascript/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [1 mdn/dom-examples PR](https://github.com/mdn/dom-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [1 mdn/stumptown-experiment PR](https://github.com/mdn/stumptown-experiment/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [1 mdn/html-examples PR](https://github.com/mdn/html-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")
- [1 mdn/short-descriptions PR](https://github.com/mdn/short-descriptions/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-12-01..2018-12-31")

This includes some important changes and fixes:

- safari addstream event
  ([BCD PR 3085](https://github.com/mdn/browser-compat-data/pull/3085)),
  from
  [Xin](https://github.com/betimer).
- ff, safari has onbufferedamountlow &amp; bufferedAmountLowThreshold
  ([BCD PR 3087](https://github.com/mdn/browser-compat-data/pull/3087)),
  from
  [Jimmy Wärting](https://github.com/jimmywarting).
- Added support for new parameters to chrome_settings_overrides
  ([BCD PR 3089](https://github.com/mdn/browser-compat-data/pull/3089)),
  from
  [Irene Smith](https://github.com/irenesmith).
- &#91;Chrome&#93; Correct updateViaCache.
  ([BCD PR 3091](https://github.com/mdn/browser-compat-data/pull/3091)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Add compatibility info for optional redirect_uri URL param in identity API
  ([BCD PR 3104](https://github.com/mdn/browser-compat-data/pull/3104)),
  from
  [Martin Giger](https://github.com/freaktechnik).
- Add PayerErrors to BCD
  ([BCD PR 3118](https://github.com/mdn/browser-compat-data/pull/3118)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Add PaymentItem dictionary
  ([BCD PR 3134](https://github.com/mdn/browser-compat-data/pull/3134)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- update to gradients to add multipoint color stops
  ([BCD PR 3135](https://github.com/mdn/browser-compat-data/pull/3135)),
  from
  [Estelle Weyl](https://github.com/estelle).
- Webnavigation transitiontype update
  ([BCD PR 3137](https://github.com/mdn/browser-compat-data/pull/3137)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- add opera 57 release data
  ([BCD PR 3144](https://github.com/mdn/browser-compat-data/pull/3144)),
  from
  [Germain](https://github.com/gsouquet).
- Revert "Revert "Bug 1487982: Rename `applications` to  `browser_specific_settings`""
  ([BCD PR 3147](https://github.com/mdn/browser-compat-data/pull/3147)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- fix(css): `cursor` property - Replace `true` with known versions
  ([BCD PR 3150](https://github.com/mdn/browser-compat-data/pull/3150)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Adds getDisplayMedia() to MediaDevices
  ([BCD PR 3154](https://github.com/mdn/browser-compat-data/pull/3154)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- DocumentFragment() constructor is supported in Edge
  ([BCD PR 3155](https://github.com/mdn/browser-compat-data/pull/3155)),
  from
  [Tim Düsterhus](https://github.com/TimWolla).
- Update CanvasRenderingContext2D.resetTransform()
  ([BCD PR 3161](https://github.com/mdn/browser-compat-data/pull/3161)),
  from
  [mfluehr](https://github.com/mfluehr).
- Enhance the Instructions for npm run confluence.
  ([BCD PR 3167](https://github.com/mdn/browser-compat-data/pull/3167)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Update items that are not in Android Webview
  ([BCD PR 3170](https://github.com/mdn/browser-compat-data/pull/3170)),
  from
  [Joe Medley](https://github.com/jpmedley).
- More webview-related updates
  ([BCD PR 3172](https://github.com/mdn/browser-compat-data/pull/3172)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Fixing some missing compat data for display
  ([BCD PR 3173](https://github.com/mdn/browser-compat-data/pull/3173)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Add PluralRules interface.
  ([BCD PR 3176](https://github.com/mdn/browser-compat-data/pull/3176)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Add Proxy.revocable.
  ([BCD PR 3177](https://github.com/mdn/browser-compat-data/pull/3177)),
  from
  [Joe Medley](https://github.com/jpmedley).
- feat(css): Add the attribute selector case‑sensitive modifier (`s`)
  ([BCD PR 3179](https://github.com/mdn/browser-compat-data/pull/3179)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Add getStats() to RTC interfaces.
  ([BCD PR 3181](https://github.com/mdn/browser-compat-data/pull/3181)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Add path() support to offset-path.
  ([BCD PR 3182](https://github.com/mdn/browser-compat-data/pull/3182)),
  from
  [Joe Medley](https://github.com/jpmedley).
- &#91;Chrome&#93; Add data for Request.cache.
  ([BCD PR 3183](https://github.com/mdn/browser-compat-data/pull/3183)),
  from
  [Joe Medley](https://github.com/jpmedley).
- scroll-snap-stop is not implemented anywhere
  ([BCD PR 3187](https://github.com/mdn/browser-compat-data/pull/3187)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- &#91;Chrome&#93; Media preload attrib now defaults to metadata.
  ([BCD PR 3188](https://github.com/mdn/browser-compat-data/pull/3188)),
  from
  [Joe Medley](https://github.com/jpmedley).
- basic CSS Font API from 2014 is well supported and not experimental.
  ([BCD PR 3193](https://github.com/mdn/browser-compat-data/pull/3193)),
  from
  [Estelle Weyl](https://github.com/estelle).
- updating experimental/standard status of onbeforeinstallprompt
  ([BCD PR 3197](https://github.com/mdn/browser-compat-data/pull/3197)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Add addons-linter as a user of BCD
  ([BCD PR 3203](https://github.com/mdn/browser-compat-data/pull/3203)),
  from
  [wbamberg](https://github.com/wbamberg).
- adding note about macOS scrollbar-color
  ([BCD PR 3204](https://github.com/mdn/browser-compat-data/pull/3204)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Upgrade firefox current browser version
  ([BCD PR 3206](https://github.com/mdn/browser-compat-data/pull/3206)),
  from
  [Germain](https://github.com/gsouquet).
- Mark FileReader.readAsBinaryString as removed in IE 11
  ([BCD PR 3207](https://github.com/mdn/browser-compat-data/pull/3207)),
  from
  [Christophe Coevoet](https://github.com/stof).
- Add initial pull request template
  ([BCD PR 3208](https://github.com/mdn/browser-compat-data/pull/3208)),
  from
  [Daniel D. Beck](https://github.com/ddbeck).
- Add RTCIceCandidateStats
  ([BCD PR 3209](https://github.com/mdn/browser-compat-data/pull/3209)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- &#91;Chrome&#93; Improve CSSStyleDeclaration data.
  ([BCD PR 3210](https://github.com/mdn/browser-compat-data/pull/3210)),
  from
  [Joe Medley](https://github.com/jpmedley).
- &#91;Chrome&#93; Improve HTMLImageElement data.
  ([BCD PR 3211](https://github.com/mdn/browser-compat-data/pull/3211)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Bug 1512386: Implement case‑sensitive attribute selectors (`s`)
  ([BCD PR 3212](https://github.com/mdn/browser-compat-data/pull/3212)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- &#91;Chrome&#93; Add data for ResizeObserver.
  ([BCD PR 3213](https://github.com/mdn/browser-compat-data/pull/3213)),
  from
  [Joe Medley](https://github.com/jpmedley).
- Update RTCRtpSender.setParameters for Firefox
  ([BCD PR 3214](https://github.com/mdn/browser-compat-data/pull/3214)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- api.Node.removeChild is standard and non-deprecated
  ([BCD PR 3215](https://github.com/mdn/browser-compat-data/pull/3215)),
  from
  [Konstantin Rouda](https://github.com/Konrud).
- Mark the Clipboard API as unsupported in Edge and IE
  ([BCD PR 3216](https://github.com/mdn/browser-compat-data/pull/3216)),
  from
  [Christophe Coevoet](https://github.com/stof).
- Add RTCRtpSendParameters and RTCRtpEncodingParameters
  ([BCD PR 3217](https://github.com/mdn/browser-compat-data/pull/3217)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Update MediaStreamAudioSourceNode for mediaStream property
  ([BCD PR 3218](https://github.com/mdn/browser-compat-data/pull/3218)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Add MediaStreamAudioSourceOptions dictionary
  ([BCD PR 3219](https://github.com/mdn/browser-compat-data/pull/3219)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- fix(webext): Firefox required `applications` before version 48
  ([BCD PR 3220](https://github.com/mdn/browser-compat-data/pull/3220)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- updating FetchEvent data
  ([BCD PR 3221](https://github.com/mdn/browser-compat-data/pull/3221)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- updating createImageBitmap Firefox compat data for SVGImageElement so…
  ([BCD PR 3230](https://github.com/mdn/browser-compat-data/pull/3230)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Map.prototype&#91;@@toStringTag&#93; exists it Firefox
  ([BCD PR 3235](https://github.com/mdn/browser-compat-data/pull/3235)),
  from
  [Tom Schuster](https://github.com/evilpie).
- Bug 1169350 – Add the Accessibility Checker plugin to CKEditor
  ([Kuma PR 4989](https://github.com/mozilla/kuma/pull/4989)),
  from
  [Florian Scholz](https://github.com/Elchi3).
- bug 1505084: update the kuma_base Docker image to use Node 10.14
  ([Kuma PR 5137](https://github.com/mozilla/kuma/pull/5137)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- Bug 1503923, additional page variations for performance experiment
  ([Kuma PR 5144](https://github.com/mozilla/kuma/pull/5144)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- bug 1490727: Manage recurring payments - cancel button.
  ([Kuma PR 5146](https://github.com/mozilla/kuma/pull/5146)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727:  Added a new set of analytics for recurring payments.
  ([Kuma PR 5147](https://github.com/mozilla/kuma/pull/5147)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Force form to remove custom amount on change.
  ([Kuma PR 5148](https://github.com/mozilla/kuma/pull/5148)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Align payment error page content to the centre.
  ([Kuma PR 5149](https://github.com/mozilla/kuma/pull/5149)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- Add some validation and success info on feedback form.
  ([Kuma PR 5150](https://github.com/mozilla/kuma/pull/5150)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Remove clear field `x` from email input on IE on payments  form.
  ([Kuma PR 5151](https://github.com/mozilla/kuma/pull/5151)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- Bug 1504320, swap design tools banner for grid tools
  ([Kuma PR 5152](https://github.com/mozilla/kuma/pull/5152)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Updating submodules
  ([Kuma PR 5153](https://github.com/mozilla/kuma/pull/5153)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- Bug 1423716 - fix a failing functional test
  ([Kuma PR 5155](https://github.com/mozilla/kuma/pull/5155)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- bug 1490727: Adjust payment management UI strings
  ([Kuma PR 5156](https://github.com/mozilla/kuma/pull/5156)),
  from
  [me](https://github.com/jwhitlock).
- Updating submodules
  ([Kuma PR 5158](https://github.com/mozilla/kuma/pull/5158)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- Update submodules (for real this time)
  ([Kuma PR 5159](https://github.com/mozilla/kuma/pull/5159)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- Bug 1509357: redirect En/ and EN/ to en-US/
  ([Kuma PR 5161](https://github.com/mozilla/kuma/pull/5161)),
  from
  [David Flanagan](https://github.com/davidflanagan).
- Fix Bug 1513203, add Jest and True, and initial tests
  ([Kuma PR 5162](https://github.com/mozilla/kuma/pull/5162)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- bug 1462400: fix test_footer_language_selector test
  ([Kuma PR 5163](https://github.com/mozilla/kuma/pull/5163)),
  from
  [Ryan Johnson](https://github.com/escattone).
- bug 1462400: fix test_header_signin and test_edit_sign_in
  ([Kuma PR 5166](https://github.com/mozilla/kuma/pull/5166)),
  from
  [Ryan Johnson](https://github.com/escattone).
- bug 1169350: ckeditor with latest a11y plugins
  ([Kuma PR 5167](https://github.com/mozilla/kuma/pull/5167)),
  from
  [Ryan Johnson](https://github.com/escattone).
- update sub-modules
  ([Kuma PR 5168](https://github.com/mozilla/kuma/pull/5168)),
  from
  [Ryan Johnson](https://github.com/escattone).
- bug 1483072: update prod attachment origin
  ([Kuma PR 5169](https://github.com/mozilla/kuma/pull/5169)),
  from
  [Ryan Johnson](https://github.com/escattone).
- make the try-catch example simpler by removing the need for eval()
  ([Interactive Examples PR 1225](https://github.com/mdn/interactive-examples/pull/1225)),
  from
  [Flying-Toast](https://github.com/Flying-Toast).
- Update dependency stylelint to v9.9.0
  ([Interactive Examples PR 1243](https://github.com/mdn/interactive-examples/pull/1243)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency ajv to v6.6.1
  ([Interactive Examples PR 1246](https://github.com/mdn/interactive-examples/pull/1246)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency prettier to v1.15.3
  ([Interactive Examples PR 1247](https://github.com/mdn/interactive-examples/pull/1247)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency mdn-bob to v1.1.21
  ([Interactive Examples PR 1251](https://github.com/mdn/interactive-examples/pull/1251)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Adds @karlstolley as contributor
  ([Interactive Examples PR 1252](https://github.com/mdn/interactive-examples/pull/1252)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Adds @mamamusings as contributor
  ([Interactive Examples PR 1253](https://github.com/mdn/interactive-examples/pull/1253)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Adds @dholbert as contributor
  ([Interactive Examples PR 1254](https://github.com/mdn/interactive-examples/pull/1254)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Add @kevinsimper as contributor
  ([Interactive Examples PR 1255](https://github.com/mdn/interactive-examples/pull/1255)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Adds @romulocintra as contributor
  ([Interactive Examples PR 1256](https://github.com/mdn/interactive-examples/pull/1256)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Use foo-bar convention
  ([Interactive Examples PR 1257](https://github.com/mdn/interactive-examples/pull/1257)),
  from
  [Yahya Elharony](https://github.com/elharony).
- added conic gradient examples
  ([Interactive Examples PR 1265](https://github.com/mdn/interactive-examples/pull/1265)),
  from
  [Estelle Weyl](https://github.com/estelle).
- Add CSS Examples for scrollbar-color and scrollbar-width
  ([Interactive Examples PR 1269](https://github.com/mdn/interactive-examples/pull/1269)),
  from
  [Kenrick](https://github.com/kenrick95).
- add conic gradient to gradient page
  ([Interactive Examples PR 1272](https://github.com/mdn/interactive-examples/pull/1272)),
  from
  [Estelle Weyl](https://github.com/estelle).
- chore(deps): update dependency snyk to v1.114.0
  ([bob PR 185](https://github.com/mdn/bob/pull/185)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency semantic-release to v15.12.4
  ([bob PR 186](https://github.com/mdn/bob/pull/186)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency puppeteer to v1.11.0
  ([bob PR 187](https://github.com/mdn/bob/pull/187)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- fix(deps): update dependency semantic-release-cli to v4.0.12
  ([bob PR 188](https://github.com/mdn/bob/pull/188)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Adding two value shorthands
  ([Data PR 329](https://github.com/mdn/data/pull/329)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Fix border-bottom-color reference syntax
  ([Data PR 333](https://github.com/mdn/data/pull/333)),
  from
  [Fredrik Nicol](https://github.com/frenic).
- CloudFront: Vary CKEditor build files on t= param
  ([infra PR 166](https://github.com/mdn/infra/pull/166)),
  from
  [me](https://github.com/jwhitlock).
- Adding a lifecycle rule for mdn-elb-logs bucket
  ([infra PR 167](https://github.com/mdn/infra/pull/167)),
  from
  [Ed Lim](https://github.com/limed).
- Bug 1387454 - Add AudioContext options
  ([KumaScript PR 704](https://github.com/mdn/kumascript/pull/704)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Rename MediaTrackConstraintSet to MediaTrackConstraints
  ([KumaScript PR 1021](https://github.com/mdn/kumascript/pull/1021)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Add sign/verify examples for Web Crypto
  ([dom-examples PR 33](https://github.com/mdn/dom-examples/pull/33)),
  from
  [wbamberg](https://github.com/wbamberg).
- Bring total number of short descriptions in the repo to 30
  ([short-descriptions PR 8](https://github.com/mdn/short-descriptions/pull/8)),
  from
  [Daniel D. Beck](https://github.com/ddbeck).

27 pull requests were from first-time contributors:

- Added compatibility data from svg/attribute/paint-property
  ([PR 3074](https://github.com/mdn/browser-compat-data/pull/3074)),
  and
  fixed svg text mdn_urls, textLength IE support
  ([PR 3098](https://github.com/mdn/browser-compat-data/pull/3098)),
  to BCD from
  [Steven Kalt](https://github.com/SKalt).
- Update ParentNode.json - lastElementChild attribute
  ([BCD PR 3099](https://github.com/mdn/browser-compat-data/pull/3099)),
  from
  [Andrew Stewart Gibson](https://github.com/goofballLogic).
- Added Opera "class" support version
  ([BCD PR 3102](https://github.com/mdn/browser-compat-data/pull/3102)),
  from
  [Christian Sirolli](https://github.com/HeyITGuyFixIt).
- Add "Experimental JavaScript Features" note for `RegExp.flags`
  ([BCD PR 3142](https://github.com/mdn/browser-compat-data/pull/3142)),
  from
  [ulrichb](https://github.com/ulrichb).
- Fix typo in KeyboardEvent
  ([BCD PR 3146](https://github.com/mdn/browser-compat-data/pull/3146)),
  from
  [Philipp Spiess](https://github.com/philipp-spiess).
- display-mode is not supported by Samsung Browser
  ([BCD PR 3153](https://github.com/mdn/browser-compat-data/pull/3153)),
  from
  [Sumurai8](https://github.com/Sumurai8).
- Update desktop Edge compability data for URLSearchParams
  ([BCD PR 3162](https://github.com/mdn/browser-compat-data/pull/3162)),
  from
  [Vitaly K.](https://github.com/VitalyKrenel).
- Update nodejs flatMap support - works in v11.0.0
  ([BCD PR 3163](https://github.com/mdn/browser-compat-data/pull/3163)),
  from
  [Artur Klesun](https://github.com/klesun).
- Document.hasFocus, ChildNode.remove are not supported by Opera 12.18
  ([BCD PR 3165](https://github.com/mdn/browser-compat-data/pull/3165)),
  from
  [Abradoks](https://github.com/Abradoks).
- Lookbehind has no firefox support
  ([BCD PR 3189](https://github.com/mdn/browser-compat-data/pull/3189)),
  from
  [StefanSchoof](https://github.com/StefanSchoof).
- support for await...of
  ([BCD PR 3194](https://github.com/mdn/browser-compat-data/pull/3194)),
  from
  [Yuichi Nukiyama](https://github.com/YuichiNukiyama).
- Update animateMotion.json for basic iOS compatibility
  ([BCD PR 3222](https://github.com/mdn/browser-compat-data/pull/3222)),
  from
  [Paul Masson](https://github.com/paulmasson).
- Add compat for BigInt
  ([BCD PR 3224](https://github.com/mdn/browser-compat-data/pull/3224)),
  from
  [VFDan](https://github.com/VFDan).
- Opera still supports @keyframes
  ([BCD PR 3227](https://github.com/mdn/browser-compat-data/pull/3227)),
  from
  [Tony Ross](https://github.com/antross).
- Fix typo in preference name
  ([BCD PR 3234](https://github.com/mdn/browser-compat-data/pull/3234)),
  from
  [Josh Smith](https://github.com/joshua-s).
- Make the first Math.round example simpler
  ([Interactive Examples PR 1230](https://github.com/mdn/interactive-examples/pull/1230)),
  from
  [Kevin Simper](https://github.com/kevinsimper).
- Adding  Intl.RelativeDateFormat example
  ([Interactive Examples PR 1245](https://github.com/mdn/interactive-examples/pull/1245)),
  from
  [Romulo Cintra](https://github.com/romulocintra).
- Put prefixed sticky value before standard value
  ([Interactive Examples PR 1249](https://github.com/mdn/interactive-examples/pull/1249)),
  from
  [Daniel Holbert](https://github.com/dholbert).
- Change name to virtual person name
  ([Interactive Examples PR 1259](https://github.com/mdn/interactive-examples/pull/1259)),
  from
  [Osama Soliman](https://github.com/microsmsm).
- &#91;Math.trunc&#93; - Negative numbers
  ([Interactive Examples PR 1264](https://github.com/mdn/interactive-examples/pull/1264)),
  from
  [Hugo Nogueira](https://github.com/Marabyte).
- Spelling correction
  ([Interactive Examples PR 1274](https://github.com/mdn/interactive-examples/pull/1274)),
  from
  [Dale Harris](https://github.com/Da13Harris).
- scrollbar-width does not take lengths.
  ([Data PR 334](https://github.com/mdn/data/pull/334)),
  from
  [Emilio Cobos Álvarez](https://github.com/emilio).
- &lt;html&gt; element must have a lang attribute
  ([learning-area PR 113](https://github.com/mdn/learning-area/pull/113)),
  from
  [Alexey Filin](https://github.com/alexphilin).
- &lt;input&gt; element miss a id attribute
  ([learning-area PR 114](https://github.com/mdn/learning-area/pull/114)),
  from
  [lfzyx](https://github.com/lfzyx).
- add travis-based markdown linting and spell checking
  ([PR 6](https://github.com/mdn/stumptown-experiment/pull/6)),
  from
  [Ryan Johnson](https://github.com/escattone)
  (first contribution to stumptown-experiment).
- Removes bulk preloading all existing fonts
  ([html-examples PR 3](https://github.com/mdn/html-examples/pull/3)),
  from
  [Vadim Makeev](https://github.com/pepelsbey).


Planned for January
===
Intro

<a name="plan1-dec-18">Plan 1</a>
---
Main effort

<a name="plan2-dec-18">Plan 2</a>
---
Second effort

<a name="plan3-dec-18">Plan 3</a>
---
Thing we promised last month

