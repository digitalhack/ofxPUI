ofxPUI
==================

ofxPUI is an Open Frameworks addon for building user interfaces with the PUI c++ classes.  It has been tested on Windows but should run on Linux and Mac OS as well.

OpenFrameworks is a cross platform open source toolkit for creative coding in C++.

[http://www.openframeworks.cc/](http://www.openframeworks.cc/)

PUI: A Picoscopic User Interface - The Picoscopic User Interface (PUI - pronounced 'poohey') is a simple set of C++ classes that allow programs written in GLUT and OpenGL to create buttons, sliders, menus etc.

[http://plib.sourceforge.net/pui/index.html](http://plib.sourceforge.net/pui/index.html)

Installation
------------

To use ofxPUI, first you need to download and install Open Frameworks.

To get a copy of the repository you can download the source from [http://github.com/digitalhack/ofxPUI/zipball/master](http://github.com/digitalhack/ofxPUI/zipball/master) or, alternatively, you can use git clone:
<pre>
git clone git://github.com/digitalhack/ofxPUI.git
</pre>

The addon should sit in openFrameworks/addons/ofxPUI/.

Next you will need to download the source for PUI which is included with PLIB and can be downloaded from SourceForge at [http://sourceforge.net/projects/plib/](http://sourceforge.net/projects/plib/).

You will need to copy the following directories from the PLIB distribution: fnt, puAux, pui, sq and util to openFrameworks/addons/ofxPUI/src/.

Files from openFrameworks/addons/ofxPUI/src/ should be recursively added to you openFrameworks project with the src, fnt, puAux, pui, sq and util directories added to the Compiler include path.

ofxPUIexample.cbp is a Windows Codeblock's project that should compile the example project.
