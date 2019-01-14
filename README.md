# minimal-ok-page

Sane defaults for simple pages with text.

Example: [open page](https://reo7sp.github.io/minimal-ok-page/) or [see raw html](https://raw.githubusercontent.com/reo7sp/minimal-ok-page/master/index.html).

<br>

CSS:
```css
body {
    font-family: sans-serif;
    font-size: 16px;
    color: #222222;
    margin: 16px;
}

p, ul, li {
    line-height: 1.6em;
}

p, ul {
    margin: 0.8em 0;
}

a {
    color: #0060a0;
    text-decoration: none;
    border-bottom: 1px solid rgba(0, 96, 160, 0.2);
}
a:hover {
    color: #d04000;
    border-bottom-color: rgba(208, 64, 0, 0.2);
}
h1 a {
    border-bottom-width: 2px;
}

img {
    max-width: 100%;
}

.site-container {
    max-width: 640px;
    margin: 4em auto 6em auto;
}
```
