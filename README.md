dockerfile.vim
==============

Syntax highlighting for Dockerfiles
Forked from https://github.com/moby/moby/tree/master/contrib/syntax/vim because cloning 200+ MB doesn't make sense

Installation
------------
With [pathogen](https://github.com/tpope/vim-pathogen), the usual way...

With [Vundle](https://github.com/gmarik/Vundle.vim)

    Plugin 'moby/moby' , {'rtp': '/contrib/syntax/vim/'}

With [vim-plug](https://github.com/junegunn/vim-plug)

    Plug 'moby/moby' , {'rtp': '/contrib/syntax/vim/'}

Features
--------

The syntax highlighting includes:

* The directives (e.g. `FROM`)
* Strings
* Comments

License
-------

BSD, short and sweet
