---
title: "Fix ArchWiki's awful styling"
date: 2023-09-02T21:02:26+05:30
# bookComments: false
# bookSearchExclude: false
---

By @x86asm_

Full fix (JS)
```js
const key = 'useskinversion';
const params = new URLSearchParams(window.location.search);
const version = params.get(key);
if (!version) {
  // replace makes redirect not reflected in the browser back history
  window.location.replace(`${window.location.href}?${key}=1`);
}
```


Size fix (CSS)
```CSS
.skin--responsive, .mw-page-container, .mw-content-container, .mw-workspace-container, .mw-article-toolbar-container {
     max-width: none;
     margin-left: 0;
     margin-right: 0;
}
```

