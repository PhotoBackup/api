# Server implementations
Here are some recommendations to write consistent server implementation
for PhotoBackup. Nothing is mandatory and everything can be discussed
and changed over time, feel free to discuss it!

## Configuration
Configuration file should be in a `.ini` format and called `~/.photobackup`,
with `~` the user's directory (small precision for Windows users).

# Commands
Configuration file should be created with:

    `photobackup init`

and PhotoBackup launched with:

    `photobackup run`

`docopt` is used for [Python](https://pypi.python.org/pypi/docopt/0.6.2)
and [NodeJS](https://www.npmjs.com/package/docopt) implementation,
sharing the same docstring.

# Packaging
Python implementation use [Python Package Index](https://pypi.python.org/pypi/photobackup_bottle/),
NodeJS implementation use [npm](),
you get the idea...
