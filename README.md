A quick way to convert lots of gib files to sgf, provided you are not that attached to all the metadata

Useage:

should work with python 3+

python translate.py A B 

A : path to folder with .gib files
B : path to write folder with .sgf files

It can operate on a nested directory of .gib files and recreate the directory structure in the write folder.
For the individual records it will record the names of the players and all the moves and drop everything else.

