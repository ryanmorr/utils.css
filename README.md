# utils.css

[![Version Badge][version-image]][project-url]
[![License][license-image]][license-url]

> A collection of unopinionated and modular CSS utility classes

## Install

Download [utils.css](https://github.com/ryanmorr/utils.css/raw/master/utils.min.css) directly or install via NPM:

```sh
npm install @ryanmorr/utils.css
```

## Features

The following is a collection of over two dozen utility classes for alignment, visibility, text, and other purposes. This is not [Atomic CSS](https://css-tricks.com/lets-define-exactly-atomic-css/), but rather focuses on common helpers that add functionality beyond single-purpose classes scoped to one specific CSS property. All the utilities are wrapped in a CSS layer called `utils` for easy control of specificity and adding your own additional custom utilities. Theses classes are unopinionated and modular rulesets, making them easily adopted (individually or collectively) into any project.

> [!NOTE]
> For class names, the word "center" refers to horizontal alignment and the word "middle" refers to vertical alignment.

<table>
    <tr>
        <td width="250"><b>Class</b></td>
        <td><b>Description</b></td>
    </tr>
    <tr>
        <td><code>u-align-center</code></td>
        <td>Center an element horizontally within its container</td>
    </tr>
    <tr>
        <td><code>u-align-middle</code></td>
        <td>Center an element vertically within its container</td>
    </tr>
    <tr>
        <td><code>u-align-middle-center</code></td>
        <td>Center an element horizontally and vertically within its container</td>
    </tr>
    <tr>
        <td><code>u-align-abs-top-left</code></td>
        <td>Align an absolutely positioned element to the top-left</td>
    </tr>
    <tr>
        <td><code>u-align-abs-top-center</code></td>
        <td>Align an absolutely positioned element to the top-center</td>
    </tr>
    <tr>
        <td><code>u-align-abs-top-right</code></td>
        <td>Align an absolutely positioned element to the top-right</td>
    </tr>
    <tr>
        <td><code>u-align-abs-middle-left</code></td>
        <td>Align an absolutely positioned element to the middle-left</td>
    </tr>
    <tr>
        <td><code>u-align-abs-middle-center</code></td>
        <td>Align an absolutely positioned element to the middle-center</td>
    </tr>
    <tr>
        <td><code>u-align-abs-middle-right</code></td>
        <td>Align an absolutely positioned element to the middle-right</td>
    </tr>
    <tr>
        <td><code>u-align-abs-bottom-left</code></td>
        <td>Align an absolutely positioned element to the bottom-left</td>
    </tr>
    <tr>
        <td><code>u-align-abs-bottom-center</code></td>
        <td>Align an absolutely positioned element to the bottom-center</td>
    </tr>
    <tr>
        <td><code>u-align-abs-bottom-right</code></td>
        <td>Align an absolutely positioned element to the bottom-right</td>
    </tr>
    <tr>
        <td><code>u-align-self-top-left</code></td>
        <td>Align an element to the top-left within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-top-center</code></td>
        <td>Align an element to the top-center within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-top-right</code></td>
        <td>Align an element to the top-right within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-middle-left</code></td>
        <td>Align an element to the middle-left within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-middle-center</code></td>
        <td>Align an element to the middle-center within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-middle-right</code></td>
        <td>Align an element to the middle-right within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-bottom-left</code></td>
        <td>Align an element to the bottom-left within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-bottom-center</code></td>
        <td>Align an element to the bottom-center within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-align-self-bottom-right</code></td>
        <td>Align an element to the bottom-right within a flex or grid container</td>
    </tr>
    <tr>
        <td><code>u-hide-text</code></td>
        <td>Hide image caption but remain available to screen readers and search engines</td>
    </tr>
    <tr>
        <td><code>u-responsive-media</code></td>
        <td>Make a media element responsive while maintaining aspect ratio</td>
    </tr>
    <tr>
        <td><code>u-text-truncate</code></td>
        <td>Prevent text from wrapping and truncate with an ellipsis</td>
    </tr>
    <tr>
        <td><code>u-text-clip</code></td>
        <td>Prevent text from wrapping and truncate with a hard clip</td>
    </tr>
    <tr>
        <td><code>u-text-break</code></td>
        <td>Break words when their length exceeds the width of their container</td>
    </tr>
    <tr>
        <td><code>u-hidden</code></td>
        <td>Hide an element visually and from screen readers</td>
    </tr>
    <tr>
        <td><code>u-offscreen</code></td>
        <td>Hide an element visually, but maintain its layout offscreen</td>
    </tr>
    <tr>
        <td><code>u-visually-hidden</code></td>
        <td>Hide an element visually, but remain accessible to screen readers</td>
    </tr>
    <tr>
        <td><code>u-visually-hidden-focusable</code></td>
        <td>Identical to <code>u-hidden-accessible</code>, but will be visible if focused</td>
    </tr>
    <tr>
        <td><code>u-disabled</code></td>
        <td>Prevent all user interactions and default browser behavior</td>
    </tr>
    <tr>
        <td><code>u-scrollable</code></td>
        <td>Create a scrollable container with enhanced behavior</td>
    </tr>
</table>

## License

This project is dedicated to the public domain as described by the [Unlicense](http://unlicense.org/).

[project-url]: https://github.com/ryanmorr/utils.css
[version-image]: https://img.shields.io/github/package-json/v/ryanmorr/utils.css?color=blue&style=flat-square
[license-image]: https://img.shields.io/github/license/ryanmorr/util.css?color=blue&style=flat-square
[license-url]: UNLICENSE
