# micromark

Hey folks! 👋 Welcome to micromark, a markdown parser under the
[unified collective][unified] that’s different.
(And just an idea, for now.)

## What’s micromark

**micromark** is a super low-level markdown parser in JavaScript. In nerdy terms, it’s a lexer 👩🏽‍🏫

<small>We’d also like this to be in typescript, to catch bugs, but also because we like the idea of WASM.</small>

### 💁🏽‍♀️ It is

*   [x] **small** in file size
*   [x] **tiny** in memory use
*   [x] **fast** in speed
*   [x] **safe** to use
*   [x] **compliant** to commonmark
*   [x] **extendible** to support gfm and mdx
*   [x] **complete** in that it’s possible to construct a CST

### 🤷🏽‍♀️ It could be

*   [ ] **streaming** (for big files, this has some complexity downsides, but it may be interesting)

### 🙅🏽‍♀️ It’s not

*   something that creates HTML and the like; other projects can use marydown for that
*   something that creates a syntax tree; remark will use micromark to do that


## 👯‍♀️ We need your help

We’d love to make micromark into reality, but we need your help.
Either through ideas, code contributions, or through [open collective][collective].

[unified]: https://github.com/unifiedjs/unified

[collective]: https://opencollective.com/unified