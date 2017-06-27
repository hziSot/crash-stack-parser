crash-stack-parser
==================

Parser for obtaining functions' parameters from stack frames.

Crash tool 7.1.5, architecture x86_64

Obtain function parameters from stack frames

To build the module from the top-level crash-<version> directory, enter:

  $ wget https://github.com/hziSot/crash-stack-parser/blob/master/crash-parse-stack-7.1.5.patch

  $ patch -p1 < crash-parse-stack-7.1.5.patch

  $ make extensions
