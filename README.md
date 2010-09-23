Vim Syntax for YUI3
===================

This is a simple Vim syntax for YUI3 that's meant to augment Yi Zhao's javascript.vim syntax.

Installation
------------

1. Copy `after/syntax/javascript.vim` to your `~/.vim/after/syntax/` directory (create the directory if it doesn't exist).
2. If you aren't already using Yi Zhao's javascript.vim syntax, copy `syntax/javascript.vim` to your `~/.vim/syntax/` directory.

Contributing
------------

The YUI3 syntax is generated automatically by the `raw2syntax.rb` script from a YUIDoc `raw.json` data file. To modify the syntax, edit the `syntax.erb` template; don't edit the generated syntax file itself.

I know little about vim syntaxes, so this thing can probably be improved. Patches and feedback are very welcome.
