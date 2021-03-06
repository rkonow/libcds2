LIBCDS 2 - A Compressed Data Structure Library
==============================================

Rationale
---------  
LIBCDS 2 is the re-coding of [LIBCDS][libcds1] with these goals:

 - 64-Bit support to allow for larger, single structures.
 - Speedups
 - Improve code readability
 - Include unit tests ([googletest][googtest])
 - Improve documentation

Further long-term goals include:

 - Introduce missing types to the library.
 - Provide packages for common GNU/Linux distributions, and other OSs.
 - Provide the option of installing it as a shared library (easing compilation and updates).
 - Wrappers for popular programming languages.


Links
-----  
Some useful project links are below:

 - [LIBCDS 2 GitHub project][gitproject]
 - [LIBCDS 2 Wiki][wiki]
 - [LIBCDS 2 Issues][issues]
 - [Original LIBCDS Site][libcds1]
 - [LIBCDS 2 Developers Google Group][devgroup]


Guidelines
----------  
 - In order to keep the repository clean, please do your development in the `develop` or `feature` branch.
   This way `master` should always be at a usable state. It may help to use [Git Flow][gitflow] for this
   (although it is unnecessary if you are familiar with [Git branching][gitbranch] - [Git Flow][gitflow]
   is just a helpful wrapper).

 - When you commit, it is useful to give a good message, please read this (short) guide on [Git commit messages][commitmsg].

 - The code tries to follow this style guide [C++ Style Guide][cppstyle].

 - Reviews are posted [here][reviews].

 - Before commiting or sending any code for review, please make sure you run all tests and 'make cpplint' to check for style errors.


[libcds1]: http://libcds.recoded.cl/
[devgroup]: http://groups.google.com/group/libcds-dev/
[googtest]: http://code.google.com/p/googletest/
[gitproject]: https://github.com/fclaude/libcds2
[cppstyle]: http://google-styleguide.googlecode.com/svn/trunk/cppguide.xml
[reviews]: http://reviews.recoded.cl/
[wiki]: https://github.com/fclaude/libcds2/wiki
[issues]: https://github.com/fclaude/libcds2/issues
[commitmsg]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[gitflow]: jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/
[gitbranch]: http://progit.org/book/ch3-0.html
