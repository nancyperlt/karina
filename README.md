# karina
Small editor for UTF-8 files with a GUI in different languages (extensible) and for different hardware and operating systems

About the license(s) read the file "COPYING"!

The main directory contains the source code as Lazarus project.
The folder "bin" contains compiled versions for different systems. Copy a compiled project to its target directory of your system. Then the executable file can be executed or will stop with messages that show you additional requirements. The compiled version might be older than the source code. You can compile the source code with Lazarus, if you want the most recent version.

You can open a file on the command line. In that case it is always necessary to initialize the language of Karina. For example, execute the command

karina -l en .gitignore

if you want to open the file .gitignore that is in the current directory.
