# index

> My repos, indexed

## Browser-only javascript modules

### Media modules

* [iphone-inline-video](https://github.com/bfred-it/iphone-inline-video) - 📱 Make videos playable inline on the iPhone (prevents automatic fullscreen)
* [video-canvas](https://github.com/bfred-it/video-canvas) - Paint video on canvas. Extra light.
* [object-fit-images](https://github.com/bfred-it/object-fit-images) - 🗻 Polyfill object-fit and object-position on images on IE9, IE10, IE11, Edge, Safari, ...
* [supports-webp](https://github.com/bfred-it/supports-webp) - Instantly detect support for WEBP images in the browser in 0.2KB
* [image-promise](https://github.com/bfred-it/image-promise) - 🌄 Load an image and return a promise in the browser, in 0.3KB, no dependencies
* [get-media-size](https://github.com/bfred-it/get-media-size) - Get the real size of an (already-loaded) `<img>`, `<video>`, or `<canvas>` in the browser.
* [get-canvas-pixel-color](https://github.com/bfred-it/get-canvas-pixel-color) - Micro module to get the color of a single pixel on a HTML canvas
* [animate-prop](https://github.com/bfred-it/animate-prop) - Single, dependency-free function to tween a property. Use that on canvas or anywhere else.

### DOM modules

* [select-dom](https://github.com/bfred-it/select-dom) - Slim alternative to document.querySelector/All
* [delegate-it](https://github.com/bfred-it/delegate-it) - DOM event delegation, in <1KB
* [on-off](https://github.com/bfred-it/on-off) - Add/remove DOM events
* [one-event](https://github.com/bfred-it/one-event) - Micro module to add an event listener to be executed only once
* [get-scroll](https://github.com/bfred-it/get-scroll) - Micro module to get the scroll position (top or left) in the browser
* [get-elements-array](https://github.com/bfred-it/get-elements-array) - Array of elements from selector, Array-like objects and single elements.
* [filter-altered-clicks](https://github.com/bfred-it/filter-altered-clicks) - Filter alt-click, ctrl-click, shift-click, middle click, ...
* [visibility-change-ponyfill](https://github.com/bfred-it/visibility-change-ponyfill) - A more reliable visibilitychange event that works in more mobile WebViews
* [gsap-then](https://github.com/bfred-it/gsap-then) - Make every GSAP Tween a promise. tl.then(doSomething)
* [indent-textarea](https://github.com/bfred-it/indent-textarea) - Add editor-like tab-to-indent functionality to `<textarea>`, in a few bytes
* [fit-textarea](https://github.com/bfred-it/fit-textarea) - Automatically expand a `<textarea>` to fit its content, in a few bytes

### Network modules

* [nano-fetch](https://github.com/bfred-it/nano-fetch) - A tiny window.fetch-like promise-based AJAX implementation.
* [tiny-load-script](https://github.com/bfred-it/tiny-load-script) - Load a javascript file and forget about it
* [facebook-sdk-promise](https://github.com/bfred-it/facebook-sdk-promise) - Load Facebook's API and return a Promise. If it's already loading it won't try to load it again.
* [facebook-handshake](https://github.com/bfred-it/facebook-handshake) - Seamlessly log into Facebook silently, with a popup or with a redirect on unsupported browsers (Chrome/iOS)

### Utility modules

* [many-keys-map](https://github.com/bfred-it/many-keys-map) - A Map subclass with support for multiple keys for one entry
* [prevent-popstate-scroll](https://github.com/bfred-it/prevent-popstate-scroll) - Prevent the scroll restoration caused by the popstate event or back/forward buttons.
* [scroll-restoration-polyfill](https://github.com/bfred-it/scroll-restoration-polyfill) - Polyfill for the "History API: Scroll Restoration"
* [console-class](https://github.com/bfred-it/console-class) - Get yourself a light, togglable, namespaced and colored console.log in the browser
* [intervalometer](https://github.com/bfred-it/intervalometer) - Call a function at every frame or every X ms. With start/stop.
* [intrinsic-scale](https://github.com/bfred-it/intrinsic-scale) - Replicate `background-size: cover/contain` for canvas/CSS/Node/… on any type of media.
* [poor-mans-symbol](https://github.com/bfred-it/poor-mans-symbol) - Poor man's Symbol implementation, not compliant. Uses window.Symbol if present
* [random-encoder](https://github.com/bfred-it/random-encoder) - Lightweight way to generate multiple, random, reversible "hashes" or encoding
* [pet-names](https://github.com/bfred-it/pet-names) - &#128145; Get popular pet names (for girlfriends and boyfriends)
* [shorten-repo-url](https://github.com/bfred-it/shorten-repo-url) - Shorten GitHub links like GitHub shortens Issues and Commit links.
* [list-github-dir-content](https://github.com/bfred-it/list-github-dir-content) - List all the files in a GitHub repo’s directory
* [tiny-version-compare](https://github.com/bfred-it/tiny-version-compare) - Compare two software versions, with any number of points (<1KB)

## Node-only modules

* [tumblr-upload](https://github.com/bfred-it/tumblr-upload) - 🚡 Upload your Tumblr theme via node or CLI
* [bin-dir](https://github.com/bfred-it/bin-dir) - Find or open the folder of a global command (installed via npm or not)
* [npm-bundler](https://github.com/bfred-it/npm-bundler) - Opinionated ES6 library bundler based on rollup-babel-lib-bundler. For my own modules, but maybe you can find it useful too.
* [rollup-config-webext](https://github.com/bfred-it/webext-inject-on-install) - Suggested configuration to bundle files in browser extensions.

## Modules for browser extensions

* [webext-options-sync](https://github.com/bfred-it/webext-options-sync) - Helps you manage and autosave your extension's options.
* [webext-dynamic-content-scripts](https://github.com/bfred-it/webext-dynamic-content-scripts) - Automatically inject your `content_scripts` on custom domains.
* [webext-content-script-ping](https://github.com/bfred-it/webext-content-script-ping) - One-file interface to detect whether your content script have loaded.
* [webext-inject-on-install](https://github.com/bfred-it/webext-inject-on-install) - Automatically add content scripts to existing tabs when your extension is installed.
* [webext-domain-permission-toggle](https://github.com/bfred-it/webext-domain-permission-toggle) - Browser-action context menu to request permission for the current tab.

## Browser extensions

* [GhostText](https://github.com/GhostText/GhostText) - :ghost: Use your text editor to write in your browser. Everything you type in the editor will be instantly updated in the browser (and vice versa).
* [GitHub Issue Link Status](https://github.com/bfred-it/github-issue-link-status) - Colorize issue and PR links to see their status (open, closed, merged)
* [npmhub](https://github.com/npmhub/npmhub/) - :mag_right: A browser extension for exploring npm dependencies on GitHub repos.
* [One Click Extension Manager](https://github.com/HangYang/ext_manager) - Simple Chrome extension to manage your Chrome extensions.
* [Refined GitHub](https://github.com/sindresorhus/refined-github/) - Simplifies the GitHub interface and adds useful features.
* [GitHub Clean Feed](https://github.com/bfred-it/github-clean-feed) - Group GitHub news feed by repo.
* [sticky-pinned-tabs](https://github.com/bfred-it/sticky-pinned-tabs) - Chrome Extension: When in a pinned tab, external links open in a new tab
* [gstocks](https://github.com/bfred-it/gstocks) - Chrome extension + bookmarklet
* [browser-player](https://github.com/bfred-it/browser-player) - 🔈 Chrome extension: pause other tabs when you play something

## Web tools

Unpolished and undocumented, though

* [regallery.ga](https://github.com/bfred-it/regallery.ga) - Paste a Reddit post URL, get a gallery of each comment's image. Perfect for /r/photoshopbattles.
* [index-github-bot](https://github.com/bfred-it/index-github-bot) - Bot that reminds me to add my new repos to my index.
* [Sapere.it-Mobile](https://github.com/bfred-it/Sapere.it-Mobile) - Italian Dictionary
* [HTML-Slayer](https://github.com/bfred-it/HTML-Slayer) - Trim images/layers and position them in HTML+CSS automatically
* [art-cropper](https://github.com/bfred-it/art-cropper) - Drop images, export art-directed cropped images

## Extras

* [Awesome-WebExtensions](https://github.com/bfred-it/Awesome-WebExtensions) - A curated list of awesome resources for Web Extensions development
* [github-desktop-open-in-sublime-text](https://github.com/bfred-it/github-desktop-open-in-sublime-text) - In GitHub Desktop on Mac, replace "Open in Atom" with Sublime Text
* [rollup-config-es6-browser](https://github.com/bfred-it/rollup-config-es6-browser)
* [rollup-config-buble](https://github.com/bfred-it/rollup-config-buble)

## Personal stuff

* [currency-slider](https://github.com/bfred-it/currency-slider) - A personal app to quickly convert currency. Not automatically updated
* [MovieList](https://github.com/bfred-it/MovieList) - Built with Meteor: A multi-user movie list with comments
* [hotelteti.com](https://github.com/bfred-it/hotelteti.com) - Jekyll website, wip
