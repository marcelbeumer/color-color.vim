color-color.vim
===============

Highlight colors in any source file with awesome toggling. Use:

        :ColorColorToggle

To go from this (in any file):

![Screen shot]()

To this:

![Screen shot]()

Toggle again to go back to normal. I map ColorColorToggle to Leader,Leader-c using:

        map <Leader><leader>c :ColorColorToggle<cr>

Credits
-------

This script is basically a hack on [Max Vasiliev's vim-css-color](https://github.com/skammer/vim-css-color), applying his code to any file, basing it on a VIM toggling command rather than a after/syntax, and adding a few tweaks to get the visuals right.
