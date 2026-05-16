# BiPP – Binary Parser in Python

The Binary Parser in Python is constructed around text files (```.bip```) defining a binary data format in several columns, simplifying the packing and unpacking of binary data files. The translation from and into binary data can be done with the help of python's ```struct``` module.

## List of Columns specifying Binary Data

    - Signedness
    - Datatype
    - Variable Name
    - ...

The columns should be spaced by tabulators or other whitespace.
One or multiple lines of a columns can be expanded by "macro-style" expressions with a consecutive number.

That is a free specification, that I have given to the project. As far as the actual parsing action is concerned, I am now working on it in some example scripts.

## Features

 - JSON-style data and Python dictionaries should be convertible into binary data and vice-versa, provided the appropriate ```.bip```-file.
 - A structured and annotated graph-style visualisation of the _language_ reading and writing bytes in the form of a finite automaton can be generated (e.g. as plain-text or ```pdf```-file).
 - A language can be defined interchangably by regular expresssions.

## Licensing and Contribution

This is an educational project for myself, simplifying my life in reading/writing binary data. Feel free to contribute to it and make use of it for your own convenience!

Licensed under the GNU Affero General Public License v3.0.
Commercial use is allowed, but source code and modifications must remain available under the same license, including for networked services.
