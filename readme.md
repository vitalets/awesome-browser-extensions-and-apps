# Awesome Browser Extensions and Apps [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for building browser extensions and apps

## Contents
* [Tools](#tools)
  * [Development](#development)
  * [Testing](#testing)
  * [Publishing](#publishing)
* [Documentation](#documentation)
* [Examples](#examples)
* [Stores](#stores)
* [Articles](#articles)
* [Videos](#articles) 
* [Community](#community)

## Tools
### Development
* [generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) <sub><img src="https://img.shields.io/github/stars/yeoman/generator-chrome-extension?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/yeoman/generator-chrome-extension?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - yeoman Chrome extension generator that creates everything you need to get started with extension development.
* [then-chrome](https://github.com/acvetkov/then-chrome) <sub><img src="https://img.shields.io/github/stars/acvetkov/then-chrome?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/acvetkov/then-chrome?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - promise-based Chrome extensions API.
* [chnl](https://github.com/vitalets/chnl) <sub><img src="https://img.shields.io/github/stars/vitalets/chnl?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/vitalets/chnl?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - implementation of events compatible with [Chrome Extensions Events API](https://developer.chrome.com/extensions/events#type-Event).
* [bro-fs](https://github.com/vitalets/bro-fs) <sub><img src="https://img.shields.io/github/stars/vitalets/bro-fs?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/vitalets/bro-fs?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - Promise-based [HTML5 Filesystem API](https://dev.w3.org/2009/dap/file-system/file-dir-sys.html) allowing to work with sandboxed filesystem in browser.
* [chrome-manifest](https://github.com/ragingwind/chrome-manifest) <sub><img src="https://img.shields.io/github/stars/ragingwind/chrome-manifest?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/ragingwind/chrome-manifest?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - manage manifest, easily include/exclude keys.
* [WebExtension Manifest Formatter](https://github.com/pastak/wemf) <sub><img src="https://img.shields.io/github/stars/pastak/wemf?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/pastak/wemf?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - Format manifest.json in Chrome Extension, Firefox WebExtension and Extension for Edge
* [WebExtension `browser` API Polyfill](https://github.com/mozilla/webextension-polyfill) <sub><img src="https://img.shields.io/github/stars/mozilla/webextension-polyfill?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/mozilla/webextension-polyfill?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - A lightweight polyfill library for Promise-based WebExtension APIs in Chrome.
* [web-ext](https://github.com/mozilla/web-ext) <sub><img src="https://img.shields.io/github/stars/mozilla/web-ext?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/mozilla/web-ext?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - A command line tool designed to speed up various parts of the extension development process, making development faster and easier.

### Testing
* [sinon-chrome](https://github.com/acvetkov/sinon-chrome) <sub><img src="https://img.shields.io/github/stars/acvetkov/sinon-chrome?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/acvetkov/sinon-chrome?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - testing Chrome extension with Sinon and Node.js.
* [karma-sinon-chrome](https://github.com/9joneg/karma-sinon-chrome) <sub><img src="https://img.shields.io/github/stars/9joneg/karma-sinon-chrome?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/9joneg/karma-sinon-chrome?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - karma adapter to run extension tests with sinon-chrome.

### Publishing
* [crx](https://www.npmjs.com/package/crx) - packs directory into CRX file.
* [grunt-crx](https://github.com/oncletom/grunt-crx) <sub><img src="https://img.shields.io/github/stars/oncletom/grunt-crx?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/oncletom/grunt-crx?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - grunt task used to package Chrome Extensions.
* [chrome-extension-deploy](https://github.com/erikdesjardins/chrome-extension-deploy) <sub><img src="https://img.shields.io/github/stars/erikdesjardins/chrome-extension-deploy?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/erikdesjardins/chrome-extension-deploy?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - programmatic deploy extensions to Chrome Web Store.
* [download-crx](https://github.com/acvetkov/download-crx) <sub><img src="https://img.shields.io/github/stars/acvetkov/download-crx?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/acvetkov/download-crx?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - npm package to dowload CRX from Chrome Web Store by id.
* [chrome-web-store-item-property](https://github.com/pandawing/node-chrome-web-store-item-property) <sub><img src="https://img.shields.io/github/stars/pandawing/node-chrome-web-store-item-property?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/pandawing/node-chrome-web-store-item-property?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - gather version, count of downloads and rating from chrome Web Store.
* [chrome-store-api](https://github.com/acvetkov/chrome-store-api) <sub><img src="https://img.shields.io/github/stars/acvetkov/chrome-store-api?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/acvetkov/chrome-store-api?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - Chrome Webstore [API](https://developer.chrome.com/webstore/using_webstore_api) for Node.js.
* [chrome-webstore-manager](https://github.com/pastak/chrome-webstore-manager) <sub><img src="https://img.shields.io/github/stars/pastak/chrome-webstore-manager?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/pastak/chrome-webstore-manager?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - managing Chrome Web Store items from Node.js.
* [chrome-extension-downloader.com](http://chrome-extension-downloader.com/) - online service to download CRX from Chrome Web Store.
* [crxviewer](https://github.com/Rob--W/crxviewer) <sub><img src="https://img.shields.io/github/stars/Rob--W/crxviewer?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/Rob--W/crxviewer?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - view Chrome, Opera or Firefox extensions content without installing it.

## Documentation
* [Chrome Extensions API](https://developer.chrome.com/extensions/api_index)
* [Opera Extensions API](https://dev.opera.com/extensions/apis/)
* [Firefox WebExtensions API](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API)
* [Firefox Add-ons SDK](https://developer.mozilla.org/en-US/Add-ons/SDK/High-Level_APIs) (legacy)
* [Safari Extensions API](https://developer.apple.com/library/safari/documentation/UserExperience/Reference/SafariExtensionsReference/index.html)
* [Safari App Extensions API](https://developer.apple.com/library/content/documentation/NetworkingInternetWeb/Conceptual/SafariAppExtension_PG/)
* [Edge Extensions API](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/api-support/)

## Examples
* [Official WebExtension Example for Firefox](https://github.com/Standard8/example-webextension) <sub><img src="https://img.shields.io/github/stars/Standard8/example-webextension?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/Standard8/example-webextension?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - Example repository containing templates and good practices for creating a WebExtension for Firefox.
* [webextensions-examples](https://github.com/mdn/webextensions-examples) <sub><img src="https://img.shields.io/github/stars/mdn/webextensions-examples?style=flat-square&label=%E2%98%85&color=777777" alt="Stars"></sub> <sub><img src="https://img.shields.io/github/last-commit/mdn/webextensions-examples?style=flat-square&label=upd&color=777777" alt="Last commit"></sub> - Example Firefox add-ons created using the WebExtensions API. Maintained by the MDN team at Mozilla.

## Stores
* [Chrome Web Store](https://chrome.google.com/webstore)
* [Opera Web Store](https://addons.opera.com/en/extensions/)
* [Firefox Add-ons Store](https://addons.mozilla.org)
* [Safari Extensions Gallery](https://safari-extensions.apple.com/)

## Articles
* [The Future of Developing Firefox Add-ons](https://blog.mozilla.org/addons/2015/08/21/the-future-of-developing-firefox-add-ons/) - official blog post introducing WebExtensions in Firefox
* [Setting up Chrome extensions with a free trial period](http://www.nuanced.it/2016/09/setting-up-chrome-extensions-with-free.html) - This blog post will be helpful for those who are looking to set up a free trial period for their Chrome extension hosted in the Chrome web store.

## Videos
Contribute some ;)

## Community
* [Reddit Chrome Extensions](https://www.reddit.com/r/chrome_extensions)
* [Reddit Chrome Apps](https://www.reddit.com/r/chromeapps)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/google-chrome-extension)

## Contribute
Feel free to share your experience and contribute useful extension resources by creating [new issue](https://github.com/vitalets/awesome-browser-extensions-and-apps/issues/new) or [pull request](https://github.com/vitalets/awesome-browser-extensions-and-apps/compare). Please read the [contribution guidelines](contributing.md) first. Thanks!

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
