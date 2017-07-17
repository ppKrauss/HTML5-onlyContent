HTML5-onlyContent
=================

HTML with only content, definition and conversion tools.

See also [HTML5 flow-content tags](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content) and [XHTML-print W3C standard](https://www.w3.org/TR/xhtml-print/) with [HTML5 polyglot suggestions](https://www.w3.org/TR/html-polyglot/), as reference model.

## Introduction ##
Many online tools with a "HTML upload" interface, offline softwares with "document loading", input modules of [Content Management Systems](https://en.wikipedia.org/wiki/Content_management_system), 
of [Document Management Systems (DMSs and old EDMs)](https://en.wikipedia.org/wiki/Document_management_system)... They supposed that user is sending full-text content in a whole HTML document (only relevant content are into the tag `body`). This is  because HTML is the "lingua franca" and the best way to do *content-interchange*.

So, in that context, HTML must be interpreted as "only content" (no text is about menus, sidebars, forms, Javascript, etc.). In that conetxt arises a HTML's DTD variant that can be named "SIMPLIFIED  HTML FOR NON-INTERACTIVE CONTENT", and for short, *HTML-OnlyContent*.
## Definition ##
A *formal definition* is under construction...

## Tools ##
Some transformation tools, compatible with the definition, are available. See ex. the simple XSLT `onlyContent-filter.xsl`.

Another usual (complex) task in this context is to transform all the CSS, and all `class` attributes, into `style` attributes (see. ex. [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) project); where the use of old `font` and `center`  tags, as well normalization of bolds and italics, can be accomplished.
