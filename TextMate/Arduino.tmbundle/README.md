Arduino TextMate Bundle - ino edition
============================
[TextMate](http://macromates.com) is the best editor in human history. [Arduino](http://arduino.cc) is the easiest embedded platform to dive into. Why don't the two work together? The Arduino TextMate Bundle solves that glaring error, and the universe is thus balanced.

There are other TextMate bundles out there, but they're mostly over two years old and don't work with new Arduino versions. This project aims to remain up-to-date and make embedded as enjoyable as everything else in TextMate.

The little 'a' in '1.0a' stands for 'alpha'. Read that as "might not work for you". It will grow and improve with time, but for now brace yourself for bugs. That means bug reports, feature requests and patches!

As of 1.0a, the bundle can compiles and uploads to the device, provides access to the documentation and highlights syntax correctly.

Installation
============
1. [Get the latest Arduino](http://arduino.cc/en/Guide/MacOSX). Version 1.0 and later is supported, and it must be installed to /Applications
2. [Get TextMate](http://macromates.com/).
3. install ino tool and configure it properly

Usage
=====
* **⌘U** Compiles and uploads your sketch to the connected Arduino
* **⌃⌥⌘H** Opens up local HTML documentation on to current word
* **Bundles > Arduino > Watch Serial Port** Opens a terminal window monitoring the serial port.
* **File > New From Template > Arduino > Basic Sketch** Creates a file with a blank basic sketch.

Shell Variables
===============
The compile/upload process can be finely controlled using TextMate's shell variables.

Textmate > Preferences > Advanced > Shell Variables

<table>
  <tr>
    <th>Variable</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>ARDUINO_SKETCH_HOME</td>
    <td>Indicates where the sketches will be created.</td>
  </tr>
 
