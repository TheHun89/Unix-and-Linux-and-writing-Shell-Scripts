# Unix and Linux and writing Shell Scripts

* [Tutorialspoint - Unix/Linux Tutorial](https://www.tutorialspoint.com/unix/index.htm)
* [LinuxCommand.org](http://linuxcommand.org/)

![Unix Architecture](https://www.tutorialspoint.com/unix/images/unix_architecture.jpg)

A kernel is the core bit of the operating system. It’s the kernel that allocates resources, manages access to the hardware, determines how security works, shuttles messages between different bits of the system, and determines how much processor time a program gets before it needs to let another program have some. Software communicates with the kernel internally, but a user doesn’t directly interact with the kernel.

UNIX is a trademark and a standard for operating systems. Any operating system that adheres to the UNIX specification (a bunch of documents that describe how a UNIX operating system works) can apply to be certified as a UNIX operating system. AIX, OS X/macOS, HP/UX, Solaris, etc. are all UNIX operating systems. The specification describes how filesystems are handled, how security works, the feature required for filesystems, the features required to be present in the kernel, a baseline of software utilities that must be present, etc.

Bash is the the Bourne Again Shell. It was written by a guy named Brian Fox as a replacement for the Bourne Shell (written by Stephen Bourne of Bell Labs in 1977, on UNIX systems it is /bin/sh). A shell is a program that provides a prompt where it reads and runs commands. Generally speaking, the command is the name of an executable file (program) followed by some text that’s options passed to that program. Most shells, including bash, have features that let you set and use variables, define subroutines, and do some sort of flow control (make conditional statements and loops). While fairly simplistic, a shell is enough to write fairly complex scripts, or text files with text commands that does something. Bash is a superset of the Bourne Shell, having the same syntax and features, and then adding some additional features.

The OS X Terminal is a terminal emulator program. It’s a GUI application that presents a text box that behaves like an old-fashioned text terminal. It can run any program, but generally it’s some sort of shell (like bash) that accepts typed in commands. The app allows you to fiddle with the appearance of the window, the fonts, and it provides cut-and-paste and scrolling features (on top of whatever the programs you run in it do).


* [Youtube - BASH Shell Scripting Tutorial](https://youtu.be/hwrnmQumtPw)
* [jq - lightweight and flexible command-line JSON processor](https://stedolan.github.io/jq/)
