# Notes and rationale

## HTML5 references

* "Palpable" elements as [DOM/palpable-content](https://www.w3.org/TR/html5/dom.html#palpable-content-0): all HTML5-onlyContent tags are palpable.

* Template: *"The template element is used to declare fragments of HTML that can be cloned and inserted in the document by script"*, so, as script-dependent, `template` tag is not in the HTML5-onlyContent tag set.

## xhtml-print selection

Tags selected from [xhtml-print 2010](https://www.w3.org/TR/xhtml-print/), that was an XHTML1 and HTML4 based standad.

> The XHTML-Print document type is defined as a set of XHTML modules. All XHTML modules are defined in the Modularization of XHTML specification [XHTMLMOD].

Selected modules by HTML5-onlyContent as reference-model:

* Structure Module: `body`, `head`, `html`, `title`.

* Text Module: `abbr`, `acronym`, `address`, `blockquote`, `br`, `cite`, `code`, `dfn`, `div`, `em`, `h1`, `h2`, `h3`, `h4`, `h5`, `h6`, `kbd`, `p`, `pre`, `q`, `samp`, `span`, `strong`, `var`.

* Hypertext Module:  `a`

* List Module: `dl`, `dt`, `dd`, `ol`, `ul`, `li`.

* Text Extension Module - Presentation: `b`, `big`, `hr`, `i`, `small`, `sub`, `sup`, `tt`

* Basic Tables Module: `caption`, `table`, `td`, `th`, `tr`

* Image Module: `img`

* Metainformation Module: `meta`

* Base Module: `base`

## Removed tags

See tags `nav`, `script`, `style`, etc.
