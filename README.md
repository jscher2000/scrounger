# scrounger
Session History Scrounger for Firefox

_Note: The following new repository may update more promptly than this one:_ https://github.com/jscher2000/Firefox-File-Utilities

This script decompresses LZ4-compressed session history files such as recovery.jsonlz4. It can extract URLs from a variety of session history files without requiring valid JSON (it splits on various text strings).

From https://www.jeffersonscher.com/res/scrounger.html 

* lz4.js Copyright 2014 Pierre Curto from https://github.com/pierrec/node-lz4/tree/master/build
* FileSaver.min.js Copyright 2016 Eli Grey from https://github.com/eligrey/FileSaver.js/tree/1.3.2
