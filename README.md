# My personal manual pages #

## Introduction ##

This repository contains manual pages written in `groff (1)` for various
system utilities created by me. They are placed in `$HOME/.local/share/man`.

## Usage ##
To make them appear to `man (1)` just run `mandb` after cloning the repository
into the directory specified above.

If you wish to display them in some other way, run `groff -T ascii` or `groff -T pdf`.
In the latter case you may wish to redirect output to a file.
