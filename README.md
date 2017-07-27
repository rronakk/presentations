# presentations
Ability to create presenation in browser using [remark.js](https://github.com/gnab/remark) and [mark-down-to-slides](https://github.com/partageit/markdown-to-slides)

## Install

```
$ npm install markdown-to-slides -g
```

## Usage

```
$ markdown-to-slides my-file.md -o slideshow.html
```
### options
```
--title, -t          Generated page title
--style, -s          Path to custom stylesheet
--script, -j         Path to custom javascript
--template, -l       Path to custom mustache template
--help, -h           This screen
--output-file, -o    Path to output file (stdout if not specified)
--document-mode, -d  Generate slides from a document without slide separators (---) or annotations
--watch, -w          Watch mode
--level              Heading level to use as new slides (for example 3 is ###)
--include-remark -i  Include Remark sources (around 850kB) into the generated document
```
