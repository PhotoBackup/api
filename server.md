# Server implementations
Here are some recommendations to write consistent server implementation
for PhotoBackup. Nothing is mandatory and everything can be discussed
and changed over time, feel free to discuss it with the authors!

## Configuration
Configuration file should be in a `.ini` formatted file called
`~/.photobackup`, with `~` the user's directory
(small precision for Windows users).

Default port is `8420`.

# Commands
Configuration file should be created with:

    photobackup init

and PhotoBackup launched with:

    photobackup run

`docopt` is used for [Python](https://pypi.python.org/pypi/docopt)
and [NodeJS](https://www.npmjs.com/package/docopt) implementations,
sharing the same docstring.

# Packaging
Python implementation use [Python Package Index](https://pypi.python.org/pypi/photobackup_bottle/)
and is installable with `pip install photobackup_bottle`,
NodeJS implementation use [npm](),
and is installable with `npm install photobackup`,
you get the idea...
