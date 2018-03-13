# checkers2

## The Chinese Checkers implementation in C / GTK+2

This application is the original version of the upgraded GTK+3 project [checkers3](https://github.com/auxiliaire/checkers3) featuring GTK+2

## Why Chinese Checkers?

Because it's fun and implementing it provides a good insight into a language/toolkit.

## How to build

See [Automake](https://www.gnu.org/software/automake/manual/automake.html)

* `./autogen.sh`
* `make`
* `make install` (if you're enthusiastic enough)

## Cross-platform

The app was written on Linux but it supports other platforms as well like Windows or OSX. See [Other OS Support](https://wiki.gnome.org/Projects/GTK+#Other_OS_support) for details.

## Porting a GTK+2 app to GTK+3

This project comparing with its successor [checkers3](https://github.com/auxiliaire/checkers3) can provide some hints about what needs to be changed in the code in order to make it work with GTK+3. Of course it's not a very sophisticated project so many gotchas necesseraly left out, but the basics seems to be covered.

## Old features

This version was written about ten years ago and never really finished (although working as a game). It lacks the features intended for Gnome3 "integration".
