---
layout: post
title: MDN Changelog for July 2018
author: John Whitlock
---

Done in July
===

Here's what happened in July to the
[code, data, and tools](https://github.com/mdn/)
that support
[MDN Web Docs](https://developer.mozilla.org):

- [Experimented with the CDN](#cdn-jul-18)
- [Decommissioned zones](#zones-jul-18)
- [Converted compatibility data](#bcd-jul-18)
- [Shipped tweaks and fixes](#tweaks-jul-18)
  by merging 307 pull requests,
  including 58 pull requests
  from 43 new contributors.

Here's the plan for August:

- [Upgrade to ElasticSearch 5.6](#es-jul-18)

<a name="item2-jul-18">Experimented with the CDN</a>
---
- Change cache TTL from 5min to 48hr
  ([Kuma PR 4876](https://github.com/mozilla/kuma/pull/4876)),
  from
  [Ryan Johnson](https://github.com/escattone).

Other performance stuff:

- Inline dnt-helper
  ([Kuma PR 4881](https://github.com/mozilla/kuma/pull/4881)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).
- Add Jinja helper for SVG
  ([Kuma PR 4860](https://github.com/mozilla/kuma/pull/4860)),
  from
  [Schalk Neethling](https://github.com/schalkneethling).

<a name="zones-jul-18">Decommissioned zones</a>
---
We disabled zones on TKTK. They are gone. There is a little more to do.

- Death of zones
  ([Kuma PR 4853](https://github.com/mozilla/kuma/pull/4853)),
  from
  [Ryan Johnson](https://github.com/escattone).

<a name="bcd-jul-18">Converted compatibility data</a>
---
In July of last year, the BCD project hit the milestone of over 1000 MDN pages
using the new compatibility data, with about 4900 to convert. This month, there
are less than 850 pages left to convert, and over 5000 MDN pages are using the
new data. The steady work of the BCD team has made a huge impact on MDN and the
community.

Visual Studio Code
[improved the accuracy of their Browser Compatibility Data](https://code.visualstudio.com/updates/v1_25#_improved-accuracy-of-browser-compatibility-data)
by adopting the BCD project in the June 2018 release. This was proposed by
[Pine](https://github.com/octref) in
[vscode-css-languageservice issue #102](https://github.com/Microsoft/vscode-css-languageservice/issues/102)
and implemented in
[PR #105](https://github.com/Microsoft/vscode-css-languageservice/pull/105),
with feedback from BCD and mdn/data regular
[Connor Shea](https://github.com/connorshea).

![vscode](
 {{ site.baseurl }}/public/images/kuma/2018-08-vscode.png
 "BCD data in VS Code, from the Visual Studio Code update notes")

After a long discussion, the BCD project has updated the policy for
Node.js versions numbers
([PR 2196](https://github.com/mdn/browser-compat-data/pull/2196),
[PR 2294](https://github.com/mdn/browser-compat-data/pull/2294),
and others). At first, browser-style version numbers were used, such as
"4", "6", and "8", but the Node.js community requested "4.0.0",
"6.0.0", and "8.0.0", to more closely reflect how they think of
release numbers. This was a wide ranging change that unstuck several
Node.js pull requests.

[Florian Scholz](https://github.com/Elchi3) went on vacation, and
[Daniel D. Beck](https://github.com/ddbeck) took the lead on project
maintenance, including shipping the npm package
(documented in
[PR 2480](https://github.com/mdn/browser-compat-data/pull/2480)).
Most of the
[PRs from the Paris Hack on MDN event](https://github.com/mdn/browser-compat-data/pulls?utf8=%E2%9C%93&q=is%3Apr+label%3A%22HackOnMDNParis2018+%3Afr%3A%22+)
are now merged or closed, and the project is down to 120 open PRs,
representing about half of the remaining conversion work.

<a name="tweaks-jul-18">Shipped Tweaks and Fixes</a>
---
There were 307 PRs merged in July:

- [197 mdn/browser-compat-data PRs](https://github.com/mdn/browser-compat-data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [48 mdn/interactive-examples PRs](https://github.com/mdn/interactive-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [26 mozilla/kuma PRs](https://github.com/mozilla/kuma/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [13 mdn/kumascript PRs](https://github.com/mdn/kumascript/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [6 mdn/bob PRs](https://github.com/mdn/bob/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [5 mdn/infra PRs](https://github.com/mdn/infra/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [4 mdn/learning-area PRs](https://github.com/mdn/learning-area/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/learning-area-pt-br PR](https://github.com/mdn/learning-area-pt-br/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/dom-examples PR](https://github.com/mdn/dom-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/voice-change-o-matic PR](https://github.com/mdn/voice-change-o-matic/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/web-components-examples PR](https://github.com/mdn/web-components-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/webextensions-examples PR](https://github.com/mdn/webextensions-examples/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/doc-linter-webextension PR](https://github.com/mdn/doc-linter-webextension/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/data PR](https://github.com/mdn/data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")
- [1 mdn/web-speech-api PR](https://github.com/mdn/web-speech-api/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31")

58 of these were from first-time contributors:

- Correct node support for spread (`...`) in object literals
  ([BCD PR 2189](https://github.com/mdn/browser-compat-data/pull/2189)),
  from
  [Tobias](https://github.com/m4staka).
- Add NodeJS versions for some features
  ([BCD PR 2196](https://github.com/mdn/browser-compat-data/pull/2196)),
  from
  [Solant](https://github.com/Solant).
- Update JavaScript spread operator (`...`) for Node.js
  ([PR 2262](https://github.com/mdn/browser-compat-data/pull/2262)),
  Update Node.js versions
  ([PR 2294](https://github.com/mdn/browser-compat-data/pull/2294)),
  and
  [9 more PRs](https://github.com/mdn/browser-compat-data/pulls?page=1&utf8=✓&q=is:pr+is:closed+merged:"2018-07-01..2018-07-31"+author:jcsahnwaldt)
  to BCD from
  [Christopher Sahnwaldt](https://github.com/jcsahnwaldt).
- Add browser compatibility table for `<input type="checkbox">`
  ([PR 2383](https://github.com/mdn/browser-compat-data/pull/2383)),
  Add browser compatibility table for `<input type="button">`
  ([PR 2384](https://github.com/mdn/browser-compat-data/pull/2384)),
  and
  Add browser compatibility table for `<input type="search">`
  ([PR 2385](https://github.com/mdn/browser-compat-data/pull/2385)),
  to BCD from
  [varun singh](https://github.com/varun07).
- Add missing entity ampersands in description.
  ([BCD PR 2397](https://github.com/mdn/browser-compat-data/pull/2397)),
  from
  [epistemex](https://github.com/epistemex).
- Add `DOMStringMap`
  ([BCD PR 2401](https://github.com/mdn/browser-compat-data/pull/2401)),
  from
  [Ayush Poddar](https://github.com/Mr-Magnificent).
- Add Edge support for `overflow-wrap`
  ([BCD PR 2406](https://github.com/mdn/browser-compat-data/pull/2406)),
  from
  [Quentin Calvez](https://github.com/quentez).
- Add missing `browserSettings` permission
  ([BCD PR 2407](https://github.com/mdn/browser-compat-data/pull/2407)),
  from
  [Juraj Mäsiar](https://github.com/icl7126).
- Add data on `window.scroll` for MS Edge
  ([BCD PR 2433](https://github.com/mdn/browser-compat-data/pull/2433)),
  from
  [David Wheatley](https://github.com/davwheat).
- Update data on `<input type="color">` for Edge
  ([BCD PR 2434](https://github.com/mdn/browser-compat-data/pull/2434)),
  from
  [Thomas Prochazka](https://github.com/zlypher).
- Add IDEA (IntelliJ, WebStorm, etc.) to `.gitignore`
  ([PR 2435](https://github.com/mdn/browser-compat-data/pull/2435)),
  and
  Add Node.js 8.0.0 support for JavaScript features
  ([PR 2436](https://github.com/mdn/browser-compat-data/pull/2436)),
  to BCD from
  [Peter Mouland](https://github.com/peter-mouland).
- Update `backdrop-filter`
  ([BCD PR 2438](https://github.com/mdn/browser-compat-data/pull/2438)),
  from
  [Philip Goto](https://github.com/flipflop97).
- Add `text-align`’s `<string>` value
  ([BCD PR 2442](https://github.com/mdn/browser-compat-data/pull/2442)),
  from
  [Jakob Krigovsky](https://github.com/sonicdoe).
- Add `search.get`, `search.search` API data
  ([BCD PR 2444](https://github.com/mdn/browser-compat-data/pull/2444)),
  from
  [Geoffrey De Belie](https://github.com/Smile4ever).
- Add compatibility for `window.scrollTo`
  ([BCD PR 2445](https://github.com/mdn/browser-compat-data/pull/2445)),
  from
  [Mauro Mandracchia](https://github.com/M3kH).
- Add support for CSS selector `:defined`
  ([BCD PR 2454](https://github.com/mdn/browser-compat-data/pull/2454)),
  from
  [Estelle Weyl](https://github.com/estelle).
- Add support for `window.scroll` functions in Safari
  ([BCD PR 2462](https://github.com/mdn/browser-compat-data/pull/2462)),
  from
  [Raz Goldin](https://github.com/zargold).
- Mark properties defined in ECMA-262 Annex B as deprecated
  ([BCD PR 2469](https://github.com/mdn/browser-compat-data/pull/2469)),
  from
  [TSlivede](https://github.com/TSlivede).
- Add support for `MediaDevices` API
  ([BCD PR 2472](https://github.com/mdn/browser-compat-data/pull/2472)),
  from
  [Gaurav Mahto](https://github.com/gauravmahto).
- Update Safari support for CSS property `overscroll-behavior` from unknown to
  unsupported
  ([BCD PR 2490](https://github.com/mdn/browser-compat-data/pull/2490)),
  from
  [Peter Fernandes](https://github.com/fernap3).
- Update Safari support for `Navigator.registerProtocolHandler` API from
  unknown to unsupported
  ([BCD PR 2499](https://github.com/mdn/browser-compat-data/pull/2499)),
  from
  [Lioman](https://github.com/lioman).
- Move Firefox support for `Server-Timing` header from 59 to 61
  ([BCD PR 2504](https://github.com/mdn/browser-compat-data/pull/2504)),
  from
  [Charles Vazac](https://github.com/cvazac).
- Fix JS `RegExp` lookbehind assertion description
  ([BCD PR 2521](https://github.com/mdn/browser-compat-data/pull/2521)),
  from
  [Nate Weaver](https://github.com/Wevah).
- Update IE's support of CSS property `text-align-last`
  ([BCD PR 2525](https://github.com/mdn/browser-compat-data/pull/2525)),
  from
  [Refael Iliaguyev](https://github.com/rellect).
- Add Node.js 10 support for `promise.finally`
  ([BCD PR 2529](https://github.com/mdn/browser-compat-data/pull/2529)),
  from
  [NKN1396](https://github.com/NKN1396).
- Add Chrome support for `crisp-edges` as `-webkit-optimize-contrast`
  ([BCD PR 2531](https://github.com/mdn/browser-compat-data/pull/2531)),
  from
  [Eugene Pankov](https://github.com/Eugeny).
- Fix CSP term `navigate-to` (was `navigation-to`)
  ([BCD PR 2532](https://github.com/mdn/browser-compat-data/pull/2532)),
  from
  [Malvoz](https://github.com/Malvoz).
- Lowercase `minlength` attribute for `<input type=password>` example
  ([Interactive Examples PR 1024](https://github.com/mdn/interactive-examples/pull/1024)),
  from
  [Timo Tijhof](https://github.com/Krinkle).
- Change `<select>` examples to use “placeholder label option” pattern
  ([Interactive Examples PR 1025](https://github.com/mdn/interactive-examples/pull/1025)),
  from
  [Taylor Hunt](https://github.com/tigt).
- Add a new line for markdown bullet list
  ([Interactive Examples PR 1028](https://github.com/mdn/interactive-examples/pull/1028)),
  from
  [Enguerran](https://github.com/enguerran).
- Add `balance-all` value to `column-fill` example
  ([Interactive Examples PR 1039](https://github.com/mdn/interactive-examples/pull/1039)),
  from
  [Estelle Weyl](https://github.com/estelle).
- Add `id` as reference for `<label for=>` attribute
  ([Interactive Examples PR 1045](https://github.com/mdn/interactive-examples/pull/1045)),
  from
  [Jon Borglund](https://github.com/Row).
- Make "Publish and Keep Editing" height the same as others
  ([Kuma PR 4900](https://github.com/mozilla/kuma/pull/4900)),
  from
  [Mihir Karbelkar](https://github.com/Mihir-Karbelkar).
- Update the URL of Web Speech API
  ([KumaScript PR 731](https://github.com/mdn/kumascript/pull/731)),
  from
  [Kagami Sascha Rosylight](https://github.com/saschanaz).
- Updating Learn sidebar to add new Layout guides
  ([PR 736](https://github.com/mdn/kumascript/pull/736)),
  from
  [Rachel Andrew](https://github.com/rachelandrew)
  (first contribution to KumaScript).
- Move Writing Modes Level 4 to Candidate Recommendation (CR)
  ([KumaScript PR 744](https://github.com/mdn/kumascript/pull/744)),
  from
  [Estelle Weyl](https://github.com/estelle).
- Reference correct video source video file
  ([learning-area PR 84](https://github.com/mdn/learning-area/pull/84)),
  from
  [Rohit Arondekar](https://github.com/rohit).
- Fix "farenheit" typo
  ([learning-area PR 85](https://github.com/mdn/learning-area/pull/85)),
  from
  [arda152](https://github.com/arda152).
- Fix comparison operator (`!==`) in Event Listener
  ([learning-area PR 86](https://github.com/mdn/learning-area/pull/86)),
  from
  [Mourad El garma](https://github.com/aka-yuki).
- Add folder `javascript/object-basics` for chapter translation
  ([learning-area-pt-br PR 2](https://github.com/mdn/learning-area-pt-br/pull/2)),
  from
  [Felipe Maia](https://github.com/webfelipemaia).
- Change convolver to disconnect and reconnect to the audio path
  ([voice-change-o-matic PR 15](https://github.com/mdn/voice-change-o-matic/pull/15)),
  from
  [LUCAS GARIBALDI ALVES](https://github.com/lgaribaldi).
- Use ES2015+ syntax
  ([web-components-examples PR 8](https://github.com/mdn/web-components-examples/pull/8)),
  from
  [Kevin Nagurski](https://github.com/knagurski).
- Add `{{EventRef}}` to the list of allowed macros
  ([PR 70](https://github.com/mdn/doc-linter-webextension/pull/70)),
  from
  [Eric Shepherd](https://github.com/a2sheppy)
  (first contribution to Doc Linter WebExtension).
- Maintain case consistency
  ([web-speech-api PR 26](https://github.com/mdn/web-speech-api/pull/26)),
  from
  [utkarsh-raj](https://github.com/utkarsh-raj).

Other significant PRs:

- Check bugzil.la link format
  ([BCD PR 2511](https://github.com/mdn/browser-compat-data/pull/2511)),
  one of
  [32 Pull Requests](https://github.com/mdn/browser-compat-data/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aclosed+merged%3A%222018-07-01..2018-07-31%22+author%3Acaugner)
  from
  [Claas Augner](https://github.com/caugner).
- Open interactive example links in a new tab
  ([Interactive Examples PR 1009](https://github.com/mdn/interactive-examples/pull/1009)),
  from
  [Stephan Max](https://github.com/stephanmax).
- Update node 8, dependencies
  ([Kuma PR 4852](https://github.com/mozilla/kuma/pull/4852)),
  from
  [me](https://github.com/jwhitlock).

Planned for August
===
More of the same.

<a name="es-jul-18">Upgrade to ElasticSearch 5.6</a>
---
We're on ES 2.4, but need to update to ES 5.6 in August.
