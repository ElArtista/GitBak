GitBak
======

Introduction
------------
GitBak is a command line tool for batch cloning all the GitHub repositories of a given user written in Haskell

Features
--------
 * Packs the fetched repositories in gzipped tarballs
 * Can use GitHub API keys for bigger jobs

Building
--------
 1. Clone the project and cd to its directory.
 2. Run:  
    ```
    cabal sandbox init
    cabal install --only-dependencies
    cabal build
    ```
 3. Built binary will reside in the `dist\build\GitBak` subdirectory.

Usage
-----
 * See `gitbak --help` for options.

ChangeLog
---------
 * v0.0.1: Initial release

Contributing
------------
 * For bug fixes, any well checked pull requests are welcome

Credits
-------
Written and maintained by: 
* "Agorgianitis Loukas" <agorglouk@gmail.com>

Licensing
---------
Read [LICENSE](LICENSE.md)  

Copyright (C) 2015 Agorgianitis Loukas <agorglouk@gmail.com>  
All rights reserved.
