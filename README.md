# prism
This is a test of PRISM.js

The files `langs.js` and `langs.css` include support for the following languages:
1. `HTML` (including `SVG` and `XML`)
2. `CSS` (including `SASS` and `SCSS`)
3. `JavaScript` (including `React`)
4. `JSON`
5. `Python`

# Usage
First, link to these 2 files like so:
```
<link href="https://adir-sl.github.io/prism/langs.css" rel="stylesheet" />
<script src="https://adir-sl.github.io/prism/langs.js" />
```

Second, put the code you want to highlight inside a `code` tag that is inside a `pre` tag, this `pre` tag should have a class of `language-` and the desired language, for example `language-python`.