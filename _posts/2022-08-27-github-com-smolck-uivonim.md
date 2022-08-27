---
title: uivonim
categories: ['typescript', 'neovim', 'neovim-guis']
---
## [uivonim](https://github.com/smolck/uivonim)

### Fork of the Veonim Neovim GUI


- 100% compatibility with Neovim (see [#9421](https://github.com/neovim/neovim/issues/9421))
- All configuration done via vimrc with vimscript/Lua/remote plugins
- GUI features and eyecandy
- Full support for international keyboard layouts and dead keys (tested on macOS and Linux)
- Fast, building upon the work done by @breja, with things like WebGL GPU
  rendering and multithreading
- Extensibility via a Lua API providing access to frontend GUI features such as
  [LSP hover/signature help/symbols](https://github.com/smolck/uivonim/wiki/Builtin-LSP) and a fuzzy finder UI
