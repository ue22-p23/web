---
celltoolbar: Slideshow
jupytext:
  cell_metadata_filter: all,-hidden,-heading_collapsed,-run_control,-trusted
  formats: md:myst
  notebook_metadata_filter: all,-language_info,-toc,-jupytext.text_representation.jupytext_version,-jupytext.text_representation.format_version
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: JavaScript (Node.js)
  language: javascript
  name: javascript
language_info:
  name: javascript
nbhosting:
  title: exo - calculator
---

Licence CC BY-NC-ND, Thierry Parmentelat

+++

# practice : a calculator

```{code-cell}
tools = require('../js/tools'); tools.init()
```

+++ {"slideshow": {"slide_type": "slide"}}

## assignement

start from this tutorial here
<https://www.freecodecamp.org/news/how-to-build-an-html-calculator-app-from-scratch-using-javascript-4454b8714b98/>

it comes [**with the html and css template**](https://codepen.io/zellwk/pen/pLgmGL)  
for a nice yet simple, calculator

the assignment is to write the **javascript companion** so that

* the device **actually does calculations**
* in a first step, ignore the '.' and just write an integer calculator

+++ {"slideshow": {"slide_type": "slide"}}

## what it should look like

```{code-cell}
---
slideshow:
  slide_type: ''
tags: [remove-input]
---
tools.sample_from_stem("../samples/46-calculator", {sources_show: false})
```
