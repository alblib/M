# M
The M Language is a multi-layer free software for Mathematical use. One of the motivations is to replace Mathematica, but also we are aiming for better experience for various application. The basic structure of the M language should be:
* Full-featured C/C++ Library
* The M Compiler on every platform, which requires:
  * The M Syntax,
  * M to C++ Interpreter,
  * and C++ compiler included to provide complete compile.
* The M script, an app which can run real-time script on any platform (just like Mathematica).
* M Package, which is an M script package and can run on compiler-prohibited environments like mobile platform.
* The M Document, which 
  * is a output format of M Package,
  * and also is a replacement of PDF and TeX, so provides real-time calculation output to documents, and interactive documents.
  * is part of M Package interface and should provide document viewer for web browser, desktop, and mobile, with paper-printing ability.
  * should provide TeX <-> M Document conversion for time period.
