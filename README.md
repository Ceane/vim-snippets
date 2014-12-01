vim-snippets
==================

<img src="http://i.imgur.com/DnN4Wbi.gif" width="50%" />


A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/) library, forked from [justinj/vim-react-snippets](https://github.com/justinj/vim-react-snippets). This repo has been remixed  with the ES6 syntax, along with JSHint comments and licensing.

A direct port of the awesome snippets from 
[jgebhardt/sublime-react](https://github.com/jgebhardt/sublime-react).

Requires [vim-snipmate](https://github.com/garbas/vim-snipmate).

Installation
============

Use your preferred Vim plugin installation method.
I like [Vundle](http://github.com/gmarik/vundle), but other options like
[pathogen](https://github.com/tpope/vim-pathogen) should work fine as well.

If you're using Vundle, and you don't currently have SnipMate, you will need to
add the following to your `.vimrc` (taken from the [SnipMate README](https://github.com/garbas/vim-snipmate/blob/master/README.md)):

```
" vim-react-snippets:
Bundle "justinj/vim-react-snippets"

" SnipMate and its dependencies:
Bundle "MarcWeber/vim-addon-mw-utils"
Bundle "tomtom/tlib_vim"
Bundle "garbas/vim-snipmate"

" Other sets of snippets (optional):
Bundle "honza/vim-snippets"
```
