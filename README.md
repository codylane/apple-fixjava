apple-fixjava
=============

A nice little helper utility to fix java on OSX after you install a new version of java on OSX.  This works for java 1.6, java 1.7 and apple java.

This attempts to fix the java plugin integration in your browser.  

This has been tested and works in the following browsers: Safari, Firefox and Chrome.

NOTE
====
If the java plugin already works in Safari this script will break that functionality. However, each time this script is run a copy of the original java plugin will be saved in /Library/Internet\ Plug-Ins/disabled/

You also need to make sure the correct version of java is installed.

USAGE
=====
To force manual version, you can do the following:

Java 1.6
========
fixjava 1.6

Java 1.7
========
fixjava 1.7

Apple Java
==========
fixjava apple-java

Show Program Usage
==================
fixjava help
