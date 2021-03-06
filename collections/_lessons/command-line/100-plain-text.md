---
layout: lesson
target-tutorial: command-line
title: "Unit 1: Conversing in Plain Text"
authors: Dennis Yi Tenen
---

>  Bash/sh/zsh family is brilliant at intense interaction with humans. Aliases,
>  short built-in commands, one liner-oriented nature, keyboard ergonomics,
>  really concise file/process handling - all of this makes it _the
>  shell_.<sup>1</sup>

<sup>1. 
https://web.archive.org/web/20150623025431/https://news.ycombinator.com/item?id=6866085</sup>

> The craft of scripting is not hard to master, since scripts can be built in
> bite-sized sections and there is only a fairly small set of shell-specific
> operators and options [1] to learn. The syntax is simple---even austere---
> similar to that of invoking and chaining together utilities at the command
> line, and there are only a few "rules" governing their use. Most short
> scripts work right the first time, and debugging even the longer ones is
> straightforward.<sup>2</sup>

<sup>2. http://www.tldp.org/LDP/abs/html/why-shell.html</sup>

> One person who posted to the net said he had an "epiphany" from a shell
> script (which used four commands and a script that looked like line noise)
> which renamed all his `.pas` files so that they ended with `.p` instead. I
> reserve my religious ecstasy for something more than renaming files. And,
> indeed, that was my memory of Unix tools---you spend all your time learning
> to do complex and peculiar things that are, int he end, not really all that
> impressive.<sup>3</sup>

<sup>3. Gim Giles of the Los Alamos National Laboratory as quoited in
Garfinkel, Simson L., Donald Norman, and Dennis Ritchie. [The UNIX Hater's
Handbook: The Best of UNIX-Haters On-Line Mailing Reveals Why UNIX Must
Die!](http://www.csf.ac.at/fileadmin/user_upload/BioComp/training/unix_haters_handbook.pdf).
Edited by Daniel Weise, Simson Garfinkel, and Steven Strassmann. San Mateo, CA:
IDG Books Worldwide, 1994, 161.</sup>

## Resources

- [The Command Line Crash Course](http://cli.learncodethehardway.org/book/) by
  Zed Shaw
- [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/index.html) by Machtelt Garrels
- [Data Science at the Command Line](http://datascienceatthecommandline.com/)
  by Jeroen Janssens
- [The Bash Guide](http://guide.bash.academy/), [Bash Reference Sheet](http://mywiki.wooledge.org/BashSheet), and the old [BashGuide](http://mywiki.wooledge.org/BashGuide) by [Maarten Billemont](http://lhunath.com/)
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
  by jlevy
- [commandlinefu.com](http://www.commandlinefu.com)
- [Advanced Bash-Scripting Guide](http://www.tldp.org/LDP/abs/html/) by Mendel Cooper
- [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls)

## Follow Along

```
mkdir test/
cd test

echo "hello world" > hello.txt
cat hello.txt
wc -c hello.txt

# open Microsoft Word
# type hello world
# save file to your test folder as hello.docx
cat hello.docx
wc -c hello.docx

# What other information accounts for the disparity between hello.txt and hello.docx?
```

## Historical Interlude: Morse and Baudot


![Morse Code](https://beckchris.files.wordpress.com/2013/11/americanmorsechart.jpg)

---

![Baudot Tape](http://www.clivemaxfield.com/diycalculator/imgs/qkbd-fig3.gif)

---

![ASCII](https://raw.githubusercontent.com/dh-notes/dhnotes/master/images/ascii.jpg)
## Your Turn

- Find three different types of files online
- Download to your `test/` directory
- use `cat` to peak inside
