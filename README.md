# fandom-debloat-css
A tweak css for fandom I made a year ago. Allows you to debloat fandom and make the pages wider.

**Intended to be used with Ublock Origin.**

## Notable features:

* Wider page UI (while keeping the width toggle button functional)
* No wiki page bloat (Fan feed)
* No saerch bloat (suggested communities)
* No login buttons on the top of the page
* No anonymous fandom bar (ads)
* No fandom sidebar (now replaced with the account & notification button on the bottom corner of the page)
* No top results in search modal (risky for spoilers)
* Maintained code
* Etc...

# Screenshots

## Wiki page
* Before:

* After:

## Search page
* Before:

* After

# Install
## Method 1: Stylus (Recommended)
1. Install Stylus browser extension: [Chromium](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)/[Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

2. Open Stylus and select "manage". Then under the "Action" dropdown, select "Write new styles"

3. Paste the following in the code box:
```css
@import url(https://raw.githubusercontent.com/Poki-Pancake/fandom-debloat-css/main/fandom-debloat.css);
```

4. Under the code box, set the dropdown to "URLs on the domain" and add `fandom.com` as the domain

## Method 2: UserChrome.css (Firefox only)
TBA
