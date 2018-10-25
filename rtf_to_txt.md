Bundle RTF to TXT converting using Mac Terminal
=====

To convert all the RTF files in a directory to TXT use this command: 

> find . -name 'directory'\\*.rtf -print0 | xargs -0 textutil -convert txt

* Instead of 'directory' type your path to the files (for example, \Users\Macintosh\Documents\new_folder\*.rtf)
* Make sure there're backsplashes in the directory path (\\)
* \\* means that all the files in the directory will be converted
* If you need to convert one file, type it's full name (for example, \Users\Macintosh\Documents\new_folder\myfile.rtf)
