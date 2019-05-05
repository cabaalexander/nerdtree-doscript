# nerdtree-doscript

Creates an executable script file in the current directory

[![asciicast](https://asciinema.org/a/HdEibWvP1VGin0o2pHV7U6jm5.svg)](https://asciinema.org/a/HdEibWvP1VGin0o2pHV7U6jm5)

There are two ways to achieve this goal.

By using 👇

- NERDTreeMenu
- NERDTreeKeyMap

## Installation

With [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'cabaalexander/nerdtree-doscript'
```

## NERDTreeMenu

This adds a new item (`do a script (h)ere`) to the menu.

Example

```
NERDTree Menu. Use j/k/enter . or the shortcuts indicated
=========================================================
  (a)dd a childnode
  (m)ove the current node
  (d)elete the current node
  (c)opy the current node
  (l)ist the current node
> do a script (h)ere
```

## NERDTreeKeyMap

This is the mapping added `ds`, for creating a script with a few key stokes. Below
there is an example showing you your custom mappings (`Press (?) when
nerdtree is open`)

Example

```
" ----------------------------
" Custom mappings
" [c: Jump to prev git hunk
" ]c: Jump to next git hunk
" ds: Create an executable script <
```
