### 🐓 Prerequisites

* [Fira Code font](https://github.com/tonsky/FiraCode)
* [Script12 BT font](https://www.dafontfree.net/freefonts-script12-bt-f141942.htm)
* [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

### 🐖 styles.css

```css
.type.storage,
.type.storage.declaration,
.storage.class.modifier {
  font-family: "script12-bt";
  font-size: 1.7em;
}

.type.storage.arrow.function {
  font-family: "Fira Code";
}

.decorator.name,
.decorator.punctuation:not(.block),
.import.keyword {
  font-family: "script12-bt";
  font-size: 1.7em;
  color: #68f39b !important;
}
.attribute-name {
  font-family: "script12-bt";
  font-size: 1.5em;
}

.html.quoted.double {
  color: #a6f3a6 !important;
}
.comment {
  color: #c5c5fd !important;
}
.comment:not(.punctuation) {
  font-family: script12-bt;
  font-size: 1.5em;
}
```
