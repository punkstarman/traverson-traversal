[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/traverson/traverson-traversal)

# &lt;traverson-traversal&gt;

This web component makes it easy to traverse RESTful APIs.

It is based on the amazing [Traverson library](https://github.com/basti1302/traverson).

## Install

Install the component using [Bower](http://bower.io/):

```bash
$ bower install traverson-traversal --save
```

## Usage

Import Web Components polyfill:

```js
<script src="/bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

Import Traverson Traversal Element:

```html
<link rel="import" href="/bower_components/traverson-traversal/traverson-traversal.html"> 
```

Use it!:

```html
<traverson-traversal
    auto
    from="http://example.org/api"
    follow="['link_to', 'resource']"
    last-response="{{document}}">
</traverson-traversal>

<p>{{document}}</p>
```
