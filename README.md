# OldNBuggy
Gentoo overlay with old and buggy ebuilds :)

## dev-python/matplotlib
The current version has a bug on the Tk interface, which is not present on version 1.5.1.

## sys-power/bbswitch
The live ebuild does not compile because of an `if` statement. Here I just commented the whole statement out, and things appears to be working.

## www-client/qutebrowser
The live ebuild does not compile because the `.asciidoc` files were relocated to a `doc/` folder. Here I added a line to point to the correct location.
