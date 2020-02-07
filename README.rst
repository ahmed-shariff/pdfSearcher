***********
pdf-searcher
***********
This cli tools allows you to search for phrases in your pdf files.

Installation
------------
::

  pip install pdfsearcher

Usage
-----
The first argument taken is a regular expression, that is being searcher for. For the remining arguments, you can pass either a set of files or directories. At the end, the list of files which have a match for the regular expression passed will be listed out.
::

  pdf-searcher "\btest\b" test.pdf test2.pdf pdf-directory/pdf-sub-directory

Wishlist/todo:
--------------
* Optimizations (cache)
* Support for wildcards in path names
