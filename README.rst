========
packages
========

This repository contains some ArchLinux packages I had to customize in order to
work with my system.

vim
===

Using Unite_ on large projects, vim is randomly doing long freezes caused by the garbage
collector (see Unite `issue 798`_, or the `official bug report`_ on vim_dev list).

So this is the official ArhLinux vim package with the `suggested patch`_ applied to it.

.. _Unite: https://github.com/Shougo/unite.vim
.. _issue 798: https://github.com/Shougo/unite.vim/issues/798
.. _official bug report: https://groups.google.com/forum/#!searchin/vim_dev/GC/vim_dev/DBYOdHQWvqY/1WH04_dwETIJ
.. _suggested patch: https://gist.github.com/mattn/0c58a7398c63ab4c3066
