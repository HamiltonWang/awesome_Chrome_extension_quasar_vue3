# Awesome Chrome Extension Quasar Vue3
some notes and useful links to getting Quasar + Vue3 + Chrome Extension to work together


## Interaction among doc + content script + background script
- [Chinese read from ithome](https://ithelp.ithome.com.tw/articles/10187744)
- [Quasar is added to act as middleman in the framework](https://dev.to/quasar/quasar-and-browser-extension-development-getting-bexy-part-2-17ea)
note: `background-hooks.js` is merged into `background.js` and in `backgound.js`, `chrome.action.onClicked.addListener(...)` should be used. `chrome.browserAction.onClicked.addListener(...)` is for content.js
- [understanding how bex communication work in Quasar](https://quasar.dev/quasar-cli-vite/developing-browser-extensions/bex-communication) You should read these articles too to understanad them thoroughly. If you do not understand, come back later.
  - [Types of BEX](https://quasar.dev/quasar-cli-vite/developing-browser-extensions/types-of-bex) 
  - [Background Script](https://quasar.dev/quasar-cli-vite/developing-browser-extensions/background-script)
  - [Content Script](https://quasar.dev/quasar-cli-vite/developing-browser-extensions/content-scripts)
  - [DOM Script](https://quasar.dev/quasar-cli-vite/developing-browser-extensions/dom-script)
