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

```{code-cell}
tools = require('../js/tools'); tools.init()
```

# practice : a calculator

````{admonition} calculator:
we give you the html and css, you have to write the JS:  
see on github here: <https://github.com/ue22-p23/web-calculator>

here's what it should look like
````

```{code-cell}
---
slideshow:
  slide_type: ''
tags: [remove-input]
---
tools.sample_from_stem("../samples/46-calculator", {sources_show: false})
```
