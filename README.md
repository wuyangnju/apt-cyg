apt-cyg
=======

A command-line package manager for Cygwin, simlary to apt-get and tracing back to https://code.google.com/p/apt-cyg/ with some recent bugs fixed. Usage examples:

* "apt-cyg install <package names>" to install packages
* "apt-cyg remove <package names>" to remove packages
* "apt-cyg update" to update setup.ini
* "apt-cyg show" to show installed packages
* "apt-cyg find <pattern(s)>" to find packages matching patterns
* "apt-cyg describe <pattern(s)>" to describe packages matching patterns
* "apt-cyg packageof <commands or files>" to locate parent packages

Quick start
-----------

apt-cyg is a simple script. Once you choose a copy from 64bit version or 32bit version, make it executable:

# chmod +x /bin/apt-cyg

Optionally place apt-cyg in a bin/ folder on your path.

Then use apt-cyg, for example:

# apt-cyg install nano

Contributing
------------

The original [Google Code project](https://code.google.com/p/apt-cyg/), which has been inactive for long, got some problems recently:

* Cygwin has distinguished 64bit version from 32bit version, and so does the repositories

* Some packages(like python) have started using xz as its compressor rather than bzip2

This re-publish has solved these problems. Please feel free to use directly or modify the code.
