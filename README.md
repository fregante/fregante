# index

> My repos, indexed

## Browser-only javascript modules

### Media modules

* [iphone-inline-video](https://github.com/fregante/iphone-inline-video) - 📱 Make videos playable inline on the iPhone (prevents automatic fullscreen)
* [video-canvas](https://github.com/fregante/video-canvas) - Paint video on canvas. Extra light.
* [object-fit-images](https://github.com/fregante/object-fit-images) - 🗻 Polyfill object-fit and object-position on images on IE9, IE10, IE11, Edge, Safari, ...
* [supports-webp](https://github.com/fregante/supports-webp) - Instantly detect support for WEBP images in the browser in 0.2KB
* [image-promise](https://github.com/fregante/image-promise) - 🌄 Load an image and return a promise in the browser, in 0.3KB, no dependencies
* [get-media-size](https://github.com/fregante/get-media-size) - Get the real size of an (already-loaded) `<img>`, `<video>`, or `<canvas>` in the browser.
* [get-canvas-pixel-color](https://github.com/fregante/get-canvas-pixel-color) - Micro module to get the color of a single pixel on a HTML canvas
* [animate-prop](https://github.com/fregante/animate-prop) - Single, dependency-free function to tween a property. Use that on canvas or anywhere else.

### DOM modules

* [doma](https://github.com/fregante/doma) - Parse an HTML string into `DocumentFragment` or one `Element`, in a few bytes
* [select-dom](https://github.com/fregante/select-dom) - Slim alternative to document.querySelector/All
* [delegate-it](https://github.com/fregante/delegate-it) - DOM event delegation, in <1KB
* [on-off](https://github.com/fregante/on-off) - Add/remove DOM events
* [one-event](https://github.com/fregante/one-event) - Micro module to add an event listener to be executed only once
* [get-scroll](https://github.com/fregante/get-scroll) - Micro module to get the scroll position (top or left) in the browser
* [get-elements-array](https://github.com/fregante/get-elements-array) - Array of elements from selector, Array-like objects and single elements.
* [filter-altered-clicks](https://github.com/fregante/filter-altered-clicks) - Filter alt-click, ctrl-click, shift-click, middle click, ...
* [visibility-change-ponyfill](https://github.com/fregante/visibility-change-ponyfill) - A more reliable visibilitychange event that works in more mobile WebViews
* [gsap-then](https://github.com/fregante/gsap-then) - Make every GSAP Tween a promise. tl.then(doSomething)
* [indent-textarea](https://github.com/fregante/indent-textarea) - Add editor-like tab-to-indent functionality to `<textarea>`, in a few bytes
* [fit-textarea](https://github.com/fregante/fit-textarea) - Automatically expand a `<textarea>` to fit its content, in a few bytes

### Network modules

* [nano-fetch](https://github.com/fregante/nano-fetch) - A tiny window.fetch-like promise-based AJAX implementation.
* [tiny-load-script](https://github.com/fregante/tiny-load-script) - Load a javascript file and forget about it
* [facebook-sdk-promise](https://github.com/fregante/facebook-sdk-promise) - Load Facebook's API and return a Promise. If it's already loading it won't try to load it again.
* [facebook-handshake](https://github.com/fregante/facebook-handshake) - Seamlessly log into Facebook silently, with a popup or with a redirect on unsupported browsers (Chrome/iOS)

### Utility modules

* [many-keys-map](https://github.com/fregante/many-keys-map) - A Map subclass with support for multiple keys for one entry
* [prevent-popstate-scroll](https://github.com/fregante/prevent-popstate-scroll) - Prevent the scroll restoration caused by the popstate event or back/forward buttons.
* [scroll-restoration-polyfill](https://github.com/fregante/scroll-restoration-polyfill) - Polyfill for the "History API: Scroll Restoration"
* [console-class](https://github.com/fregante/console-class) - Get yourself a light, togglable, namespaced and colored console.log in the browser
* [intervalometer](https://github.com/fregante/intervalometer) - Call a function at every frame or every X ms. With start/stop.
* [intrinsic-scale](https://github.com/fregante/intrinsic-scale) - Replicate `background-size: cover/contain` for canvas/CSS/Node/… on any type of media.
* [poor-mans-symbol](https://github.com/fregante/poor-mans-symbol) - Poor man's Symbol implementation, not compliant. Uses window.Symbol if present
* [random-encoder](https://github.com/fregante/random-encoder) - Lightweight way to generate multiple, random, reversible "hashes" or encoding
* [pet-names](https://github.com/fregante/pet-names) - &#128145; Get popular pet names (for girlfriends and boyfriends)
* [shorten-repo-url](https://github.com/fregante/shorten-repo-url) - Shorten GitHub links like GitHub shortens Issues and Commit links.
* [list-github-dir-content](https://github.com/fregante/list-github-dir-content) - List all the files in a GitHub repo’s directory
* [tiny-version-compare](https://github.com/fregante/tiny-version-compare) - Compare two software versions, with any number of points (<1KB)

## Node-only modules

* [tumblr-upload](https://github.com/fregante/tumblr-upload) - 🚡 Upload your Tumblr theme via node or CLI
* [bin-dir](https://github.com/fregante/bin-dir) - Find or open the folder of a global command (installed via npm or not)
* [npm-bundler](https://github.com/fregante/npm-bundler) - Opinionated ES6 library bundler based on rollup-babel-lib-bundler. For my own modules, but maybe you can find it useful too.
* [rollup-config-webext](https://github.com/fregante/webext-inject-on-install) - Suggested configuration to bundle files in browser extensions.

## Modules for browser extensions

* [webext-options-sync](https://github.com/fregante/webext-options-sync) - Helps you manage and autosave your extension's options.
* [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) - Automatically inject your `content_scripts` on custom domains.
* [webext-content-script-ping](https://github.com/fregante/webext-content-script-ping) - One-file interface to detect whether your content script have loaded.
* [webext-inject-on-install](https://github.com/fregante/webext-inject-on-install) - Automatically add content scripts to existing tabs when your extension is installed.
* [webext-domain-permission-toggle](https://github.com/fregante/webext-domain-permission-toggle) - Browser-action context menu to request permission for the current tab.

## Browser extensions

* [GhostText](https://github.com/GhostText/GhostText) - :ghost: Use your text editor to write in your browser. Everything you type in the editor will be instantly updated in the browser (and vice versa).
* [GitHub Issue Link Status](https://github.com/fregante/github-issue-link-status) - Colorize issue and PR links to see their status (open, closed, merged)
* [npmhub](https://github.com/npmhub/npmhub/) - :mag_right: A browser extension for exploring npm dependencies on GitHub repos.
* [One Click Extension Manager](https://github.com/HangYang/ext_manager) - Simple Chrome extension to manage your Chrome extensions.
* [Refined GitHub](https://github.com/sindresorhus/refined-github/) - Simplifies the GitHub interface and adds useful features.
* [GitHub Clean Feed](https://github.com/fregante/github-clean-feed) - Group GitHub news feed by repo.
* [sticky-pinned-tabs](https://github.com/fregante/sticky-pinned-tabs) - Chrome Extension: When in a pinned tab, external links open in a new tab
* [gstocks](https://github.com/fregante/gstocks) - Chrome extension + bookmarklet
* [browser-player](https://github.com/fregante/browser-player) - 🔈 Chrome extension: pause other tabs when you play something

## Web tools

Unpolished and undocumented, though

* [regallery.ga](https://github.com/fregante/regallery.ga) - Paste a Reddit post URL, get a gallery of each comment's image. Perfect for /r/photoshopbattles.
* [index-github-bot](https://github.com/fregante/index-github-bot) - Bot that reminds me to add my new repos to my index.
* [Sapere.it-Mobile](https://github.com/fregante/Sapere.it-Mobile) - Italian Dictionary
* [HTML-Slayer](https://github.com/fregante/HTML-Slayer) - Trim images/layers and position them in HTML+CSS automatically
* [art-cropper](https://github.com/fregante/art-cropper) - Drop images, export art-directed cropped images

## Extras

* [Awesome-WebExtensions](https://github.com/fregante/Awesome-WebExtensions) - A curated list of awesome resources for Web Extensions development
* [github-desktop-open-in-sublime-text](https://github.com/fregante/github-desktop-open-in-sublime-text) - In GitHub Desktop on Mac, replace "Open in Atom" with Sublime Text
* [rollup-config-es6-browser](https://github.com/fregante/rollup-config-es6-browser)
* [rollup-config-buble](https://github.com/fregante/rollup-config-buble)

## Personal stuff

* [currency-slider](https://github.com/fregante/currency-slider) - A personal app to quickly convert currency. Not automatically updated
* [MovieList](https://github.com/fregante/MovieList) - Built with Meteor: A multi-user movie list with comments
* [hotelteti.com](https://github.com/fregante/hotelteti.com) - Jekyll website, wip
