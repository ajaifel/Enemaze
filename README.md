# Enemaze #

This is an example C++ application using the SDL library.
It tries to be as nicely C++11 as possible but do keep in
mind that SDL is written in C and, at some stage, you have
to interface with it.

## Story ##
As a family with a long standing history of maze building
it was little surprise that you've been summoned to the
kings court on a matter of grave mazeness. When you arrive
you find the royal mazes filled with defenseless protesters.
Better clear them off with guns, to be sure.

## Installation ##
You will have to have the SDL development libraries installed on
your system.  The easiest way to compile is to use a command-line

```bash
$ g++ -c -std=c++11 src/*.cpp
$ g++ -o enemaze *.o -lSDL2 -lSDL2_image
```

which will produce an executable file called "enemaze" in the
top-level directory.  To execute this file do the following

`$ ./enemaze`
 
from the top-level directory.  The game will expect to find the
`assets` directory under its current working directory.

## Credits ##
The sprites in this game come directly from 
[SpriteLib](http://www.widgetworx.com/widgetworx/portfolio/spritelib.html) and are used
under the terms of the [CPL 1.0](http://opensource.org/licenses/cpl1.0.php).
Aiden Delaney who gave the starting code.
