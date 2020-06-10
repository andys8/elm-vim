# ~~vim-elm-syntax~~ (deprecated in favour of [Vim](https://github.com/vim/vim/blob/master/runtime/syntax/elm.vim))

`vim-elm-syntax` _only_ provides syntax highlighting. Other functionality (like compiling code) is provided by [`elm-language-server`](https://github.com/elm-tooling/elm-language-server).

## Important: Elm Syntax is included in Vim

Starting with Vim 8.2 patch 929 `Elm` syntax is **part of `Vim`**. No need to install this plugin. If you use an older version you can still use this plugin.

- <https://github.com/vim/vim/blob/master/runtime/ftplugin/elm.vim>
- <https://github.com/vim/vim/blob/master/runtime/syntax/elm.vim>

## Features

1. Syntax highlighting
1. Automatic indentation

### Missing features

Compiling, linting, formatting and other features aren't included in this plugin.
Have a look at [elm-tooling/elm-vim](https://github.com/elm-tooling/elm-vim) for general instructions how to setup Vim with Elm.

## Installation

- **Vim-Plug** (recommended): `Plug 'andys8/vim-elm-syntax'`and run `:PlugInstall`
- Vundle: `Plugin 'andys8/vim-elm-syntax'`
- NeoBundle: `NeoBundle 'andys8/vim-elm-syntax'`
- Pathogen: `cd ~/.vim/bundle && git clone https://github.com/andys8/vim-elm-syntax`
- Vim 8+: `git clone --depth 1 https://github.com/andys8/vim-elm-syntax.git ~/.vim/pack/git-plugins/start/vim-elm-syntax`

### Note about vim-polyglot

If you are using [vim-polyglot](https://github.com/sheerun/vim-polyglot), you need to disable its default elm plugin by adding `let g:polyglot_disabled = ['elm']` to your config file.

## Credits

This repository is a fork of [`ElmCast/elm-vim`](https://github.com/ElmCast/elm-vim).
All credits go to the authors of this repository.

- Joseph Hager
- [Contributors](https://github.com/elmcast/elm-vim/graphs/contributors) of elm-vim
- Other vim-plugins, thanks for inspiration (elm.vim, ocaml.vim, haskell-vim)

## License

Copyright © Joseph Hager. See `LICENSE` for more details.
