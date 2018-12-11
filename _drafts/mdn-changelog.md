---
layout: post
title: MDN Changelog for November 2018
author: John Whitlock
---

Here's what happened in November to the
[code, data, and tools](https://github.com/mdn/)
that support
[MDN Web Docs](https://developer.mozilla.org):

- [Item 1](#item1-nov-18)
- [Item 2](#item2-nov-18)
- [Item 3](#item3-nov-18)
- [Shipped tweaks and fixes](#tweaks-nov-18)
  by merging 248 pull requests,
  including 35 pull requests
  from 30 new contributors.

Here's the plan for December:

- [Plan 1](#plan1-nov-18)
- [Plan 2](#plan2-nov-18)
- [Plan 3](#plan3-nov-18)

Done in November
===

<a name="item1-nov-18">Monthly payments ship</a>
---
Here's the first item, including lots of images.

<a name="item2-nov-18">Item 2</a>
---
The second item is also important.

<a name="item3-nov-18">Item 3</a>
---
Everyone stopped reading.

<a name="tweaks-nov-18">Shipped tweaks and fixes</a>
---
There were 248 PRs merged in November:

- [74 mozilla/kuma PRs](https://github.com/mozilla/kuma/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [59 mdn/browser-compat-data PRs](https://github.com/mdn/browser-compat-data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [34 mdn/kumascript PRs](https://github.com/mdn/kumascript/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [21 mdn/interactive-examples PRs](https://github.com/mdn/interactive-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [19 mdn/infra PRs](https://github.com/mdn/infra/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [12 mdn/bob PRs](https://github.com/mdn/bob/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [11 mdn/data PRs](https://github.com/mdn/data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [3 mdn/dom-examples PRs](https://github.com/mdn/dom-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [2 mdn/django-locallibrary-tutorial PRs](https://github.com/mdn/django-locallibrary-tutorial/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [2 mdn/web-speech-api PRs](https://github.com/mdn/web-speech-api/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [2 mdn/stumptown-experiment PRs](https://github.com/mdn/stumptown-experiment/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [2 mdn/short-descriptions PRs](https://github.com/mdn/short-descriptions/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/fetch-examples PR](https://github.com/mdn/fetch-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/web-components-examples PR](https://github.com/mdn/web-components-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/learning-area PR](https://github.com/mdn/learning-area/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/simple-web-worker PR](https://github.com/mdn/simple-web-worker/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/crossbrowser-testing-lab PR](https://github.com/mdn/crossbrowser-testing-lab/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/css-examples PR](https://github.com/mdn/css-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")
- [1 mdn/imsc PR](https://github.com/mdn/imsc/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-11-01..2018-11-30")

This includes some important changes and fixes:

### Payments
- bug 1490727: Basic recurring payments view
  ([Kuma PR 5061](https://github.com/mozilla/kuma/pull/5061)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- Static pages for testing layout perf
  ([Kuma PR 5062](https://github.com/mozilla/kuma/pull/5062)),
  from
  [tkadlec](https://github.com/tkadlec).
- bug 1490727: Anonymize user.stripe_customer_id
  ([Kuma PR 5068](https://github.com/mozilla/kuma/pull/5068)),
  from
  [me](https://github.com/jwhitlock).
- bug 1490727: implement recurring payment designs
  ([Kuma PR 5072](https://github.com/mozilla/kuma/pull/5072)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Recurring payments thank you page styling.
  ([Kuma PR 5073](https://github.com/mozilla/kuma/pull/5073)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Add new page for payment terms, for now just empty template
  ([Kuma PR 5075](https://github.com/mozilla/kuma/pull/5075)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Recurring payments user registration styling
  ([Kuma PR 5080](https://github.com/mozilla/kuma/pull/5080)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: add new template for recurring payment thank you email
  ([Kuma PR 5081](https://github.com/mozilla/kuma/pull/5081)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Include confirmation checkbox for recurring payments.
  ([Kuma PR 5082](https://github.com/mozilla/kuma/pull/5082)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Fix payments nits
  ([Kuma PR 5084](https://github.com/mozilla/kuma/pull/5084)),
  from
  [me](https://github.com/jwhitlock).
- bug 1490727: Recurrent payment force GitHub redirect
  ([Kuma PR 5092](https://github.com/mozilla/kuma/pull/5092)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Add legal copy for payment terms page.
  ([Kuma PR 5094](https://github.com/mozilla/kuma/pull/5094)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: include recurring payments on banner
  ([Kuma PR 5101](https://github.com/mozilla/kuma/pull/5101)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Update information about subscription cancellation
  ([Kuma PR 5102](https://github.com/mozilla/kuma/pull/5102)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Fixed redirect bug in payments error page
  ([Kuma PR 5104](https://github.com/mozilla/kuma/pull/5104)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Recurring payment analytics implementation
  ([Kuma PR 5105](https://github.com/mozilla/kuma/pull/5105)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: add four new FAQ for monthly payments
  ([Kuma PR 5106](https://github.com/mozilla/kuma/pull/5106)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Fix for multiple subscriptions issue
  ([Kuma PR 5110](https://github.com/mozilla/kuma/pull/5110)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Changed to pre-fill payment name only from MDN user fullname field
  ([Kuma PR 5112](https://github.com/mozilla/kuma/pull/5112)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Update recurring payment amount brackets.
  ([Kuma PR 5115](https://github.com/mozilla/kuma/pull/5115)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Copy updates
  ([Kuma PR 5116](https://github.com/mozilla/kuma/pull/5116)),
  from
  [me](https://github.com/jwhitlock).
- bug 1490727: Round floating point amounts to 2 decimal places
  ([Kuma PR 5118](https://github.com/mozilla/kuma/pull/5118)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Change text on banner
  ([Kuma PR 5121](https://github.com/mozilla/kuma/pull/5121)),
  from
  [me](https://github.com/jwhitlock).
- bug 1490727: Fix issue with pre-filling fullname in recurring payment form
  ([Kuma PR 5123](https://github.com/mozilla/kuma/pull/5123)),
  from
  [Michal Macioszczyk](https://github.com/michal-macioszczyk).
- bug 1490727: Fix validation for first name input, adjust custom amount  input validation.
  ([Kuma PR 5125](https://github.com/mozilla/kuma/pull/5125)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- bug 1490727: Prevent recurring payment events being fired if cookies are  disabled.
  ([Kuma PR 5129](https://github.com/mozilla/kuma/pull/5129)),
  from
  [Josh Jarvis](https://github.com/joshJarr).
- Dont send analytics if localstorage is disabled, send a default label if  there is no user.
  ([Kuma PR 5130](https://github.com/mozilla/kuma/pull/5130)),
  from
  [Josh Jarvis](https://github.com/joshJarr).

### Performance

- bug 1504246: Manually inline a set of examples for testing in production
  ([Kuma PR 5019](https://github.com/mozilla/kuma/pull/5019)),
  from
  [James Hobin](https://github.com/hobinjk).
- bug 1503923: Updating paths for unused CSS test
  ([Kuma PR 5070](https://github.com/mozilla/kuma/pull/5070)),
  from
  [tkadlec](https://github.com/tkadlec).
- Add static test of inlined example plus unused css
  ([Kuma PR 5098](https://github.com/mozilla/kuma/pull/5098)),
  from
  [James Hobin](https://github.com/hobinjk).
- Revert "bug 1504246: Manually inline a set of examples for testing in…
  ([Kuma PR 5099](https://github.com/mozilla/kuma/pull/5099)),
  from
  [James Hobin](https://github.com/hobinjk).
- bug 1503923: Additional page variations for performance experiments
  ([Kuma PR 5132](https://github.com/mozilla/kuma/pull/5132)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Inline missing interactive example scripts and styles
  ([Kuma PR 5134](https://github.com/mozilla/kuma/pull/5134)),
  from
  [James Hobin](https://github.com/hobinjk).

### SVG

- Bug 1451261, complete change to svg icon system, remove FontAwesome lib
  ([Kuma PR 5058](https://github.com/mozilla/kuma/pull/5058)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Fix Bug 1505486, reduce top margin for inline secureContext icon
  ([Kuma PR 5093](https://github.com/mozilla/kuma/pull/5093)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Bug 1496482, fix horizontal scrolling on mobile viewwports, landing page
  ([Kuma PR 5122](https://github.com/mozilla/kuma/pull/5122)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).

### Accessibility

- Bug 1493499, add aria roles to notes/warning boxes inside ckeditor
  ([Kuma PR 5069](https://github.com/mozilla/kuma/pull/5069)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).

### CSP

- bug 9489151: Set Sentry environment
  ([Kuma PR 5066](https://github.com/mozilla/kuma/pull/5066)),
  from
  [me](https://github.com/jwhitlock).

### Python 3
- bug 1467518: Migration from Python 2 to Python2/3
  ([Kuma PR 5071](https://github.com/mozilla/kuma/pull/5071)),
  from
  [Anthony Maton](https://github.com/MatonAnthony).
- bug 1467520: bug 1467532: Resolve RemovedInDjango20Warnings
  ([Kuma PR 5089](https://github.com/mozilla/kuma/pull/5089)),
  from
  [Anthony Maton](https://github.com/MatonAnthony).
- bug 1508268: Do not load queryset before paginate
  ([Kuma PR 5119](https://github.com/mozilla/kuma/pull/5119)),
  from
  [me](https://github.com/jwhitlock).

### ExE-Boss and random
- Bug 1488884: Miscellaneous sidebar fixes
  ([Kuma PR 5036](https://github.com/mozilla/kuma/pull/5036)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Bug 1492018: Prefer `.blockIndicator` for styling Note and Warning boxes
  ([Kuma PR 5079](https://github.com/mozilla/kuma/pull/5079)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- (fix) - Bug 1504238, interactive examples and content area has gotten narrower
  ([Kuma PR 5091](https://github.com/mozilla/kuma/pull/5091)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Fix Bug 1506591, reduce font size of sidebar entries and crumbs
  ([Kuma PR 5095](https://github.com/mozilla/kuma/pull/5095)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Miscellaneous Quicklinks sidebar fixes
  ([Kuma PR 5131](https://github.com/mozilla/kuma/pull/5131)),
  from
  [ExE Boss](https://github.com/ExE-Boss).

### BCD
- Bug 1438889, switch to text labels and icons for BCD table headers
  ([Kuma PR 5117](https://github.com/mozilla/kuma/pull/5117)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Bug 1480106: Fix mobile BCD table support background and name overflow
  ([Kuma PR 5034](https://github.com/mozilla/kuma/pull/5034)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Bug 1501282, add BCD survey
  ([Kuma PR 5133](https://github.com/mozilla/kuma/pull/5133)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).

### Functional Tests

- bug 1462400: Improve functional tests
  ([Kuma PR 5143](https://github.com/mozilla/kuma/pull/5143)),
  from
  [Ryan Johnson](https://github.com/escattone).

### Bucket

- Bug 1425874: Make &lt;marquee&gt; construct HTMLMarqueeElement
  ([BCD PR 3088](https://github.com/mdn/browser-compat-data/pull/3088)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Bug 1503019: Remove Shadow DOM and Custom Elements prefs
  ([BCD PR 3094](https://github.com/mdn/browser-compat-data/pull/3094)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- updating Firefox compat data for Window.event
  ([BCD PR 3097](https://github.com/mdn/browser-compat-data/pull/3097)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- adding data for screenLeft and screenTop
  ([BCD PR 3106](https://github.com/mdn/browser-compat-data/pull/3106)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- updating buildID compat data
  ([BCD PR 3110](https://github.com/mdn/browser-compat-data/pull/3110)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- updating window.sidebar and adding window.external
  ([BCD PR 3111](https://github.com/mdn/browser-compat-data/pull/3111)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- adding data point about only allowing one window.open() call per event
  ([BCD PR 3112](https://github.com/mdn/browser-compat-data/pull/3112)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- adding data about getAllResponseHeaders() returning all lower case he…
  ([BCD PR 3114](https://github.com/mdn/browser-compat-data/pull/3114)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- updating setSinkId compat data
  ([BCD PR 3119](https://github.com/mdn/browser-compat-data/pull/3119)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- fix(css): Correct Firefox custom properties compatibility data
  ([BCD PR 3121](https://github.com/mdn/browser-compat-data/pull/3121)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Revert "Bug 1487982: Rename `applications` to `browser_specific_settings`"
  ([BCD PR 3122](https://github.com/mdn/browser-compat-data/pull/3122)),
  from
  [Irene Smith](https://github.com/irenesmith).
- Add data for well-formed JSON.stringify
  ([BCD PR 3124](https://github.com/mdn/browser-compat-data/pull/3124)),
  from
  [Florian Scholz](https://github.com/Elchi3).
- Add Firefox versions to isPrototypeOf and propertyIsEnumerable
  ([BCD PR 3125](https://github.com/mdn/browser-compat-data/pull/3125)),
  from
  [Florian Scholz](https://github.com/Elchi3).
- Adding data for missing border-radius logical mappings.
  ([BCD PR 3128](https://github.com/mdn/browser-compat-data/pull/3128)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- updating Fx support data for ServiceWorkerContainer.startMessages
  ([BCD PR 3129](https://github.com/mdn/browser-compat-data/pull/3129)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- making webNavigation transitionType compat data clearer and more deta…
  ([BCD PR 3132](https://github.com/mdn/browser-compat-data/pull/3132)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Issue #2041: Add writing release notes to the publishing procedures
  ([BCD PR 3158](https://github.com/mdn/browser-compat-data/pull/3158)),
  from
  [Florian Scholz](https://github.com/Elchi3).
- pt-BR translations for HTMLSidebar macro
  ([KumaScript PR 673](https://github.com/mdn/kumascript/pull/673)),
  from
  [Giorgio](https://github.com/GPrimola).
- pt-BR translations for JsSidebar macro
  ([KumaScript PR 674](https://github.com/mdn/kumascript/pull/674)),
  from
  [Giorgio](https://github.com/GPrimola).
- Added WAI-ARIA Authoring Practices
  ([KumaScript PR 793](https://github.com/mdn/kumascript/pull/793)),
  from
  [Estelle Weyl](https://github.com/estelle).
- adding Media Queries Level 5 to SpecData
  ([KumaScript PR 795](https://github.com/mdn/kumascript/pull/795)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Add trailing slashes to Media Capabilities, XMLHttpRequest, and  Compatibility spec URLs
  ([KumaScript PR 878](https://github.com/mdn/kumascript/pull/878)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Fix SpecData.json DeviceOrientation URL
  ([KumaScript PR 899](https://github.com/mdn/kumascript/pull/899)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Fix SpecData.json Input Events Level 2 URL
  ([KumaScript PR 900](https://github.com/mdn/kumascript/pull/900)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Fix SpecData.json Static Range URL
  ([KumaScript PR 901](https://github.com/mdn/kumascript/pull/901)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Drop redundant SpecData.json 'Web Background Sync'
  ([KumaScript PR 903](https://github.com/mdn/kumascript/pull/903)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Add CSS Scroll Anchoring to SpecData
  ([KumaScript PR 932](https://github.com/mdn/kumascript/pull/932)),
  from
  [Kagami Sascha Rosylight](https://github.com/saschanaz).
- Updating device orientation event specification
  ([KumaScript PR 936](https://github.com/mdn/kumascript/pull/936)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- fix(macros.CSSRef): Add proper support for combinators
  ([KumaScript PR 942](https://github.com/mdn/kumascript/pull/942)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Update SpecData.json CSP: Embedded Enforcement URL
  ([KumaScript PR 946](https://github.com/mdn/kumascript/pull/946)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Update SpecData XPath 2.0 URL
  ([KumaScript PR 950](https://github.com/mdn/kumascript/pull/950)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Update SpecData CSS Logical Properties URL
  ([KumaScript PR 951](https://github.com/mdn/kumascript/pull/951)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Bug 1509430: Use JSDoc instead of comments for the built‑in library
  ([KumaScript PR 959](https://github.com/mdn/kumascript/pull/959)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- GroupData: Update Fullscreen API to match current spec
  ([KumaScript PR 962](https://github.com/mdn/kumascript/pull/962)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- bug 1483072: remove Jenkins code related to MozMEAO
  ([KumaScript PR 970](https://github.com/mdn/kumascript/pull/970)),
  from
  [Ryan Johnson](https://github.com/escattone).
- moving the accessiblity inspector to be a core tool
  ([KumaScript PR 973](https://github.com/mdn/kumascript/pull/973)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- Browser extensions sidebar menu update…
  ([KumaScript PR 976](https://github.com/mdn/kumascript/pull/976)),
  from
  [rebloor](https://github.com/rebloor).
- CSS Scrollbars is at FPWD
  ([KumaScript PR 978](https://github.com/mdn/kumascript/pull/978)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Display is now a CR
  ([KumaScript PR 979](https://github.com/mdn/kumascript/pull/979)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Bug 1451261, add class to macros for use in custom styling
  ([KumaScript PR 981](https://github.com/mdn/kumascript/pull/981)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Add trailing slash to Keyboard Lock URL
  ([KumaScript PR 982](https://github.com/mdn/kumascript/pull/982)),
  from
  [Michael[tm] Smith](https://github.com/sideshowbarker).
- Fix name of the overview page for Background Tasks
  ([KumaScript PR 991](https://github.com/mdn/kumascript/pull/991)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Add Payment Method Identifiers spec to SpecData.json
  ([KumaScript PR 995](https://github.com/mdn/kumascript/pull/995)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Bug 1438889, change bcd head icons to text labels
  ([KumaScript PR 997](https://github.com/mdn/kumascript/pull/997)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Add Media Playback Quality specification
  ([KumaScript PR 1007](https://github.com/mdn/kumascript/pull/1007)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- Add Screen Capture API (Q4S3)
  ([KumaScript PR 1011](https://github.com/mdn/kumascript/pull/1011)),
  from
  [Eric Shepherd](https://github.com/a2sheppy).
- fix(gitignore): Ignore `kumascript.log` and other log files
  ([KumaScript PR 1014](https://github.com/mdn/kumascript/pull/1014)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Update dependency stylelint to v9.7.1
  ([Interactive Examples PR 1208](https://github.com/mdn/interactive-examples/pull/1208)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- rename offset properties
  ([Interactive Examples PR 1209](https://github.com/mdn/interactive-examples/pull/1209)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Update image and multimedia examples
  ([Interactive Examples PR 1216](https://github.com/mdn/interactive-examples/pull/1216)),
  from
  [wbamberg](https://github.com/wbamberg).
- Fix logical properties
  ([Interactive Examples PR 1217](https://github.com/mdn/interactive-examples/pull/1217)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update inline text semantics examples
  ([Interactive Examples PR 1218](https://github.com/mdn/interactive-examples/pull/1218)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update input examples
  ([Interactive Examples PR 1219](https://github.com/mdn/interactive-examples/pull/1219)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update interactive elements examples
  ([Interactive Examples PR 1221](https://github.com/mdn/interactive-examples/pull/1221)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update table content examples
  ([Interactive Examples PR 1222](https://github.com/mdn/interactive-examples/pull/1222)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update text content examples
  ([Interactive Examples PR 1223](https://github.com/mdn/interactive-examples/pull/1223)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update global attributes
  ([Interactive Examples PR 1224](https://github.com/mdn/interactive-examples/pull/1224)),
  from
  [wbamberg](https://github.com/wbamberg).
- Update dependency ajv to v6.5.5
  ([Interactive Examples PR 1226](https://github.com/mdn/interactive-examples/pull/1226)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency prettier to v1.15.1
  ([Interactive Examples PR 1227](https://github.com/mdn/interactive-examples/pull/1227)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- fix issues with the Jenkins build step
  ([Interactive Examples PR 1229](https://github.com/mdn/interactive-examples/pull/1229)),
  from
  [Ryan Johnson](https://github.com/escattone).
- remove Jenkinsfile code related to MozMEAO
  ([Interactive Examples PR 1231](https://github.com/mdn/interactive-examples/pull/1231)),
  from
  [Ryan Johnson](https://github.com/escattone).
- Update dependency stylelint to v9.8.0
  ([Interactive Examples PR 1232](https://github.com/mdn/interactive-examples/pull/1232)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency eslint to v5.9.0
  ([Interactive Examples PR 1233](https://github.com/mdn/interactive-examples/pull/1233)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency prettier to v1.15.2
  ([Interactive Examples PR 1234](https://github.com/mdn/interactive-examples/pull/1234)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency npm-run-all to v4.1.5
  ([Interactive Examples PR 1239](https://github.com/mdn/interactive-examples/pull/1239)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- Update dependency mdn-bob to v1.1.20
  ([Interactive Examples PR 1241](https://github.com/mdn/interactive-examples/pull/1241)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- bug 948151: Use Sentry CSP reporter
  ([infra PR 139](https://github.com/mdn/infra/pull/139)),
  from
  [me](https://github.com/jwhitlock).
- cleanup after cutover from MozMEAO services
  ([infra PR 140](https://github.com/mdn/infra/pull/140)),
  from
  [Ryan Johnson](https://github.com/escattone).
- update Terraform to reflect S3 bucket changes
  ([infra PR 142](https://github.com/mdn/infra/pull/142)),
  from
  [Ryan Johnson](https://github.com/escattone).
- Add cnames to reflect changes that is currently in cloudfront
  ([infra PR 143](https://github.com/mdn/infra/pull/143)),
  from
  [Ed Lim](https://github.com/limed).
- Fixing some issues with s3
  ([infra PR 145](https://github.com/mdn/infra/pull/145)),
  from
  [Ed Lim](https://github.com/limed).
- bug 1490727: Add STRIPE_PRODUCT_ID
  ([infra PR 146](https://github.com/mdn/infra/pull/146)),
  from
  [me](https://github.com/jwhitlock).
- Update interactive-examples aliases
  ([infra PR 147](https://github.com/mdn/infra/pull/147)),
  from
  [Ed Lim](https://github.com/limed).
- removed bin directory and its unused contents
  ([infra PR 148](https://github.com/mdn/infra/pull/148)),
  from
  [Ryan Johnson](https://github.com/escattone).
- Rename cluster in scripts, this doesn't affect running clusters its mostly  for script paths
  ([infra PR 149](https://github.com/mdn/infra/pull/149)),
  from
  [Ed Lim](https://github.com/limed).
- cleanup top-level k8s folder
  ([infra PR 150](https://github.com/mdn/infra/pull/150)),
  from
  [Ryan Johnson](https://github.com/escattone).
- clean-up EFS and RDS backup tools/utils
  ([infra PR 151](https://github.com/mdn/infra/pull/151)),
  from
  [Ryan Johnson](https://github.com/escattone).
- more infra cleanup
  ([infra PR 152](https://github.com/mdn/infra/pull/152)),
  from
  [Ryan Johnson](https://github.com/escattone).
- bug 948151: Enforce CSP in staging
  ([infra PR 157](https://github.com/mdn/infra/pull/157)),
  from
  [me](https://github.com/jwhitlock).
- PR for additional metrics
  ([infra PR 159](https://github.com/mdn/infra/pull/159)),
  from
  [Ed Lim](https://github.com/limed).
- parse_log: Update docs for MozIT clusters
  ([infra PR 160](https://github.com/mdn/infra/pull/160)),
  from
  [me](https://github.com/jwhitlock).
- add support for percona toolkit, specifically a pod that runs pt-kill  continuously
  ([infra PR 161](https://github.com/mdn/infra/pull/161)),
  from
  [Dave Parfitt](https://github.com/metadave).
- Fix IAM permission to inlcude account id
  ([infra PR 162](https://github.com/mdn/infra/pull/162)),
  from
  [Ed Lim](https://github.com/limed).
- bug 1490727: Add a monthly payments ID for prod
  ([infra PR 163](https://github.com/mdn/infra/pull/163)),
  from
  [me](https://github.com/jwhitlock).
- misc tweaks to percona toolkit
  ([infra PR 164](https://github.com/mdn/infra/pull/164)),
  from
  [Dave Parfitt](https://github.com/metadave).
- chore(deps): update dependency semantic-release to v15.12.2
  ([bob PR 168](https://github.com/mdn/bob/pull/168)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency snyk to v1.110.2
  ([bob PR 169](https://github.com/mdn/bob/pull/169)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency husky to v1.2.0
  ([bob PR 173](https://github.com/mdn/bob/pull/173)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency puppeteer to v1.10.0
  ([bob PR 174](https://github.com/mdn/bob/pull/174)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency jest-puppeteer to v3.5.1
  ([bob PR 176](https://github.com/mdn/bob/pull/176)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- fix(deps): update dependency fs-extra to v7.0.1
  ([bob PR 177](https://github.com/mdn/bob/pull/177)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- fix(deps): update dependency cosmiconfig to v5.0.7
  ([bob PR 178](https://github.com/mdn/bob/pull/178)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- fix(deps): update dependency semantic-release-cli to v4.0.11
  ([bob PR 179](https://github.com/mdn/bob/pull/179)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency marked to v0.5.2
  ([bob PR 180](https://github.com/mdn/bob/pull/180)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency npm-run-all to v4.1.5
  ([bob PR 181](https://github.com/mdn/bob/pull/181)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency jest-puppeteer to v3.5.2
  ([bob PR 182](https://github.com/mdn/bob/pull/182)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- chore(deps): update dependency commitizen to v3.0.5
  ([bob PR 183](https://github.com/mdn/bob/pull/183)),
  from
  [renovate[bot]](https://github.com/renovate[bot]).
- feat(css): Add &lt;complex-selector&gt; syntax
  ([Data PR 287](https://github.com/mdn/data/pull/287)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Adding inset property
  ([Data PR 319](https://github.com/mdn/data/pull/319)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Scroll snap data
  ([Data PR 321](https://github.com/mdn/data/pull/321)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- adding scrollbar-width
  ([Data PR 322](https://github.com/mdn/data/pull/322)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- Moving box-align properties out of the flexbox group
  ([Data PR 323](https://github.com/mdn/data/pull/323)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- renaming :matches to :is
  ([Data PR 324](https://github.com/mdn/data/pull/324)),
  from
  [Chris Mills](https://github.com/chrisdavidmills).
- refactor(css): Update combinator URLs
  ([Data PR 325](https://github.com/mdn/data/pull/325)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- feat(css): Add the `env(…)` function syntax
  ([Data PR 326](https://github.com/mdn/data/pull/326)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- Adding border-radius logical properties
  ([Data PR 327](https://github.com/mdn/data/pull/327)),
  from
  [Rachel Andrew](https://github.com/rachelandrew).
- feat(css): Add the `:where(…)` selector
  ([Data PR 328](https://github.com/mdn/data/pull/328)),
  from
  [ExE Boss](https://github.com/ExE-Boss).
- All changes to update to current version of of Django 2.1.3
  ([django-locallibrary-tutorial PR 32](https://github.com/mdn/django-locallibrary-tutorial/pull/32)),
  from
  [Hamish Willee](https://github.com/hamishwillee).
- Lint short description text
  ([short-descriptions PR 4](https://github.com/mdn/short-descriptions/pull/4)),
  from
  [Daniel D. Beck](https://github.com/ddbeck).
- Add initial JSON entries
  ([short-descriptions PR 6](https://github.com/mdn/short-descriptions/pull/6)),
  from
  [Daniel D. Beck](https://github.com/ddbeck).
- Address warnings in console for imscjs-demo
  ([imsc PR 5](https://github.com/mdn/imsc/pull/5)),
  from
  [Pierre-Anthony Lemieux](https://github.com/palemieux).

35 pull requests were from first-time contributors:

- Support sticky table of contents on Safari
  ([Kuma PR 5113](https://github.com/mozilla/kuma/pull/5113)),
  from
  [Anthony Ricaud](https://github.com/rik).
- Upgrade clean-css to version 4.x
  ([PR 5135](https://github.com/mozilla/kuma/pull/5135)),
  and
  Stop adding the SEO root title to all document titles
  ([PR 5142](https://github.com/mozilla/kuma/pull/5142)),
  to Kuma from
  [David Flanagan](https://github.com/davidflanagan).
- Add `intrinsicsize` to HTML Media elements (`img`, `video`)
  ([PR 2979](https://github.com/mdn/browser-compat-data/pull/2979)),
  from
  [ZaneHannanAU](https://github.com/ZaneHannanAU)
  (first contribution to BCD).
- Update browser compatibility for rest properties in objects
  ([BCD PR 3038](https://github.com/mdn/browser-compat-data/pull/3038)),
  from
  [FichteFoll](https://github.com/FichteFoll).
- Update ``insertRule`` optional ``index`` compatibility for IE and FF
  ([BCD PR 3039](https://github.com/mdn/browser-compat-data/pull/3039)),
  from
  [Tim](https://github.com/timothympace).
- Add compatibility for ``FullScreen`` API on IE11
  ([BCD PR 3040](https://github.com/mdn/browser-compat-data/pull/3040)),
  from
  [CntChen](https://github.com/CntChen).
- Fix tag escaping in Edge note for ``FileSystem`` API
  ([BCD PR 3043](https://github.com/mdn/browser-compat-data/pull/3043)),
  from
  [Ryusei YAMAGUCHI](https://github.com/mandel59).
- Add `object-fit` and `object-position` Safari Support Details
  ([BCD PR 3045](https://github.com/mdn/browser-compat-data/pull/3045)),
  from
  [Holt Johnson](https://github.com/holtjohnson).
- Add support data for the `signal` feature from the `AbortController` API
  ([PR 3048](https://github.com/mdn/browser-compat-data/pull/3048)),
  from
  [Konstantin Rouda](https://github.com/Konrud)
  (first contribution to BCD).
- Update Firefox compatibility for ``Window.event``
  ([BCD PR 3057](https://github.com/mdn/browser-compat-data/pull/3057)),
  from
  [Matthieu Riegler](https://github.com/kyro38).
- Update `aspect-ratio` for Safari on iOS
  ([BCD PR 3066](https://github.com/mdn/browser-compat-data/pull/3066)),
  from
  [Eric Celeste](https://github.com/efc).
- Add and rename image directives of Feature Policy
  ([BCD PR 3095](https://github.com/mdn/browser-compat-data/pull/3095)),
  from
  [Jason Chase](https://github.com/jpchase).
- Add support for `<meter>` in iOS Safari 10.3
  ([BCD PR 3109](https://github.com/mdn/browser-compat-data/pull/3109)),
  from
  [Sven Wolfermann](https://github.com/maddesigns).
- Update "Tracking Preference Expression (DNT)" Editor's draft URL
  ([KumaScript PR 805](https://github.com/mdn/kumascript/pull/805)),
  from
  [Vivien Lacourba](https://github.com/vivienlacourba).
- Change WebDriver to Living specification
  ([PR 930](https://github.com/mdn/kumascript/pull/930)),
  from
  [Andreas Tolfsen](https://github.com/andreastt)
  (first contribution to KumaScript).
- Add Spanish support to `Glossary` macro
  ([KumaScript PR 968](https://github.com/mdn/kumascript/pull/968)),
  from
  [Joaquín Serna](https://github.com/BubuAnabelas).
- Update French string in `SeeCompatTable`
  ([KumaScript PR 975](https://github.com/mdn/kumascript/pull/975)),
  from
  [lp177](https://github.com/lp177).
- Convert `<audio>` example to valid and more semantic HTML
  ([PR 1236](https://github.com/mdn/interactive-examples/pull/1236)),
  from
  [Karl Stolley](https://github.com/karlstolley)
  (first contribution to Interactive Examples).
- Add `grid-area` label indicators to `div` content
  ([Interactive Examples PR 1248](https://github.com/mdn/interactive-examples/pull/1248)),
  from
  [Liz Lawley](https://github.com/mamamusings).
- Fix `-webkit-overflow-scrolling` inheritance
  ([Data PR 331](https://github.com/mdn/data/pull/331)),
  from
  [Timothy Liang](https://github.com/timothy003).
- Add chroma keying example
  ([PR 29](https://github.com/mdn/dom-examples/pull/29)),
  Add web crypto examples
  ([PR 30](https://github.com/mdn/dom-examples/pull/30)),
  and
  Remove web crypto examples
  ([PR 31](https://github.com/mdn/dom-examples/pull/31)),
  from
  [wbamberg](https://github.com/wbamberg)
  (first contributions to dom-examples).
- Fix indenting of ``display_genre.short_description = 'Genre'``
  ([django-locallibrary-tutorial PR 33](https://github.com/mdn/django-locallibrary-tutorial/pull/33)),
  from
  [AlekseiMarinichenko](https://github.com/AlekseiMarinichenko).
- Convert ``speechResult`` to lowercase to fix phrase matching
  ([web-speech-api PR 29](https://github.com/mdn/web-speech-api/pull/29)),
  from
  [Hartmut Bohnacker](https://github.com/bohnacker).
- In the synthesis demo, list the voices into alphabetical order (ignoring case)
  ([web-speech-api PR 30](https://github.com/mdn/web-speech-api/pull/30)),
  from
  [Chris Chittleborough](https://github.com/c12h).
- Add recipes
  ([PR 1](https://github.com/mdn/stumptown-experiment/pull/1)),
  and
  Add CSS property transform
  ([PR 3](https://github.com/mdn/stumptown-experiment/pull/3)),
  from
  [wbamberg](https://github.com/wbamberg)
  (first contributions to stumptown-experiment).
- Add error handling to multiple fetch examples
  ([fetch-examples PR 13](https://github.com/mdn/fetch-examples/pull/13)),
  from
  [T.J. Crowder](https://github.com/tjcrowder).
- Simplify `editable-list` example
  ([web-components-examples PR 13](https://github.com/mdn/web-components-examples/pull/13)),
  from
  [liuxuewei](https://github.com/liuxuewei).
- Add ``auto`` to ``flex`` to match Firefox's wrapping in Safari and Chrome
  ([learning-area PR 108](https://github.com/mdn/learning-area/pull/108)),
  from
  [stefsulzer](https://github.com/stefsulzer).
- Vary console messages to distinguish between handlers
  ([simple-web-worker PR 10](https://github.com/mdn/simple-web-worker/pull/10)),
  from
  [Bharath Bhushan Lohray](https://github.com/lordloh).
- Update README to reference MDN docs
  ([crossbrowser-testing-lab PR 1](https://github.com/mdn/crossbrowser-testing-lab/pull/1)),
  from
  [James Thompson](https://github.com/100stacks).
- Add grid wrapper example to CSS Layout Cookbook
  ([css-examples PR 12](https://github.com/mdn/css-examples/pull/12)),
  from
  [Michelle Barker](https://github.com/mbarker84).


Planned for December
===
Intro

<a name="plan1-nov-18">Plan 1</a>
---
Main effort

<a name="plan2-nov-18">Plan 2</a>
---
Second effort

<a name="plan3-nov-18">Plan 3</a>
---
Thing we promised last month

