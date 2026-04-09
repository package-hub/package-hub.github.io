---
title: prism-react-renderer
categories: ['typescript', 'react', 'reactjs']
---
## [prism-react-renderer](https://github.com/FormidableLabs/prism-react-renderer)

### 🖌️ Renders highlighted Prism output to React (+ theming & vendored Prism)


Prism React Renderer powers syntax highlighting in the amazing [Docusaurus](https://docusaurus.io/) framework and many others.

This library tokenises code using Prism and provides a small render-props-driven
component to quickly render it out into React. This is why it even works with
React Native! It's bundled with a modified version of Prism that won't pollute
the global namespace and comes with
[a couple of common language syntaxes](./packages/generate-prism-languages/index.ts#L9-L23).

_(There's also an [escape-hatch](https://github.com/FormidableLabs/prism-react-renderer#prism) to use your own Prism setup, just in case)_

It also comes with its own [VSCode-like theming format](#theming), which means by default
you can easily drop in different themes, use the ones this library ships with, or
create new ones programmatically on the fly.

_(If you just want to use your Prism CSS-file themes, that's also no problem)_
