This is a settings file for the Vim text editor. It has been tested on macOS and Ubuntu.

Installation
-------------------
`cd ~ && git clone git@github.com:ctriley/.vim.git`

`cd .vim && git submodule update --init --recursive`

In vim execute `:PluginInstall`

`cd ~/.vim/bundle/YouCompleteMe && python3 install.py --clangd-completer`

To add autocompletion for other languages see the YouCompleteMe documentation here:
https://github.com/ycm-core/YouCompleteMe


Author
-------------------
Connor Riley
