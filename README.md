# TIL

- 7 Sept: `tail -f` is awesome for watching log files, it automatically prints appended data to stdout
- 10 Sept: Setting "Key Repeat Rate" and "Delay Until Repeat", in the Mac keyboard settings, to the shortest possible values, makes Vim soo much nicer to use
- 11 Sept: `make` without any other arguments doesn't necessarily execute `make all`. It executes the first task of the Makefile. It's just the convention to put `all:` to the top
- 26 Sept: [gitsh](https://github.com/thoughtbot/gitsh) is a lot nicer than the [git-extras](https://github.com/tj/git-extras) repl
- 9 Nov: [mosh](http://mosh.org) is a great SSH replacement. It automatically reconnects after connection problems
- 26 Dec: `xargs` takes input from stdin, and passes it as a normal argument to another command. This is great for commands that ignore stdin, like `rm`. I always knew that `xargs` existed but finally took the time to see what exactly it actually does :)
- 7 Jan: `\FloatBarrier` lets LaTeX know that you want all previously defined figures to be rendered before this marker
- 9 Jan: The Vim command `gq` formats the selected text according to the Vim settings, e.g. it enforces `textwidth=80`. This is pretty nice for reformatting text
- 18 Jan: To enable viewing logging when in jupyter notebooks: `import logging; logging.getLogger().setLevel(logging.DEBUG)`
