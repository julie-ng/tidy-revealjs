# tidy-revealjs

A custom theme and build system for reveal.js

### Theme

Theoretically it's enough to just take the CSS. Image preview:

## Build System

I love reveal.js for its ability to let me do slide with code directly in the browser and with markdown. Theming and slide management is however tricky. Moving slides means navigating yourself in a potentially large and nested DOM tree.

What if instead you just wrote markdown and the slides were automatically generated for you?

### File Structure Determines Presentation

When it comes to content, there is no `index.html` with slides. Instead, you create files inside the `slides` folder, which are loaded in alphabetical order.

### How to re-order slides

Because the slides are determined by alphabetical order, the easiest way to manage order of your slides is to prepend their filenames with numbers. For example, given:

| Slide Order | Example 1 | Example 2 |
|:--|:--|:--|
| 1 | hello | 1-cat |
| 2 | world | 2-apple |


### Vertical Slides

To create vertical chapters, just include a subfolder.


## Slide Types: HTML vs Markdown

### HTML Slides

- must have `<section>` as root tag.

### Markdown Slides

It is preferred to create slides using markdown. Just make sure they have the `.md` extension.

#### Applying fragments

Use the `.element`
