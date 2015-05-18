reap
====

**reap** stands for **REverse Argument Parse**,  a simple tool to
transform help-like strings of arguments into Python `argparse` codes.

Installation
------------

> In Progress :)

Usage
-----

Ideally, type `reap` in command line and follow the instructions.  
And you can simply add to some arguments like:
```
reap -i "[-h] [-f foo]" -o args.py
```
And related codes will be generated in `args.py`.  
You can also add to a file connected to the `-i` option, in which your
argument strings are stored.
```
reap -i argstr.txt -o args.py
```
Furthermore, you can leave an simple option `-pb` to copy the codes to
your pasteboard, simultaneously the codes will be displayed in the CLI
as well.
```
reap -i argstr.txt -pb
```
But, `-o` and `-pb` options are not mutually exclusive.  
A list of options:
```
-i, --input         The argument strings that will be executed
-o, --output        The file in which the codes will be stored
-pb, --pasteboard   Copy the codes to pasteboard
```
> Again, everything in progress ;D
