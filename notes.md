# Notes

## Lesson 01: Einführung, IDE Setup &amp; Grundlagen

- Grundlagen
  - [Robustness and least power](https://adactio.com/journal/14327?skin=default)
  - [Sparse vs. Dense Arrays](https://dmitripavlutin.com/javascript-sparse-dense-arrays/)
  - [How to fill an array with initial values](https://dmitripavlutin.com/javascript-fill-array/)
  - [Array.prototype.flat()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flat)
  - [Syntax: Destructuring, spread, optional chaining, etc.](https://2020.stateofjs.com/en-US/features/syntax/)
  - [Features: Maps, Hashtables, etc.](https://2020.stateofjs.com/en-US/features/)
  - [Modern Javascript: Everything you missed over the last 10 years](https://turriate.com/articles/modern-javascript-everything-you-missed-over-10-years)

### Tools

- [Deno Linter](https://deno.land/manual/tools/linter)
- [Jest Test Runner](https://jestjs.io/)
- [AVA Test Runner](https://github.com/avajs/ava)
- [UVU Test Runner](https://github.com/lukeed/uvu)

### Lektion 2: Code Organisation (Funktionen, Klassen & Modulen)

### Builders / Loaders

- No module loader:
  - Use browser support
  - [JavaScript modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
  - [ES Module Shims](https://github.com/guybedford/es-module-shims)
  - [Skypack](https://www.skypack.dev/)
  - [Why We Switched From Webpack To Vite](https://blog.replit.com/vite)
  - [Vite](https://vitejs.dev/)
  - [Why Vite?](https://vitejs.dev/guide/why.html)
- [How I Build JavaScript Apps In 2021](https://timdaub.github.io/2021/01/16/web-principles/)
- [CommonJS to ESM in Node.js](https://ar.al/2021/01/27/commonjs-to-esm-in-node.js/)
- [Snowpack](https://www.sitepoint.com/learn-snowpack/)
  - [Snowpack Demo](https://github.com/sitepoint-editors/snowpack-demo)
  - [Learn Snowpack](https://www.sitepoint.com/learn-snowpack/)
- [ESBuild Content Types](https://esbuild.github.io/content-types/)

- [Javascript Card Trick - Computerphile](https://www.youtube.com/watch?v=rkrjo4IIb1I) ([code](https://pastebin.com/YheE3kJQ))
- [Intl](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl) (native i18n)

### Browser

- [State of JS 2020: Browser APIs](https://2020.stateofjs.com/en-US/features/browser-apis/)

## Lesson 3: DOM, Events & HTML Forms

- Intervals and timers

### HTML, CSS, and Inputs

- [CSS Logical Properties Are the Future of the Web & I18N](https://medium.com/swlh/css-logical-properties-are-the-future-of-the-web-i18n-c7d554c6dd72)
- [Responsible Web Applications](https://responsibleweb.app/)
- [Understanding Z-Index in CSS](https://ishadeed.com/article/understanding-z-index/)

- [Exploring the SameSite cookie attribute for preventing CSRF](https://simonwillison.net/2021/Aug/3/samesite/)
- [VirtualKeyboard](https://www.w3.org/TR/virtual-keyboard/#dom-virtualkeyboard)
- [accent-color](https://web.dev/accent-color/)
- [Using Aria](https://www.w3.org/TR/using-aria/#notes2)

## Lesson 4: Persistenz (Cookies & LocalStorage)

### DOM

- [Exploring DOM Events](https://domevents.dev/)
- [Observing rendered DOM nodes](https://whistlr.info/2021/observing-dom/) (ResizeObserver/IntersectionObserver)

### Browser integration

- [Use console.log() like a pro](https://markodenic.com/use-console-log-like-a-pro/)

## Lesson 5: JSON & Fetch

### Fetch

- Promises
- Async/Await

- [What is a Promise in JavaScript?](https://dmitripavlutin.com/what-is-javascript-promise/)
- Await/async
- [How to Greatly Enhance fetch() with the Decorator Pattern](https://dmitripavlutin.com/enhance-fetch-with-decorator-pattern/)

## Lektion 6: Komponenten (Web Components)

- [CSS env()](https://developer.mozilla.org/en-US/docs/Web/CSS/env())
- [CSS Circle Focus Effect](https://www.bram.us/2021/09/17/css-circle-focus-effect/)

### Class, proxies, decorators

Note: move this earlier

- [Understanding JavaScript Decorators](https://www.simplethread.com/understanding-js-decorators/) (might be too advanced, but good to know)
- [Proxy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)

## Lektion 7: Animationen & Grafik

- Intro to web components
- Shadow DOM, etc.
- [Single-file Web Component](https://gist.github.com/simonw/2df444ce0bd75c8bf91beb7a6516ba5b)
- [HTML with Superpowers](https://daverupert.com/2021/10/html-with-superpowers/)
  - [two-up-element](https://codepen.io/developit/pen/qBdbNLK)
- [Spectrum Web Components](https://opensource.adobe.com/spectrum-web-components/components/color-handle/)
- [Lit](https://lit.dev/)
- [TAO of React](https://alexkondov.com/tao-of-react/) (move this down)
- [CSS Full-Height Slideshow with Centered Slides thanks to grid-auto-rows](https://www.bram.us/2021/11/04/css-full-height-slideshow-with-centered-slides-thanks-to-grid-auto-rows/) (no JS needed for animation)

## Lektion 8: Animationen & Grafik

### Animation

- [The World of CSS Transforms](https://www.joshwcomeau.com/css/transforms/)
- [An Interactive Guide to CSS Transitions](https://www.joshwcomeau.com/animation/css-transitions/)
- [An Interactive Guide to Keyframe Animations](https://www.joshwcomeau.com/animation/keyframe-animations/)
- [Advanced CSS Animation using Cubic Bezier](https://css-tricks.com/advanced-css-animation-using-cubic-bezier/)
- [The new native web: Bye bye animation libraries? by Ben Deitmer](https://www.youtube.com/watch?v=7kz4tYF4DZk)
- [Debugging layout repaint issues triggered by CSS Transition](https://dzhavat.github.io/2021/02/18/debugging-layout-repaint-issues-triggered-by-css-transition.html)

### Security

- [How to win at CORS](https://jakearchibald.com/2021/cors/), [CORS Playground](https://jakearchibald.com/2021/cors/playground/)
- [CS Visualized: CORS](https://dev.to/lydiahallie/cs-visualized-cors-5b8h)
- [\<a>: The Anchor element / Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attributes) (a/href is not so innocent)
- [Lit](https://lit.dev/)

### Grafik

- [Observable Plot](https://observablehq.com/@observablehq/plot)
- [Plot & Vega-Lite](https://observablehq.com/@observablehq/plot-vega-lite)
- [React + D3.js](https://wattenberger.com/blog/react-and-d3)
- [SVG Explained in 100 Seconds - YouTube](https://www.youtube.com/watch?v=emFMHH2Bfvo)
- [SVG Path Visualizer](https://svg-path-visualizer.netlify.app/#M2%2C8%20L5%2C2%20L8%2C8)
- [Too Many SVGs Clogging Up Your Markup? Try `use`.](https://css-tricks.com/too-many-svgs-clogging-up-your-markup-try-use/)

## Lesson 9

### Service Workers

- [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)

### Alternatives/Extensions to JavaScript

- [Vanilla JS v. jQuery v. hyperscript](https://hyperscript.org/comparison/)
- [Starting a TypeScript Project in 2021](https://www.metachris.com/2021/04/starting-a-typescript-project-in-2021/)
- ELM
- Svelte
- [Upgrading to Typescript (book)](https://exploringjs.com/tackling-ts/)
