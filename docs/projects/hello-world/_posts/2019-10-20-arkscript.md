---
title: Hello World in Arkscript
layout: default
last-modified: 2019-10-22
featured-image: hello-world-in-python-featured-image.JPEG
tags: [arkscript, hello-world]
authors:
  - arjitg
---

Welcome to this originally first edition of the Hello World in Every Language
series where I plan to embark on a journey of coding language exploration. 
First up, how to implement Hello World in ArkScript.
Its really easy. Let's just get into it

## How to Implement the Solution

So first up we'll write the actual program and then explain the rules surrounding it. 
It is almost pythonic in terms of readability:

```arkscript
(print "Hello world")
```
Now, let's understand how it works, basically arkscript programs start with parentheses(now referred to as 'parens' throughout). 
Each of these parens enclose a bloc and this is the barebones of Arkscript programs.

A variable (immutable or not) declaration is a single bloc.
A function call is a single bloc.
A program is a single bloc composed of multiple blocs following each other, using each other.
Thus, to have multiple blocs in one, we use the bloc begin which can take any amount of blocs you want.
They will be executed one after another, in the same scope.[^1]

## How to Run Solution

For Linux users, first download the ark-linux64.zip and the lib.zip. More info about different OSs on the Superfola github page linked below.

Go to ArkScript/releases and download the latest one corresponding to your operating system. If you want to install it system-wide, see the wiki, otherwise just unzip the archive wherever you want, open a terminal and launch Ark --repl --lib ./lib (to tell it the lib isn't installed system-wide). It will start an ArkScript interpreter where you can type in the code given above.

---

#### References

[^1]: SuperFola, Arkscript. [Online]. Available: 
<https://github.com/SuperFola/Ark/wiki/Creating-your-first-program/>.  

[1]: https://github.com/SuperFola/Ark/wiki/Building-and-installing
