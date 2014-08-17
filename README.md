#vim-lsdyna
[VIM](http://www.vim.org/) filetype plugin for [Ls-Dyna](http://www.lstc.com) FE solver.

What is Ls-Dyna filetype plugin? It's just bunch of scripts for VIM to speed up work with Ls-Dyna keyword file.

##Main features
- Syntax highlighting
- Folding
- Keyword library
- Useful commands, functions and mappings

###Syntax highlighting
With color syntax it's easier to navigate through a keyword file.

![vimLsDynaColorSyntax](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaColorSyntax.gif)

###Folding
Node & element table folding, no more never ending scrolling!

![vimLsDynaFold](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaFold.gif)

###Keyword library
With keyword library you can very quick add a new Ls-Dyna keyword into your model.

![vimLsDynaKeyLib](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaKeyLib.gif)

Visit [keyword library wiki page](https://github.com/gradzikb/vim-lsdyna/wiki/Keyword-Library) to see more.

###Curve commands
You can use commands to operate with curve data directly in VIM.

![vimLsDynaScale](https://raw.github.com/wiki/gradzikb/vim-lsdyna/screenshots/vimLsDynaScale.gif)

Visit [curve commands wiki page](https://github.com/gradzikb/vim-lsdyna/wiki/Curve-Commands) to meet all commands.

###Functions & mappings
The plugin has couple of useful functions to make your work even faster:
- [mappings](https://github.com/gradzikb/vim-lsdyna/wiki/Mappings) `:help lsdyna-mappings`
- comment/uncomment `:help lsdyna-comment`
- data line autoformating `:help lsdyna-autoFormat`
- text objects `:help lsdyna-textObject`
- include path `:help lsdyna-includePath`

##Installation

[Pathogen](https://github.com/tpope/vim-pathogen)

```
cd ~/.vim/bundle
git clone https://github.com/gradzikb/vim-lsdyna
```

##Documentation

List of all great features and detail information about them you will find in plugin documentation

`:help lsdyna`


Some examples how to use the plugin can be found on [wiki pages](https://github.com/gradzikb/vim-lsdyna/wiki).

##License

The GNU General Public License

Copyright &copy; 2014 Bartosz Gradzik
