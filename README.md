# apidock.vim #

This plugin allows you to browse [APIdock](http://apidock.com)'s Ruby, Rails, and RSpec docs
from within Vim.  It will invoke Firefox from the command line, and open the
query in a new tab.

## Installation ##

I recommend downloading the download link up above.  Once unzipped and/or
un-archived, you should have a directory holding a plugin/ directory and a doc/
directory.  Those correspond with ~/.vim/plugin and ~/.vim/doc respectively.
To be a bit more concise:

The file apidock.vim goes in ~/.vim/plugin, and the apidock.txt file belongs in ~/.vim/doc.  Be sure to run

    :helptags ~/.vim/doc

afterwards.

## Usage ##

* RR - Search the Rails docs for the word under the cursor.

* RB - Search the Ruby docs for the word under the cursor.

* RS - Search the RSpec docs for the word under the cursor.


This Vim plugin is mostly copied from the [AkitaOnRails](http://www.akitaonrails.com/) guys' [vimfiles on GitHub](http://github.com/akitaonrails/vimfiles/tree/master).  In particular, [this commit](http://github.com/fabiokung/vimfiles/commit/6723ec056282f4d2d66d214c921111f57fa48035) by Cassio Marques on January 10th, 2009.  I just added the RSpec function, the help docs, and then threw it up on GitHub.  However, do bug _me_ if something isn't working.

Consequently, this is another Vim plugin that I won't be sending to [Vim.org](http://vim.org), without the author's permission.
