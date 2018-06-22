[![Build Status](https://travis-ci.org/advanced-rest-client/api-url-data-model.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/dom-reorderer)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/advanced-rest-client/dom-reorderer)

# dom-reorderer

A list of arrangable items generated in Polymer's `dom-repeater`.

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="dom-reorderer.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<dom-reorderer>
  <template is="dom-repeat" items='["one", "two", "three", "four", "five"]'>
    <div>[[item]]</div>
  </template>
</dom-reorderer>
```

### API components

This component is a part of API components ecosystem: https://elements.advancedrestclient.com/
