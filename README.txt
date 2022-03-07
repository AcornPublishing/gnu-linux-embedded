Chapter2 and Chapter 18 do not have code files.


If you want to learn how to use embedded machine learning capabilities and get access to a
GNU/Linux device driver to collect data from a peripheral or to control a device, this book
is for you.
If you are interested in knowing how to easily and quickly get access to different computer
peripherals in order to realize a functional control or monitor system based on GNU/Linux
for industrial applications, this book is for you.
If you have some hardware or electrical engineering experience and know the basics of C,
Bash, and Python and PHP programming in a UNIX environment and want using them
into an embedded system, this book is for you.

What you need for this book

Following are the requisites for efficient learning.

Software prerequisite

Regarding the software you should have a little knowledge of a non graphical text editor as
vi, emacs or nano. Even if you can connect an LCD display, a keyboard and a mouse
directly to embedded kits and then use the graphical interface, in this book we assume that
you is able to do little modifications to text files by using a text only editor.
The host computer, that is the computer you will use to cross-compile the code and/or to
manage your embedded systems, is assumed running a GNU/Linux based distribution. My
host PC is running an Ubuntu 15.10 but you can use also a newer Ubuntu Long Term
Support (LTS) or a Debian based system too with little modifications or you may use
another GNU/Linux distribution but with a little effort from you mainly regarding the
cross-compiling tools installation, libraries dependencies and packages management.
Foreign systems such as Windows, MacOS or similar are not covered by this book due the
fact you should not use low technology systems to develop code for high technology
system!
Knowing how a C compiler works and how to manage a Makefile is required.
This book will present some kernel programming techniques but these must cannot be
taken as a kernel programming course. You need a proper book for such topic! However each
example is well documented and you will find several suggested resources. Regarding the
kernel I'd like to state that the version used into this book is 4.4.x.

Hardware prerequisite

In this book all code is developed for BeagleBone Black board revision C, for SAMA5D3
Xplained revision A or for the WandBoard revision C1 (depending on the board used) but
you can use an older revision without any issues, in fact the code is portable and it should
work on other systems too (but the DTS files whose must be considered apart)!
Regarding the computer peripherals used in this book I reported in each chapter where I
got the hardware and where you can buy it but, of course, you can decide to surf the
Internet in order to find a better and cheaper offer. A note where to find the datasheet is
also present.
You should not have any difficulties in order to connect the hardware presented in this
book with the embedded kits since the connections are very simple and well documented.
They don't require any particular hardware skills to be performed from you (apart knowing
how to use a solder), however having a minor knowledge in electronics may help.
