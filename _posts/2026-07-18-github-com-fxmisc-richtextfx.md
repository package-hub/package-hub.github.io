---
title: RichTextFX
categories: ['java', 'javafx', 'rich-text-editor']
---
## [RichTextFX](https://github.com/FXMisc/RichTextFX)

### Rich-text area for JavaFX


`GenericStyledArea` allows one to inline custom objects into the area alongside of text. As such, it uses generics and functional programming to accomplish this task in a completely type-safe way.

It has the following parameter types:

 - `PS`, the paragraph style. This can be used for text alignment or setting the background color for the entire paragraph. A paragraph is either one line when text wrap is off or a long text displayed over multiple lines in a narrow viewport when text wrap is on.
 - `SEG`, the segment object. This specifies what immutable object to store in the model part of the area: text, hyperlinks, images, emojis, or any combination thereof.
 - `S`, the segment style. This can be used for text and object styling. Usually, this will be a CSS style or CSS style class.

Functional programming via lambdas specify how to apply styles, how to create a `Node` for a given segment, and how to operate on a given segment (e.g., getting its length, combining it with another segment, etc.).

`GenericStyledArea` is used in the [Rich-text demo](richtextfx-demos/README.md#rich-text-editor).

See the wiki for a basic pattern that one must follow to implement custom objects correctly.
