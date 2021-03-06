# TIL

## 2016

- 7 Sept: `tail -f` is awesome for watching log files, it automatically prints appended data to stdout
- 10 Sept: Setting "Key Repeat Rate" and "Delay Until Repeat", in the Mac keyboard settings, to the shortest possible values, makes Vim soo much nicer to use
- 11 Sept: `make` without any other arguments doesn't necessarily execute `make all`. It executes the first task of the Makefile. It's just the convention to put `all:` to the top
- 26 Sept: [gitsh](https://github.com/thoughtbot/gitsh) is a lot nicer than the [git-extras](https://github.com/tj/git-extras) repl
- 9 Nov: [mosh](http://mosh.org) is a great SSH replacement. It automatically reconnects after connection problems
- 26 Dec: `xargs` takes input from stdin, and passes it as a normal argument to another command. This is great for commands that ignore stdin, like `rm`. I always knew that `xargs` existed but finally took the time to see what exactly it actually does :)

## 2017

- 7 Jan: `\FloatBarrier` lets LaTeX know that you want all previously defined figures to be rendered before this marker
- 9 Jan: The Vim command `gq` formats the selected text according to the Vim settings, e.g. it enforces `textwidth=80`. This is pretty nice for reformatting text
- 18 Jan: To enable viewing logging when in jupyter notebooks: `import logging; logging.getLogger().setLevel(logging.DEBUG)`
- 30 Jan: Vim: `gqip` to format the current paragraph. `vip` selects the current paragraph
- 26 Feb: GNU [aspell](http://aspell.net) is useful for spell checking LaTeX files, as well as other plain text formats like markdown

## 2018

- 8 Apr: When using `newcommand` in LaTeX to define a shortcut for a phrase, `xspace` is very useful for ensuring proper spacing. E.g. `\usepackage{xspace} \newcommand{\fl}{Federated Learning\xspace}` makes sure that a space is inserted when a word follows (`\fl is useful`) but not when punctuation follows (`\fl,`).
- 28 Jun: Jupyter can [auto-reload modules](https://stackoverflow.com/questions/5364050/reloading-submodules-in-ipython) whenever they change:
```
%load_ext autoreload
%autoreload 2
```
- 29 Sep: Transitions in CSS are [not inherited](https://web.archive.org/web/20160305003043/https://www.bennadel.com/blog/2931-css3-transition-properties-are-not-inherited-in-angularjs.htm) by default
- 7 Oct: `r''` is not just for *regular* expressions, it's actually for *raw* strings. Every character other than the closing `'` is taken literally. This means backslashes do not need to be escaped, which is useful for regular expressions

## 2019

- 13 Jan: `\mbox` if you don't want LaTeX to break up a phrase
