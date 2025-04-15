# Splitpanes

[![Latest Version on NPM](https://img.shields.io/npm/v/splitpanes.svg)](https://npmjs.com/package/splitpanes)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)
[![npm](https://img.shields.io/npm/dt/splitpanes.svg)](https://www.npmjs.com/package/splitpanes)
[![npm](https://img.shields.io/npm/dw/splitpanes.svg)](https://www.npmjs.com/package/splitpanes)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

> A Vue.js reliable, simple and touch-ready panes splitter / resizer.
> Vue 3 compatible.

## Installation

**Vue 3**

```
npm i splitpanes
```

**Vue 2**

```
npm i splitpanes@legacy
```

---

## Demo & Documentation

> [https://antoniandre.github.io/splitpanes](https://antoniandre.github.io/splitpanes)

## Try it yourself

> [https://codepen.io/antoniandre/pen/XybPKP](https://codepen.io/antoniandre/pen/XybPKP)

---

## Browser Support

| ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Latest ✔                                                                                | Latest ✔                                                                                   | Latest ✔                                                                                | Latest ✔                                                                             | Latest ✔                                                                          | 10+ ✔                                                                                                                       |

---

## Donating

If you like this library, you can buy me a beer or [become a sponsor](https://github.com/sponsors/antoniandre)!

[![paypal](https://www.paypalobjects.com/en_AU/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/antoniandre1)
Thank you!

If you are using this library for profit business, please consider [backing me](https://github.com/sponsors/antoniandre)!
It ensures that the project your products rely on keeps being actively maintained. :)

---

## Contributing

If you have any idea, feel free to open an issue to discuss a new feature, or fork Splitpanes and submit your changes back to me.

---

## Release Notes

- **Version 2.3.0** Support rtl direction
- **Version 2.2.0** Add `firstSplitter` option allow `v-if` on panes and other improvements
- **Version 2.0.0** Fix reactivity issues
- **Version 1.14.0** Programmatically set pane size
- **Version 1.13.0** Emit event on splitter click
- **Version 1.12.0** Double click splitter to maximize is now an option
- **Version 1.11.0** Persist panes size after slots changed
- **Version 1.10.0** Add maximum size feature on panes
- **Version 1.9.0** Emit event on resize &amp; watch slots optional
- **Version 1.8.0** Watch slots
- **Version 1.7.0** Double click splitter to maximize next pane
- **Version 1.6.0** Emit events
- **Version 1.5.0** Add default size feature on panes (max feature coming soon!)
- **Version 1.4.0** Add minimum size feature on panes
- **Version 1.3.0** Splitpanes slots are now reactive (add/remove on the fly)
- **Version 1.2.0** Add a `default-theme` CSS class to load default theme
- **Version 1.1.0** Allow pushing other panes while dragging splitter
- **Version 1.0.0** First public release

## Releasing

Manual releases for the moment:

- `npm version <version>` (major, minor, patch)
- `pnpm run build`
- `pnpm publish`
- `git push`
