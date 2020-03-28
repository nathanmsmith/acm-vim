# An Introduction to Vim

_For a UCLA student who has taken CS 31 and 32._

Based on material from [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/2020/editors/)

## Installing vim

We're going to be using a version of vim called neovim. Instructions to install it are [available here](https://github.com/neovim/neovim/wiki/Installing-Neovim). In general, we recommend using Chocolatey if you're on Windows, Homebrew if you're on macOS, and your default package manager if you're on Linux.

## A Brief History of Vim

Two Bit History covers the [history of Vim](https://twobithistory.org/2018/08/05/where-vim-came-from.html) more in depth.

## Ideas of vim

Vim is a modal text editor: as the name implies, Vim is in different modes when inserting/editing/selecting text.

The most common modes of Vim are:

- Normal: for moving around a file and making edits
- Insert: for inserting text
- Visual (plain, line, or block) mode: for selecting blocks of text

Keys have different meanings in different modes. For example, the `x` in insert mode will just insert a literal character ‘x’, but in normal mode, it will delete the character under the cursor, and in visual mode, it will delete the selection.

Vim shows the mode it is in in the bottom left corner of the screen. By default, it is in normal mode.


## vimtutor

The de facto introduction to vim is via an interactive tutorial called vimtutor. You can access it by opening Neovim:

```
nvim
```

then typing: `:Tutor`.

## A note on CTRL and ESC

vi was originally developed on a ADM-3A computer, which had the following layout.


Note that the Ctrl key is where the caps lock key usually is and the Escape key is right above it! Typing esc or ctrl was much more ergonomic back in the good ol' vi days than it is now. Because of this, many people remap either esc or ctrl to their caps lock key. We recommend you play around with this.

https://stevelosh.com/blog/2012/10/a-modern-space-cadet/#s13-control-escape


## Where to go after vimtutor

- https://www.moolenaar.net/habits.html
- :h
- http://vimcasts.org/
- https://sanctum.geek.nz/arabesque/vim-koans/

### Plugins

[VimAwesome](https://vimawesome.com/) is a great list of plugins.

- minpac
- ALE
- FZF
- vim-commentary
- vim-surround
- vim-fugitive
- NERDTree
- vim-gitgutter
- vim-airline







