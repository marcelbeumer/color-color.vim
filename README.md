color-color.vim
===============

Vim plugin to (toggle) highlight colors in any source. Use:

    :ColorColorToggle

To go from this (in any file):

![Normal](https://raw.github.com/marcelbeumer/color-color.vim/master/screenshots/normal.png)

To this:

![ColorColored](https://raw.github.com/marcelbeumer/color-color.vim/master/screenshots/colorcolored.png)

Toggle again to go back to normal. I map ColorColorToggle to Leader,Leader-c using:

    map <Leader><leader>c :ColorColorToggle<cr>

Install
-------

Either:

- Drop plugin/color-color.vim in ~/.vim/plugin/
- Or use [pathogen.vim](http://www.vim.org/scripts/script.php?script_id=2332)
- Or use the awesome [vundle](https://github.com/gmarik/vundle) plugin manager (recommended)

Credits
-------

This script is basically a hack on [Max Vasiliev's vim-css-color](https://github.com/skammer/vim-css-color), applying his code to any filetype, basing it on a VIM toggling command rather than a after/syntax, and adding a few tweaks to get the visuals right.
