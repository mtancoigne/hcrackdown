# hcrackdown
Port of "The Hacker Crackdown" by Bruce Sterling (1994) to markdown

## What is the "Hacker Crackdown" ?
The Hacker Crackdown is a book written by Bruce Sterling in 1994. It's all about hacking in the beggining of the 90's.

The book is freeware (look at the LICENSE file or read the preface for more infos).

It's already available on some websites as [Project Gutemberg](http://www.gutenberg.org/ebooks/101), [Lib.ru](http://www.lib.ru/STERLINGB/crackdown.txt),... in digital format.

The port is based on the files found on lib.ru (text files, easy to reuse).

## Goals of this port
... So the project behind this port is to create something more complete, in markdown format for easy adaptations. By *more complete*, I mean :
  - Links to sources/articles, if found on the today's internet
  - Notes (with links to other mdown files)
  - Translations (for now, plaintext, but Gettext tools may be really better)

## How to help ?
Fork, commit, make pull requests.

The work will be organized as follow (feel free to discuss on the issues list for other organization):

    source/               Base files used
    <lang>/               Translation for the given language
      /preface.md         Preface
      /part1.md           Part one
      /partx.md           Part X...
      /notes/             Notes folder
        /intro/           Notes related to the intro
        /intro/noteX.md   Actual note for X
        /part1/
        /part1/noteY.md   Actual note for Y
        /...
    <otherlang>           ...
    credits.md            File to keep trace of people who helped


## Why ?
For fun, culture, hapinness.

### And why markdown ?
Because ...
  - it's easier to use than LaTeX :D
  - it still remains readable plaintext
  - it's easily portable to other formats.

You can find the bases of markdown on the [Daring Fireball's website](http://daringfireball.net/projects/markdown/syntax)

---

Thanks for your interest and make this thing evolve :D
